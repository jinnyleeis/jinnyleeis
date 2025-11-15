# 👋 Hi, I'm Jiin Lee  

### [포트폴리오로 이동하기](https://jiinlee-portfolio.vercel.app)


## 🧠 About Me
- Analytical yet adaptable engineer who bridges data precision with creative insight.      
  (데이터의 정확성과 창의적 통찰을 잇는 분석적이면서도 유연한 엔지니어입니다.)
- Fast learner who applies new technologies to solve real-world data challenges.      
  (새로운 기술을 빠르게 익히고 실제 데이터 문제를 해결하는 데 적용하는 것을 즐깁니다.)
- Strong at structuring ambiguity through debugging, rule definition, and scalable pipeline design.      
  (복잡한 문제를 디버깅·규칙 정의·확장 가능한 파이프라인 설계를 통해 구조화합니다.)
- Passionate about leveraging cloud-scale data architecture to enable business insights.         
  (클라우드 기반 데이터 아키텍처로 비즈니스 인사이트를 가능하게 만드는 데 열정이 있습니다.)

### Data Engineering & Analytics
- Experienced with building scalable ETL and reporting pipelines that ensure data integrity and reproducibility.          
  (정합성과 재현성을 보장하는 ETL 및 리포팅 파이프라인 구축 경험 보유)
- Experienced with data modeling (Fact–Dimension, BCNF), DQ validation, and ELT orchestration using SQL & Python.         
  (Fact–Dimension 모델링, BCNF 정규화, DQ 검증, SQL·Python 기반 ELT 오케스트레이션 수행)
- Experienced with cloud-native analytics architecture (BigQuery, GCS) and star-schema optimization for BI scalability.       
  (BigQuery·GCS 중심의 BI 레이어 집계 방식을 표준화 및 개인 프로젝트 BI 확장성 최적화(Star Schema) 경험)

### AI & Solution Architecture
- Designed LLM based pipeline architecture integrating video description, consumer reaction, and report generation.        
  (LLM 기반 파이프라인 아키텍처 설계: 영상 설명–소비자 반응–리포트 생성 통합)
- Built evaluation framework for AI output validation, integrating results into analytics dashboards.      
  (AI 결과 평가 프레임워크 구축 및 대시보드 연동)   
- Led architectural design of AI Travel Assistant, connecting backend, LLM model layer, and RAG pipeline.     
  (AI 여행 어시스턴트 백엔드 설계 및 LLM 파이프라인 통합 주도)

### Software & Platform Engineering
- Developed modular, maintainable data systems with schema governance.     
  (Schema Governance 기반 모듈형 데이터 시스템 개발)
- Experienced with low-level system programming through the C-based Pintos OS Project    
  (Pintos OS (C 기반) 프로젝트를 통해 시스템 레벨 프로그래밍 경험)
- Optimized data reuse through Server Actions and caching in a Next.js web frontend     
  (Next.js 기반 웹 프론트엔드에서 Server Actions·Caching Mechanism을 활용한 데이터 재사용 최적화)
- Designed Data Layer–UI separation architecture and state management structure for the Fandoor Web Project             
  (Fandoor Web Project에서 Data Layer–UI 분리 아키텍처 설계 및 상태관리 구조 구축)
  


---

## 🛠️ Tech Stack
- **Languages**: Python, SQL, C, C++, Javascript, Typescript
- **Cloud & Data**: BigQuery, GCS, MySQL, Pandas  
- **AI / LLM**: Gemini Flash 2.0, OpenAI, LangChain, LangGraph  
- **Frameworks/Library**: Streamlit, FastAPI, Next.js
- **Others**: Git, ER Modeling, Pydantic


---

## 🚀 Experience

### **Kearney Korea – Digital Transformation Division (Research Analyst)**  
2025.07 – 2025.10
 | Designed data engineering pipelines and analytics solutions, integrating LLMs to automate insight reporting.


