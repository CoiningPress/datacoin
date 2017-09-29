Datacoin 0.1.2.0
===================

Copyright (c) 2013-2017 Datacoin Developers

Distributed under the MIT/X11 software license, see the accompanying
file COPYING or http://www.opensource.org/licenses/mit-license.php.
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](http://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.


Intro
---------------------
Datacoin is a free open source peer-to-peer electronic cash system that is
completely decentralized, without the need for a central server or trusted
parties.  Datacoin implements the first scientific computing proof-of-work for
cryptocurrencies. The unique proof-of-work design searches for rare prime
formations, providing experimental value for mathematicians to further
understand the nature and distribution related to prime number, a simple yet
mysterious construct of arithmetic that continues to baffle the top minds of
mankind.


Setup
---------------------
You need the Qt4 run-time libraries to run Datacoin-Qt. On Debian or Ubuntu:
	`sudo apt-get install libqtgui4`

Unpack the files into a directory and run:

- bin/32/datacoin-qt (GUI, 32-bit)
- bin/32/datacoind (headless, 32-bit)
- bin/64/datacoin-qt (GUI, 64-bit)
- bin/64/datacoind (headless, 64-bit)

See the documentation at the [Bitcoin Wiki](https://en.bitcoin.it/wiki/Main_Page)
for help and more information.


Upgrade
--------------------
First backup wallet. Then follow setup instructions. Double check balance
after completing setup and starting up client.


Other Pages
---------------------
- [Unix Build Notes](build-unix.md)
- [OSX Build Notes](build-osx.md)
- [Windows Build Notes](build-msw.md)
- [Coding Guidelines](coding.md)
- [Release Process](release-process.md)
- [Release Notes](release-notes.md)
- [Multiwallet Qt Development](multiwallet-qt.md)
- [Unit Tests](unit-tests.md)
- [Translation Process](translation_process.md)
