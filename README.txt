++++++++  제네시스 홈페이지 배포 +++++++++++++++++++++++++++++++++++++++++++

GENESIS Fullscreen Carousel Project
Publisher: Moon Seon Jong

[구성]
index.html              메인 풀스크린 자동 캐러셀
landing.html            공용 랜딩페이지 (쿼리스트링으로 8개 이미지/콘텐츠 전환)
css/reset.css           리셋 스타일
css/style.css           메인 캐러셀 스타일
css/landing.css         랜딩페이지 스타일
js/script.js            자동재생/화살표/드래그/터치/클릭 이동
js/landing.js           랜딩페이지 데이터/타이틀 애니메이션/패럴럭스/goTop
images/slide01~08       업로드 이미지 8장

[동작]
- 4초 대기 후 다음 슬라이드 자동재생
- 이동시간 0.5초
- 무한루프
- 좌/우 화살표
- 데스크탑 마우스 드래그 / 모바일 터치 스와이프 (Pointer Events)
- 드래그가 아닌 클릭/탭일 때만 랜딩페이지 이동
- 랜딩페이지 풀스크린 히어로, 타이틀 등장 애니메이션, 스무스스크롤, 패럴럭스, goTop

[참고]
랜딩페이지 제원 및 가격은 수업/포트폴리오 데모용 예시 데이터입니다.

[수정사항]
- 슬라이드 단순 클릭/탭 시 landing.html?slide=번호 로 즉시 이동하도록 pointerup 기준으로 수정
- 드래그/스와이프와 클릭을 이동거리 임계값으로 분리하여 이벤트 충돌 방지
