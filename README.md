# 안녕하세요, 최수환입니다 👋
AI/Backend & Computer Vision 엔지니어.  
현재 **AI-SkinView**(모바일 피부 분석)와 **CSSLibraryMaster**(CSS/Tailwind RAG 플랫폼)를 개발하고 있습니다.

---

## 🧭 About
- 현실 문제를 **데이터 → 모델 → 서비스**로 연결하는 풀스택형 AI/백엔드 개발자
- **문서화 · 자동화 · 재현성**을 중시하고, 지표로 성과를 설명합니다
- 최근 관심사: YOLOv11 성능 개선, React Native(Expo) 최적화, RAG 하이브리드 검색 강화

---

## 🛠 Skills
**Languages & Core**  
Python · Java · JavaScript · TypeScript(선택) · C/C++ · C# · SQL

**AI/ML & CV**  
PyTorch · TensorFlow · OpenCV · Machine Learning · 알고리즘

**Backend & API**  
FastAPI · Node.js · REST API · OAuth/JWT · Async I/O

**DB & Data**  
PostgreSQL · MySQL · OracleDB · MongoDB · Pandas · NumPy

**Frontend & App**  
React · React Native(Expo) · Vue.js

**Cloud & DevOps**  
Microsoft Azure · Docker/Compose · GitHub Actions · n8n(자동화)

> 한눈 스킬 태그:  
> Pandas · TensorFlow · Java · JavaScript · NumPy · React · React Native · OracleDB · MongoDB · PostgreSQL · C# · FastAPI · MySQL · Python · MachineLearning · Microsoft Azure · C++ · Node.js · Vue.js · OpenCV · 알고리즘 · IoT · PyTorch · REST API

---

## 🧑‍💻 How I Work
- 작은 단위로 **작동하는 프로토타입 → 지표 측정 → 반복 개선**
- PR/Issue 템플릿 · 주석 · 문서화로 **온보딩/핸드오버 최적화**
- RDB 스키마 · 지표 · 로그로 **서비스 안정성**을 최우선

---

# 📦 Projects — 상세

## 1) AI-SkinView
YOLOv11로 여드름/홍조를 감지하고, FastAPI 백엔드와 RN 앱을 통해 **실시간 분석 → 기록 → 비교 → 추천**까지 연결한 모바일 스킨케어 어드바이저.

**Links**  
- App: https://github.com/suhwan855/ai-skinview-app  
- API: https://github.com/suhwan855/ai-skinview-api  
- **Notion**: https://www.notion.so/AI-SkinView-29ec5608e7a780b0add0fb5773a99cd6


**Highlights**
- 전처리(CLAHE, White Balance)로 조명/톤 편차 완화, YOLOv11 최적화, 경량 CNN 실험
- RN(Expo-Camera) 실시간 분석 & **LineChart**로 날짜별 개수/면적 비교
- FastAPI + Postgres/pgvector + Azure Blob 저장 구조, LLM 챗봇/설문 연동 설계
- **성과**: 실시간 분석 속도 ~40%↑, 소병변 인식률 개선, 통합 프로토타입 완성

## 2) CSSLibraryMaster

분산된 CSS/Tailwind 스니펫을 수집·정제하여 검색 · 미리보기 · 설명까지 제공하는 플랫폼.

**Links**
- Web: https://github.com/suhwan855/csslibrarymaster
- Backend: https://github.com/suhwan855/csslibrarymaster-backend
- Notion: https://notion.so/csslibrarymaster

**Highlights**
-- 크롤링/정제: Selenium/BeautifulSoup, 라이선스/출처/등록일 파싱, 엔티티 복원, 중복 통합
-- RAG: 코드+메타 임베딩, pgvector 하이브리드 검색(키워드+벡터), 후보 랭킹/캐싱
-- 미리보기: React Iframe srcdoc 샌드박스, Tailwind 자동 감지/주입, auto-height, 코드/미리보기 토글·전체 확장
-- 모델 전환: Ollama 로컬 LLM → GPT-4o 전환(설명/리팩터링 신뢰도↑, 비용은 캐싱으로 관리)

## 🧑‍💼 Experience / Activities / Education
### 넥스트 디앤에이 — 미국 AGV 시운전 (2024.07 ~ 2024.10)
- **S**: 교대 팀 환경에서 센서 오작동·도킹 불량
- **T**: 자율주행/도킹 안정화 & 협업 체계 구축
- **A**: Lidar 감도 조정, QR 위치 최적화, 문서화·실시간 피드백 운영
- **R**: 도킹 오차율 **20%↓**, 비정상 정지 **30%↓**

### 넥스트 디앤에이 — 동원 공장 AGV (2024.10 ~ 2025.02)
- **S**: 마그네틱 라인 주행 오류·도킹 정밀도 저하
- **T**: 주행 안정성 확보, 정밀도 향상, 안전관리 강화
- **A**: 센서 감도/라인 보수, 도킹 위치 재조정, 장애 대응 문서화, 인수인계 체계 구축
- **R**: 도킹 정밀도 **25%↑**, 비정상 정지 **35%↓**

### Microsoft AI School — AI-SkinView (2025.07 ~ 2025.08)
- **S**: 조명/피부톤 편차·소병변 인식률 부족, AI–앱–챗봇 통합 필요
- **T**: 경량 CNN, FastAPI–React Native 연동, 시각화/연동 설계
- **A**: CLAHE/White Balance, YOLOv11 최적화, RN 시각화, FastAPI 연동
- **R**: 실시간 분석 **~40%↑**, 인식률 개선, 통합 프로토타입 완성

### Microsoft AI School (2025.02.27 ~ 2025.09.01)
- Python 알고리즘/OOP 실습, OracleDB·MongoDB CRUD
- 웹 크롤링·HTTP 통신, XML/JSON 전처리·파이프라인 설계
- Flask REST API + React, **Azure 배포/운영**
- 지도/비지도/강화 · CNN/RNN/GAN 원리 및 기초 통계 분석
- 요구사항 → 데이터 → 학습 → 시각화까지 팀 프로젝트 전 과정 경험

### 대림대학교 — 센서 기반 마우스 대체 장치 (2024.03 ~ 2024.06)
- **S**: 자이로/휨 센서 노이즈·지연, 통신 불안정
- **T**: 커서 정확도 개선, 통신 안정화
- **A**: 이동평균·오프셋 보정, Python 모듈화/예외 처리, 문서화
- **R**: 정확도·반응속도 개선, 안정적 HW–SW 통합 구현

### 코멘토 — 백엔드 체험(스프링 게시판) (2023.10 ~ 2023.11)
- MVC 계층 분리, CRUD·댓글·목록/상세 구현, MySQL 연동  
- **R**: Spring MVC 기반 웹앱 완성, 서버–클라이언트 통신 이해

---

## 🧑‍🤝‍🧑 Soft Skills
- 팀 갈등 조율·협업(해외/현장): **의사소통·핸드오버**로 일정/품질 유지  
- 추진력·꼼꼼함: 역할 분담·코드 리뷰·문서화로 **완성도와 재현성** 확보  
- 문제정의 → 실행 → 검증: **수치 기반 개선**과 책임 있는 오너십

---

## 🔗 Contact
- GitHub: https://github.com/suhwan855  
- Email: you@example.com

