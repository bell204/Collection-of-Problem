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


<h1> Q4 사용자가 입력하는 것은 이벤트임 </h1>

이벤트가 발생했을 때 변경된 상태가 변수에 저장되어야 함. 

<h1> Q5 Splice 함수 </h1>

24장의 카드에서  카드에서 한장씩 뽑아서 할 때, 처음엔 24개 , 두번째는 23개 이런식으로 하나씩 제거되어야 하므로 반복문과 함께 씀. 

ex) 

splice(위치, 삭제개수)

var img = cards.splice(idx, 1);

<h1> Q6 Find 함수 </h1> 

ex) 

find(요소) / find(선택자) / find ($객체)

-> var openCardSrc2 = $(this).find('img') // 이미지 태그를 찾아라.

<h1> Q7 Attr 함수 </h1>

ex)

-> var openCardSrc2 = $(this).find('img').attr('src'); // 이미지 태그의 src 속성의 값을 openCardSrc2에 저장해라.

<h1> Q8 text, html 함수 </h1>

ex)




