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

데이터를 업로드한 이후, 데이터셋을 생성할 수 있습니다. 


'데이터 관리' 페이지 우측 상단, '데이터셋 생성' 버튼을 클릭합니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/dataset_dialog/table/create_dataset_button.png)



'새로운 데이터셋 생성' 창이 열립니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/dataset_dialog/table/create_dataset_dialog.png)



### 1. 원천 데이터를 선택합니다. 앞서 업로드했던 .csv 형식의 파일들이 선택 가능합니다.

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/dataset_dialog/table/select_source_data.png)



### 2. 학습 데이터 분할

데이터셋을 학습, 검증, 테스트 데이터셋으로 분할합니다.

데이터셋은 기본적으로 학습 데이터셋 70%, 검증 데이터셋 20%, 테스트 데이터셋 10%의 비율로 분할되어 있습니다. 

사용자는 슬라이더 바를 움직여 이 비율을 조정할 수 있습니다. 


![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/dataset_dialog/table/split_train_data.png)



### 3. 컬럼 설정

선택한 .csv 파일에서 컬럼 설정을 진행합니다. 

필요한 컬럼 선택, 타입 지정, 전처리 지정 등이 가능합니다.

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/dataset_dialog/table/column_setting.png)



어떤 컬럼을 포함할지, 체크박스를 통해 설정할 수 있습니다.

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/dataset_dialog/table/column_setting_select_column.png)



컬럼마다 유형(데이터 타입)을 지정할 수 있습니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/dataset_dialog/table/column_setting_select_data_type.png)



기본 설정은 'AUTO'로 되어 있으며, 이는 데이터 타입을 자동으로 판단하여 설정합니다. 

사용자가 수동으로 데이터 유형을 선택하려면, string, int, double, date, date_time 중에서 선택할 수 있습니다.

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/dataset_dialog/table/column_setting_select_data_type_2.png)



데이터 변환 설정을 합니다. 

이 설정은 데이터가 범주형 문자일 때만 필요하며, 숫자형 데이터에는 적용할 필요가 없습니다.

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/dataset_dialog/table/column_setting_select_transformation.png)


현재 사용할 수 있는 변환은 라벨 인코딩, 원핫 인코딩 두 가지 방식을 지원하고 있습니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/dataset_dialog/table/column_setting_select_transformation_2.png)



기계 학습에서는 숫자가 아닌 데이터를 사용할 수 없기 때문에, 변환 과정이 필요합니다. 이를 위해 라벨 인코딩이나 원-핫 인코딩과 같은 방법으로 데이터를 변형한 후 학습에 사용합니다.

- **라벨 인코딩(Label Encoding)**: 범주형 변수를 숫자로 변환하는 방법입니다. 각 범주에 고유한 정수를 할당합니다.
- **원-핫 인코딩(One-Hot Encoding)**: 범주형 변수를 이진 벡터로 변환하는 방법입니다. 각 범주는 0과 1로 표현되며, 해당 범주는 1, 나머지는 0으로 표시됩니다.

라벨 인코딩과 원-핫 인코딩의 예시를 들어 설명드리겠습니다.

**라벨 인코딩(Label Encoding)**: 예를 들어, ‘봄’, ‘여름’, ‘가을’, '겨울’이라는 계절 범주가 있다고 가정해봅시다. 

라벨 인코딩을 적용하면 각 계절은 고유한 숫자로 변환됩니다. 예를 들어, '봄’은 0, '여름’은 1, '가을’은 2, '겨울’은 3으로 변환될 수 있습니다.

**원-핫 인코딩(One-Hot Encoding)**: 같은 ‘계절’ 범주에 대해 원-핫 인코딩을 적용하면, 각 계절은 이진 벡터로 표현됩니다.

'봄’은 [1, 0, 0, 0], '여름’은 [0, 1, 0, 0], '가을’은 [0, 0, 1, 0], '겨울’은 [0, 0, 0, 1]로 변환될 수 있습니다.


**라벨 인코딩(Label Encoding)**: 데이터의 크기가 증가하지 않습니다. 단점은 숫자의 크기가 모델에 영향을 줄 수 있어서, 순서가 없는 범주형 데이터에는 적합하지 않을 수 있습니다.
**원-핫 인코딩(One-Hot Encoding)**: 장점은 숫자의 크기가 모델에 영향을 주지 않으며, 순서가 없는 범주형 데이터에 적합합니다. 단점은 데이터의 차원이 늘어나는 문제(차원의 저주)가 있습니다.

이렇게 변환된 데이터는 기계 학습 모델에 입력으로 사용될 수 있습니다. 이러한 인코딩 방법은 범주형 데이터를 처리할 때 매우 중요합니다.



### 4. 상세 정보

데이터셋을 식별할 수 있는 태그를 지정합니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/dataset_dialog/table/set_tag_name_and_creation_button.png)




### 5. 오른쪽 하단의 '생성' 버튼을 클릭하면, 곧바로 데이터셋 페이지로 이동합니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/dataset_dialog/table/creating_dataset.png)






데이터셋 관리 페이지 
------

생성된 데이터셋을 확인할 수 있는 페이지입니다. 

데이터셋의 버전, 이름, 상세 정보, 컬럼 설정 등의 정보 확인, 다운로드, 삭제 등이 가능합니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/dataset_index/table/dataset_index.png)


### 상세 정보 

데이터셋의 버전, 이름, 데이터 개수, 유형, 생성 시간 등을 볼 수 있습니다. 

학습, 검증, 테스트 데이터의 수는 컬럼의 줄(row)을 기준으로 계산됩니다.

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/dataset_index/table/detail_info.png)



### 컬럼 설정 

데이터셋 생성시 설정했던 컬럼 설정 정보를 볼 수 있습니다. 

컬럼 이름, 유형(데이터 타입), 빈값 처리, 변환, 라벨링 그룹(변환시 생긴 라벨과 원본 값)을 볼 수 있습니다. 


![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/dataset_index/table/column_setting.png)




### 새로운 모델 학습

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/dataset_index/image/go_to_training_button.png)  

'새로운 모델 학습' 버튼을 클릭하면, 현재 데이터셋을 사용하여 학습 창이 즉시 열립니다. 

학습에 대한 더 자세한 정보는 ‘학습’ 섹션에서 찾을 수 있습니다




### 버전 목록 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/dataset_index/image/version_list.png)  

데이터셋의 버전 목록을 확인할 수 있으며, 각 버전과 그 생성 시간을 볼 수 있습니다.



### 다운로드 





### 데이터셋 삭제 

데이터 셋을 삭제하고 싶을 때, 오른쪽 하단의 '삭제' 버튼을 클릭합니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/dataset_index/image/dataset_delete_button.png)  

'삭제' 버튼 클릭 시, 확인 창이 나오게 되고, 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/dataset_index/image/delete_confirm_dialog.png)  

'삭제' 버튼을 다시 한번 클릭하면, 곧바로 데이터셋이 삭제됩니다. 









