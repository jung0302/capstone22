# capstone22

팀명:스테로이드<br>
이름:김승정(팀원:App)<br>
졸업작품 소개 사이트:URL<br>
포트폴리오 소개 사이트:URL<p>
 # [졸업 작품 소개]
- 작품명:Travel Roid
- Android Studio
- 작품 소개:여행을 다닐때 번역을 도와주고 그 위치에 날씨를 알려주는 앱
- 작품의 특징: 번역기능,위치에 따른 날씨정보 제공
        
 # 개발일지
 
 (4월 13일)<br>
 카카오 로그인 버튼 이미지 다운 후 로그인 시도해봄<br>
 카카오 로그인 api를 사용해서 로그인을 할려고 했는데<br>
 Toast.makeText(this, "토큰 정보 보기 실패", Toast.LENGTH_SHORT).show()<br>
 애뮬레이터에서 첫실행했을 때 토큰 정보 보기 실패 토스트 메시지가 나옴<br>
 토큰값이 없어서(?) 로그인이 되지않고 SecnodActivity로 넘어가지 못함.<br>
  Toast.makeText(this, "기타 에러", Toast.LENGTH_SHORT).show()<br>
 callback에서 기타 에러가 발생함. <br>
 로그아웃 버튼과 회원 탈퇴 버튼생성.<br>
 kakao developers에서 로그인 활상화 상태를 ON으로 변경.<br>
 일단 화면이 안넘어가는 오류로 로그인 api는 보류.<br>
 위치에 따른 날씨를 알려주기 위해 위치를 알려주는 api추가 시작.<br>
 build.gradle에 구글 플레이 서비스에 제공하는 api추가<br>
 AndroidManifest.xml에 권한 코드를 추가<br>
 <uses-permission android:name="android.permission.ACCESS_FINE_LOCATION" /><br>
 <uses-permission android:name="android.permission.ACCESS_COARSE_LOCATION" /><br>
 정확한 위치와 대략적인 위치 파악해서 현재위치를 가져올수 있게함.<br>
 
 
 
 
 (4월 10일)<br>
 해시 키 가져오는 것을 성공.<br>
 kakao Developers에 애플리케이션 추가하고 Android플랫폼 등록에서<br> 
 패키지명과 가져온 키해시를등록하고 앱을 등록함.<br>
 kakao sdk 사용을 위해 GlobalApplication 코틀린 class를 생성해서<br>
 appKey에 네이비트 앱 키를 작성함.<br>
 AndroidManifest.xml에 GlobalApplication class가 사용될 수 있도록<br>
 android:name=".GlobalApplication" 코드를 추가함.<br>
 그리고 로그인 창이 되는 액티비티를 추가함.<br>
 
 
 
 
 (4월 6일)<br>
 kotlin카카오 로그인 api를 구현해봄.<br>
 LoginActivity에서 로그인 했을때 <br>
 SecondActivity로 넘어가게 할려고함.<br>
 해시 키를 가져오는 과정에서 문제가 생김.<br>
 Android studio Arctic Fox 버전 이후 <br>
 gradle allprojects 추가방법을 보고 <br>
 settings.gradle에 레포지토리를 추가해야 한다는 것을 알게됨.<br>


 (3월 30일)<br>
 앱 이름을 Travel Roid로 정함.<br>
 github에서 협업 프로젝트 시작.<br>
 
 (3월 23일)<br>
 텍스트를 찍었을때 텍스트를 번역해주고 그위치에<br> 
 그위치의 날씨를 알려주는 앱을 만들기로함.<br>
 
  (3월 19일)<br>
 AI와 메시지를 주고 받는 API가 우리가 생각한 내용과<br> 
 거리가 있다고 판단되어 다른 아이디어를 생각한 결과<br>
 여행갈때 번역을 도와주는 앱을 만들기로 결정<br> 
        
 (3월 16일)<br>
 무슨 앱을 만들지 아이디어회의<br>
 메타버스,방치형 게임,AI와 메시지 주고 받기 등 아이디어가 나옴<br>
 최종적으로 AI와 메시지를 주고 받는 앱으로 결론 지음.
        
       
 

        
        
 
 

        
  
        
 
        
        
        


