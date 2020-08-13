# 3강 Django가 관리하는 법
### Bootstrap>
Front-End 개발을 빠르고 쉽게 할 수 있는 오픈 소스 Framework</br>
- 누구나 쉬운 사용 가능</br>
- 반응형 CSS 제공</br>
- 모든 최신 브라우저와 호환</br>
- PC & 모바일 디자인 제공</br>
### URL 관리
Django의 URL 관리는 urls.py의 urlpatterns에서 담당</br>
Path의 구조</br>
- path('URL',views 내부의 함수, name = "url의 이름")</br>
  - 'URL' : 페이지 주소 (ex. introduce/, new/)</br>
  - 함수 : url이 불렸을 때 실행할 함수 (ex. views.home)</br>
  - name : 해당 path를 대표하는 이름 (ex. name = "home")</br>
### Template 언어
Python 변수 & 문법을 HTML에서 쓸 수 있도록 Django에서 제공하는 언어</br>
- {{}} : 템플릿 변수(명사)</br>
- {%%} : 템플릿 태그(동사)</br>
### Static File
이미지나 CSS, JS 파일처럼 내용이 고정되어 있어, 응답을 할 때 파일 그대로를 보내주면 되는 파일</br>
- Static : 웹 서비스를 위해, 개발자가 준비해두는 파일</br>
- Media : 웹 서비스 이용자들이 업로드하는 파일</br>
#### Static File 처리하기
1.Static 폴더 생성 - App 폴더 내에 static 폴더 만들기 & 파일 생성</br>
2.Settings.py (Static 설정)</br>
   STATICFILES_DIRS=[Path(BASE_DIR, 'App 이름','static')] # Static File들이 들어있는 경로</br>
   STATIC_ROOT = Path(BASE_DIR, 'static') # Static File을 모을 디렉토리</br>
3.Static 파일 모으기 - python manage.py collectstatic
