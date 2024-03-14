  

모델을 배포하여 테스트 또는 추론 하는 데에 사용되는 **추론 서버** (Inference Server)에 대해 설명합니다.

  

## 웹 포인트 등록

조직 사이즈 메뉴 → '웹 포인트'로 이동합니다. 

오른쪽 상단의 '웹 포인트 등록' 버튼을 클릭합니다.

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/web_points/inference_server_2/create_webpoint_1.png)  

  

웹 포인트 이름을 작성하고,

클라우드 유형 • 지역 • 서버 사양을 선택합니다.

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/web_points/inference_server_2/create_webpoint_2.png)  

  

생성 버튼을 클릭하면, 웹 포인트가 생성됩니다. 

현재 아시아 태평양(서울) 리전에서만 포인트 생성이 가능하며, g4dn.xlarge 유형만 지원하고 있습니다. 

다른 서비스를 이용하시려면 아래의 연락처로 문의해 주시기 바랍니다.

전화 문의 : 051-609-9633
이메일 문의 : programming@vazilcompany.com


  

생성은 몇 분이 소요될 수 있으며, 'PENDING' 상태에서는 서버를 사용할 수 없습니다.

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/web_points/inference_server_2/create_webpoint_3.png)  

  

생성이 끝나면 'RUNNING' 상태로 바뀌며, 서버를 사용할 수 있습니다.

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/web_points/inference_server_2/create_webpoint_4.png)  
  

  

## 서버 시작&중지&삭제


웹 포인트 목록에서 사용하고자 하는 웹포인트를 클릭합니다.

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/web_points/inference_server_2/create_webpoint_5.png)  


![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/web_points/inference_server_2/create_webpoint_6.png)  


'서버 시작' 버튼을 누르면 서버가 가동되고,

'서버 중지' 버튼을 클릭하면, 확인 창이 열립니다. 

'중지' 버튼을 클릭하면, 서버가 중지됩니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/web_points/inference_server_2/create_webpoint_7.png)


시작과 중지 작업은 몇 분이 걸릴 수 있습니다.

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/web_points/inference_server_2/create_webpoint_7_1.png)


'삭제' 버튼을 클릭하면, 삭제 확인 창이 열립니다.

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/web_points/inference_server_2/create_webpoint_8.png)


'삭제' 버튼을 클릭하면, 웹 포인트가 삭제 됩니다. 




  

## 웹 포인트 상세정보


웹 포인트 목록에서 웹 포인트를 선택하면 상세 정보가 나옵니다.

  

웹 포인트 아이디, 이름 등의 정보를 확인할 수 있습니다.

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/web_points/inference_server_2/create_webpoint_9.png)  

  

'추론'과 '구현' 탭에 대해서는 '9-2-1. 모델 테스트 하기'와 '9-2-2. 추론 API 서버로 사용하기'에서 설명합니다.

  

'통계' 탭에서

배포된 모델의 판단 수, 전체 판단율 등의 통계 내역을 확인할 수 있습니다.

*   판단 수 : 선택한 기간 동안 사용된 모델의 판단 수를 보여줍니다.
*   전체 판단율 : 선택한 기간 동안 모델의 전체 평균 판단율
*   전체 평균 추론 시간 : 선택한 기간 동안 모델의 추론에 걸린 평균 시간
*   평균 추론 시간 :
*   평균 판단율 :
*   추론 요청 수 :
*   클래스별 판단율 :
*   분류별 판단 결과 :

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/web_points/inference_server_2/create_webpoint_10.png)  

  

  

'배포' 탭에서 해당 웹 포인트를 사용한 배포 기록을 확인할 수 있습니다.

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/web_points/inference_server_2/create_webpoint_11.png)  


![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/web_points/inference_server_2/create_webpoint_12.png)  
