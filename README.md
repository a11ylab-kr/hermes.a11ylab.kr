# Hermes-Agent OAuth 안내 사이트

`hermes.a11ylab.kr`에 배포하는 독립 정적 사이트입니다.

- 홈: Google Workspace 연동 목적과 접근 서비스 안내
- `/privacy/`: Google 사용자 데이터 개인정보처리방침
- JavaScript, 분석 도구, 쿠키, 입력 폼 없음
- Cloudflare Pages의 정적 자산 배포를 전제로 함

## 로컬 확인

```sh
python3 -m http.server 8080
```

## 배포 설정

- Framework preset: None
- Build command: 비워 둠
- Build output directory: `/`
- Production branch: `main`
- Custom domain: `hermes.a11ylab.kr`
