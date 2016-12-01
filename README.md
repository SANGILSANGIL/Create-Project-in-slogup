# Create Project

_이 포스트는 앱개발에서 가장 기본이 되는 sg-core-new와 sg-app-new로 작성할 것이다.
프로젝트 중간에 참여 한다면 app을 참여할 project로 clone하면 된다._

1. sg-core-new clone  
	프로젝트의 기반이 되는 core를 클론한다.
	
	```bash
	#core앱  클론
	git clone https://github.com/teamslogup/sg-core-new.git www
	cd www
	sudo npm install
	```

2. sg-app-new clone  
	사용할 app을 클론한다.
	
	```bash
	git clone https://github.com/teamslogup/sg-app-new.git app
	cd app
	
	#의존 라이브러리 설치
	sudo npm install
	```
	
3. 실행
	실행 시 webpack 빌드 후 실행한다.
	
	```bash
	sudo npm run build-dev
	```
	
