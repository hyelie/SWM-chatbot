# 👋팀 소개  
- #### 팀 이름 : 멘토링.gg
- #### 팀장 : 박창환
- #### 팀원 : 손태균,최준성,차도인,정혜일,전민수
- #### 역할 :

| 리드프로그래밍 | 크롤링 | 서버 |  
|---|---|---|  
| - 정혜일 | - 손태균 </br> - 최준성 | - 전민수 </br> - 박창환 </br> - 차도일 |




# 📝개요  

- **멘토링 알리미 챗봇**  
소마 활동중 멘토링을 빠르게 확인하지 못해 참여하고 싶은 멘토링을 놓치는 경우가 다수 발생함.  
이러한 문제점을 해결하기 위하여 멘토링이 올라오면 빠르게 알려줄수 있는 챗봇을 개발.



# 📈구성도  
![image](/libs/images/structure.PNG)

# 📐동작 구현


1. 서버에서 60초마다 1번씩 크롤러 함수를 실행시킨다.
2. 크롤러 함수에서 db_num.txt 파일에 마지막으로 크롤링한 글의no를 저장해놓고 이를 이용하여 새로생긴 글의정보를 크롤링하여 서버로 전달한다
3. 새로생긴 글이 있을 시 사용자에게 글의 정보를 전달한다

- 실행 화면  

![image](/libs/images/screen1.PNG)  

멘토 이름 , 멘토링 제목, 멘토링 날짜 , 멘토링 링크주소를 보내줌.  

![image](/libs/images/screen2.PNG)  

동시에 여러글이 생겼을시 멘토링 마다 메세지를 보내줌  

# 🎈결론  

멘토링이 새로 등록될 때 제한 인원이 있는 경우가 많아 많은 분들이 원하는 멘토링이 등록되었을때 인지하지 못하여 잘 이용하지 못하는 경우가 많았습니다.  
저희가 개발한 멘토링 알림 챗봇을 이용하여 많은 분들이 원하는 멘토링을 듣는데 도움이 되었으면 좋겠습니다.😊  



![image](/libs/images/somalogo.png)

