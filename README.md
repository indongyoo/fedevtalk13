# FEDevtalk 모던 자바스크립트를 활용한 서비스 개발기(13회)

 - 제목 - Template literals,  Promise,  동시성, 함수형 프로그래밍
 - 부제 - http://en.marpple.com 개발 경험기
 - [마플 영문 서비스 안드로이드 웹뷰 구동 영상](https://youtu.be/0Wc7CELvoiI)
 - [슬라이드](https://www.slideshare.net/ssuser2ecf32/template-literals-promise-126352081)
 - [FEDevtalk Github](https://github.com/NAVER-FEPlatform/FEDevtalk/blob/master/13_fedevtalk.md)

#### 라이브 코딩에서 간헐적으로 동작을 안했던 이유

자바스크립트 코드에는 문제가 없었는데 css의 `tr:active { background: #ccc; }` 때문에 간헐적으로 `transitionend` 이벤트가 제대로 동작을 안했던 것 같습니다. ㅠ_ㅠ. 평소에는 `requestAnimationFrame`을 사용했었다고... 시간이 없어서 `transitionend`를 썼다고... 이야기하고 싶지만... 시간을 돌리고 싶다.