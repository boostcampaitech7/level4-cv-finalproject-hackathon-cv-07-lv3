<div align=center> 
  <img width="17%" alt="result" src="https://github.com/user-attachments/assets/af34adc8-fe57-494c-97cc-27543aed2a3d"> <br>
  <img width="20%" alt="result" src="https://github.com/user-attachments/assets/a549361c-41d1-44ee-8c49-b9292f4b13c5">
  <h2> AI 기반의 대학교 입학처 업무 자동화 및 의사 결정 지원 웹 서비스 </h2>
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

<br/>

### 문제 해결 방향
Upstage OCR, Chat API를 활용한 문제 해결 및 기능 구현
#### **1. 서류 업로드 및 OCR**
<p align="center"><img width="60%" alt="result" src="https://github.com/user-attachments/assets/344c68bf-88a1-4c30-9705-32c11fcf7e8a"></p>

#### **2. 입학 서류 자동 분류**
- 문서분류기
<p align="center"><img width="60%" alt="result" src="https://github.com/user-attachments/assets/4277ac1f-152c-4de1-9524-ad8f8f4907a1"></p>

- 서류 적부적합
<p align="center"><img width="60%" alt="result" src="https://github.com/user-attachments/assets/87e2c6ea-211f-4fcd-95be-68aa4640dd05"></p>

#### **3. 생활기록부 내용 요약 및 면접 질문 생성**
<p align="center"><img width="60%" alt="result" src="https://github.com/user-attachments/assets/9c415c6a-2c0e-472f-b177-60b2b2de039c"></p>

#### **4. 논술 답안지 요약문 생성 및 규칙 기반 자동 평가**
- 전처리 및 교정
<p align="center"><img width="60%" alt="result" src="https://github.com/user-attachments/assets/903d39e1-e687-4495-ad54-4c12ac985e04"></p>

- 요약문 생성 및 규칙 기반 평가
<p align="center"><img width="60%" alt="result" src="https://github.com/user-attachments/assets/2112cb0f-247e-4350-84af-f0a940fb0d66"></p>


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
      <img src="https://github.com/user-attachments/assets/ba4050d9-674a-46b7-bf9f-35b0afaaf03d" width="200" height="150"/>
      <br />
      <a href="https://github.com/kim-minsol">김민솔</a>
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/9a1d2899-0d7e-4295-9c73-39e33137c30a" width="200" height="145"/>
      <br />
      <a href="https://github.com/yeyechu">김예진</a>
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/740bbe37-5211-43ce-91b1-bffa84d6f8e7" width="200" height="145"/>
      <br />
      <a href="https://github.com/BaeHyungJoon">배형준</a>
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/b0e98476-cbf7-4aeb-89a1-cf30763c997b" width="200" height="145"/>
      <br />
      <a href="https://github.com/mongsam2">송재현</a>
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/dae2813d-1af9-489a-b611-b62299589f5d" width="200" height="145"/>
      <br />
      <a href="https://github.com/jxxhyo">이재효</a>
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/823c1087-b735-4265-a9be-609f1b7f3237" width="200" height="145"/>
      <br />
      <a href="https://github.com/MICHAA4">차성연</a>
    </td>
  </tr>
</table>

- **김민솔** : 생기부 면접 질문 기능 구현, 영상 편집
- **김예진** : 서류 업로드 기능 구현, 입학 서류 검토 기능 구현, PPT 제작
- **배형준** : 생기부 프롬프팅 고도화, 영상 제작, 발표
- **송재현** : 백엔드, 데이터베이스
- **이재효** : 프론트엔드, 생기부 요약 기능 구현, 영상 제작
- **차성연** : UI 디자인, 논술 기능 구현, 랩업리포트 작성

<br/>

## 5. 타임라인
<img width="100%" alt="result" src="https://github.com/user-attachments/assets/20e28be7-f0b2-4249-9836-d23530008120">

<br/>

<br/>

## 6. 시스템 아키텍쳐
<img width="100%" alt="result" src="https://github.com/user-attachments/assets/a1cb0223-7b13-472b-aa9b-fc85ccce53f1">

<br/>

<br/>


## 7. 발표자료 및 랩업리포트

- [발표자료](https://www.canva.com/design/DAGeSfDEtqA/7CaBUYudAD1WWYUqFpb_vQ/view?utm_content=DAGeSfDEtqA&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=hf34fca6da4) (링크)

- [랩업리포트](https://www.notion.so/naver-boostcamp-cv-07/AIMS-19a14f1bea6d80b18ee6e2e409edfba3?pvs=25)
