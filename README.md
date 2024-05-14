# nodeJS-Carwash-Project
공공데이터 API를 활용한 세차장 관리 웹서비스 시스템 구축

```
개발 기간 : 2023.03. ~ 2023. 04. (2개월)
개발 인원 : 2명 
프로젝트 내 역할 : 관리자 페이지 - 사용자 정보 관리(CRUD), 데이터 전처리 및 가공, 현재 위치 기반 세차장 검색 구현, 페이지 기능 구현을 위한 REST API 작성
```


<개발 환경>

언어 : JavaScript, HTML5/CSS3
서버 : Node.js 18.15.0, Linux Ubuntu 22.04
프레임워크 : Express.js
DB : MySQL 8.0.34, MongoDB 4.4.24
IDE : MySQL WorkBench(MySQL 관리 및 개발용), MongoDB Compass(MongoDB 관리 및 개발용), Visual Studio Code(코드 편집 및 개발용)
API, Package : Rest API, Open API, Kakao map API


<프로젝트 요약>

GitHub : https://github.com/SeguirLuna0114/nodeJS-Carwash-Project
https://github.com/SeguirLuna0114/Project-s/tree/main/1st_carwash_nodeJS

- 세차장 데이터(세차장명, 주소, 세차타입, 전화번호)를 사용자에게 효과적으로 전달
- 세차장 데이터는 전국 기준으로 수집하고, 정보가 많은 강남구, 서초구, 송파구 지역의 데이터 활용
- 가공 데이터를 활용하여 사용자의 위치(위도, 경도)를 바탕으로 인근 세차장 10곳 추천
- 가공이 끝난 데이터를 활용하여 지도위에 마커 형태로 시각화
- 데이터 검색 예외처리(~동, ~구를 생략하고 입력해도 데이터 검색 가능)
