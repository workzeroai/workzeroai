![workzeroai — 광고 운영과 현장 업무를 AI·자동화 시스템으로 돌리는 AX 실무자](assets/banner.png)

### 광고 운영과 현장 업무를 AI·자동화 시스템으로 돌리는 AX 실무자

<sub>An AX practitioner who turns ad operations and field work into AI & automation systems that teams use every day.</sub>

- 이전 직장에서 퍼포먼스 마케터로 **월 약 4천만 원 다채널 광고**를 운영했습니다.
- 지금은 개발 조직이 없는 안전관리 전문 기업에서 현업의 반복 업무를 **LLM·API·자동화 시스템**으로 바꾸고, 현업이 매일 쓰도록 운영합니다.
- 자동 실행보다 **사람이 승인하는 자동화**를 기본으로 설계합니다.

#### 회사 운영 결과

| 업무 | 결과 |
|---|---|
| 검색광고 운영 자동화 | 3개 계정, API 반영 37건 실행 오류 0 · 2주 비교 노출 +67%, 평균 노출순위 2.7 → 2.1위 |
| LLM 계약서 PDF 자동 입력 | 약 1,145건 · 건당 1~3분(수기 추정) → 10~15초 |
| 견적 웹 도구 | 3개 사업부 약 2,250건 · 건당 6~24분 → 1~15분(추정) |
| 업무 데이터 통합 | 흩어진 데이터 약 2.2만 건 통합 |

<sub>위 수치는 실제 회사 운영 결과입니다. 공개 저장소의 코드와 데모는 같은 설계 아이디어를 가상 데이터로 새로 구현한 것입니다.</sub>

## 일하는 방식

<p align="center">
  <img src="assets/diagrams/how-i-work.png" alt="일하는 방식: 문제 정의 → 데이터로 진단 → 사람 승인형 자동화 구현 → 현업 정착·운영 → 성과 측정 → 다시 문제 정의" width="720">
</p>

1. **문제부터 정의한다** — 도구를 고르기 전에 누가, 어디서, 얼마나 자주 막히는지부터 확인합니다.
2. **사람 승인을 기본으로 한다** — 시스템은 제안하고 기록하며, 실행은 사람이 승인한 뒤에만 합니다.
3. **현업이 매일 쓰게 만든다** — 만든 날이 아니라 현업이 매일 쓰기 시작한 날을 완료로 봅니다.

## 대표 프로젝트

<sub>실무에서 운영한 구조를 회사 코드·데이터 없이, 가상 데이터로 처음부터 다시 구현한 공개 데모입니다.</sub>

<table>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/workzeroai/ad-ops-approval-engine"><img src="https://raw.githubusercontent.com/workzeroai/ad-ops-approval-engine/main/assets/banner.png" alt="ad-ops-approval-engine"></a>

**[ad-ops-approval-engine](https://github.com/workzeroai/ad-ops-approval-engine)** — 승인형 광고 운영 엔진<br>
광고 계정을 매일 진단해 규칙으로 조정안을 만들고, 사람이 승인한 것만 반영·재조회 검증·실행 ID로 되돌리기.<br>
<sub>Python · YAML 규칙 엔진 · SQLite 감사 로그 · 테스트 80개</sub>
</td>
<td width="50%" valign="top">
<a href="https://github.com/workzeroai/llm-doc-extraction-pipeline"><img src="https://raw.githubusercontent.com/workzeroai/llm-doc-extraction-pipeline/main/assets/banner.png" alt="llm-doc-extraction-pipeline"></a>

**[llm-doc-extraction-pipeline](https://github.com/workzeroai/llm-doc-extraction-pipeline)** — LLM 문서 추출 파이프라인<br>
PDF를 정해진 형식으로 추출 → 스키마·업무 규칙 검증 → 실패·애매한 건은 사람 확인 대기열로, 정확도까지 측정.<br>
<sub>Python · JSON Schema · n8n · Gemini/Claude/OpenAI 어댑터 · 테스트 87개</sub>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/workzeroai/airtable-korean-ime-fix"><img src="https://raw.githubusercontent.com/workzeroai/airtable-korean-ime-fix/main/assets/banner.png" alt="airtable-korean-ime-fix"></a>

**[airtable-korean-ime-fix](https://github.com/workzeroai/airtable-korean-ime-fix)** — 에어테이블 한글 입력 수정 도구<br>
셀 선택 후 한글 첫 글자가 영문으로 새는 문제를, 편집 모드 진입 키를 먼저 보내 막는 작은 도구.<br>
<sub>AutoHotkey v2</sub>
</td>
<td width="50%" valign="top">
</td>
</tr>
</table>

## 기술

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![Airtable](https://img.shields.io/badge/Airtable-18BFFF?style=flat-square&logo=airtable&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=claude&logoColor=white)

## 연락

- 이메일: [workzeroai@gmail.com](mailto:workzeroai@gmail.com)
- 노션 포트폴리오: [AX 포트폴리오](https://workzero.notion.site/AX-_-3d312e3c61c981958e60f69a8f6d546e)
