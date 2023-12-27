사용자 설정 학습을 진행할 경우 학습에 필요한 사용자 변수를 설정합니다.

  

데이터셋 선택
------


학습 시 사용할 데이터 셋을 선택합니다.

  

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/ai_modeling/image_type/training_dialog/select_dataset.png)  

  

설정을 다 하면 계속 버튼을 눌러 다음 설정으로 이동합니다.

  

  

학습 설정
------


1. 새로운 버전의 모델을 만들기 위한 베이스 모델을 설정합니다.
   - 오픈 라이센스로 제공되는 여러 pre-trained 된 모델을 베이스 모델로 선택할 수 있습니다.
   
2. 하이퍼 파라미터 설정

   하이퍼파라미터는 학습 프로세스가 시작되기 전에 설정되는 매개변수로,
   
   모델의 바깥에 있으며(데이터로 학습이 불가능), 학습 성능에 직접적인 영향을 미칩니다. 
   
   - epoch
     : 전체 훈련 데이터셋을 한 번 완전히 통과하는 것을 의미합니다.
     
       Epoch 값이 너무 작으면 모델이 충분히 학습되지 않아 Underfitting이 발생할 수 있습니다.
       
       반면, Epoch 값이 너무 크면 모델이 훈련 데이터에 과도하게 적합되어 Overfitting이 발생할 수 있습니다
       
   - batch size
     : 배치 크기는 한 번의 반복(iteration)에서 사용되는 데이터 샘플의 수입니다.
     
       배치 크기를 줄이면
       
       필요한 메모리가 감소하며,
       
       전체 데이터를 쪼개어 여러 번 학습하기 때문에 최소 요구 메모리량을 줄일 수 있습니다.
       
       작은 배치 크기는 노이즈가 많은 경사 추정치를 제공하여 옵티마이저가 지역 최소값을 피하도록 돕습니다. 
       
       배치 크기를 늘리면
       
       모델의 일반화 성능을 저하시킬 수 있습니다.
       
       이는 큰 배치 크기가 경사 하강법의 노이즈를 줄이므로, 모델이 훈련 데이터에 과적합될 가능성이 높아지기 때문입니다.
       
       큰 배치 크기는 더 정확한 경사 추정치를 제공하지만, 옵티마이저가 지역 최소값에 갇힐 가능성이 높아집니다
       
   - learning rate
   
     : 손실 함수의 기울기와 관련하여 네트워크의 가중치를 얼마나 조정할지를 결정합니다.
     
       학습률이 높으면 가중치 조정이 크게 이루어져 모델이 빠르게 수렴하게 되지만, 이 경우 최적의 값을 지나칠 수 있습니다.
       
       반면 학습률이 낮으면 가중치 조정이 작게 이루어져 모델이 느리게 수렴하게 되며, 이 경우 지역 최소값에 갇히거나 수렴하는 데 오랜 시간이 걸릴 수 있습니다.
       
   - warmup learning rate
   
     : 웜업 학습률은 훈련 초기에 학습률을 점진적으로 증가시키는 기법입니다.
     
       학습 초기에 모든 가중치들이 무작위로 초기화되어 있기 때문에, 처음부터 높은 학습률을 적용하면 가중치 업데이트가 불안정해질 수 있습니다.
       
       이러한 불안정성은 모델이 학습 과정에서 불안정한 상태에 빠지거나, 최적의 솔루션을 찾지 못하게 만들 수 있습니다.
       
       이를 방지하기 위해 학습률 웜업 전략에서는 학습 초기에 학습률을 낮게 설정하고, 점차적으로 높여 나갑니다.
       
       이렇게 하면 가중치 업데이트가 점진적으로 이루어지므로, 모델이 안정적으로 학습할 수 있습니다.
   
4. 모델 태그 설정
   - 모델에 대한 태그를 설정합니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/ai_modeling/image_type/training_dialog/set_training_config.png)  
  


학습 서버 선택 
-----


학습이 진행될 서버를 선택합니다.

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/ai_modeling/image_type/training_dialog/select_training_server.png)  

  

학습 서버 선택후, 계속 버튼을 눌러 다음 설정으로 이동합니다.

  

  

학습 설정 확인
--------


학습 시작 전 최종적으로 설정한 내용을 확인하고 완료 버튼을 누릅니다.
  

  

  

학습 시작 버튼이 활성화되면 클릭합니다.

  

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/ai_modeling/image_type/training_dialog/start_training.png)  

  

최종 시작 확인 다이얼로그 창이 뜨면 확인 버튼을 눌러 학습을 시작합니다.

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/ai_modeling/image_type/training_dialog/check_start_training.png)  
