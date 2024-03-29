## 데이터 관리

이미지 유형 프로젝트의 데이터(이미지)를 관리합니다.

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/image_data_management.png)  


  

## 이미지 추가


'파일 업로드' 버튼을 눌러 이미지를 업로드할 수 있습니다.


파일 업로드 버튼

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/upload/image/file_upload_button.png)  


파일 업로드 버튼을 클릭하면, 이미지 업로드 화면이 나옵니다. 
  
이미지 업로드 창
![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/upload/upload_dialog.png)  


  

'파일 선택' 란을 클릭하거나, 파일을 드래그하여 첨부할 수 있습니다.

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/upload/image/image_upload_dialog_big_0.png)  
  

  

## 폴더 추가


'폴더 선택' 버튼을 눌러 폴더 단위로 이미지를 업로드할 수 있습니다.

열린 파일 탐색창의 폴더를 클릭하거나, 점선 내부 영역으로 드래그하여 첨부할 수 있습니다.
  

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/image_dataset_04.png)  


업로드 버튼을 누르면 업로드가 진행됩니다.

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/upload/image/uploading.png)  



## 압축 파일 업로드 


'압축 파일 선택'버튼을 눌러 zip 형식으로 압축된 이미지를 업로드 할 수 있습니다. 
열린 파일 탐색창의 압축 폴더를 클릭하거나, 점선 내부 영역으로 드래그하여 첨부할 수 있습니다. 


![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/upload/image/upload_setting/zip_file.png)  



압축 파일안에 폴더가 있는 경우, 제일 하위의 폴더까지 내려가 모든 이미지 파일을 가져 옵니다.

예를 들어 sample.zip 파일의 구조가 아래 이미지와 같이, 압축 파일안의 폴더, 폴더 안의 이미지 파일들이 있다면, 


![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/upload/image/upload_setting/zip_file_structure_1.png)  

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/upload/image/upload_setting/zip_file_structure_2.png)  



업로드 창에서는 폴더 제일 아래의 이미지들이 업로드 됩니다. 


![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/upload/image/image_upload_dialog_big_0.png)  


  
## 업로드 설정 


업로드 시 라벨, 태그, 색상, 크기, 파일 이름 설정을 할 수 있습니다. 

업로드 설정 버튼

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/upload/image/upload_setting/upload_option_button.png)  


학습 타입에 따라 업로드 설정이 다릅니다. 


'이미지 분류' 업로드 옵션 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/upload/image/upload_setting/classification_upload_option.png)  



'이미지 객체 탐지' 업로드 옵션 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/upload/image/upload_setting/object_detection_upload_option.png)  





### 라벨 설정 

이미지 분류 타입일 경우, 이미지 파일 하나에 하나의 라벨을 기본적으로 갖습니다. 

그렇기에 이미지 업로드시 파일에 대한 라벨링이 가능합니다. 



![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/upload/image/upload_setting/upload_setting_label.png)  


### 태그 추가 

업로드 설정 버튼에서 '태그 추가' 버튼을 클릭하면 아래와 같은 창이 열립니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/upload/image/upload_setting/upload_setting_add_tag.png)  



이미지를 식별할 수 있는 태그 문구를 적고, 추가 버튼을 클릭하면, 업로드시 태그를 확일 할 수 있습니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/upload/image/upload_setting/tag_setting_1.png)  


업로드가 끝난 후, 이미지에 추가된 태그를 확인 할 수 있습니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/upload/image/upload_setting/tag_setting_2_1.png)  





### 색상 필터 변경 

추가 수정 필요. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/upload/image/upload_setting/change_color_filter.png)  
 


### 전체 크기 조정 

업로드시, 이미지의 크기를 조절하는 설정입니다. 
예를 들어, 가로 세로 28px의 작은 이미지가 있습니다.

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/upload/image/upload_setting/resize_setting/before_resize.png)  



전체 크기 조정 설정을 클릭하면, 아래와 같은 설정 창이 열립니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/upload/image/upload_setting/resizing_the_whole_image.png)  

'전체 크기 조정'의 초기값은 원본 이미지 파일의 크기입니다. 


원하는 너비, 높이를 설정하고 확인 버튼을 누르면,

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/upload/image/upload_setting/resize_setting/check_resize_button.png)  


