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

## Auto Deploy (Vercel GitHub Integration)
이 저장소는 Vercel에서 GitHub 저장소를 직접 연동해 자동 배포합니다.

- `main` 푸시: Production 배포
- Pull Request: Preview 배포

설정 방법:
1. Vercel Dashboard > Project `nhsportfolio` > Settings > Git
2. Git Provider를 GitHub로 연결
3. Repository를 `Hyunseung-Nam/nhsportfolio`로 선택
4. Production Branch를 `main`으로 설정

이 방식은 GitHub Actions 시크릿(`VERCEL_TOKEN` 등) 없이 동작합니다.

## Local Preview
정적 서버 실행 후 확인:

```bash
python3 -m http.server 8080
```

브라우저: `http://localhost:8080`
