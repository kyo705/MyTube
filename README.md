# VOD-Service
유튜브와 같이 웹에서 VOD 서비스를 제공하는 프로젝트


프로젝트 내 적용 기술
-----------------------------------------
> - 백 앤드
>   - 언어 : Java
>   - 프레임 워크 : SpringBoot, Spring MVC, Spring Security, Spring Session
>   - ORM : JPA(Hibernate)
> - DevOps
>   - WAS : Tomcat
>   - Cache : Redis
>   - DBMS :
>      - 실제 서버 환경 : MariaDB
>      - 테스트 환경 : h2
>   - Codec : ffmpeg
>   - Message Queue : Kafka


프로젝트 구성 서버
-------------------------
### 1. [**VOD Service Server**](https://github.com/kyo705/VOD-Service-Server) : 웹으로 VOD 서비스를 제공하는 서버
### 2. [**Uploading Server**](https://github.com/kyo705/Video-Uploading-Server) : VOD 서비스에서 유저의 파일 업로드를 처리하는 서버
### 3. [**Transcoding Server**](https://github.com/kyo705/Video-Transcoding-Server) : 기본 동영상 파일을 웹에서 스트리밍하도록 동영상 인코딩하는 서버

