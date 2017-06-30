# LV.1 명령어 익히기
0. 
* ```git add <file>``` - stage에 올리기
* ```git commit``` - 커밋하기

1. 상태 보기
* ```git status ``` - git 상태확인
* ```git log``` - 로그 확인

2. 변경사항 확인하기
* ```git log -p``` - 버전간의 차이점 확인
* ```git diff``` - add 전과 후의 비교
* ```git diff <v1> <v2>``` - 입력한 커밋간 차이점 비교

3. Back To the Future
* ```git reset <version> --hard``` - 입력한 커밋으로 돌아감
* ```git revert <version>``` - 입력한 커밋을 취소한 새로운 버전을 만듬 

4. Branch!
* ```git branch``` - 브랜치 목록확인
* ```git branch <new branch>``` - 브랜치 생성
* ```git checkout <branch>``` - 브랜치 전환
* ```git checkout -b <new branch>``` - 브랜치 생성&전환
* ```git merge <target branch>``` - target branch를 현재 브랜치에 병합


##### 참고
* [지옥에서 온 Git](https://opentutorials.org/course/2708)
* [Reset vs. Revert](http://www.popit.kr/%EA%B0%9C%EB%B0%9C%EB%B0%94%EB%B3%B4%EB%93%A4-git-back-to-the-future/)
* [SVN vs. GIT](https://tonyne.jeju.onl/2016/06/07/why-use-github-on-small-company/)
 
