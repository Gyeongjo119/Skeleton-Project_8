# 💰 Skeleton Project 8 - Vue 가계부 웹앱
Vue 3 + Vite 기반의 간단하고 직관적인 가계부 웹 애플리케이션입니다. 수입과 지출을 손쉽게 기록하고, 월별/카테고리별 통계를 통해 현명한 소비 습관을 만들어보세요.

## 🔧 주요 기능
✏️ 수입/지출 내역 등록: 날짜, 카테고리, 금액, 메모를 입력해 가계부 작성

📅 월별 내역 보기: 특정 월의 수입/지출 내역을 한눈에 확인

📊 카테고리별 통계: 식비, 교통비, 문화비 등 카테고리별 소비 비율 시각화

🧾 총합 계산 기능: 총 수입, 총 지출, 잔액을 자동 계산

🔍 필터 및 정렬: 날짜순, 금액순 정렬 및 카테고리 필터링

## 🛠️ 사용 기술 스택
프레임워크: Vue 3 (Composition API)

빌드 도구: Vite

상태 관리: Vue의 reactive system 사용

스타일링: CSS / SCSS

백엔드 시뮬레이션: JSON Server (db.json 활용)

## 📂 프로젝트 구조
```plaintext
Skeleton-Project_8/
├── public/
├── src/
│   ├── assets/
│   ├── components/       # 재사용 가능한 UI 컴포넌트
│   ├── views/            # 페이지 단위 컴포넌트
│   ├── App.vue
│   └── main.js
├── db.json               # 가계부 데이터 (Mock API)
├── index.html
└── vite.config.js
```


## 🖥️ 실행 방법
저장소 클론

```bash
git clone https://github.com/Gyeongjo119/Skeleton-Project_8.git
cd Skeleton-Project_8
```

패키지 설치
```bash
npm install
```

개발 서버 실행
```bash
npm run dev
```

JSON Server 실행 (API용)
```bash
npx json-server --watch db.json --port 3000
```

## 👥 팀원
| 이름     | 역할                             |
|----------|----------------------------------|
| 정경조   | 최근 내역, 전체 내역 및 상세 보기 / 라우팅 |
| 김원영   | 상세 페이지 / 거래 내역 관련 CRUD 및 관련 Pages |
| 김은수   | 월별 분석 페이지 / 날짜 및 카테고리 필터링|
| 윤준식   | 전반적인 스타일 담당 / 헤더 및 푸터 / 프로필 페이지|
