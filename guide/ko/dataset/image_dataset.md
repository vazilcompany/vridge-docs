데이터 관리
------

이미지 유형 프로젝트의 데이터(이미지)를 관리합니다.

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/image_data_management.png)  


  

이미지 추가
------


'파일 업로드' 버튼을 눌러 이미지를 업로드할 수 있습니다.


파일 업로드 버튼

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/upload/image/file_upload_button.png)  


파일 업로드 버튼을 클릭하면, 이미지 업로드 화면이 나옵니다. 
  
이미지 업로드 창
![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/upload/upload_dialog.png)  


  

'파일 선택' 란을 클릭하거나, 파일을 드래그하여 첨부할 수 있습니다.

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/upload/image/image_upload_dialog_big_0.png)  
  

  

폴더 추가
------


'폴더 선택' 버튼을 눌러 폴더 단위로 이미지를 업로드할 수 있습니다.

열린 파일 탐색창의 폴더를 클릭하거나, 점선 내부 영역으로 드래그하여 첨부할 수 있습니다.
  

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/image_dataset_04.png)  


업로드 버튼을 누르면 업로드가 진행됩니다.

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/upload/image/uploading.png)  



압축 파일 업로드 
------


'압축 파일 선택'버튼을 눌러 zip 형식으로 압축된 이미지를 업로드 할 수 있습니다. 
열린 파일 탐색창의 압축 폴더를 클릭하거나, 점선 내부 영역으로 드래그하여 첨부할 수 있습니다. 


![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/upload/image/upload_setting/zip_file.png)  



압축 파일안에 폴더가 있는 경우, 제일 하위의 폴더까지 내려가 모든 이미지 파일을 가져 옵니다.

예를 들어 sample.zip 파일의 구조가 아래 이미지와 같이, 압축 파일안의 폴더, 폴더 안의 이미지 파일들이 있다면, 


![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/upload/image/upload_setting/zip_file_structure_1.png)  

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/upload/image/upload_setting/zip_file_structure_2.png)  



업로드 창에서는 폴더 제일 아래의 이미지들이 업로드 됩니다. 


![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/upload/image/image_upload_dialog_big_0.png)  


  
업로드 설정 
------

업로드 시 라벨, 태그, 색상, 크기, 파일 이름 설정을 할 수 있습니다. 

업로드 설정 버튼

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/upload/image/upload_setting/upload_option_button.png)  


학습 타입에 따라 업로드 설정이 다릅니다. 


'이미지 분류' 업로드 옵션 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/upload/image/upload_setting/classification_upload_option.png)  



'이미지 객체 탐지' 업로드 옵션 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/upload/image/upload_setting/object_detection_upload_option.png)  





### 라벨 설정 

이미지 분류 타입일 경우, 이미지 파일 하나에 하나의 라벨을 기본적으로 갖습니다. 

그렇기에 이미지 업로드시 파일에 대한 라벨링이 가능합니다. 



![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/upload/image/upload_setting/upload_setting_label.png)  


### 태그 추가 

업로드 설정 버튼에서 '태그 추가' 버튼을 클릭하면 아래와 같은 창이 열립니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/upload/image/upload_setting/upload_setting_add_tag.png)  



이미지를 식별할 수 있는 태그 문구를 적고, 추가 버튼을 클릭하면, 업로드시 태그를 확일 할 수 있습니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/upload/image/upload_setting/tag_setting_1.png)  


업로드가 끝난 후, 이미지에 추가된 태그를 확인 할 수 있습니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/upload/image/upload_setting/tag_setting_2_1.png)  





### 색상 필터 변경 

추가 수정 필요. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/upload/image/upload_setting/change_color_filter.png)  
 


### 전체 크기 조정 

업로드시, 이미지의 크기를 조절하는 설정입니다. 
예를 들어, 가로 세로 28px의 작은 이미지가 있습니다.

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/upload/image/upload_setting/resize_setting/before_resize.png)  



전체 크기 조정 설정을 클릭하면, 아래와 같은 설정 창이 열립니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/upload/image/upload_setting/resizing_the_whole_image.png)  

'전체 크기 조정'의 초기값은 원본 이미지 파일의 크기입니다. 


원하는 너비, 높이를 설정하고 확인 버튼을 누르면,

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/upload/image/upload_setting/resize_setting/check_resize_button.png)  


업로드 창에서, 변화된 크기의 이미지를 볼 수 있습니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/upload/image/upload_setting/resize_setting/after_resize.png)  


업로드 하게 되면, 이미지는 크기가 변화된 상태로 저장됩니다. 

\* 주의, 크기 조정이 되더라도 이미지 해상도는 변하지 않으므로, 확대 시 이미지가 흐릿하게 보일 수 있습니다.


### 파일 이름 규칙 변경 

'파일이름 규칙변경' 버튼을 클릭하면 아래와 같은 창이 열립니다.  

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/upload/image/upload_setting/change_file_naming_conventions.png)  
  

먼저, 이름 규칙의 경우 파일의 이름 앞에 붙일 prefix를 정하는 곳입니다. 

예를 들어, 아래의 이미지와 같이, 이름 규칙 칸에 'mnist' 적게 되면, 예시에서 볼 수 있듯이, 파일명이 'mnist'로 시작하게 됩니다.   

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/upload/image/upload_setting/file_name_rule/file_name_rule_2.png)  


