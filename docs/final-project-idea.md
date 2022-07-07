# Final-Project-Idea

## updata and send the latest news

제출 형식: 깃허브 액션 :octocat:

주제 선정 동기: 흩어진 정치, 경제, 사회, IT 등의 뉴스를 한번에 모아보기에 불편하다는 생각이 들었고, 이에
여러분야의 새로 업데이트 되는 내용의 뉴스를 분야별로 깃허브 액션을 통해 알려 사용자가 조금 더 편하게 뉴스를 접할 수 있게 하고싶었다.

프로젝트 설명: 깃허브 액션을 활용해 여러 분야의 뉴스를 스크랩핑 해오고 해당 데이터를 주기적으로 업데이트, 뉴스레터를 보내는 깃허브 액션 

1. [네이버 뉴스](https://news.naver.com/main/main.naver?mode=LSD&mid=shm&sid1=100)를 들어가서 아래의 분야의 뉴스들에 대해 이미지, 링크, 헤더, 요약뉴스부분을 스크랩핑 해온다.
*****
정치> 정치 일반

경제

사회>사건사고, 노동, 인권복지

생활정보> 건강정보

IT
*****

2. 위에서 스크랩핑 해온 정보를 json형태로 저장한다. 
3. 깃허브 액션에서 필요한 라이브러리들을 install 한다. 
4. 깃허브 액션으로 스크랩핑 해온 정보들을 자동으로 커밋, 푸쉬가 이루어 지게 한다.
5. 깃허브 액션으로 간단한 뉴스레터를 만들어 알림을 띄운다.

필요한 테크 스택: BeautifulSoup, Github Actions, python