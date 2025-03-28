[IANA 공식 문서](https://www.iana.org/assignments/protocol-numbers/protocol-numbers.xhtml)

IPv4(Internet Protocol Version 4)의 헤더에는 13개의 필드로 구성되어 있습니다.      

이중 프로토콜 필드는 8 비트 값으로 이루어져 있으며 4(전송) 계층에서 어떤 프로토콜을 사용하는지 명시하고 있습니다.         
프로토콜은 수납되는 상위 계층 프로토콜을 나타내는 식별자/유형/번호 정보를 포함합니다. 쉽게 말하면 컴퓨터 간 정보를 주고받을 때 통신방법에 대한 규약입니다. 
예를 들어 대화할 때 같은 언어를 사용해야 말이 통하는 것과 같습니다.대표적으로 사용하는 프로토콜은 ICMP(1), TCP(6), UDP(17) 입니다.    

ipv4 -> a.b.c.d /32 -> a.b.c.1~255
a.b.c.d/24 -> a.b.1~255.1~255


tcp 6, udp 17, icmp, 0,1

# 프로토콜 번호와 프로토콜 이름 + 기능 설명 추가 최종본

| 프로토콜 번호 | 프로토콜 이름 | 기능 설명 |
|--------------|---------------|-----------|
| 1            | ICMP          | 인터넷 제어 메시지 프로토콜로, 오류 보고 및 진단에 사용됩니다. |
| 2            | IGMP          | 인터넷 그룹 관리 프로토콜로, 멀티캐스트 그룹 관리를 담당합니다. |
| 3            | GGP           | 게이트웨이 간 프로토콜로, 초기 라우팅 프로토콜 중 하나입니다. |
| 4            | IPv4          | IPv4 패킷 캡슐화를 위한 프로토콜입니다. |
| 5            | ST            | 스트림 프로토콜로, 실시간 데이터 전송을 지원합니다. |
| 6            | TCP           | 전송 제어 프로토콜로, 신뢰성 있는 연결 지향 데이터 전송을 제공합니다. |
| 7            | CBT           | 코어 기반 트리 프로토콜로, 멀티캐스트 라우팅을 지원합니다. |
| 8            | EGP           | 외부 게이트웨이 프로토콜로, 자율 시스템 간 라우팅에 사용됩니다. |
| 9            | IGP           | 내부 게이트웨이 프로토콜로, 내부 라우팅에 사용됩니다. |
| 10           | BBN-RCC-MON   | BBN RCC 모니터링 프로토콜입니다. |
| 11           | NVP-II        | 네트워크 음성 프로토콜로, 음성 데이터 전송을 지원합니다. |
| 12           | PUP           | PARC 유니버설 패킷 프로토콜로, 초기의 패킷 교환 프로토콜입니다. |
| 13           | ARGUS         | ARGUS 프로토콜로, 분산 모니터링 시스템에 사용됩니다. |
| 14           | EMCON         | EMCON 프로토콜로, 통신 제어에 사용됩니다. |
| 15           | XNET          | 크로스 네트 디버거 프로토콜입니다. |
| 16           | CHAOS         | CHAOS 프로토콜로, MIT에서 개발한 네트워킹 프로토콜입니다. |
| 17           | UDP           | 사용자 데이터그램 프로토콜로, 비연결형 데이터 전송을 제공합니다. |
| 18           | MUX           | 멀티플렉싱 프로토콜로, 여러 신호를 하나의 신호로 결합합니다. |
| 19           | DCN-MEAS      | DCN 측정 서브시스템 프로토콜입니다. |
| 20           | HMP           | 호스트 모니터링 프로토콜로, 호스트 상태 모니터링에 사용됩니다. |
| 21           | PRM           | 패킷 라디오 측정 프로토콜입니다. |
| 22           | XNS-IDP       | Xerox 네트워크 시스템의 인터넷 데이터그램 프로토콜입니다. |
| 23           | TRUNK-1       | 트렁크-1 프로토콜입니다. |
| 24           | TRUNK-2       | 트렁크-2 프로토콜입니다. |
| 25           | LEAF-1        | 리프-1 프로토콜입니다. |
| 26           | LEAF-2        | 리프-2 프로토콜입니다. |
| 27           | RDP           | 신뢰할 수 있는 데이터그램 프로토콜로, 안정적인 데이터 전송을 제공합니다. |
| 28           | IRTP          | 인터넷 신뢰할 수 있는 트랜잭션 프로토콜입니다. |
| 29           | ISO-TP4       | ISO 전송 프로토콜 클래스 4입니다. |
| 30           | NETBLT        | 대용량 데이터 전송 프로토콜입니다. |
| 31           | MFE-NSP       | MFE 네트워크 서비스 프로토콜입니다. |
| 32           | MERIT-INP     | MERIT 노드 간 프로토콜입니다. |
| 33           | DCCP          | 데이터그램 혼잡 제어 프로토콜로, 혼잡 제어를 지원합니다. |
| 34           | 3PC           | 서드 파티 연결 프로토콜입니다. |
| 35           | IDPR          | 도메인 간 정책 라우팅 프로토콜입니다. |
| 36           | XTP           | XTP 프로토콜로, 고속 전송을 지원합니다. |
| 37           | DDP           | 데이터그램 전달 프로토콜로, 로컬 네트워킹에 사용됩니다. |
| 38           | IDPR-CMTP     | IDPR 제어 메시지 전송 프로토콜입니다. |
| 39           | TP++          | TP++ 전송 프로토콜입니다. |
| 40           | IL            | IL 전송 프로토콜로, 벨 연구소에서 개발한 프로토콜입니다. |
| 41           | IPv6          | IPv6 패킷 캡슐화를 위한 프로토콜입니다. |
| 42           | SDRP          | 소스 수요 라우팅 프로토콜입니다. |
| 43           | IPv6-Route    | IPv6 라우팅 헤더로, 패킷의 라우팅 정보를 포함합니다. |
| 44           | IPv6-Frag     | IPv6 단편화 헤더로, 패킷 분할에 사용됩니다. |
| 45           | IDRP          | 도메인 간 라우팅 프로토콜입니다. |
| 46           | RSVP          | 리소스 예약 프로토콜로, QoS를 지원합니다. |
| 47           | GRE           | 일반 라우팅 캡슐화 프로토콜로, 터널링에 사용됩니다. |
| 48           | MHRP          | 모바일 호스트 라우팅 프로토콜입니다. |
| 49           | BNA           | BNA 프로토콜입니다. |
| 50           | ESP           | IPsec의 캡슐화 보안 페이로드로, 데이터 암호화를 제공합니다. |
| 51           | AH            | IPsec의 인증 헤더로, 데이터 무결성을 제공합니다. |
| 52           | I-NLSP        | NLSP의 인터네트워크 프로토콜입니다. |
| 53           | SWIPE         | IP 암호화 프로토콜입니다. |
| 54           | NARP          | NBMA 주소 결정 프로토콜입니다. |
| 55           | MOBILE        | IP 모바일 호스트 프로토콜입니다. |
| 56           | TLSP          | 전송 계층 보안 프로토콜입니다.
| 57           | SKIP            | 인터넷 프로토콜을 위한 간단한 키 관리 프로토콜 |
| 58           | IPv6-ICMP       | IPv6용 ICMP 프로토콜, 오류 보고 및 네트워크 진단 수행 |
| 59           | IPv6-NoNxt      | IPv6에서 다음 헤더가 없음을 나타내는 헤더 |
| 60           | IPv6-Opts       | IPv6의 확장 헤더 중 하나로, 패킷 옵션 정보를 포함 |
| 61           | 내부 호스트 프로토콜 | 내부 네트워크에서 사용되는 예약된 프로토콜 |
| 62           | CFTP            | 실험적인 파일 전송 프로토콜 |
| 63           | 로컬 네트워크 전용 | 로컬 네트워크 전용으로 예약된 프로토콜 |
| 64           | SAT-EXPAK       | 위성 네트워크에서 사용되는 프로토콜 |
| 65           | KRYPTOLAN       | 암호화된 데이터 통신을 위한 네트워크 프로토콜 |
| 66           | RVD             | MIT 원격 가상 디스크 프로토콜 |
| 67           | IPPC            | 인터넷 다중 패킷 전송 프로토콜 |
| 68           | 분산 파일 시스템 전용 | 분산 파일 시스템 용도로 예약된 프로토콜 |
| 69           | SAT-MON         | 위성 네트워크 모니터링 프로토콜 |
| 70           | VISA            | VISA 프로토콜 |
| 71           | IPCU            | 인터넷 패킷 코어 유틸리티 |
| 72           | CPNX            | 컴퓨터 프로토콜 네트워크 실행 프로토콜 |
| 73           | CPHB            | 컴퓨터 프로토콜 하트비트 프로토콜 |
| 74           | WSN             | Wang Span 네트워크 프로토콜 |
| 75           | PVP             | 패킷 비디오 프로토콜 |
| 76           | BR-SAT-MON      | 백룸 위성 네트워크 모니터링 프로토콜 |
| 77           | SUN-ND          | Sun Microsystems의 네트워크 디스커버리 프로토콜 |
| 78           | WB-MON          | 광대역 네트워크 모니터링 프로토콜 |
| 79           | WB-EXPAK        | 광대역 확장 패킷 프로토콜 |
| 80           | ISO-IP          | ISO 표준 인터넷 프로토콜 |
| 81           | VMTP            | 다목적 메시지 트랜잭션 프로토콜 |
| 82           | SECURE-VMTP     | 보안이 강화된 VMTP 프로토콜 |
| 83           | VINES           | VINES 네트워크 프로토콜 |
| 84           | TTP             | 트랜잭션 전송 프로토콜 (사용 중지됨) |
| 85           | NSFNET-IGP      | NSFNET 내부 게이트웨이 프로토콜 |
| 86           | DGP             | 이기종 게이트웨이 프로토콜 |
| 87           | TCF             | TCF 프로토콜 |
| 88           | EIGRP           | 향상된 내부 게이트웨이 라우팅 프로토콜 |
| 89           | OSPF            | 개방형 최단 경로 우선 라우팅 프로토콜 |
| 90           | Sprite-RPC      | Sprite 운영체제의 원격 프로시저 호출 프로토콜 |
| 91           | LARP            | Locus 주소 결정 프로토콜 |
| 92           | MTP             | 멀티캐스트 전송 프로토콜 |
| 93           | AX.25           | 아마추어 무선 네트워크용 데이터 링크 프로토콜 |
| 94           | IPIP            | IP 패킷을 다른 IP 패킷 내에 캡슐화하는 프로토콜 |
| 95           | MICP            | 모바일 인터넷워킹 제어 프로토콜 |
| 96           | SCC-SP          | 세마포어 통신 보안 프로토콜 |
| 97           | ETHERIP         | 이더넷을 IP 내에서 캡슐화하는 프로토콜 |
| 98           | ENCAP           | 일반적인 캡슐화 프로토콜 |
| 99           | 개인 암호화 스킴 전용 | 특정 개인 암호화 시스템 전용 프로토콜 |
| 100          | GMTP            | 일반 메시지 전송 프로토콜 |
| 101          | IFMP            | Ipsilon 흐름 관리 프로토콜 |
| 102          | PNNI            | PNNI 기반 라우팅 프로토콜 |
| 103          | PIM             | 독립적인 멀티캐스트 라우팅 프로토콜 |
| 104          | ARIS            | ARIS 프로토콜 |
| 105          | SCPS            | 우주 통신 프로토콜 표준 |
| 106          | QNX             | QNX 운영체제 네트워크 프로토콜 |
| 107          | A/N             | 능동 네트워크 프로토콜 |
| 108          | IPComp          | IP 패킷 압축 프로토콜 |
| 109          | SNP             | Sitara 네트워크 프로토콜 |
| 110          | Compaq-Peer     | Compaq 피어 프로토콜 |
| 111          | IPX-in-IP       | IPX 패킷을 IP로 캡슐화하는 프로토콜 |
| 112          | VRRP            | 가상 라우터 이중화 프로토콜 |
| 113          | PGM             | 신뢰성 있는 멀티캐스트 전송 프로토콜 |
| 114          | 0-hop 프로토콜 전용 | 홉 수가 없는 프로토콜 전용 예약 값 |
| 115          | L2TP            | 계층 2 터널링 프로토콜 |
| 116          | DDX             | D-II 데이터 교환 프로토콜 |
| 117          | IATP            | 대화형 에이전트 전송 프로토콜 |
| 118          | STP             | 일정 전송 프로토콜 |
| 119          | SRP             | SpectraLink 라디오 프로토콜 |
| 120          | UTI             | UTI 프로토콜 |
| 121          | SMP             | 단순 메시지 프로토콜 |
| 122          | SM              | 단순 멀티캐스트 프로토콜 |
| 123          | PTP             | 성능 투명성 프로토콜 |
| 124          | IS-IS over IPv4 | IS-IS 라우팅 프로토콜을 IPv4에서 실행하는 프로토콜 |
| 125          | FIRE            | 유연한 자율 시스템 라우팅 환경 |
| 126          | CRTP            | 전투 라디오 전송 프로토콜 |
| 127          | CRUDP           | 전투 라디오 UDP 프로토콜 |
| 128~254      | 미배정          | 현재 사용되지 않는 예약된 프로토콜 번호 |
| 255          | 예약됨          | 향후 사용을 위해 예약된 값 |
 
