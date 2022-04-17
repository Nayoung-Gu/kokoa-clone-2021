#  💌 Kokoa Clone 2021

## 🖋 개요

- 채팅 기능을 제외한 html, css로 카카오톡 화면 클론하기
- 로그인 화면, 친구 리스트, 채팅 화면, 설정 화면 구현
<br>

## 💻 주요 기능

- 화면 전체를 구성하는 screens와 일부 요소 기능을 포함한 components로 구분해 css 파일 정리
- :root에 자주 쓰이는 속성 변수 저장
- 가상 선택자 활용
- user component, footer component 등 화면 공통적으로 쓰일 수 있는 부분 컴포넌트화
- search 화면 하단의 애니메이션 (@keyframes, transform 사용)
- 미디어쿼리를 사용해 모바일 사이즈를 넘어갔을 때 화면 크기를 요청하는 화면 생성
<br>

## 💬 프로젝트를 하며 느낀 점

- 당장 화면을 구현하는 데 급급해 css 파일을 정리하고 컴포넌트화하는 것의 중요성을 느끼지 못했으나 화면 개수가 늘어날수록 컴포넌트를 재사용함으로써 절약되는 시간 및 비효율성을 체감했다.
- 헤더의 시간을 js를 활용해 실시간으로 불러오는 기능,  WebSockets, SocketIO, WebRTC 등을 활용해 실제 실시간 채팅 기능을 앞으로 추가 구현해보고 싶다. 
<br>

## 실제 구현 화면
![image](https://user-images.githubusercontent.com/80025366/163707248-a3c8cb20-0cbe-4fba-a2ce-4a9b4913467c.png)

