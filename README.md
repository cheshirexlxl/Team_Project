# 🎓 [팀프로젝트] Tutoring-Go

> "외국어 온라인 강의 튜터 매칭 플랫폼" 전 세계 외국인 학습자와 검증된 전문 외국어 튜터를 연결하는 1:1 맞춤형 학습 서비스 실시간 예약, 결제, 리뷰 시스템을 통해 최적의 학습 경험을 제공하는 플랫폼 입니다.

<br>

---

<img width="1396" height="785" alt="Image" src="https://github.com/user-attachments/assets/e97848b7-698b-4355-b16b-239eee1c694e" />

<br><br>

## 👥 프로젝트 참여자

<table>
  <thead>
    <tr>
      <th width="100">이름</th>
      <th>역할</th>
    </tr>    
  </thead>
  <tbody>
    <tr>
      <td align="center">정성준</td>
      <td align="left">JWT 기반 인증 필터 및 SecurityContext 처리 구현, 튜터 마이페이지, 예약 API 개발, 서버 측 예약 충돌 검증 로직 설계, Toss 결제 승인 처리 및 OpenAI API 연동 기능 구현, MyBatis 기반 DB 설계 및 매퍼 작성</td>
    </tr>
    <tr>
      <td align="center">이효미</td>
      <td align="left">사용자·튜터 API, DB 매퍼·DTO, 사용자 가입·튜터 등록 기능, 인증·보안, 예외/응답 표준화 <br> 프로필/문서 업로드 흐름과 FileService구현 및 업로드 저장소 구성</td>
    </tr> 
    <tr>
      <td align="center">김경화</td>
      <td align="left">전반적인 웹페이지 프론트 및 Figma 디자인, 요구사항/기능 정의서 , QA</td>
    </tr> 
    <tr align="center">
      <td>조성진</td>
      <td align="left">
        프론트엔드 개발 및 UI/UX 디자인 총괄, 디자인 시스템 및 시각화, 템플릿 구조화 및 생산성 향상, 핵심 비즈니스 로직 UI 구현, 회원 및 인증 서비스, 결제 및 부가 기능, 백엔드와의 연동, 한국어 속담 게임 페이지 구현, 푸터 링크페이지, 헤더 링크페이지 제작, PPT제작, ERD트리 작성
      </td>
    </tr> 
  </tbody>
</table>

<br>

## 개발 환경

- **Frontend**: `HTML5` `CSS3` `JavaScript` `Ajax` `Bootstrap`
- **Backend**: `Java 23` `Spring Boot` `Spring Security`  `Spring MVC` `MyBatis` `API` `JWT` `OAuth2` `Toss Payments` `Gradle` `Lombok`
- **Database & Infra**: `MySQL` `Git` `GitHub`
- **Tool**: `VSCode`

<br>

## 기획의도

최근 글로벌 교류와 해외 취업, 유학, 여행 등의 증가로 인해 전 세계적으로 외국어 학습에 대한 수요가 빠르게 증가하고 있습니다. 영어를 비롯해 일본어, 중국어, 스페인어 등 다양한 언어를 배우려는 학습자들이 늘어나면서, 온라인 기반 언어 학습 플랫폼의 중요성 또한 더욱 커지고 있습니다.

하지만 기존 대형 플랫폼들은 20~30%의 높은 수수료, 획일적인 커리큘럼, 경직된 스케줄로 인해 튜터와 학습자 모두에게 한계를 보이고 있습니다.
저희는 이러한 문제를 해결하기 위해 검증된 튜터 풀, 맞춤형 매칭, 유연한 예약, 합리적인 수수료 구조를 갖춘 새로운 플랫폼을 기획했습니다. 전 세계 학습자들이 자신에게 꼭 맞는 강사를 만나 효과적으로 학습할 수 있는 생태계를 구축하고자 합니다.


<br>

## 프로젝트 핵심 기능

