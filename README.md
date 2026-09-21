### 박성호

웹 플랫폼 개발자. TypeScript와 Node로 만들고, 되돌릴 수 없는 기능에는 안전장치를 먼저 답니다.
AI로 만든 결과는 다른 모델이나 측정으로 검증하는 쪽을 좋아합니다.

- 사내 CMS를 단독으로 맡아 데이터 모델 18종, 관리자 화면 60개, REST API 118개까지
- AI 영상 생성 도구를 설계부터 서버, 과금, 설치형 배포까지
- VPS 5대와 자체 메일 서버(SMTP/IMAP, SPF/DKIM/DMARC) 운영과 장애 진단

**TypeScript, Next.js, Node, Prisma, PostgreSQL, Redis, Docker, GitHub Actions**

---

#### 만든 것

**[pantheon-skills](https://github.com/lolu1032/pantheon-skills)** — 하나의 모델이 낸 답을 믿지 않는 하네스

같은 과제를 여러 갈래로 구현하고, 각 결과를 다른 모델이 공격하게 한 뒤 견딘 것만 남깁니다.
이 구조로 돌려서 사람이 읽고 지나쳤던 순환 루프 오분류 결함을 실제로 잡았습니다. MIT.

**[daedalus](https://github.com/lolu1032/daedalus)** — 스키마 조언을 실측으로 뒷받침하는 스킬

오픈소스 스키마 969개(테이블 40,013)에서 패턴 31종을 뽑고, PostgreSQL 실험 42개를 7회씩
반복해 1,011회를 측정했습니다. 실행 시간이 회차마다 10~19% 흔들려서, 매번 같은 값이 나오는
읽은 블록 수를 근거로 삼았습니다. 카운터 인덱스가 HOT 업데이트를 죽이는 것, 자식 FK 인덱스
누락으로 부모 삭제가 75배 느려지는 것 같은 안티패턴을 수치로 검출합니다. MIT.

**[taperun](https://github.com/lolu1032/taperun)** — 기능 하나를 실제 크롬에서 끝까지 돌려보고 영상으로 남기는 E2E

통과 판정을 LLM이 아니라 시나리오의 expect 단계가 냅니다. Playwright 테스트 코드로도 변환합니다.

---

#### 기록

[lolu1032.github.io](https://lolu1032.github.io) — 공부한 것을 남기는 블로그
