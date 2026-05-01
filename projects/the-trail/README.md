# 더트레일(The Trail)

**지도 기반 아웃도어 트래킹 및 콘텐츠 생성 서비스**  
2025.09 ~ 현재 (8개월)  
[https://thetrail.co.kr/](https://thetrail.co.kr/)

사용자의 운동 기록을 기반으로 이동 경로를 지도에 시각화하고, 이를 영상 및 미리보기 이미지 콘텐츠로 생성할 수 있는 서비스입니다. 지도 탐색, 활동 기록, 드론 영상 생성, 커뮤니티 피드 기능을 제공하며 GeoJSON 기반 지도 데이터 처리와 사용자 활동 데이터 기록을 지원합니다.

## 사용자 웹

**주요 구현**

- Next.js 기반 사용자 웹 서비스 개발
- Google Maps, Naver Maps, Mapbox GL을 전환해 사용할 수 있는 지도 provider 구조 설계
- 지도 provider별 API 차이를 고려한 지도 UI 및 인터랙션 구현
- GPX 데이터 파싱 및 커스텀 확장 데이터 처리

**기술**

- Next.js, React, TypeScript, Google Maps, Naver Maps, Mapbox GL

**성과**

- 여러 지도 provider의 API 차이를 흡수하여 동일한 사용자 흐름에서 전환 가능한 구조 마련
- GPX 업로드부터 지도 경로 시각화까지 이어지는 핵심 사용자 흐름 구현
- 지도 렌더링 및 인터랙션 응답성 개선

## 관리자 페이지

**주요 구현**

- React + Vite 기반 관리자 페이지 설계 및 개발
- 데이터 관리 및 콘텐츠 제어 기능 구현
- Ollama 기반 사용자 콘텐츠 검수 기능을 구현하여 게시글·댓글의 부적절 표현을 사전 탐지
- 공지사항 및 게시판 작성 화면에 AI 기반 글쓰기 보조 기능을 적용하여 운영자의 콘텐츠 작성 흐름 개선
- 구체화되지 않은 요구사항을 구조화하여 관리자 UI 및 기능 흐름 설계
- 빠른 화면 구현을 통해 기획 의도를 구체화하고 기획과 개발 간 협업 흐름 개선

**기술**

- React, Vite, Redux Toolkit, Ollama

**성과**

- 데이터 관리, 콘텐츠 제어, AI 보조 기능을 관리자 화면에 통합하여 운영 흐름 개선

## 상세 문서

- [지도 기반 영상 생성 자동화 시스템](./video-generation.md)
- [지도 기반 미리보기 이미지 생성기](./preview-generator.md)
- [Redis Stream Consumer 기반 고부하 처리 서버 운영](./stream-consumer-infra.md)
- [예시 영상](https://the-trails.s3.ap-northeast-2.amazonaws.com/videos/2026/4/8647.mp4)
