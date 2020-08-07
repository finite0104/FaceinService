# FaceinService
얼굴 인식을 이용한 간편 로그인 서비스 개발

## Architecture
 Service Application  <-->  API Server  <-->  Machine Learn System
( Mobile,WebService )

### Service Application
Application에서 회원가입 및 로그인 기능 지원

#### Mobile
Android, iOS Application Develop

#### Web Service
React.js based Application Devleop


### API Server
Application에서 회원가입 및 로그인 요청 시 요청에 대한 데이터 처리
Node.js based RestfulAPI Develop

### Machine Learn System
회원가입 시 입력될 이미지 데이터를 이용해 신원 증명이 가능하도록 처리
Python Tensorflow System Develop
