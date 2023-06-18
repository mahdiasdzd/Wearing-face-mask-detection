# Wearing-face-mask-detection
The official code for ["Wearing face mask detection using deep learning through COVID-19 pandemic_"](https://arxiv.org/abs/2305.00068).
## Updates
## Citation
```
@article{Faculty of Mechanical Engineering, Tarbiat Modares University, Tehran, Iran,
  title={Wearing face mask detection using deep learning through COVID-19 pandemic},
  author={Javad Khoramdela
, Soheila Hatamib
, and Majid Sadedel},
  journal={https://arxiv.org/abs/2305.00068},
  year={2023}
}
```
## How to use
first download models and save them in same directory with IPYNB file as jupyter notebooks one of them is for YOLOv4 and the other is for Mobilnetv2 and the odel is same as nootbooks.

### Model weights
Google Drive Link:().

### Training and Testing
1) Download the face mask detection dataset from [here](https://www.kaggle.com/andrewmvd/face-mask-detection (2020)).
2) 2) Run the following code to install the Requirements.

    `pip install -r requirements.txt`

3) Run the below code to train the Wearing-face-mask-detection on the face mask detection dataset.
    SSD.ipynb
    YOLOv4.ipynb
4) Test trained model with this dataset in in IPYNB too.

## Results
Performance comparision on face-mask-detection dataset.
## YOLOv4 Result
![](https://github.com/mahdiasdzd/Wearing-face-mask-detection/blob/main/yv4.jpg)


## MobilnetV2
![](https://github.com/mahdiasdzd/Wearing-face-mask-detection/blob/main/mobilnet.png)


## Final Result
![](SSD Result](https://github.com/mahdiasdzd/Wearing-face-mask-detection/blob/main/mAP.png)
