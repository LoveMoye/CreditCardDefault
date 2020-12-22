# CreditCardDefault

- kaggle 신용카드 데이터: default 분류

### Oversampling을 통해 불균형한 데이터 처리
불균형한 데이터를 처리하기 위해, oversampling 기법을 활용 함.

### Model 설명
- 시계열 자료는 LSTM cell에 입력하여 feature를 추출하고 추출된 feature에 추가 자료를 연결해 fully connected layer에 연결하였음.

### 결과
<img src = "https://user-images.githubusercontent.com/68679247/102864221-18a20380-4477-11eb-9642-e4ddf0fc5d9f.PNG" width = "80%">
<br>
precision, recall, f1-score, accuracy로 비교한 결과, sampling 한 후, recall과 f1-score는 향상되었고, precision은 줄어들었음. accuracy는 비슷한 결과를 나타냄.
