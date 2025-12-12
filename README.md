# Portfolio 랜딩 페이지

포트폴리오 랜딩 페이지입니다. HTML과 CSS만을 사용하여 구현한 단일 페이지 애플리케이션입니다.

## 기술 스택

- HTML5: 시맨틱 마크업 구조
- CSS3: 인라인 스타일을 활용한 스타일링
- CSS Grid: 반응형 레이아웃 구현
- CSS Animations: 페이드인 애니메이션 효과

## 주요 기능

그리드 기반 카드 레이아웃
- CSS Grid를 사용한 반응형 프로젝트 카드 배치
- repeat(auto-fit, minmax(300px, 1fr))를 활용한 자동 반응형 그리드
- 모바일 환경에서는 단일 컬럼으로 자동 전환

인터랙티브 카드 디자인
- 호버 시 카드 상단에 그라디언트 바 애니메이션 효과
- box-shadow 변화를 통한 깊이감 있는 호버 효과
- transform: scaleX()를 활용한 부드러운 전환 애니메이션

그라디언트 및 애니메이션
- linear-gradient를 활용한 배경 및 텍스트 그라디언트 효과
- background-clip: text를 사용한 텍스트 그라디언트
- fadeInUp 키프레임 애니메이션으로 페이지 로드 시 페이드인 효과

반응형 디자인
- 미디어 쿼리를 통한 모바일 최적화
- 화면 크기에 따른 폰트 크기 및 레이아웃 조정

## 구현 세부사항

단일 HTML 파일에 모든 스타일을 인라인으로 포함하여 외부 의존성 없이 독립적으로 동작하도록 구현했습니다. CSS Grid의 auto-fit과 minmax를 조합하여 화면 크기에 따라 자동으로 컬럼 수가 조정되는 반응형 레이아웃을 구현했습니다.

카드 호버 효과는 ::before 가상 요소를 사용하여 상단에 그라디언트 바를 생성하고, transform: scaleX()를 통해 호버 시 확장되도록 구현했습니다. 이를 통해 JavaScript 없이도 인터랙티브한 사용자 경험을 제공합니다.

그라디언트 텍스트 효과는 -webkit-background-clip과 -webkit-text-fill-color를 조합하여 구현했으며, 애니메이션은 @keyframes를 사용하여 opacity와 transform을 동시에 제어합니다.

## 프로젝트 구조

```
hyunsoo_portfolio_/
├── index.html
└── 넛지_IR.pdf
```
