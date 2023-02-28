# POMODORO APP

## 노마드 코더 강의 : Flutter로 웹툰 앱 만들기 #5 POMODORO APP 실습 repo. <br /> <br />

### rfc

- Pomodoro 개요: 생산성 기술의 일종. 25분 동안 일한 뒤, 5분 휴식.
- 디자인 가이드: https://www.behance.net/gallery/98918603/POMO-UIKIT?tracking_source=search_projects%7Cpomo+uikit
- 요구사항 및 시나리오
  - Pomodoro의 기본 기능 구현.
  - 25분 카운터.
  - 시작 버튼 클릭시 카운트.
  - 시간이 0이 될시, 사용자가 완료한 총 횟수 1 증가.

<br />

### 0. User Interface (학습일자: 23.02.28)

- Flexible: UI 비율에 기반한 container.
- Expanded: 영역을 화면 끝까지 확장.
- ColorScheme.fromSwatch로 기설정된 컬러 스킴 수정 가능.
- pomodoro screen publishing.
  <br /><br />

### 1. Timer (학습일자: 23.02.28)

- Timer를 이용한 count state 구현.
  <br /><br />

### 2. Pause Play (학습일자: 23.02.28)

- isRunning state로 일시정지 기능 구현.
