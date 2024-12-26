### github란?

인터넷 상에 있는 코드(원격) 저장소입니다.
=> 컴퓨터마다 작업한 각가의 로컬 저장소를 하나의 원격 저장소로 업로드 하는 행위

### 레포지토리

프로젝트 저장소

github => 클라우드 드라이브 
레포지토리 => 프로젝트 폴더

github안에 많은 레포지토리(폴더)가 있는 것.

### Git 과 Github 차이


Git은 버전(시점)관리 도구.
Github는 Git을 기반으로 하는 원격 저장소 플랫폼

- 원격 저장소 명령어 


git remote add origin 

`나 너가 만든 github의 특정 레포지토리에 연결할건데 이름은 origin으로 할게`

git push origin main

로컬의 main 브랜치를 원격 저장소의 origin 으로 넣습니다.

git push -u origin main 

로컬의 main 브랜치를 원격 저장소의 origin 으로 넣겠다. 근데, 이 브랜치(main)을 추적 브랜치로 설정.

## 비밀번호 입력 오류 

github는 2021년 8월 13일 부터 HTTPS(깃허브 비밀번호)를 이용한 비밀번호 인증 수단이 종료되었습니다. 
그래서 당연히 에러가 나는겁니다.
그래서 personal Access Token(PAT)라는 방식으로 인증해야 함.