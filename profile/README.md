<div align="center">
  <img src="./assets/logo.png" alt="EATAMAMA Logo" width="220" height="220">
  <h1>EATAMAMA</h1>
  <p><b>임산부 맞춤형 음식 검색 및 식단관리 서비스</b><br>
  <i>“먹어도 될까?”를 “안심하고 먹자!”로 바꿉니다.</i></p>
</div>


---

> ## 1. 서비스 소개
EATAMAMA는 임산부의 **주차, 질환, 알레르기** 등 **개인 건강 정보**를 반영해  
**안전한 음식 선택과 식단 추천**을 제공하는 서비스입니다.

### 이 프로젝트가 해결하는 문제
1.	음식 정보에 대한 검색피로와 불안감 해결
2.	개인 맞춤 식단 정보 부재 해결
3.	요리·재료 단위의 확인 불가 문제 해결

---

> ## 2. 개발 인원

| Frontend | Frontend | Backend | Backend |
|---|---|---|---|
| <a href="https://github.com/jijun0129"><img src="https://github.com/jijun0129.png" width="80"><br/>정인준</a> | <a href="https://github.com/HHHv-v"><img src="https://github.com/HHHv-v.png" width="80"><br/>홍한희</a> | <a href="https://github.com/Koeunsaem"><img src="https://github.com/Koeunsaem.png" width="80"><br/>고은샘</a> | <a href="https://github.com/yangjunsik"><img src="https://github.com/yangjunsik.png" width="80"><br/>양준식</a> |


---

> ## 3. 소프트웨어 아키텍쳐

<p align="center">
  <img width="1062" height="772" alt="image" src="./assets/architecture.png" />
</p>

---

> ## 4. 페이지


> ### 4.1 로그인 페이지
<img width="318" height="686" alt="로그인" src="./assets/login.png" />


> ### 4.2 메인 페이지
<img width="400" height="1300" alt="메인 페이지" src="./assets/main.png" />


> ### 4.3 검색 페이지
<img width="400" height="1300" alt="검색 페이지" src="./assets/search.png" />


---

> ## 5. 주요 기능
- **음식 검색 & 분석**  
  - 음식명 / 재료명 입력 시 **위험·안전 여부** 즉시 확인  
  - 알레르기 성분 및 질환 관련 주의 성분 자동 표시  
  - AI 기반:  
    - 음식 검색 시 → **요리 추천** (더 안전하거나 균형 잡힌 요리 제안)  
    - 재료 검색 시 → **성분·영양소 분석** (임산부 맞춤 리스크 해석)

- **개인화 식단 추천**  
  - 사용자의 **임신 주차, 건강 상태(질환), 알레르기 정보** 반영  
  - AI가 하루 권장 섭취량을 고려해 **맞춤형 식단 조언** 제안  
  - 시기별 권장 영양소(엽산, 철분, 단백질 등) 우선 반영

- **AI 식단 관리 & 기록**  
  - 아침 / 점심 / 저녁 단위로 섭취 음식을 기록  
  - AI가 하루 식단을 분석하여 **균형 지표** 제공 (영양 불균형 경고, 권장 보충 성분 안내)  

- **안심 리포트 & 공유 기능 (확장 예정)**  
  - 하루 / 주간 단위 **영양 리포트 PDF** 자동 생성  
  - 가족 계정(남편·보호자) 또는 담당 의사와 **식단 기록 공유** 기능  
  - 산부인과 / 산후조리원과 연동해 **맞춤 가이드** 제공 가능

---

> ## 6. 기술 스택
<!-- ===== Badges: Tech Stack (GitHub-safe) ===== -->

<!-- Core -->
<p>
  <a href="#"><img alt="License" src="https://img.shields.io/badge/License-MIT-111111"></a>
  <a href="#"><img alt="Build" src="https://img.shields.io/badge/CI%2FCD-GitHub%20Actions-2088FF?logo=githubactions&logoColor=white"></a>
  <a href="#"><img alt="Backend" src="https://img.shields.io/badge/Backend-Spring%20Boot-6DB33F?logo=springboot&logoColor=white"></a>
  <a href="#"><img alt="Frontend" src="https://img.shields.io/badge/Frontend-React-61DAFB?logo=react&logoColor=black"></a>
</p>

