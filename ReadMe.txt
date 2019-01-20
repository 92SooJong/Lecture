
해당 폴더 git 사용가능하게 초기화
--> git init 

해당 폴더를 온라인 저장소와 연결
git remote add origin 저장소 주소



pull은 로컬 폴더로 가져오는것.
--> git pull origin master




현재 git과 나의 폴더의 syn 상태 체크
--> git status

온라인이나 로컬에서 파일이 변형된것을 트랙킹
--> git add . 

인식 할 수 있는 commit을 달아준다.
git commit -m "메세지"

실제로 Git에 PUSH
git push origin +master