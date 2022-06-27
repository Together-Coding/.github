# Together Coding

[English](/profile/README-en.md) ∙ [한국어](#together-coding)

*투게더코딩*은 인하대학교 컴퓨터공학과 종합설계 수업에서 [a2tt](https://github.com/a2tt), [boyfromthewell](https://github.com/boyfromthewell), [chasw0326](https://github.com/chasw0326) 세 학생이 2022년 3월 13일부터 6월 15일까지 진행한, '일대다 코딩 수업을 위한 **실시간 코드 공유 서비스**' 프로젝트입니다.

저희는 기존의 협업용 코드 공유 서비스와 전통적인 코딩 수업의 단점을 보완할 수 있는 서비스를 만드는 것을 목표로 하였습니다.

## 주요 기능

- 강의와 수업을 생성하고, 참여 학생들을 관리할 수 있습니다.
- 일반적인 코드 에디터처럼 파일 생성, 읽기, 수정, 삭제를 할 수 있습니다.
- 파일 변경 사항과 커서 위치를 실시간으로 상호 공유합니다.
- 외부 서버를 통해 코드를 실행할 수 있습니다.
- 코드를 참조하는 질의응답을 생성할 수 있습니다.

## 사용 효과

- 수업별로 체계적이고 지속적으로 코드 공유를 관리할 수 있습니다.
- 모든 참여자들은 클라우드 상에 자신만의 프로젝트를 가집니다.
- 코드 수정을 실시간으로 상호 공유하여, 기존 수업의 단방향성을 개선합니다.
- 코드를 참조하는 질의응답을 통하여, 더 효율적이고 직관적으로 질문과 답변을 할 수 있습니다.
- 학생들의 현황을 누적해서 기록할 수 있습니다.
- 수업이 끝나도, 수업 중에 사용된 코드에 언제든지 접근할 수 있습니다.

## 저장소

- [Client](https://github.com/Together-Coding/Client) : 수업 관리를 위한 페이지와 웹 IDE
- [API-Server](https://github.com/Together-Coding/API-Server) : 유저, 인증, 수업과 관련된 API
- [Runtime-Container](https://github.com/Together-Coding/Runtime-Container) : 코드가 실행될 수 있는 도커 컨테이너 이미지
- [Runtime-Agent](https://github.com/Together-Coding/Runtime-Agent) : *Runtime-Container* 안에서 실행되어, SSH relay 와 컨테이너 관리
- [Runtime-Bridge](https://github.com/Together-Coding/Runtime-Bridge) : *Runtime-Container* 를 생성하여 유저에게 할당
- [IDE-Server](https://github.com/Together-Coding/IDE-Server) : IDE 에서의 실시간 이벤트를 처리하는 웹소켓 서버
- [Project-Backup-Lambda](https://github.com/Together-Coding/Project-Backup-Lambda) : 오래된 프로젝트를 Redis 에서 AWS S3 으로 백업
- [Performance-Analysis](https://github.com/Together-Coding/Performance-Analysis) : *IDE-server* 의 성능 평가

## 관련 링크

- [Presentation](https://bit.ly/3zSAWUm)
- [Demo video](https://youtu.be/znzmxhIVmqs)