# Learn about http basics

# Internet Network
* ## How internet Communicate
  * ### IP Packet
    * 출발지IP, 목적지IP 
    * 비신뢰성
    * 비연결성
  * ### TCP/IP Packet
    * 출발지 IP, 목적지 IP 등
    * 출발지 PORT, 목적지 PORT, 전송제어, 순서, 검증 정보 등
    * 전송 데이터
* ## 인터넷 프로토콜 스택의 4계층
  * ### 애플리케이션 계층
    * HTTP, FTP 
  * ### 전송 계층
    * TCP, UDP 
  * ### 인터넷 계층
    * IP
  * ### 네트워크 계층 
* ### TCP
  * TCP 3way handshake
    * SYN, SYN-ACK, ACK
  * PORT
    * 0 ~ 65535 : 할당 가능
    * 0 ~ 1023 : 비권장(잘 알려져 있음)
      * FTP - 20, 21
      * TELNET - 23
      * HTTP - 80
      * HTTPS - 443

* ### UDP
* ### DNS
