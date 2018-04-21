### 봄이네집 스프링 - (1) Spring Security + Auth0 JWT Library
---

#### 안녕하세요.

안녕하세요.

봄이네집 스프링의 첫 세션입니다.

이번 세션에서는 Spring Security의 기본 개념을 알아보고, 레퍼런스 문서를 함께 읽습니다. 또 내장된 기본 구현체들을 까 보는(?) 시간도 가질 예정입니다.

또한 Auth0 Java-JWT( https://github.com/auth0/java-jwt )를 사용해 JWT를 발급하고, 인증하는 방법을 알아봅니다. 소셜 공급자 연동도 간단히 맛봅니다.

감사합니다!

[방송 바로가기](https://www.youtube.com/watch?v=SMZm2aqI_dQ)

---
#### Account 객체 요구사항

* 기본적인 유저 정보

    * 아이디, 비밀번호, 이름, 프사 링크(profileHref)
    * 서비스상에서 유저에게 부여하고싶은 권한 
    * 소셜 로그인한 사용자의 경우, 소셜 서비스가 부여한 ID 코드 **(로그인 ID 아님)**