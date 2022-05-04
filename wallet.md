# 메타마스크
메타마스크(Metamask)는 이더리움을 보유하고 송금 및 관리할 수 있는 암호화폐 지갑이다. 메타마스크는 구글 크롬 웹브라우저에서 플러그인 방식으로 사용하는 크롬 확장 프로그램이다. 메타마스크는 조셉 루빈(Jeseph Lubin)이 이끄는 미국의 컨센시스(ConsenSys) 회사가 개발하고 있다.

## 소개
메타마스크(MetaMask)란 이더리움(Ethereum) 개인지갑을 편리하고 안전하게 관리할 수 있는 구글 확장프로그램이다. 그래서 모바일에서는 사용이 불가능하고 PC 브라우저인 크롬으로만 사용이 가능하다.(현재는 모바일 앱도 활발히 쓰이고 있다.) 메타마스크를 이용하여 전체 이더리움 노드를 실행하지 않고도 브라우저에서 이더리움 디앱을 바로 실행 할 수 있으며, 이더리움 송금과 토큰을 확인하고 관리할 수 있다. 메타마스크에는 보안 ID 볼트가 포함되어 있어 서로 다른 사이트에서 사용자의 ID를 관리하고 블록체인 트랜잭션을 서명할 수 있는 사용자 인터페이스를 제공한다. 또한 메타마스크 추가 기능을 크롬(Chrome), 파이어폭스(Firefox), 오페라(Opera) 및 새 Brave 브라우저에 설치할 수 있다. 개발자라면 메타마스크로 개발을 시작할 수 있다. 메타마스크의 임무는 가능한 한 많은 사람들을 위해 이더리움을 사용하기 쉽게 만드는 것이다.
## 특징
### 입금 방법
1. 메타마스크(MetaMask) 확장 프로그램을 연다.
2. 창 상단의 계정 이름 위에 마우스를 올려 놓으면 "클립 보드에 복사"가 표시된다.
3. 주소를 복사하려면 계좌 이름을 클릭한다.
4. 이더리움(ETH) 또는 토큰을 발송할 신청서의 "수령인" 필드에 주소를 붙여 넣는다.
5. 거래를 제출하기 위해 필요한 다른 모든 단계를 완료한다.

### 계정
사용자의 자금을 보유하는 공공 및 개인 키페어이다. 자금은 실제 지갑이나 계좌가 아닌 블록체인에 보관되어있다. Reddit 계정의 사용자 이름(공용)과 암호(개인)가 있는 것처럼, 이더리움 계정도 마찬가지이다. 추가적인 보안을 위해 암호를 사용하여 사용자 이름과 암호 및 더 안전한 암호를 만들 수 있는 개인 키를 암호화할 수 있다.
### 퍼블릭 키
퍼블릭 키(public key)는 사용자가 계좌로 자금을 보낼 때 사용한다. 주소(address)라고도 한다. 프라이빗 키는 0x + 40 16진수 문자로 구성된 문자열로 이루어지며, 이더리움(Etherum)에서 주소는 0x로 시작한다. (예: 0x06A85356DCb5b307096726FB86A78c59D38e08ee). 암호에는 퍼블릿 키와 프라이빗 키가 있다. 프라이빗 키에서 퍼블릭 키를 추출할 수 있지만, 퍼블릿 키에서 프라이빗 키를 추출할 수는 없다. 이더리움(Etherum)에서 공용 키는 개인 키에서 파생되어 128 16진수이며, 파생 후 64자의 "SHA3"(Kecak-256) 해시를 가져와서 마지막 40자를 취하고 0x로 접두사를 하면 42자 주소를 알려준다.
### 프라이빗 키
프라이빗 키(private key)는 사용자가 계좌에서 자금을 보낼 때 사용한다. 64자의 16진수 문자열로 이루어지며, 주로 64개의 16진수 문자로 된 모든 문자열은 프라이빗 키이다.
### 하드웨어 지갑
하드웨어 지갑(hardware wallet)은 프라이빗 키를 보유하여 안전한지 확인하는 단일 목적의 장치이다. 전형적으로 24단어을 사용한다. 만약 사용자가 하드웨어 지갑을 잃어버렸다면, 사용자는 사용자가 적었던 단어를 통해 계좌와 펀드에 접근할 수 있다.
## 핵심 기능
**메타마스크의 핵심기능은 키 관리(key management)이다.**
- 프라이빗 키(private key)를 생성해준다.
- 생성된 프라이빗 키(private key)를 보관해두었다가 사용자가 필요할 때 꺼내쓸 수 있게 한다.
- 단순히 프라이빗 키(private key) 그대로를 보관해 두었다가 바로 꺼내쓰는 것은 위험하기 때문에 사용자에게 따로 패스워드를 설정할 수 있게해서 프라이빗 키(private key)를 꺼낼 때 패스워드를 물어보게 하여 보안에 신경썼다.

# Kaikas
**Kaikas는 Klaytn 블록체인 상의 자산을 보관하고 전송하는 탈중앙화된 지갑입니다.**

