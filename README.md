# MyTube
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


## 시퀀스 다이어그램

### 1. 업로드 시퀀스 다이어그램

![upload_sequence_diagram](https://github.com/kyo705/MyTube/assets/89891704/bcd17ee0-80ea-4a72-b7f0-c928aac3e627)

### 2. 다운로드 시퀀스 다이어그램

## ERD

![vod_service_ERD](https://github.com/kyo705/MyTube/assets/89891704/eae31b45-c52d-44d7-8512-fd01b04b2320)
