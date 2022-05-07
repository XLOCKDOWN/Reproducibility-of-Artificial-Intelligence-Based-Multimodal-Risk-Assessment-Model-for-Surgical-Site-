# Reproducibility of Artificial Intelligence–Based Multimodal Risk Assessment Model for Surgical Site Infection (AMRAMS): Development and Validation Study

ssogi2@illinois.edu<br>
Group ID: 171<br>
Paper ID: 176<br>
Difficulty: Easy

## Dependencies
```
pip install -r requirements.txt
```

## Data
* Download for Chinese: https://linguatools.org/tools/corpora/wikipedia-monolingual-corpora/
* Download medinform_v8i6e18186_app2.xlsx from Multimedia Appendix 2 from cited [paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7325005/?report=classic)

All other data will be downloaded by the Notebook, during runtime.

## Notebook
A Jupyter notebook with a Python 3.7.6 kernel
was used to implement the models proposed in the
paper. Pytorch (Paszke et al., 2019), Pandas (McK-
inney et al., 2010), Numpy (Harris et al., 2020) and
Sklearn (Pedregosa et al., 2011) formed the back-
bone of the preprocessing and machine learning
frameworks for the structured features. Prepro-
cessing of the Wikipedia corpus was performed by
Gensim (Rehurek and Sojka, 2011) and the Wiki
python libraries. Fasttext (Bojanowski et al., 2016)
and Jieba (fxsjy, 2020) were used to perform word
encoding, after being trained on the Wikipedia cor-
pus(s). Visualization were created by Plotly (Inc.,
2015) and Seaborn (Waskom, 2021).

The notebook will perform preprocessing, training, AUROC calculations, etc


## Results
See previous outputs of the Notebook