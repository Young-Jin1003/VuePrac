## Ajax 개념 정리
#### Ajax 갖는 의미 : 웹 페이지의 전체가 아닌 일부분의 로딩이 가능해짐 (사용자의 동작에 영향을 주지 않고서 백그라운드로 서버와 통신가능)

### Ajax 동작 원리
#### 1. 사용자에 의한 요청 이벤트 발생
#### 2. 이벤트 핸들러에 의하여 JS 호출
#### 3. JS는 XMLHttpRequest 객체를 사용하여 서버로 요청 보냄
#### 4. 서버로 전달받은 XMLHttpRequest 객체를 가지고 Ajax 요청 처리
#### 5. 서버는 처리한 결과를 HTML, XML, JSON 형태의 데이터로 브라우저에 전달
#### 6. 서버로부터 받은 데이터를 웹 페이지의 일부분만을 갱신하는 JS호출
#### 7. 웹 페이지의 일부분만 리로딩 
