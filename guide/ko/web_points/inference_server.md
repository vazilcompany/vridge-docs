  

모델을 배포하여 테스트 또는 추론 하는 데에 사용되는 **추론 서버****(Custom Inference Server)**에 대해 설명합니다.

  

웹 포인트 등록
--------


오른쪽 상단의 '웹 포인트 등록' 버튼을 클릭합니다.

  

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/web_points/inference_server_01.png)  

  

웹 포인트 이름을 작성하고,

클라우드 유형 • 지역 • 서버 사양을 선택합니다.

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/web_points/inference_server_02.png)  

  

  

예상 청구 금액이 명시되며, '등록' 버튼을 누르면 웹 포인트 등록(서버 임대)이 시작됩니다.

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/web_points/inference_server_03.png)  

  

  

등록은 몇 분이 소요될 수 있으며, 'PENDING' 상태에서는 서버를 사용할 수 없습니다.

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/web_points/inference_server_04.png)  

  

  

등록이 끝나면 'RUNNING' 상태로 바뀌며, 서버를 사용할 수 있습니다.

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/web_points/inference_server_05.png)  

  

  

서버 시작&중지
--------


웹 포인트 목록에서 사용하고자 하는 웹포인트를 클릭합니다.

오른쪽 상단의 '서버 시작' 버튼을 누르면 서버가 가동되고,

'서버 중지' 버튼을 누르면 서버가 중지됩니다.

시작과 중지 작업은 몇 분이 걸릴 수 있습니다.

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/web_points/inference_server_06.png)  

  

  

웹 포인트 상세정보
----------


웹 포인트 목록에서 항목을 선택하면 상세 정보가 나옵니다.

  

웹 포인트 아이디, 이름 등의 정보를 확인할 수 있습니다.

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/web_points/inference_server_07.png)  

  

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

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/web_points/inference_server_08.png)  

  

  

'배포' 탭에서 해당 웹 포인트를 사용한 배포 기록을 확인할 수 있습니다.

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/web_points/inference_server_09.png)  

