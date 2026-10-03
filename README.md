# 한 끗 타이머 Android 설치

이 폴더는 설치 가능한 PWA(Progressive Web App)입니다.

1. `main.heaity.com/timer/`를 **HTTPS**로 배포합니다.
2. Android Chrome에서 타이머 페이지를 엽니다.
3. 상단 `안드로이드에 설치` 버튼 또는 Chrome 메뉴의 `앱 설치` / `홈 화면에 추가`를 누릅니다.

브라우저와 기기 환경에 따라 앱 런처와 홈 화면에 설치되는 WebAPK 또는 홈 화면 바로가기로 제공됩니다. 웹페이지가 사용자 동의 없이 바로가기를 자동 생성할 수는 없습니다.

## 파일

- `index.html`: 타이머 앱과 설치 버튼
- `manifest.webmanifest`: Android 앱 이름, 아이콘, 실행 설정, 빠른 실행 메뉴
- `service-worker.js`: 앱 셸 오프라인 캐시
- `icon.svg`: 홈 화면 아이콘 원본
