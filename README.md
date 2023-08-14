## Data Science Portfolio

[GitHub](https://github.com/jaeyonggy)  
[LinkedIn](https://www.linkedin.com/in/jaeyonglee5)  



## About Me

<p align="center">
  <img width="171" alt="ss" src="https://user-images.githubusercontent.com/63530964/153692586-913f1ee5-65cc-4992-83bb-fc8d672a251a.png">
</p>
<p align="center">
  Jaeyong Lee (이재용) / Email: jaeyonggy@cau.ac.kr  
</p>
<br/>


I am a **data scientist** with many research experience in **Bayesian statistics** and **AI**.  

I received a Bachelor's degree in Applied Statistics and a Bachelor's degree in Software Humanities at Chung-Ang University on February, 2022.  
I'm currently pursuing a Master's degree in Statistics at Chung-Ang University with full scholarship from Chung-Ang University GRS (Graduate Research Scholarship).  

I was a member of Chung-Ang University GAS (Global Ambassador Scholarship - 중앙대학교 국제처 학생대사) from July 2020 to June 2021.  
I was a member of CUAI (Chung-Ang University Artificial Intelligence - 중앙대학교 인공지능 학회) from March 2021 to August 2022.  

I am proficient in Python, R, MySQL, and Tableau.  
<br/>


Feel free to contact me via email.  

This page archives all the projects I have done so far.  

<br/>



## Contents

• [Projects](#projects)  
• [CUAI (Chung-Ang Univ. Artifical Intelligence - 중앙대학교 인공지능 학회)](#cuai)  
• [Studies](#studies)  

<br/>



<a name="projects"></a>
## Projects

Projects I have done out of my own interest or for participations in competitions.

#### • Causal inference of the effect of participation in sports on the interest in sports as a hobby

[R notebook](https://raw.githack.com/jaeyonggy/Projects/main/causal.nb.html)  
I analyzed [2021년 국민여가 활동조사](https://policydb.kcti.re.kr/#/surveyLeisure4?bbstypecd=3003013&poststatcd=1400) (Korean National Survey on Recreational Activities, 2021) in an attempt to discover causal relationship between sports participation history and interest in sports as a hobby. Since there is a positive correlation between the two variables, I was interested in whether a person having participated in sports before tends to have higher interest in sports as a hobby. Since I am dealing with observational data, propensity score matching (PSM) methodology was used to mitigate the confounding and selection bias in observational studies. In this case, the matching couldn't make the distribution of observed covariates more similar between the two groups. The interpretation of the causal effect was given, while making it clear it is only valid if the assumptions of causal inference was met. Lastly, I explored several options to improve the balance of the observed covariates between the two groups for future research.  
<br/>


#### • Data analysis of ordered categorical outcomes

[Data preprocessing](https://rawcdn.githack.com/jaeyonggy/Projects/b52eb0231ba68baabdfbc64d3d7351f2ed91cac9/data_preprocessing.nb.html)  
[Data analysis](https://github.com/jaeyonggy/Projects/blob/main/analysis.pdf)  
Dataset used for analysis is [Brazilian ecommerce public dataset of orders made at Olist Store](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) which contains the review score given to a product by customers and various covariates. I was especially interested in the covariates, product photos quantities, freight price, and difference between actual delivery time and estimated delivery time. Exploratory data analysis was conducted to explore the relationship between the review score and the covariates of interest. Ordered probit regression was used to model the review score with the covariates. Marginal effects were calculated to see the effects of the covariates on the probabilities of each ordered categorical outcome.  
<br/>


#### • 디지털 활용 관광 산업발전 BI (Business Idea) 경진대회 우수상 (Data analysis competition hosted by Jeju Technopark and organized by Dacon)

[수상작 ipynb - 제주도 여행, 렌트카만 안타면 더 배부른 여행!](https://dacon.io/competitions/official/236012/codeshare/7092?page=1&dtype=random)  
본 팀은 렌트카를 탈 수 밖에 없는 제주도 관광의 문제점, 특히나 제주도 버스의 문제점에 대해 관심을 가지게 되었다. 관광객들이 비싼 렌트카를 빌리지 않아 절약한 경비는 여행 시 다른 데에서 쓰일 수 있다. 30대 미만의 연령층에서 ‘음식/미식 탐방’을 여행 고려요인으로 중요시하는 것을 보면 절약된 경비는 식음료업에서 쓰일 가능성이 높다. 이를 위해 본 팀은 다음의 데이터 분석을 수행하였다. (1) 제주도 내국인관광객 카드 데이터를 분석하여 관광객들이 주로 어디에 소비를 하는지를 연령대별로 알아보기. (2) 제주도 버스정류장 데이터를 분석하여 제주도 버스의 문제점이 무엇인지 알아보기. (3) 제주도 렌트카 이동경로를 분석하여 관광객들이 주로 어디로 이동하는지 알아보기. (4) 제주도의 음식점 데이터를 분석하여 맛집들이 주로 어디에 분포되어 있는지를 알아보기. 마지막으로 위 데이터 분석결과를 정리하고 이에 대한 활용방안 및 기대효과를 제시하였다.  
<br/>


#### • 2022년 문화·관광 데이터 분석대회 최우수상 (Data analysis competition hosted by Korea Culture and Tourism Institute)

[수상작 PPT - 스포츠 활동 및 산업 활성화 방안](http://www.tourbigdata.kr/award.asp)  
2022년 문화·관광 데이터 분석대회에 "스포츠 활동 및 산업 활성화 방안 (스포츠 관련 데이터 분석을 통한 수요 증대 방법 제안)"이라는 주제로 참가하였다. 분석에 사용한 데이터는 국민여가활동조사 (2021), 신한카드 데이터 (2022), 체육시설 데이터 (2022)이다. 국민여가활동조사 데이터를 분석하며 한번이라도 스포츠를 경험한 여부와 스포츠를 취미활동으로 희망하는 여부 간에 양의 상관관계를 확인할 수 있었다. 이를 바탕으로 '스포츠비경험자'를 '스포츠경험자'로 만든다면 스포츠 참여율을 증대시킬 수 있다고 가정하였다. 신한카드 데이터를 통해 소비자의 특성 중 연령대, 성별, 거주지에 따라 알맞는 스포츠를 추천해주는 추천시스템을 구현하였다. 마지막으로, 스포츠를 기피하는 이유 중 하나인 접근성 부족의 원인을 파악하기 위해 체육시설 데이터를 이용하여 지역별 지도에 체육시설을 시각화하였고 체육시설들이 중심지에만 과도하게 분포가 되어있음을 확인하였다.  
<br/>


#### • Bayesian hierarchical modeling to estimate proportions of young people not planning on having a child in South Korea

[R Notebook](https://rawcdn.githack.com/jaeyonggy/Projects/b74c63a1328d9164f9c244b3abaeec1a8d4163c2/young_child_yesorno.nb.html)  
A project done while participating in 2022 통계청논문공모전. A Bayesian hierarchical beta-binomial model was used to estimate proportions of young people not planning on having a child in South Korea. With the advantage of Bayesian hierarchical models' information pooling effects, a more robust and accurate estimates of the proportions were measured. JAGS was used to simulate MCMC samples and various visualizations were employed for inferences and analysis.  
<br/>


#### • Image classification and Grad-CAM of infected leaf images

[Implementation of image classification in PyTorch](https://github.com/jaeyonggy/CVproject/tree/main/PT)  
[Implementation of Grad-CAM in TensorFlow](https://github.com/jaeyonggy/CVproject/tree/main/TF)  
A project done while participating in [Image classification challenge](https://zindi.africa/competitions/makerere-fall-armyworm-crop-challenge) hosted by Zindi.africa. The classification itself was not challenging so Grad-CAM technique was used to obtain heatmaps of each image in addition. I compared how the two models (EfficientNet-B0 and ResNet-50) viewed the images and where they focused on while classifying the images. I wanted to see on which part of image the models focused on when they misclassified it and if there was any difference between the two models on which part of images they focused on.  
<br/>


#### • Time series analysis on fish production of Busan

[R Notebook](https://rawcdn.githack.com/jaeyonggy/Projects/1d280d77a28d9ac6ba66ae1f20be96ff72d299ed/TS.html)  
I performed a time series analysis with the fish production time series data of Busan. The dataset was analyzed using seasonal naive model, STL decomposition, and exponential smoothing model. The results by each model were compared in the end.  
<br/>

<br/>



<a name="cuai"></a>
## CUAI (Chung-Ang Univ. Artifical Intelligence - 중앙대학교 인공지능 학회)  

The projects I have done as a member of CUAI (Chung-Ang Univ. Artifical Intelligence).


#### • Text generation for academic papers's introduction - 논문 서론 작성 AI

[Repo](https://github.com/jaeyonggy/2022_Summer_NLP_T12)  
[Paper](https://github.com/CUAI-CAU/2022-CUAI-Summer-Conference/blob/main/paper/2022_CUAI_Summer_Conference_Shortpaper_NLP_T12.pdf)  
[Presentation](https://www.youtube.com/watch?v=oGnbYiWPBSE)  
We trained a text generation model, specifically KoGPT2, on a series of papers' introduction part. By giving a sentence as an input, the model generated several sentences which would form a full paragraph based on the input sentence. We also paraphrased the generated sentences to avoid any plagiarism. We expect the users to easily write a full introduction by coming up with only a few sentences with this model.  
<br/>


#### • Album Recommendation System Based On Image Similarity - 이미지 유사도 기반 앨범 추천 시스템

[Repo](https://github.com/CUAI-CAU/Recommend-By-Album-Covers)  
[Paper](https://github.com/CUAI-CAU/2021-CUAI-Winter-Conference/blob/main/paper/J.pdf)  
[Presentation](https://www.youtube.com/watch?v=ff_UeduK5lk)  
Our team has managed to implement a music recommendation system based on image similarity. The system gets a user's preferred album's album cover and the album's emotions (one of angry, happy, relaxed and sad) as inputs. By YOLO and k-means models, we output 5 albums that is pre-classified as the same emotion as the input's whose album covers are the most similar to the input's album cover.  
<br/>


#### • Predicting change in stock price using news' headlines - 뉴스 기사 제목을 활용한 주가 변동여부 예측

[Prediction model](https://nbviewer.org/github/jaeyonggy/CUAI-Headlines_TextAnalysis_For_StockPrice_Prediction/blob/main/tfidf_title_to_pred.ipynb)  
[Scraping headlines](https://nbviewer.org/github/jaeyonggy/CUAI-Headlines_TextAnalysis_For_StockPrice_Prediction/blob/main/Web%20Scraping%20for%20headlines/data_title.ipynb)  
[Scraping stock price data](https://nbviewer.org/github/jaeyonggy/CUAI-Headlines_TextAnalysis_For_StockPrice_Prediction/blob/main/Web%20Scraping%20for%20headlines/data_stock.ipynb)  
[Merging data](https://nbviewer.org/github/jaeyonggy/CUAI-Headlines_TextAnalysis_For_StockPrice_Prediction/blob/main/Web%20Scraping%20for%20headlines/data_merge.ipynb)   
Our team wanted to predict whether or not a stock's price increases based on an article's headline. We utilized webscraping to get various headlines of some specific stocks and their stock price at the end of a market the day after the headline was written. We implemented a classification model to predict and assessed its performance.  
<br/>

<br/>



<a name="studies"></a>
## Studies

Studies I have done for statistics classes, research, or any other topic of interests.


#### • Bayesian Statistics

[Bayesian Statistics - pt.1](https://rawcdn.githack.com/jaeyonggy/Studies/5678ff76fc1a549193c28ab9ed5b3df4d09e3291/Bayesian/Bayesian.nb.html)  
[Bayesian Statistics - pt.2](https://rawcdn.githack.com/jaeyonggy/Studies/5678ff76fc1a549193c28ab9ed5b3df4d09e3291/Bayesian/Bayesian_pt2.nb.html)  
[Bayesian Statistics Assignment](https://rawcdn.githack.com/jaeyonggy/Studies/5678ff76fc1a549193c28ab9ed5b3df4d09e3291/Bayesian/Bayes_HW.nb.html)  
[Slice sampler](https://rawcdn.githack.com/jaeyonggy/Studies/25e14e5db26138ed54f4622694562c311074b29f/Bayesian/slice.nb.html)  
[Dirichlet process mixture](https://github.com/jaeyonggy/Studies/blob/main/Bayesian/DPM.pdf)  
A collection of codes and notes I made while studying for classes or anything related to Bayesian statistics.  
<br/>


#### • Bayesian additive regression trees (BART)

[Tan and Roy (2019) - pt.1](https://github.com/jaeyonggy/Studies/blob/main/BART/BART2019-review.pdf)  
[Tan and Roy (2019) - pt.2](https://github.com/jaeyonggy/Studies/blob/main/BART/BART2019-review2.pdf)  
[Hill (2011)](https://github.com/jaeyonggy/Studies/blob/main/BART/BART_bio.pdf)  
A collection of PPT that I've made while studying papers related to Bayesian additive regression trees (BART).  
<br/>


#### • Hidden Markov models (HMM) for time series

[Ch.1 Preliminaries: mixtures and Markov chains](https://rawcdn.githack.com/jaeyonggy/HMM/f8d41722020e60950eb7982601bdd7fcf7b385c6/HMM.nb.html)  
[Ch.2 Hidden Markov models: definition and properties](https://rawcdn.githack.com/jaeyonggy/HMM/f8d41722020e60950eb7982601bdd7fcf7b385c6/HMM_ch2.nb.html)  
[HMM paper](https://rawcdn.githack.com/jaeyonggy/HMM/6978acd327ef2328295f64254275d827703aeb4b/HMM_paper.nb.html)  
A collection of R Notebooks that I've written while studying 'Hidden Markov models for time series an introduction using R' by Zucchini et al.  
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
<br/>


#### • Bayesian hierarchical clustering (BHC)

[Heller and Ghahramani (2005)](https://github.com/jaeyonggy/Studies/blob/main/BHC.pdf)  
A PPT that I've made while studying a paper related to Bayesian hierarchical clustering (BHC).  
<br/>


#### • Basic R Statistics

[Hypothesis Testing](https://rawcdn.githack.com/jaeyonggy/Studies/9eb7428ee5aeefc89c6550100684c975b047a1e2/RStatBasic/HypothesisTesting.nb.html)  
[Categorical Data Analysis](https://rawcdn.githack.com/jaeyonggy/Studies/9eb7428ee5aeefc89c6550100684c975b047a1e2/RStatBasic/categorical.nb.html)  
[Simple Linear Regression](https://rawcdn.githack.com/jaeyonggy/Studies/9eb7428ee5aeefc89c6550100684c975b047a1e2/RStatBasic/SimpleLinearRegression.nb.html)  
A collection of R Notebooks that I've written while studying '제대로 알고 쓰는 R 통계분석' by 이윤환.  
<br/>

<br/>


