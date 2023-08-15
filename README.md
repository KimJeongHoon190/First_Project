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
    네트워크     :a1,2023-08-17  , 1d
    서버(도커) : after a1,  1d
    서버(젠킨스) :after a1 , 1d
    서버(쿠버네티스) : after a1

    section Back-end
    django 학습 및 적용 : a1,2020-10-14 , 10d
    회원기능      :a2,after a1 , 10d
    친구기능      :after a1  ,10d
    결과 이미지저장,공유  : a3,after a2, 2d
    스티커 기능  : a4,after a3, 2d
```