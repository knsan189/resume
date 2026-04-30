# 진하늘 이력서 - 잡코리아 축약본

## 자기소개

지도 기반 서비스와 관리 시스템을 중심으로 프론트엔드 개발 경험을 쌓아온 개발자입니다. React, Next.js 기반 UI 개발뿐 아니라 Google Maps, Naver Maps, Mapbox GL, MapLibre GL 등 다양한 지도 provider를 다루며 지도 시각화와 사용자 인터랙션을 구현해왔습니다.

Puppeteer 기반 브라우저 자동화, WebGL 실행 환경 구성, Redis Stream 기반 비동기 처리, Ollama 기반 AI 기능 적용 등 서비스 운영에 필요한 문제를 직접 해결해왔습니다. 기획이 구체화되지 않은 단계에서도 요구사항을 정리하고, 화면 구조와 기능 흐름을 먼저 구현해 제품 방향을 빠르게 검증하는 방식으로 일해왔습니다.

## 경력

### 시터스(CITUS)

**2019.06 ~ 현재 (6년 11개월)**  
지도 기반 서비스 및 관리 시스템 개발

**주요 업무**

- React, Next.js, Vite 기반 사용자 웹 및 관리자 페이지 개발
- GPX, GeoJSON 기반 지도 데이터 처리 및 시각화 기능 구현
- Google Maps, Naver Maps, Mapbox GL, MapLibre GL 기반 지도 UI 및 인터랙션 구현
- Puppeteer, FFmpeg, BullMQ, Redis 기반 지도 콘텐츠 생성 자동화 시스템 구현
- Docker, Linux, AWS EC2/S3, 온프레미스 서버를 활용한 운영 환경 구성
- Jenkins 기반 배포 흐름을 GitLab CI로 일원화하여 배포 자동화 구조 개선

## 주요 프로젝트

### 더트레일(The Trail)

**2025.09 ~ 현재 (8개월)**  
[https://thetrail.co.kr/](https://thetrail.co.kr/)

GPX 데이터를 기반으로 사용자 트래킹 경로를 시각화하고, 영상 및 미리보기 이미지 콘텐츠로 생성할 수 있는 지도 기반 아웃도어 트래킹 서비스입니다.

**주요 구현**

- Next.js 기반 사용자 웹 서비스 개발
- Google Maps, Naver Maps, Mapbox GL의 API 차이를 흡수해 지도 provider 전환이 가능한 구조 구현
- GPX 업로드, 파싱, 경로 시각화까지 이어지는 트래킹 핵심 흐름 구현
- React + Vite 기반 관리자 페이지 개발 및 콘텐츠 관리 기능 구현
- Ollama 기반 사용자 콘텐츠 검수 및 AI 글쓰기 보조 기능 구현
- NestJS Orchestrator API, BullMQ, Puppeteer, FFmpeg 기반 지도 영상 생성 자동화 시스템 구현
- Redis Stream Consumer 기반 미리보기 이미지 생성 및 고부하 처리 서버 운영
- GPX parser, GeoJSON simplifier 작업을 온프레미스 서버로 분리하여 클라우드 비용 부담 완화

**기술**

- Next.js, React, TypeScript, Vite, Redux Toolkit
- Google Maps, Naver Maps, Mapbox GL, WebGL
- NestJS, Node.js, BullMQ, Redis Streams
- Puppeteer, FFmpeg, Docker, Linux, AWS EC2, AWS S3
- Ollama

### 루센 네비게이션 웹

**2024.04 ~ 2024.10 (7개월)**

Android 및 iOS 앱의 WebView에 탑재된 웹 기반 차량용 내비게이션 서비스입니다.

**주요 구현**

- MapLibre.js 기반 차량용 지도 화면 및 주행 안내 UI 구현
- Android 및 iOS WebView 환경에 맞춘 화면 구성 및 동작 처리
- GPS 기반 현재 위치 추적 및 지도 중심 이동 처리
- 주행 경로, 안내 정보, 현재 위치를 함께 표시하는 내비게이션 화면 구성

**기술**

- React, TypeScript, MapLibre.js, Android WebView, iOS WebView

### 소방대원 실내 위치 추정 및 관제 시스템

**2025.04.01 ~ 현재 (1년 1개월)**

화재 현장과 같은 실내 환경에서 건물 도면을 2D 지도와 3D 공간으로 시각화하고, 소방대원의 위치를 매핑하여 실시간으로 모니터링할 수 있는 관제 시스템입니다.

**주요 구현**

- Electron 기반 데스크톱 모니터링 애플리케이션 설계 및 개발
- React 기반 UI 구성 및 상태 관리 설계
- 건물 도면 데이터를 2D 지도 및 3D 공간으로 시각화하고 사용자 위치 매핑 기능 구현
- Three.js 기반 3D 공간 시각화 및 MapLibre GL 기반 지도 시각화 구현

**기술**

- Electron, React, TypeScript, Three.js, MapLibre GL

### 정밀주소 플랫폼 기반 재난 응급상황 신고·출동 서비스

**2023.04.01 ~ 2025.12.31 (2년 9개월)**

정밀주소 기반으로 재난 상황 발생 시 신고 접수 및 출동을 지원하고, 영상 통화를 통해 현장 상황을 실시간으로 전달할 수 있는 서비스입니다.

**주요 구현**

- WebRTC 기반 영상 통화 서버(Jitsi) 구축 및 운영 환경 구성
- Android WebView에서 사용할 영상 통화 UI 페이지 개발
- 관리자 페이지에서 신고, 출동, 영상 통화 관리 기능을 설계부터 구현까지 단독 수행
- 영상 통화 세션 연결 및 상태 처리 로직 구현

**기술**

- React, JavaScript, Jitsi, WebRTC, Android WebView, Node.js

## 오픈소스

### @rousen/react-naver-maps

**React용 Naver Maps Wrapper 라이브러리**  
[npm](https://www.npmjs.com/package/@rousen/react-naver-maps) / [문서](https://knsan189.github.io/react-naver-maps/) / [GitHub](https://github.com/knsan189/react-naver-maps)

기존 Naver Maps JavaScript API가 React 컴포넌트 방식의 공식 wrapper를 제공하지 않아, React 환경에서 선언형으로 지도를 사용할 수 있도록 만든 라이브러리입니다.

**주요 구현**

- Naver Maps JavaScript API를 React 컴포넌트 구조로 래핑
- 지도, 마커, 오버레이 기능을 선언형 컴포넌트 API로 설계
- TypeScript 기반 타입 정의 및 사용성 개선
- Rollup.js 기반 번들링 환경 구성 및 npm 패키지 배포
- GitHub Pages 기반 문서 사이트 구축

**기술**

- React, TypeScript, Naver Maps API, Rollup.js

## 기술 스택

- **Frontend**: React, Next.js, Vite, Redux Toolkit, TypeScript
- **UI**: Material UI, Emotion.js
- **Map / Visualization**: Google Maps, Naver Maps, Mapbox GL, MapLibre GL, Three.js, WebGL
- **Backend / Automation**: NestJS, Node.js, Express, Puppeteer, FFmpeg, BullMQ, Redis Streams
- **AI**: Ollama
- **Infra / DevOps**: Docker, Nginx, Apache2, Linux, AWS EC2, AWS S3, GitLab CI

## 학력

**공주대학교 컴퓨터공학과 중퇴**  
2011.03 ~ 2015.02 (4년)
