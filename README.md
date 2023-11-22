<div align="center">
  <div id="user-content-toc">
    <ul>
      <summary><h1 style="display: inline-block;"> Content-based Image Indexing And Retrieval System (CBIR)</h1></summary>
    </ul>
  </div>
  
  <p>Computer vision project</p>
    🔍
    🛸
    🔍
</div>
<br>
<div align="center">
      <a href="https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white"><img src="https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white"/></a>
      <img src="https://img.shields.io/github/stars/hamagistral/DataEngineers-Glassdoor?color=blue&style=social"/>
</div>

## 📝 Table of Contents

1. [ Project Overview ](#introduction)
2. [ Project Architecture ](#arch)
3. [ Installation ](#installation)
4. [ Contact ](#contact)
<hr>

### 🕵️ Search engine Page
![Flask1](https://github.com/BENAMAR-Zaid/content_based_image_retrieval_gaborfilter/assets/105943885/7a4ee630-f695-4ef4-850e-f2061f2122f6)
![Falsk2](https://github.com/BENAMAR-Zaid/content_based_image_retrieval_gaborfilter/assets/105943885/86999f15-3e62-40c3-9737-922b50077e2a)




<a name="introduction"></a>
## 🔬 Project Overview :

### 🎯 Goal :

Our aim in this project is to develop a Web application that implements the basic functionalities of a content-based image indexing and retrieval system, using Texture decriptors such as Gabor filters and Tamura features with relevance feedback (Re-weighting Type-2).

### 🧭 Steps :

In our way to develope and build the content-based image retrieval system, we've passed with the following steps : 
#### 1- We choosed the gabor filters as the texture feature extraction method to  represent the semantic content of an image.
<div align="center">
  <a href="">
    <img src="https://github.com/BENAMAR-Zaid/content_based_image_retrieval_gaborfilter/assets/105943885/ff332fb7-2e5e-4782-a254-45eadbe94d8e" alt="Banner" width="720">
  </a>
</div>

#### 2- We choosed the Tamura's methodology, which is an approaches texture extraction and analysis by designing features that correspond to human visual perception.
#### 3- We choosed the reweighting-Type 2 as feature reweighting algorithm. The aim of updating weights is to focus on the most discriminating parameters. In practice, the idea is to perform a dynamic selection of features, based on user feedback. The feature reweighting algorithm used in this work is similar to that proposed in Mattia and Francesco (2010) and Wu and Zhang (2002) and is based on a set of statistical features.
#### 4- We choosed the chi squared distance metric as a similarity metric that quantifies the similarity between an image in the database and the requested image.
#### 5- The final step is to perform an actual search. A user will submit a query image to our system (from a download form or via a mobile application) and then we need to (1) extract the features from this query image and then (2) apply the similarity function to compare the query features with the features already indexed.

#### The search is carried out using an image database with the following characteristics:
    a) The observed image data amounts to 7200 items.
    b) Each image is in png format.
    c) The resolution of the images searched and queried is 128x128 pixels.

<a name="arch"></a>
## 📝 Project Architecture

#### The processes are :

    a) Capture the input image.
    b) Texture extraction from the input image using Tamura features.
    c) Texture extraction from the input image using Gabor filters.
    d) Match image to database.
    e) Display comparison results.
    
<div align="center">
  <a href="">
    <img src="https://github.com/BENAMAR-Zaid/content_based_image_retrieval_gaborfilter/assets/105943885/1919bff6-5883-4f1b-b596-ab9508d92a16" alt="Banner" width="720">
  </a>
</div>

#### First, a user must submit a query image to our image search engine. We then take this image and extract features from it. These "query features" are then compared with the features of the images we have already indexed in our dataset. Finally, the results are sorted by relevance and presented to the user.

<div align="center">
  <a href="">
    <img src="https://github.com/BENAMAR-Zaid/content_based_image_retrieval_gaborfilter/assets/105943885/3964df60-8c05-4680-aa89-ccb364e08560" alt="Banner" width="720">
  </a>
</div>

### 🛠️ Technologies Used

![Jupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![OpenCV](https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=%white)
![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)




<a name="installation"></a>
## 🖥️ Installation : 
Clone the repository:

```
git clone https://github.com/BENAMAR-Zaid/content_based_image_retrieval_gaborfilter.git
```

### - Run Flask Project

1. Activate the virtual environnement :

```
   Scripts\activate
```

2. Install the required packages (not necessary because all the packages are installed within the virtual environnement):

```
pip install -r requirements.txt
```

3. Change directory to src:

```
cd src
```

4. Launch project : 

```
python server.py
```

<a name="contact"></a>
## 📨 Contact Me

[LinkedIn](https://www.linkedin.com/in/zaid-benamar/) •
[Gmail](zaid.benmr@gmail.com)
