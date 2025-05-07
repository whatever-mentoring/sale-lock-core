# sale-lock-core

## 7. Gradle 멀티 모듈 프로젝트 구조

```
sale-lock-system/
├── api-server/                     # API 서버 모듈
├── admin-server/                   # 관리자 서버 모듈
├── integration-service/            # 외부 시스템 통합 모듈
├── shared/                         # 공통 모듈
├── build.gradle.kts                # 루트 프로젝트 빌드 스크립트
├── settings.gradle.kts             # 프로젝트 설정 스크립트
├── gradlew                         # Gradle 래퍼 실행 스크립트 (Unix)
└── gradlew.bat                     # Gradle 래퍼 실행 스크립트 (Windows)
```
