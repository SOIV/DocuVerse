# DocuVerse
[한국어(KR)](readme_v2-ko.md) | [영어(EN)](readme_v2.md)

<div align="center">

![DocuVerse 로고](https://via.placeholder.com/200x200)

**강력한 협업 편집 기능을 갖춘 현대적인 문서 시스템**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![React](https://img.shields.io/badge/React-18.x-61DAFB.svg?logo=react&logoColor=white)](https://reactjs.org/)
[![Node.js](https://img.shields.io/badge/Node.js-16.x-339933.svg?logo=node.js&logoColor=white)](https://nodejs.org/)
[![MongoDB](https://img.shields.io/badge/MongoDB-5.x-47A248.svg?logo=mongodb&logoColor=white)](https://www.mongodb.com/)

</div>

## 🌟 개요

DocuVerse는 팀 협업과 지식 공유를 향상시키기 위해 개발된 종합적인 문서 관리 시스템입니다. 강력하고 유연한 편집 기능을 통해, DocuVerse는 팀이 기존 위키 시스템에서 찾아볼 수 없는 고급 기능으로 프로젝트 문서를 생성, 구성 및 유지할 수 있게 해줍니다.

### 주요 기능

- **고급 문서 에디터** - 강력한 표 지원을 통한 풍부하고 구조화된 문서 작성
- **실시간 협업** - 팀원들과 동시에 문서 편집
- **버전 관리** - 변경 사항 추적 및 필요시 이전 버전으로 복원
- **계층적 구조** - 유연하고 직관적인 구조로 문서 구성
- **풍부한 미디어 지원** - 이미지, 다이어그램, 코드 블록 등 삽입
- **강력한 검색** - Elasticsearch 통합으로 빠른 콘텐츠 검색
- **사용자 지정 권한** - 문서 및 카테고리 수준에서 접근 제어
- **내보내기 및 백업** - 여러 형식(JSON, Markdown, PDF, HTML)으로 문서 내보내기

## 🚀 시작하기

### 사전 요구 사항

- Node.js 16.x 이상
- MongoDB 5.x 이상
- npm 또는 yarn

### 설치

1. 저장소 복제:
   ```bash
   git clone https://github.com/your-organization/docuverse.git
   cd docuverse
   ```

2. 의존성 설치:
   ```bash
   # 서버 의존성 설치
   cd server
   npm install

   # 클라이언트 의존성 설치
   cd ../client
   npm install
   ```

3. 환경 변수 구성:
   ```bash
   # 서버 디렉토리에서
   cp .env.example .env
   # .env 파일을 구성에 맞게 수정
   ```

4. 개발 서버 시작:
   ```bash
   # 백엔드 서버 시작
   cd server
   npm run dev

   # 다른 터미널에서 프론트엔드 시작
   cd client
   npm run dev
   ```

5. 브라우저를 열고 http://localhost:3000으로 이동

## 🏗️ 아키텍처

DocuVerse는 최신 기술 스택을 사용하여 구축되었습니다:

### 프론트엔드
- **React.js** - UI 라이브러리
- **Redux** - 상태 관리
- **ProseMirror/TipTap** - 커스텀 문서 에디터의 기반
- **yjs** - 실시간 협업 데이터 구조
- **Material-UI/Tailwind CSS** - UI 컴포넌트

### 백엔드
- **Node.js + Express** - 서버 프레임워크
- **MongoDB** - 문서 데이터베이스
- **Elasticsearch** - 전체 텍스트 검색
- **Socket.io** - 실시간 통신
- **JWT** - 인증

## 🖋️ 고급 문서 에디터

DocuVerse의 에디터는 강력하면서도 직관적인 문서 편집 경험을 제공합니다:

- **포괄적인 마크업 지원** - 마크다운 및 커스텀 마크업 구문 완전 지원
- **고급 표 에디터** - 병합된 셀, 배경, 중첩 콘텐츠가 있는 복잡한 표 생성
- **접을 수 있는 섹션** - 콘텐츠 섹션 숨기기 및 표시
- **문서 구조** - 자동 목차 생성
- **드래그 앤 드롭** - 이미지나 파일을 쉽게 업로드하고 삽입
- **이중 모드** - 시각적 모드와 마크업 편집 모드 간 전환

## 👥 협업 기능

DocuVerse는 원활한 팀 협업을 가능하게 합니다:

- **실시간 공동 편집** - 여러 사용자가 동시에 같은 문서를 편집 가능
- **사용자 존재감** - 현재 문서를 보거나 편집 중인 사용자 확인
- **커서 추적** - 다른 사용자의 커서 위치 보기
- **변경 사항 강조** - 문서의 최근 변경 사항 쉽게 식별
- **댓글 및 토론** - 문서의 특정 부분에 대해 논의

## 🔒 보안

- JWT 기반 인증
- 세부적인 권한 제어
- 입력 유효성 검사 및 정제
- HTTPS 암호화

## 🗺️ 로드맵

| 단계 | 일정 | 주요 내용 |
|-------|----------|-------|
| MVP | 1-2개월 | 기본 마크다운 에디터, 문서 CRUD, 사용자 인증 |
| 핵심 | 2-3개월 | 버전 관리, 고급 에디터, 고급 검색 |
| 협업 | 2-3개월 | 실시간 편집, 알림, 댓글 |
| 고급 | 3-4개월 | CSS 테마, API 개발, 성능 최적화 |

## 🤝 기여하기

DocuVerse에 기여해 주세요! 시작하는 방법에 대한 자세한 내용은 [CONTRIBUTING.md](CONTRIBUTING.md)를 참조하세요.

## 🌐 Community

우리 커뮤니티에 참여하세요:

<div align="center">
  <a href="https://discord.gg/docuverse">
    <img src="https://img.shields.io/badge/Discord-%235865F2.svg?style=for-the-badge&logo=discord&logoColor=white" alt="디스코드">
  </a>
  <a href="https://x.com/DocuVerseApp">
    <img src="https://img.shields.io/badge/X-%23000000.svg?style=for-the-badge&logo=X&logoColor=white" alt="X">
  </a>
  <a href="https://instagram.com/DocuVerseOfficial">
    <img src="https://img.shields.io/badge/Instagram-%23E4405F.svg?style=for-the-badge&logo=Instagram&logoColor=white" alt="인스타그램">
  </a>
  <a href="https://youtube.com/c/DocuVerse">
    <img src="https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white" alt="유튜브">
  </a>
</div>

## 📜 라이선스

DocuVerse는 MIT 라이선스로 배포됩니다. 자세한 내용은 [LICENSE](LICENSE) 파일을 참조하세요.

이 DocuVerse project는 GPL-3.0 라이선스에 따라 라이선스가 부여되었습니다. 자세한 내용은 [LICENSE](LICENSE) 파일을 참조하세요.

## 📞 연락처

질문이나 지원이 필요하시면 [이슈 열기](https://github.com/SOIV/docuverse/issues)를 통해 문의하거나 biz@docuverse-pj.com 으로 연락주세요.