- Built **IG ETL pipelines** (Excel → Parquet → BigQuery), cutting preprocessing time **4h → 1h** with GCS orchestration (Step0–4).        
  [👉 대량의 Excel 데이터 기반 IG 댓글 온디맨드 배치 파이프라인 구축](https://jiinlee-portfolio.vercel.app/projects/1)
- Implemented **MERGE-based DQ validation** ensuring **100% KPI consistency**.          
  [👉 기간별 자산 리포트 개발과, 집계 로직과 정합성 리팩터링](https://jiinlee-portfolio.vercel.app/projects/4)) 
- Refactored **timestamp-based recrawling logic** → redundant queries ↓40%.  
- Integrated **Gemini Flash 2.0 Video LLM** to generate video descriptions & automate creative/consumer insight reports.

### **Ludens – Fullstack Engineer (Startup)**  
2025.03 – 2025.07 | Developed full-stack features from database modeling to frontend UI


- Designed ER Diagram based on business logic
- Built a **BCNF-normalized MySQL schema (27 tables)** for a creator platform.    
  [👉 팬 커뮤니티 후원·정산 플랫폼 – 스키마 설계(ERD→논리 환원→BCNF→물리 구현)](https://jiinlee-portfolio.vercel.app/projects/7)


### Ulift (Coding Valley) – Content Developer (Part-Time)‬
2024.01 – 2024.05 
- Authored and reviewed HTML/CSS/JS learning materials, ensuring clarity and technical accuracy.        
  (HTML, CSS, JS 학습 자료를 집필하고 검수하여 명확성과 기술적 정확성을 보장했습니다.)
- Designed and validated coding exercises on DOM manipulation.       
  (DOM 조작에 관한 코딩 연습문제를 설계하고 검증했습니다.)
---

## 🎓 Education
**Sogang University (B.A., Expected 2026.02)**  
Philosophy · Art & Technology · Computer Science  
Relevant Courses: Database Systems, OS, Networks, Algorithms, NLP

---

## 🏆 Honors & Awards
- **Namkoong Hoon Future Talent Scholarship (2024)** – by ex-Kakao CEO  
- **Prometheus AI Hackathon (2023)** – 🥇 Grand Prize, *Webtoon Text-to-Drawing SaaS*

---

## 💡 Selected Projects

### [🤖 Bookie AI Travel Assistant](https://github.com/Bookie-Chatbot/backend-api-ai-monorepo)
- LLM-based travel agent (8-intent routing) built with **FastAPI + LangChain**.         
  (FastAPI + LangChain 기반으로 구축한 LLM 기반 여행 어시스턴트(8개 Intent 라우팅)입니다.)
- Designed evaluation loop to score recommendations using cost & POI datasets.
- (비용 및 POI(Point of Interest) 데이터셋을 활용하여 추천 결과를 평가하는 루프를 설계했습니다.)

### [🏪 Convenience Store DB System](https://github.com/jinnyleeis/convenience-store-db-system)
- Designed **Fact–Dimension schema** and BI feature queries for retail analytics.        
  소매 데이터 분석을 위한 Fact–Dimension 스키마를 설계하고, BI 분석용 쿼리를 구현했습니다.

### [🧩 Pintos OS Project](https://github.com/jinnyleeis/PintosOS)
- Implemented process scheduling & syscall pipelines in C for an educational OS kernel.       
  교육용 OS 커널에서 C 언어로 프로세스 스케줄링 및 시스템 콜 파이프라인을 구현했습니다.

---

## 🌱 Beyond Work
### XREAL Metaverse Academy (2nd Dev Team / 3rd Ops(운영진), 2022.03 - 2023.02)
- Conducted Shader research and led the HLSL study group     
  (Shader 연구를 수행하고 HLSL 스터디를 주도했습니다.) [👉 hlsl 쉐이더 기반 타임라인 무비 제작 프로젝트](https://github.com/jinnyleeis/apocalypseteam)
- Developed a prototype that used collective intelligence to generate insights from NFT purchases          
  (NFT 구매 데이터를 기반으로 집단 지성을 활용해 인사이트를 생성하는 프로토타입을 개발했습니다.)

### CEOS Shinchon Startup Circle (19th Frontend / 20th Ops(운영진), 2024.03 - 2025.01) 
- PetPlate (Frontend Engineer) [👉PetPlate 프로젝트](https://github.com/CEOS-PAT-PLATE/FrontEnd)
  - Developed Naver OAuth2.0 login and nutrition/favorites pages using Next.js 14, Recoil, and custom React Query hooks.
    (Next.js 14, Recoil, 커스텀 React Query 훅을 활용해 Naver OAuth2.0 로그인 및 일일 영양소 입력 ·즐겨찾기 페이지를 개발했습니다.)
  - Implemented a dynamic nutrition results page with reusable styled-components and Chart.js visualizations.     
    (재사용 가능한 styled-components와 Chart.js 시각화를 활용해 동적인 영양 분석 결과 페이지를 구현했습니다.) 

### Sogang Univ. Art and Technology Conference 2022 — Event Planning Team‬
- Participated in planning and execution of 2022 ATC’s Family Meeting, Guest Visit (GV), and‬
‭ Homecoming events.       
   (2022 ATC Family Meeting, Guest Visit (GV), Homecoming 행사의 기획 및 실행에 참여했습니다.)

---














