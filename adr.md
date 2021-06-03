ADR

0527 첫 회의 기록

Q. 논의 채널 결정
카톡
장점 : 편하게 접근 가능, 알람을 바로 확인 가능, 친숙
단점 : 휘발성이 높다, 대화를 정리하기 어렵다
SLACK
슬랙으로 하려고 했으나, 무료 버전은 메시지 제한이 있어서 기각
DISCORD
휘정님이 디스코드 사용에 불편을 느끼심
실시간으로 대화하기에는 좋으나 역시 대화 정리에 조금 번거로움이 있음
NOTION
회의 기록에 효율적
실시간으로 동시접속하여 수정할 수 있고 바로 반영됨 → 비대면 회의에 적합
1000블록 제한 → 역시 기각
Google Docs
Notion과 비슷한 기능(실시간 기록이 가장 큰 장점)
무료
+ 캘린더, Keep(메모), 할일목록 기능 (이건 공유 X, 각자 메모할 수 있는 칸 제공)
구글 미트와 연동하여 화면 공유가능 → 비대면 회의와 동시에 기록 가능합니다.
→ Google Docs 확정!
Q. 기술 도구 정하기

📌 Web vs App.
유진 : 웹에 더 관심이 많아 웹을 했으면 좋겠습니다. HTML, CSS로 웹을 제작해본 적 있습니다.
휘정 : 마찬가지로 웹에 더 관심이 많습니다.
→ 웹으로 결정

📌 FRONT
	→ JS, TS, React, Vue
 JS가 React와 함께 사용하기 좋다고 들었다.
	현재 JS 공부 중이고 JS에 좀 더 익숙하다
→ JS, React로 사용 (추후 변경 가능성 有) 

	📌 Database
→ RDBMS
휘정, 유진 : MySQL 사용 경험

	📌 DB → FRONT
	→ GraphQL - MySQL 사용
라이브러리 : Apollo
	GraphQL을 선택한 이유
: 기존 REST API의 문제점을 보완한 쿼리 언어 / 백엔드와 프론트엔드 간의 협업 도구로 뜨고 있다고 함 / 협업 구조상 백엔드보다 프론트엔드에 좀 더 힘이 실릴 수 있음(백엔드에의 의존성 약간 저하)
	참고
https://tech.kakao.com/2019/08/01/graphql-basic/
https://velog.io/@cadenzah/series/GraphQL-Node-Tutorial
https://velog.io/@cbj0523/GraphQL%EC%9D%84-Apollo-%EC%99%80-%ED%95%A8%EA%BB%98-%EC%8D%A8%EB%B3%B8-%ED%9B%84%EA%B8%B0

→ 스프링 
MVC 
Model : DB가 담겨있다
View : Front 화면 구성
Controller : 연결

	자바기반이라서 조금 친숙한 언어일 것이다. 하지만 파일을 다루기 쉽지 않고 이 또한
둘 다 다뤄본 적이 없습니다.

→ NodeJS
배우기 쉽다는 말을 들었었습니다.

공부를 한다면
https://www.inflearn.com/course/node-js-%EC%9B%B9%EA%B0%9C%EB%B0%9C

여기서 할 예정이고 잠깐 해보았는데 나름 이해가 되는 것으로 보아 학습이 어려울 것 같지는 않아보입니다.
