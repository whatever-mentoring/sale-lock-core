# sale-lock-core

## 8. Git 브랜치 전략

### 브랜치 구조
* **main**: 제품 출시 버전을 관리하는 메인 브랜치 (배포 환경에 적용)
* **develop**: 개발 버전을 관리하는 브랜치 (개발 환경에 적용)

### 개발 워크플로우
1. 개발자는 origin repository를 개인 GitHub 계정으로 fork
2. 로컬에서 기능 개발 완료 후 개인 repository에 push
3. origin의 develop 브랜치로 Pull Request 생성
4. 코드 리뷰 후 승인되면 develop 브랜치에 merge
5. 배포 준비가 완료되면 develop 브랜치를 main 브랜치로 merge하여 배포

### 브랜치 규칙
* 모든 코드 변경은 PR을 통해 진행
* PR은 최소 1명 이상의 리뷰어 승인 필요
* main 브랜치는 항상 배포 가능한 상태 유지
* develop 브랜치는 다음 배포를 위한 기능을 포함
