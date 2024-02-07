  

  

## 학습 결과 확인

학습 결과를 확인할 수 있는 두 가지 방법이 있습니다. 

첫째, AI 성장 및 배포 → 학습 → 학습 히스토리 → 학습 상세 정보 → 학습 평가



![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/ai_modeling/image_type/training_result/training_result_move_training_history.png)  



둘째, AI 성장 및 배포 → 모델 → (모델별) 학습 정보 확인 → 학습 평가



![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/ai_modeling/image_type/training_result/training_result_move_model.png)  



아이디(OR 버전 목록)를 클릭하여 학습 상세 페이지로 이동합니다.

학습 상세 정보로 이동한 뒤, 학습 평가를 눌러 학습 결과를 확인할 수 있습니다. 


  

## 모델(학습) 평가


평가 탭을 클릭하여 평가 결과를 확인할 수 있습니다.

  
## 분류, 이상치 탐지

모델의 정확도를 확인할 수 있으며, 라벨 클래스별 세부 평가 점수를 확인할 수 있습니다.



![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/ai_modeling/csv_type/training_result/training_result_classification.png)  

  

\*각 세부 평가 항목 공식은 다음과 같습니다.

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/ai_modeling/image_type/training_result_05.png)  
![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/ai_modeling/image_type/training_result_06.png)  
![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/ai_modeling/image_type/training_result_07.png)  
![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/ai_modeling/image_type/training_result_08.png)  

  

  

### 혼동 행렬


현재 모델의 평가에 사용된 데이터들의 기대치와 예측값을 행렬 그래프로 표현합니다.

행렬의 각 셀을 선택하여 상세한 데이터별 예측 정보를 확인할 수 있습니다.




## 시계열 예측 

평가 지표 : 모델의 평가 지표(기본적으로 평균 절대오차)를 확인할 수 있습니다. 

결과 그래프 : 설정한 window 단위로 구분된 그래프를 통해, input data, 라벨(실제 값), 예측값을 볼 수 있습니다.  

테스트 데이터 셋 : 테스트 시 사용한 컬럼별 데이터를 표 형태로 볼 수 있습니다.



![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/ai_modeling/csv_type/training_result/training_result_forecasting2.png)  





## 회귀

평가 지표 : 모델의 평가 지표(평균 절대오차, 평균 제곱오차, 평균 제곱근오차)를 확인할 수 있습니다. 

테스트 데이터 셋 : 테스트 시 사용한 컬럼별 데이터를 표 형태로 볼 수 있습니다.

결과 그래프 : input data, 라벨(실제 값), 예측값을 볼 수 있습니다.  



![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/ai_modeling/csv_type/training_result/training_result_regression.png)  










