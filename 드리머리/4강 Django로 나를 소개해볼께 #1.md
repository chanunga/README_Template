# Django로 나를 소개해볼께 #1
### Model
데이터에 접속하고 관리하도록 도와주는 객체
#### Model 생성 & 적용
1.models.py - 모델명의 첫글자는 무조건 대문자</br>
2.Terminal 
- DB가 알아듣도록 번역하기 : python manage.py makemigrations (+ App 이름)
- 번역한 내용을 DB에 적용 : python manage.py migrates (+ App 이름)
### Admin 기능
Django는 웹 서비스 관리를 위한 admin 기능 기본 제공
