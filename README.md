# 음성 인식을 활용한 게임 제작 (Voice Controlled Game)
> **로딩 프로덕션 (Loading Production)**
> AI·SW 캡스톤디자인: 사용자의 음성 명령과 LLM을 결합한 지시자-수행자 방식의 게임 프로젝트

---

## 1. 프로젝트 개요 (Project Overview)
기존의 키보드/마우스 입력에서 벗어나, **사용자의 음성(STT)**을 통해 캐릭터를 조작하는 게임
단순히 특정 단어를 매칭하는 것이 아니라, **LLM API**를 활용하여 플레이어의 다양한 발화 의도를 해석하고 게임 내 행동으로 연결

- **개발 기간**: 2025.09 ~
- **주요 특징**: 
  - 지시자(플레이어)와 수행자(캐릭터) 간의 상호작용 극대화
  - LLM을 활용한 자연어 명령 해석 및 매핑
  - Unity 엔진 기반의 유연한 조작 시스템 구축

---

## 2. 팀원 및 역할 (Team Members)
| 성명 | 역할 | 상세 업무 |
| :--- | :---: | :--- |
| **안정빈 (팀장)** | 기획 및 총괄 | 프로젝트 매니징, 문서 작성, 시스템 기획 |
| **원용준 (팀원)** | 메인 개발 | Unity 게임 로직 설계, 음성 인식(STT) 모듈 구현 |
| **김민우 (팀원)** | 개발 및 리소스 | LLM API 연동 및 데이터 처리, 사운드 에셋 관리 |

---

## 3. 기술 스택 (Tech Stack)
### Environment
<img src="https://img.shields.io/badge/Unity-FFFFFF?style=flat-square&logo=Unity&logoColor=black"/> <img src="https://img.shields.io/badge/C%23-239120?style=flat-square&logo=c-sharp&logoColor=white"/> <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white"/>

### Technology & Logic
- **Backend Logic**: API-based Stateless Architecture (C#)
- **AI Interface**: LLM API (OpenAI GPT) for Intent Analysis
- **STT**: Voice-to-Text Integration
- **Sound**: Cakewalk for BGM & SFX

---

## 4. 프로젝트 구조 (Project Structure)
```text
.
├── docs/               # 프로젝트 관련 문서 (결과보고서 등)
├── src/                # Unity 프로젝트 소스 코드 (.cs)
├── assets/             # 게임 리소스 (Sprites, Audio, Prefabs)
│   ├── Audio/          # BGM 및 효과음
│   └── Sprites/        # 캐릭터 및 배경 이미지
├── .gitignore          # Git 제외 파일 설정
└── README.md           # 프로젝트 소개
