# 네트워크

1. OSI 7계층 ?

   - 네트워크의 통신을 7계층으로 나누어 각 계층이 수행하는 역할과 기능을 정의한 ISO 모델
   - 물리 계층 : 전기적, 광학적 신호를 사용하여 데이터를 전송하는 계층. 데이터를 0과 1로 이루어진 비트로 변환하고, 물리적인 매체를 통해 전송
   - 데이터 링크 계층 : 데이터의 오류를 검출하고 수정하는 계층.
   - 네트워크 계층 : 데이터를 목적지에 전잘하는 계층. IP 주소를 사용하여 데이터를 목적지까지 전달하는 경로르 결정

2. TCP / UDP 차이
   - TCP
     - 신뢰할 수 있는 연결 프로토콜.
     - 데이터의 순서를 보장하고, 손상된 데이터를 감지하고 수정하며, 패킷이 손실되지 않도록 보장.
     - 대용량 데이터 전송이나, 신뢰성이 중요한 응욮 프로그램에 적합하다
   - UDP
     - 비연결 프로토콜
     - 신뢰성 떨어짐, 데이터의 순서를 보장하지 않으며 손상된 데이터를 감지하거나 수정하지 않음.
