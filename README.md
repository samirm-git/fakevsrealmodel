
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


## Test Results

### SVM using LBP Encoding

| Dataset | Accuracy | Precision | Recall | F1 Score |
|---------|----------|-----------|--------|----------|
| rvf10k  | 0.6425   | 0.6276    | 0.7010 | 0.6623   |
| hfd     | 0.9642   | 0.9658    | 0.9625 | 0.9641   |
| dfvr    | 0.6225   | 0.6012    | 0.7280 | 0.6585   |

### SVM using SIFT Encoding

### CNN


## GradCam Results

## SIFT Keypoint results
