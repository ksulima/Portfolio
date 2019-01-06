# Data Science Portfolio
 
This repository gathers side projects I worked on or currently working on. The goal of projects is to use my data science/machine learning skills to explore interesting things. For each project I write short summary. I mainly use Python in Jupyter Notebook. To see full analysis and code click on the projects headline.

Enjoy reading and if you have some questions, you can contact with me through my [Linkedin profile.](https://www.linkedin.com/in/krzysztof-sulima/)

## Projects:

### [Neural networks with Entity Embeddings applied to structured, time series data (in progress)](https://github.com/ksulima/Entity_Embedding_Structured_Data)

In this project my goal is to use neural networks to structured, time series data. I use Keras to implement method "Entity Embeddings" originally described by Cheng Guo and Felix Berkhahn in a [paper.](https://arxiv.org/abs/1604.06737)

**Motivation**

Nowadays most of the research in deep learning field is focused on unstructed data, like computer vision, natural language processing, where neaural networks bring outstanding results comparing to others methods. Exploring deep learning to structured data is not in a academic spotlight, whereas lots of business problems and decisions are related to structured data. My plan is to apply neural networks to practical real-world problem.

**Dataset description**

I use a dataset from Kaggle competiton. You can download all provided data together with external datasets put by participants from this [link.](http://files.fast.ai/part2/lesson14/rossmann.tgz)
Since data cleaning and feature engineering is not my main goal in this project, I based this part of implementation from 'Practical Deep Learning for Coders' and fast.ai library by Jeremy Howard. You can find details [here](https://www.fast.ai/2018/04/29/categorical-embeddings/)



### [Age Detection with Convolution Neaural Network on small dataset size](https://github.com/ksulima/Age_Detection_Convolutional_NN)
* Image Preprocessing using Keras ImageDataGenerator.
* Reference CNN model from the scratch.
* Using data augmentation to mitigate overfitting.
* Using some publicly available CNN architectures pre-trained on ImageNet dataset
* **Keywords** (Keras, ConvNet, VGG16, image classification, python)
<img src="https://github.com/ksulima/Age_Detection_Convolutional_NN/blob/master/images/dataset_intro.PNG" width="550" height="250">

<img src="https://github.com/ksulima/Age_Detection_Convolutional_NN/blob/master/images/vgg16.png" width="550" height="250">

---

### [Automated Feature Engineering and parallel computing with Dask](https://github.com/ksulima/Home_Credit)

* use Deep Feature Synthesis to generate set of features in a automated way. 
* parallelize computation with Dask.
* hyperparameter tunning of xgboost.
* **Keywords** (Featuretools, Python, Dask, AWS)
<img src="https://github.com/ksulima/Home_Credit/blob/master/images/dask_board.PNG" width="500">
<img src="https://github.com/ksulima/Home_Credit/blob/master/images/auc.png" width="500" height="350">


---
### [Pipelines](https://github.com/ksulima/Pipelines)

* my tutorial to explain concept of pipelines with practical examples in python and scikit-learn library.
* **Keywords** (pipeline, scikit-learn, python, custom transformers)
<img src="https://github.com/ksulima/Pipelines/blob/master/pipeline.jpg" width="500">


---
### [Time Series analysis](https://github.com/ksulima/Time_Series)
* Check some general assumption about data.
* Use Dickey-Fuller Test to test statonaryand forecast the time series using ARIMA.
* Introduce Prophet library.
* **Keywords** (time series, ARIMA, Prophet, python)
<img src="https://github.com/ksulima/Time_Series/blob/master/images/plot.png" width="550" height="300">


---

