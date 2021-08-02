# Welcome to KT Cloud Biz 스토어

이 문서는 KT Cloud Biz 스토어<https://cloud.kt.com/bizstore>와의 연동을 위해 사용합니다

연동 대상은 KT Cloud Biz 스토어의 Web server와 API server입니다

## 알아두기

- VisualStudio Code를 다운받아 문서를 열기를 권장합니다

- 하단 "문서 구성 내역"의 Diagram은 yuml VisualStudio Code의 yuml extention을 설치하시고, API Document는 Swagger.io extention을 설치해 주세요

- API Document의 기본 규격은 Open api입니다

- Bizstore 연동 시, **Primary Key**는 **KT Cloud 포탈의 E-mail**로 지정되어 있습니다.

## 문서 구성 내역

- API Document: [kt-cloud-biz-store-2.0.0.yaml](https://github.com/KTCloud-git/bizstore/blob/main/kt-cloud-saas-1.0.3-oas3.yaml) 또는 [Swagger UI](https://app.swaggerhub.com/apis-docs/KTCloud-git/bizstore/2.1.2)로 보기
  - 서비스 신청 및 SSO : [kt-cloud-bizstore-register-sso.yuml](https://github.com/KTCloud-git/bizstore/blob/main/diagram/kt-cloud-bizstore-register-sso.svg)
  - 서비스 탈퇴 : [kt-cloud-bizstore-resign.yuml](https://github.com/KTCloud-git/bizstore/blob/main/diagram/kt-cloud-bizstore-resign.svg)
  - 과금정보 요청 : [kt-cloud-bizstore-customer-bill.yuml](https://github.com/KTCloud-git/bizstore/blob/main/diagram/kt-cloud-bizstore-daily-bill.svg)
  - 상태확인 요청 : [kt-cloud-bizstore-check-status.yuml](https://github.com/KTCloud-git/bizstore/blob/main/diagram/kt-cloud-bizstore-check-status.svg)
  - 상태확인 요청 API를 통해 관리포탈에서 실시간 확인 가능


## 저자

1. KT Cloud 플랫폼개발팀 장용운 과장(yongwoon.jang@kt.com)
