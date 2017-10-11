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

### ICO Funding and Coin Purchase
ICO funding ADDRESS
BTC
3BGusyERzBf5uiDdTFQdqQCFYUFUrig2iz

ETH
0xef8f69d6fab5e83806bcd9a208462a5af238a3fb

BCC
19BFvMqAoZDmwRFyHctYVtZaNyLcjsAZTt

DASH
XeEEhiKGixZw1eTy3phSvkwZ8KXrup5hxQ

ZEC
t1Y7y1QxQDaxbtpsrDZp8uPZpKnQKy72sUb

XMR
41quKNZo1zATiNubhhJMxkBqmb3fBARW7EviGvButzQSc4EMVGL6RmUjXqrT3anyZ22j7DEE74GkbVc QFyH2nNiC3cuEc2u

To participate follow the instructions below

1. Send your funding source to any address above at .03 USD per (ETN) you wish to purchase.
For reference use BTC converter

2. Email use at electroneumcoin@webname.com your transaction send and we will reply back with your (ETN) wallet address and confirmation
transaction hash for Cryptonote (ETN) along with import keys to use with your (ETN) wallet


All fields supported:
```
EMISSION_SPEED_FACTOR=1
DIFFICULTY_TARGET=10
CRYPTONOTE_DISPLAY_DECIMAL_POINT=2
MONEY_SUPPLY=2100000000000
GENESIS_BLOCK_REWARD=2100000000000
SYNC_FROM_ZERO=1
DEFAULT_DUST_THRESHOLD=0
MINIMUM_FEE=1
CRYPTONOTE_MINED_MONEY_UNLOCK_WINDOW=120
CRYPTONOTE_BLOCK_GRANTED_FULL_REWARD_ZONE=100000
MAX_TRANSACTION_SIZE_LIMIT=100000
CRYPTONOTE_PUBLIC_ADDRESS_BASE58_PREFIX=737
DIFFICULTY_CUT_V1=60
DIFFICULTY_CUT_V2=60
DIFFICULTY_CUT=0
DIFFICULTY_LAG_V1=15
DIFFICULTY_LAG_V2=15
DIFFICULTY_LAG=0
DIFFICULTY_WINDOW_V1=8640
DIFFICULTY_WINDOW_V2=8640
DIFFICULTY_WINDOW=17
ZAWY_DIFFICULTY_V3=1
ZAWY_DIFFICULTY_DIFFICULTY_BLOCK_VERSION=3
p2p-bind-port=70761
rpc-bind-port=80762
BYTECOIN_NETWORK=ca234860-8f46-9e41-b12a-c0b6f64d0876
CRYPTONOTE_NAME=electroneumcoin
GENESIS_COINBASE_TX_HEX=TO BE ADDED After ICO
MAX_BLOCK_SIZE_INITIAL=100000
UPGRADE_HEIGHT_V2=1
UPGRADE_HEIGHT_V3=30

// simplewallet parameters
wallet-rpc-bind-ip=127.0.0.1        // instead rpc-bind-ip
wallet-rpc-bind-port=33671          // instead rpc-bind-port
SYNC_FROM_ZERO=1                    // to sync the wallet from block 0. Used for premine coins or brain wallets
```

---
This code is generated by Cryptonote generator - https://github.com/forknote/cryptonote-generator
Seed source - https://github.com/amjuarez/bytecoin
