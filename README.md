# EtherateMT

[![Build Status](https://travis-ci.org/jwbensley/EtherateMT.svg?branch=master)](https://travis-ci.org/jwbensley/EtherateMT)  
[![PayPal Donate](https://img.shields.io/badge/paypal-donate-green.svg) < donate a dev coffee!](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=james%2Bpaypal%40bensley%2eme&lc=GB&item_name=EtherateMT&currency_code=GBP)  


#### What is it


[Etherate](https://github.com/jwbensley/Etherate) is a Linux CLI application for testing layer 2 Ethernet and MPLS connectivity. It can generate various Ethernet and MPLS frames for testing different devices such as switches/routers/firewalls etc, to test traffic parsing/matching/filtering/forwarding. Etherate is not an effective load tester, it is not designed for high performance. It is designed for testing many traffic parsing scenarios.  

EtherateMT is a multi-threaded ("MT") load generator and load sinker (not "traffic" generator). EtherateMT simply sends frames as fast as it can.  

The user can run the application in different modes (like transmit or receieve), choose the number of worker threads and which method for transmission/reception to use within the Kernel (e.g. `sendto()` or `sendmsg()` and `PACKET_MMAP` etc.).  

The code is still in beta so it's a bit buggy but mostly works.


#### Features



### FAQ and Troubleshooting

See the Wiki page: https://github.com/jwbensley/EtherateMT/wiki/FAQ-&-Troubleshooting
from eth_account import Account
acct = Account.create('KEYSMASH FJAFJKLDSKF7JKFDJ 1530')
acct.address
'0x5ce9454909639D2D17A3F753ce7d93fa0b9aB12E'
acct.key
HexBytes('0x8676e9a8c86c8921e922e61e0bb6e9e9689aad4c99082620610b00140e5f21b8')

# These methods are also available: sign_message(), sign_transaction(),
# encrypt().
# They correspond to the same-named methods in Account.*
# but without the private key argument
from eth_account import Account

# Generate a new Ethereum account
account = Account.create
 