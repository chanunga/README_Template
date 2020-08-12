# 5강 Fetch API
###비동기 처리
들어온 요청들을 순차적으로 실행시킨다면? </br>
앞에 들어온 작업이 시간이 오래 걸리는 작업일 시 뒤에 있는 작업들이 밀리게 된다.</br>
이런 작업들을 그대로 실행시키면서 뒤에 있는 코드들을 실행시키는 것이 비동치 처리다.</br>
Promise 객체를 사용 - 대기, 이행, 거부</br>
#### 비동기 호출 keyword</br>
async, await</br>
Promise객체 - then(콜백함수), catch(콜백함수)</br>
### fetch API
네트워크 통신을 위해 제공되는 API</br>
Promise 객체 반환</br>
Request, Response라는 두 객체 사용</br>
### 실습
Promise 대기, 이행, 거부
- Pending (대기)
- Resolved (이행)
- Rejected (거부)
