dentiq2 Web Client
==================

Project dentiq - second revision.

# 주요 변경 사항 (first revision 대비)

* 세션 유지 방식 변경
	- 세션 토큰에 서명 값 추가

* liveboard.html에 우리동네/관심지역 통합 처리
	- Summary를 서버에서 수신 받고 응답 값으로 다시 공고 목록 요청하는 방식으로 liveboard/우리동네/관심지역을 하나로 처리


# TODO

* 프리미어 공고 Rotation
	- 프리미어 공고의 경우, 좌측 스와이프를 '랜덤+공정'하게 보여주어야 하는데, 이에 대한 처리 방법이 필요함

* 공지 사항
	- 공지사항 기능 개발 및 이에 따르는 Admin화면도 개발하여야 하나?


# Road Map

* Rev. 2. (current)
	- 모바일 웹 개발
		- iOS Safari 테스트
	- Android App 개발
		- Android 앱 스토어에서 다운 가능
		- Android 앱 개발자 계정을 신규 개설
	- PC용 웹 개발
		- CSS 변경 및 JS 추가 (ie10 용)
	- 웹 환경 설정
		- Web 서버 및 API 서버, DB 서버 등을 신규 개설하여 환경 이관
		- 도메인
		- 이메일 서버 (or 서비스)
		- 비즈콜 전화 서비스
		- SMS 서비스
	- Etc.

* Rev. 3.
	- 카드 결제
		- 모바일 웹, PC 웹, iOS, Android 모두 가능
	- iOS App 개발
	- 이력서에 대한 liveboard 개발

* Rev. 4.
	- 외부 공고 스크래핑
		- 외부 공고 스크래핑 시, 정보를 병원정보와 공고 정보로 분리한 후 이를 현재의 DB 구조에 적용할 수 있어야 함
	- 위치 정보 기반 우리 동네 개발
		- 특정 지역 지도에서, 전체 병원/외부 공고 낸 병원/우리 공고 낸 병원 등을 표시할 수 있어야 함
	- 검색 기능
		- Elastic Search 등을 통하여 검색을 구현하여야 함 (검색 결과에서 현재 liveboard에 있는 필터링(지역, 속성) 기능 작동 가능하여야 함)
