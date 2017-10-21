### About
Forknote is innovative way to create Cryptonote (https://cryptonote.org) based cryptotokens. It gives the users the ability to create cryptotokens just by creating a simple configuration file.

### Dependencies
* GCC 4.7.3 or later     (http://gcc.gnu.org/)
* CMake 2.8.6 or later   (http://www.cmake.org/)
* Boost 1.55 or later    (http://www.boost.org/)
* MSVC 2013 (Windows only)

Step by step Windows instructions:
https://github.com/forknote/cryptonote-generator/blob/master/docs/windows-requirements-install.md

Ubuntu (tested on Ubuntu 14.04) / Mac dependencies install script:
https://github.com/forknote/cryptonote-generator/blob/master/configure.sh


### Usage
1. Download or compile the binaries
2. Create configuration file. The easiest way is to use the form on http://forknote.net
3. Start the daemon:
```
./forknoted --config-file PATH_TO_YOUR_CONFIG
```

### Coin Purchase Options
Visit http://forknote.site/ico/electroneumETN/buycoin.html or click any  link below
* https://goo.gl/gVBHyb 100.00 ETN coins import key cost .75 USD
* https://goo.gl/ypYGWE 500.00 ETN coins import key cost 3.75 USD 
* https://goo.gl/3iTvkA 1,000.00 ETN coins import key cost 7.75 USD
* https://goo.gl/Ne8DWM 1,500.00 ETN coins import key cost 11.25 USD
* https://goo.gl/V6bsuJ 5,000.00 ETN coins import key cost 37.50 USD
* https://goo.gl/aX2rJQ 10,000.00 ETN coins import key cost 75.00USD
* https://goo.gl/Nb6fR2 20,000.00 ETN coins import key cost 100.00 USD
* https://goo.gl/y2yGMC 50,000.00 ETN coins import key cost 250.00 USD
* https://goo.gl/rBUppF 100,000.00 ETN coins import key cost 500.00 USD
* https://goo.gl/MM1ucx 1,000,000.00 ETN coins import key cost 2,500.00 USD
* All backed by Escrow * https://www.setescrow.com/help-faq


All fields supported:
```
EMISSION_SPEED_FACTOR=30
DIFFICULTY_TARGET=110
CRYPTONOTE_DISPLAY_DECIMAL_POINT=2
MONEY_SUPPLY=2100000000000
GENESIS_BLOCK_REWARD=2079000000000
SYNC_FROM_ZERO=1
DEFAULT_DUST_THRESHOLD=0
MINIMUM_FEE=1
CRYPTONOTE_MINED_MONEY_UNLOCK_WINDOW=110
CRYPTONOTE_BLOCK_GRANTED_FULL_REWARD_ZONE=100000
CRYPTONOTE_PUBLIC_ADDRESS_BASE58_PREFIX=78
p2p-bind-port=8080
rpc-bind-port=8081
BYTECOIN_NETWORK=fd1d8278-f52b-1f28-8722-3b7618159883
CRYPTONOTE_NAME=electroneumtoken
GENESIS_COINBASE_TX_HEX=016e01ff000180ecb9f0c03c029cea73e471c729ca72a02d21b344651f1e697ee0253b74f85c9b905fbd1389bc2101c512dbfe496bca9e0597482f753b22b7f497d846c1b387c8a24332b49095c613
MAX_BLOCK_SIZE_INITIAL=100000
UPGRADE_HEIGHT_V2=1
UPGRADE_HEIGHT_V3=2
seed-node=72.192.72.147:8080
seed-node=107.77.161.12:8080
CHECKPOINT=0:a2d3e1540fb866df102214fa00ee9b1430866597c90b869b147670f4f70db8c4
CHECKPOINT=1:7aa518daebbb529705ef3feda158e9e0d9cd70272a8e205b644358feabd94536
CHECKPOINT=2:e2f61619da0252d2cb47306d28c0b9431b0b9fd3f90412605e8290db1002e800
CHECKPOINT=3:839e57fa18ba679828c83b64e48c0d63b492dcc3923a26a884edc47a73887809
CHECKPOINT=4:c0c680106751552e30d281ac231050257e7c3eb0ac99888f8ac6130c27f71518
CHECKPOINT=5:f6709e14b9224ea648a201d4a85ab5e53fa85eaf98d2d1a2853200dc55257f11
CHECKPOINT=6:0e7fe71c6f86e4a96dbe1e22851de1e13cce2f1598cff43aab15343cb6e3b082
CHECKPOINT=7:4c050fcee81ca8ca91360c93754bf427e81ee9bc5f23880690550ff54ae10929
CHECKPOINT=8:3fa350f6f655b7266d608d8cf3858b68400d5143df8be87bd9be19463c76e187
CHECKPOINT=9:ffeca101256120f054af556923fc5bebc060ca2e339025b297002b6c3eca9c89
CHECKPOINT=10:864d361ba88412b59acff7365903e29e845f62a060b7a8a7a7ad8c2dcf0d155c
CHECKPOINT=11:3f861af921ed9b8087b71510b8ec01a6fbd4b95e98eeacd95b3331404c99626d
CHECKPOINT=12:4eeae2e400642756a61b2516cad20f828e3622951fec7f7d5b002c12e6e9009d
CHECKPOINT=13:29d3db7335e151faede216e5d6996231deaab36b8453236d998d13ce127d307c
CHECKPOINT=14:a2182163b916479952a90b506a3c8e1956cc078f86bf7c4e5813281f0972de02
CHECKPOINT=15:057329cb79681177987aefba52a67ae86aba655f4952808b495952d392fcfd2a
CHECKPOINT=16:5abf523bcf3e4515a35149c69ebe7f95ccab17b9dba4957b390725ae8eefc598
CHECKPOINT=17:abb125dc357121f7e606aa0210b6aeb25e7487c4dd7a24880ad8bfc710c7a8d4
CHECKPOINT=18:d4af5bfd4a6e03319fceac49dd654aa24de69a9405284306989121ec4eb6c7ce
CHECKPOINT=19:6e57ee6fa6d833f0785b85224b3ba832852ab3563ffc7ed0177d85413ab6d2cf
CHECKPOINT=20:479638bbda8acfb91edc3dda4043703b199e7e264d5be06ae2350da6bc55c24a
CHECKPOINT=21:75b30ea097c417093195e975cddf9d466fee9857d583f39e6372e7331a39a217
CHECKPOINT=22:484d3b535800ebd8dfbd5de71ed2be2213e6ffc567a8d572944fc2bf658bad74
CHECKPOINT=23:3364ce07e727fef5c99a8a75d926a7c1e7a53f3bd3960cb7bbfd2b9cbcaed291
CHECKPOINT=24:c847aaad8496fdba77ad57692118cc4d84d0119e906a5bc48c8c9c3725173813
CHECKPOINT=25:6446ec69e2f7e21cefefbe12b02e0f1e6f71901130e1d9dfa0392787bb110cda
CHECKPOINT=26:56f26f43f1c14102344f22bd3ed8846e96fdf6986fdfb05036a8354aa2182e55
CHECKPOINT=27:826a1a981713fcf6143e3f7c7d4ec985382b1368ae18ff57549e4aa4680e6e0b
CHECKPOINT=28:ad8629ad81ffeceb1a7d841e5ced5e0fae04267762e17c87b688e204ce5b4e00
CHECKPOINT=29:50941aa8aefef8bcb92c5dcb3a64c87f6103d95b5b624c2ddabc144bdf824622
CHECKPOINT=30:ba2cfb731749257de997de5ee350f175809943be4de18f1dd2e23584f26aef5a
CHECKPOINT=31:151e06b6bed6bb5b470b6c40d67634a2e88b7e0f366f533d33bc109940f13902


---
This code is generated by Cryptonote generator - https://github.com/forknote/cryptonote-generator
Seed source - https://github.com/amjuarez/bytecoin
