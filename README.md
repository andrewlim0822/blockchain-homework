# Blockchain Instructions:

* Type **./geth --datadir node1 --mine --miner.threads 1**  in git bash to start node1

* Type **./geth --datadir node2 --port 30304 --http --bootnodes "enode://8c40cbbc4efa273a2208f7a3c075ff8b9534a33926f136d35efc9aa7902ffab64f6b502dcac447244106cfe27f6930dd008b551879b5039e42d9370133f22ec3@127.0.0.1:30303" --ipcdisable** in terminal to start node2


* Open MyCrypto and connect to the custom network called **anycoin** which is created using custom network information that was set in the genesis. 

* Open wallet through Keystore file and select the keystore from node1 folder. Enter the passcode which was set while initalizing the nodes.

* Check Balance and send transaction. Please refer to screenshots.

* There were a 2 errors I encountered: 1. The TX Status was infinitely pending. 2. Could not push fully into github due to github's max limit capacity. 
