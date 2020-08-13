# 2강 Hello, Django
### 가상환경
자신이 원하는 Python 환경 구축을 위해 필요한 모듈만 담아 놓는 바구니.
### PIP
Python으로 작성된 패키지 소프트웨어를 관리하는 패키지 관리 시스템.
### VS Code 단축키
터미널 생성 - Crtl + Shift + `</br>
현재 커서 위치의 코드 복사 - Ctrl + D (여러 줄 복사도 가능)</br>
현재 커서 위치의 코드 이동 - Alt + (상키) or (하키)</br>
### 가상환경 명령어
가상환경 생성 - python3 -m venv <가상환경 이름></br>
가상환경 활성화 - source <가상환경 이름>/Script/activate</br>
가상환경 끄기 - deactivate</br>
### Django 명령어
Django 패키지 설치 - pip install django</br>
Django 프로젝트 생성 - django-admin startproject <프로젝트명>. (마지막에 . 붙이지 않으면 새로운 폴더 생성안됨)</br>
Django App 생성 - python manage.py startapp <App 이름></br>
Django 로컬서버 시작 - python manage.py runserver</br>
### Project & App
하나의 Project == 하나의 Web Site</br>
Project 안의 의미 있는 기능들을 각각의 App으로 관리</br>
#### Project
settings.py - 전체 프로젝트를 관리하는 설정 파일</br>
urls.py - 프로젝트의 URL 관리 파일</br>
wsgi.py, asgi.py - 프로젝트를 서비스하기 위한 파일</br>
init.py - 해당 디렉토리가 Python Package의 일부임을 Python에게 알려주는 파일</br>
#### App
views.py - 웹 요청을 받고, 전달받은 데이터를 처리해서 가공하는 파일</br>
models.py - Database와 관련된 다양한 역할 수행</br>
admin.py - 관리자 관련 파일</br>
apps.py - Project에게 App의 존재 알려줄 때 활용되는 파일</br>
### Home 페이지 출력하기
1.settings.py : Project에게 App의 존재 알리기</br>
2.Templates : User에게 보여줄 HTML 파일 만들기</br>
3.views.py : 요청이 들어오면 HTML 파일을 열어주는 함수 정의</br>
4.urls.py : url 요청을 views와 연결하기
