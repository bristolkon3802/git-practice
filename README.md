# git-github

Practicing Git &amp; Github for collaboration.

## Who has been here?

Add your Github username below.

- [x] bingstar

## git

- [x] repositories

        git init
        git remote add origin url
        git remote remove origin

        git add .
        git commit -m ""
        git push origin main

- [x] pull - 원격브런치 에서 현재 브런치로 가져옴

        git pull origin main

- [x] commit 이력 확인

        git log

- [x] push

        git push origin main

- [x] stage 추가

        git add .

- [x] commit

        git commit -m ""

- [x] 이전 커밋으로 되돌아가 가기

        git checkout 5eb5c49c983da7e39c021774cb3ca73d79fc6df3

- [x] 이전 커밋 취소

        git checkout main

- [x] reset 하드리셋 - 이전 커밋으로 돌아가고, 파일 변경 내역을 유지하지 않음

        git reset --hard HEAD^^^
        git push origin main --force

- [x] reset 복합리셋 - 마지막 커밋 혹은 선택한 커밋에서의 변경사항을 unstage 영역으로 변경, 변경내용 유지

        git reset HEAD^
        git add .
        git commit -m ""
        git pull origin main --force

- [x] reset 소프트리셋 - 마지막 커밋 혹은 선택한 커밋에서의 변경사항을 unstage 영역에 두지 않음,
      작업중 파일이 있을 때 섞이지 않고 싶으면 사용

        git reset HEAD^^ --soft

- [x] checkout - 새로운 브런치 만들기

        git checkout 363741a636b94a35577fff67a45c8055a5581f42 -b new-branch-name
        git checkout main

- [x] 브런치 목록

        git branch
        git push origin branch-name

- [x] 브런치 삭제

        git branch -d branch-name

- [x] 커밋 수정

        git add .
        git commit --amend --no-edit
        git push origin main --force

- [x] 커밋 상태 확인

        git status

- [x] add 상태 취소 - -r 폴더일경우, --cacged 캐쉬 삭제

        git rm -r [/images] --cacged

- [x] remote - 저장소 확인

        git remote -v
        git remote add [add-name] [url]
        git remote remove [remove-name]
        git push [gitlab-name]

- [x] git clone

        git clone [url] [new-project-name]

- [x] git의 내장 GUI

        gitk

- [x] 콘솔에서 git output을 컬러로 출력

        git config color.ui true
