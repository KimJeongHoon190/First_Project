# First_Project


```mermaid
gantt
    title 프로젝트 일정표
    dateFormat  YYYY-MM-DD
    section 문서화
    제안서 작성  : a1, 2023-08-15, 1d
    구성도 작성  : after a1, 1d
    설치 메뉴얼 : after a2, 12d
    시연 PPT 준비 : after a3, 2d

    section 구현
    네트워크     : b1, 2023-08-17, 1d
    서버(도커) : b2, 2023-08-21, 1d
    서버(젠킨스) :after b2 , 1d
    서버(쿠버네티스) : after b3, 1d
```