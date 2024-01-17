데이터 관리
------

정형 데이터 유형 프로젝트의 데이터를 관리합니다.

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/data_manage/table/data_manage_index.png)  


현재 프로젝트에 업로드 된 파일명, 크기, 생성일 등을 볼 수 있습니다. 


  

데이터 추가
------

파일 업로드 버튼을 클릭하여, 데이터를 업로드 할 수 있습니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/data_manage/table/file_upload_button.png)  


파일 업로드 버튼을 클릭하면, 정형 데이터 업로드 창이 나옵니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/data_manage/table/upload/file_upload_dialog.png)  


데이터를 추가하는 방법에 2가지가 있습니다. 

첫째, '파일 선택' 란을 클릭하거나, 파일을 드래그하여 업로드할 수 있습니다. 


둘쩨, '데이터베이스 선택' 란을 클릭하여, 외부 데이터베이스에 있는 데이터를 가져올 수 있습니다.




### 파일 선택 업로드 

정형 데이터 업로드 창에서 '파일 선택'을 클릭 시, 파일을 선택할 수 있는 탐색 창이 열립니다. 
(현재 .csv 파일 형식만 지원하고 있습니다. )

지원하는 형식에 맞는 파일을 선택 후, 업로드할 수 있습니다. 

파일을 선택하시면, 업로드 창에 선택한 파일의 데이터를 표 형식으로 확인할 수 있습니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/data_manage/table/upload/upload_dialog_after_select_csv_file.png)  


업로드 창 아래에 있는 페이지네이션 바를 이용하면 다양한 데이터를 쉽게 탐색할 수 있습니다.



데이터를 확인한 후 업로드하려면 왼쪽 하단의 ‘업로드’ 버튼을 클릭하십시오.


'업로드 확인' 창이 열립니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/data_manage/table/upload/upload_check_dialog.png)  


'업로드 확인' 창에서 '확인' 버튼을 클릭하시면, 업로드가 시작됩니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/data_manage/table/upload/uploading.png)  



선택된 파일을 비우려면, '정형 데이터 업로드' 창 오른쪽 상단의 톱니바퀴 모양을 클릭합니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/data_manage/table/upload/upload_setting_button.png)  


'비우기' 버튼을 클릭하면, 선택된 파일을 비울 수 있습니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/data_manage/table/upload/clear_select_file.png)  





### 데이터베이스 선택 업로드 

정형 데이터 업로드 창에서 '데이터베이스 선택'을 클릭 시, 외부 데이터베이스에 있는 데이터를 가져올 수 있습니다. 

(\* 현재 연결 가능한 DB 목록 : MariaDB, MongoDB)

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/data_manage/table/select_database_button.png)  




1. 어떤 데이터베이스에서 데이터를 가져올 것인지 선택합니다.

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/data_manage/table/upload/select_database_dialog.png)  



2. Host, Port, Database name, User name, password를 입력하고 왼쪽 하단의 '상태 확인' 버튼을 클릭합니다.

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/data_manage/table/upload/check_database_status.png)  


상태 체크 중 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/data_manage/table/upload/checking_database_status.png)  

입력한 정보의 데이터베이스와 연결이 성공적으로 이루어졌다면, '상태 확인' 버튼이 초록색으로 변합니다.

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/data_manage/table/upload/check_database_status_ok.png)  



4. 데이터베이스와 연결이 이루어 졌다면, 데이터베이스의 테이블을 선택합니다.

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/data_manage/table/upload/select_table.png)  



5. 테이블의 컬럼들 중, 필요한 컬럼들을 선택합니다.

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/data_manage/table/upload/select_columns.png)  



6. 선택한 데이터베이스의 데이터는 .csv 형식의 파일로 저장됩니다. 저장될 파일의 이름을 적어주세요.

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/data_manage/table/upload/database_dialog_detail_info.png)  



7. 오른쪽 하단, '생성' 버튼을 클릭하시면, 선택이 완료됩니다.

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/data_manage/table/upload/after_select_database_upload_dialog.png)  


이후로는, 앞에서 설명드렸던 파일 선택 업로드와 같은 방법으로, 데이터를 업로드할 수 있습니다. 


데이터베이스 데이터 업로드 후, 데이터 관리 페이지 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/data_manage/table/upload/data_manage_index_after_upload_database.png)  



  



데이터셋 생성
------




데이터셋 생성
------


데이터셋 관리 페이지 
------






