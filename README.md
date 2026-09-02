# 신차 상담 에이전트 Master

기준일: 2026-08-31 · v2

## 구성
- `index.html`: Netlify 메인 진입 파일
- `assets/icons/agent.svg`: 타이틀/파비콘용 앱 스타일 아이콘
- `assets/icons/newcar.svg`: 신차 상담 아이콘
- `assets/icons/eco.svg`: 전기·수소차 상담 아이콘
- `assets/icons/tradein.svg`: 트레이드인 상담 아이콘
- `assets/icons/bluemembers.svg`: 블루멤버스 혜택 아이콘
- `netlify.toml`: Netlify 배포 설정

## 현재 4개 메인 메뉴
1. 신차 상담
2. 전기·수소차 상담
3. 트레이드인 상담
4. 블루멤버스 혜택 확인

## 버전 관리 원칙
이 ZIP을 현재 Master/Base로 사용합니다.
과거의 `newcar_agent_4menu.html` 등 단일 HTML은 Reference로만 사용하고,
향후 수정 시 Master 프로젝트 구조와 `assets/` 상대경로를 유지합니다.

## Netlify 배포
ZIP을 해제한 폴더 전체를 Netlify에 배포합니다.
`index.html`과 `assets/` 폴더의 상대적 위치를 변경하지 마세요.

## 주의
- 보조금 접수현황 일부는 프로토타입 데이터/화면일 수 있으므로 실제 운영 전 데이터 연동 검증이 필요합니다.
- 외부 링크 및 방문자 카운터 API는 네트워크 환경/회사 보안정책에 따라 동작이 제한될 수 있습니다.

## v2 변경사항
- Codex 아이콘 컨셉 원본 이미지를 assets/images에 보존.
- H안(겹쳐진 대화 말풍선)을 타이틀/파비콘 아이콘으로 적용.
- 프로젝트 내부 상대경로로 구성해 Netlify 배포 시 아이콘 누락 방지.
