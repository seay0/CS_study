## DHCP(Dynamic Host Configuration Protocol)

---

DHCP(Dynamic Host Configuration Protocol)는 네트워크에 연결된 장치들에게 자동으로 IP 주소와 기타 관련 설정을 제공하는 프로토콜입니다.
이는 네트워크 관리자가 각 장치에 수동으로 IP 주소를 할당하고 설정할 필요를 없애 주어 네트워크 설정과 관리를 훨씬 간편하게 합니다.
DHCP는 IP 주소를 효율적으로 관리하고, IP 주소 충돌을 방지하고, 네트워크 구성 요소를 자동으로 구성하는데 중요한 역할을 합니다.

### DHCP 작동 과정

1. Discover: DHCP 클라이언트(즉, IP 주소를 필요로 하는 장치)는 네트워크에 DHCP 서버가 있는지를 찾기 위해 'DHCP Discover' 메시지를 브로드캐스트합니다.
2. Offer: DHCP 서버는 자신이 서비스를 제공할 수 있다는 메시지인 'DHCP Offer'를 클라이언트에게 보냅니다. 이 메시지에는 클라이언트에 할당할 수 있는 IP 주소가 포함되어 있습니다.
3. Request: 클라이언트는 DHCP 서버에게 'DHCP Request' 메시지를 보내어 제안된 IP 주소를 요청합니다.
4. Acknowledgement: 마지막으로, DHCP 서버는 'DHCP Acknowledgement' 메시지를 클라이언트에 보내어 IP 주소를 확정하고, 이 IP 주소를 사용할 수 있음을 알립니다.
