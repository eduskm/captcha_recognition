# CAPTCHA Recognition with CNN

This project was made as a final homework project for my Artificial Intelligence class that I took last semester. This model uses a CNN (Convolutional Neural Network) that I implemented using PyTorch.

# How it works

It first preprocesses captcha images by converting them into tensors and encoding labels. The CNN then extracts features from the images using convolutional and pooling layers. During training, the model adjusts its weights by minimizing prediction errors using backpropagation. After it's trained, random images from the samples are selected and it can make pretty accurate predictions, surely, only if the number of epochs is accordingly adjusted. Okay now, let's get it running!!

# Dataset

https://www.kaggle.com/datasets/fournierp/captcha-version-2-images/data<br/>

# Prerequisites

```pip install torch torchvision numpy scikit-learn matplotlib pillow kagglehub```

# How to run

```jupyter notebook captcha_recognition.ipynb```<br/>
Note: when running, the code automatically downloads the dataset from above using ```kagglehub``` <br/>
To disable just remove these lines from the code: <br/>
```import kagglehub``` <br/> ```PATH = kagglehub.dataset_download("fournierp/captcha-version-2-images") + '/' + PATH # if u DONT have samples already downloded```

# Results

![image](https://github.com/user-attachments/assets/3a736125-a00c-4ceb-abdc-707b8425a60b)
![image](https://github.com/user-attachments/assets/ac863f6b-9bbc-4174-902c-c2edf96b1624)
![image](https://github.com/user-attachments/assets/7764732b-060c-4ed5-be56-a788020ca547)
![image](https://github.com/user-attachments/assets/4b24a706-6dfc-474a-aff8-ab78e97cdcd2)
![image](https://github.com/user-attachments/assets/597861d4-8953-4e30-9443-5bde3d716438)



