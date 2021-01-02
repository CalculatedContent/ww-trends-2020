# Repo to accompany Paper

"Predicting trends in the quality of state-of-the-art neural networks without access to training or testing data"

## Requirements to reproduce results: 

 Python 3.7.6
 weightwatcher 0.2.7 (only this version)

 Conda environment in requirements.txt

## Includes

 Jupyter Notebooks for reproducing most Tables and all Figures

 All results can be generated using pretrained models available in the [torchvision](https://pytorch.org/docs/stable/torchvision/index.html) pyTorch models
 (except ResNet-1K, which requies the Cv Sandbox)

### data

 Contains data from weightwatcher runs using Google Colab
 All Tables and Figures are generated directly from this raw data

### distiller/

 Jupyter Notebooks for reproducing Figure 4 and accompanying text
 (note: user must install Intell [distiller](https://github.com/NervanaSystems/distiller) to run these)

### submission

 original Latex files

### img/

 images, generated by Jupyter Notebooks
 
 ### pdfs/
 
 current PDF of the archive paper

### Comments on Reproducibility

 The original weightwatcher calculations were done in the Summer of 2019, and then repeated in Jan 2020
 Since that time, the weightwatcher code has been updated, and the OSMR models have have changed

 This paper reports details results from the Jan 2020 data, stored in data/omsr

 The calculations can be repeated using weightwatcher (with ww2x=True set) however, there may be minor differences 
in the numerical results. 

#### Deprecated: ww-colab/


 Data from older submission:
 Google Colab Notebooks for reproducing results in sections 6

 Notebooks can be run in parallel on the users Google Cloub
 They Will download pretrained models from the [CV Sandbox](https://github.com/osmr/imgclsmob) 

