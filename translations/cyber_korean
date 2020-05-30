#                                       cyber:   위대한 웹에 대한 지식 컴퓨팅



![img](https://github.com/serejandmyself/cyber/raw/master/images/graph.png)

## 추상

합의 컴퓨터는 구글, 아마존 이나 페이스 북과 같은 어떤 의견 블랙 박스 중개인없이 입증 관련 답변의 컴퓨팅을 할 수 있습니다. IPFS와 같은 상태 비수기, 콘텐츠 주소 지정 가능한 피어 투 피어 통신 네트워크 및 이더리움과 같은 상태 관리 합의 컴퓨터는 유사한 답변을 얻는 데 필요한 솔루션의 일부만 제공할 수 있습니다. 그러나 위에서 언급한 구현과 관련된 3개 이상의 문제가 있습니다. (A) 관련성의 주관적인 특성. (B) 대규모 지식 그래프에 대한 합의 컴퓨터의 확장에 어려움. (C) 이러한 지식 그래프 사이에 품질의 부족. 그들은 다양한 표면 공격하는 경향이있다, 이러한 sybil 공격, 상호 작용 에이전트의 이기적인 행동. 이 문서에서는 IPFS 개체 간의 관련성에 대한 입증 가능한 합의 컴퓨팅 프로토콜을 정의하며, 이는 합의에 따라 GPU를 사용하여 계산되는 사이버~랭크의 Tendermint 합의를 기반으로 합니다. 지분 증명 합의는 초기 배포에 도움이되지 않기 때문에, 우리는 생태학적이고 효율적인 유통 게임의 디자인을 간략하게 설명합니다. 우리는 프로토콜의 최소한의 아키텍처가 도메인 별 지식 합의 컴퓨터의 네트워크의 형성에 중요하다고 생각합니다. 우리의 작업의 결과로, 이전에 존재하지 않았던 일부 응용 프로그램이 등장할 것입니다. 우리는 가능한 기능과 잠재적 인 응용 프로그램에 대한 비전으로이 문서를 확장합니다.

## 위대한 웹

TCP/IP, DNS, URL 및 HTTP/S와 같은 인터넷의 원래 프로토콜은 웹을 현재 위치하는 오래된 지점으로 가져왔습니다. 이러한 프로토콜이 웹의 초기 개발을 위해 생성한 모든 이점을 고려할 때, 이러한 프로토콜은 이러한 프로토콜과 함께 테이블에 상당한 장애물을 가져왔습니다. 글로벌성, 웹의 중요한 속성인 것은 처음부터 실제 위협을 받고있다. 유비쿼터스 정부의 개입으로 인해 네트워크 자체가 계속 증가하는 동안 연결 속도가 저하됩니다. 후자는 인권에 대한 실존적 위협으로 개인 정보 보호 문제를 야기한다.

처음에 분명하지 않은 하나의 속성은 인터넷의 일상적인 사용과 함께 중요해진다 : 영구 링크를 교환 할 수있는 능력, 따라서, 그들은 [시간이 경과 한 후 휴식하지 않습니다](https://ipfs.io/ipfs/QmNhaUrhM7KcWzFYdBeyskoNyihrpHvUEBQnaddwPZigcN). ISP는 한 번에 하나씩 아키텍처에 의존하여 정부가 패킷을 효과적으로 검열할 수 있도록 합니다. 이것은 우리 아이들의 미래에 대해 우려하는 모든 엔지니어를위한 전통적인 웹 스택의 마지막 하락입니다.

ISP는 한 번에 하나씩 아키텍처에 의존하여 정부가 패킷을 효과적으로 검열할 수 있도록 합니다. 이것은 우리 아이들의 미래에 대해 우려하는 모든 엔지니어를위한 전통적인 웹 스택의 마지막 하락입니다.

의 출현 [새로운 웹 스택](https://ipfs.io/ipfs/Qmf2rKkDPSsvdudwSmdDPbZuYae8XRV26c1wAFCCvg8Dhw) 우수한 인터넷을 위한 기회를 창출합니다. 커뮤니티는 이를 web3이라고 부릅니다. 우리는 그것을 위대한 웹이라고 부릅니다. 우리는 다양한 유형의 저수준 통신이 불변이어야 하며 수십 년 동안 변경할 수 없는 콘텐츠 링크와 같은 변경해서는 안 된다고 생각합니다. 그들은 기존의 프로토콜 스택의 문제를 제거하는 데 매우 유망한 것처럼 보입니다. 그들은 더 큰 속도를 추가하고 새로운 웹에 더 접근 가능한 연결을 제공합니다. 그러나 독특한 무언가를 제공하는 개념으로 발생함에 따라 새로운 문제가 발생합니다. 이러한 관심사 중 하나는 범용 검색입니다. 기존의 범용 검색 엔진은 모든 사람이 신뢰해야 하는 제한적이고 중앙 집중식 데이터베이스입니다. 이러한 검색 엔진은 주로 TCP/IP, DNS, URL 및 HTTP/S를 기반으로 클라이언트-서버 아키텍처를 위해 설계되었습니다. Great Web은 새로운 기술을 기반으로 하고 이러한 목적을 위해 특별히 설계된 검색 엔진에 도전과 기회를 제공합니다. 놀랍게도, 허가없는 블록 체인 아키텍처는 이전 건축가가 접근 할 수없는 방식으로 범용 검색 엔진을 구축 할 수 있습니다.es.

## 적대적인 예의 문제

[검색 엔진의 현재 아키텍처](https://ipfs.io/ipfs/QmeS4LjoL1iMNRGuyYSx78RAtubTT2bioSGnsvoaupcHR6) 는 일부 엔터티가 모든 똥을 처리하는 시스템입니다. 이 접근 방식은 뛰어난 Google 과학자들조차도 아직 해결되지 않은 하나의 도전과 뚜렷한 문제로 고통받고 있습니다. [적대적인 예 문제](https://ipfs.io/ipfs/QmNrAFz34SLqkzhSg4wAYYJeokfJU5hBEpkT4hPRi226y9). Google이 인정하는 문제는 특정 샘플이 적대적인지 여부를 알고리즘적으로 추론하기가 다소 어렵다는 것입니다. 이것은 그 자체로 교육 기술이 얼마나 멋진에 사려 깊다. 암호화 폐 경제적 접근 방식은 게임의 수혜자를 바꿀 수 있습니다. 따라서 이 접근 방식은 가능한 sybil 공격 벡터를 효과적으로 제거합니다. 단일 엔터티에 의한 하드 코드 모델 크롤링 및 의미 추출에 대한 필요성을 제거합니다. 대신, 그것은 전 세계에이 힘을 제공합니다. 학습 sybil 저항, 에이전트 생성 모델, 아마 더 많은 예측 결과의 크기의 순서로 이어질 것입니다.

## 사이버 프로토콜

핵심 프로토콜은 매우 최소하며 다음 단계로 표현할 수 있습니다.

1. 정의된 분포를 기반으로 사이버 프로토콜의 기원계산
2. 의 상태를 정의합니다. [지식 그래프](https://github.com/serejandmyself/cyber/blob/master/cyber.md#knowledge-graph)
3. 다음을 사용하여 트랜잭션을 수집합니다. [합의 컴퓨터](https://github.com/serejandmyself/cyber/blob/master/cyber.md#the-notion-of-a-consensus-computer)
4. 서명의 유효성 확인
5. 확인 을 통해 [대역폭 제한](https://github.com/serejandmyself/cyber/blob/master/cyber.md#relevance-machine)
6. CID의 유효성 확인
7. 서명, 대역폭 제한 및 CID가 모두 유효한 경우 [cyberlinks](https://github.com/serejandmyself/cyber/blob/master/cyber.md#cyberlinks) 및 거래
8. 의 가치를 계산[cyber~순위](https://github.com/serejandmyself/cyber/blob/master/cyber.md#cyberrank) CID의 모든 라운드에 대해 지식 그래프  [지식 그래프](https://github.com/serejandmyself/cyber/blob/master/cyber.md#knowledge-graph)

이 문서의 나머지 부분에서는 제안된 프로토콜의 근거와 기술적 세부 사항에 대해 설명합니다.

## 지식 그래프

지식 그래프는 콘텐츠 주소 간의 지시링크에 대한 가중치 그래프로 표시됩니다. 일명, 콘텐츠 식별자, CID, IPFS 해시, 또는 단순히 - IPFS 링크. 이 문서에서는 위의 용어를 동의어로 사용합니다.

![img](https://github.com/serejandmyself/cyber/raw/master/images/knowledge-graph.png)

콘텐츠 주소는 기본적으로 web3 링크입니다. 불분명하고 가변성 인 사용 대신 :

```
https://github.com/cosmos/cosmos/blob/master/WHITEPAPER.md
```

우리는 객체 자체를 사용합니다.

```
Qme4z71Zea9xaXScUi6pbsuTKCCNFp5TAv8W5tjdfH7yuH
```

콘텐츠 주소를 사용하여 지식 그래프를 작성함으로써 [너무 많이 필요](https://steemit.com/web3/@hipster/an-idea-of-decentralized-search-for-web3-ce860d61defe5est) [IPFS](https://ipfs.io/ipfs/QmV9tSDx9UiPeWExXEeH6aoDvmihvx6jD5eLb4jbTaKGps) - [처럼](https://ipfs.io/ipfs/QmXHGmfo4sjdHVW2MAxczAfs44RCpSeva2an4QvkzqYgfR) 검색 엔진에 대 한 원하는 p2p 프로토콜의 초강대국:

- 메쉬 네트워크 미래 지향적
- 행성 간 접근성
- 검열 저항
- 기술적 독립성

우리의 지식 그래프는 멋진 주인에 의해 생성됩니다. 마스터는 단일 트랜잭션, 사이버 링크의 도움으로 지식 그래프에 자신을 추가합니다. 따라서 공개된 공개 키의 콘텐츠 주소에 대한 개인 키가 있음을 증명합니다. 이러한 메커니즘을 사용하여 [합의 컴퓨터](https://github.com/serejandmyself/cyber/blob/master/cyber.md#the-notion-of-a-consensus-computer) 지식 그래프에서 주제와 개체 간의 가능한 차별화를 달성할 수 있습니다.

우리의 구현은 [go-cyber](https://github.com/cybercongress/go-cyber) 를 기반으로 합니다. [cosmos-SDK](https://github.com/cosmos/cosmos-sdk)정체성  [CIDv0/CIDv1](https://github.com/multiformats/cid#cidv0) 콘텐츠 주소.

마스터는 적용하여 지식 그래프를 형성합니다. [cyberlinks](https://github.com/serejandmyself/cyber/blob/master/cyber.md#cyberlinks).

## Cyberlinks

사이버 링크가 어떻게 작동하는지 이해하려면 URL 링크 (일명 하이퍼 링크)와 IPFS 링크 간의 차이점을 이해해야합니다. URL 링크는 IPFS 링크가 콘텐츠 자체를 가리키는지 여부에 관계없이 콘텐츠의 위치를 가리킵니다. 위치 링크와 콘텐츠 링크를 기반으로 하는 웹 아키텍처의 차이는 급진적이며 고유한 접근 방식이 필요합니다.

사이버 링크는 두 개의 콘텐츠 주소 또는 IPFS 링크를 의미적으로 연결하는 접근 방식입니다.

```
.md syntax: [QmdvsvrVqdkzx8HnowpXGLi88tXZDsoNrGhGvPvHBQB6sH](Qme4z71Zea9xaXScUi6pbsuTKCCNFp5TAv8W5tjdfH7yuH)    
.dura syntax: QmdvsvrVqdkzx8HnowpXGLi88tXZDsoNrGhGvPvHBQB6sH.Qme4z71Zea9xaXScUi6pbsuTKCCNFp5TAv8W5tjdfH7yuH
```

위의 사이버 링크는 [go-cyber](https://github.com/cybercongress/go-cyber) 동안 [cyberc0n](https://etherscan.io/token/0x61B81103e716B611Fff8aF5A5Dc8f37C628efb1E) 코스모스 백서를 참조하고 있습니다. 사이버 링크의 개념은 모든 p2p 네트워크에서 통신 형식의 간단한 의미 론에 관한 규칙입니다.

![img](https://github.com/serejandmyself/cyber/raw/master/images/cyberlink.png)

우리는 사이버 링크가 두 링크 사이의 링크를 나타내는 것을 볼 수 있습니다. 쉬운 쉬운!

사이버 링크는 우주의 예측 모델을 구축하기위한 간단하면서도 강력한 의미 체계 구조입니다. 즉, 하이퍼링크 대신 사이버 링크를 사용하면 범용 검색 엔진의 이전 아키텍처에 액세스할 수 없었던 초능력을 사용할 수 있습니다.

사이버 링크는 확장 될 수 있습니다., 즉 그들은 두 개 이상의 사이버 링크 는 하나의 마스터에서 subsist 경우 링크 체인을 형성할 수 있습니다., 첫 번째 사이버 링크의 두 번째 링크는 두 번째 사이버 링크의 첫 번째 링크와 동일:

![img](https://github.com/serejandmyself/cyber/raw/master/images/linkchain.png)

에이전트가 기본 IPFS 링크를 의미상으로 더 풍부한 것으로 확장하는 경우(예: [경막](https://github.com/cybercongress/cyb/blob/dev/docs/dura.md) 링크, 다음 특정 프로그램에 의해 실행 규칙에 대 한 합의에 도달 할 수 있습니다 보다 자연 스러운 접근.

그만큼 [go-cyber](https://github.com/cybercongress/go-cyber) 사이버 링크의 구현은 [.cyber](https://github.com/cybercongress/dot-cyber) 우리의 실험 웹3 브라우저의 응용 프로그램 [cyb](https://cyb.ai/), 또는 [cyber.page](http://cyber.page/).

마스터가 제출한 사이버 링크는 [RFC-6962 표준](https://ipfs.io/ipfs/QmZpJLmc3T2L1FLUxzvU3P8MBCPe15fEmUyVS7Bz8ZKMhG). 이를 통해 [관련성 증명](https://github.com/serejandmyself/cyber/blob/master/cyber.md#proof-of-relevance).

![img](https://github.com/serejandmyself/cyber/raw/master/images/graph-tree.png)

사이버 링크를 사용하여, 우리는 주제와 개체의 관련성을 계산할 수 있습니다. [지식 그래프](https://github.com/serejandmyself/cyber/blob/master/cyber.md#knowledge-graph). 그러나 우리는 [합의 컴퓨터](https://github.com/serejandmyself/cyber/blob/master/cyber.md#the-notion-of-a-consensus-computer).

## 합의 컴퓨터의 개념

합의 컴퓨터는 에이전트 간의 상호 작용에서 나오는 추상 컴퓨팅 컴퓨터입니다. 컨센서스 컴퓨터는 메모리와 계산이라는 기본적인 컴퓨팅 리소스의 용량을 가지고 있습니다. 에이전트와 상호 작용하려면 컴퓨터가 대역폭이 필요합니다. 이상적인 합의 컴퓨터는 다음과 같은 컴퓨터입니다.

```
the sum of all the computations and memory available to individuals`
`is equal to`
`the sum of all the verified computations and memory of the consensus computer
```

우리는 그것을 알고 :

```
verifications of computations < (computations + verifications of computations)
```

따라서, 우리는 이상적인 합의 컴퓨터를 달성 할 수 없을 것입니다. CAP 정리와 확장성 trilemma는 이 진술에 더 많은 증거를 추가합니다.

![img](https://github.com/serejandmyself/cyber/raw/master/images/consensus-computer.png)

그러나이 이론은 합의 컴퓨터에 대한 성능 지표로 작동 할 수 있습니다. 컨센서스 컴퓨터에 투자한 지 6년이 지난 지금, 우리는 [Tendermint](https://ipfs.io/ipfs/QmaMtD7xDgghqgjN62zWZ5TBGFiEjGQtuZBjJ9sMh816KJ) 합의는 우리의 작업에 필요한 차가움과 생산 준비 사이의 충분한 균형을 가지고있다. 따라서, 우리는 구현하기로 결정했습니다 [cyber](https://github.com/serejandmyself/cyber/blob/master/cyber.md#cyber-protocol) 코스모스 허브에 매우 가까운 설정을 가지고 Tendermint 합의를 사용하여 프로토콜. Tthe [go-cyber](https://github.com/cybercongress/go-cyber) 구현은 64바이트 문자열 공간에 대한 관련성의 64비트 Tendermint 합의 컴퓨터입니다. 이것은 적어도 1/146으로, 우리는 생산 동일한 계산을 확인 146 유효성 검사기를 가지고 있기 때문에, 지금까지 이상적이지 않다 [지식 그래프](https://github.com/serejandmyself/cyber/blob/master/cyber.md#knowledge-graph).

합의 컴퓨터의 계산, 저장 및 대역폭 공급을 쿼리에 대한 최대수요에 결합해야 합니다. 계산 및 스토리지( 기본 [관련성 기계](https://github.com/serejandmyself/cyber/blob/master/cyber.md#relevance-machine) 대역폭을 기반으로 쉽게 예측할 수 있습니다. 그러나 대역폭에는 제한 메커니즘이 필요합니다..

## 관련성 기계 

우리는 우리를 정의한 관련성을 기계 기계로 전환되는 상태의 [지식 그래프](https://github.com/serejandmyself/cyber/blob/master/cyber.md#knowledge-graph) 가르치고 자하는 대리인의 뜻에 따라 [지식 그래프](https://github.com/serejandmyself/cyber/blob/master/cyber.md#knowledge-graph). 의지는 모든 사람에 의해 예상됩니다 [cyberlinks](https://github.com/serejandmyself/cyber/blob/master/cyber.md#cyberlinks) 마스터가 수행합니다. 에이전트가 많을수록 [지식 그래프](https://github.com/serejandmyself/cyber/blob/master/cyber.md#knowledge-graph), 지식이 더 가치있게 됩니다. 이러한 예측을 기반으로 콘텐츠 주소 간의 관련성을 계산할 수 있습니다. 관련성 머신을 사용하면 쿼리 및 답변을 전달하여 검색 메커니즘을 간단하게 구성할 수 있습니다.

관련성 기계의 한 속성은 매우 중요합니다. 유도 추론 속성이 있거나 블랙 박스 원칙을 따라야합니다.

```
The machine should be able to interfere with predictions without any knowledge about the objects,`
`except for who, when and what was cyberlinked
```

우리가 가정하는 경우 [합의 컴퓨터](https://github.com/serejandmyself/cyber/blob/master/cyber.md#the-notion-of-a-consensus-computer) 연결된 개체에 대한 몇 가지 정보가 있어야 하며 이러한 모델의 복잡성은 예측할 수 없게 증가합니다. 따라서 메모리 및 계산을 위한 프로세싱 컴퓨터의 높은 요구 사항. 블랙박스 원칙을 따르는 관련성 머신을 다루는 콘텐츠 덕분에 데이터를 저장할 필요가 없습니다. 그러나, 여전히 효과적으로 그 위에 작동 할 수 있습니다. 내부의 의미의 공제는 [합의 컴퓨터](https://github.com/serejandmyself/cyber/blob/master/cyber.md#the-notion-of-a-consensus-computer) 비싸다. 따라서 이러한 디자인은 가정 실명에 따라 달라질 수 있습니다. 내부의 의미를 공제하는 대신 [합의 컴퓨터](https://github.com/serejandmyself/cyber/blob/master/cyber.md#the-notion-of-a-consensus-computer), 우리는 추출이 인센티브를 제공하는 시스템을 설계했습니다. 이는 마스터가 [CYB](https://github.com/serejandmyself/cyber/blob/master/cyber.md#cyb) 토큰은 관련성 기계가 순위를 계산할 수 있는 에 따라 자신의 의지를 표현할 수 있습니다.

스팸 방지 시스템의 중심에는 관련 기계의 진화적 성공에 기득권을 가진 사람들만 쓰기 작업을 실행할 수 있다는 가정이 있습니다. 유효 지분의 1%마다 [합의 컴퓨터](https://github.com/serejandmyself/cyber/blob/master/cyber.md#the-notion-of-a-consensus-computer) 가능한 네트워크 대역폭과 컴퓨팅 기능의 1%를 사용할 수 있습니다. 간단한 규칙은 에이전트의 남용을 방지합니다: 한 쌍의 콘텐츠 식별자는 한 번만 주소로 사이버 링크될 수 있습니다.

![img](https://github.com/serejandmyself/cyber/raw/master/images/algo1.png)

계좌의 유효 지분 (활성 지분 + 채권)을 변경하는 방법은 다이렉트 토큰 이체와 본딩 운영의 두 가지뿐입니다.

[Cyber](https://github.com/serejandmyself/cyber/blob/master/cyber.md#cyber-protocol) 매우 간단한 대역폭 모델을 사용합니다. 이 모델의 주요 목표는 일일 네트워크 증가를 지정된 상수로 줄이는 것입니다. 이는 인프라에 대한 향후 투자를 예측할 수 있는 영웅(유효성 검사기)을 수용하기 위한 것입니다. 따라서 여기에서는 '와트' 또는 'W'를 소개합니다. 각 메시지 유형에는 할당된 W 비용이 있습니다. 상수 '바람직한 대역폭'은 W 값에 의해 소비되는 바람직한 '복구 창'을 결정합니다. 복구 기간은 마스터가 대역폭을 0에서 최대 대역폭으로 복구할 수 있는 속도입니다. 마스터는 다음 공식에 의해 결정되는 자신의 유효 지분에 최대 W 비례를 가합니다:

```
AgentMaxW = EffectiveStake * DesirableBandwidth
```

'adjustPricePeriodPeriod' 기간은 최신 블록의 '복구 기간' 기간 동안 W가 소비된 금액을 요약합니다. '소비 대역폭' / '바람직한 대역폭' 비율을 소수 예비 비라고 합니다. 네트워크 사용량이 적으면 소수 준비 비율이 메시지 비용을 조정하여 베팅 금액이 낮은 마스터가 더 많은 트랜잭션을 커밋할 수 있도록 합니다. 리소스에 대한 수요가 증가하면 소수 준비 비율이 1로 되므로 메시지 비용이 증가하고 장기 기간 동안 최종 tx 수를 제한합니다(W 복구는 <다음 W 지출이 됩니다). 아무도 소유한 대역폭을 모두 사용하지 않아서 가격 재계산 목표 기간 내에 최대 100배의 분수 보유를 안전하게 사용할 수 있습니다. 이러한 메커니즘은 만들기에 대한 할인을 제공합니다. [cyberlinking](https://github.com/serejandmyself/cyber/blob/master/cyber.md#cyberlinks), 따라서, 효과적으로 그것에 대한 수요를 극대화. 제안된 설계에는 관련성이 가치 있게 되기 위해 전체 대역폭에 대한 수요가 필요하다는 것을 알 수 있습니다.

인간의 지능은 시간이 지남에 따라 아무도 관련이 없고 중요한 기억이 잊혀지는 방식으로 조직됩니다. 관련성 컴퓨터에도 동일하게 적용할 수 있습니다. 관련성 기계는 [적극적인 가지 치기 전략](https://ipfs.io/ipfs/QmP81EcuNDZHQutvdcDjbQEqiTYUzU315aYaTyrVj6gtJb), 예를 들어, 형성의 역사의 가지 치기 [지식 그래프](https://github.com/serejandmyself/cyber/blob/master/cyber.md#knowledge-graph), 관련성이 떨어지는 링크를 잊어버리는 경우.

그 결과, 구현된 사이버 노믹스는 [CYB](https://github.com/serejandmyself/cyber/blob/master/cyber.md#cyb) 토큰은 의지 표현 및 스팸 방지 메커니즘뿐만 아니라 영웅의 처리 능력과 처리에 대한 시장 수요를 조정할 수있는 경제 규제 도구의 역할을합니다. 관련성 머신의 사이버 사이버 구현은 사이버 직급이라는 매우 간단한 메커니즘을 기반으로합니다.

## cyber~순위

를 사용한 순위 [합의 컴퓨터](https://github.com/serejandmyself/cyber/blob/master/cyber.md#the-notion-of-a-consensus-computer) 합의 된 컴퓨터는 심각한 리소스 제약 조건을 가지고 있기 때문에 어려울 수 있습니다. 첫째, 우리는 왜 계산하고 체인에 순위를 저장하고 같은 방식으로 수행하지 해야합니까? [Colony](https://ipfs.io/ipfs/QmZo7eY5UdJYotf3Z9GNVBGLjkCnE1j2fMdW2PgGCmvGPj) or [Truebit](https://ipfs.io/ipfs/QmTrxXp2xhB2zWGxhNoLgsztevqKLwpy5HwKjLjzFa7rnD)?

랭크가 내부에서 계산된 경우 [합의 컴퓨터](https://github.com/serejandmyself/cyber/blob/master/cyber.md#the-notion-of-a-consensus-computer) 하나는 해당 순위의 콘텐츠 배포에 쉽게 액세스 할 수 있으며, [입증 가능한 응용 프로그램 빌드](https://github.com/serejandmyself/cyber/blob/master/cyber.md#apps) 그 순위의 상단에. 따라서, 우리는 더 우주 건축을 따르기로 결정했습니다. 다음 섹션에서는 [관련성 증명](https://github.com/serejandmyself/cyber/blob/master/cyber.md#proof-of-relevance) 도메인별 네트워크를 통해 확장할 수 있습니다. [관련성 기계](https://github.com/serejandmyself/cyber/blob/master/cyber.md#relevance-machine). IBC 프로토콜 덕분에 동시에 작업할 수 있습니다..

결국, [관련성 기계](https://github.com/serejandmyself/cyber/blob/master/cyber.md#relevance-machine) (1) 결정적 알고리즘을 구해야 하며, 이는 지속적으로 인더해하는 네트워크에서 순위를 계산할 수 있게 해주며, 그 자체가 [Google](https://google.com/). 또한 완벽한 알고리즘(2)에는 선형 메모리와 계산 복잡성이 있어야 합니다. 가장 중요한 것은( 3) 관련 존재에 대한 가장 높은 예측 능력이 있어야 한다는 것입니다. [cyberlinks](https://github.com/serejandmyself/cyber/blob/master/cyber.md#cyberlinks).

후[철저한 조사 ](https://ipfs.io/ipfs/QmTJPJ55ePgR2MS1HoAtyqS1mteVLXUjAS4H8W97EEopxC), 우리는 은총알을 얻는 것이 불가능하다는 것을 발견했습니다. 따라서, 우리는 네트워크를 부트 스트랩 할 수있는 보다 기본적인 방탄 방법을 찾기로 결정했습니다 : [순위](http://ipfs.io/ipfs/QmbuE2Pfcsiji1g9kzmmsCnptqPEn3BuN3BhnZHrPVsiVw) 래리와 세르게이는 이전 네트워크를 부트스트랩하는 데 사용했습니다. 원래 PageRank의 주요 문제는 sybil 공격에 저항하지 않았다는 것입니다. 그러나 토큰 가중 대역폭 모델에 의해 제한되는 토큰 가중 PageRank는 순진한 PageRank의 주요 문제를 상속하지 않습니다. 당분간, 우리는 더 적합한 무언가가 나타날 때까지, 그것을 사이버 ~ 랭크라고 합니다. 다음 알고리즘은 제네시스의 구현에 적용됩니다.

![img](https://github.com/serejandmyself/cyber/raw/master/images/algo2.png)

우리는 순위 메커니즘은 항상 빨간색 청어 남아 있음을 이해합니다. 이것이 우리가 주어진 시간에 가장 적합한 메커니즘을 정의할 수 있는 온체인 거버넌스 도구에 의존할 것으로 예상되는 이유입니다. 우리는 네트워크가 단순히 주관적인 의견에 기초한 것이 아니라 도메인별 '하드 스푼'을 통해 경제적인 a/b 테스트에 따라 하나의 알고리즘에서 다른 알고리즘으로 전환할 수 있다고 가정합니다. [관련성 기계](https://github.com/serejandmyself/cyber/blob/master/cyber.md#relevance-machine).

cyber~Rank는 가장 중요한 두 가지 설계 결정을 보호합니다: (1) 에이전트의 현재 의도를 설명하며, (2) 순위 인플레이션을 장려합니다. [cyberlinks](https://github.com/serejandmyself/cyber/blob/master/cyber.md#cyberlinks). 첫 번째 속성은 사이버 ~ 순위와 함께 게임 할 수 없습니다 보장합니다. 에이전트가 [CYB](https://github.com/serejandmyself/cyber/blob/master/cyber.md#cyb) 토큰은 계정에서 나오며, [관련성 기계](https://github.com/serejandmyself/cyber/blob/master/cyber.md#relevance-machine) will adjust all the [cyberlinks](https://github.com/serejandmyself/cyber/blob/master/cyber.md#cyberlinks) 에이전트의 현재 의도에 따라 이 계정과 관련이 있습니다. 에이전트가 전송하는 경우 그 반대의 경우도 마찬가지입니다. [CYB](https://github.com/serejandmyself/cyber/blob/master/cyber.md#cyb) 토큰을 자신의 계정으로, 모든 [cyberlinks](https://github.com/serejandmyself/cyber/blob/master/cyber.md#cyberlinks) 이 계정에서 제출하면 즉시 더 많은 관련성을 얻을 수 있습니다. 두 번째 속성은 과거에 시멘트얻을하지 않기 위해 필수적이다. 새로운 [cyberlinks](https://github.com/serejandmyself/cyber/blob/master/cyber.md#cyberlinks) 지속적으로 추가되며, 기존 링크의 순위를 비례적으로 희석시됩니다. 이 속성은 새롭고 더 나은 콘텐츠가 최근에 제출되었기 때문에 순위가 낮은 상황을 방지합니다. 우리는 이러한 결정이 최근 추가 된 콘텐츠에 대한 추론 품질을 가능하게 할 것으로 기대합니다. [지식 그래프](https://github.com/serejandmyself/cyber/blob/master/cyber.md#knowledge-graph).

우리는 투표 구매의 문제를 논의하고 싶습니다. 투표 를 발생으로 구매하는 것은 그렇게 나쁘지 않습니다. 투표 구매의 딜레마는 투표가 해당 시스템 인플레이션의 할당에 영향을 미치는 시스템 내에서 나타납니다. 예를 들어 [Steem](http://ipfs.io/ipfs/QmepU77tqMAHHuiSASUvUnu8f8ENuPF2Kfs97WjLn8vAS3) 또는 피아트 상태 기반 시스템. 투표 구매는 가치를 추가할 필요 없이 제로섬 게임을 사용하는 적에게 쉽게 수익을 낼 수 있습니다. 분산 된 검색에 대한 우리의 원래 아이디어는이 접근 방식을 기반으로했습니다. 그러나, 우리는 그 아이디어를 거부했다, 의 형성의 인센티브를 제거 [지식 그래프](https://github.com/serejandmyself/cyber/blob/master/cyber.md#knowledge-graph) 합의 수준으로. 모든 참가자가 예측 모델에 영향을 미치기 위해 시스템에 어떤 가치를 가져와야하는 환경에서 투표 구매는 NP 하드 문제가됩니다. 따라서 시스템에 유익합니다.

의 현재 구현 [관련 기계](https://github.com/serejandmyself/cyber/blob/master/cyber.md#relevance-machine) GPU를 활용하여 순위를 계산합니다. 기계는 64바이트 CID 공간에서 주어진 검색 요청에 대한 관련 결과에 응답하고 제공할 수 있습니다. 그러나 도메인별 네트워크를 구축하는 것만으로는 충분하지 않습니다. [관련 기계](https://github.com/serejandmyself/cyber/blob/master/cyber.md#relevance-machine). [합의 컴퓨터](https://github.com/serejandmyself/cyber/blob/master/cyber.md#the-notion-of-a-consensus-computer) 서로 의관련성을 입증할 수 있는 능력이 있어야 합니다.

## 관련성 증명

검색과 관련하여 악의적 인 행동과 같은 것은 존재하지 않는다는 가정하에 네트워크를 설계했습니다. 답을 찾을 의도로 악의적 인 행동을 찾을 수 없기 때문에 가정 할 수 있습니다. 이 접근 방식은 모든 표면 공격을 크게 줄입니다.

```
Ranks are computed based on the fact that something was searched, thus linked, and as a result - affected the predictive model
```

관찰 자체가 행동에 영향을 미치는 양자 역학에서 좋은 비유가 관찰됩니다. 그렇기 때문에 우리는 부정적인 투표와 같은 것에 대한 요구 사항이 없습니다. 이렇게 하면 프로토콜에서 주관성을 제거하고 관련성 증명을 정의할 수 있습니다.

![img](https://github.com/serejandmyself/cyber/raw/master/images/graph-tree.png)

각 새 CID는 시퀀스 번호를 받습니다. 번호 매기기는 0으로 시작합니다. 그런 다음 각 새 CID에 대해 하나씩 증가합니다. 따라서 인덱스가 CID 시퀀스 번호인 1차원 배열에 순위를 저장할 수 있습니다. 머클 트리 계산은 [RFC-6962 표준](https://ipfs.io/ipfs/QmZpJLmc3T2L1FLUxzvU3P8MBCPe15fEmUyVS7Bz8ZKMhG). Merkle 나무를 사용하여 특정 콘텐츠 주소의 순위를 효과적으로 증명 할 수 있습니다. 관련성은 여전히 본질적으로 주관적이지만, 우리는 어떤 시점에서 특정 커뮤니티와 관련이 있다는 집단적 증거를 가지고 있습니다.

이 유형의 증거를 사용하여 두 가지 [IBC 호환](https://ipfs.io/ipfs/QmSGbrGAPZtR6Q1jHHe8mmS3bLBehKmfp9ZYvrg5ycaZuk) [합의 컴퓨터](https://github.com/serejandmyself/cyber/blob/master/cyber.md#the-notion-of-a-consensus-computer) 서로 관련성을 증명할 수 있습니다. 즉, 도메인별 [관련성 기계](https://github.com/serejandmyself/cyber/blob/master/cyber.md#relevance-machine) 번창할 수 있습니다.

공통의 관련성에서 [go-cyber](https://github.com/cybercongress/go-cyber) Merkle 트리는 매 라운드마다 계산되며 ABCI에 전념하는 루트 해시입니다.

## 속도

우리는 기존의 웹 응용 프로그램의 느낌을 사용자에게 제공하기 위해 즉각적인 확인 시간이 필요합니다. 이것은 경제적인 토폴로지와 확장성을 형성하는 강력한 아키텍처 요구 사항입니다. [cyber](https://github.com/serejandmyself/cyber/blob/master/cyber.md#cyber-protocol) 프로토콜. 제안된 블록체인 디자인은 [텐더민트 컨센서스](https://ipfs.io/ipfs/QmaMtD7xDgghqgjN62zWZ5TBGFiEjGQtuZBjJ9sMh816KJ) 146 개의 유효성 검사기가있는 알고리즘과 빠른 5 초 tx 최종 시간을 가있습니다. 평균 확인 시간은 1 초에 가까울 수 있으며 복잡한 블록 체인 상호 작용이 에이전트에게 거의 보이지 않게 될 수 있습니다.

우리는 하나의 특정한 것을 나타냅니다 [go-cyber](https://github.com/cybercongress/go-cyber) 속도의 맥락에서 속성 - 순위 계산. 합의의 일부이기 때문에 라운드 내의 트랜잭션 유효성 검사와 병렬로 발생합니다. 라운드는 이해 관계자가 정의한 합의 변수입니다. 시작 시 한 라운드는 20 블록으로 설정됩니다. 실질적으로, 이것은 네트워크가 100초마다 네트워크의 현재 루트 해시에 동의해야 함을 나타냅니다. [지식 그래프](https://github.com/serejandmyself/cyber/blob/master/cyber.md#knowledge-graph). This means that every [cyberlink](https://github.com/serejandmyself/cyber/blob/master/cyber.md#cyberlinks) 제출된 제출물의 일부가 됩니다. [지식 그래프](https://github.com/serejandmyself/cyber/blob/master/cyber.md#knowledge-graph) 50초 의 평균 기간 내에 랭크를 획득할 수 있습니다. 초기에 [Google](https://google.com/) 계급은 대략 매주 재계산되었습니다. 우리는 위대한 웹의 주인은 실시간으로 순위 변화를 관찰하는 것을 기쁘게 생각하지만,이 창이 충분하다는 가정하에 네트워크를 시작하기로 결정했습니다. 의 발전과 함께 [cyber](https://github.com/serejandmyself/cyber/blob/master/cyber.md#cyber-protocol) 프로토콜은 각 라운드의 속도가 감소합니다. 이것은 영웅 들 간의 경쟁 때문입니다. 우리는 이 함수 순서를 더 빠르게 만들기 위한 특정 메커니즘을 알고 있습니다.

- 합의 매개 변수의 최적화
- 순위 계산의 더 나은 병렬화
- a [더 나은 시계](https://ipfs.io/ipfs/QmbsKzizZVVVzPbZvg1qSsNMkwmA3MFufgXb3MFqbSnmPs) 합의에 앞서

## 확장성

우리는 우리가 같은 의 중요성에 아이디어를 확장 할 수 있도록 아키텍처가 필요합니다 [Google](https://google.com/). 우리가 가정하자, 그 노드 구현, 이는 기반 [코스모스-SDK](https://github.com/cosmos/cosmos-sdk) 초당 10k 트랜잭션을 처리할 수 있습니다. 즉, 매일 적어도 864만 명의 마스터가 100명의 마스터를 제출할 수 있습니다. [cyberlinks](https://github.com/serejandmyself/cyber/blob/master/cyber.md#cyberlinks) 검색 결과에 동시에 영향을 미칩니다. 이것은 야생에서 밖으로 모든 가정을 확인 하기에 충분 한, 하지만, 그것은 인터넷의 현재 규모에서 작동 하는 말을 충분 하지. 우리 팀에 의해 수행 된 예술 연구의 현재 상태를 감안할 때, 우리는 안전하게 우리가 필요로하는 크기로 특정 블록 체인을 확장 할 수 있도록, 존재에 합의 기술이 없다는 것을 명시 할 수 있습니다. 따라서 도메인별 개념을 소개합니다. [지식 그래프](https://github.com/serejandmyself/cyber/blob/master/cyber.md#knowledge-graph).

![img](https://github.com/serejandmyself/cyber/raw/master/images/network.png)

하나는 forking하여 자신의 도메인 별 검색 엔진을 시작할 수 있습니다. [go-cyber](https://github.com/cybercongress/go-cyber), textit{공용 지식}에 중점을 둔다. 또는 플러그를 꽂기만 하면 됩니다. [go-cyber](https://github.com/cybercongress/go-cyber) 기존 체인, 즉 코스모스 허브에 모듈로. 블록 체인 간 통신 프로토콜은 사이의 상태를 동기화하는 동시 메커니즘을 도입합니다. [관련성 기계](https://github.com/serejandmyself/cyber/blob/master/cyber.md#relevance-machine). 따라서 제안된 검색 아키텍처에서 도메인별 [관련성 기계](https://github.com/serejandmyself/cyber/blob/master/cyber.md#relevance-machine) 상식에서 배울 수 있을 것입니다. 도메인별에서 배울 수 있는 일반적인 지식과 마찬가지로 [관련성 기계](https://github.com/serejandmyself/cyber/blob/master/cyber.md#relevance-machine).

## 브라우저

우리는 제안 된 네트워크가 web3 브라우저로 어떻게 작동하는지 상상하고 싶었습니다. 우리의 실망에 우리는 [할 수 없습니다.](https://github.com/cybercongress/cyb/blob/master/docs/comparison.md) 웹3 브라우저를 찾아 제안된 접근 방식의 시원함을 보여줄 수 있습니다. 우리가 처음부터 웹3 브라우저를 개발하기로 결정한 이유입니다. [Cyb](https://cyb.ai/) 견본이 있는 당신의 친절한 로봇입니다 [.cyber](https://cyber.page/) 와 상호 작용하기 위한 응용 프로그램 [cyber](https://github.com/serejandmyself/cyber/blob/master/cyber.md#cyber-protocol) 프로토콜.

![img](https://github.com/serejandmyself/cyber/raw/master/images/cyb.jpg)

배달의 좋은 예로, 우리는 [cyber.page](https://cyber.page/). 그것은 영웅, 마스터 와 전도사 웹 2 게이트웨이를 통해 프로토콜과 상호 작용할 수 있습니다. 사이버 링크를 만들고, 콘텐츠를 IPFS에 직접 고정하고, 그레이트 웹을 검색하고, 사이버 거버넌스에 참여하는 등의 방식으로 콘텐츠를 생성합니다. 또한 심층 탐색기, 지갑 및 원장 장치와 같은 하드웨어 지갑을 포켓 할 수 있습니다.

현재 검색 스니펫은 못생겼습니다. 그러나, 우리는 그들이 쉽게 사용하여 확장 할 수 있다고 가정 [IPLD](https://github.com/ipld/specs) 콘텐츠 유형에 대해 결국, 그들은 의 경우보다 훨씬 더 매력적으로 될 수 있습니다. [Google](https://google.com/).

![img](https://github.com/serejandmyself/cyber/raw/master/images/architecture.png)

제안된 아키텍처를 구현하는 동안, 우리는 적어도 3가지 주요 이점을 실현했습니다. [Google](https://google.com/) 아마도 기존의 접근 방식으로는 제공 할 수 없을 것입니다.

- 검색 결과는 모든 p2p 네트워크에서 쉽게 전달 될 수있다 : 예를 들어 .cyber는 비디오를 재생할 수 있습니다
- 지불 버튼은 오른쪽에 포함 될 수있다
