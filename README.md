# Dispatch Routing System (Static Preview)

물류센터 배차·노선·센터 운영 통합 관리 시스템의 브라우저 정적 미리보기입니다.

## 접속

- 라이브: https://ootan71-create.github.io/dispatch-routing/ (GitHub Pages 활성화 후)
- 로컬: `dispatch-routing-app.html` 파일을 브라우저로 직접 열어도 동작합니다.

## 특징

- 단일 HTML — 서버 없이 브라우저만으로 실행
- 데이터는 브라우저 `localStorage`에 저장 (사용자별 로컬 저장, 공유 안 됨)
- 3개 모드: 🚚 배차 라우팅 / 🗺️ 노선 최적화 / 🏭 센터 운영

## 정적 배포의 한계

이 저장소에는 **화면 코드만** 포함되어 있으며, 실제 운영 시 사용되는 공용 계정
API(`server.py`)·요율 데이터·계정 정보 등은 포함되지 않습니다. 팀 공용 계정
공유가 필요하면 별도 서버 환경(내부망)이 필요합니다.
