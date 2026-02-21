# README_PRIVATE

공개 저장소에 올리지 않을 개인 운영 메모입니다.

## Current Status (2026-02-21)
- Vercel production: `https://nhsportfolio.vercel.app`
- 프로젝트명: `nhsportfolio`
- 도메인 `nhsportfolio.com`: 미구매 상태
- 현재 운영 방식: `vercel.app` 도메인만 사용

## Contact
- 공개 이메일: `namhyunseung.work@gmail.com`

## Notes
- 이미지 영역은 현재 빈 화면(화이트 슬롯) 상태
- 실제 스크린샷 적용 시 `index.html`의 데이터 URI를 실제 파일 경로로 교체

## Domain Plan (Later)
- 도메인 구매 후 연결 예정: `nhsportfolio.com`
- DNS 기본값:
  - `A @ -> 76.76.21.21`
  - `A www -> 76.76.21.21`
- `www -> apex` 리다이렉트는 `vercel.json`에 반영됨

## Safety
- `.vercel`, `.env*`, 로그 파일은 `.gitignore`로 제외됨
- 공개 업로드 전 민감정보/고객정보 재확인 필요
