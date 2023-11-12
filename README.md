# Learn about http basics

# Internet Network
* ## How internet Communicate?
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

--------------------------------------------------------------------------

# URI
* ## URI (Uniform Resource Identifier)
 * ### URL (Uniform Resource Locater)
   * 리소스가 있는 위치를 지정
   * Protocol (scheme)
   * Host name
   * port number
   * path
   * query parameter
   * fragment
 * ### URN (Uniform Resource Name)
   * 리소스에 이름을 부여
--------------------------------------------------------------------------
# HTTP
* ## HTTP history
  * HTTP/0.9 1991
    * GET Method, Http header X
  * HTTP/1.0 1996년
    * Method, header
  * *HTTP/1.1 1997년*
    * 현재 가장 많이 사용
  * HTTP/2 2015년
    * 성능 개선
  * HTTP/3 진행중
    * TCP 대신 UDP 사용
* ## Protocol based
  * TCP: HTTP/1.1, HTTP/2
  * UDP: HTTP/3
  * NOW: HTTP/1.1 주로 사용 (HTTP/2, HTTP/3도 증가하는 추세)
* ## HTTP?
  * ### Request, Response Structure (요청, 응답 구조)
  * ### Stateless (무상태 프로토콜)
  * ### connectionless (비연결)
  * ### HTTP Message
   * Request message
     * start-line 
     * header
     * empty line(CRLF)
     * (message body를 가질 수 있기는 함)
  * Response body 
     * start-line
     * header
     * empty line(CRLF)
     * Message body
