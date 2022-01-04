# Instagram_Follower_Bot <a href="https://hits.seeyoufarm.com"><img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fbaka9131%2FInstagram_Follower_Bot&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false"/></a>

![K-002](https://user-images.githubusercontent.com/93738662/148058501-f8ce170e-f09b-443c-b402-766c00b1a9fe.gif)

### 필요한 프로그램
+ ChromeDriver가 필요합니다.
- 크롬 드라이버 설치 후 driver = webdriver.Chrome('chromedriver',options=options) 코드의 경로를 설정해 주세요 <br> 만약 같은 경로라면 수정 하지 않으셔도 됩니다.
+ https://chromedriver.chromium.org/downloads 공식 설치 홈페이지

### 인스타그램 팔로우 Bot 입니다.
제작환경 Jupyter Notebook 이며, 주석처리가 있으므로 쉽게 이해할 수 있습니다. 
+ [ 셀레니움 사용 ]

### 사용방법
1. elem.send_keys('아이디') # 아이디 입력
2. elem.send_keys('비밀번호') # 비밀번호 입력
3. 그 후 tag = input()을 통해 사용자를 겨냥할 Tag를 입력 받아 설정 합니다.
4. 이 후 따로 건드릴 필요 없이 반복적으로 팔로우를 자동으로 실행하게 됩니다.


### 주의사항
1. API 방식이 아닌 XPATH를 사용하여 Element를 찾는 방식이므로 주기적으로 XPATH 경로가 바뀔 수 있습니다. 변경사항이 발생했을 경우 수동으로 변경해주셔야 작동 됩니다.
2. 수정 사항이 발생될 경우 주기적으로 업데이트 하겠습니다.
  
### 추가 개발 사항
1. 텔레그램과 연동하여 실시간으로 진행사항 알림 설정 추가하기

### 급하게 하루 만에 만든 팔로우 Bot이라 오류 사항이 있을 수 있습니다.
