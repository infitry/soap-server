### SOAP Server Example

스프링부트 SOAP Server 공식예제

##### WSDL 확인
http://localhost:8080/ws/countries.wsdl

#### SOAP 통신 확인

미리 생성해둔 요청 SOAP Body를 curl 을 통해 요청한다.
해당 SOAP Body 파일은 src/main/resources 에 request.xml 을 사용한다.
curl --header "content-type: text/xml" -d @request.xml http://localhost:8080/ws