## papyruth-android-beta-issues
파피루스 베타 테스트에서 발생하는 버그 및 레이아웃 문제점을 모을 곳입니다.

## HISTORY
### [v0.0.8] 2016.1.8 / 01:04(+09:00)
> 
0.0.8버전이 Google Play Store 에 업로드 되었습니다.  
자원과 시간 상의 문제와 더불어 점점 저 해상도의 스마트폰 잔량이 줄어듦에 따라, hdpi(갤럭시 S2정도)와 API15(ICS, 아이스크림 샌드위치) 에 대한 지원은 하지 않기로 결정하였습니다. 기타 업데이트 사항은 다음과 같습니다.  
#### 업데이트 사항  
\- 기존에 있던 hdpi 지원을 위한 별도의 레이아웃 삭제  
\- API 16의 핸드폰에서 레이아웃이 잘못 표시되던 문제 수정  
\- 초 고해상도(xxxhdpi)를 위한 이미지 리소스 모두 업데이트  
\- 이메일을 보낸 후 인터넷 앱에서 인증을 한 후 돌아왔을 때 여전히 팝업창이 뜨던 문제 해결  
\- 로딩화면에서 취소를 눌러 앱을 종료하였는데 메인 혹은 로그인 화면이 나타나던 문제 해결 (앱이 완전히 종료됩니다)  
\- 로딩 화면에서 뒷 배경이 이동하지 않게 됩니다.  

### [v0.0.7] 2016.1.5 / 02:18(+09:00)
> 
0.0.7버전이 Google Play Store 에 업로드 되었습니다.  
앱이 조금 더 예뻐졌는데요, 네트워크 에러 / 검색 결과 없음 / 내 강의평 / 내 댓글 / 관심 강좌 탭에 아무것도 없을 때 대체하여 보여줄 아이콘과 문구들이 생겼습니다. 문구는 차차 수정해 나갈 텐데, 이에 대한 건의사항도 주시면 감사하겠습니다.  
#### 업데이트 사항  
\- 권한이 없는 상태에서 점수를 볼 수 없도록 하였습니다(비공개 처리).  
\- 네트워크 에러 / 빈 리스트 대신 보여줄 레이아웃의 아이콘 추가.  
\- 네트워크 에러 / 빈 리스트 대신 보여줄 레이아웃의 문구 수정.  
\- 이제 앱 시작/로그아웃 시 권한이 없다는 메세지가 출력되지 않습니다.  
\- 기타 사소한 버그 수정  

### [v0.0.6] 2016.1.2 / 23:44(+09:00)
> 
0.0.6버전이 Google Play Store 에 업로드 되었습니다.  
제가 정말 멍청한 실수를 해서...앱이 계속 죽었을...거에요...죄송...  
#### 업데이트 사항  
\- 어플리케이션 시작 시 죽는 문제를 해결하였습니다.  
\- 에러코드 401과 403의 대응 행동이 반대로 적용되어있던 문제를 고쳤습니다.  
\- 유저가 접근할 수 없을 때의 대한 안내가 향상되었습니다.  

### [v0.0.5] 2016.1.2 / 00:05(+09:00)
> 
0.0.5버전이 Google Play Store 에 업로드 되었습니다.  
다들 새해 복 많이 받으셨나요?? 새해 선물로 첫 업데이트를 드립니다:D  
#### 업데이트 사항  
\- 특정 상황에서 메인 화면이 로딩될 때 앱이 죽는 문제를 고쳤습니다.  
\- 이제 입학 년도 하한선이 서버에서 불려지는 값으로 설정됩니다.  
\- 특정 상황에서 알림과 리스트 사이에 있는 그림자 그라데이션이 잘못 적용되던 문제를 해결하였습니다.  
\- 로그인 화면에서 Galaxy S2 등의 저 해상도 앱을 위한 레이아웃이 전체에 적용되던 문제가 있었습니다. 이제 고해상도 앱에서도 제대로 된 로그인 화면이 나타납니다.  

### [v0.0.4] 2015.12.31 / 21:12(+09:00)
> 
0.0.4버전이 Google Play Store 에 업로드 되었습니다.  
미국은 아직 새해가 되려면 멀었으니까(^-^!!)  
새해가 될 때 쯤에는 새로운 버전으로 업데이트가 가능할 것 같습니다.  
모두들 새해 복 많이 받으세요!!  
#### 업데이트 사항  
\- 안내 문구의 확인 버튼을 눌렀을 때 죽는 버그를 고쳤다고 생각합니다. 부디 테스트..부탁드립니다.
\- 어플리케이션 시작 시 우측 아래에서 버전명을 확인하실 수 있습니다. (향후 앱 내 세팅 부분에도 추가하도록 하겠습니다)  
\- 디버깅용 로깅을 비활성화 하였습니다. 만약 아이콘들 한쪽에 삼각형들이 있으면 제보해주시면 감사하겠습니다.  
\- 원형 로딩 아이콘 색상들을 조금 어둡게 하였습니다 (기존이 더 밝았었음)  
\- 앱 밖으로 나갔다가 돌아오면 위에서 당겨 리프레시 하는 기능이 비활성화 되던 것을 고쳤습니다.  

### [v0.0.3] 2015.12.31 / 01:57(+09:00)
> 
VersionName v0.0.3 업데이트가 되었습니다.  
아침 즈음에는 앱스토어에서 받아서 보실 수 있습니다.
