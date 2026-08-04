# Codivew

**로컬 Ollama 기반 AI 코드 리뷰 도구**

- [npm](https://www.npmjs.com/package/codivew)
- [CLI GitHub](https://github.com/codivew/codivew)
- [VS Code 확장 GitHub](https://github.com/codivew/vscode)

Git 저장소의 변경사항을 로컬 또는 네트워크의 Ollama 코딩 모델로 분석하는 코드 리뷰 도구입니다. 별도의 서버나 데이터베이스 없이 사용할 수 있는 CLI와, 리뷰 과정을 편집기 안에서 진행할 수 있는 VS Code 확장을 함께 개발했습니다.

## CLI

- working tree, staged, branch 기준의 Git 변경사항 수집 기능 구현
- 파일과 변경 라인별 요약 및 피드백을 제공하는 AI 코드 리뷰 흐름 설계
- Ollama 응답을 구조화하고 Zod로 검증하여 예측 가능한 리뷰 데이터 생성
- 민감 정보와 lockfile, 빌드 결과물, 생성 파일 등을 리뷰 대상에서 자동 제외
- Preact 서버 렌더링과 Tailwind CSS를 활용해 외부 리소스가 필요 없는 HTML 리포트 생성
- HTML과 JSON을 각각 또는 동시에 생성할 수 있는 출력 형식 제공
- CLI 메시지, 리뷰 피드백, HTML 리포트에 한국어와 영어 적용
- npm 전역 설치 후 모든 Git 저장소에서 사용할 수 있는 CLI 패키지로 배포

## VS Code 확장

- Activity Bar의 전용 Webview에서 작업 트리, staged, branch 변경사항 리뷰 기능 제공
- Ollama 연결 정보와 설치된 모델, 기준 브랜치, 리뷰 가능한 최대 Diff 크기 설정
- 리뷰 전 변경 파일과 라인 수를 미리 확인하고 포함할 파일을 선택하는 기능 구현
- 파일과 심각도별로 구조화된 피드백을 제공하고 해당 소스 라인으로 바로 이동
- 리뷰 결과를 VS Code Problems 패널과 연동하고 전체 HTML 리포트 제공
- CLI의 공개 `codivew/core` API를 사용해 Git 수집, AI 분석, 리포트 생성 로직 공유
- VS Code 표시 언어를 따르거나 한국어와 영어를 직접 선택할 수 있는 다국어 UI 구성

## 기술

- **CLI / Core**: Node.js, TypeScript, Git, Ollama, Preact, Tailwind CSS, Zod, Jest
- **VS Code 확장**: VS Code Extension API, React, Redux Toolkit, React Router, esbuild

## 성과

- 코드와 리뷰 데이터를 외부 서버에 저장하지 않는 로컬 우선 코드 리뷰 환경 구축
- 리뷰 엔진을 공개 Core API로 분리하여 CLI와 VS Code 확장에서 동일한 분석 흐름 재사용
- 명령어 중심의 CLI와 시각적 작업 흐름을 제공하는 편집기 확장으로 사용 환경 확대
- 변경 파일 선택, Diff 크기 제한, 소스 라인 이동, Problems 패널 연동으로 리뷰 탐색성 개선
- HTML과 JSON 리포트, 한국어와 영어 지원을 통해 사용자 및 자동화 환경에 대응
