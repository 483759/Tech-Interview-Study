- [네트워크](#네트워크)
- [인터넷](#인터넷)
- [네트워크 분류](#네트워크-분류)
- [네트워크 통신 방식](#네트워크-통신-방식)
- [프로토콜](#프로토콜)
- 참고 자료                  
        
        https://www.youtube.com/watch?v=Av9UFzl_wis&list=PL0d8NnikouEWcF1jJueLdjRIC4HsUlULi&index=1

## 네트워크
노드들이 데이터를 공유할 수 있게 하는 디지털 전기통신망     
분산된어 있는 컴퓨터를 통신망으로 연결한 것          

## 인터넷
문서, 그림 영상과 같은 여러가지 데이터를 공유하도록 구성된 세상에서 가장 큰 전세계를 연결하는 네트워크       
네트워크 망의 한 종류          
cf) www: 인터넷을 통해 웹과 관련된 데이터를 공유하는 것       

### 인터넷의 특징
1. TCP/IP라는 하나의 프로토콜만 사용    
2. 웹 브라우저 이용

## 네트워크 분류
  ### 크기에 따른 분류
    1. LAN(Local Area Network): 가까운 지역을 하나로 묶은 네트워크. 예) 같은 피시방에 있는 사람들끼리만 게임
    2. WAN(Wide Area Network): 멀리 떨어진 지역을 하나로 묶은 네트워크. 여러개의 LAN과 LAN을 하나로 묶은 것. 
  ### 연결 형태에 따른 분류
    1. Star형: 중앙 장비에 모든 노드 연결. 중앙 장비가 고장나면 네트워크 통신이 되지 않음. LAN 대역에서 주로 사용
    2. Mesh형: 여러 노드가 서로 연결. 어느 하나가 고장나도 전체에 영향 없음. WAN 대역에서 주로 사용
    * 실제 인터넷은 여러 형태가 혼합
    
## 네트워크 통신 방식
    1. 유니캐스트: 특정 대상과 1:1 통신. 목적지 주소가 아닌 다른 PC의 CPU 성능을 저하시키지 않음.(자신에게 온게 아니면 버려서)
    2. 멀티캐스트: 특정 다수와 1:N 통신. 
    3. 브로드캐스트: 내가 속한 네트워크 안의 모든 대상과 통신. 패킷을 받은 PC의 CPU 성능 저하.(하던 일을 멈추고 다른 일을 해야해서)

## 프로토콜
네트워크에서 노드와 노드가 통신할 때, 어떤 노드가 어느 노드에게 어떤 데이터를 어떻게 보내는지 작성하기 위한 약속           
여러 가지 프로토콜들로 캡슐화된 패킷 사용       

## 여러 가지 프로토콜
가까운 곳과 연락할 때: Ethernet 프로토콜(MAC 주소 사용)          
멀리 있는 곳과 연락할 때: ICMP, IPv4, ARP(IP 주소 사용)            
여러가지 프로그램으로 연락할 때: TCP, UDP(포트 번호)             