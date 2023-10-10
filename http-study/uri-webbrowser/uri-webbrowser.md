# URI(Uniform Resource Identifier)
## URI? URL? URN?
* URI는 로케이터(*L*ocator), 이름(*N*ame) 또는 둘 다 추가로 분류될 수 있다.
* 즉, URI는 URL과 URN을 총칭하는 상위 개념이다.
* URI는 웹 상의 자원(resource)을 나타내는 고유한 식별자이다.
* 즉, 어떤 자원을 식별하고 찾을 수 있도록 하는 문자열.
### *U*niform: 리소스 시별하는 통일된 방식
### *R*esource: 자원, URI로 식별할 수 있는 모든 것(제한이 없다)
### *I*dentifier: 다른 항목과 구분하는데 필요한 정보

------------------------------------------------
# URL
* Locator : 리소스가 있는 위치를 지정
* 위치는 변할 수 있음.
* URL의 문법 및 구조
    * 프로토콜 (https)
    * 호스트명 (예: www.google.com)
    * 포트번호 (443)
    * path (예 : /main/sub)
    * 쿼리 파라미터(q=hi&name=jay)
* 예:
    * scheme://[userinfo@]host[:port][/path][?query][#fragment]
    * https:// www.google.com:443/search?q=hello&hl=ko

## *scheme*
* 주로 프로토콜을 사용
* 프로토콜: 어떤 방식으로 자원에 접근할 것인가 하는 규칙
* http, https, ftp 등
* http는 80포트, https는 443포트를 사용(포트 생략 가능)
* https는 http에서 강력한 보안이 추가된 형태이며, 최근에 많이 사용됨(HTTP Secure)

## *[userInfo@]*
* URL에 사용자 정보를 포함해서 인증하는 방식
* 최근에 거의 사용하지 않음

## *host*
* 호스트명
* 도메인 명 또는 IP주소를 직접 사용하는 것도 가능하다.

## *PORT*
* 접속 포트
* 일반적으로 생략함.

## *path*
* 리소스 경로(path)이며, 계층적 구조가 특징이다.
* 예) /main1/sub1, /main2/sub2, /home/file1.jpg

## *query*
- 웹 요청 URL의 일부, 웹 서버로 데이터를 전달하기 위한 목적으로 사용되는 문자열
- 일반적으로 URL 끝에 물음표(?) 뒤에 나오는 문자열로 구성
- 주로 키와 값 쌍으로 이루어져 있으며, 이를 request parameter라고도 말함.

## *fragment*
* html 내부 북마크 등에 사용
* 서버에 전송하는 정보가 아님

### URL 예시
예시 : search.naver.com/search.naver?where=nexearch&sm=top_hty&fbm=0&ie=utf8&query=무빙

1. 웹페이지의 주소(ip, 도메인) -  'search.naver.com'

2. 컨트롤러 매핑 경로 - '/search.naver /'

3. ? - Query String의 시작을 나타내는 구분자

4. 쿼리 스트링(키와 값, 쌍으로 이루어짐) - 'where=nexearch&sm=top_hty&fbm=0&ie=utf8&query=무빙'
------------------------------------------------
# URN
* Name : 리소스에 이름을 부여
* 이름은 변하지 않음
* URN 이름만으로 실제 리소스를 찾을 수 있는 방법이 보편화 되지 않으므로, 잘 사용되지 않는 개념이다.