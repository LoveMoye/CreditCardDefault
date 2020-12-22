# CreditCardDefault

- kaggle 신용카드 데이터: default 분류

### Oversampling을 통해 불균형한 데이터 처리
불균형한 데이터를 처리하기 위해, oversampling 기법을 활용 함.

### Model 설명
- 시계열 자료는 LSTM cell에 입력하여 feature를 추출하고 추출된 feature에 추가 자료를 연결해 fully connected layer에 연결하였음.

### 결과
<img src = "https://user-images.githubusercontent.com/68679247/102863968-b6e19980-4476-11eb-9b3a-9f24d626210e.PNG" width = "50%">
