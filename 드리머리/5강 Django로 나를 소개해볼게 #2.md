# Django로 나를 소개해볼게 #2
### QuerySet
전달 받은 모델의 객체 목록</br>
views.py
### Detail Page 구현
- 각각의 글을 어떻게 분류하지? -> PK(Primary Key)</br>
- urls.py에서 글마다 Path를 만들어야 하는 건가? -> Path Convertor</br>
- 만약 없는 글을 불러오려고 하면 어쩌지? -> ** get_object_or_404**
### PK (primary Key)
Model을 통해 생성된 객체들을 구분할 수 있는 "고유한" Key
### Path Convertor
여러 객체의 url를 "계층적으로" 다룰 수 있도록 도와주는 도구
### get_object_or_404
Object를 가져오려 했는데 없을 경우 나타나는 에러
