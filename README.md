# SmartContract-VotingApp

블록체인이 적용될 사례는 무궁무진하나, 현재 상황에서 블록체인 네트워크의 한계, 효율 등을 모두 고려했을 때 가장 기대할 수 있는 분야는 투표 및 공공 문서 관리일 것이다.
이번 프로젝트에서는 투표를 예제로 블록체인 네트워크에서의 직접적인 코드 작성 및 클라이언트에의 제시까지를 해본다.

프로젝트에서 제안하는 방식은 다음 두 가지이다.
1. 선거권을 가지고 투표하기
2. 직접 유권자가 되어 선거에 참여하기

한 컨트랙트

### 소켓통신에 대한 지식이 없다면 이 부분은 넘어가셔도 좋습니다.

이더리움 네트워크 플랫폼을 사용하거나 API를 사용하는 경우, 이미 P2P 방식(혹은, 소켓 통신)의 프로토콜이 베이스가 되어 있기 때문에 이를 직접적으로 경험해 볼 수 있도록 클라이언트에 채팅방을 구현한다. 채팅방은 socket.io 라이브러리를 이용하였다.

혹시나, javascript net, 혹은 WebSocket, (+a JSON-RPC) 등의 개념을 익히고 있는 중이라면, 블록체인 네트워크를 자바스크립트 환경에서 구현한 다음 프로젝트를 제시한다.
event 모듈을 사용하여 자바스크립트 모듈 중 상당수 차지하는 event 및 그에 대한 callback 처리를 확인할 수 있다.

[SmartServer-WebSocket-TypeScript](https://github.com/imkyle94/SmartServer-WebSocket-TypeScript)



### Requirement
- Remix
- Postman
- Truffle
- Ganache
