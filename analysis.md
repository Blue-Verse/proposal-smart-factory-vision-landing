# 스마트 팩토리 비전 검사 서비스 소개 홈페이지 개발 — 제안 분석 로그

> 생성일: 2026-04-29
> 공고 URL: https://www.wishket.com/project/154955/

## 1. 공고 파싱 결과

```yaml
job:
  title: "스마트 팩토리 비전 검사 서비스 소개 홈페이지 개발"
  category: "웹 / 홈페이지·게시판 / 랜딩·소개 페이지"
  budget_range: "3,000,000원"
  duration: "20일"
  tech_stack:
    - "HubSpot CMS Hub (우대)"
    - "WordPress / 아임웹 등 대안 CMS"
    - "반응형 웹 (PC/Mobile)"
  description: "스마트 팩토리 비전 검사 서비스 시장 확대를 위한 B2B 산업 솔루션 랜딩 페이지 신규 구축. HubSpot CRM 운영 중이므로 동일 환경에서 구축 우대."
  requirements:
    - "참고 사이트(overview.ai) 절반 규모, 핵심 3 메뉴"
    - "회사/서비스 소개, 주요 기술/솔루션, 문의하기 페이지"
    - "HubSpot CMS Hub 활용 (또는 동급 대안 — 블로그 확장성 보장)"
    - "문의 폼 → HubSpot CRM 자동 연동 (우대)"
    - "향후 블로그 기능 확장 기반 마련"
    - "PC/Mobile 반응형 구현"
    - "디자인 가이드는 클라이언트 내부 제공 → 구현 위주"
  client_questions: []
  deadline: "2026-05-13"
  job_post_url: "https://www.wishket.com/project/154955/"
  urls:
    - "https://www.overview.ai/"
  images: []
```

## 2. URL/이미지 분석

### overview.ai (참고 사이트)
- **사이트 유형**: 글로벌 산업용 AI 비전 검사 솔루션 기업의 마케팅 홈페이지
- **IA / 메뉴 구조**: Products(스마트 카메라 OV10i/OV20i/OV80i, GenAI 도구) / Solutions(산업·유스케이스·케이스 스터디) / Company / Resources(블로그·러닝센터·비디오)
- **메인 페이지 섹션**:
  1. Hero — "AI Vision Leader in Manufacturing" 슬로건 + 데모 요청 CTA
  2. Product Showcase — 카메라 3종 + GenAI 소프트웨어
  3. Differentiation — "Built to Deploy Fast / Zero-Escapes" 카피 카드
  4. Global Deployment Stats (수치 카드)
  5. Use Cases — Assembly verification, Defect detection, Multi-point inspection
  6. Customer Logos (Toyota, Honda, Tyson 등 신뢰 요소)
  7. Testimonial 인용
  8. CTA + Footer
- **디자인 스타일**: 클린/프로페셔널, 제품 이미지 비중 높음, 미니멀 타이포그래피, 중성 톤 컬러, 명확한 CTA
- **기술 단서**: NVIDIA GPU, Edge computing, Sub-100ms inference, Industrial protocol 강조 → B2B 산업 도메인의 신뢰감 표현 방식 참고
- **폼/CTA 패턴**: "Schedule a Demo" CTA가 사이트 전반에 반복, 직접 이메일/전화 노출

### 본 프로젝트 반영
- 절반 규모로 압축 → 3 메뉴(소개/기술·솔루션/문의)에 핵심 신뢰 요소(고객 로고, 도입 효과, 핵심 가치)만 선택 반영
- "Schedule a Demo" 패턴을 "문의하기" CTA로 미러링하여 HubSpot Form-CRM 연결
- 전문 용어를 신뢰감 있게 전달하는 정보 위계로 IA 설계

## 3. 실현 가능성 분석 (내부용)

- **프로젝트 유형**: FE 중심 웹 (랜딩 페이지) → **강력 추천**, 버퍼 +0%
- **기본 공수 (AI 보조 없이)**: 17.5 M/D
  - 기획/IA: 2 M/D
  - HubSpot 셋업/디자인 적용: 4 M/D
  - FE 개발 (3 메뉴 + 공통 + 반응형): 6 M/D
  - 폼-CRM 연동: 1.5 M/D
  - 블로그 확장 기반: 1 M/D
  - QA/배포: 3 M/D
