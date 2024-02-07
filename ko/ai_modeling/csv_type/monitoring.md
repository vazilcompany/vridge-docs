현재 프로젝트에서 진행 중인 모델 학습을 모니터링합니다.

학습이 진행 중일 때만 페이지를 볼 수 있습니다.

  

학습 진행 시퀀스
---------


학습은 다음과 같은 단계로 진행됩니다.

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/ai_modeling/image_type/monitoring_01.png)  

  

1.  브릿지 서버에서 학습 서버로 학습 요청을 하고 학습 서버에서 성공적으로 학습 가능한 상태를 확인합니다.
2.  학습 준비가 완료되면 학습 서버에서 브릿지 플랫폼에서 데이터셋 다운 요청을 실행합니다.
3.  데이터셋 다운로드가 완료되면 사전에 설정한 학습 설정 정보를 사용해 학습합니다.
4.  학습이 완료되고 모델이 생성되면, 테스트 데이터셋으로 모델을 평가합니다.
5.  평가가 완료되면, 결과 정보와 모델 파일을 브릿지 플랫폼에 전송합니다.
------


# 학습 유형에 따른 모니터링


## 분류, 이상치 탐지, 시계열 예측

딥러닝 모델을 활용합니다. 
손실, 평균 절대 오차(MAE)의 변화를 그래프로 보여줍니다. 


![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/ai_modeling/csv_type/monitoring/monitoring.png)  



## 회귀 

딥러닝 모델과 선형회귀와 같은 ML 모델 모두를 사용할 수 있습니다. 
딥러닝 모델이 아닌 경우, Monitoring 볼 수 없습니다.



![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/ai_modeling/csv_type/monitoring/regression_monitoring.png)  
 

