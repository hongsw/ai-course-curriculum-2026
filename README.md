# Teaching AI-Assisted Coding & LLM Fine-Tuning — Undergraduate Curriculum (2026)

> 2026학년도 1학기 연세대학교 학부 두 과목의 **커리큘럼 설계 + 익명 집계 통계 + 개선안** 공개 자료.
> Open curriculum design, aggregate outcome data, and lessons learned from two undergraduate courses.
>
> **학생 이름·학번·점수·개인 repo·특정 프로젝트 도메인은 포함하지 않습니다.** 집계 통계와 설계만 공개합니다.
> No student names, IDs, individual grades, personal repos, or identifying project details — aggregate stats and design only.

---

## 무엇을 가르쳤나 / What was taught

| 과목 | 한 줄 | 아크 |
|------|-------|------|
| **오픈소스SW응용** (Open-Source SW Applications) | AI 코딩 도구로 오픈소스를 다루는 법 | 상향식: 도구 온보딩 → 산출물 → 배포형 에이전트 |
| **자연어정보분석** (NLP Information Analysis) | 한국어 NLP에서 LLM 파인튜닝으로 | 모델 내부로: 토크나이저 → Attention → 파인튜닝 |

두 과목의 공통 철학: **"AI API를 호출하는 법"이 아니라 "직접 만들고 개선하는 법"**을 손으로 익히게 한다.

---

## 📚 커리큘럼 / Curriculum

- [`curriculum/oss.md`](curriculum/oss.md) — 오픈소스SW응용 주차별 설계 (Git·터미널 → MCP → 로컬 LLM → Pi 에이전트 웹서비스)
- [`curriculum/nlp.md`](curriculum/nlp.md) — 자연어정보분석 주차별 설계 (토크나이저 벤치마크 → microGPT → Unsloth/QLoRA 파인튜닝)

각 문서는 주차별 **학습 목표 · 산출물 · 평가 루브릭**을 담습니다.

---

## 📊 집계 통계 / Aggregate outcomes

- [`stats/outcomes.md`](stats/outcomes.md) — 익명 집계 (점수 분포, 기술 스택, 도메인 다양성)

한눈에:

| 지표 | 오픈소스SW응용 | 자연어정보분석 |
|------|:---:|:---:|
| 기말 90점+ 비율 | **90%** | **83%** |
| 특징 | 10개 실서비스 도메인 | QLoRA 표준(10:2), Qwen 다수 |
| 파인튜닝 데이터 규모 | — | 20 ~ 53,000건 |

> 90점+ 비율은 유효 제출·채점 인원 기준.

> 모든 파인튜닝은 무료 Colab T4(15GB) 제약 하에서 재현 가능하게 수행됨.

---

## 💡 배운 것 / Lessons (2027 개선안)

1. **제출 규격을 표준화하라** — 명확한 산출물 규격(repo+보고서+영상)이 있던 과목은 제출 관련 사고가 없었고, 없던 과목은 제출 편차가 컸다.
2. **대형 기말은 마일스톤 3개로** — 주제 선정 → 중간 데모 → 최종.
3. **채점은 분량이 아니라 실질** — 직접 수행 증거·정량 개선·데이터 품질을 기준으로.
4. **두 과목 연계 캡스톤** — 파인튜닝한 모델을 에이전트 서비스로 배포하는 수직 통합.

전문: [`curriculum/improvements-2027.md`](curriculum/improvements-2027.md)

---

## 누구에게 유용한가 / Who this is for

- 비슷한 **AI/LLM 과목을 설계하는 교육자**
- 학부 수준 **에이전트·파인튜닝 실습 커리큘럼**을 찾는 분
- "AI로 무엇을 어디까지 가르칠 수 있나"가 궁금한 분

---

## 라이선스 / License

[CC BY 4.0](LICENSE) — 출처를 밝히면 자유롭게 사용·수정·재배포할 수 있습니다.
Free to use, adapt, and share with attribution.

---

*근거: 실제 강의 운영 데이터(과제 채점·제출물 감사)의 익명 집계. 개인 식별 정보는 제외되었습니다.*
*Based on anonymized aggregate data from actual course operation. No personally identifiable information included.*