- **AI 절감률 적용 (50%)**: 8.75 M/D ≈ 9 M/D
- **버퍼 +0%** (FE 중심 강력 추천): 9 M/D
- **달력 일수**: 9 × (7/5) = 12.6일 ≈ 13일
- **클라이언트 예상 기간 vs 산정 기간**: 20일 vs 13일
- **판정**: 산정 기간 ≤ 클라이언트 기간 → 클라이언트 기간(20일) 그대로 사용 (서두를 필요 없음, 콘텐츠 입력·검수 여유 확보)

## 4. 포트폴리오 매칭

| 프로젝트 | 매칭 점수 | 매칭 근거 |
|---------|----------|----------|
| EZ-Approve | 90/100 | 50+ 페이지 B2B SaaS, 모듈 기반 콘텐츠 관리, 비개발자 운영 가능한 구조 — HubSpot 모듈 설계와 동일 철학 |
| Series-B | 92/100 | 50+ 페이지 B2B 포탈, 통합 콘텐츠 관리, 폼 → 백오피스 자동 연동 → HubSpot Form-CRM 연동에 직접 적용 가능 |
| Harmony Link | 85/100 | B2B SaaS 콘텐츠/공지/안내 관리, 반응형 웹, 호스팅/DNS/SSL 인프라 셋업 노하우 → HubSpot CMS 도메인 연결 |

## 5. 최종 제안 요약

- **지원 금액**: 2,550,000원 (VAT 별도) — 클라이언트 예상 3,000,000원의 85%
- **지원 기간**: 20일 (계약 즉시 착수)
- **핵심 제안 포인트**:
  1. 참고 사이트(overview.ai) IA·전환 동선·신뢰 요소를 분석한 3 메뉴 압축 설계
  2. HubSpot CMS Hub 우선 제안 — CRM 동일 환경 = 별도 미들웨어 없이 마케팅 자동화 즉시 가능
  3. 블로그 확장 기반 사전 셋업 (Listing/Post 템플릿, 카테고리/태그, RSS, SEO 자동화)
  4. B2B 50+ 페이지 포탈 / CMS 운영 노하우를 20일에 안정적 압축 납품
  5. HubSpot 활용이 어려운 경우 WordPress / 아임웹 대안 제안 (블로그 확장성 동일 보장)

## 6. 최종 산출물 (8단계 출력 전문)

### 제안서 사이트 URL
https://proposal-router.claude-ai-b27.workers.dev/proposal-smart-factory-vision-landing/

### 지원 금액
2,550,000원

### 지원 기간
20일

### 클라이언트 질문 답변

**Q: 유사한 프로젝트를 수행한 경험이 있다면 무엇입니까?**

네, B2B 기업 사이트·콘텐츠 관리 시스템·폼-CRM 연동 영역에서 다수의 유사 프로젝트를 수행하였습니다.

▶ Series-B — VC 펀드 관리 포탈 (2023.11~2024.12)
- B2B 50+ 페이지 규모의 마케팅·정보 포탈 구축
- 다국어(국문/영문) 통합 콘텐츠 관리, 22개 도메인 모듈 모듈형 설계
- 폼 제출 → 백오피스 자동 연동(리드 생성·알림 워크플로우) — 본 건 HubSpot Form-CRM 연동에 직접 적용 가능
- 기술: Next.js 13, NestJS 10, MySQL, AWS

▶ EZ-Approve — 전자결재 SaaS 플랫폼 (2026.01~2026.03)
- 50+ 페이지 B2B SaaS, 비개발자가 콘텐츠를 직접 운영하는 모듈 기반 구조 — HubSpot 모듈 설계와 동일 철학
- 리치 에디터 기반 콘텐츠 관리(170 파일, 26 커스텀 노드), 다국어 통합 관리
- 반응형 웹(PC/Mobile) 풀스택 구축
- 기술: Next.js 13, NestJS 10, TypeScript, MySQL 8, Lexical, MUI v5

