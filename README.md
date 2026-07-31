# 진하늘 | Frontend Developer

## Summary

지도 기반 서비스와 관리 시스템을 중심으로 프론트엔드 개발 경험을 쌓아온 개발자입니다.

React, Next.js 기반 UI 개발뿐 아니라 Google Maps, Naver Maps, Mapbox GL, MapLibre GL 등 다양한 지도 provider를 다루며 지도 시각화와 사용자 인터랙션을 구현해왔습니다.

Puppeteer 기반 브라우저 자동화, WebGL 실행 환경 구성, Ollama 기반 AI 기능 적용 등 서비스 운영에 필요한 문제를 직접 해결해왔습니다. 기획이 구체화되지 않은 단계에서도 요구사항을 정리하고, 화면 구조와 기능 흐름을 먼저 구현해 제품 방향을 빠르게 검증하는 방식으로 일해왔습니다.

---

## Tech Stack

- **Frontend**: React, Next.js, Vite, Redux Toolkit, TypeScript
- **UI**: Material UI, Emotion.js
- **Visualization**: Google Maps, Naver Maps, Mapbox GL, MapLibre GL, Three.js, WebGL
- **AI**: Ollama
- **Automation**: Puppeteer
- **Backend**: NestJS, Node.js, Express, Spring Boot
- **Infra / DevOps**: Docker, Nginx, Apache2, Linux, AWS EC2, AWS S3
- **Etc**: WebSocket, Redis

---

## Experience

### 시터스(CITUS)

**기간**: 2021.06 ~ 현재 (5년)  
**역할**: 지도 기반 서비스 및 관리 시스템 개발
**주요 업무**

- 지도 기반 사용자 웹 및 관리자 시스템 개발
- GPX, GeoJSON 기반 지도 데이터 처리 및 시각화 기능 개발
- 지도 provider 연동 및 지도 인터랙션 구현
- 지도 콘텐츠 생성 자동화 기능 개발
- 서비스 운영을 위한 배포 및 서버 환경 구성 참여

**주요 성과**

- Google Maps, Naver Maps, Mapbox GL 등 여러 지도 provider의 API 차이를 흡수하는 구조 구현
- Puppeteer, FFmpeg, BullMQ, Redis 기반 지도 영상 및 미리보기 이미지 생성 자동화 흐름 구축
- Docker, Linux, AWS EC2/S3, 온프레미스 서버를 활용한 고부하 처리 운영 구조 구성
- Jenkins 기반 배포 흐름을 GitLab CI로 일원화하여 배포 자동화 구조 개선

---

## Projects

### 더트레일(The Trail)

**기간**: 2025.09 ~ 현재 (8개월)  
**서비스**: [https://thetrail.co.kr/](https://thetrail.co.kr/)

사용자의 운동 기록을 기반으로 이동 경로를 지도에 시각화하고, 이를 영상 및 미리보기 이미지 콘텐츠로 생성할 수 있는 서비스입니다.

**상세 문서**

- [프로젝트 상세](./projects/the-trail/README.md)
- [지도 기반 영상 생성 자동화 시스템](./projects/the-trail/video-generation.md)
- [지도 기반 미리보기 이미지 생성기](./projects/the-trail/preview-generator.md)
- [Redis Stream Consumer 기반 고부하 처리 서버 운영](./projects/the-trail/stream-consumer-infra.md)
- [예시 영상](https://the-trails.s3.ap-northeast-2.amazonaws.com/videos/2026/4/8647.mp4)

### 루센 네비게이션 웹

**기간**: 2024.04 ~ 2024.10 (7개월)

Android 및 iOS 앱의 WebView에 탑재된 웹 기반 차량용 내비게이션 서비스입니다. MapLibre.js 기반 지도 화면에서 경로와 현재 위치를 표시하고, 주행 안내에 필요한 정보를 제공하는 인터페이스를 구현했습니다.

**상세 문서**

- [프로젝트 상세](./projects/rousen-navigation-web/README.md)

### 소방대원 실내 위치 추정 및 관제 시스템

**기간**: 2025.04 ~ 현재 (1년 1개월)

건물 도면을 2D 지도와 3D 공간으로 시각화하고, 소방대원의 위치를 매핑하여 실시간으로 모니터링할 수 있는 관제 시스템입니다.

**상세 문서**

- [프로젝트 상세](./projects/firefighter-indoor-positioning/README.md)

### 정밀주소 플랫폼 기반 재난 응급상황 신고·출동 서비스

**기간**: 2023.04 ~ 2025.12 (2년 9개월)

정밀주소 기반으로 재난 상황 발생 시 신고 접수 및 출동을 지원하고, 영상 통화를 통해 현장 상황을 실시간으로 전달할 수 있는 서비스입니다.

**상세 문서**

- [프로젝트 상세](./projects/emergency-dispatch/README.md)

---

## Open Source

### Codivew

Git 변경사항을 Ollama 코딩 모델로 분석하고, 파일과 변경 라인별 피드백을 독립 실행형 HTML 리포트로 생성하는 로컬 AI 코드 리뷰 CLI입니다.

**링크**

- [npm](https://www.npmjs.com/package/codivew)
- [GitHub](https://github.com/knsan189/codivew)
- [프로젝트 상세](./projects/codivew/README.md)

### @rousen/react-naver-maps

React용 Naver Maps Wrapper 라이브러리입니다.

**링크**

- [npm](https://www.npmjs.com/package/@rousen/react-naver-maps)
- [문서](https://knsan189.github.io/react-naver-maps/)
- [GitHub](https://github.com/knsan189/react-naver-maps)
- [프로젝트 상세](./projects/react-naver-maps/README.md)

---

## Education

**공주대학교 컴퓨터공학과 중퇴**  
**기간**: 2011.03 ~ 2015.02 (4년)
