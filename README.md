# Portfolio

Cloud Engineer & Backend Developer 포트폴리오 웹사이트입니다.

## 스택

- HTML + CSS + JavaScript
- [Font Awesome](https://fontawesome.com/) (아이콘)
- [Google Fonts - Inter](https://fonts.google.com/specimen/Inter) (폰트)

## 배포

### Vercel

```bash
npx vercel --prod
```

또는 GitHub 레포지토리를 Vercel에 연결하면 자동 배포됩니다.

### 로컬 개발

```bash
# 아무 웹 서버로 실행
npx serve .
# 또는
python -m http.server 8000
```

## 구조

```
portfolio/
├── index.html          # 메인 페이지
├── css/style.css       # 스타일
├── js/main.js          # 인터랙션
├── assets/             # 이미지 등
├── vercel.json         # Vercel 설정
├── .nojekyll           # GitHub Pages 설정
└── README.md
```

## 수정할 내용

- `index.html` 내 이메일, Instagram 링크, 프로젝트 링크 채우기
- `assets/`에 프로젝트 이미지 추가 후 `project-img` 영역 교체
