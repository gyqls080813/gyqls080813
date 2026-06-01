<style>
  @import url('https://cdn.jsdelivr.net/gh/orioncactus/pretendard/dist/web/static/pretendard.css');
  
  :root {
    --primary: #4F46E5;
    --text-dark: #1e293b;
    --text-muted: #475569;
    --bg-light: #f8fafc;
    --border-color: #e2e8f0;
  }

  body {
    font-family: 'Pretendard', sans-serif !important;
    line-height: 1.65;
    color: var(--text-muted);
    word-break: keep-all;
  }

  /* 헤더 영역 */
  h1 {
    font-size: 2.6em;
    font-weight: 800;
    color: var(--text-dark);
    margin-bottom: 0.1em;
    letter-spacing: -0.03em;
  }
  .job-title {
    font-size: 1.3em;
    font-weight: 700;
    color: var(--primary);
    margin-bottom: 15px;
  }
  .contact-info {
    font-size: 0.95em;
    color: var(--text-muted);
    margin-bottom: 30px;
  }
  .contact-info a {
    color: var(--primary);
    text-decoration: none;
    font-weight: 500;
  }

  /* 섹션 타이틀 */
  h2 {
    font-size: 1.35em;
    font-weight: 800;
    color: var(--text-dark);
    border-bottom: 2px solid var(--text-dark);
    padding-bottom: 6px;
    margin-top: 2.5em;
    margin-bottom: 1em;
    letter-spacing: 0.02em;
  }

  /* 프로젝트 타이틀 및 아이콘 정렬 */
  h3 {
    font-size: 1.15em;
    font-weight: 700;
    color: var(--text-dark);
    margin-top: 1.8em;
    margin-bottom: 0.2em;
    display: flex;
    align-items: center;
  }
  .project-icon {
    width: 22px;
    height: 22px;
    margin-right: 8px;
    border-radius: 4px;
    object-fit: contain;
  }
  
  .project-meta {
    font-size: 0.9em;
    color: #64748b;
    font-weight: 500;
    margin-bottom: 12px;
    display: flex;
    align-items: center;
    gap: 6px;
  }
  .github-link-icon {
    width: 14px;
    height: 14px;
    vertical-align: middle;
    opacity: 0.65;
    margin-right: 3px;
  }

  /* 프로젝트 배너 — 컴팩트하고 자연스러운 인라인 이미지 */
  .project-banner {
    display: flex;
    align-items: center;
    gap: 16px;
    margin: 10px 0 14px 0;
    padding: 12px 16px;
    background: linear-gradient(135deg, var(--bg-light), #eef2ff);
    border: 1px solid var(--border-color);
    border-radius: 10px;
  }
  .project-banner img {
    height: 52px;
    width: auto;
    border-radius: 8px;
    object-fit: contain;
    flex-shrink: 0;
  }
  .project-banner .banner-text {
    font-size: 0.82em;
    color: #64748b;
    line-height: 1.5;
    font-weight: 500;
  }
  .project-banner .banner-text strong {
    color: var(--text-dark);
    font-weight: 700;
    font-size: 1.05em;
  }

  /* 본문 및 리스트 */
  p, li { font-size: 14.5px; color: var(--text-muted); }
  li { margin-bottom: 6px; }
  strong { color: var(--text-dark); font-weight: 700; }
  
  /* 직무 정체성 인용구 */
  .quote-box {
    border-left: 4px solid var(--primary);
    background-color: var(--bg-light);
    padding: 16px 20px;
    margin: 1.2em 0;
    border-radius: 0 8px 8px 0;
    font-size: 1.05em;
    font-weight: 600;
    color: var(--text-dark);
    box-shadow: 0 1px 2px rgba(0,0,0,0.03);
  }

  /* 테크 스택 배지 */
  .skill-row { margin-bottom: 10px; display: flex; align-items: flex-start; }
  .skill-category { font-weight: 700; color: var(--text-dark); width: 130px; flex-shrink: 0; font-size: 14.5px; padding-top: 4px;}
  .skill-badges { display: flex; flex-wrap: wrap; gap: 6px; }
  .badge {
    background: #fff;
    color: var(--text-dark);
    padding: 4px 10px;
    border-radius: 6px;
    font-size: 0.85em;
    font-weight: 600;
    border: 1px solid var(--border-color);
    box-shadow: 0 1px 2px rgba(0,0,0,0.02);
  }

  hr { border: 0; height: 1px; background: var(--border-color); margin: 25px 0; }
</style>

<img src="이민엽.jpg" width="130" align="right" alt="이민엽 프로필 사진" style="border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.08); object-fit: cover;">

<h1>이민엽</h1>
<div class="job-title">Frontend Developer</div>
<div class="contact-info">
  <div style="display: flex; align-items: center; gap: 6px;">
    <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" style="color: var(--primary);"><path d="M20 10c0 6-8 12-8 12s-8-6-8-12a8 8 0 0 1 16 0Z"/><circle cx="12" cy="10" r="3"/></svg>
    경기도 용인시
  </div>
  <div style="display: flex; align-items: center; gap: 6px;">
    <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" style="color: var(--primary);"><rect width="14" height="20" x="5" y="2" rx="2" ry="2"/><path d="M12 18h.01"/></svg>
    010-8807-5927
  </div>
  <div style="display: flex; align-items: center; gap: 6px;">
    <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" style="color: var(--primary);"><rect width="20" height="16" x="2" y="4" rx="2"/><path d="m22 7-8.97 5.7a1.94 1.94 0 0 1-2.06 0L2 7"/></svg>
    gyqls080813@naver.com
  </div>
  <div style="display: flex; align-items: center; gap: 6px;">
    <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" style="color: var(--primary);"><path d="M15 22v-4a4.8 4.8 0 0 0-1-3.5c3 0 6-2 6-5.5.08-1.25-.27-2.48-1-3.5.28-1.15.28-2.35 0-3.5 0 0-1 0-3 1.5-2.64-.5-5.36-.5-8 0C6 2 5 2 5 2c-.3 1.15-.3 2.35 0 3.5A5.403 5.403 0 0 0 4 9c0 3.5 3 5.5 6 5.5-.39.49-.68 1.05-.85 1.65-.17.6-.22 1.23-.15 1.85v4"/><path d="M9 18c-4.51 2-5-2-7-2"/></svg>
    <a href="https://github.com/gyqls080813" target="_blank" style="text-decoration: none;">github.com/gyqls080813</a>
  </div>
</div>

<br clear="all" />

## PROFESSIONAL IDENTITY

<div class="quote-box">
  "단순한 기능 구현을 넘어, 복잡한 데이터 이면의 비즈니스 로직을 구조화하고 끊김 없는 최적의 웹 경험을 치열하게 고민하는 프론트엔드 개발자입니다."
</div>

* **'어떻게 하면 변경에 유연하고 예측 가능한 코드를 작성할 수 있을까?'에 집중합니다.** React와 Next.js 생태계를 깊이 이해하고 관심사 분리(SoC)와 선언적 프로그래밍을 적극 도입합니다. 단순히 화면을 그리는 것을 넘어, 복잡한 도메인 환경에서도 유지보수가 용이하고 확장 가능한 프론트엔드 아키텍처를 설계하는 데 가치를 둡니다.
* **'비동기 통신 환경에서 사용자 경험의 끊김을 어떻게 방어할 것인가?'를 치열하게 고민합니다.** 네트워크 지연 자체를 통제할 수는 없지만, 그로 인한 UX 저하는 방어할 수 있습니다. 다중 API 호출 시 발생하는 데이터 경합(Race Condition)을 제어하고, 점진적 렌더링(Progressive Rendering)을 도입하여 불안정한 환경에서도 매끄럽고 일관된 화면을 보장합니다.
* **'방대한 데이터와 알고리즘을 사용자에게 어떻게 직관적으로 전달할 것인가?'를 고민합니다.** 데이터 분석 및 AI(RL, GAN) 모델링 역량으로 다져진 탄탄한 데이터 리터러시를 갖추고 있습니다. 이를 바탕으로 기획 및 백엔드 직군과 시스템 설계 단계부터 기술적 제약과 해결책을 밀도 있게 논의하며, 비즈니스 목표를 최적의 UI/UX로 타결해 냅니다.

## TECH STACK

<div class="skill-row">
  <div class="skill-category">Frontend</div>
  <div class="skill-badges">
    <span class="badge">React</span><span class="badge">Next.js</span><span class="badge">TypeScript</span><span class="badge">JavaScript</span><span class="badge">Effect-TS</span>
  </div>
</div>
<div class="skill-row">
  <div class="skill-category">State & Data</div>
  <div class="skill-badges">
    <span class="badge">TanStack Query</span><span class="badge">Zustand</span>
  </div>
</div>
<div class="skill-row">
  <div class="skill-category">Styling & UI</div>
  <div class="skill-badges">
    <span class="badge">TailwindCSS</span><span class="badge">Framer Motion</span><span class="badge">Lottie</span><span class="badge">Canvas API</span><span class="badge">Recharts</span>
  </div>
</div>
<div class="skill-row">
  <div class="skill-category">Testing & QA</div>
  <div class="skill-badges">
    <span class="badge">Storybook</span><span class="badge">Playwright</span><span class="badge">Vitest</span><span class="badge">MSW</span><span class="badge">Chromatic</span>
  </div>
</div>
<div class="skill-row">
  <div class="skill-category">Build & Infra</div>
  <div class="skill-badges">
    <span class="badge">Vite</span><span class="badge">Webpack</span><span class="badge">Docker</span><span class="badge">Jenkins</span><span class="badge">Nginx</span>
  </div>
</div>
<div class="skill-row">
  <div class="skill-category">Communication</div>
  <div class="skill-badges">
    <span class="badge">WebRTC</span><span class="badge">WebSocket</span><span class="badge">STOMP</span><span class="badge">SSE</span><span class="badge">REST API</span><span class="badge">GraphQL</span>
  </div>
</div>
<div class="skill-row">
  <div class="skill-category">Data & AI</div>
  <div class="skill-badges">
    <span class="badge">Python</span><span class="badge">Reinforcement Learning</span><span class="badge">TimeGAN</span><span class="badge">PyTorch</span>
  </div>
</div>

## WORK EXPERIENCE & PROJECTS

### Tickle (AI 매크로 탐지 기반 공정 티켓팅 플랫폼)
<div class="project-meta">
  Frontend Leader | 2026.04 - 2026.05 | 6인 (FE 2, BE 2, AI 1, Infra 1) |
  <span>https://github.com/gyqls080813/Tickle</span>
</div>

<div class="project-banner">
  <div class="banner-text">
    <strong>Next.js 16 · React 19 · TypeScript · Zustand · TanStack Query · TailwindCSS 4 · Framer Motion · SSE · Effect Schema · Canvas API</strong><br>
    AI가 실시간으로 매크로 봇을 판별하는 공정한 티켓 예매 플랫폼. 프론트엔드에서 42개 행동 Feature를 수집하여 AI 서버로 전달하는 데이터 파이프라인과 인프라를 직접 설계했습니다.
  </div>
</div>

* **이런 기술적 특징이 있어요.**
  * **행동 데이터 수집 파이프라인 설계:** React 상태 트리와 완전히 격리된 순수 TypeScript 클래스(`TrialCollector`, 729줄)를 설계하여, 마우스 궤적·클릭 타이밍·키보드 입력 등 42개 Feature를 `useRef` 클로저로 재렌더링 없이 축적하고, 세션 종료 시 1회 비동기 전송. **렌더링 횟수 1,886→0회, 네트워크 요청 941→1회로 단축하여 60 FPS 방어**
  * **Canvas 기반 Anti-Bot 좌석 렌더링:** 수천 개 좌석을 DOM이 아닌 단일 `<canvas>` 태그 위에 벡터 드로잉으로만 렌더링하고, 클릭을 좌표 기반 AABB 히트 테스트로 매핑하여 `document.querySelector` 방식의 매크로 스크립트를 프론트엔드 단에서 원천 차단
  * **FE-AI 인프라 직접 구축:** Nginx 경로 분기(`/api/behavior/*` → Ingest 서버), Docker Compose 멀티 컨테이너 구성, Jenkins CI/CD(GitLab Push → Build → SCP → Deploy → Health Check → Mattermost 알림) 파이프라인을 직접 구축
  * **IA(정보 구조) 설계 및 와이어프레임 선행:** 개발 착수 전 역할별(예매자/기획사/관리자) 페이지 계층 구조(IA)를 수립하고, 페이지별 컴포넌트 바운더리를 와이어프레임으로 사전 정의하여 팀 전체가 동일한 구조 위에서 병렬 개발할 수 있는 환경을 조성
* **이런 문제를 해결했어요.**
  * **브라우저 핑거프린팅 기반 1차 봇 필터링:** `navigator.webdriver` 및 DOM 주입 변수 스캐닝으로 Selenium/Playwright 등 기초 자동화 스크립트를 AI 연산 전 단계에서 선제적으로 차단하여 서버 리소스 절감
  * **SSE 기반 실시간 봇 판별 결과 수신:** `useBotDetectionSSE` 훅을 설계하여, AI 서버의 판별 결과(`RETRY_CAPTCHA` / `SUCCESS_CLOSE` / `BOT_BLOCKED`)를 실시간 스트림으로 수신하고 콜백 ref 패턴으로 useEffect 재실행 없이 최신 핸들러를 유지

---

### WITHY (실시간 워치파티 브라우저 익스텐션)
<div class="project-meta">
  메인페이지 구현 / 넷플릭스 익스텐션 구현 | 2026.01 - 2026.02 | 6인 (FE 3, BE 2, AI 1) |
  <span>https://github.com/gyqls080813/WITHY</span>
</div>

<div class="project-banner">
  <img src="Header_Withy.png" alt="WITHY">
  <div class="banner-text">
    <strong>Next.js (React 19) · WXT Framework · TypeScript · Zustand · React Query · STOMP/SockJS · Tailwind CSS · Framer Motion</strong><br>
    넷플릭스 위에서 동작하는 실시간 워치파티 크롬 익스텐션. Cross-World 메시징과 Shadow DOM 기반 스타일 격리를 직접 설계했습니다.
  </div>
</div>

* **이런 기술적 특징이 있어요.**
  * **Cross-World 양방향 메시징 아키텍처:** Content Script(Isolated World)에서 넷플릭스 플레이어 API(`window.netflix...`)에 접근 불가한 한계를 `world: 'MAIN'` 스크립트 주입과 `postMessage` 기반 통신 프로토콜로 극복. 재생/정지/탐색 명령과 idle 상태 변화를 양방향으로 전달하는 구조 설계
  * **Shadow DOM 기반 완전한 스타일 격리:** `createShadowRootUi`로 익스텐션 UI를 Shadow DOM 내부에 렌더링하여 넷플릭스와의 양방향 CSS 오염을 원천 차단하고, 넷플릭스 다층 DOM 노드 5개를 일괄 조정(`adjustLayout`)하여 사이드바 공간 확보
  * **Decoupled Navigation Guard:** SPA 네비게이션, 브라우저 뒤로가기, 새로고침을 모두 가로채는 다층 방어 라우터 가드를 `useGuardedRouter` 훅으로 구현하여 결정론적 세션 정리 보장
* **이런 문제를 해결했어요.**
  * **넷플릭스 이벤트 탈취(Hijacking) 방어:** Capture Phase에서 포커스 이벤트를 선제적으로 감시하여, 채팅 중 넷플릭스 단축키(스페이스바 재생/정지 등)가 입력을 탈취하는 현상을 `stopPropagation`으로 선별 차단. `MutationObserver`로 idle 상태 전환 시 포커스 유실까지 2중 방어
  * **WebSocket 기반 다자간 영상 동기화:** Host 유저의 영상 이벤트를 `useVideoBridge` 훅에서 감지 → WebSocket 서버 전송 → Guest에게 브로드캐스트 → `postMessage`로 Main World에 명령 전달하는 전체 파이프라인 구축. 5초 간격 Heartbeat와 1초 이내 오차 무시 Smart Seek 로직 적용

---

### PETtfolio (반려동물 금융 관리 애플리케이션)
<div class="project-meta">
  Frontend Leader | 2026.02 - 2026.03 | 6인 (FE 2, BE 3, AI 1) |
  <span>https://github.com/gyqls080813/Petfolio</span>
</div>

<div class="project-banner">
  <img src="layer-join-puppy.png" alt="PETtfolio" style="height: 48px;">
  <div class="banner-text">
    <strong>Next.js (React 19) · TypeScript · React Query · Effect-TS · @effect/schema · Tailwind CSS · Framer Motion</strong><br>
    다수의 반려동물과 가족이 공유하는 가계부. Effect-TS 기반 Zero-Trust 방어 아키텍처를 설계하여 런타임 크래시 프리 환경을 달성했습니다.
  </div>
</div>

* **이런 기술적 특징이 있어요.**
  * **Effect-TS 기반 Zero-Trust 방어 아키텍처:** API 응답을 맹신하지 않고, `@effect/schema`로 런타임 스키마 검증을 프론트엔드 최전방에서 수행. 스키마 불일치 시 `ParseError`로 즉시 분류하여 렌더링 크래시 사전 차단
  * **컴파일러 기반 에러 분기 강제화:** `TaggedError` 패턴(`ApiError | NetworkError | UnauthorizedError | ParseError`)으로 에러 타입 계층을 정의하고, `useEffectQuery` 훅 내부에서 `Exit.match`를 활용하여 **에러 분기 누락 시 컴파일 에러를 발생**시키는 구조 설계
  * **Feature-Sliced Design(FSD) + TanStack Query:** 15개 이상의 Feature Module을 도메인별로 분리하고, 중앙집중식 Query Key Factory로 캐시 무효화 시 사이드이펙트 제로 보장. **응답 속도 75% 개선**
* **이런 문제를 해결했어요.**
  * **OAuth 토큰 갱신 Race Condition 해결:** Axios 인터셉터에 **Promise Wait Queue 패턴**을 구현하여, 동시다발적 401 응답 시 단일 갱신 요청만 실행하고 대기 요청을 일괄 재시도
  * **다중 API 병렬 호출 부분 실패 처리:** `Promise.allSettled`와 Partial Success 패턴을 결합하여 특정 API 실패가 전체 화면 로딩을 블록하지 않도록 점진적 렌더링(Progressive Rendering) 적용
* 해당 프로젝트에서는 **MSW 기반의 Mock 서버(36개 핸들러)와 자체 디자인 시스템(18개 공통 컴포넌트)을 선제적으로 구축**하여 프론트-백엔드 병렬 개발 프로세스를 확립했습니다.

---

### 🔬 하수처리장 SBR 공정 폭기(Aeration) 제어 최적화 시뮬레이션
<div class="project-meta">
  데이터 분석 및 AI 모델링 (석사 논문) | 2023.03 - 2025.02 | 
  <span>https://github.com/gyqls080813/optimizing_the_aeration_in_the_sbr_process</span>
</div>

* **상황 및 과제:** 하수처리장(WWTP) SBR 공정의 과도한 폭기로 인한 에너지 낭비를 줄이고 수질을 안정적으로 관리하기 위한 강화학습 기반의 지능형 자동 제어 환경 구축
* **이런 기술적 특징이 있어요.**
  * **DQN 기반 맞춤형 제어 환경 설계:** 센서 데이터를 상태(State)로, 폭기 펌프의 제어를 행동(Action)으로 정의한 커스텀 강화학습 환경(`SBR_Environment`) 구축
  * **TimeGAN 기반 시계열 데이터 증강:** 모델 학습에 필요한 실제 센서 데이터의 희소성 문제를 극복하기 위해 TimeGAN 모델을 도입, 다량의 고품질 가상 시계열 데이터를 생성하여 학습의 안정성 확보
* **이런 문제를 해결했어요.**
  * **비선형적 수질 변화 예측의 정확도 개선:** 센서 노이즈를 제어하기 위해 MLP 및 SGD Regressor 모델을 설계하고 사전 학습(Pre-train)시켜, 펌프 가동량에 따른 오염물질 변화 예측의 신뢰도를 대폭 향상함
  * **다중 목표 최적화 보상 함수(Reward Function) 설계:** 수동 제어 방식과 시뮬레이션 결과를 비교하여, 수질 기준을 충족하면서도 펌프 가동 시간을 최소화할 수 있는 최적의 보상 함수 구현

## AWARDS
* **삼성청년 SW AI 아카데미 자율 프로젝트 우수상** (2026.05)
* **삼성청년 SW AI 아카데미 공통 프로젝트 최우수상** (2026.02)
* **연세대학교 환경에너지공학과 대학원 추계 학술제 발표 우수상** (2024.11)
* **제 11회 기초과학연구소 학술제 포스터 발표 최우수상** (2023.12)
* **연세대학교 환경에너지공학과 추계 학술제 우수포스터발표상** (2023.11)
* **연세대학교 환경공학부 성적우수상** (2022.02)

## EDUCATION
* **삼성청년SW아카데미(SSAFY)** | **AI 트랙** (2025.07 - 현재)
  * 알고리즘 및 웹/AI 실무 프로젝트 기반의 집중 소프트웨어 교육 과정 이수
* **연세대학교 대학원** | **환경공학 석사 졸업** (2023.03 - 2025.02)
  * SBR 공정 최적화 및 AI 데이터 분석 연구 수행 (석사 논문 작성)
* **연세대학교 미래캠퍼스** | **환경공학 학사 수석 졸업** (2018.03 - 2023.02)

## SOFT SKILLS & DESIGN APPROACH

* **설계가 먼저, 코드는 그 다음입니다.**
  * 프로젝트 착수 시 가장 먼저 **IA(Information Architecture)** 를 작성하여 서비스 전체의 페이지 계층과 사용자 흐름을 시각화합니다. Tickle 프로젝트에서는 예매자·기획사·관리자 3개 역할의 페이지 트리를 수립하여, 팀원 전원이 동일한 구조적 맥락 위에서 기능을 분담할 수 있도록 했습니다.
  * 이후 페이지별 **와이어프레임**에서 컴포넌트 바운더리를 사전 정의하고, 재사용 가능한 Micro Component 단위로 분리합니다. 이를 통해 FE 팀원 간 작업 영역의 충돌을 최소화하고 병렬 개발 속도를 확보합니다.

* **"코드 리뷰 이전에 구조 리뷰"를 실천합니다.**
  * IA → 와이어프레임 → 컴포넌트 설계서 순서로 팀과 공유하고 합의한 뒤 개발에 착수합니다. 설계 단계에서 구조적 결함을 잡으면 구현 단계의 대규모 리팩토링을 사전에 방지할 수 있기 때문입니다.
  * 실제로 3개 프로젝트(Tickle, Withy, Petfolio) 모두에서 이 프로세스를 적용하여, 기능 추가 시 기존 코드 변경 범위를 최소화하는 안정적인 확장 구조를 유지했습니다.
