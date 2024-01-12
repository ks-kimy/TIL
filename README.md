---

**git remote add origin remote_repo_url**

git remote 

- 한 쌍으로 쓰임

로컬 저장소에 원격 저장소 주소 추가

origin 이라는 별칭을 붙임으로써 주소를 계속해서 입력해야 하는 불편함을 없앰.

origin : 추가하는 원격 저장소 별칭

remote_repo_url : origin 에 해당하는 주소

- git remote -v
    - git의 자세한 정보를 보여줌 별칭과

github repository ↔  local repository

push : 깃허브에 올릴 때

- git push -u origin master
    - 원격 저장소에 commit 목록을 업로드
        - “git아, push 해줘! origin 이라는 이름의 원격 저장소에 master라는 이름의 브랜치를”

clone : 전체를 다 (깃허브로부터 로컬저장소로)

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/31646b6b-b42d-4cf2-be78-b5a591bfad6f/40d51cf0-a3dc-40d4-ba1e-982f3c1dd10d/Untitled.png)

자리 바꾸고 이거 지움.

git pull origin master

- 원격 저장소의 변경사항만을 받아옴(업데이트)

git clone remote_repo_url

- 원격 저장소 전체를 복제(다운로드)
    - clone으로 받은 프로젝트는 이미 git init이 되어 있음
    (집 가자마자 해야할 것)

gitignore

Git 에서 특정 파일이나 디렉토리를 추적하지 않도록 설정하는 데 사용되는 텍스트 파일

→ 프로젝트에 따라 공유하지 않아야 하는 것들도 존재하기 때문

github 활용하기

TIL(내가 배운 것) 을 통해 내가 학습하는 것을 기록

TIL (Today I learned)

매일 내가 배운 것을 마크다운으로 정리해서 문서화하는 것

단순히 배운 것만을 필기하는 것이 아닌 스스로 더 나아가 어떤 학습을 했는지를 기록하는 것.

문서화의 중요서

신입 개발자에게 요구되는 가장 중요한 덕목

꾸준히 스스로 학습해 성장할 수 있고 문서화를 통해 내 생각을 정리하고 팀에게 공유할 수 있어야한다.