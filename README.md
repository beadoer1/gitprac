## **git과 github 사용법을 연습해보았습니다.**

1. CLI를 통해 git을 생성하고 add, commit 해보기
- git init : git 생성
- git add fime명 : commit 할 file 을 선택
- git commit -m "message" : file 을 message와 함께 commit

2. git에 내 정보 등록하기
- git config --global user.email "beadoer1@gmail.com"
- git config --global user.name "beadoer1"

3. log를 확인하고 과거의 git에 checkout 하여 파일이 변경되는 것을 확인
- git log : git 의 log들을 확인함
- git checkout git주소 : 해당 주소의 git을 가리키어 당시의 파일을 나타냄

4. github에서 원격저장소(레포지토리)를 만들고 연결함
- git remote add origin https://github.com/beadoer1/gitprac.git

5. 로컬저장소의 데이터를 원격저장소로 push
- git push origin master : origin(원격저장소) 로 master 브랜치가 가리키는 커밋의 파일들을 보냄

6. gitprac2 디렉토리를 만들어 제 2 작업구역을 설정하고 git clone 및 pull 진행
- git clone https://github.com/beadoer1/gitprac.git . : 원격저장소의 git을 clone('.'주의!)
- git pull origin master : 원격저장소 master 브랜치가 가리키는 깃의 파일을 불러옴

7. GUI(소스트리)를 통해 기존의 git을 불러 시각화 하고 checkout, add, commit, push 등을 진행
- Clone : 원격저장소를 내 컴퓨터에 받아오고(로컬저장소 자동 생성) 소스트리에도 추가
- Add : 내 컴퓨터에서 이미 만든 로컬 저장소를 소스드리에 추가
- Create : 내 컴퓨터의 폴더에 새로운 로컬 저장소를 생성(git init)



