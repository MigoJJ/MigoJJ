# 👋 Welcome to MigoJJ's Source Hub

> EMR 소프트웨어 시스템, 의료 신호 머신러닝 파이프라인, 그리고 임상 자동화 유틸리티를 통합 관리하는 중앙 디렉토리 대시보드입니다.

---

## 🗂️ Project Directory Tree

```text
MigoJJ-SourceRepo/
├── 📂 emr-systems/                                       # EMR 소프트웨어 및 백엔드 연동
│   ├── 📦 [MigoJJ-GDSEMR_ver_1.2001](https://github.com/MigoJJ/MigoJJ-GDSEMR_ver_1.2001)   - 멀티 티어 Gradle 기반 EMR 소프트웨어 워크스페이스
│   ├── 📦 [APIGDSEMR](https://github.com/MigoJJ/APIGDSEMR)                     - EMR 시스템 연동 API 모듈
│   ├── 📦 [AppGDS](https://github.com/MigoJJ/AppGDS)                         - 임상 자동화 유틸리티 앱
│   └── 📦 [Itia_version_1.0](https://github.com/MigoJJ/Ittia_version_1.0)         - 레거시 시스템 버전 1.0
│
├── 📂 medical-ml-analytics/                              # 의료 신호 처리 및 딥러닝 파이프라인
│   ├── 📦 [EKG_GDS](https://github.com/MigoJJ/EKG_GDS)                         - 심전도(EKG) 및 의료 신호 분석 파이프라인
│   └── 📦 [AI_2023.07](https://github.com/MigoJJ/AI_2023.07)                 - 딥러닝 분류 프레임워크 및 모델 레거시
│
├── 📂 clinical-guides-and-tools/                         # 임상 가이드 및 처방 유틸리티
│   ├── 📦 [Guide-ADA2026-Prescription](https://github.com/MigoJJ/Guide-ADA2026-Prescription) - ADA 가이드 기반 처방 지원 시스템
│   └── 📦 [ICD8_ver_011](https://github.com/MigoJJ/ICD8_ver_011)                 - 질병 분류 코드 데이터 가공 유틸리티
│
└── 📂 system-infrastructure/                             # 자동화 및 유틸리티 도구
    ├── 📦 [RoutineCheck](https://github.com/MigoJJ/RoutineCheck)                 - 시스템 루틴 자동화 및 검증 도구
    └── 📦 [VioletBlue](https://github.com/MigoJJ/VioletBlue)                     - 커스텀 유틸리티 시스템
