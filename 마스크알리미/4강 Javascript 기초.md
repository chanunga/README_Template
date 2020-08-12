# 4강 Javascript 기초
### Javascript
- 웹페이지를 동적으로 만들 때 사용하는 언어
- 객체 기반의 언어
- 브라우저에서 제공하는 API / 2D, 3D 그래픽 작업 / JS로 가능
- 스크립트 언어 인터프리터(파이썬과 동일) - 입력 후 바로 확인 가능
- 사용법 - HTML 내부에서 <script> 태그 내에서 사용
         -.js 파일로 만들고 <script src="파일 경로"><script>

#### 변수
데이터 타입 - boolean, null, undefined, number, string, symbol, object
var - 권장하지 않는 변수 선언 방식
let - block scope 변수
const - 변하지 않는 데이터를 저장
#### 조건문
let score = prompt("점수를 입력하세요 1", 0);
if ( score >= 90){ console.log("A"); }
