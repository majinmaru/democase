# NovaDocent — Landing Page

QR 코드 스캔 시 진입하는 NovaDocent 데모 선택 랜딩페이지입니다.

## 파일 구조

```
novadocent-landing/
├── index.html          # 메인 랜딩페이지
├── style.css           # 전체 스타일시트
├── README.md           # 이 파일
│
│   # 아래 파일은 별도로 추가 필요
├── docent-beauty.html      # 뷰티 팝업스토어 도슨트 페이지
├── docent-electronics.html # 국제 전자 박람회 도슨트 페이지
├── docent-auto.html        # 자동차 프로모션 도슨트 페이지
├── docent-game.html        # 게임 박람회 도슨트 페이지
└── docent-museum.html      # 박물관 도슨트 페이지
```

## 데모 케이스

| 카드 | 파일 | 설명 |
|------|------|------|
| 💄 뷰티 팝업스토어 | `docent-beauty.html` | 신규 스킨케어 브랜드의 팝업스토어 |
| 🖥️ 국제 전자 박람회 | `docent-electronics.html` | AI와 전자 제품의 만남을 소개하는 글로벌 쇼케이스 |
| 🚗 자동차 프로모션 | `docent-auto.html` | 환경과 함께 발전하는 스마트 전기차 출시 |
| 🎮 게임 박람회 | `docent-game.html` | 단순한 캐릭터가 아닌 내제된 세계관 스토리까지 |
| 🏛️ 박물관 | `docent-museum.html` | 수천 년의 역사와 예술을 담은 컬렉션 |

## 디자인 스펙

- **포인트 컬러**: `#0F48EB`
- **배경**: `#FFFFFF`
- **폰트**: 시스템 고딕 (Apple SD Gothic Neo / 맑은 고딕 / Noto Sans CJK)
- **최적화 기준**: 태블릿 (768px ~ 1024px)
- **외부 의존성 없음** — 인터넷 연결 없이도 동일하게 렌더링됩니다

## 사용 방법

1. 이 리포지토리를 클론합니다
2. 각 도슨트 페이지(`docent-*.html`)를 추가합니다
3. `index.html`을 브라우저에서 열거나 GitHub Pages로 배포합니다

### GitHub Pages 배포

1. 리포지토리 → **Settings** → **Pages**
2. Source: `Deploy from a branch` → `main` / `root`
3. 저장 후 생성된 URL을 QR 코드로 변환

## 로컬 실행

별도 서버 없이 `index.html`을 직접 열어도 동작합니다.
