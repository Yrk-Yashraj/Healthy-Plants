# Plant 🌱 Disease 🐛 Detector 🔎
 
## Machine Learning Model

Multi-Class Image classifier Built on PyTorch framework using CNN architecture. Currently Project Detects 17 States of disease in 4 plants namely Cherry, Pepper, Potato and tomato.

* Framework : PyTorch
* Architecture : Convolutional Neural Networks

#### How to train

Upload the **[Python notebook](https://colab.research.google.com/drive/1oabgjQjUqi3u5VNDOG7gVl1Y2vvxUohD?usp=sharing)** to Google Colab and run each cell for training the model. I have included a demo dataset to configure quickly. 
You can also use the original dataset at **[Kaggle Dataset](https://www.kaggle.com/vipoooool/new-plant-diseases-dataset)**

#### How It Works

The input image dataset is converted to tensor and is passed through a CNN model, returning an output value corresponding to the plant disease. 
Input image tensor is passed through four convolutional layers and then flattened and inputted to fully connected layers.
