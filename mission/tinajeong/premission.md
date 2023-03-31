1. 컨테이너 기술이란 무엇입니까? (100자 이내로 요약)

- 디펜던시를 비롯한 각종 설정을 포함해 어플리케이션을 `패키징` 하는 방법이다.
- 이식성_Portability_이 있는 형태로 다양한 머신 위에서 돌아갈 수 있다.
- 컨테이너는 host os에 존재하는 프로세스들과는 완전히 독립된 형태의 프로세스이다.

2. 도커란 무엇입니까? (100자 이내로 요약)

- docker는 물리적인 machine 위에 다양한 resource들이 `일관되게` 돌아갈 수 있도록 지원해주는 플랫폼이다. 


3. 도커 파일, 도커 이미지, 도커 컨테이너의 개념은 무엇이고, 서로 어떤 관계입니까?

- docker file은 docker image를 구축하기 위한 청사진이다. docker file에 환경을 정의한다.
- docker image는 docker container를 실행하기 위한 템플릿이다. 변경 불가능한 스냅샷으로 동작하는 환경을 구축하기 위한 세팅이다.
- docker container는 프로세스이다.

4. [실전 미션] 도커 설치하기 (참조: [도커 공식 설치 페이지](https://docs.docker.com/engine/install/))
- 아래 `도커 설치부터 실행 튜토리얼`을 참조하여 도커를 설치하고, 도커 컨테이너를 실행한 화면을 캡쳐해서 Pull Request에 올리세요.
