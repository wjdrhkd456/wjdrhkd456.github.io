---
title: "Project Log. 2"
date: 2020-07-07 23:02:40 -0400
categories: project log
---

현재 정부사업을 진행하면서 기록하는 두 번째 로그이다.
<br><br>
어제와 오늘 뿌듯함과 아찔함을 둘 다 느꼈다.
<br><br>
Backend 쪽 service 와 mapper 의 이관을 거의다 마쳐놓은 상태로, 퍼블리싱이 나오기만을 기다리고 있는 요즘이다. 그러면서 미리 클라이언트쪽 작업을 sample view 를 만들어 진행중에 있다.
클라이언트쪽엔 공통으로 쓰이는 기능들이 많다. 가령 각 input에 대한 정합성 체크라던가,
고객들이 search를 하기 위해서 선택지들을 setting 해주는 등 comboBox를 구성해놓는 것 등이다.
이 '공통' 부분은 PL 님께서 현재 맡고 계신다. 개발자들이 좀 더 편리하게 api 를 사용할 수 있도록 고심해서 만들어야 하고, 재활용성이 좋도록 해야 한다.
어제 이 '공통' 부분에 대한 개발업무가 나에게도 주어졌다. PL님께서 상당수 개발을 하셨지만, 이외에도 맡고계신 파트가 많아 나에게 일부 개발을 요청해주셨다. 현재 사용하고 있는 UI tool 은 DataCollection
즉, Data Model 들을 GUI 형식으로 만들수가 있어서 직접 코딩을 하는 것보다 쉬울 수 있다. 하지만, PL님께서 GUI 작성까지도 하지 않고 페이지가 로딩될 때 동적으로 Data Model 의 생성부터, 그 Model 내
데이터를 받아오는 것까지 한꺼번에 처리할 수 있도록 했으면 좋겠다고 요청을 하셨다. 나 역시도 이렇게 구현을 해놓으면 협업하는 개발자들이 수고로움을 덜고 좀 더 특수한 업무들에 집중할 수 있겠다고 생각했다.
PL님의 업무를 받고 바로 작업을 시작했다. 로직을 직접 펜으로 그려서 정리하고 이를 코딩으로 옮겼다. 20% 작업을 하고 어느덧 퇴근시간이 되어 퇴근을 실시했다.
집에 가는 도중 PL님께 카톡을 받았다. "테스트는 꼭 하고 commit 하세요. 에러납니다..ㅜㅜ" 이 카톡을 확인하고 아차 싶었다. 평상시 Javascript가 에러를 compact 하게 잡지 않는다는 사실은 
잘 알고있었지만, 퇴근시간이 되어 급하게 코딩을 한 후 안일한 생각으로 commit을 한 것이다... 너무 죄송스러웠고, 경각심을 제대로 갖게 되었다.
<br><br>
다음날이 되었다.
<br><br>
PL님께 어제 있었던 일에 대해 바로 사과를 드렸고, PL님은 격려해주시고 오히려 응원해주셨다.~~너무 친절하시고 감사한 분이다.~~
이후 곧바로 작업을 시작했고, API Document 를 잘 찾아보며 차근차근 작업을 하니 4시간정도만에 작업을 완수할 수 있었다. 
동기들이 이를 테스트해줬고, 바로 본인들의 개발업무에 적용을 시키는 모습을 볼 수 있었다. 공들여서 만든 공통 기능 하나가 적용되는 모습이 너무 뿌듯했다.
PL님께도 좋은 리뷰를 받을 수 있었고, 두 번째 업무인 파일업로드 공통화 역시 실시하게 되었다. 내일도 치열하게 코딩해서 뿌듯함을 느껴보리라..!!


