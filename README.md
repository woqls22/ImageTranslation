# 실시간 이미지 스캔 페이지
## 주제
사용자가 이미지를 업로드하면, 실시간으로 스캔된 이미지의 형태를 반환하는 웹페이지[OpenCV라이브러리 이용]
- 원근 변환을 이용하여 기울어진 이미지도 정사각형 형태로 자동변환기능 지원

## URL
http://15.164.85.45:3000/

## 사용방법
  * 이미지 파일 업로드
![1](./src/1.JPG)
  * 스캔 이미지 반환[문서 영역 자동 추출]
![2](./src/2.JPG)
  * 문서 TEXT 추출 [영어지원]
![3](./src/3.JPG)
  * 이미지 파일 업로드
![4](./src/4.JPG)
  * Text 추출.
![5](./src/5.JPG)

## 개발 환경
- npm install
- pytesseract
- opencv with python3


## 수정 내역
 * [20.05.11] 레파지토리 생성
 * [20.05.15] 이미지 스캔모듈 추가
 * [20.05.18] app.js 라우터분리, ocr모듈 추가
 * [20.05.19] AWS EC2 서버 로드 완료
