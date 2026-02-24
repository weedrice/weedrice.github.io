# weedrice.github.io

Backend Developer 포트폴리오 사이트입니다.

- **URL**: https://weedrice.github.io

## 구성

- **Hero**: 소개, 기술 한 줄, 통계(경력·저장소)
- **Projects**: 사이드 프로젝트(Project Whiteboard, MSA Webtoon, Novel AI, Relations, Gradu) + 교육/스터디 프로젝트(CareMoa, SNS Service, 서울살이)
- **Experience**: 경력 타임라인(SK Inc. AX, Naver BoostCamp, Handong Global University)
- **Skills**: 기술 스택 카드(Backend, Database, DevOps/Cloud, Architecture, Frontend, AI/ML)

다크/라이트 테마 전환, 스크롤 시 섹션 페이드인, 네비 하이라이트가 포함되어 있습니다.

## 수정

- 콘텐츠·링크: `index.html`에서 해당 섹션의 텍스트와 `href`만 수정하면 됩니다.
- 스타일: 같은 파일 상단 `<style>` 블록에서 CSS 변수(`:root`, `[data-theme="light"]`) 및 클래스별 스타일을 변경할 수 있습니다.

## 로컬에서 확인

```bash
python -m http.server 8000
# 브라우저에서 http://localhost:8000 접속
```

## 배포

`main` 브랜치에 push하면 GitHub Pages가 자동으로 배포합니다.  
**Settings → Pages**에서 소스가 **main** 브랜치(또는 `/ (root)`)로 설정되어 있는지 확인하세요.

---

© 2025 weedrice · Vanilla HTML/CSS/JS · GitHub Pages
