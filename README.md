# git-github

Practicing Git &amp; Github for collaboration.

## Who has been here?

Add your Github username below.

- [x] bingstar

## git

- [x] git === pc 변경사항 pull

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
