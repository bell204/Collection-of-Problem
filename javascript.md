자바스크립트 자주 쓰는 함수들 

<h1> Q1 SetTimeOut (타이머 함수) </h1>

특정 코드를 의도적으로 지연한 후 사용하고 싶을 때 사용.

ex)
setTimeout(function(){ // 지연시간 뒤에 실행될 코드 넣기// }, delay);


<h1> Q2 SetInterval </h1>

일정 시간마다 반복실행하는 함수

ex)
var intervalId= setInterval(setText, 1000); // 1초마다 setText를 실행시킴. 

<h1> Q3 ClearInterval </h1>

타이머를 중지하는 함수 

ex) 
clearInterval(intervalId);
