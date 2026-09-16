<div align="center">

# 👋 Hello, I'm Kobe

### Backend Developer | Java & Spring Boot Enthusiast

*A traveler who loves nature, stars, and books*

[![Email](https://img.shields.io/badge/Email-dev.skyachieve91@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:dev.skyachieve91@gmail.com)

</div>

---

## 🧑‍💻 About Me

```java
public class Developer {
    private String name = "Kobe";
    private String role = "Backend Developer";
    private String[] interests = {"JVM", "Spring Ecosystem", "Clean Architecture"};
    
    public void introduce() {
        System.out.println("🧑‍💻 Recently worked at PUMP");
        System.out.println("👨‍🎓 Graduated from Mokwon University");
        System.out.println("🐻 Completed 9th Yagom Career Starter Camp");
        System.out.println("🔍 Looking for SpringBoot projects to contribute");
        System.out.println("📝 Enjoying learning, organizing, and documenting");
    }
}
```

---

## 🪈 Open Source

### [piedpiper](https://github.com/devKobe24/piedpiper)

**명세 문서에서 Phase별 구현과 기능 마감까지 안내하는 Claude Code 워크플로 플러그인**

[![Claude Code](https://img.shields.io/badge/Claude%20Code-Workflow-D97757?style=flat-square)](https://github.com/devKobe24/piedpiper)
[![MIT License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)](https://github.com/devKobe24/piedpiper/blob/main/LICENSE)

요구사항 정리, 조사, 구현 계획, 리뷰, 완료 보고를 하나의 흐름으로 연결합니다.</br>
현재 진행 상황을 판단해 **사용자가 확인하고 실행할 다음 명령어**를 완성해 제시합니다.

- **명세 구체화**: 미결 사항을 질문으로 정리하고, 조사에 필요한 질문과 확정된 답변을 기록합니다.
- **Phase 계획**: 각 구현 단계에 테스트 통과 여부처럼 판정 가능한 완료 조건을 정의합니다.
- **진행 상태 확인**: 완료로 기록된 Phase를 실제 소스·테스트 파일과 대조해 다음 단계를 안내합니다.
- **결정 근거 전달**: 의도적으로 유지한 코드와 그 이유를 리뷰 안내에 포함하고, 기능 완료 보고서로 정리합니다.

**설계 포인트**: `CLAUDE.md`에는 계획을, `.progress-report/`에는 진행 상태와 결정 근거를 분리해 관리합니다.</br>
Claude Code의 `/deep-research`, `/goal`과 [ponytail](https://github.com/DietrichGebert/ponytail)을 연결하며, 상태 파일은 사용자가 관리합니다.

**검증 경험**: Spring Boot 프로젝트(Java 21 + Gradle, 할 일 목록 API)에서 명세 작성부터 기능 하나 완료까지 전체 흐름을 확인했습니다.

[설치 및 사용 방법](https://github.com/devKobe24/piedpiper#readme) · [문제 신고 및 피드백](https://github.com/devKobe24/piedpiper/issues)

---

## 📦 Featured Projects

<table>
<tr>
<td width="50%">

### 🏪 [DevKobeBlog](https://github.com/devKobe24/DevKobeBlog)
개발 블로그
- **Tech**: Spring Boot 3.2.2, JPA, MySQL, Docker, AWS S3, JGit, Flexmark, Thymeleaf
- **Features**: Git-Driven CMS, GitHub Webhook 자동 동기화, 마크다운 파싱, S3 이미지 자동 업로드, 카테고리/태그 시스템
- **Highlights**: Git Push만으로 블로그 자동 발행, 마크다운 Front Matter 기반 메타데이터 관리, 비동기 동기화 처리로 성능 최적화

</td>
<td width="50%">

### 🎮 [PokeKernal](https://github.com/devKobe24/pokekernal)
포켓몬 카드 컬렉션 관리 시스템
- **Tech**: Spring Boot 3.2.0, JPA, QueryDSL, MySQL, AWS S3/CloudFront, Chart.js, Thymeleaf
- **Features**: 카드 등록/관리, 상태별 분류(7단계), 시세 추적 및 그래프 시각화, 수익률 분석 대시보드, 위시리스트 관리
- **Highlights**: 이미지 자동 S3 업로드 및 CDN 배포, 개별/전체 컬렉션 수익률 계산, 프로필별 환경 분리(dev: H2 로컬, prod: MySQL + S3)

</td>
</tr>
<tr>
<td width="50%">

### 🛒 [Moamart](https://github.com/devKobe24/moamart)
픽업 서비스 기반 온라인 마켓
- **Tech**: Spring Boot 3.x, JPA, QueryDSL, Spring Security, MySQL, AWS S3, Thymeleaf, Thumbnailator
- **Features**: 매장별 픽업 서비스, 실시간 재고 관리, 부분 반품/교환 시스템, 비회원 주문, 종량제 봉투 선택, Markdown 상품 설명
- **Highlights**: 개별 상품 단위 상태 관리로 부분 반품/교환 지원, 이미지 자동 리사이징 및 최적화(Thumbnailator), 차액/환불 금액 자동 계산

</td>
<td width="50%">

### 📸 [ClickSnap](https://github.com/devKobe24/clicksnap)
4컷 사진부스 서비스
- **Tech**: Spring Boot 3.3.5, Canvas API, MediaStream API, Vanilla JavaScript, Multipart File Upload
- **Features**: 웹캠 실시간 촬영, 5초 카운트다운, 11가지 감성 필터, 4컷 자동 합성(900x1200 → 1000x5200 스트립), PNG 다운로드
- **Highlights**: Canvas Filter API + Pixel-level Fallback으로 모든 브라우저 호환, UUID 기반 파일명 및 Path Traversal 방지로 보안 강화

</td>
</tr>
</table>

<details>
<summary><b>📚 More Projects</b></summary>

- **[Recomon](https://github.com/devKobe24/recomon)** - AI 기반 도서 추천 시스템
- **[Solitaire](https://github.com/devKobe24/solitaire)** - 클래식 카드 게임 구현
- **[Kobe Website](https://github.com/devKobe24/kobe-website)** - 개인 포트폴리오 웹사이트

</details>

---

## 📱 Released Apps

- **Pomorail** - [View on the App Store](https://apps.apple.com/kr/app/pomorail/id6806898602)
- **Focus Habit Tracker** — [View on the App Store](https://apps.apple.com/kr/app/focus-habit-tracker/id6787873226)
- **Pholendar** — [View on the App Store](https://apps.apple.com/kr/app/pholendar/id6789025192)

---

## 🛠️ Tech Stack

![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square)

| Area | Technologies |
| --- | --- |
| Backend | Java, Spring Boot, JPA / Hibernate, QueryDSL, Lombok |
| Database | MySQL, Redis |
| Authentication & Security | Spring Security, JWT |
| DevOps & Cloud | AWS, Docker |
| Developer Tools | Claude Code, Git, IntelliJ IDEA, VS Code |

---

## 📫 Contact Me

Spring Boot 프로젝트와 개발 도구에 관한 이야기, 협업 제안을 환영합니다.

[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dev.skyachieve91@gmail.com)

---

<div align="center">

*"Talk is Cheap. Show me the code." - Linus Torvalds*

![Visitor Count](https://komarev.com/ghpvc/?username=devKobe24&color=blueviolet&style=flat-square)

</div>

         







