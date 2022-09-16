#Todo List
- [] 강의평가 하기
- [] 기술 블로그 제출하기
- [] 블로그 포스팅 하기

#오늘 배운거
- git flow 실습을 했다.
organization repo를 만들어서 팀원들에게 배포하고 팀원들이 작성한 파일을 하나로 합치는 일을 했다.
거기서 나는 팀장을 맡았지만 팀원으로써의 역할도 수행하고 싶어서 둘다 진행했다.
- 생성부터 배포까지의 과정(팀장 입장)
	1. organizations 생성하기
	2. 생성한 organization에서 repository 생성하기
	3. 생성후 clone 하기
	4. README.md 작성하기
	5. 새파일 생성 (우리의 주제는 blackjack이어서 blackjack.md 파일을 만들었다.)
	6. git status (git push 까지 끝낸 깨끗한 상태여야함)
	7. git flow init
	8. develop 브런치가 생성된 것을 확인후 팀원들을 초대한다.

- organizaiton 초대 받은 후(팀원 입장)
	1. 초대 받은 후 fork 한다. (organization에서 내 git으로 복사함)
	2. issues를 작성한다.
	3. git clone
	4. git flow init
	5. develop 브랜치가 생성 되었고 받아온 프로젝트와 일치하는지 확인한다.
	6. git flow feature start blackjack 
	7. 프로젝트를 수행한다.(add, commit 까지 완료하기)
	8. git flow feature finish blackjack
	9. develop 브랜치에 잘 써졌는지 확인하고 push 한다.
	10. push후 pull request를 생성한다.

- pull request 이후 (팀장 입장)
	1. pull request를 확인한다.
	2. 최종 파일에서 코드 리뷰를 한다. 
	3. 피드백 시간
	4. 피드백이 반영 되면 merge 한다.
	5. git flow release start v0.1
	6. git flow release finish v0.1
	7. main에 파일이 잘 적용 되어 있는지 확인하고 git push origin main
	8. git push --tags 도 해준다.


