# **영상처리 OpenCV 기말 프로젝트👩🏻‍💻📸**
영상처리 강의 중에 배웠던 내용을 토대로 OpenCV 라이브러리를 활용하여 사진 앨범 만드는 기말 프로젝트입니다.



## **🌟 프로젝트 소개**
기존의 정형화된 그리드 형식 앨범에서 벗어나, 사용자가 자유롭게 이미지를 배치하고 편집할 수 있는 이미지 콜라주 애플리케이션을 개발하였습니다. 다양한 조작 기능을 통해 사용자의 편의성과 창의적인 편집 경험을 제공할 수 있도록 구현하였습니다.



## **❣️ 결과 화면**
###### 발표자료도 함께 첨부하였으니, 참고해주시기 바랍니다 :)

<img width="1470" alt="스크린샷 2025-03-27 오후 5 47 59" src="https://github.com/user-attachments/assets/4078363c-9d6f-4d0a-a98b-b1e955b7b4f7" />
<img width="1470" alt="스크린샷 2025-03-27 오후 5 48 05" src="https://github.com/user-attachments/assets/3594dafc-c2ea-4775-991d-65aec58f6fec" />
<img width="1470" alt="스크린샷 2025-03-27 오후 5 48 09" src="https://github.com/user-attachments/assets/9f4cf2ea-08bd-4419-982b-e007e1fbbc4d" />
<img width="1470" alt="스크린샷 2025-03-27 오후 5 48 14" src="https://github.com/user-attachments/assets/541baa3a-7153-433f-9eec-0a2544c8ca62" />
<img width="1470" alt="스크린샷 2025-03-27 오후 5 48 25" src="https://github.com/user-attachments/assets/5c0fdae6-d03e-4714-901f-214eba552d9e" />
<img width="1470" alt="스크린샷 2025-03-27 오후 5 48 31" src="https://github.com/user-attachments/assets/6c8328f1-792f-401a-9b92-b2bcc60b4e1c" />



## **📌 주요 기능**
✅ 이미지 불러오기 및 자유 배치
  * 사용자가 여러 장의 이미지를 선택하고, 캔버스 위에 자유롭게 배치 및 드래그 이동 가능
✅ 그리드 기반 콜라주 초기 구성
  * 사용자가 직접 지정한 행/열 값을 기반으로 기본 콜라주 형태 구성
✅ 이미지 편집 기능
  * 마우스로 직접 ROI(관심 영역) 설정 후 해당 영역만 잘라내기
  * 트랙바를 통해 이미지 크기 조절
  * 더블 클릭을 통해 이미지 선택 및 편집 가능
✅ 필터 적용
  * 밝기 필터: 전체 이미지 밝기를 증가시켜 화사하게 표현
  * 흑백 필터: Grayscale 변환을 통한 분위기 전환
✅ 스티커 합성
  * 사용자가 선택한 PNG 스티커를 콜라주에 자유롭게 추가 및 위치 조정
  * OpenCV 배열 변환을 통해 이미지에 직접 합성 구현
✅ 그림판 기능
  * 브러시 색상 및 두께 선택 가능
  * 마우스 우클릭 드래그로 자유롭게 그림 그리기
  * 캔버스 초기화(지우기) 기능 포함
✅ 콜라주 결과물 저장
  * 모든 이미지와 스티커, 그림 요소를 하나의 배경에 합성하여 최종 콜라주 생성
  * PNG 이미지로 저장 및 미리보기 제공



## **🛠️ 기술 스택** 
* Python GUI: Tkinter (Canvas, Button, Menu, ColorChooser 등 위젯 활용)
* 이미지 처리: OpenCV (cv2.add, cvtColor, ROI, resize 등)
* 이미지 출력 및 저장: PIL (Image, ImageTk)
* 기타: Numpy, 파일 다이얼로그 및 사용자 입력(SimpleDialog 등)



## **⏳ 개발 기간**
- 2023.10.30 ~ 2023.12.11 (42일)
