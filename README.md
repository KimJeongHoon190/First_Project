# First_Project

```mermaid
gantt
    title 프로젝트 일정표
    dateFormat  YYYY-MM-DD
    section 문서화
    제안서 작성 : a1, 2023-08-15, 1d
    구성도 작성 : after a1, 1d
    설치 메뉴얼 작성 : after a1, 2023-08-17, 9d
    시연 PPT 준비 : after a1, 2023-08-21, 3d
   

    section 구현
    네트워크 구성 : b0, 2023-08-16, 1d
    서버(NFS) 구축 : b1, 2023-08-17, 1d
    서버(Docker-registry) 구축 : b2, 2023-08-18, 2d
    서버(Jenkins) + 서버(Ngrok) 구축 : after b1, 2023-08-19, 2d
    서버(SonarQube) 구축 : b3, 2023-08-20, 3d
    프로젝트 보완 : after b3, 1d
```