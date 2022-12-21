# 감성분석을 활용한 VOC System - Bert 모델 활용 도전기
> 진행기간: 2022.11.30~2022.12.05
#### 목차
1. [개요](#개요)
2. [프로젝트 환경](#프로젝트-환경)
3. [References](#references)

## 1. 개요
### 1.1 기획 동기 및 의도
- 클라이언트의 '니즈' 파악이 부서 내에서 상당히 파편적인 정보를 기반, 비객관적으로 파악되는 것의 답답함
- 진짜 그들의 '니즈'는 소셜미디어 상에 여과없이 드러나 있음
- 이들의 정성적 평가를 감성분석을 통해 정량화해보자! 오피니언 마이닝 VOC(Voice of customer)

### 1.2 개인적인 회고
**좋았던 점**   
- 

**보완이 필요한 점**    
- 
   
**1달 전 나보다 발전한 것?**   
- 
   
**What I learned** 
-  
   
**더 배우고 싶은 점 :**   
- 
   
### 1.2 피드백
**Good👍**   
- 
   
**Needs to be improved😈**
- 

-----



## 2. 프로젝트 환경
### 2.1 학습 데이터
1. 오버워치 인벤 게시판 스크레핑(직접 진행)
2. [bab2min님의 steam.txt 데이터셋](https://github.com/bab2min/corpus/tree/master/sentiment)
- 다만 데이터 라벨링이 조금 부적절하는 피드백이 있었음

### 2.2 모델
- LSTM
- Bidirectional LSTM
- BERT | [google-research/bert](https://github.com/google-research/bert/blob/master/multilingual.md)

## 3. References
책
- 파이썬 텍스트 마이닝 완벽 가이드:자연어 처리 기초부터 딥러닝 기반 BERT 모델까지 | 박상언, 강주영, 정석찬 저 | 위키북스
- [딥 러닝을 이용한 자연어 처리 입문](https://wikidocs.net/book/2155)

영상
- [뜻밖의 텍스트마이닝](http://ndcreplay.nexon.com/NDC2017/sessions/NDC2017_0003.html#k%5B%5D=%EB%8D%B0%EC%9D%B4%ED%84%B0)

논문
- 김하람, 전찬희 and 김동수. (2022). 앱 마켓 리뷰 데이터 분석을 통한 배달 앱의 사용자 만족도 연구: 배달의민족과 쿠팡이츠를 중심으로. 한국전자거래학회지, 27(3), 113-125.
- HA, S. H., & ROH, T. H. (2020). Sentiment Analysis for Public Opinion in the Social Network Service. The Journal of the Convergence on Culture Technology, 6(1), 111–120. https://doi.org/10.17703/JCCT.2020.6.1.111