업로드 창에서, 변화된 크기의 이미지를 볼 수 있습니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/upload/image/upload_setting/resize_setting/after_resize.png)  


업로드 하게 되면, 이미지는 크기가 변화된 상태로 저장됩니다. 

\* 주의, 크기 조정이 되더라도 이미지 해상도는 변하지 않으므로, 확대 시 이미지가 흐릿하게 보일 수 있습니다.


### 파일 이름 규칙 변경 

'파일이름 규칙변경' 버튼을 클릭하면 아래와 같은 창이 열립니다.  

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/upload/image/upload_setting/change_file_naming_conventions.png)  
  

먼저, 이름 규칙의 경우 파일의 이름 앞에 붙일 prefix를 정하는 곳입니다. 

예를 들어, 아래의 이미지와 같이, 이름 규칙 칸에 'mnist' 적게 되면, 예시에서 볼 수 있듯이, 파일명이 'mnist'로 시작하게 됩니다.   

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/upload/image/upload_setting/file_name_rule/file_name_rule_2.png)  


'순번 숫자 단위'는 이름 규칙 뒤에 붙을 숫자의 단위를 의미합니다. 

예를 들어, 아래의 이미지와 같이 순번 숫자 단위에 4를 입력한다면, 

예시에서 볼 수 있듯이, 파일명의 끝은 4자리 숫자로, 하나씩 증가하게 됩니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/upload/image/upload_setting/file_name_rule/file_name_rule_3.png)  



종합적으로,  이름 규칙에 'mnist', 순번 숫자 단위에 '3'을 적게 된다면 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/upload/image/upload_setting/file_name_rule/file_name_rule_1.png)  



업로드 이후 파일들의 이름은 규칙과 같이 아래처럼 변하게 됩니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/upload/image/upload_setting/file_name_rule/file_name_rule_4.png)  






## 비우기

업로드 창에 올렸던 파일들을 비웁니다. 



업로드 창에서 업로드하기 전, 파일들을 내려 업로드 창을 비우고 싶을 때, 두 가지 방법이 있습니다. 

첫 번째, 왼쪽 상단 파일 이름 옆의 'X'버튼을 클릭합니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/upload/image/upload_setting/clear/clear_1.png)  



여러 파일들을 동시에 업로드 한 경우, 하나의 파일만을 내릴 수 있습니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/upload/image/upload_setting/clear/clear_2.png)  



두 번째, 일괄적으로 모든 파일들을 내리고 싶은 경우, 

업로드 설정 버튼을 누른 뒤, 비우기 버튼을 클릭하면, 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/upload/image/upload_setting/clear/clear_button.png)  



일괄적으로 모든 파일들을 내릴 수 있습니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/upload/image/upload_setting/empty.png)  




  

## 이미지 목록


업로드된 이미지의 이름, 라벨(어노테이션), 크기, 생성일 등을 확인할 수 있습니다.

  

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/image_data_management.png)  


오른쪽 상단에서, 업로드된 이미지의 총개수와 총 크기를 확인할 수 있습니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/image_dataset_08.png)  



### 앨범으로 보기 

이미지들을 '앨범'형태로 보고 싶은 경우, 오른쪽 상단의 '앨범형' 버튼을 클릭하시면 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/upload/image/upload_setting/album_1.png)  



아래와 같은 앨범 형태로 이미지 데이터를 볼 수 있습니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/upload/image/upload_setting/album_2.png)  




### 필터

라벨 클래스, 업로드된 날짜 등으로 필터링이 가능하고, 내림차순, 오름차순 정렬이 가능합니다. 


![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/image_list/filtering.png)  



  


### 오른쪽 마우스 클릭 옵션

이미지 오른쪽 마우스 클릭시, 다양한 설정을 할 수 있습니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/image_list/right_click/rigth_click_option.png)  


#### 상세 정보

이미지의 파일이름, 가로 세로 길이, 크기, 업로드 날짜, 라벨링 내역등의 상세 정보를 볼 수 있습니다.  


![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/image_list/right_click/file_detail_info.png)  


#### 라벨링 

라벨링 페이지로 넘어 가게 됩니다. 

상세한 설명은 가이드의 라벨링 작업을 참고해 주시기 바랍니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/image_list/right_click/labeling.png)  


#### 다운로드 

파일을 다운로드 할 수 있는 창이 나옵니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/image_list/right_click/download_file.png)  

