# 3강 Github 협업
## 자주 사용하는 명령어

git init - 깃 저장소 초기화

git add . - 폴더에 변경된 모든 파일 올리기

git commit -m "커밋에 대한 설명" - 유사시 돌아갈 수 있는 저장소의 체크포인트 생성

git remote add origin 원격저장소주소 - 원격저장소<->local연결

git branch 브랜치 명 - 한 레포에 사용 용도에 따라서 저장소를 나누는 것

git checkout 브랜치 명 - 해당하는 브랜치로 이동

git push origin 브랜치 - 원격 저장소의 특정 브랜치에 프로젝트 저장

git pull origin 브랜치 - 원격 저장소의 특정 브랜치에 변경사항 다운로드

git clone 원격저장소 주소.git - 원격 저장소에 있는 파일 전체ㅔ 복사


1. New Repository 생성
2. 팀원 collaborator 추가
3. 초기 프로젝트 push
4. 팀원들의 로컬 프로젝트 pull(or clone)
5. 팀원의 각자의 브랜치를 생성하여 작업
6. 브랜치에 작업한 내용을 push
7. Master와 merge 하시 전 pull request
8. pull request 확인 후 Master와 merge
