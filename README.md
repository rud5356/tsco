# TSCO 회사소개 홈페이지

중앙자동제어시스템 전문기업 **TSCO**의 공식 회사소개 웹사이트입니다.

## 🌐 배포 주소

> GitHub Pages 활성화 후 주소 기입

## 📁 파일 구조

```
tsco/
├── index.html       # 메인 홈페이지 (단일 파일)
├── logo.png         # 로고 이미지 (추가 예정)
└── README.md
```

## 📄 페이지 구성

| 섹션 | 설명 |
|---|---|
| Header | 로고 + 네비게이션 |
| Hero | 메인 슬로건 |
| 회사소개 | 실적 수치 및 회사 사진 |
| 사업영역 | 주요 서비스 6종 |
| 오더메이드 | 맞춤 제작 프로세스 |
| 특장점 | Why TSCO |
| 문의하기 | 연락처 및 문의 폼 |

## ✏️ 수정 방법

### 로고 교체
로고 이미지 파일(`logo.png`)을 루트에 추가한 뒤, `index.html`의 헤더 부분을 아래와 같이 교체합니다.

```html
<!-- 변경 전 -->
<div class="logo-img-wrap">로고<br>준비중</div>

<!-- 변경 후 -->
<img src="logo.png" alt="TSCO" height="44">
```

### 회사 정보 수정
`index.html` 내 아래 항목을 실제 정보로 교체합니다.

- 주소, 전화, 팩스, 이메일 → `#contact` 섹션
- 업력, 납품 실적 → `#about` 섹션 `.stat-box`
- 회사/시설 사진 → `#about` `.about-img-wrap` → `<img>` 태그로 교체

## 🛠 기술 스택

- HTML5 / CSS3 (순수 CSS, 프레임워크 미사용)
- Vanilla JavaScript
- Google Fonts (Noto Sans KR)
- 반응형 웹 지원 (모바일 대응)
