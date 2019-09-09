#Git Branch

## Git 기초
 - `git init`
 - `git add`
 - `git commit `
 - `git log` (-oneline)

 ## Git 원격저장소(remote)
 - `git remote add [저장소이름] [저장소주소]`
 - `git remote ` : 원격 저장소의 리스트(이름)
 - `git remote -v`: 원격저장소의 리스트(이름, 주소)

 ## Git 브랜치(branch)
 - `git branch` : Branch의 리스트
 - `git branch [브랜치 이름]` : 새 브랜치 만든다
 - `git checkout [브랜치 이름]` : 브랜치 바꿈
 - `git switch [브랜치 이름]` : 브랜치 바꿈
 - `git branch -d [브랜치 이름]` : 브랜치 삭제
 - `git checkout -b [브랜치 이름]` : 브랜치 생성 & 이동 
 - `git switch -c [브랜치 이름]` : 브랜치 생성 & 이동
 - `git merge [대상브랜치 이름]` : 현재 브랜치에서 대상브랜치를 머지한다.

 ## Git Merge 시나리오
 1. fast-forward merge
 2. auto merge (without conflict)
 3. merge with conflict

 ## Conflict 뭘까
 ### conflict 정의
 - 동일 파일
 - 동일 라인의 내용이 다를 경우