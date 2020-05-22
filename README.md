# portfolio
포트폴리오


1. 대인훼리 여객 시스템 https://agent.dainferry.co.kr
```
spring framework
kendoUI
spring-security
aop-Transactional
jasperReport
```
![init](./images/dainferryMain.jpg)

kendo Grid 작업 
![grid](./images/kendoGrid.jpg)

kendo scheduler
![scheduler](./images/scheduler.jpg)

예약화면    
![init](./images/reserve.jpg)

jasper Report 출력물
![print](./images/print.jpg)

spring-security

```
url intercept
```
![urlIntercept](./images/urlIntercept.jpg)
```
login , logout
```
![urlIntercept](./images/login_logout.jpg)
```
userService 구현
password 암호화 sha256사용
```
![urlIntercept](./images/userService.jpg)

```
'aop 트랜잭션'
select 제외 service 부분에서 자동 처리되도록 설정
```
![transaction](./images/transaction.jpg)

2. spring integration 세틀뱅크 전문시스템
``` 
ip:tcp-connection-factory
service factory
serializer, deserializer ( 직렬화 , 역직렬화 )
encoding message : euc-kr,  project : utf-8
```
```
ip:tcp-connection-factory

흐름
server-factory 생성 -> client msg 송신 -> gateway -> message 역직렬화 -> channelRouter(채널분기)-> channel -> serviceActivator(로직구현)
-> outchannel -> 직렬화 송신
```
![tcpFactory](./images/tcpFactory.jpg)
![tcpFactory](./images/gateway.jpg)
![tcpFactory](./images/router.jpg)
![tcpFactory](./images/serviceActivator.jpg)
```
serializer, deserializer ( 직렬화 , 역직렬화 )
seed 암호화 , base64Encoding
```
![deserialize](./images/deserialize.jpg)
![serialize](./images/serialize.jpg)

3. 대인훼리 선박 시스템 
```
기존 대인훼리 여객 시스템 Bootstrap 이용하여 반응형으로 재구성
ZXing.js 바코드스캐너 구현
jQuery-Scanner-Detection 바코드스캐너 연동하여 값읽기 구현
좌석배치도 구현
```
기존 main에서 반응형으로 구현
![responsiveMain](./images/responsiveMain.jpg)
![sidebar](./images/sidebar.jpg)
![responsiveGrid](./images/responsiveGrid.jpg)
```
좌석배치도 leaflet.js 로구현
그림 포토샵 사용
포토샵에서 x, y 좌표 추출해주는 PhotoshopToSpine 사용 (databinding)
```
![responsiveGrid](./images/seatDiagram.jpg)
![responsiveGrid](./images/seatDiagram2.jpg)

