HSHLcoin integration/staging tree
================================

Copyright (c) 2009-2014 Bitcoin Developers
Copyright (c) 2011-2017 Litecoin Developers
Copyright (c) 2018      HSHLcoin Developers

What is HSHLcoin?
----------------

HSHLcoin is a lite version of Bitcoin using scrypt as a proof-of-work algorithm.
 - 2.5 minute block targets
 - subsidy halves in 840k blocks (~4 years)
 - ~84 million total coins

The rest is the same as Bitcoin.
 - 20 coins per block
 - 2016 blocks to retarget difficulty


License
-------

HSHLcoin is released under the terms of the MIT license. See `COPYING` for more
information or see http://opensource.org/licenses/MIT.

Development process
-------------------

HSHLCoin is a finished experiment, it works on Windows as well as on Linux and does just what you would expect a Litecoin-clone to do.



Installation on Windows
-----------------------
Just download the HSHLCoin-qt.exe and execute. It will automatically create a Wallet and an Address for you. Problem is that there is no existing Network in place for you to connect to. But worry not! You can just create your own! Just install the software on multiple PC´s and create a HSHLCoin.conf file at C:\Users\You\AppData\Roaming\HSHLcoin. There you can add your other PCs' IP's with addnode="PC'sIP". That should do the trick.

Installation on Linux
---------------------
Just download the repo and execute HSHLCoin-qt. The other stuff is similar to the Windows-installation.

Thanks for reading.
Feel free to comment on what you think could be changed/improved.

Best regards,

an anonymous HSHL-Student
