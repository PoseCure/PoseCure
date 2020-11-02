# PoseCure
//사용자의 자세를 교정하는 프로그램입니다
sudo apt-get update

- 한글 관련 모듈

1. 라즈베리파일 한글 깨짐 
sudo apt-get install fonts-unfonts-core
2. 에디터에 한글을 사용하기 위함
sudo apt-get install fcitx-hangul
im-config -n fcitx

- git 사용법

1. 설치 
sudo apt install git-all
2. 저장소 복제
git clone https://github.com/zungun/PoseCure.git
3. branch 생성
git checkout -b <branch 이름>
4. 스테이징 영역에 추가 add
git add .
5. 로컬 저장소에 커밋 commit 아래 명령어 순서대로 실행
 - git config --global user.name "NAME" //NAME에 원하는 이름
 - git config --global user.email "EMAIl" //EMAIL에 유효한 이메일 주소
 - git commit -m "message" //message에는 원하는 메세지 입력
6. 리모트 저장소에 푸시 push
git push origin <branch name> //ex) git push origin zungun
7. master branch에서 pull
git pull origin master

