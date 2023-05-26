# 목표
- 정보통신망의 정의와 목적, 간략한 역사를 설명할 수 있다. 
- 데이터통신 시스템의 구성요소를 열거할 수 있다.
- 점대점 선로와 멀티드롭 선로를 비교 설명할 수 있다. 
- 네트워크 연결장치에 대해 설명할 수 있다. 
- 데이터 교환방식에 대해 설명할 수 있다. 
- 정보통신망의 유형을 분류하고 설명할 수 있다. 
- 통신 프로토콜의 필요성을 설명할 수 있다.

# 정보통신 개요

## 정보통신 개념
- 통신
    - 서신, 봉화, 전보, 전화
- 정보통신
    - 디지털 데이터, 디지털 정보의 통신
- 정보통신망
    - 정보 기술 + 통신기술 + 네트워크기술
    - 컴퓨터통신망(컴퓨터의 역할을 강조한 용어)
    

## 정보통신 역사
- 광의의 통신 - 전기통신 이전
        - 서신, 봉화, 기타 다양한 기호
- 협의의 통신 - 데이터 통신
- 전보
    - 사무엘 모스, 모스 부호
- 전화기
    - 벨, 최초의 음성통화
- 계산기와 통신
    - 조지 스티비츠, 원격의 계산기에 데이터 통신 성공
- SAGE(Semi-Automatic Ground Environment) 시스템 (1958)
    - 컴퓨터와 통신을 결합시킨 최초의 컴퓨터 통신 시스템
- SABRE(Semi-Automatic Business Research Environment) 시스템 (1964)
    - American Airline사의 여객기 좌석 예약 업무 처리
- __ARPA(Advanced Research Project Agency) Network(60년대)__
    - __Internet의 전신(<- TCP/IP 개발)[->제 11강]__
