# 🚀 Global HS Code & Customs Duty Profit Engine

글로벌 트래픽을 수익(CPA)으로 전환하기 위한 0ms 레이턴시 정적 사이트 엔진입니다. 
Cloudflare 글로벌 엣지 네트워크를 통해 전 세계에 무지연으로 배포되었습니다.

## 🛠 Tech Stack (부품 명세)
- **Engine:** Hugo (Fastest Static Site Generator)
- **Data Generator:** Go (Parallel Processing / 100 Workers)
- **Frontend:** Vanilla JS (Zero-latency Calculation Logic)
- **Deployment:** Cloudflare Pages (Global Edge Caching)
- **Optimization:** MD5 Fractal Directory Structure & 19K Page Throttling

---

## ✅ 완료된 작업 (Accomplished Tasks)

### 1. 코어 엔진 조립 (Core Engine)
- [x] **Go 타설 스크립트(`generator.go`) 완성:** 병렬 처리를 통해 수초 만에 수만 개의 마크다운 생성 가능.
- [x] **0ms 연산 UI(`calculator.html`) 조립:** 외부 API 호출 없이 브라우저 CPU만 사용하는 즉각적 연산 로직 구현.
- [x] **SEO 구조 설계:** JSON-LD 스키마 및 메타 태그 자동 주입 파이프라인 구축.

### 2. 글로벌 표준화 (Global Localization)
- [x] **100% 영문화 완료:** `en-us` 언어 코드 및 USD(달러) 화폐 단위 적용.
- [x] **글로벌 UI 조준:** 해외 유저 타겟팅을 위한 인터페이스 및 라벨 영문 교체.

### 3. 인프라 배포 (Infrastructure & Deployment)
- [x] **GitHub 원격 저장소 도킹:** `hscode-engine` 레포지토리 안착.
- [x] **Cloudflare Pages CI/CD 결속:** 빌드 타임 타설(Go run + Hugo build) 프로세스 확립.
- [x] **물리적 한계 우회:** Cloudflare의 2만 개 파일 제한을 19,000개 생산으로 정밀 조정하여 배포 성공.

---

## 🚀 내일의 작업 (Upcoming Roadmap)

### Phase 1: 트래픽 수문 개방 (Traffic Ignition)
- [ ] **Google Search Console 등록:** `hscode-engine.pages.dev` 소유권 인증.
- [ ] **Sitemap 제출:** `sitemap.xml` 주소를 구글 뇌(인덱서)에 직접 주입하여 19,000개 페이지 노출 시작.
- [ ] **키워드 인덱싱 모니터링:** 특정 아이템 번호로 검색 시 구글 결과에 노출되는지 관측.

### Phase 2: 수익 최적화 (Monetization & Scaling)
- [ ] **실제 CPA 링크 교체:** `cpa-partner-link.com` 더미 주소를 실제 제휴 마케팅(아마존, 배대지 등) 수익 주소로 교환.
- [ ] **확장성 테스트:** 2만 개 제한을 뚫기 위한 '서브도메인 분할' 또는 'Cloudflare Workers KV' 기반 아키텍처 검토.
- [ ] **A/B 테스트:** CPA 버튼의 문구(Call to Action)에 따른 클릭률 분석.

---

## 📂 Project Structure (물리적 구조)
- `/scripts/generator.go` : 19,000개 마크다운 생성 공장
- `/layouts/partials/calculator.html` : 0ms 연산 및 CPA 레이어
- `/layouts/partials/seo/json-ld.html` : 구글 상위 노출용 데이터 구조
- `config.toml` : 엔진 총괄 설정 파일
- `build.sh` : 클라우드 통합 지휘 스크립트
