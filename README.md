# eth-chain
ethereum private blockchain demo

personal.listAccounts[0]

eth.hashrate

miner.start()

miner.stop()

_________________________________

password nokia123

geth --datadir "octopod/" init "octopod/octopod.json"

geth --datadir "octopod/" --rpc --networkid 786786 --nodiscover --maxpeers=0 --rpcapi "eth,net,web3,personal,miner,admin" --allow-insecure-unlock --ethstats masternode:s3cr3t@localhost:3000 console
