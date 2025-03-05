
## Datasets

2 datasets: *rvf10k* (Real vs Fake 10k) and *dfvr* (Deep Fake vs Real).

### Access the Datasets

[**rvf10k**](https://www.kaggle.com/datasets/sachchitkunichetty/rvf10k) 

[**dfvr**](https://www.kaggle.com/code/dima806/deepfake-vs-real-faces-detection-vit/input)

All models have 2 versions corresponding to the 2 datasets used. 

Note that the rvf10k dataset seems to be 'harder' than dfvr for humans: (INSERT LINK TO SURVEY RESULTS).



## SVM
To train and test the SVM models use the pipeline.py file as follows: 
```
  python pipeline.py <encoding> <dataset>
```
### Arguments


**encoding** 

specifies whether to use SIFT or LBP encoding. *Options: SIFT, LBP*

**dataset** 

specifies which dataset to use. *Options: rvf10k, dfvr*


## CNN

Train and test the CNN model from this [Google Collab Workbook](https://colab.research.google.com/drive/1QG-p-fIeqMuI2ITNRuwpgdMoL6HlzGPw?usp=sharing)
