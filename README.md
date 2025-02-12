<div align=center> 
  <img width="17%" alt="result" src="https://github.com/user-attachments/assets/31e7fa7e-f7e3-40f3-bdd3-6b438c233447"> <br>
  <img width="20%" alt="result" src="https://github.com/user-attachments/assets/a549361c-41d1-44ee-8c49-b9292f4b13c5">
  <h1> AI 기반의 대학교 입학처 업무 자동화 및 의사 결정 지원 웹 서비스 </h1>
  전국 대학의 입학 과정을 담당하는 입학사정관 및 교수들을 위해<br>
  입학 서류 등록과 확인 작업을 자동화하고,<br>
  논술 답안을 요약하고 규칙 기반 평가를 자동 수행하는, <br>
  입학 업무 보조 시스템
</div>

<br>

## 1. 주제 선정 배경
<h3>[Upstage 기업 해커톤 주제] - 업무 자동화, 의사 결정 지원 등 비즈니스 가치 창출 AI 서비스 개발</h3>
<h4>1. 근무 중에 겪은 비효율적인 서류 검토 작업</h4>
서류 분류, 목록 대조 등 단순 반복 작업은 단순한 작업<br>
과도한 시간 소요와 안구 피로도 누적으로 실수 가능성 증가<br>
<h4>2. 생활기록부 및 논술 평가</h4>
정규직 입학 사정관이 감당 불가 → 단기 위촉 사정관 고용<br>
1인 당 평가하는 서류 수 가중으로 실수 가능성 농후<br>

<br>

## 2. 문제 정의 및 해결 방향

### 문제 정의
| 현업 입학사정관을 통한 요구 사항 파악 | 요구사항을 해결하기 위한 문제 정의 |
|----------------------------------------|-------------------------------------|
| 20,000 여건 서류 수작업 분류/검토로 체력적 부담 과중 | 입학 서류 자동 분류기 OCR, LLM으로 서류 유효성 검증 |
| 생기부 평가 항목에 알맞는 문장형의 요약문이 필요 | OCR과 LLM을 통해 평가 항목 기반 생기부 요약 기능 |
| 실면접 시 서류 완독 시간 부족 평가 항목 기반 질문 생성 기능 필요 | 생기부 평가 항목 기반 면접 질문 자동 생성 기능 |
| 연구 시간 부족! 빠른 채점을 위한 보조 도구 필요 | 논술 답안 추출 및 요약 기능 규칙 기반 자동 채점 기능 |

### 문제 해결 방향
Upstage OCR, Chat API를 활용한 문제 해결 및 기능 구현
- **서류 업로드 및 OCR**
- **입학 서류 자동 분류**
- **생활기록부 내용 요약 및 면접 질문 생성**
- **논술 답안지 요약문 생성 및 규칙 기반 평가**

<br>

## 3. 프로젝트 기대효과

**기존 서류 6000개 기준 약 15명이 3일 소요 작업** 

- **서류 당 1초 이내 분류** → 약 3시간 내외로 완료
- 서류 온라인 제출 변경 시 **전면 자동화 가능**

**생활기록부 요약 및 면접 질문 추천**
- 모든 지원자에게 신속/동등한 평가의 기회 제공
- 입학 사정관 업무 환경 개선
- **단기 위촉 사정관 고용에 필요한 비용 절감**

**논술 답안 요약 내용 제공 및 규칙 기반 자동 평가**
- 규칙 기반 평가 자동화 → 평가 일관성 확보
- 객관적 기준을 제공 → 평가 주관성 최소
- 평가 시간 단축 → **교수에 연구 집중 시간 보장**

<br>

## 4. 팀원소개 및 역할분배
<table>
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/51235bb8-bff2-4026-a2af-12e4eb78fe66" width="200" height="150"/>
      <br />
      <a href="https://github.com/kim-minsol">김민솔</a>
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/ba0a59b9-88db-43a1-995c-977a85c3128f" width="200" height="150"/>
      <br />
      <a href="https://github.com/yeyechu">김예진</a>
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/b9eee66f-51db-4dbb-b61f-f2ea12956da0" width="200" height="150"/>
      <br />
      <a href="https://github.com/BaeHyungJoon">배형준</a>
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/72df8b46-718a-4471-b176-ba17e3887a77" width="200" height="150"/>
      <br />
      <a href="https://github.com/mongsam2">송재현</a>
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/7afc3745-190d-426c-8f69-5b47fce5c0e1" width="200" height="150"/>
      <br />
      <a href="https://github.com/jxxhyo">이재효</a>
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/949fd85a-0a55-435b-8a36-20d98eac7ce4" width="200" height="150"/>
      <br />
      <a href="https://github.com/MICHAA4">차성연</a>
    </td>
  </tr>
</table>

<br/>

## 5. 타임라인
<img width="100%" alt="result" src="https://github.com/user-attachments/assets/20e28be7-f0b2-4249-9836-d23530008120">

<br/>

<br/>

## 6. 시스템 아키텍쳐
<img width="100%" alt="result" src="https://github.com/user-attachments/assets/a1cb0223-7b13-472b-aa9b-fc85ccce53f1">

<br/>


## 7. 발표자료 및 랩업리포트

- [발표자료](https://www.canva.com/design/DAGeSfDEtqA/xUDUK7duDaZQHo8sAlvMTA/edit?utm_content=DAGeSfDEtqA&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton) (링크)

- 랩업리포트 (추후업로드)