**탈중앙화 지갑**
블록체인은 오직 "개인키"만을 통해 계정의 소유권을 증명하고 전송을 수행합니다.
이 개인키는 Kaikas 설치 시 시드 구문의 형태로 "무작위로" 생성되어 사용자 컴퓨터에만 저장되며, 당사는 관련 정보를 일체 저장하지 않습니다. 따라서 만약 이 개인키를 분실하고 Kaikas가 초기화되는 경우 계정을 복구할 수 있는 방법이 전혀 없습니다.
기존의 은행이나 거래소는 사용자의 "계정"이 존재하고 중앙 서버에서 계정과 자산을 관리하나, 탈중앙화 지갑은 이러한 개념이 없고 Kaikas는 단순히 "개인키"를 사용자 컴퓨터에 저장하고 Klaytn 블록체인과 상호작용하기 위한 도구일 뿐입니다.

**시드 구문** 
시드 구문은 다수의 개인키를 "확정적"이고 "계층적"으로 도출해내기 위한 무작위 단어 조합입니다. 즉, 동일한 시드 구문은 항상 암호학적으로 똑같은 개인키를 도출해내며, 계정 주소는 개인키로부터 확정적으로 도출됩니다.
따라서 시드 구문이 곧 Klaytn 계정의 ID이자 비밀번호로, 이를 분실하면 어떠한 경우에도 계정을 복구할 수 없고 반대로 이 구문이 노출되면 누구나 해당 계정의 소유권을 취득하여 자산을 전송할 수 있게 됩니다. 일반적으로 어떠한 이벤트나 고객 센터에서도 시드 구문이나 개인키의 입력을 요구하지 않기 때문에, 해당 요청은 사기나 스캠으로 의심하셔도 무방합니다.
아울러 시드 구문을 온라인 상의 이메일이나 메모 서비스에 보관하는 경우, 해당 계정이 해킹당하여 Kaikas 계정도 같이 탈취 당하는 사례가 빈번하게 보고되고 있으니 가급적이면 오프라인(종이에 수기로 기록)으로 안전하게 보관하시는 것을 권해드립니다.

**Klaytn 블록체인 기반**
Kaikas는 Klaytn 블록체인 상의 자산을 조회하고 전송하는 지갑입니다. Kaikas로 자산을 전송하거나 Kaikas에서 전송할 때에는 반드시 해당 코인(토큰)이 Klaytn 기반인지 확인 부탁드립니다.
아울러, Kaikas는 블록체인 상에서 거래를 바로 발생시키기 때문에 전송 후에는 절대 취소나 회수가 불가능하오니 수신 주소에 오탈자가 없고 해당 주소가 Klaytn 기반 주소인지 확인하시기 바랍니다. (이러한 부분 때문에 일반적으로 소량을 먼저 전송하여 테스트 후 원하는 수량을 전송하기도 합니다.)
Klaytn은 퍼블릭 블록체인으로, Klaytn 개발사를 포함한 누구도 특정 계정의 자산을 임의로 이동시키거나 회수/동결할 수 없습니다. 오전송된 자산을 되찾아줄 수 있는 것은 오직 해당 자산을 전송받은 계정의 개인키를 알고 있는 주체뿐이며, 개인키가 알려지지 않은 주소(예: 0x000...000)로 전송되는 경우 이를 회수할 수 있는 방법이 없고, 해당 자산은 그 계정에 계속 남아있게 됩니다.

# Klaytn
클레이튼(Klaytn)은 ㈜카카오의 자회사인 그라운드엑스가 개발한 디앱(dApp·분산애플리케이션)을 위한 블록체인 플랫폼이다. 그라운드X는 IT 강국인 한국의 기술로 글로벌한 자체 블록체인 플랫폼인 클레이튼을 개발했다. 15개 국가의 51개 서비스가 운영되고 있다. 클레이튼은 카카오와는 독립적인 퍼블릭 블록체인 플랫폼이며 이더리움에 비해 탈중앙화를 약화시키는 대신 디앱에 필요한 실용성을 강화했다. 클레이튼은 빠른 퍼블릭 블록체인을 목표로 하고 있다.     
      
클레이튼과 같은 서비스 지향 블록체인을 위한 이상적인 거버넌스 모델은 모든 네트워크 참여자가 참여하며 플랫폼의 이익을 위해 신속한 의사결정 프로세스를 가능하게 하는 모델이다. 불행히도 완전히 분산되어 있는 환경에서는 그러한 모델을 달성하는 것이 어렵지만 클레이튼은 일부 분산(semi-decentralized) 방식을 활용함으로써 적절한 플랫폼 거버넌스를 달성하고자 하는 공통의 목표를 공유하는 기여자 그룹을 선택할 것이다.         
      
클레이튼은 신뢰할 수 있는 기업에 의한 공동 관리 프레임워크 내에서 확장 솔루션과 데이터 중심 의사 결정을 제안한다. 그렇게 함으로써 클레이튼은 퍼블릭 플랫폼의 신뢰성과 투명성을 유지하면서 프라이빗 블록체인의 성능과 신뢰성을 달성한다. 또한 클레이튼은 일반유저와 개발자가 편리하게 블록체인을 사용할 수 있도록 하는데 주안점을 두었다. 일반 사용자들에게 친숙한 UI, UX 디자인과 엔터프라이즈급 애플리케이션, 스테이블한 토큰 구조 등으로 설계된 새로운 형태의 블록체인 플랫폼이다.[2] 한편, 클레이튼은 투기용이 아닌 실생활에서 사용할 수 있는 블록체인 서비스를 내놓겠다는 포부를 밝혔다. 이 외에도 ICO의 부작용을 지적하며, ICO를 진행하지 않겠다고 밝혔다.