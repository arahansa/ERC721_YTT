# crypto-ytt-starter
Klaytn ERC721 BApp

truffle migrate --compile-all --reset --network ganache
truffle console --network ganache

instance = await YoutubeThumbnailToken.deployed()
instance.name()
instance.symbol()

---
ERC721 Metadata 
ERC721 Enumerable
오픈제플린에서 세개의 인터페이스를 구현

Enumerable 안에 totalSupply()

- 비디오아이디, 제목, 유튜버, 게시일
https://github.com/ethereum/EIPs/blob/master/EIPS/eip-721.md
  
웹주소 블록체인


instance.mintYTT("1234" ,"sejong", "2019.1.11", "https://ipfs.io", {from:accounts[1]})

instance.getYTT(1)
instance.isTokenAlreadyCreated("1234")

