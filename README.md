브라우저 저장소를 활용해 데이터를 영구 보존하고 실시간으로 관리하는 자바스크립트 웹앱입니다.

 주요 기능
- 등록: `form` 이벤트 차단 후 고유 ID(`Date.now()`)를 부여해 동적 추가
- 완료: 클릭 시 `completed` 클래스를 토글하여 시각적 효과(취소선) 제공
- 삭제: `filter` 메서드로 배열 불변성을 유지하며 DOM에서 제거
- 저장: `localStorage`와 `JSON` 메서드를 연동해 새로고침 후에도 데이터 유지

 핵심 기술
- `createElement`, `appendChild`를 통한 동적 DOM 조작
- `forEach`, `map`, `filter` 및 전개 연산자(`...`) 활용 상태 관리
- 기본 브라우저 동작 제어를 위한 `preventDefault()` 적용