'다운로드' 버튼 클릭 시, 이미지 파일이 다운로드 됩니다. 


#### 삭제 

파일 삭제를 할 수 있는 창이 나옵니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/image_list/right_click/delete_image.png)  

\* 주의. '삭제' 버튼 클릭 시, 별도의 확인 창 없이, 곧바로 파일이 삭제됩니다. 






### 이미지 선택

데이터 행을 클릭하여 라벨을 바꾸거나, 다운로드, 삭제할 수 있습니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/image_list/selected_image.png)  


#### 다운로드

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/image_list/select_download.png)  

다운로드 옵션에는 

이미지만 다운, Json 포맷, Coco Json 포맷, Pascal VOC 포맷 등이 있습니다.

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/image_list/download_option.png)  



  






## 데이터셋 생성

새로운 데이터셋을 생성합니다. 


### 원천 데이터 

데이터셋으로 만들 원천 데이터를 확인 합니다. 

라벨별 이미지 수, 총 이미지 개수등을 확인 할 수 있습니다. 


![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/dataset_dialog/image/source_data.png)  


### 학습 데이터 분할 

원천데이터를 학습데이터, 검증데이터, 테스트데이터 셋으로 구분합니다. 

바를 움직여, 비율을 조정할 수 있습니다. 

조정된 비율에 맞는 이미지 개수가 데이터셋 이름 앞에 보입니다. 


![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/dataset_dialog/image/split_data.png)  


### 전처리 설정 

데이터셋을 만들 때, 이미지에 전처리 설정을 할 수 있습니다.

가능한 설정에는 리사이즈, 그레이 스케일링 등이 있습니다. 

리사이즈 옵션을 조정하면, 바뀐 이미지를 바로 볼 수 있습니다. 


![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/dataset_dialog/image/preprocessing_setting.png)  


#### 그레이 스케일링

그레이 스케일링은 각 픽셀의 값이 빛의 양을 나타내는 하나의 샘플인 이미지를 가리키며, 이는 오직 광도의 정보만을 전달합니다. 

이는 색상(rgb 채널) 정보가 전달되지 않는다는 것을 의미하며, 결과적으로 이미지가 흑백으로 변환됩니다.

그레이 스케일링의 주요 장점 중 하나는 계산 효율성입니다. 색상 정보를 제거함으로써, 데이터의 복잡성이 줄어들고 처리 속도가 빨라집니다. 

또한, 그레이 스케일링은 특정 애플리케이션에서 더 나은 결과를 가져올 수 있습니다. 

예를 들어, 텍스트 인식이나 얼굴 인식과 같은 작업에서는 색상 정보가 중요하지 않을 수 있습니다.

그러나 주의해야 할 점은, 색상 정보가 중요한 경우에는 그레이 스케일링을 사용하면 모델의 성능이 감소할 수 있다는 것입니다. 

따라서, 그레이 스케일링의 사용은 문제의 특성과 요구 사항에 따라 달라집니다.



before 그레이 스케일링 


![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/dataset_dialog/image/gray_scale/gray_scale_1.png) 


after 그레이 스케일링


![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/dataset_dialog/image/gray_scale/gray_scale_2.png) 




### 증강 설정 

이미지의 개수가 부족할 경우, 데이터 수를 증가시키는 증강 옵션을 설정 할 수 있습니다. 

가능한 증강 옵션에는 밝기 조정, 자르기, 회전, 반전(상, 하, 좌, 우)등이 있습니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/dataset_dialog/image/augmented_setting.png)  


#### 밝기(brightness) 조정

데이터 증강의 한 가지 방법으로, 이미지의 밝기를 조장이 있습니다. 

이는 이미지의 밝기 수준을 조정하여 다양한 조명 조건에서의 모델의 견고성을 향상시키는 데 도움이 될 수 있습니다.

밝기 조정의 정도는 일반적으로 0.1에서 2.0 사이의 범위에서 설정할 수 있습니다. 

이 값이 0에 가까울수록 이미지는 점점 어두워지며, 반대로 이 값이 1.0을 초과하면 이미지는 점점 밝아집니다. 

이렇게 함으로써, 우리는 동일한 이미지에 대해 다양한 밝기 수준을 가진 새로운 학습 샘플을 생성할 수 있습니다. 

