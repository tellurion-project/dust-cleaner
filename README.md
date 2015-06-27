dust-cleaner
==========

Joins "dust" payments created by p2pool into bigger transactions with minimal fee

Requirements:
-------------------------
Generic:
* Groestlcoin >=2.1.0.6
* Python >=2.6

Linux:
* sudo apt-get install python-pip -y
* sudo pip install requests

Running dust-cleaner.py:
-------------------------
* Install your local groestlcoind
* Import the private keys with the 'dust' payments into the local wallet
* Run dust-cleaner.py in test mode first, to confirm that your wallet is properly
set and that you are using the correct parameters.

`./dust-cleaner.py <destination-address>`

Replace `<destination-address>` with the Groestlcoin address to receive the new
created transaction.

For additional options:

`./dust-cleaner.py --help`