![image](https://github.com/DJSon2/personal-study/assets/124123956/5183f92f-ca55-46dd-901b-9a9843fbd66d)

## 정보통신망의 목적
- 자원의 공유(resource sharing)
- 신뢰도(reliability) 향상
- 처리기능의 분산(disstribution)

# 정보통신망 구성
1. 데이터통신 시스템의 구성요소
![image](https://github.com/DJSon2/personal-study/assets/124123956/cbac738f-9ea0-461f-acc8-dc9db6d38e81)
2. 통신선로의 구성
    - 점대적 선로와 멀티드롭 선로
    ![image](https://github.com/DJSon2/personal-study/assets/124123956/8f4242d7-4d4f-43b4-b464-346a61d94e26)
3. 네트워크 연결장치
    - 네트워크 세그먼트를 서로 연결하거나 네트워크를 인터넷에 연결시키기 위한 통신 장치
    - 종류
        - Modem
        - NIC(Network Interface Card)
        - Hub(dumb hub; switching hub)
        - Repeater
        - Bridge
        - Router
        - Gateway
4. 네트워크 연결장치
    - Hub
        - 하나의 노드에서 수신한 신호를 정확히 재생하여 다른 노드로 전송하는 장치
        - 종류
            - 더미 허브(dumb hub)
            - 스위칭 허브(switching hub)
            - 스태커블 허브(Stackable hub)
    - Repeater
        - 장거리전송을 위해 신호를 새로 재생시키거나 출력 전압을 높여 주는 장치
    - Bridge
        - 복수개의 LAN을 연결하는 장치
    - Router
        - IP 네트워크 간의 연결 또는 IP 네트워크과 인터넷 간의 연결하기 위한 장치
    - Gateway
        - 서로 다른 통신 프로토콜을 사용하는 네트워크들을 연결하기 위한 장치
    ![image](https://github.com/DJSon2/personal-study/assets/124123956/54685116-d2b1-411d-a66b-b005d1966414)

# 정보통신 방식

## 데이터 전송방식
1. 전송방향에 따른 전송방식
![image](https://github.com/DJSon2/personal-study/assets/124123956/2508139a-35ed-4fca-b977-53cc2824aeff)
    - 전송모드에 따른 전송방식
        - 직렬전송(serial transmission)
        - 병렬전송(parallel transmission)
        ![image](https://github.com/DJSon2/personal-study/assets/124123956/664304e8-c916-4c2c-a2e3-a5c3a8edcd00)
        ![image](https://github.com/DJSon2/personal-study/assets/124123956/61c038e1-799c-47e4-8f80-b5ad1ab59d1a)
2. 데이터 교환방식
![image](https://github.com/DJSon2/personal-study/assets/124123956/4c353a70-b9a7-4073-9fe6-3c49b9d31de9)
- 회션교환(circuit switching) 방식
- 축적교환(store-and-forward switching) 방식
    - 메시지교환 방식
    - 패킷교환 방식
        - 가상회선 방식
        - 데이터그램 방식
![image](https://github.com/DJSon2/personal-study/assets/124123956/bda67c3e-0041-4d1d-ba92-559b23b5ea6f)
![image](https://github.com/DJSon2/personal-study/assets/124123956/9b317d92-8fb4-4fd2-a596-911d95c3103d)
![image](https://github.com/DJSon2/personal-study/assets/124123956/e5db929d-2c85-4ba0-9974-64bac12e10c4)
![image](https://github.com/DJSon2/personal-study/assets/124123956/cb927e87-31b0-4105-b5f3-fd2860d83b59)
![image](https://github.com/DJSon2/personal-study/assets/124123956/d9035d4d-c165-4ae4-bf25-73b43dda942d)

# 정보통신망 유형
1. 위상에 따른 유형
    - 성형(star)
    - 환형(ring)
    - 버스형(bus)
    - 그물형(mesh)
    - 트리형(tree)
    ![image](https://github.com/DJSon2/personal-study/assets/124123956/16178803-e681-43f9-ade6-a5a4ee354df0)
2. 규모에 따른 유형
    - PAN(Personal Area Network)
    - LAN(Local Area Network)
    - CAN(Campus Area Network)
    - MAN(Metropolitan Area Network)
    - WAN(Wide Area Network)
3. 활용 목적에 따른 유형
    - VAN(Value Added Network)
        - 통신망사업자에게 전용선을 임차하여 구성
        - 홈뱅킹, 홈쇼핑 등의 서비스 제공
    - ISDN(Integrated Services Digital Network)
        - 여러 서비스를 통합하여 제공(전화망과 컴퓨터망의 통합)
        - 하나읭 망에서 음성 통신과 영상 통신이 가능함
    - B-ISDN(Broadband ISDN)
        - 광대역 서비스가 가능한 ISDN
        - 광케이블을 이용한 통신(수백 Mbps)

# 통신 프로토콜
1. 통신 프로토콜의 필요성
    - 개념 및 필요성
        - "통신을 원하는 두 개체 간에 무엇을, 어떻게, 언제 통신하도록 할 것인지를 서로 약속한 규약"
2. 통신 프로토콜의 종류
    - TCP
    - IP
    - UDP
    - SMTP
    - POP3
    - HTTP

# 주요 정리
1. 정보통신망의 목적(자원공유, 신뢰도 향상, 처리기능 분산)
2. 정보통신망 구성
    - 통신선로의 구성(점대점/멀티드롭)
    - 네트워크 연결장치(hub, repeater, bridge, router, gateway)
3. 정보통신 방식
    - 데이터 전송 방식 
        - 전송방향 
            - 단방향, 반이중, 전이중 전송
        - 전송모드
            - 직렬, 병렬 전송
    - 데이터 교환 방식
        - 회선교환
        - 축적교환
            - 메시지교환
            - 패킷교환
                - 가상회선 방식
                - 데이터그램 방식
4. 정보통신망 유형
    - 위상에 따른 유형(성형, 환형, 버스형, 그물형, 트리형)
    - 규모에 따른 유형(PAN, LAN, CAN, MAN, WAN)
    - 활용목적에 따른 유형(VAN, ISDN, B-ISDN)
5. 통신 프로토콜
    - 필요성
        - 정의: 통신이 원하는 대로 구현되기 위해 통신 주체들간에 미리 정해놓은 규약
    - 통신 프로토콜의 종류
        - TCP, IP, UDP, SMTP, POP3, HTTP 등