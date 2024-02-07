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

  

# 학습 평가 탭

## Classification 
학습을 진행하면서 실시간으로 학습 횟수(epoch)에 따른 loss 값과 accuracy 값을 그래프로 표현합니다.

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/ai_modeling/image_type/monitoring/training_monitoring.png)  

## Object Detection 
학습을 진행하면서 실시간으로 학습 횟수(epoch)에 따른 손실(분류 손실, 위치 추정 손실, 정규화 손실, 총 손실)을 그래프로 표현합니다.

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/ai_modeling/image_type/monitoring/ojbect_detection_monitoring.png)  

