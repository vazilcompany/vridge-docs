이미지 유형 프로젝트의 라벨링 작업 인터페이스를 설명합니다.

  

## 화면 구성


라벨링 공간은 상단의 작업 상태 바, 왼쪽의 작업 도구 바, 오른쪽의 작업 테이블 그리고 메인 작업 공간으로 구성됩니다.

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/interface_explanation_index.png)  

  
## 작업 상태 바

라벨링 공간의 상단 작업 상태 바를 통해, 전체 라벨링 현황, 프로젝트 이름, 현재 이미지 파일 이름 등을 알 수 있습니다. 


좌우 버튼으로 이전 데이터, 다음 데이터를 불러올 수 있고

현재 프로젝트의 라벨링 진행률을 확인할 수 있습니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/interface_1_task_progress.png)  


프로젝트 이름과 현재 선택된 이미지 파일명을 확인할 수 있습니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/interface_2_project_image_name.png)  



  

## 작업 도구 바


![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/interface_9_labeling_tool_bar.png)  

( 위에서 아래로 차례대로 1~11 )

1.  라벨 선택
2.  이미지 이동
3.  사각형 박스 - 라벨링 도구  
4.  다각형 - 라벨링 도구
5.  실행 취소(undo)
6.  다시 실행 (redo)
7.  이미지 확대
8.  이미지 축소
9.  대비 조절
10. 명도 조절
11. 어시스트 AI




### 1. 라벨 선택

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/labeling_tool/select_1.png)

작업 도구 바의 라벨 선택 아이콘을 선택합니다. 
(선택하면, 파란색으로 아이콘이 변경됩니다.)

이제, (이미지의) 라벨을 선택합니다. (라벨링을 어떻게 하는지는 3. 사각형 박스 또는, 이미지 분류 or 이미지 객체 탐지를 참고해 주세요.)


![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/labeling_tool/select_2.png)

라벨을 선택하면, 어떤 라벨인지를 알려주는 작은 창이 라벨 바로 밑에 나옵니다. 


![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/labeling_tool/select_2.png)

또한, 오른쪽 상세 정보 창에 어떤 라벨이 현재 선택되었는지를 작은 점으로 표시합니다. 



![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/labeling_tool/select_4.png)

라벨이 여러 개 있는 경우, 다른 라벨을 선택하여, 라벨을 바꿀 수 있고, 삭제 또한 가능합니다.





### 2. 이미지 이동 



![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/labeling_tool/move_1.png)

이동 아이콘을 선택하거나 키보드 W키를 사용하면, 이미지를 이동시킬 수 있습니다. 


![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/labeling_tool/move_2.png)

화면 정중앙에 있던 이미지를 옮긴 이후의 모습입니다. 




### 3. 사각형 박스 - 라벨링

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/labeling_tool/rectangle_label_box_1.png)

사각형 박스 아이콘을 클릭하거나 키보드 E키를 누르면, 



![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/labeling_tool/rectangle_label_box_2.png)

사각형 라벨링을 할 수 있게 마우스 포인터에 삽자가가 표시됩니다. 



![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/labeling_tool/rectangle_label_box_4.png)

마우스를 클릭한 상태로 상,하,좌,우 드래그 앤 드랍을 하면, 시작점 부터 끝점을 사각형의 대각선 꼭지점으로 하는 라벨이 생성됩니다. 

또한, 오른쪽 상세 정보 창에 현재 라벨링 작업이 추가된 것이 보입니다. 



### 4. 다각형 - 라벨링

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/labeling_tool/Polygon_1.png)

다각형 아이콘을 클릭하면, 사각형 박스 모양이 아니라, 다각형으로 라벨링 할 수 있습니다.



![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/labeling_tool/Polygon_2.png)

마우스 포인트를 찍으며 이동하면, 찍힌 포인트를 꼭지점으로 하는 다각형이 그려집니다. 





### 5. 실행 취소(undo)


![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/labeling_tool/Polygon_2.png)


라벨링 작업 중에 취소하려면 실행 취소 아이콘을 클릭하거나, Ctrl + z 키보드 단축키를 사용용하여 실행 취소를 할 수 있습니다.


![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/labeling_tool/undo_2.png)

실행 취소 전 이미지


![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/labeling_tool/undo_3.png)

실행 취소 실행 후 이미지 

라벨링이 사라진 것을 볼 수 있습니다. 




### 6. 다시 실행 (redo)


![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/labeling_tool/redo_1.png)


다시 실행 아이콘을 클릭하거나, Ctrl + y 키보드 단축키를 사용하여 다시 실행할 수 있습니다.