'순번 숫자 단위'는 이름 규칙 뒤에 붙을 숫자의 단위를 의미합니다. 

예를 들어, 아래의 이미지와 같이 순번 숫자 단위에 4를 입력한다면, 

예시에서 볼 수 있듯이, 파일명의 끝은 4자리 숫자로, 하나씩 증가하게 됩니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/upload/image/upload_setting/file_name_rule/file_name_rule_3.png)  



종합적으로,  이름 규칙에 'mnist', 순번 숫자 단위에 '3'을 적게 된다면 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/upload/image/upload_setting/file_name_rule/file_name_rule_1.png)  



업로드 이후 파일들의 이름은 규칙과 같이 아래처럼 변하게 됩니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/upload/image/upload_setting/file_name_rule/file_name_rule_4.png)  






비우기
------

업로드 창에 올렸던 파일들을 비웁니다. 



업로드 창에서 업로드하기 전, 파일들을 내려 업로드 창을 비우고 싶을 때, 두 가지 방법이 있습니다. 

첫 번째, 왼쪽 상단 파일 이름 옆의 'X'버튼을 클릭합니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/upload/image/upload_setting/clear/clear_1.png)  



여러 파일들을 동시에 업로드 한 경우, 하나의 파일만을 내릴 수 있습니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/upload/image/upload_setting/clear/clear_2.png)  



두 번째, 일괄적으로 모든 파일들을 내리고 싶은 경우, 

업로드 설정 버튼을 누른 뒤, 비우기 버튼을 클릭하면, 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/upload/image/upload_setting/clear/clear_button.png)  



일괄적으로 모든 파일들을 내릴 수 있습니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/upload/image/upload_setting/empty.png)  




  

이미지 목록
------


업로드된 이미지의 이름, 분류, 크기, 생성 날짜를 확인할 수 있습니다.

  

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/image_data_management.png)  


업로드된 이미지 개수와 파일 크기를 확인할 수 있습니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/image_dataset_08.png)  



### 필터

라벨 클래스, 업로드된 날짜 등으로 필터링이 가능하고, 내림차순, 오름차순 정렬이 가능합니다. 


![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/image_list/filtering.png)  

  


### 오른쪽 마우스 클릭 옵션

이미지 오른쪽 마우스 클릭시, 다양한 설정을 할 수 있습니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/image_list/right_click/rigth_click_option.png)  


#### 상세 정보

이미지의 파일이름, 가로 세로 길이, 크기, 업로드 날짜, 라벨링 내역등의 상세 정보를 볼 수 있습니다.  


![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/image_list/right_click/file_detail_info.png)  


#### 라벨링 

라벨링 페이지로 넘어 가게 됩니다. 

상세한 설명은 가이드의 라벨링 작업을 참고해 주시기 바랍니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/image_list/right_click/labeling.png)  


#### 다운로드 

파일을 다운로드 할 수 있는 창이 나옵니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/image_list/right_click/download_file.png)  


#### 삭제 

파일 삭제를 할 수 있는 창이 나옵니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/image_list/right_click/delete_image.png)  






### 이미지 선택

데이터 행을 클릭하여 라벨을 바꾸거나, 다운로드, 삭제할 수 있습니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/image_list/selected_image.png)  


#### 다운로드

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/image_list/select_download.png)  

다운로드 옵션에는 

이미지만 다운, Json 포맷, Coco Json 포맷, Pascal VOC 포맷 등이 있습니다.

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/image_list/download_option.png)  



  






데이터셋 생성
------
새로운 데이터셋을 생성합니다. 


### 원천 데이터 

데이터셋으로 만들 원천 데이터를 확인 합니다. 

라벨별 이미지 수, 총 이미지 개수등을 확인 할 수 있습니다. 


![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/dataset_dialog/image/source_data.png)  


### 학습 데이터 분할 

원천데이터를 학습데이터, 검증데이터, 테스트데이터 셋으로 구분합니다. 

바를 움직여, 비율을 조정할 수 있습니다. 

조정된 비율에 맞는 이미지 개수가 데이터셋 이름 앞에 보입니다. 


![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/dataset_dialog/image/split_data.png)  


### 전처리 설정 

데이터셋을 만들 떄, 이미지에 전처리 설정을 할 수 있습니다.

가능한 설정에는 리사이즈, 그레이스케일링 등이 있습니다. 

리사이즈 옵션을 조정하면, 바뀐 이미지를 바로 볼 수 있습니다. 


![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/dataset_dialog/image/preprocessing_setting.png)  


### 증강 설정 

이미지의 개수가 부족할 경우, 데이터 수를 증가시키는 증강 옵션을 설정 할 수 있습니다. 

가능한 증강 옵션에는 밝기 조정, 자르기, 회전, 반전(상, 하, 좌, 우)등이 있습니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/dataset_dialog/image/augmented_setting.png)  


### 상세 정보

만들어진 데이터셋을 구분할 태그를 설정할 수 있습니다.  

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/guide/img/dataset/dataset_dialog/image/detail_info.png)  


### 데이터셋 생성 버튼 


### 데이터 생성 후 페이지 이동 

### 데이터셋 페이지에서 확인 할 수 있는 것들에 대한 설명 










