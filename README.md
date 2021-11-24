# 201840223 이재현
## https://ko.reactjs.org/

npx create-react-markdown-deitor<br>
설치 npm install remarkable<br>
npm start<br>
시간 나오는 : Date().toLocaleTimeString() <br>
<hr>
react에는 함수 컴포넌트와 클래스 컴포넌트가 있다 <br> 
★ 컴포넌트의 이름은 항상 <b>대문자</b>로 ★ <br>
컴포넌트 합성 : 컴포넌트는 출력에 다른 컴포넌트를 참조할 수 있다.<br>
<hr>

# 11월 24일

state를 이용하여 remarkable에 변환할 마크다운 문장을 제출 <br>
글이 입력되면 handleChange 이븐트를 사용하여 state의 value를 갱신 <br>
getRawMarkup()메소드를 이용하여 init에 적용<br>
<hr>
React는 처음부터 점진적으로 적용할 수 있도록 설계되었다<br>
필요만큼 react를 사용가능<br>
codesandbox는 create-react-app으로 생성된 프로젝트와 동일한 환경에서 테스트 가능<br>
cdn방식으로 간편하게 테스트를 할 수 있도록 html코드를 제공<br>
react문서가 어렵게 느껴지면 tania rascia가 쓴 react개요를 먼저학습<br>
개발을 통해 react를 학습하고 싶다면 자습서 추천<br>
<hr>

### jsx 
jsx는 React “엘리먼트(element)” 를 생성 <br>
jsx가 필수사용은 아님 하지만 시각적으로 도움이된다고 생각 <br> 
jsx의 중괄호 안에는 유효한 모든 JavaScript 표현식을 넣을 수 있다.<br>
어트리뷰트에 따옴표를 이용해 문자열 리터럴을 정의할 수 있다<br>

<.img/> <br>
<.img> <./img> 마감을 안시켜주면 오류 발생 <br>

#### 엘리먼트 렌더링
element는 react앱의 가장 작은 단위 <br>
브라우저 DOM 엘리먼트와 달리 React 엘리먼트는 일반 객체이며(plain object) 쉽게 생성할 수 있습니다. React DOM은 React 엘리먼트와 일치하도록 DOM을 업데이트<br>
React 엘리먼트를 루트 DOM 노드에 렌더링하려면 둘 다 ReactDOM.render()로 전달<br>

### Components and Props
컴포넌트를 정의하는 가장 간단한 방법은 JavaScript 함수를 작성<br>
React가 사용자 정의 컴포넌트로 작성한 엘리먼트를 발견하면 JSX 어트리뷰트와 자식을 해당 컴포넌트에 단일 객체로 전달 이것을 Props라고 말한다<br>
props는 읽기전용<br>
<b> 모든 React 컴포넌트는 자신의 props를 다룰 때 반드시 순수 함수처럼 동작해야한다</b>

### State and Lifecycle
스스로 업데이트 = > 컴포넌트에 <b>“state”</b>를 추가 <br>





# 11월 17일
npx create-react-markdown-deitor<br>
설치 npm install remarkable<br>
npm start<br>

버전확인 package.json
<br>
"remarkable": "^2.0.1"

### code review
외부 컴포넌트를 사용하기 위해 생성자 내에 객체를 생성
<br>
state를 이용하여 remarkable에 변환할 마크다운 생성
<br>
