```
비고: 아래 내용은 템플릿으로 향후 변동 가능합니다.
```
# Welfind 🧭

> 지역사회 복지 자원을 빠르고 정확하게 자동으로 조사하는 AI 기반 지도 서비스


## 📌 소개 (About)

**Welfind**는 복지 사각지대를 줄이기 위해 지역 내 자원(공공기관, 민간서비스, 지원정책 등)을  
자동으로 수집·분류·시각화하는 **AI 기반 자원 조사 자동화 플랫폼**입니다.

사회복지사, 지역 주민, 기관들이 자원을 더 쉽게 찾고 연결할 수 있도록 돕습니다.


## 🚀 핵심 기능 (Key Features)

- 🔍 **자원 크롤링 자동화**: 지역명/분류 기반 AI 자원 탐색
- 🧠 **자원 분류/요약 AI**: GPT/Embedding 기반 자동 카테고리화
- 🗺️ **자원 지도 시각화**: 사용자가 이해하기 쉬운 형태로 제공
- 🏢 **공공 데이터 연계**: 공공 API 및 CSV 자동 통합
- 📚 **사례관리 통합 연계** (예정): 기관·사례 관리 연동 기능 계획


## 🛠 기술 스택 (Tech Stack)
| 영역        | 기술                              |
|-------------|-----------------------------------|
| 프론트엔드  | React, Vite, TanStack Router      |
| 백엔드      | Spring Boot, JPA, PostgreSQL      |
| AI/자동화   | OpenAI GPT, LangChain, Python Crawling |
| DB/저장소   | pgvector, Redis                   |
| 배포/인프라 | AWS (EC2, S3, RDS), Nginx, Docker |
| 기타        | GitHub Actions, Figma, Cloudflare |

---

## 📁 프로젝트 구조 (Project Structure)

```bash
welfind/
├── frontend/        # React 기반 프론트엔드
├── backend/         # Spring Boot 백엔드 API
├── ai-engine/       # 자원 분석/자동화 파이프라인
├── docs/            # 제안서, 발표자료 등
└── README.md