<!-- Frontend -->
<p>
  <a href="#"><img alt="React" src="https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=000000"></a>
  <a href="#"><img alt="Vite" src="https://img.shields.io/badge/Vite-646CFF?logo=vite&logoColor=white"></a>
  <a href="#"><img alt="styled-components" src="https://img.shields.io/badge/styled--components-DB7093?logo=styled-components&logoColor=white"></a>
  <!-- 필요 시 TypeScript 사용 시 추가 -->
  <!-- <a href="#"><img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white"></a> -->
</p>

<!-- Backend -->
<p>
  <a href="#"><img alt="Java" src="https://img.shields.io/badge/Java-007396?logo=openjdk&logoColor=white"></a>
  <a href="#"><img alt="Spring Boot" src="https://img.shields.io/badge/Spring%20Boot-6DB33F?logo=springboot&logoColor=white"></a>
  <a href="#"><img alt="Spring Security" src="https://img.shields.io/badge/Spring%20Security-43A047?logo=springsecurity&logoColor=white"></a>
  <a href="#"><img alt="OAuth 2.0" src="https://img.shields.io/badge/OAuth%202.0-000000"></a>
  <a href="#"><img alt="JWT" src="https://img.shields.io/badge/JWT-000000?logo=jsonwebtokens&logoColor=white"></a>
  <a href="#"><img alt="JPA / Hibernate" src="https://img.shields.io/badge/JPA%20%2F%20Hibernate-59666C?logo=hibernate&logoColor=white"></a>
  <a href="#"><img alt="OpenAPI/Swagger" src="https://img.shields.io/badge/OpenAPI%20%2F%20Swagger-85EA2D?logo=swagger&logoColor=black"></a>
</p>

<!-- Infra & DevOps -->
<p>
  <a href="#"><img alt="AWS" src="https://img.shields.io/badge/AWS-232F3E?logo=amazonaws&logoColor=white"></a>
  <a href="#"><img alt="EC2" src="https://img.shields.io/badge/EC2-FF9900?logo=amazonec2&logoColor=white"></a>
  <a href="#"><img alt="RDS" src="https://img.shields.io/badge/RDS-527FFF?logo=amazonrds&logoColor=white"></a>
  <a href="#"><img alt="S3" src="https://img.shields.io/badge/S3-569A31?logo=amazons3&logoColor=white"></a>
  <a href="#"><img alt="Nginx" src="https://img.shields.io/badge/Nginx-009639?logo=nginx&logoColor=white"></a>
  <a href="#"><img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white"></a>
  <a href="#"><img alt="Docker Compose" src="https://img.shields.io/badge/Docker%20Compose-1D63ED?logo=docker&logoColor=white"></a>
  <a href="#"><img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=githubactions&logoColor=white"></a>
  <!-- 필요 시 CloudFront, ECR 등 추가 -->
  <!-- <a href="#"><img alt="CloudFront" src="https://img.shields.io/badge/CloudFront-232F3E?logo=amazonaws&logoColor=white"></a> -->
  <!-- <a href="#"><img alt="ECR" src="https://img.shields.io/badge/ECR-FF9900?logo=amazonaws&logoColor=white"></a> -->
</p>

<!-- Database & Build -->
<p>
  <a href="#"><img alt="MySQL" src="https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white"></a>
  <a href="#"><img alt="Gradle" src="https://img.shields.io/badge/Gradle-02303A?logo=gradle&logoColor=white"></a>
  <a href="#"><img alt="Maven" src="https://img.shields.io/badge/Maven-C71A36?logo=apachemaven&logoColor=white"></a>
</p>

---

> ## 7. 비즈니스 모델
**Freemium (무료 + 구독)**  
- 기본: 음식 검색/재료 분석  
- 프리미엄: 맞춤형 식단 추천, AI 영양 분석 리포트, 가족 공유 계정  

**B2B 제휴**  
- 건강기능식품 & 영양제 브랜드 협찬·샘플링  
- 산후조리원, 산부인과 부가서비스 연계  

---

> ## 8. 추후 로드맵
- ✅ MVP: 음식 검색 & 위험도 확인  
- ⬜ AI 기반 맞춤형 식단 추천  
- ⬜ 가족/의사 계정 공유 기능  
- ⬜ 앱 런칭 및 B2B 파트너십 확장  

---

<div align="center">
  <sub>© EATAMAMA — All rights reserved.</sub>
</div>