▶ Harmony Link — 시니어 주간보호 관리 플랫폼 (2025)
- B2B SaaS — 콘텐츠/공지/안내 통합 관리 시스템 구축
- 다국어 키 2,532개·140+ API, 반응형 웹 + 호스팅/DNS/SSL 인프라 풀스택 구성(AWS CDK)
- HubSpot CMS 도메인 연결·SEO 셋업에 동일 노하우 적용 가능
- 기술: Next.js, NestJS, Flutter, MySQL, AWS CDK, Docker

위 3개 프로젝트 모두 본인이 100% 참여율로 기획부터 배포까지 직접 수행한 사례이며, 본 프로젝트의 핵심 요구사항인 ① B2B 신뢰감 있는 정보 위계 설계 ② 모듈 기반 콘텐츠 관리 ③ 폼 → CRM 자동 연동 ④ 반응형 웹 + 호스팅 셋업 모두 동일하게 적용 가능합니다.

### 지원 내용

안녕하세요, 스마트 팩토리 비전 검사 서비스 소개 홈페이지 개발 프로젝트에 지원합니다.

본 프로젝트에 대한 상세 제안서(견적서, 공수계산서, PRD, 일정, 포트폴리오)를 별도 페이지로 준비하였습니다. 아래 링크에서 확인해 주시면 감사하겠습니다.
▶ 제안서 상세 페이지: https://proposal-router.claude-ai-b27.workers.dev/proposal-smart-factory-vision-landing/
▶ 위시켓 포트폴리오: https://www.wishket.com/partners/p/blueverse1/

---

<프로젝트 진행 제안>

■ 프로젝트 분석
- 스마트 팩토리 비전 검사 서비스의 시장 확대를 위한 B2B 산업 솔루션 랜딩 페이지 신규 구축
- 핵심 3 메뉴(① 회사/서비스 소개 ② 주요 기술/솔루션 ③ 문의하기)를 중심으로 참고 사이트 절반 규모로 구성
- HubSpot CMS Hub 기반 구축으로 기존 HubSpot CRM과 유기적 연동 → 별도 미들웨어 없이 마케팅 자동화 즉시 가능
- 향후 블로그 기능 확장을 고려한 모듈형 구조 설계 (Listing/Post 템플릿, 카테고리·태그·RSS·SEO 자동화 사전 셋업)
- HubSpot 활용이 어려운 경우 WordPress / 아임웹 기반 대안 제안 (블로그 확장성 동일 보장)
- PC/Mobile 반응형 구현 + Lighthouse 성능 점검 포함

■ 작업 일정

[Phase 1 — 킥오프 / 기획] Day 1~3
- 요구사항 인터뷰, 사이트맵·IA 정의, HubSpot 모듈 구조 설계, 콘텐츠 자료 수집 가이드 전달

[Phase 2 — 환경 셋업 / 디자인 적용] Day 4~7
- HubSpot CMS Hub 환경 구성, 도메인/SSL 연결
- 제공 디자인 가이드 → 디자인 토큰(컬러·타이포·간격) 정의
- 헤더/푸터 글로벌 모듈, 베이스 테마 개발

[Phase 3 — 페이지 개발] Day 8~15
- 회사/서비스 소개 → 주요 기술/솔루션 → 문의하기 순으로 반응형(PC/Tablet/Mobile) 마크업 및 HubL 템플릿 개발
- 공통 페이지(404, 폼 제출 완료) 구현

[Phase 4 — CRM 연동 / 블로그 기반] Day 16~17
- 문의 폼 → HubSpot CRM Lead 자동 생성 + 알림 워크플로우 구성
- Blog Listing/Post 템플릿, 카테고리·태그·RSS·SEO 자동화 셋업

[Phase 5 — QA / 배포] Day 18~20
- 크로스 브라우저(Chrome/Safari/Edge) 및 모바일(iOS/Android) 검증, Lighthouse 점검
- GA4 셋업, 최종 배포 및 운영 가이드 전달

■ 마일스톤 및 산출물
- M1 (Day 3): 요구사항 정의서, 사이트맵, HubSpot 모듈 설계서
- M2 (Day 7): HubSpot 환경, 도메인 연결, 디자인 토큰 / 글로벌 모듈
- M3 (Day 15): 3 메뉴 반응형 구현 + 콘텐츠 입력 검수
- M4 (Day 17): 폼 → CRM Lead 자동 생성 검증, 블로그 템플릿 셋업
- M5 (Day 20): 라이브 도메인 배포, 운영 가이드, 1개월 무상 하자 보수 시작

