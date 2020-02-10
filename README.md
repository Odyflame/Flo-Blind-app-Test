## Flo-Blind-app-Test

드림어스컴퍼니(FLO) 블라인드 채용 - 백엔드, 앱 개발 챌린지 과제작

- - -
프로그래머스 iOS 개발 부문 과제작입니다.

앱을 개발할 때 FLO 앱을 참고하여 UI나 디자인을 구상했습니다.

앱은 총 세개의 화면으로 구성되어 있습니다.

메인 화면과 앨범 사진 화면, 가사 화면으로 구성되있습니다.

![initail](https://github.com/odyflame/Flo-Blind-app-Test/blob/master/Flo%20Demo%20ScreenShot.png)

1. 메인 화면
 *  여기서는 음악 재생 화면이 나옵니다. 기업에서 준 [json](https://grepp-programmers-challenges.s3.ap-northeast-2.amazonaws.com/2020-flo/song.json) 주소를 사용하여 파싱을 한 다음 가수, 노래 제목, 앨범 이미지와 가사들이 나오도록 설정하였습니다.
 *  재생 버튼을 누르면 음악이 재생되며 가사가 알맞게 나오면서 싱크에 맞는 가사는 굵게, 그 다음 가사는 얇게 설정하였습니다.
 *  음악이 다 재생되면  종료되고 슬라이더는 처음으로 위치합니다. 
 *  play 버튼을 누르면 pause icon으로, pause icon을 누르면 다시 pause 버튼으로 이동합니다.

2. 앨범 사진 화면
  * 이 화면은 메인 화면에서 앨범 사진을 받아오며 사진을 클릭하면 다시 메인화면으로 이동합니다.


3. 가사 화면  
  * 메인 화면에서 가사를 눌렀을 시 전체 가사가 보여지며 가사를 클릭하면 다시 메인화면으로 돌아옵니다.

  
#### 앱을 완벽히 사용하기 위한 추후 개발과정
  >  빨리감기 버튼과 뒤로감기 버튼 기능을 구현해야 한다. 
 
 
프로그래머스 채용 홈페이지 : [https://programmers.co.kr/competitions/135/2020-dreamus-blind-recruitment](https://programmers.co.kr/competitions/135/2020-dreamus-blind-recruitment)
