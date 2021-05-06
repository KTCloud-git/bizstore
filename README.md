# Welcome to KT Cloud Biz 스토어

이 문서는 KT Cloud Biz 스토어<https://cloud.kt.com/bizstore>와의 연동을 위해 사용합니다

연동 대상은 KT Cloud Biz 스토어의 Web server와 API server입니다

## 알아두기

- VisualStudio Code를 다운받아 문서를 열기를 권장합니다

- 하단 "문서 구성 내역"의 Diagram은 yuml VisualStudio Code의 yuml extention을 설치하시고, API Document는 Swagger.io extention을 설치해 주세요

- API Document의 기본 규격은 Open api입니다

- Bizstore 연동 시, **SSO Key**는 **kt Cloud 포탈의 MEM-SQ**로 지정되어 있습니다.

## 문서 구성 내역

- API Document: [kt-cloud-biz-store-2.0.0.yaml](https://github.com/KTCloud-git/bizstore/blob/main/kt-cloud-saas-1.0.3-oas3.yaml) 또는 [Swagger UI](https://app.swaggerhub.com/apis-docs/KTCloud-git/bizstore/2.1.2)로 보기
  - 토큰 발급 관련 다이어그램 [kt-cloud-bizstore-token-management.yuml](https://github.com/KTCloud-git/bizstore/blob/main/diagram/kt-cloud-bizstore-token-management.svg)
    - JWT 정의문서: [링크](https://jwt.io/#debugger-io?token=eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1lIjoia3QgY2xvdWQgYml6IHN0b3JlIiwiaWF0IjoxNjEzMjM5MDIyfQ.Aj4dRXjzLyobZQTpxOO3p66Dq5mrBPKCb5XtD-gmhxI128la6p_CdKzLI7X2j_eFFRXQL2zf8Q7tZ2NcTJ8Pz7nq1xitp77JsBLCNBjvOqKwEmIf9R3kci2uJinkGj-xiGq3gplBOZ0jeBKv60Lt1nmKZ-LvmFh_Kf3WMTwFDOVlrwPgvXYMK4qyyCRG3JGFTjMQNX7JrNnoUfU9D8lDDsAI21fksmSU_SHEVJnc172VfXOt2UMb4eAcBP3Sk8x6MEwGXQXKp2ltEhh3NNMgY7VaKD7iPEg1--D_9g_7XuVmAqkUhm3ZcAo6dKgdXA9t99xh8TY3cbsY_QEv4dyqbQ&publicKey=-----BEGIN%20PUBLIC%20KEY-----%0AMIIBIjANBgkqhkiG9w0BAQEFAAOCAQ8AMIIBCgKCAQEAnzyis1ZjfNB0bBgKFMSv%0AvkTtwlvBsaJq7S5wA%2BkzeVOVpVWwkWdVha4s38XM%2Fpa%2Fyr47av7%2Bz3VTmvDRyAHc%0AaT92whREFpLv9cj5lTeJSibyr%2FMrm%2FYtjCZVWgaOYIhwrXwKLqPr%2F11inWsAkfIy%0AtvHWTxZYEcXLgAXFuUuaS3uF9gEiNQwzGTU1v0FqkqTBr4B8nW3HCN47XUu0t8Y0%0Ae%2Blf4s4OxQawWD79J9%2F5d3Ry0vbV3Am1FtGJiJvOwRsIfVChDpYStTcHTCMqtvWb%0AV6L11BWkpzGXSW4Hv43qa%2BGSYOD2QU68Mb59oSk2OB%2BBtOLpJofmbGEGgvmwyCI9%0AMwIDAQAB%0A-----END%20PUBLIC%20KEY-----)
    - Token은 10분 마다 갱신  
  - 서비스 신청 및 SSO : [kt-cloud-bizstore-register-sso.yuml](https://github.com/KTCloud-git/bizstore/blob/main/diagram/kt-cloud-bizstore-register-sso.svg)
  - 서비스 탈퇴 : [kt-cloud-bizstore-resign.yuml](https://github.com/KTCloud-git/bizstore/blob/main/diagram/kt-cloud-bizstore-resign.svg)
  - 과금정보 요청 : [kt-cloud-bizstore-customer-bill.yuml](https://github.com/KTCloud-git/bizstore/blob/main/diagram/kt-cloud-bizstore-daily-bill.svg)
  - 상태확인 요청 : [kt-cloud-bizstore-check-status.yuml](https://github.com/KTCloud-git/bizstore/blob/main/diagram/kt-cloud-bizstore-check-status.svg)
    - 상태확인 요청 API를 통해 관리포탈에서 실시간 확인 가능


## 저자

1. KT Cloud 플랫폼개발팀 장용운 과장(yongwoon.jang@kt.com)

2. KT Cloud 플랫폼개발팀 김한슬 대리(kim.hanseul@kt.com)
