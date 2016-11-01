# singinglava
> 인사이드 아웃 시작하기 전에 나왔던 lava 노래가 너무 좋아서 남자 화산 여자 화산이 오래오래 사랑하라고 만든 프로젝트

 - lyricSender 프로세스는 가사 file을 읽어서 남자/여자 라바 프로세스에게 메시지를 라우팅 해서 MQTT프로토콜로 전송한다.
 - lava들은 자기 가사를 MQTT로 받으면 노래를 부른다. (broad cast로 환경 설정에서 읽은 특정 대역으로 전송)
 - lava들은 특정 가사를 받으면 그에 해당하는 표정을 짓는다. 
 
 ### 참 친절한 설계서
![alt tag](https://github.com/raregne/singinglava/blob/master/raw/whattodo.jpeg)