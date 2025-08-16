# CounselFlow
상담 세션 관리 시스템. 
: 상담 시작부터 보류·실패·취소·진단중 단계를 거쳐 최종 완료까지의 흐름을 제어합니다.


React + TypeScript 기반 상담 플로우 관리 웹 애플리케이션

## 📌 소개
`consult-flow-manager`는 상담사가 고객 상담을 체계적으로 진행할 수 있도록 돕는 관리 도구입니다.  
상담 시작, 진행, 보류, 실패, 진단 완료까지의 전 과정을 직관적인 UI와 실시간 상태 동기화로 지원합니다.

---

## 🚀 주요 기능
- 상담 시작/진행 버튼 관리
- 보류, 실패, 취소, 진단중 등 상태 전환
- 상담 완료 후 자동 수렴 처리 (1분 타이머 포함)
- 실시간 상태 반영 (웹소켓 기반)
- 권한 기반 접근 제한 (관리자/매니저 차등 기능 제공)

---

## 🛠 기술 스택
- **Frontend**: React, TypeScript
- **State Management**: React Hooks
- **실시간 통신**: WebSocket + REST 초기 동기화
- **스타일링**: Tailwind CSS (선택 가능)

## 📦 설치 및 실행

```bash
# 의존성 설치
npm install

# 개발 서버 실행
npm run dev

# 빌드
npm run build
