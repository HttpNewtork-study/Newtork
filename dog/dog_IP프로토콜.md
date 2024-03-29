IP 프로토콜

---

ip프로토콜, 즉 인터넷 프로토콜은 인터넷에서 데이터를 전송하는 데 사용되는 규칙과 절차의 집합을 의미한다.

이 프로토콜은 네트워크를 통해 데이터 패킷을 보내고 받는 방법을 정의하며, 인터넷의 기본적인 프로토콜 중 하나다.

---

###### IP 프로토콜의 핵심 기능은 다음과 같다.

> 주소지정 ->
>
> > 각 장치에는 고유한 IP 주소가 할당된다.
> > 이 주소를 통해 데이터는 정확한 목적지로 전송될 수 있다.

> 라우팅 ->
>
> > IP프로토콜은 데이터 패킷이 출발지에서 목적지까지 어떻게 전달될건지를 결정한다. 이 과정에서 여러 네트워크 장비를 통과하게 된다.

> 패킷 분할과 재조립 ->
>
> > 큰 데이터는 여러 작은 패킷으로 나누어진다.
> > 이 패킷들은 목적지에서 다시 원래의 데이터로 재조립된다.

> 오류 처리와 진단 ->
>
> > IP 프로토콜은 전송 중에 발생할 수 있는 오류를 감지하고 네트워크 문제를 진단하는 데 도움을 준다.

---

#####Q. IP 프로토콜의 한계에 대해서

주소 공간의 한계
`IPv4는 약 43억 개의 고유한 주소만을 지원한다.`
`이는 인터넷의 초기 설계 시점에는 충분해 보였지만, 기기 수의 폭발적인 증가와`
`IoT의 등장으로 인해 매우 제한적이다.(주소 부족 문제)`

보안 문제
`IPv4는 기본적인 보안 기능을 제공하지 않는다.`
`이는 데이터 무결성, 기밀성, 인증 등을 보장할 수 없다는 것을 의미한다.`
`이러한 문제는 종종 추가적인 보안 프로토콜을 통해 해결되지만, 이는 복잡성을 증가시킨다.`

프레그먼테이션 문제
`IPv4는 데이터 패킷을 분할하여 전송할 수 있으나, 이 과정에서 발생하는`
`프래그먼테이션은 네트워크 지연과 성능 저하를 일으킬 수 있다.`
`또한, 패킷 재조립 과정은 네트워크 장비에 부담을 줄 수 있다.`

모바일 네트워킹의 제한
`IPv4는 모바일 네트워킹과 같이 동적으로 변하는 네트워크 환경을`
`효과적으로 지원하지 못한다. 이동성을 지원하기 위해서는 추가적인 메커니즘이 `
`필요하다.`

비연결성
`1. 비신뢰성 : IP프로토콜은 패킷이 목적지에 도착했는지, 올바른 순서로`
`도착했는지, 또는 손상되지 않았는지 확인하지 않는다. 이는 IP 프로토콜`
`자체가 신뢰할 수 있는 데이터 전송을 보장하지 않는다는것을 의미한다.`

`2. 오류 복구 미흡 : 패킷 손실이나 오류가 발생했을 때, IP 프로토콜은`
`이를 복구하거나 재전송하지 않는다. 이런 기능은 상위 계층 프로토콜,`
`예를 들어 TCP에서 제공된다.`

---

Q. 프레그먼테이션이란?
`네트워크에서 데이터 패킷을 전송하는 과정에서 발생할 수 있는 문제를 뜻한다.`
