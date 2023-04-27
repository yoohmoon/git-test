## Git Command

- `git init` : 신규로 프로젝트를 시작할 때, 새로운 디렉토리를 생성한 후, git init 명령어를 통해서 해당 디렉토리를 깃이 추적할 수 있게 해주는 명령어.
- `git remote add origin <remote repository url>` : 현재 로컬에 저장된 디렉토리를 깃허브 내의 원격 저장소와 연결되게 해주는 명령어.
- `git add <file name>` : 수정한 파일들을 staged 상태로 올려두어 저장할 수 있게 해주는 명령어이다. 해당 명령어를 git commit 하기 전에 반드시 거쳐야 한다.
- `git commit`: 수정, 변경, 추가한 파일들의 수정 내역을 실제적으로 저장하는 명령어이다.
- `git push origin <branch name>` : 현재 작업중인 파일들을 연결된 원격 레포지터리 내의 특정 브랜치에 올리는 명령어이다.
- `git pull origin <branch name>` : 원격 레포지터리 내의 특정 브랜치에 있는 파일들을 로컬로 당겨서 가져올 수 있게 해주는 명령어이다.
- `git merge <branch name>` : 로컬에서 특정 브랜치와 합치고 싶은 다른 브랜치를 합칠 수 있게 해주는 명령어이다.