이는 모델이 다양한 조명 조건에 대해 더 잘 일반화되도록 돕습니다.




밝기 조정 전 이미지 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/dataset_dialog/image/brightness/brightness_0.png)  



밝기 0.1 이미지 
![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/dataset_dialog/image/brightness/brightness_1.png)  



밝기 2.0 이미지 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/dataset_dialog/image/brightness/brightness_2.png)  




#### 자르기(crop)

특정 부분을 잘라내는 작업을 crop이라고 말합니다.

“crop” 작업의 정도는 0과 1 사이의 값으로 설정됩니다. 이 값이 0에 가까울수록 이미지의 크기는 거의 변하지 않으며, 반대로 이 값이 1에 가까울수록 이미지의 크기는 크게 줄어듭니다. 

이렇게 조절함으로써, 원본 이미지의 다양한 부분을 강조하거나 제거하여 새로운 학습 샘플을 생성할 수 있습니다. 

이는 모델이 다양한 시나리오에 대해 더 잘 일반화되도록 돕습니다.



before ceop

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/dataset_dialog/image/crop/crop_0.png)  


crop 0.3

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/dataset_dialog/image/crop/crop_1.png)  




#### 회전(rotation)

이미지를 특정 각도로 회전시키는 것을 의미하며, 

회전은 일반적으로 이미지의 중심을 기준으로 수행되며, 회전 각도는 0도에서 +90도 사이로 설정됩니다. 

이렇게 조절함으로써, 원본 이미지를 다양한 각도로 회전시켜 새로운 학습 샘플을 생성할 수 있습니다. 

이는 모델이 다양한 방향에서 객체를 인식하는 능력을 향상시키는 데 도움이 됩니다


before rotation

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/dataset_dialog/image/rotation/rotation_0.png)  


after rotation 45도

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/dataset_dialog/image/rotation/rotation_1.png)  



#### 뒤집기(flip)

"이미지 증강(augmentation)"의 한 방법으로 "뒤집기(flip)"라는 작업이 있습니다. 

이는 이미지를 수평(horizon) 또는 수직(vertical) 방향으로 뒤집는 것을 의미하며, 이를 통해 모델이 다양한 방향에서 객체를 인식하는 능력을 향상시킬 수 있습니다.

수평 뒤집기(Horizontal Flip): 이미지를 수평축을 기준으로 뒤집습니다. 즉, 이미지의 왼쪽과 오른쪽을 바꿉니다. 이는 거울에 비친 것처럼 이미지를 반전시킵니다.

수직 뒤집기(Vertical Flip): 이미지를 수직축을 기준으로 뒤집습니다. 즉, 이미지의 상단과 하단을 바꿉니다.

이러한 뒤집기 작업은 이미지 데이터셋의 다양성을 증가시키고, 모델이 이미지의 방향에 덜 민감하게 만들어 일반화 성능을 향상시키는 데 도움이 됩니다. 

그러나 주의해야 할 점은, 뒤집기가 문제의 특성에 따라 적절하지 않을 수 있다는 것입니다. 

예를 들어, 텍스트 인식이나 자연의 방향성을 가진 이미지(예: 선인장의 성장 방향)에서는 뒤집기가 부적절할 수 있습니다



before horizon 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/dataset_dialog/image/flip/horizon_0.png)  

after horizon

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/dataset_dialog/image/flip/horizon_1.png)  



before vertical

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/dataset_dialog/image/flip/vertical_0.png)  


after vertical 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/dataset_dialog/image/flip/vertical_1.png)  



### 상세 정보

만들어진 데이터셋을 구분할 태그를 설정할 수 있습니다.  

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/dataset_dialog/image/dataset_tag_setting.png)  


### 데이터셋 생성 버튼 

데이터셋 생성 창 오른쪽 하단에 있는 '생성' 버튼을 클릭하면, 데이터셋이 생성됩니다.  

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/dataset_dialog/image/dataset_generate_button.png)  



'데이터셋 생성'을 클릭하면, 데이터셋이 생성되고, 데이터셋 페이지로 이동됩니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/dataset_index/image/dataset_index_gernerating.png)  




## 데이터셋

데이터셋이 생성된 후, 데이터셋 인덱스 페이지입니다. 

