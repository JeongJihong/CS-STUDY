# 네트워크

### 1. 웹 동작 방식은? 

<details>
    <summary>답 보기</summary>

    - 1. 사용자가 브라우저에 URL을 입력한다.
      2. 브라우저는 DNS를 통해 서버의 진짜 주소를 찾는다.
      3. HTTP 프로토콜을 사용해서 HTTP 요청 메세지를 생성한다.
      4. TCP/IP 연결을 통해 HTTP 요청이 서버로 전송된다.
      5. 서버는 HTTP 프로토콜을 활용해 HTTP 응답 메세지를 생성한다.
      6. TCP/IP 연결을 통해 요청한 컴퓨터로 전송한다.
      7. 도착한 HTTP 응답 메세지는 웹페이지 데이터로 변환되고, 웹 브라우저에 의해 출력되어 사용자가 볼 수 있다.
</details>



### 2. TCP, UDP의 차이는?

<details>
    <summary>답 보기</summary>

    - TCP는 연결형 서비스로 3-way handshaking 과정을 통해 연결을 설정한다. 높은 신뢰성을 보장하지만 속도가 느리다. UDP는 비연결형 서비스로 신뢰성이 떨어지지만 속도가 빠르다.

</details>



### 3. HTTP, HTTPS 차이는?

<details>
    <summary>답 보기</summary>
    
    - HTTP는 하이퍼 텍스트를 위한 통신 규약이고 여기에 정보를 암호화 하기위해 SSL을 사용한 것이 HTTPS이다. 인증기관으로부터 공개키를 저장한 인증서 발급을 요청함으로써 보안을 높인다.
</details>

