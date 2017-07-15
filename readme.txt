Btcoin a fork of BitCoin  
Copyright (c) 2009 Satoshi Nakamoto
Distributed under the MIT/X11 software license, see the accompanying
file license.txt or http://www.opensource.org/licenses/mit-license.php.
This product includes software developed by the OpenSSL Project for use in
the OpenSSL Toolkit (http://www.openssl.org/).  This product includes
cryptographic software written by Eric Young (eay@cryptsoft.com).

Setup
-----
Unpack the files into a directory and run Bcoin.exe.

The software automatically finds other nodes to connect to.  You should set
your firewall to forward port 8333 to your computer so you can receive incoming
connections, otherwise the nodes you can connect with will be limited.

To support the network by running a node, select:

  Options->Generate Coins

and keep the program open or minimized.  It runs at idle priority when no other
programs are using the CPU.  Your computer will be solving a very difficult
computational problem that is used to lock in blocks of transactions.  The time
to generate a block varies each time, but may take days or months, depending
on the speed of your computer and the competition on the network.  It's not a
computation that has to start over from the beginning if you stop and restart
it.  A solution might be found at any given moment it's running.  As a reward
for supporting the network, you receive coins when you successfully generate a
block.
