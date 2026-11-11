# KANG SUJI PORTFOLIO

Vue 3 · TypeScript로 클라우드·GPU·가상화 인프라 관리 플랫폼을 만들어 온 **프론트엔드 개발자 강수지**의 포트폴리오 사이트입니다.

**사이트 바로가기 → https://kangsujiportfolio.netlify.app/**

## 소개

- 프론트엔드 개발 경력 4년 4개월
- 이기종 클라우드·GPU·가상화 관리 플랫폼 3종(SPINEL, JADE, P-CMP), 9개 버전의 프론트엔드 개발
- 동일 API 3회 중복 호출을 Pinia store 공유 구조로 바꿔 대시보드 API 호출 수 67% 감소
- 목록 공통 툴킷(11개 화면), Job 관리 유틸(23개 화면) 등 팀 공통 컴포넌트 설계·개발
- 3개 클러스터, 30개 이상 노드의 서비스 맵 렌더링 지연을 초기 조회 범위 제한으로 개선

**주요 기술**: Vue 3, TypeScript, Pinia, Quasar, ECharts, d3.js, Socket.IO, jsPDF, exceljs, html2canvas, Turborepo, GitLab Runner, Git, Docker, Jenkins

## 페이지 구성

| 페이지 | 내용 |
| --- | --- |
| [Home](https://kangsujiportfolio2023.netlify.app/) | 실무 프로젝트 슬라이더, 기술 스택 |
| [About](https://kangsujiportfolio2023.netlify.app/about.html) | 기본 정보, 경력 요약, 기술별 경험, 교육, 연락 폼 |
| [Project](https://kangsujiportfolio2023.netlify.app/project.html) | 프로젝트별 핵심 성과와 세부 업무 |
| [Profile](https://kangsujiportfolio2023.netlify.app/profile.html) | 경력 · 자격증 · 교육 · 학력 · 자기소개 |

### 수록 프로젝트

**(주)예스씨앤씨** · 2023.06 ~ 재직 중

| 프로젝트 | 기간 | 주요 내용 |
| --- | --- | --- |
| P-CMP v1.0~v1.3 | 2025.11 ~ 현재 | Proxmox 기반 가상화 통합 제어 플랫폼. 대시보드 API 호출 67% 감소, Job 관리 공통 유틸(23개 화면) |
| JADE v1.3 (IDC-CMP) | 2025.06 ~ 2025.09 | 외부 대시보드 솔루션 미터링 기능 내재화, 엑셀 의존 자원 등록을 GUI로 전환 |
| JADE (IDC-BMP) | 2025.02 ~ 2025.05 | 목록 공통 툴킷(11개 화면), 다크모드 구조 설계, GitLab Runner CI 구축 |
| SPINEL v1.2 | 2024.08 ~ 2025.01 | Socket.IO 실시간 자가 진단, AWS 퍼블릭 클라우드 연동 |
| SPINEL v1.1 | 2024.01 ~ 2024.07 | d3.js PaaS 서비스 맵 및 렌더링 개선, TypeDoc API 문서화 |
| SPINEL v1.0 | 2023.06 ~ 2023.12 | IaaS·PaaS 관리 화면, 기간 검색 공통 컴포넌트 |

**아이웹** · 2022.06 ~ 2023.06 — 자사 홈페이지 리뉴얼, 웹 에이전시 퍼블리싱

> 사내 프로젝트는 보안상 소스 코드와 화면을 공개하지 않으며, 사이트에서는 담당 업무와 성과만 소개합니다.

## 이 사이트의 기술 스택

빌드 도구 없이 정적 파일로 구성했습니다.

- HTML5, CSS3, jQuery
- [Swiper](https://swiperjs.com/) — 메인 프로젝트 슬라이더
- [AOS](https://michalsnik.github.io/aos/) — 스크롤 애니메이션
- [Rellax](https://dixonandmoe.com/rellax/) — 메인 텍스트 패럴랙스
- [EmailJS](https://www.emailjs.com/) — About 페이지 연락 폼
- [Simple Icons](https://simpleicons.org/) — 기술 스택 로고 (CC0)
- Netlify 배포

## 로컬 실행

CSS·JS·이미지를 루트 기준 절대경로(`/css/...`)로 불러오기 때문에 파일을 직접 열지 말고 로컬 서버로 실행해야 합니다.

```bash
# VS Code Live Server (포트 5502로 설정됨)
# 또는
python -m http.server 5502
```

브라우저에서 `http://localhost:5502`를 엽니다.

## 폴더 구조

```
portfolio_ver2/
├── index.html        # 메인
├── about.html        # 소개
├── project.html      # 프로젝트 상세
├── profile.html      # 이력
├── css/
│   ├── reset.css
│   ├── index.css     # 공통(헤더·푸터) + 메인
│   ├── sub.css       # 서브 페이지
│   └── responsive.css
├── js/
│   └── index.js      # 공통 스크립트
└── images/
    └── skills/       # 기술 스택 로고(SVG)
```

## 연락처

- E-mail: sukang0608@naver.com
- GitHub: https://github.com/KangSuji
- Blog: https://creambbang0608.tistory.com/
