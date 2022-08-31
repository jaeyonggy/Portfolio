## Data Science Portfolio

[GitHub](https://github.com/jaeyonggy)  
[LinkedIn](https://www.linkedin.com/in/jaeyonglee5)  



## About Me

<p align="center">
  <img width="171" alt="ss" src="https://user-images.githubusercontent.com/63530964/153692586-913f1ee5-65cc-4992-83bb-fc8d672a251a.png">
</p>
<p align="center">
  Jaeyong Lee(이재용) / Email: i.am.jaeyong.lee@gmail.com  
</p>
<br/>


I am a statistician interested in Bayesian Statistics and AI.  

I received a Bachelor's degree in Applied Statistics and a Bachelor's degree in Software Humanities at Chung-Ang University on February, 2022.  
I'm currently pursuing a Master's degree in Statistics at Chung-Ang University with full scholarship from Chung-Ang University GRS(Graduate Research Scholarship).  

I was a member of Chung-Ang University GAS(Global Ambassador Scholarship - 중앙대학교 국제처 학생대사) from July 2020 to June 2021.  
I was a member of CUAI(Chung-Ang University Artificial Intelligence - 중앙대학교 인공지능 학회) from March 2021 to February 2022.  

I am proficient in Python and R.  
<br/>


Feel free to contact me via email.  

This page archives all the projects I have done so far.  

<br/>



## Contents

• Personal Projects  
• CUAI(Chung-Ang Univ. Artifical Intelligence) - 중앙대학교 인공지능 학회  
• Studies  

<br/>



## Personal Projects

Projects I have done out of my own interest or for participations in competitions.


#### • Image classification and Grad-CAM of infected leaf images

[Implementation of image classification in PyTorch](https://github.com/jaeyonggy/CVproject/tree/main/PT)  
[Implementation of Grad-CAM in TensorFlow](https://github.com/jaeyonggy/CVproject/tree/main/TF)  
A project done while participating in [Image classification challenge](https://zindi.africa/competitions/makerere-fall-armyworm-crop-challenge) hosted by Zindi.africa. The classification itself was not challenging so Grad-CAM technique was used to obtain heatmaps of each image in addition. I compared how the two models (EfficientNet-B0 and ResNet-50) viewed the images and where they focused on while classifying the images. I wanted to see on which part of image the models focused on when they misclassified it and if there was any difference between the two models on which part of images they focused on.  
Check out [GitHub repository](https://github.com/jaeyonggy/CVproject) for more information.  
<br/>


#### • Time series analysis on fish production of Busan

[R Notebook](https://rawcdn.githack.com/jaeyonggy/Studies/d463577b07f001091e6eb970e60c7a2bd4fc9d99/HW1.html)  
I performed a time series analysis with the fish production time series data of Busan.  
Check out [GitHub repository](https://github.com/jaeyonggy/Studies) for more information.  
<br/>


#### • r/depression Text Anaylsis

[Jupyter Notebook](https://nbviewer.org/github/jaeyonggy/Project-RedditDepressionTextAnalysis/blob/main/depression_text_analysis.ipynb)  
I performed a text analysis with posts from a subreddit called r/depression.  
Check out [GitHub repository](https://github.com/jaeyonggy/Project-RedditDepressionTextAnalysis) for more information.  
<br/>


#### • bloods.ai Blood Spectroscopy Classification Challenge

[Jupyter Notebook](https://nbviewer.org/github/jaeyonggy/Zindi_Classification/blob/main/pca_rf_xgb_cv_final.ipynb)  
I participated in a competition called Blood Spectroscopy Classification Challenge hosted by zindi.africa. It was a mutliclass classification problem and preventing overfitting was of the utmost importance.  
Check out [GitHub repository](https://github.com/jaeyonggy/Zindi_Classification) for more information.  
<br/>

<br/>



## CUAI(Chung-Ang Univ. Artifical Intelligence) - 중앙대학교 인공지능 학회  

The projects I have done as a member of CUAI(Chung-Ang Univ. Artifical Intelligence).


#### • Text generation for academic papers's introduction - 논문 서론 작성 AI

[Paper](https://github.com/CUAI-CAU/2022-CUAI-Summer-Conference/blob/main/paper/2022_CUAI_Summer_Conference_Shortpaper_NLP_T12.pdf)  
[Presentation](https://www.youtube.com/watch?v=oGnbYiWPBSE)  
We trained a text generation model, specifically KoGPT2, on a series of papers' introduction part. By giving a sentence as an input, the model generated several sentences which would form a full paragraph based on the input sentence. We also paraphrased the generated sentences to avoid any plagiarism. We expect the users to easily write a full introduction by coming up with only a few sentences with this model.  
Check out [GitHub repository](https://github.com/jaeyonggy/2022_Summer_NLP_T12) for more information.  
<br/>


#### • Album Recommendation System Based On Image Similarity - 이미지 유사도 기반 앨범 추천 시스템

[Paper](https://github.com/CUAI-CAU/2021-CUAI-Winter-Conference/blob/main/paper/J.pdf)  
[Presentation](https://www.youtube.com/watch?v=ff_UeduK5lk)  
Our team has managed to implement a music recommendation system based on image similarity. The system gets a user's preferred album's album cover and the album's emotions(one of angry, happy, relaxed and sad) as inputs. By YOLO and k-means models, we output 5 albums that is pre-classified as the same emotion as the input's whose album covers are the most similar to the input's album cover.  
Check out [GitHub repository](https://github.com/CUAI-CAU/Recommend-By-Album-Covers) for more information.  
<br/>


#### • Predicting change in stock price using news' headlines - 뉴스 기사 제목을 활용한 주가 변동여부 예측

[Prediction model - Jupyter Notebook](https://nbviewer.org/github/jaeyonggy/CUAI-Headlines_TextAnalysis_For_StockPrice_Prediction/blob/main/tfidf_title_to_pred.ipynb)  
[Scraping headlines - Jupyter Notebook](https://nbviewer.org/github/jaeyonggy/CUAI-Headlines_TextAnalysis_For_StockPrice_Prediction/blob/main/Web%20Scraping%20for%20headlines/data_title.ipynb)  
[Scraping stock price data - Jupyter Notebook](https://nbviewer.org/github/jaeyonggy/CUAI-Headlines_TextAnalysis_For_StockPrice_Prediction/blob/main/Web%20Scraping%20for%20headlines/data_stock.ipynb)  
[Merging data - Jupyter Notebook](https://nbviewer.org/github/jaeyonggy/CUAI-Headlines_TextAnalysis_For_StockPrice_Prediction/blob/main/Web%20Scraping%20for%20headlines/data_merge.ipynb)   
Our team wanted to predict whether or not a stock's price increases based on an article's headline. We utilized webscraping to get various headlines of some specific stocks and their stock price at the end of a market the day after the headline was written. We implemented a classification model to predict and assessed its performance.  
Check out [GitHub repository](https://github.com/jaeyonggy/CUAI-Headlines_TextAnalysis_For_StockPrice_Prediction) for more information.  
<br/>

<br/>



## Studies

The R Notebooks and Jupyter notebooks I have written while studying for some Statistics classes and any other topic of interests.


#### • Bayesian Statistics

[Bayesian Statistics - pt.1](https://rawcdn.githack.com/jaeyonggy/Studies/5678ff76fc1a549193c28ab9ed5b3df4d09e3291/Bayesian/Bayesian.nb.html)  
[Bayesian Statistics - pt.2](https://rawcdn.githack.com/jaeyonggy/Studies/5678ff76fc1a549193c28ab9ed5b3df4d09e3291/Bayesian/Bayesian_pt2.nb.html)  
[Bayesian Statistics Assignment](https://rawcdn.githack.com/jaeyonggy/Studies/5678ff76fc1a549193c28ab9ed5b3df4d09e3291/Bayesian/Bayes_HW.nb.html)  
A collection of R Notebooks that includes all the examples and codes that were used during Bayesian Statistics class.  
Check out [GitHub repository](https://github.com/jaeyonggy/Studies) for more information.  
<br/>


#### • Bayesian Computation with R

[Ch.2 Introduction to Bayesian thinking](https://rawcdn.githack.com/jaeyonggy/BCR/6524fc38e944398d192280d936243956576de8e5/BCR.nb.html)  
[Ch.3 Single-parameter models](https://rawcdn.githack.com/jaeyonggy/BCR/5a30e60b1841d77ff576bb4a6459e3747436d6df/BCR_ch3.nb.html)  
[Ch.4 Multiparameter models](https://rawcdn.githack.com/jaeyonggy/BCR/49f19692ee94767109df53c41a5790c02aec7ad8/BCR_ch4.nb.html)  
[Ch.5 Introduction to Bayesian computation](https://rawcdn.githack.com/jaeyonggy/BCR/828227475b4ef93c0e30412510fd1e13a877b7dd/BCR_ch5.nb.html)  
[Ch.6 Markov Chain Monte Carlo methods](https://rawcdn.githack.com/jaeyonggy/BCR/828227475b4ef93c0e30412510fd1e13a877b7dd/BCR_ch6.nb.html)  
[Ch.7 Hierarchical modeling](https://rawcdn.githack.com/jaeyonggy/BCR/f739b145c8ef73bc78ca2e12cd606c7b3919595f/BCR_ch7.nb.html)  
A collection of R Notebooks that I've written while studying 'Bayesian Computation with R' by Jim Albert.  
Check out [GitHub repository](https://github.com/jaeyonggy/BCR) for more information.  
<br/>


#### • Multivariate Statistical Anaylsis

[1장: 다변량 데이터 / 2장: 기초행렬대수 / 3장: 다변량 확률표본 / 4장: 다변량 정규분포](https://rawcdn.githack.com/jaeyonggy/Studies/ecc29feb7fdf3df2dc102404d17d829d22b64fd6/MVA/MVA.nb.html)  
[5장: 모집단 평균벡터에 관한 추론](https://rawcdn.githack.com/jaeyonggy/Studies/ecc29feb7fdf3df2dc102404d17d829d22b64fd6/MVA/MVA2.nb.html)  
[6장: 다변량 분산분석](https://rawcdn.githack.com/jaeyonggy/Studies/ecc29feb7fdf3df2dc102404d17d829d22b64fd6/MVA/MVA3.nb.html)  
[7장: 주성분분석](https://rawcdn.githack.com/jaeyonggy/Studies/ecc29feb7fdf3df2dc102404d17d829d22b64fd6/MVA/MVA4.nb.html)  
[8장: 인자분석 / 9장: 정준상관분석](https://rawcdn.githack.com/jaeyonggy/Studies/ecc29feb7fdf3df2dc102404d17d829d22b64fd6/MVA/MVA5.nb.html)  
[10장: 판별분석과 분류](https://rawcdn.githack.com/jaeyonggy/Studies/ecc29feb7fdf3df2dc102404d17d829d22b64fd6/MVA/MVA6.nb.html)  
[11장: 군집분석 / 12장: 다차원 척도법](https://rawcdn.githack.com/jaeyonggy/Studies/ecc29feb7fdf3df2dc102404d17d829d22b64fd6/MVA/MVA7.nb.html)  
[13장: 확인적 인자분석 및 구조방정식 모형](https://rawcdn.githack.com/jaeyonggy/Studies/ecc29feb7fdf3df2dc102404d17d829d22b64fd6/MVA/MVA8.nb.html)  
[14장: 반복측정데이터 분석](https://rawcdn.githack.com/jaeyonggy/Studies/ecc29feb7fdf3df2dc102404d17d829d22b64fd6/MVA/MVA9.nb.html)  
A collection of R Notebooks that include all the examples and codes that were used during Multivariate Statistical Analysis class.  
Check out [GitHub repository](https://github.com/jaeyonggy/Studies) for more information.  
<br/>


#### • R in Action

[Ch.7 Basic statistics](https://rawcdn.githack.com/jaeyonggy/Studies/ddedb95f4675d0d030acdc2231389bd60843dc79/RInAction/stats.nb.html)  
[Ch.8 Regression](https://rawcdn.githack.com/jaeyonggy/Studies/3d2e1d6998c4a42c6207a5b75daea00eb64cf71d/RInAction/Regression.nb.html)  
[Ch.9 Analysis of variance](https://rawcdn.githack.com/jaeyonggy/Studies/3d2e1d6998c4a42c6207a5b75daea00eb64cf71d/RInAction/anova.nb.html)  
[Ch.10 Power analysis](https://rawcdn.githack.com/jaeyonggy/Studies/3d2e1d6998c4a42c6207a5b75daea00eb64cf71d/RInAction/power_analysis.nb.html)  
[Ch.11 Intermediate graphs](https://rawcdn.githack.com/jaeyonggy/Studies/a7df1d6b836a3d7bf7b4af13d064beb4f7974586/RInAction/inter-graphs.nb.html)  
[Ch.12 Resampling statistics and bootstrapping](https://rawcdn.githack.com/jaeyonggy/Studies/7b60c865f9500b09ae250bac5f496b4510515007/RInAction/resampling.nb.html)  
[Ch.13 Generalized linear models](https://rawcdn.githack.com/jaeyonggy/Studies/75f88cddc0d010ef238280941699e29168eaf64a/RInAction/glm.nb.html)  
[Ch.14 Principal components and factor analysis](https://rawcdn.githack.com/jaeyonggy/Studies/20b8abd84d689c7ae989979b18bcc5f04cdbe05a/RInAction/pcfa.nb.html)  
[Ch.15 Advanced methods for missing data](https://rawcdn.githack.com/jaeyonggy/Studies/20b8abd84d689c7ae989979b18bcc5f04cdbe05a/RInAction/missingdata.nb.html)  
A collection of R Notebooks that I've written while studying 'R in Action' by Rob Kabacoff.  
Check out [GitHub repository](https://github.com/jaeyonggy/Studies) for more information.  
<br/>


#### • Hidden Markov models for time series

[Ch.1 Preliminaries: mixtures and Markov chains](https://rawcdn.githack.com/jaeyonggy/HMM/f8d41722020e60950eb7982601bdd7fcf7b385c6/HMM.nb.html)  
[Ch.2 Hidden Markov models: definition and properties](https://rawcdn.githack.com/jaeyonggy/HMM/f8d41722020e60950eb7982601bdd7fcf7b385c6/HMM_ch2.nb.html)  
[HMM paper](https://rawcdn.githack.com/jaeyonggy/HMM/6978acd327ef2328295f64254275d827703aeb4b/HMM_paper.nb.html)  
A collection of R Notebooks that I've written while studying 'Hidden Markov models for time series an introduction using R' by Zucchini et al.  
Check out [GitHub repository](https://github.com/jaeyonggy/HMM) for more information.  
<br/>


#### • Basic R Statistics

[Hypothesis Testing](https://rawcdn.githack.com/jaeyonggy/Studies/9eb7428ee5aeefc89c6550100684c975b047a1e2/RStatBasic/HypothesisTesting.nb.html)  
[Categorical Data Analysis](https://rawcdn.githack.com/jaeyonggy/Studies/9eb7428ee5aeefc89c6550100684c975b047a1e2/RStatBasic/categorical.nb.html)  
[Simple Linear Regression](https://rawcdn.githack.com/jaeyonggy/Studies/9eb7428ee5aeefc89c6550100684c975b047a1e2/RStatBasic/SimpleLinearRegression.nb.html)  
A collection of R Notebooks that I've written while studying '제대로 알고 쓰는 R 통계분석' by 이윤환.  
Check out [GitHub repository](https://github.com/jaeyonggy/Studies) for more information.  
<br/>

<br/>