■ 미팅 시 협의 필요 사항
- HubSpot CMS Hub 라이선스 등급 및 접근 권한 공유 방식
- 디자인 가이드/콘텐츠(텍스트·이미지·동영상) 전달 일정 및 형태
- 도메인/DNS 권한 및 연결 방식
- 참고 사이트 대비 구체적으로 우선시할 섹션(고객 로고, 케이스 카드 등)
- HubSpot 외 대안(WordPress/아임웹) 검토 여부
- 향후 블로그 운영 담당자/발행 주기 (운영 가이드 수준 결정)

---

<유사 프로젝트 진행 경험>

▶ EZ-Approve — 전자결재 SaaS 플랫폼 (2026.01~2026.03)
- 프로젝트 유형: B2B SaaS / 기업용 콘텐츠·관리 시스템
- 핵심 기능: 50+ 페이지 규모 어드민/포탈, 모듈 기반 콘텐츠 관리, 다국어(국문/영문), 반응형 웹
- 유사점: 비개발자가 콘텐츠를 직접 운영할 수 있는 모듈형 구조 — HubSpot 모듈 설계와 동일 철학
- 기술 스택: Next.js 13, NestJS 10, TypeScript, MySQL 8, Lexical, MUI v5

▶ Series-B — VC 펀드 관리 포탈 (2023.11~2024.12)
- 프로젝트 유형: B2B SaaS / 50+ 페이지 포탈
- 핵심 기능: 다국어(국문/영문) 통합 마케팅 사이트, 22 도메인 모듈, 폼 → 백오피스 자동 연동, 5계층 보안
- 유사점: B2B 마케팅·정보 사이트 IA 설계 + 폼-백오피스 자동 연동 → HubSpot Form-CRM 연동에 직접 적용
- 기술 스택: Next.js 13, NestJS 10, MySQL, AWS, Lexical

▶ Harmony Link — 시니어 주간보호 관리 플랫폼 (2025)
- 프로젝트 유형: B2B SaaS / 콘텐츠·관리 시스템
- 핵심 기능: 멀티테넌트 콘텐츠 관리, 140+ API, 다국어 키 2,532개, 반응형 웹 + 풀스택 인프라(AWS CDK)
- 유사점: 운영자가 콘텐츠를 직접 관리하는 CMS 구조, 호스팅/DNS/SSL 인프라 셋업 노하우 → HubSpot CMS 도메인 연결에 적용
- 기술 스택: Next.js, NestJS, Flutter, MySQL, AWS CDK, Docker

---

<사용 기술과 툴>

▶ 개발 기술
- CMS: HubSpot CMS Hub (HubL 템플릿, 모듈, Theme), HubSpot CRM Form / Workflow, HubSpot Blog Module
- Frontend: HTML5, CSS3 / SCSS, JavaScript (ES6+), 반응형 (Flexbox / Grid)
- 분석: Google Analytics 4, HubSpot Tracking Code
- SEO: 페이지별 메타·OG 태그, sitemap.xml, robots.txt, RSS
- 대안 솔루션 옵션: WordPress, 아임웹 (블로그 확장성 동일 보장)

▶ 개발 도구 및 인프라
- 버전 관리: GitHub
- CI/CD: GitHub Actions (정적 자산), HubSpot CLI
- 클라우드: HubSpot CMS (호스팅 / CDN / SSL 자동 처리)
- 디자인 핸드오프: Figma

▶ 커뮤니케이션
- 일일 진행 공유: Slack 또는 카카오톡
- 주간 미팅: Zoom / Google Meet
- 문서 공유: Notion 또는 Google Docs
- 이슈 트래킹: GitHub Issues 또는 Linear

### 관련 포트폴리오 추천
1. EZ-Approve — 50+ 페이지 B2B SaaS, 모듈 기반 콘텐츠 관리, 비개발자 운영 구조
2. Series-B — B2B 포탈, 폼 → 백오피스 자동 연동, 통합 콘텐츠 관리
3. Harmony Link — B2B 콘텐츠/공지 관리, 반응형 웹, 호스팅/인프라 셋업 경험
