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

- **지원 금액**: 2,700,000원 (VAT 별도) — 클라이언트 예상 3,000,000원의 90%
- **지원 기간**: 20일 (계약 즉시 착수)
- **핵심 제안 포인트**:
  1. 참고 사이트(overview.ai) IA·전환 동선·신뢰 요소를 분석한 3 메뉴 압축 설계
  2. HubSpot CMS Hub 우선 제안 — CRM 동일 환경 = 별도 미들웨어 없이 마케팅 자동화 즉시 가능
  3. 블로그 확장 기반 사전 셋업 (Listing/Post 템플릿, 카테고리/태그, RSS, SEO 자동화)
  4. B2B 50+ 페이지 포탈 / CMS 운영 노하우를 20일에 안정적 압축 납품
  5. HubSpot 활용이 어려운 경우 WordPress / 아임웹 대안 제안 (블로그 확장성 동일 보장)

## 6. 최종 산출물 (8단계 출력 전문)

(8단계 완료 후 추가)
