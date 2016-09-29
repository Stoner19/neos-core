
NeosCoin is a PoS-based cryptocurrency.

NeosCoin uses libsecp256k1,
			  libgmp,
			  Boost1.55,
			  OR Boost1.57,  
			  Openssl1.01p,
			  Berkeley DB 4.8,
			  QT5 to compile


Block Spacing: 60 Seconds
Stake Minimum Age: 24 Hours

Port: 29320
RPC Port: 29321

Development in progress.  This is only the base we've chosen to work with and improve, and there is much more to come.

Every 500K blocks, the rewards are cut down by .10 for the next 5 years roughly (every 347 days)


BUILD LINUX
-----------
1) git clone https://github.com/neoscoin/neos-core

2) cd neos-core/src

3) make -f makefile.unix            # Headless

(optional)

4) strip neoscoind

5) sudo cp neoscoind /usr/local/bin
