# 안녕하세요, 최수환입니다 👋
AI/Backend & Computer Vision 엔지니어.  
현재 **AI-SkinView**(모바일 피부 분석)와 **CSSLibraryMaster**(CSS/Tailwind RAG 플랫폼)를 개발하고 있습니다.

---

## 🧭 About
- 현실 문제를 **데이터 → 모델 → 서비스**로 연결하는 풀스택형 AI/백엔드 개발자
- **문서화 · 자동화 · 재현성**을 중시하고, 지표로 성과를 설명합니다
- 최근 관심사: YOLOv11 성능 개선, React Native(Expo) 최적화, RAG 하이브리드 검색 강화

---

## 🛠️ 기술 스택 (Tech Stack)
<div align="center">

### Backend  
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white&style=for-the-badge)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white&style=for-the-badge)
![Node.js](https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=white&style=for-the-badge)
![Java](https://img.shields.io/badge/Java-007396?logo=openjdk&logoColor=white&style=for-the-badge)
![C#](https://img.shields.io/badge/C%23-239120?logo=csharp&logoColor=white&style=for-the-badge)

### Frontend  
![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black&style=for-the-badge)
![React Native](https://img.shields.io/badge/React%20Native-61DAFB?logo=react&logoColor=black&style=for-the-badge)
![Expo](https://img.shields.io/badge/Expo-000020?logo=expo&logoColor=white&style=for-the-badge)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black&style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white&style=for-the-badge)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white&style=for-the-badge)
![jQuery](https://img.shields.io/badge/jQuery-0769AD?logo=jquery&logoColor=white&style=for-the-badge)

### Database  
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white&style=for-the-badge)
![Oracle](https://img.shields.io/badge/Oracle-F80000?logo=oracle&logoColor=white&style=for-the-badge)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white&style=for-the-badge)

### AI  
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white&style=for-the-badge)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white&style=for-the-badge)
![scikit--learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white&style=for-the-badge)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?logo=opencv&logoColor=white&style=for-the-badge)
![YOLO](https://img.shields.io/badge/YOLO-00FFFF?style=for-the-badge) 
![RAG](https://img.shields.io/badge/RAG-9E9E9E?style=for-the-badge)
![VectorDB_(pgvector)](https://img.shields.io/badge/Vector%20DB%20(pgvector)-4169E1?logo=postgresql&logoColor=white&style=for-the-badge)

### Cloud & DevOps  
![Azure](https://img.shields.io/badge/Azure-0078D4?logo=microsoftazure&logoColor=white&style=for-the-badge)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black&style=for-the-badge)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white&style=for-the-badge)
![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white&style=for-the-badge)

### Etc.  
![C](https://img.shields.io/badge/C-A8B9CC?logo=c&logoColor=black&style=for-the-badge)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white&style=for-the-badge)
![Figma](https://img.shields.io/badge/Figma-F24E1E?logo=figma&logoColor=white&style=for-the-badge)

</div>

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
- **Notion**: https://aware-plane-6e6.notion.site/AI-SkinView-29ec5608e7a780b0add0fb5773a99cd6


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
- Notion: https://aware-plane-6e6.notion.site/CSSMasterLibrary-2a7c5608e7a780d08b22cc8e1afb59b9

**Highlights**
-- 크롤링/정제: Selenium/BeautifulSoup, 라이선스/출처/등록일 파싱, 엔티티 복원, 중복 통합
-- RAG: 코드+메타 임베딩, pgvector 하이브리드 검색(키워드+벡터), 후보 랭킹/캐싱
-- 미리보기: React Iframe srcdoc 샌드박스, Tailwind 자동 감지/주입, auto-height, 코드/미리보기 토글·전체 확장
-- 모델 전환: Ollama 로컬 LLM → GPT-4o 전환(설명/리팩터링 신뢰도↑, 비용은 캐싱으로 관리)

##3) Mental Risk Survey (청소년 정신건강 위험 설문 ML 데모)
PHQ-9A / GAD-7 / K10 / ASQ 기반 설문 데이터를 활용해 우울·불안·자살 위험도를 예측하고, 결과를 API/시각화로 제공하는 정신건강 위험 평가 데모 서비스.

**Links**
-- GitHub: https://github.com/suhwan855/machine-learning-project
-- Notion: https://aware-plane-6e6.notion.site/ML-2b2c5608e7a780c3b58bc0d14178581b

**Highlights**
-- 설문 점수 구조를 반영한 합성 데이터 생성(상관관계 기반 샘플링 + sigmoid 라벨링)으로 학습 데이터 구축
-- Logistic Regression / RandomForest / XGBoost 학습 후 앙상블 & 확률 보정(Calibration) 적용
-- FastAPI 기반 /predict 단일 엔드포인트 + 위험도 등급(banding) 반환 구조 구현
-- 지역·연도별 위험률 데이터 저장/갱신 → 위험도 지도 시각화 화면과 연동
-- 성과: ML 학습–평가(AUC/PR-AUC)–API 파이프라인 구축

## 4) Microsoft AI School (2025.02.27 ~ 2025.09.01)
Python/DB/웹/ML/DL을 요구사항 → 데이터 → 모델 → 서비스 흐름으로 학습한 실습 중심 AI·백엔드 교육 과정.

**Links**
-- Study Log: https://github.com/suhwan855/Microsoft-Azure

**Highlights**
-- Python 알고리즘/OOP 실습으로 문제 분해·구현 기본기 강화
-- OracleDB·MongoDB CRUD/정규화/집계 쿼리 실습으로 RDB–NoSQL 설계 경험 확보
-- 웹 크롤링 → XML/JSON 전처리 → 저장까지 데이터 파이프라인 설계 경험
-- Flask/FastAPI REST API + React 연동으로 서비스 구조 구현 및 배포 실습
-- 지도/비지도/강화학습, CNN/RNN/GAN 핵심 원리 학습 및 모델 평가·시각화
-- 팀 프로젝트에서 요구사항 정의 → 모델 설계/학습 → 결과 해석 → 데모 서비스화 전 과정 경험


## 🧑‍🤝‍🧑 Soft Skills
- 팀 갈등 조율·협업(해외/현장): **의사소통·핸드오버**로 일정/품질 유지  
- 추진력·꼼꼼함: 역할 분담·코드 리뷰·문서화로 **완성도와 재현성** 확보  
- 문제정의 → 실행 → 검증: **수치 기반 개선**과 책임 있는 오너십

---

## 🔗 Contact
- GitHub: https://github.com/suhwan855  
- Email:ytn011103@naver.com