![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/labeling_tool/redo_2.png)


아까 실행 취소를 한 이미지에서 다시 실행을 할 경우, 


![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/labeling_tool/redo_3.png)


이미지를 보면, 사라졌던 바운딩 박스가 다시 나타나는 것을 확인할 수 있습니다. 또한, 오른쪽 상세 정보 창에는 라벨 기록이 표시됩니다.





### 7,8 이미지 확대 및 이미지 축소


![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/labeling_tool/zoom_in_1.png)

줌 인 아이콘을 클릭하거나, 마우스 휠을 위로 돌려서 이미지를 확대할 수 있습니다.


![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/labeling_tool/zoom_out_1.png)

줌 아웃 아이콘을 선택하거나, 마우스 휠을 아래로 돌려서 이미지를 축소할 수 있습니다.  




### 9.  대비 조절

대비: 대비는 둘을 비교했을 때의 차이를 의미합니다. 예를 들어, 흰색과 검은색은 명도 대비가 크고, 노란색과 보라색은 서로 반대쪽에 있는 보색이니 색상 대비가 큽니다. 

이미지에서 대비는 밝은 영역과 어두운 영역 사이의 차이를 나타냅니다

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/labeling_tool/contrast_1.png)


대비 아이콘을 클릭하거나, Alt + 또는 Alt - 키보드 단축키를 사용하여 대비를 조절할 수 있습니다.


대비 조절 전 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/labeling_tool/contrast_2.png)


대비 0.5로 조절 한 후

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/labeling_tool/contrast_3_05.png)


대비 5로 조절 한 후 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/labeling_tool/contrast_4_5.png)




### 10. 명도 조절

명도: 명도는 색상의 밝고 어두운 정도를 의미합니다. 흰색에 가까울수록 명도가 높아지고, 검은색에 가까울수록 명도는 낮아집니다

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/labeling_tool/brightness_1.png)

명도 아이콘을 클릭하거나, Ctrl + 또는 Ctrl - 키보드 단축키를 사용하여 명도를 조절할 수 있습니다.


명도 0.5

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/labeling_tool/brightness_2_05.png)


명도 5

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/labeling_tool/brightness_3_5.png)



### 11. 어시스트 AI

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/autolabeling/autolabeling_1_assistAI.png)


어시스트 AI 아이콘을 클릭하여 어시스트 AI를 활성화할 수 있습니다.

어시스트 AI가 활성화된 후에는 '자동 라벨링’을 실행할 수 있습니다.



어시스트 AI가 비활성화 상태라면, 아이콘은 파란색이 아닙니다.

반면에, 어시스트 AI가 활성화 상태라면, 아이콘은 파란색으로 표시됩니다.


![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/autolabeling/autolabeling_2_assistAI_dialog.png)


어시스트 AI가 활성화 되지 않았을 경우의 어시스트 AI 설정 창입니다. 

연결된 웹 포인트가 보이지 않고, 인공지능 모델 또한 화면에 표시되지 않습니다. 




![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/autolabeling/autolabeling_3_go_to_project_setting.png)

어시스트 AI는 프로젝트 설정 > 라벨 설정 > 어시스트 AI 설정에서 설정 할 수 있습니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/autolabeling/autolabeling_3_assiatAI_setting_1.png)

어시스트 AI 설정 화면. 


![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/autolabeling/autolabeling_3_assiatAI_setting_2.png)

모델이 배포되어 있는 포인트가 있을 경우, 위의 이미지와 같이 포인트를 설정한 후, 저장 할 수 있습니다. 

모델이 배포되어 있는 포인트가 없을 경우, 먼저 모델을 배포해 주시기 바랍니다. 

모델 배포는 사용자 가이드의 '모델 배포' 섹션을 참고해 주시기 바랍니다. 



어시스트 AI를 설정한 후에는 라벨링 공간의 작업 도구 바에서 ‘어시스트 AI’ 아이콘의 색이 파란색으로 변경되는 것을 확인할 수 있습니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/autolabeling/autolabeling_5.png)



이 아이콘을 클릭하면, 업데이트된 어시스트 AI 설정 창이 표시됩니다. 

여기에는 프로젝트 설정에서 지정한 포인트와 모델 등의 정보가 표시됩니다. 

또한, 활성화 또는 비활성화 버튼을 클릭하여 어시스트 AI의 활성 여부를 변경할 수 있습니다.

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/autolabeling/autolabeling_6.png)









## 자동 라벨링 


어시스트 AI를 설정하고 활성화한 후에는 ‘자동 라벨링’ 기능을 사용할 수 있습니다. 

