# Codivew

**로컬 Ollama 기반 AI 코드 리뷰 CLI**

- [npm](https://www.npmjs.com/package/codivew)
- [GitHub](https://github.com/knsan189/codivew)

Git 저장소의 변경사항을 로컬 또는 네트워크의 Ollama 코딩 모델로 분석하고, 리뷰 결과를 독립 실행형 HTML 리포트로 생성하는 CLI 도구입니다. 별도의 서버나 데이터베이스 없이 개발 환경 안에서 코드 리뷰를 완료할 수 있도록 만들었습니다.

## 주요 구현

- working tree, staged, branch 기준의 Git 변경사항 수집 기능 구현
- 파일과 변경 라인별 요약 및 피드백을 제공하는 AI 코드 리뷰 흐름 설계
- Ollama 응답을 구조화하고 Zod로 검증하여 예측 가능한 리뷰 데이터 생성
- 민감 정보와 lockfile, 빌드 결과물, 생성 파일 등을 리뷰 대상에서 자동 제외
- Preact 서버 렌더링과 Tailwind CSS를 활용해 외부 리소스가 필요 없는 HTML 리포트 생성
- Ollama 연결 정보와 모델을 선택해 저장하는 대화형 초기 설정 기능 구현
- npm 전역 설치 후 모든 Git 저장소에서 사용할 수 있는 CLI 패키지로 배포

## 기술

- Node.js, TypeScript, Git, Ollama, Preact, Tailwind CSS, Zod, Jest

## 성과

- 코드와 리뷰 데이터를 외부 서버에 저장하지 않는 로컬 우선 코드 리뷰 환경 구축
- working, staged, branch 등 개발 단계에 맞춰 리뷰 범위를 선택할 수 있는 CLI 제공
- 변경 라인과 피드백을 연결한 접이식 HTML 리포트로 리뷰 결과의 탐색성 개선
- 설치부터 초기 설정, 리뷰 실행, 리포트 확인까지 하나의 npm CLI 흐름으로 구성
