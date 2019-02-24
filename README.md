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

python genesis.py -a quark -t 1551028551 -z "Class by Professor Tfinch 2019" -p "0442c37cda3dca38aa4bfd14c674d01d133e2e748570ca9a0698b5f81ba52030069993901d5723fd9aaf632d9ee0dc96ed5fd77df1ccb4fc275c410d4afe400f62"

Searching for genesis hash...

algorithm: quark

merkle hash: 4ddc528185a2541eebecc15fd8f6bb44c71d98a7e8c9e9ad858b817257ebc25c

pszTimestamp: Class by Professor Tfinch 2019

pubkey: 0442c37cda3dca38aa4bfd14c674d01d133e2e748570ca9a0698b5f81ba52030069993901d5723fd9aaf632d9ee0dc96ed5fd77df1ccb4fc275c410d4afe400f62

time: 1551028551

bits: 0x1e0ffff0

genesis hash found!

nonce: 329635

genesis hash: 000009a7f0130febebd2d6b84bfa2c8ca66cabd963c78f24e823611ade3778f5


SAMPLE KEY1 (vAlertPUBkey used above)
0442c37cda3dca38aa4bfd14c674d01d133e2e748570ca9a0698b5f81ba52030069993901d5723fd9aaf632d9ee0dc96ed5fd77df1ccb4fc275c410d4afe400f62

SAMPLE KEY2 
04c996877f4edc6095f2e18a78be675de4b3a74f729eeabc148f27ddf6f46f68e133b7cfc4522c9a6c3d596eb552e34c75b3eb1498dceba4da57dad69727dbdcb7

SAMPLE KEY3
049f58cf48a5e38b2f8af1c29c233a805fe818a3084122bdbc84469405d92b3bdc49b890b3e41bf006fe1d223c5a692557271b161efa4f37643bb5621aa9482cd3

SAMPLE KEY4
0423b7af794ec13770d98f5aa1f3956f2df8f6a03867459890f96e4ea77628384f8962bbd7c64286b6794b3341aac7d8d8e9a7df63884e505f8882f69911322264

SAMPLE KEY5
04b6209d7542dd5b6daddb677e0df8020f4e9ab5684c313886127e02cde0ff19f3ea1d4c97af94bbeb15a1436930a884c3bb2cbf6cb69dcf530e8fcc972d24c001



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

find . -type f -print0 | xargs -0 sed -i 's/9333/8888/g'  //(P2P)

find . -type f -print0 | xargs -0 sed -i 's/9332/8887/g'  //(RPC)

find . -type f -print0 | xargs -0 sed -i 's/19333/18888/g'  //(P2P) -testnet

find . -type f -print0 | xargs -0 sed -i 's/19332/18887/g'  //(RPC) -testnet