이 기능은 사전에 학습된 모델을 사용하여 라벨링 작업을 수행합니다. 

어시스트 AI에 설정된 모델을 통해 라벨링이 진행됩니다.


라벨링 공간의 우측 상단에서 ‘자동 라벨링’ 버튼을 확인할 수 있습니다.

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/autolabeling/autolabeling_7_autolabeling_button.png)


‘자동 라벨링’ 버튼을 클릭하면 새 창이 나타납니다.

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/autolabeling/autolabeling_4.png)


‘시작’ 버튼을 클릭하면 자동 라벨링이 시작됩니다

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/autolabeling/autolabeling_8.png)




## 작업 테이블

### 상세 정보

오른쪽 상단 상세 정보를 클릭하면, 라벨링 기록에 대한 상세한 정보를 볼 수 있습니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/interface_4_detail_info.png)



느낌표 아이콘에 마우스 포인트를 올려놓으면, 라벨에 대한 상세 정보를 볼 수 있습니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/detail_info/labeling_tool_detail_info_1.png)



숨김 아이콘을 클릭하면, 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/detail_info/labeling_tool_detail_info_2.png)


라벨이 숨겨집니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/detail_info/labeling_tool_detail_info_3.png)


휴지통 아이콘을 클릭하면, 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/detail_info/labeling_tool_detail_info_4.png)


라벨 삭제를 재확인하는 창이 나옵니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/detail_info/labeling_tool_detail_info_5.png)

삭제 버튼을 누르면,

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/detail_info/labeling_tool_detail_info_6.png)


라벨이 삭제된 것을 확인할 수 있습니다. 



### 작업 기록 

오른쪽 상단 작업 기록을 클릭하면, 진행되었던 직업들에 대한 기록을 볼 수 있습니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/interface_5_work_history.png)


느낌표 아이콘을 클릭하면, 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/work_history/interface_5_work_hostorypng_2.png)


작업 기록에 대한 상세 정보를 볼 수 있습니다.  

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/work_history/interface_5_work_hostorypng_3.png)


되돌리기 아이콘을 클릭하면, 되돌림 여부를 확인하는 창이 나옵니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/work_history/interface_5_work_hostorypng_4.png)


되돌리기 전 이미지 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/work_history/interface_5_work_hostorypng_7.png)


되돌리기 후 이미지 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/work_history/interface_5_work_hostorypng_10.png)


삭제 아이콘을 클릭하면, 되돌리기와 마찬가지로 라벨을 취소할 수 있습니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/work_history/interface_5_work_hostorypng_8.png)




### 라벨 클래스 

라벨을 변경, 관리할 수 있는 라벨 클래스 공간입니다. 


라벨 클래스 바로 아래에 있는 라벨들을 클릭하면, 사각형 박스를 클릭 시 기본 라벨이 바뀌게 됩니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/label_class/label_class_1.png)



라벨 관리 버튼을 클릭하면, 라벨 관리 창이 나옵니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/label_class/label_class_2.png)



새로운 라벨을 추가하거나, 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/label_class/label_class_3.png)

라벨 추가 완료 후 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/label_class/label_class_3_1.png)


라벨 목록에 있는 라벨들을 클릭해, 기존 라벨을 수정할 수 있습니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/label_class/label_class_4.png)






### 목록

라벨링 되지 않은 데이터 목록(Todo)과 라벨링 된 데이터 목록(Done)입니다.

목록에서 데이터를 선택해 이동할 수 있습니다. 

라벨링 작업은 실시간 동시 작업이 가능하며,

같은 데이터에 대해 동시 작업은 불가능합니다.

이미 작업 중인 데이터를 선택할 경우 '이미 다른 멤버가 작업 중입니다.'라는 메세지가 나타납니다.

라벨링이 완료된 데이터는 옅은 글씨로 보이게 됩니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/list/list_1.png)  



필터링이 가능합니다. 

'미작업만 보기' 버튼을 클릭하면, 미완료 작업만 필터링해 볼 수 있고, 

필터 아이콘을 클릭하면 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/list/list_2.png)  

새로운 창이 열립니다. 

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling/image/interface_explanation/list/list_3.png)  

라벨, 태그로 필터링 가능하며, 시간순 정렬을 설정할 수 있습니다. 




### 작업자

해당 프로젝트에서 현재 라벨링 작업 중인 멤버 목록입니다.

작업 중인 멤버를 확인할 수 있습니다.

![img1](https://raw.githubusercontent.com/vazilcompany/vridge-docs/main/img/labeling_tools/labeling_tools_image/interface_06.png)  




