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
DIFFICULTY_TARGET=11
CRYPTONOTE_DISPLAY_DECIMAL_POINT=2
MONEY_SUPPLY=2100000000000
GENESIS_BLOCK_REWARD=2079000000000
SYNC_FROM_ZERO=1
DEFAULT_DUST_THRESHOLD=0
MINIMUM_FEE=1
CRYPTONOTE_MINED_MONEY_UNLOCK_WINDOW=110
CRYPTONOTE_BLOCK_GRANTED_FULL_REWARD_ZONE=100000
MAX_TRANSACTION_SIZE_LIMIT=100000
CRYPTONOTE_PUBLIC_ADDRESS_BASE58_PREFIX=78
DIFFICULTY_CUT_V1=60
DIFFICULTY_CUT_V2=60
DIFFICULTY_CUT=0
DIFFICULTY_LAG_V1=15
DIFFICULTY_LAG_V2=15
DIFFICULTY_LAG=0
DIFFICULTY_WINDOW_V1=7855
DIFFICULTY_WINDOW_V2=7855
DIFFICULTY_WINDOW=17
ZAWY_DIFFICULTY_V3=1
ZAWY_DIFFICULTY_DIFFICULTY_BLOCK_VERSION=3
p2p-bind-port=31073
rpc-bind-port=31074
BYTECOIN_NETWORK=75b4936a-9c33-ea7a-b2b2-d79973c4b873
CRYPTONOTE_NAME=electroneumcoin
GENESIS_COINBASE_TX_HEX=016e01ff000180ecb9f0c03c02f478d6076cd02ce188dcab9ddd5926d2aafd2054b7e819982d6d215148d6e6bf21016869c5bb845f7576b4f571bb2ba1372d3a5fbee17475f9caefdb9d6debe8a93c
MAX_BLOCK_SIZE_INITIAL=100000
UPGRADE_HEIGHT_V2=1
UPGRADE_HEIGHT_V3=30
seed-node=54.89.252.229:31073
seed-node=54.161.171.231:31073
CHECKPOINT=1:4d2199dd2367c427bb4a9a4976ccd372393c466cb2da0eba784cd9ed94dc9b29


---
This code is generated by Cryptonote generator - https://github.com/forknote/cryptonote-generator
Seed source - https://github.com/amjuarez/bytecoin
