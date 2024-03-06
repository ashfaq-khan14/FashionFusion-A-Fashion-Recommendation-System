<h2 align="left">Hi 👋! Mohd Ashfaq here, a Data Scientist passionate about transforming data into impactful solutions. I've pioneered Gesture Recognition for seamless human-computer interaction and crafted Recommendation Systems for social media platforms. Committed to building products that contribute to societal welfare. Let's innovate with data! 





</h2>

###


<img align="right" height="150" src="https://i.imgflip.com/65efzo.gif"  />

###

<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="30" alt="javascript logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" height="30" alt="typescript logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="30" alt="react logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="30" alt="html5 logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="30" alt="css3 logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="30" alt="python logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg" height="30" alt="csharp logo"  />
</div>

###

<div align="left">
  <a href="[Your YouTube Link]">
    <img src="https://img.shields.io/static/v1?message=Youtube&logo=youtube&label=&color=FF0000&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="youtube logo"  />
  </a>
  <a href="[Your Instagram Link]">
    <img src="https://img.shields.io/static/v1?message=Instagram&logo=instagram&label=&color=E4405F&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="instagram logo"  />
  </a>
  <a href="[Your Twitch Link]">
    <img src="https://img.shields.io/static/v1?message=Twitch&logo=twitch&label=&color=9146FF&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="twitch logo"  />
  </a>
  <a href="[Your Discord Link]">
    <img src="https://img.shields.io/static/v1?message=Discord&logo=discord&label=&color=7289DA&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="discord logo"  />
  </a>
  <a href="[Your Gmail Link]">
    <img src="https://img.shields.io/static/v1?message=Gmail&logo=gmail&label=&color=D14836&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="gmail logo"  />
  </a>
  <a href="[Your LinkedIn Link]">
    <img src="https://img.shields.io/static/v1?message=LinkedIn&logo=linkedin&label=&color=0077B5&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="linkedin logo"  />
  </a>
</div>

###



<br clear="both">


###


#

# fashion-recommender-system
# Fashion Recommendation

In this project, I created an end-to-end solution for large-scale image classification and visual recommendation on fashion images. More specifically, my model can learn the important regions in an image and generate diverse recommendations based on such semantic similarity.  

First, I built a clothing image classification model using a ResNet-based model. The feature layer of this model can capture fine-grained semantic clothing features like fabrics, styles and patterns of the clothes. Then, using such features, the model can recommend similar clothes to the input images using nearest neighbor search.

An accompanied blog post via FloydHub can be found at this link: [Recommending Similar Fashion Images with Deep Learning]([https://blog.floydhub.com/similar-fashion-images/](https://medium.com/@ashfaqkhan1419600/fashion-product-recommendation-system-using-resnet-50-3b8d715f893d))

## Dataset
[DeepFashion](http://mmlab.ie.cuhk.edu.hk/projects/DeepFashion.html) is a large-scale clothes database that is quite popular in the research community. It contains over 800,000 diverse fashion images ranging from well-posed shop images to unconstrained consumer photos. It is annotated with rich information of clothing items. It also contains over 300,000 cross-pose/cross-domain image pairs.

More specifically, I used the images in the [DeepFashion Attribute Prediction](http://mmlab.ie.cuhk.edu.hk/projects/DeepFashion/AttributePrediction.html) subset. It contains 289,222 number of clothes images, 50 number of clothing categories, and 1,000 number of clothing attributes. Each image is annotated by bounding box and clothing type.

![AttributePrediction](deep-fashion-attribute-prediction.jpg)

## Code
1. [preprocessing.py](https://github.com/khanhnamle1994/fashion-recommendation/blob/master/code/preprocessing.py): This code is used to pre-process the dataset.
2. [hyper_parameters.py](https://github.com/khanhnamle1994/fashion-recommendation/blob/master/code/hyper_parameters.py): This code is used to define all hyper-parameters regarding training.
3. [fashion_input.py](https://github.com/khanhnamle1994/fashion-recommendation/blob/master/code/fashion_input.py): This code is used to pre-process the image further during training.
4. [simple_resnet.py](https://github.com/khanhnamle1994/fashion-recommendation/blob/master/code/simple_resnet.py): This code is used to define ResNet architecture.
5. [train_n_test.py](https://github.com/khanhnamle1994/fashion-recommendation/blob/master/code/train_n_test.py): This code is used as the main training file.

## Sample Results

1 - Romper Category

![Romper](Results/Romper-Examples.png)

2 - Jacket Category

![Jacket](Results/Jacket-Examples.png)

3 - Blouse Shirt Category

![BlouseShirt](Results/BlouseShirt-Examples.png)

## Requirements
- [TensorFlow](https://www.tensorflow.org/) latest version
- [pandas](https://pandas.pydata.org/) latest version
- [numpy](http://www.numpy.org/) latest version

## Run on FloydHub
[![Run on FloydHub](https://static.floydhub.com/button/button-small.svg)](https://floydhub.com/run)

