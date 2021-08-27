# 기본적인 한글 분류 모델

### 형태소 분석, 불용어 삭제, 빈 string 제거
### scikit-learn의 CountVectorizer 활용한 텍스트 벡터화
### scikit-learn의 train_test_split으로 학습, 테스트 셋 분리
### 보편적으로 쓰이는 Randomforest 모델 기반으로 텍스트 벡터와 label을 학습하여 분류 예측
### metric은 accuracy, f1 score활용


### 참고자료 
#### 네이버 영화 리뷰 데이터 : https://github.com/e9t/nsmc/
#### 불용어 리스트1 : https://www.ranks.nl/stopwords/korean
#### 불용어 리스트2 : https://gist.github.com/spikeekips/40eea22ef4a89f629abd87eed535ac6a
