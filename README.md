# HTML-CSS
HTML/CSS 기초 공부 기록입니다.
<br>
강의이름: 김버그의HTML&CSS는 재밌다
<br>
강의정보:https://edu.goorm.io/lecture/20583/김버그의-html-css는-재밌다'

<h1>수강 후 정리 내용</h1>
<h2>HTML</h2>
<ul>
  <li><h2>FORM 태그</h2>
    <p><img src="https://user-images.githubusercontent.com/64995062/148060702-c4f573de-736e-4dea-bda8-905dfd8915db.png" alt="form_tag_practice"></p>
    <ol>
      <li>폼 태그는 입력된 데이터를 한 번에 서버로 전송합니다.</li>
    <li>폼 태그 속성은 name, action, method, target 등이 있는데 주로 method(GET or POST)를 사용합니다.</li>
  <li>GET은 폼 데이터를 URL 끝에 붙여 눈에 보이지만 POST는 내부적으로 보이지 않게 보냅니다.</li>
    </ol>
</li>
  <li><h2>INPUT 태그</h2>
  <ol>
      <li>사용자가 다양하게 폼 태그에 입력할 수 있는 공간을 구성해줍니다.</li>
    <li>type: 태그 모양 변경 가능(예시: button, text, radio, checkbox, fileupload, hidden 등)</li>
    </ol></li>
  </ul>
<h2>CSS</h2>
<ul>
  <li><h2>float 속성</h2>
    <p><img src="https://user-images.githubusercontent.com/64995062/148069944-40069d5a-4a0d-4c34-9c88-dda9f8e60220.png" alt="float 속성"></p>
<p>inline 요소를 float 시키는 경우 이 요소 특성은 block box로 변경되고 마치 div 태그인 것처럼 동작하게 된다.<br>
대신 한 줄을 모두 차지하는 block이 아닌, 자신의 영역만을 가지고 있는 inline-block처럼 렌더링된다.
<br>
다시 말해, 플로팅된 요소는 display: inline-block; 을 선언한 것과 동일해진다.</p>
    </ol>
</li>
  <li><h2>float 활용법</h2>
  <ol>
      <li>clearfix 활용</li>
    <li>overflow hidden 속성 이용하기<br>
    <p><img src="https://user-images.githubusercontent.com/64995062/148070141-77f38b0d-a8c6-4290-85d4-68d43aa069a5.png" alt="overflow hidden 속성"></p></li>
    <li>::before, ::after를 이용한 html 작성 대신 css 가상요소 만들어 공간 채우기<br><p><img src="https://user-images.githubusercontent.com/64995062/148070247-3773f639-f66e-40de-b40e-8c58c3bcc65d.png" alt="가상요소 이용한 float 활용법"></p>
</li>
    </ol></li>
      <li><h2>position 활용법</h2>
  <ul>
      <li>position:absolute; 활용</li>
    <li>absolute의 기준 -> 자기가 기준을 삼고 싶은 요소 선택 가능하다. position이 static이 아닌 경우 가능하다.</li>
    <li>position:fixed; 활용</li>
    <li>viewport -> 브라우저에서 사용자에게 보이는 부분이다. fixed의 경우 viewport를 기준으로 위치하게 된다.</li>
    <li>z-index 활용</li>
    <li>z-index는 창을 순서대로 배치하는 스타일</li>
    <li>기본적으로 z-index의 숫자가 높을수록 가장 상단(눈에 가깝게)에 배치, 숫자가 낮을수록 하단(눈에서 멀게) 배치된다. z-index는 음수 또는 양수의 숫자를 사용할 수 있다.</li>
    </ul></li>
  </ul>
