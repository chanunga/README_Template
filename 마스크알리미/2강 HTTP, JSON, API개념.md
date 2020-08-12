# 마스크알리미 2강 HTTP, JSON, API개념
### HTTP
#### Hyper Text Transfer Protocol
Hyper Text - 참조를 통해 한 문서에서 관련된 다른 문서들로 넘나들며 원하는 정보를 얻을 수 있게 해주는 텍스트
ex) 유튜브 - 영상을 볼때 다른 연관된 영상들을 왔다갔다 하는 텍스트들</br>
Transfer Protocol - 인터넷을 통해서 정보를 주고 받을때 지켜야 하는 규칙
#### HTTP의 구성
Request 요청 / Response 응답
#### HTTP의 요청 매소드
GET - URL(주소) 리소스 가져오기</br>
POST- body - 글에는 사진, 파일, 글을 body에 담아 서버로 보내면 서버가 입력</br>
PUT - 타이틀과 내용 모두 수정 - ex) 타이틀만 수정하여 보내고 내용은 안보내면 기존에 있는 타이틀 내용은 바뀌고 내용은 없어짐.</br>
PATCH - 일부만 수정 - ex) 타이틀만 수정하여 보내면 타이틀은 바뀌고 내용은 기존 있던 내용 유지.</br>
DELETE - URL의리소스를 특정해서 보내면 삭제.
### JSON : Java Script Object Notation
네트워크상 데이터를 보낼때 정보를 어떻게 표현할지.</br>
Key : Value 형식</br>
데이터 교환시 JSON형식 자주 사용(이전에는 XML이라는 형식도 사용했었음)
####제이슨의 특징
- 기존의 XML보다 가볍다.</br>
- 많은 프로그래밍 언어가 지원한다.</br>
- 전송시 : 직렬화 과정을 거친다.</br>
- 수신시 : 역직렬화 과정을 거친다.</br>

JSON.stringfy(super_hero) - 직렬화</br>
let serialized = JSON.stringfy(super_hero)</br>
JSON.parse(serialized) - 역직렬화(오브젝트형식)</br>

### API - Application Programming Interface
Application - 우리가 사용하는 다양한 서비스들</br>
서비스들의 프로그래밍 인터페이스를 제공해주는 도구, 서비스들이 제공해주는 데이터들에 접근하고 사용할 수 있도록 도와주는 도구 </br>
#### API의 종류
SOAP - XML을 조금 더 쉽게 주고받는</br>
REST - 아키텍처</br>
GraphQL - REST의 한계를 극복하고자 페이스북에서 만든것</br>
#### REST
소프트웨어 아키텍처 - 소프트웨어를 설계하는 지침과 원칙(법은아님)</br>
REST의 구성요소
행위/         자원</br>
GET/likeilon/member/8th/list </br>
PATCH/likeilon/member/8th/허태정 </br> </br>

표현 - 표현하는 방식이 JSON
{
"member":["김멋사,......,허멋사"]
}

