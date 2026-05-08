# 남현승 포트폴리오

불편함을 발견하고, 실제로 쓰이는 것을 만듭니다.

기획부터 배포, 유지보수까지.
실제 매장에서 운영 중인 납품 프로젝트부터
본인이 직접 쓰려고 만든 iOS 앱까지.

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
