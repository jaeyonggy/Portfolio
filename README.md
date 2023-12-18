## Data Science Portfolio

[GitHub](https://github.com/jaeyonggy)  
[LinkedIn](https://www.linkedin.com/in/jaeyonglee5)  



## About Me


**I want to be a data scientist that makes your life comfortable!** 
<br/>


I received a Bachelor's degree in Applied Statistics and a Bachelor's degree in Software Humanities at Chung-Ang University on February, 2022.  
I'm currently pursuing a Master's degree in Statistics at Chung-Ang University with full scholarship from Chung-Ang University GRS (Graduate Research Scholarship).  

I was a member of Chung-Ang University GAS (Global Ambassador Scholarship - 중앙대학교 국제처 학생대사) from July 2020 to June 2021.  
I was a member of CUAI (Chung-Ang University Artificial Intelligence - 중앙대학교 인공지능 학회) from March 2021 to August 2022.  

I am proficient in Python, R, and MySQL.  
<br/>

<br/>



## Contents

• [Research](#research)  
• [Projects from university](#projects)  

<br/>

<a name="research"></a>
## Research

To be filled!

<br/>


<a name="projects"></a>
## Projects

Projects I have done during my years in university. These include simple toy projects for data science, or more serious projects for competitions, and studies for certain subjects.

#### • Causal inference of the effect of participation in sports on the interest in sports as a hobby

[R notebook](https://raw.githack.com/jaeyonggy/Projects/main/causal.nb.html)  
I analyzed [2021년 국민여가 활동조사](https://policydb.kcti.re.kr/#/surveyLeisure4?bbstypecd=3003013&poststatcd=1400) (Korean National Survey on Recreational Activities, 2021) in an attempt to discover causal relationship between sports participation history and interest in sports as a hobby. Since there is a positive correlation between the two variables, I was interested in whether a person having participated in sports before tends to have higher interest in sports as a hobby. Since I am dealing with observational data, propensity score matching (PSM) methodology was used to mitigate the confounding and selection bias in observational studies. In this case, the matching couldn't make the distribution of observed covariates more similar between the two groups. The interpretation of the causal effect was given, while making it clear it is only valid if the assumptions of causal inference was met. Lastly, I explored several options to improve the balance of the observed covariates between the two groups for future research.  
<br/>


#### • 디지털 활용 관광 산업발전 BI (Business Idea) 경진대회 우수상 (Data analysis competition hosted by Jeju Technopark and organized by Dacon)

[수상작 ipynb - 제주도 여행, 렌트카만 안타면 더 배부른 여행!](https://dacon.io/competitions/official/236012/codeshare/7092?page=1&dtype=random)  
본 팀은 렌트카를 탈 수 밖에 없는 제주도 관광의 문제점, 특히나 제주도 버스의 문제점에 대해 관심을 가지게 되었다. 관광객들이 비싼 렌트카를 빌리지 않아 절약한 경비는 여행 시 다른 데에서 쓰일 수 있다. 30대 미만의 연령층에서 ‘음식/미식 탐방’을 여행 고려요인으로 중요시하는 것을 보면 절약된 경비는 식음료업에서 쓰일 가능성이 높다. 이를 위해 본 팀은 다음의 데이터 분석을 수행하였다. (1) 제주도 내국인관광객 카드 데이터를 분석하여 관광객들이 주로 어디에 소비를 하는지를 연령대별로 알아보기. (2) 제주도 버스정류장 데이터를 분석하여 제주도 버스의 문제점이 무엇인지 알아보기. (3) 제주도 렌트카 이동경로를 분석하여 관광객들이 주로 어디로 이동하는지 알아보기. (4) 제주도의 음식점 데이터를 분석하여 맛집들이 주로 어디에 분포되어 있는지를 알아보기. 마지막으로 위 데이터 분석결과를 정리하고 이에 대한 활용방안 및 기대효과를 제시하였다.  
<br/>


#### • 2022년 문화·관광 데이터 분석대회 최우수상 (Data analysis competition hosted by Korea Culture and Tourism Institute)

[수상작 PPT - 스포츠 활동 및 산업 활성화 방안](http://www.tourbigdata.kr/award.asp)  
2022년 문화·관광 데이터 분석대회에 "스포츠 활동 및 산업 활성화 방안 (스포츠 관련 데이터 분석을 통한 수요 증대 방법 제안)"이라는 주제로 참가하였다. 분석에 사용한 데이터는 국민여가활동조사 (2021), 신한카드 데이터 (2022), 체육시설 데이터 (2022)이다. 국민여가활동조사 데이터를 분석하며 한번이라도 스포츠를 경험한 여부와 스포츠를 취미활동으로 희망하는 여부 간에 양의 상관관계를 확인할 수 있었다. 이를 바탕으로 '스포츠비경험자'를 '스포츠경험자'로 만든다면 스포츠 참여율을 증대시킬 수 있다고 가정하였다. 신한카드 데이터를 통해 소비자의 특성 중 연령대, 성별, 거주지에 따라 알맞는 스포츠를 추천해주는 추천시스템을 구현하였다. 마지막으로, 스포츠를 기피하는 이유 중 하나인 접근성 부족의 원인을 파악하기 위해 체육시설 데이터를 이용하여 지역별 지도에 체육시설을 시각화하였고 체육시설들이 중심지에만 과도하게 분포가 되어있음을 확인하였다.  
<br/>


#### • Image classification and Grad-CAM of infected leaf images

[Implementation of image classification in PyTorch](https://github.com/jaeyonggy/CVproject/tree/main/PT)  
[Implementation of Grad-CAM in TensorFlow](https://github.com/jaeyonggy/CVproject/tree/main/TF)  
A project done while participating in [Image classification challenge](https://zindi.africa/competitions/makerere-fall-armyworm-crop-challenge) hosted by Zindi.africa. The classification itself was not challenging so Grad-CAM technique was used to obtain heatmaps of each image in addition. I compared how the two models (EfficientNet-B0 and ResNet-50) viewed the images and where they focused on while classifying the images. I wanted to see on which part of image the models focused on when they misclassified it and if there was any difference between the two models on which part of images they focused on.  
<br/>


#### • Album Recommendation System Based On Image Similarity - 이미지 유사도 기반 앨범 추천 시스템

[Repo](https://github.com/CUAI-CAU/Recommend-By-Album-Covers)  
[Paper](https://github.com/CUAI-CAU/2021-CUAI-Winter-Conference/blob/main/paper/J.pdf)  
[Presentation](https://www.youtube.com/watch?v=ff_UeduK5lk)  
Our team has managed to implement a music recommendation system based on image similarity. The system gets a user's preferred album's album cover and the album's emotions (one of angry, happy, relaxed and sad) as inputs. By YOLO and k-means models, we output 5 albums that is pre-classified as the same emotion as the input's whose album covers are the most similar to the input's album cover.  
<br/>


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

<br/>