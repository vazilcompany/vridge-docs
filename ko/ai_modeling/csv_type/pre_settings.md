## 데이터셋 선택
학습 시 사용할 데이터 셋을 선택합니다.

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/ai_modeling/csv_type/training_dialog/select_dataset.png)



## 학습 설정
모델 설정 : 

새로운 버전의 모델을 만들기 위한 베이스 모델을 설정합니다.

오픈 라이센스로 제공되는 여러 사전학습모델을 베이스 모델로 선택할 수 있습니다.

모델의 목적에 맞는 평가 지표를 선택할 수 있습니다. 


모델 태그 설정 : 

모델에 대한 태그를 설정합니다.



![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/ai_modeling/csv_type/training_dialog/set_training_config_1.png)

### window 정보 설정 

시계열 예측일 경우 학습시 사용할 window 생성을 위한 설정을 합니다. 

입력 넓이
: 시계열 예측의 맥락에서 이는 미래 값을 예측하기 위한 입력 기능으로 사용되는 과거 시간 단계의 수입니다.
  
라벨 넓이
: 모델이 예측해야 하는 미래의 시간 단계 수를 정의합니다.
  
이동
: 입력 창의 시작과 레이블 창의 첫 번째 시간 간격 사이의 시간 간격을 나타냅니다.

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/ai_modeling/csv_type/training_dialog/set_training_config_window.png)



### 하이퍼 파라미터
모델 설정에서 선택한 모델이 딥러닝 모델일 경우 하이퍼 파라미터를 설정합니다. 

epoch
: 전체 훈련 데이터셋을 한 번 완전히 통과하는 것을 의미합니다

batch size
: 배치 크기는 한 번의 반복(iteration)에서 사용되는 데이터 샘플의 수입니다.

learning rate
: 손실 함수의 기울기와 관련하여 네트워크의 가중치를 얼마나 조정할지를 결정합니다.

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/ai_modeling/csv_type/training_dialog/set_hyper_parameter_model_tag.png)

설정을 다 하면 계속 버튼을 눌러 다음 설정으로 이동합니다.



## 학습 서버 선택
학습이 진행될 서버를 선택합니다.

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/ai_modeling/image_type/training_dialog/select_training_server.png)

학습 서버 선택후, 계속 버튼을 눌러 다음 설정으로 이동합니다.



## 학습 설정 확인 

학습 시작 전 최종적으로 설정한 내용을 확인하고, 학습 시작 버튼이 활성화되면 클릭합니다.


![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/ai_modeling/image_type/training_dialog/start_training.png)  


최종 시작 확인 다이얼로그 창이 뜨면 확인 버튼을 눌러 학습을 시작합니다.


![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/ai_modeling/image_type/training_dialog/check_start_training.png)
