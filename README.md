# O4O 체크인챌린지 챗봇 📚

교보문고 **O4O(Online for Offline) 매장방문 챌린지 및 체크인 서비스** 안내를 위한 모바일 웹 챗봇입니다.  
교보 디자인 시스템(**Kyobo Design System, KDS**) 표준을 준수하며, 클라이언트 사이드 **하이브리드 시맨틱 RAG(Retrieval-Augmented Generation)** 및 오픈소스 LLM(Ollama) 연동을 지원합니다.

---

## 🌟 주요 기능

1. **Kyobo Design System (KDS) 표준 적용**
   - KDS Core Action 컬러 (`blue-700` / `#5055B1`) 및 시맨틱 팔레트 적용
   - Noto Sans KR + Roboto (`letter-spacing: -0.01em`) 고가독성 타이포그래피
   - KDS 시그니처 4색 반시계방향(Counter-Clockwise) 로딩 스피너
   - H50 규격 모바일 최적화 인풋 필드 및 기하학적 SVG 라인 아이콘
   - 비즈니스 구어체(해요체) 및 정책 문어체(하십시오체) 브랜드 보이스 준수

2. **지능형 하이브리드 시맨틱 RAG 검색 엔진**
   - 별도 서버나 외부 API 키 없이 브라우저 단독(0ms)으로 지능형 시맨틱 질의응답 지원
   - 동의어 사전(환불-반품, 교환권-쿠폰, 위치-GPS 등) 및 N-gram 유사도 가중치 매칭

3. **오픈소스 LLM 원클릭 연동 (Ollama)**
   - 로컬 환경에서 구동되는 최신 오픈소스 모델(`EXAONE 3.5`, `Qwen 2.5`, `Gemma 2`)과 실시간 API 연동
   - 로컬 서버 미감지 시 내장 RAG로 안전 자동 전환(Fallback)

4. **연관 후속 질문 칩 (Next Best Questions)**
   - 질문 답변 시 하단에 고객이 이어서 탐색할 수 있는 연관 질문 칩 동적 제공

5. **현장 고객 응대용 원클릭 복사**
   - 매장 직원이 즉시 카카오톡, 문자, 사내 메신저로 전송할 수 있는 클립보드 복사 기능

---

## 🚀 GitHub Pages 배포 및 온라인 서비스 안내

이 레포지토리는 GitHub Pages를 통해 무료로 웹에 배포하여 누구나 모바일/PC에서 접속할 수 있습니다.

### 접속 주소
```
https://<GitHub_사용자ID>.github.io/<레포지토리_이름>/
```

### GitHub Pages 활성화 방법
1. GitHub 레포지토리의 **Settings** 탭으로 이동합니다.
2. 좌측 메뉴에서 **Pages**를 클릭합니다.
3. **Build and deployment** > **Source**에서 **Deploy from a branch**를 선택합니다.
4. **Branch**를 `main` / `/ (root)`로 설정하고 **Save**를 누릅니다.
5. 1~2분 후 생성된 온라인 URL로 즉시 접속 가능합니다.

---

## 🏢 기안 부서 및 운영
- **부서**: 교보문고 점포사업본부 점포운영지원팀
- **버전**: v1.0.0 (2026.09)
