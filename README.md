# Portfolio Landing Page

실무형 백엔드 개발자 포트폴리오 정적 사이트입니다.

## Access Links
- Main: https://nhsportfolio.vercel.app
- Work: https://nhsportfolio.vercel.app/#work
- Principles: https://nhsportfolio.vercel.app/#principles
- Stack: https://nhsportfolio.vercel.app/#stack
- Contact: https://nhsportfolio.vercel.app/#contact

## Project Files
- `index.html`: 포트폴리오 메인 페이지
- `styles.css`: 레이아웃 및 UI 스타일
- `assets/`: 스크린샷/이미지 자산
- `vercel.json`: Vercel 배포 설정
- `.github/workflows/vercel-deploy.yml`: `main` 푸시 시 자동 배포

## Auto Deploy (GitHub Actions + Vercel)
아래 GitHub Repository Secrets가 설정되어 있으면, `main` 브랜치 푸시마다 자동 배포됩니다.

- `VERCEL_TOKEN`
- `VERCEL_ORG_ID`
- `VERCEL_PROJECT_ID`

현재 프로젝트 기준 값:
- `VERCEL_ORG_ID`: `team_SkpuHQg2igxvNrbpZxGbhx3J`
- `VERCEL_PROJECT_ID`: `prj_OmFbHtXNmErMqdr3VLRMkIm5KVc1`

## Local Preview
정적 서버 실행 후 확인:

```bash
python3 -m http.server 8080
```

브라우저: `http://localhost:8080`
