  

  

학습 결과 확인
--------


AI 성장 및 배포 → 학습 → 학습 히스토리 → 학습 상세 정보 → 학습 평가

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/ai_modeling/image_type/training_result/training_result_move_training_history.png)  



AI 성장 및 배포 → 모델 → (모델별) 학습 정보 확인 → 학습 평가

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/ai_modeling/image_type/training_result/training_result_move_model.png)  



아이디(OR 버전 목록)를 클릭하여 학습 상세 페이지로 이동합니다.

학습 상세 정보로 이동한 뒤, 학습 평가를 눌러 학습 결과를 확인할 수 있습니다. 


  

모델 평가
-----

평가 탭을 클릭하여 평가 결과를 확인할 수 있습니다.

  
## 분류

모델의 정확도를 확인할 수 있으며, 라벨 클래스별 세부 평가 점수를 확인할 수 있습니다.

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/ai_modeling/image_type/training_result_04.png)  

  

\*각 세부 평가 항목 공식은 다음과 같습니다.

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/ai_modeling/image_type/training_result_05.png)  
![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/ai_modeling/image_type/training_result_06.png)  
![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/ai_modeling/image_type/training_result_07.png)  
![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/ai_modeling/image_type/training_result_08.png)  

  

  

### 혼동 행렬


현재 모델의 평가에 사용된 데이터들의 기대치와 예측값을 행렬 그래프로 표현합니다.

행렬의 각 셀을 선택하여 상세한 데이터별 예측 정보를 확인할 수 있습니다.

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/ai_modeling/image_type/training_result_09.png)  


## 객체 감지

임계값에 따른 평가지표를 확인할 수 있습니다.

mean Average Precision (mAP), Precision-Recall Curve
![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/ai_modeling/image_type/training_result/object_detection_map_PRCurve.png)  


결과 항목
![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/ai_modeling/image_type/training_result/object_detection_result_item.png)  


시험 결과
![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/ai_modeling/image_type/training_result/object_detection_test_result.png)  










