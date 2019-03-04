LeisureCoin Core integration/staging repository
=================================================

LeisureCoin (LeisureCoin)

- Fast transactions featuring guaranteed zero confirmation transactions, we call it _SwiftTX_.
- Masternode is collateral of 10,000 LeisureCoin.



(Above this line = original README.md from LeisureCoinProject - sample source)
------------------------------------------------------------------------------


(Below are my basic preparation for the practice)


Genesis Block & Merkle hash Info
================================

* Generated:

algorithm: quark

pzTimestamp: Class by Professor Tfinch 2019

pubkey: 04b6209d7542dd5b6daddb677e0df8020f4e9ab5684c313886127e02cde0ff19f3ea1d4c97af94bbeb15a1436930a884c3bb2cbf6cb69dcf530e8fcc972d24c001

bits: 504365040

time: 1551172275

merkle root hash: b5789963fe108433109c84283c86a7c2b95a55c176762130f967215fbbe1bf2b

Searching for genesis hash...

nonce: 1168826

genesis hash: 00000ef21d678d256b9bc3a3bc0c7c5ec2926a3301408f4d528700e0827082eb


SAMPLE KEY1 (vAlertPUBkey used above)
04b6209d7542dd5b6daddb677e0df8020f4e9ab5684c313886127e02cde0ff19f3ea1d4c97af94bbeb15a1436930a884c3bb2cbf6cb69dcf530e8fcc972d24c001

SAMPLE KEY2 
0423b7af794ec13770d98f5aa1f3956f2df8f6a03867459890f96e4ea77628384f8962bbd7c64286b6794b3341aac7d8d8e9a7df63884e505f8882f69911322264

SAMPLE KEY3
049f58cf48a5e38b2f8af1c29c233a805fe818a3084122bdbc84469405d92b3bdc49b890b3e41bf006fe1d223c5a692557271b161efa4f37643bb5621aa9482cd3



//printf("genesis.GetHash = %s\n", genesis.GetHash().ToString().c_str());

//printf("genesis.hashMerkleRoot = %s\n", genesis.hashMerkleRoot.ToString().c_str());


* True value (after ./TESTCOINd) :

- Genesis : "0x"

- Merkle hash : "0x"




Name & Port changes
===================

find . -type f -print0 | xargs -0 sed -i 's/LeisureCoins/PRACTICE1/g'

find . -type f -print0 | xargs -0 sed -i 's/leisurecoins/PRACTICE1/g'

find . -type f -print0 | xargs -0 sed -i 's/LeisureCoin/PRACTICE1/g'

find . -type f -print0 | xargs -0 sed -i 's/leisurecoin/PRACTICE1/g'

find . -type f -print0 | xargs -0 sed -i 's/Leisurecoin/PRACTICE1/g'

find . -type f -print0 | xargs -0 sed -i 's/LSR/PRTC/g'

find . -type f -print0 | xargs -0 sed -i 's/LSR/PRTC/g'

find . -type f -print0 | xargs -0 sed -i 's/PARK/PRTC/g'  // found weird ticker

find . -type f -print0 | xargs -0 sed -i 's/EPIC/PRTC/g'  // found weird ticker (probably a fork of EPIC coin)

find . -type f -print0 | xargs -0 sed -i 's/9333/8888/g'  //(P2P)

find . -type f -print0 | xargs -0 sed -i 's/9332/8887/g'  //(RPC)

find . -type f -print0 | xargs -0 sed -i 's/19333/18888/g'  //(P2P) -testnet

find . -type f -print0 | xargs -0 sed -i 's/19332/18887/g'  //(RPC) -testnet

find . -type f -print0 | xargs -0 sed -i 's/34120/8888/g'

find . -type f -print0 | xargs -0 sed -i 's/34121/8887/g'

=========================================================================================================
change all names & file names + port --> then re-upload
