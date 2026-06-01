1# ☕ Cafe-1 스마트 주문 및 AI 발주 연동 시스템 (cafe-1)

본 프로젝트는 김수현 PM이 기획 및 구축한 **Cafe-1호점 전용 스마트 오더 및 AI 발주 제어 시스템**입니다. 
구글 AI Studio를 통해 지능적으로 연계된 AI 에이전트를 내장하여, 카페 현장의 주문 접수, F&B 재고 추적 및 스마트 발주 인터페이스를 완벽하게 서포트합니다.

---

## 🚀 Cafe-1 AI 실시간 서비스 배포 및 바로가기 주소
*   **💻 Cafe-1 스마트 오더 모바일 배포 서비스 (Vercel Live)**: 
    👉 **[https://sh-cafe-1-service.vercel.app/index.html](https://sh-cafe-1-service.vercel.app/index.html)**
*   **🤖 Cafe-1 AI 주문 에이전트 다이렉트 프리뷰 (AI Studio Live)**:
   

---

## 📋 핵심 서비스 정의 및 설계 스펙
본 Cafe-1 시스템은 다음과 같은 차별화된 실무 AI 어시스턴트 기능을 탑재하고 있습니다:

1.  **☕ 스마트 오더 자동화**: 고객의 음료 선택 및 복합 커스텀 옵션(얼음량, 시럽 조절 등)의 지능적 분류 및 포스(POS) 연동 모듈 지원.
2.  **📦 F&B 재고 실시간 최적화**: 원두 및 부자재 소모율을 분석하여 재고 부족 예견 시 AI 발주 사양서 자동 추천 및 작성.
3.  **💬 고객 맞춤형 에이전트**: 카페 방문 패턴 및 날씨/이벤트를 고려하여 오늘의 추천 메뉴 제안 및 대화식 바리스타 서비스 시나리오 정의.

---

## 🛠️ 개발 기초 가이드라인
로컬에서의 개발 셋업 및 API 연동을 희망하는 경우 아래 단계를 따릅니다:

1.  **의존성 패키지 설치**:
    ```bash
    npm install
    ```
2.  **환경변수 구성**:
    `.env.local` 파일을 생성하고 아래 API 키를 기재합니다:
    ```env
    GEMINI_API_KEY=your_gemini_api_key_here
    ```
3.  **로컬 서비스 실행**:
    ```bash
    npm run dev
    ```

---

*본 저장소는 깃허브 [https://github.com/suhyunkim-maker/cafe-1](https://github.com/suhyunkim-maker/cafe-1) 원격 저장소와 연동되어 보존되는 공식 프로젝트 홈입니다.*