![Image](https://github.com/user-attachments/assets/820652ba-f7ed-403a-93b8-2b2608dcd5d5)

<br>

## 활용방안 및 기대효과

![Image](https://github.com/user-attachments/assets/5c4cd5cc-369c-4755-9c0d-d2e0adda9675)

<br>

## 권한별 기능

![Image](https://github.com/user-attachments/assets/9d2e0dc6-7642-4da1-a6ff-db3903ef46e1)

<br>

## 주요 화면 구성

![Image](https://github.com/user-attachments/assets/87affa9c-3ab7-4af9-b765-0e1d2aaca5cb)

<br>

## 인증/보안 시스템

![Image](https://github.com/user-attachments/assets/95f83d2f-5fb3-43b7-843e-128d2e17ad3a)

<br>

## 예약 및 결제 시스템

![Image](https://github.com/user-attachments/assets/4630c46d-a181-4061-bafb-b268e0a9abfe)

<br>

## 요구사항 정의서

![Image](https://github.com/user-attachments/assets/2e82cddd-eb23-41e2-a6c4-b624e205157b)

<br>

---

<details>
  <summary><h2>ERD (펼쳐보기)</h2></summary>
  
  ![Image](https://github.com/user-attachments/assets/27174101-02cb-4ada-91bc-2d25afda008c)
  ![Image](https://github.com/user-attachments/assets/2d9d292d-0039-47ae-a7d7-12a506278254)
</details>

<br>

## 프로젝트 구조 (MVC+REST API)

![Image](https://github.com/user-attachments/assets/fad363af-a0bf-4eb1-ab99-2bf1a702a2b7)

<br>

## REST API구조

![Image](https://github.com/user-attachments/assets/a1f45024-f2db-4979-ba97-1e309046cc9d)

<br>

## 자체 평가 의견 (전체 의견)

![Image](https://github.com/user-attachments/assets/129b5653-be92-42e1-8695-37a3b169c040)

<br>

---

## 개별 평가 의견 (이효미, 백엔드담당 / 프론트 보조)

#### 기술적 성장

'외국어 온라인 강의 시스템 매칭 서비스'라는 주제로 4명의 팀원과 함께 백엔드 역할을 맡아 작업을 진행했습니다.
Spring Boot를 기반으로 강사회원과 일반회원의 회원가입 및 회원정보 수정 기능을 구현하며 사용자 유형에 따른 로직 분리와 데이터 설계에 대한 이해도가 향상되었습니다. 
또한 파일 업로드 기능을 구현하면서 Multipart 처리 방식과 서버 내 파일 저장 구조, 경로 관리 방법 등을 학습하는 경험을 할 수 있었습니다.
강사찾기 페이지의 필터 기능을 넣어 사용자 편의성 또한 고려했습니다.
프론트엔드 디자인 수정 작업에도 참여하면서 화면 구조와 백엔드 데이터 흐름에 대한 이해도도 높아졌다고 생각합니다.

#### 협업 경험

본 프로젝트는 프론트엔드 2명, 백엔드 2명으로 역할을 명확히 나뉘어 구성했고 기능 구현 과정에서 지속적인 소통으로 사전에 충분히 협의하며 각자의 역할을 수행했습니다.
백엔드 서브 역할이었지만, 필요한 부분에서는 의견을 제시하고 문제 해결에 참여하며 팀의 완성도를 높이는 데 기여했다고 생각합니다.

#### 경력 개발과의 연관

이번 프로젝트는 Spring Boot 기반의 웹 서비스 개발 경험을 체계적으로 정리할 수 있었던 기회였습니다.
회원 관리 및 파일 업로드 처리, API 설계 등 실무에서 자주 사용되는 기능을 직접 구현해보며 백엔드 개발자로서의 기본기를 다질 수 있었습니다.
이 프로젝트를 통해 전반적인 서비스 구조를 이해하고, 문제를 분석하고 해결하는 역량을 갖춘 개발자로 한 단계 성장할 수 있었다고 생각합니다. 
앞으로도 단순한 기능 구현을 넘어, 서비스 전체 흐름을 이해하는 개발자로 발전해 나가고 싶습니다.