데이터셋의 이름, 버전, 생성일, 데이터 분할 비율 등의 상세한 정보를 볼 수 있습니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/dataset_index/image/dataset_index_after_gernerate.png) 

하나씩 알아보겠습니다. 



### 이름 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/dataset_index/image/dataset_version_name.png)  

데이터셋의 버전, 이름(데이터셋 생성 창에서 설정했던 태그) 등을 볼 수 있습니다.  


### 상세 정보

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/dataset_index/image/detail_info.png)  

데이터셋의 상세 정보를 볼 수 있습니다. 

버전, 이름, 데이터 개수, 데이터 크기, 학습 유형, 생성 시간, 

학습, 검증, 테스트 데이터 수 등을 볼 수 있습니다.  



### 학습 데이터 분할 비율 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/dataset_index/image/train_data_split_ratio.png)  

학습, 검증, 테스트 데이터셋이 어떻게 분할되었는지 한눈에 볼 수 있습니다. 

왼쪽 도넛 차트는 각 데이터셋의 분할 비율을 보여주며, 

오른쪽은 각 학습, 검증, 테스트 세트가 어떻게 구성되었는지 상세하게 나타냅니다. 

라벨별 분할 개수와 구성 이미지 등을 통해 데이터의 분포를 쉽게 이해할 수 있습니다.




### 전처리 설정 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/dataset_index/image/preprocessing_setting.png)  

데이터셋 생성 시 설정했던, 전처리 설정에 대한 정보를 볼 수 있습니다. 



### 증강 설정 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/dataset_index/image/augementation_setting.png)  

데이터셋 생성 시 설정했던, 증강 설정에 대한 정보를 볼 수 있습니다. 



### 새로운 모델 학습

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/dataset_index/image/go_to_training_button.png)  

'새로운 모델 학습' 버튼을 클릭하면, 현재 데이터셋을 사용하여 학습 창이 즉시 열립니다. 

학습에 대한 더 자세한 정보는 ‘학습’ 섹션에서 찾을 수 있습니다




### 버전 목록 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/dataset_index/image/version_list.png)  

데이터셋의 버전 목록을 확인할 수 있으며, 각 버전과 그 생성 시간을 볼 수 있습니다.



### 다운로드 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/dataset_index/image/download/dataset_download_button.png)  

'다운로드' 버튼 클릭 시, 데이터셋을 바로 다운로드 할 수 있습니다. 


다운로드된 데이터셋은 zip 형식으로 압축되어 있습니다.

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/dataset_index/image/download/downloaded_dataset_zip.png)  

압축을 풀어주면, 학습, 검증, 테스트 폴더가 보입니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/dataset_index/image/download/extracted_dataset.png)

각 폴더 안에는, 라벨별로 구분된 폴더가 보입니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/dataset_index/image/download/extracted_dataset_2.png)


라벨 폴더 안에는 이미지 파일과 어노테이션 파일이 들어가 있습니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/dataset_index/image/download/extracted_dataset_3.png)


xml 형식의 어노테이션 파일을 열게 되면 다음과 같은 구조를 볼 수 있습니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/dataset_index/image/download/annotation.png)


브릿지에서는 기본적으로 Pascal VOC 형식으로 주석(annotation)에 관한 정보를 저장합니다. 

#### Pascal VOC

Pascal VOC는 이미지 주석을 저장하기 위한 형식으로, 객체 탐지 데이터셋에 대한 주석을 저장하고, 다양한 주석 편집기와 도구에서 사용됩니다. 

이 형식은 원래 Visual Object Challenge (VOC)를 위해 만들어졌지만, 이제는 객체 탐지 레이블의 일반적인 교환 형식이 되었습니다.

Pascal VOC 형식에서는 각 이미지에 대해 이미지 세부 정보, 바운딩 박스 세부 정보, 클래스, 회전 및 기타 데이터를 포함하는 XML 주석 파일이 있습니다



### 데이터셋 삭제 

데이터 셋을 삭제하고 싶을 때, 오른쪽 하단의 '삭제' 버튼을 클릭합니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/dataset_index/image/dataset_delete_button.png)  

'삭제' 버튼 클릭 시, 확인 창이 나오게 되고, 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/dataset/dataset_index/image/delete_confirm_dialog.png)  

'삭제' 버튼을 다시 한번 클릭하면, 곧바로 데이터셋이 삭제됩니다. 















