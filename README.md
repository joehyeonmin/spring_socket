# spring_socket

<h2>웹소켓 vs 소켓</h2>

1.웹소켓 - osi 7계층
2.소켓 - TCP/IP 4계층 (네트워크 접속, 인터넷, 전송, 응용 계층)에서 응용계층 바로 아래에 소켓 계층을 만듦

===

<h2>was</h2>
쓰레드풀에 쓰레드를 미리 만들어 놓고 꺼내쓴다(톰캣은 최대 200개 기본 설정)
쓰레드풀에 만들어놓은 쓰레드를 다 쓰고 있는데 요청이 들어오면 거절하거나 특정 숫자만큼 대기시킨다


<h3>웹소켓이 아닌 소켓통신을 하려면 java의 socket.io 라이브러리를 사용해야한다?</h3>
java.io.*
java.net.Socket

<h3>tls를 적용하려면</h3>
javax.net.ssl.KeyManagerFactory
javax.net.ssl.SSLContext
javax.net.ssl.SSLServerSocket
java.security.KeyStore
사용?




