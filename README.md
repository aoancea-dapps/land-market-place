# land-market-place

- https://medium.com/coinmonks/ethereum-setting-up-a-private-blockchain-67bbb96cf4f1
- https://medium.com/coinmonks/ethereum-land-marketplace-dapp-tutorial-part-1-create-and-deploy-a-smart-contract-351bc0d62be2
- https://medium.com/coinmonks/ethereum-land-marketplace-dapp-tutorial-part-2-integrate-with-a-web-app-85db82d732cd

## Commands
- ``geth --datadir ./datadir init .\genesis.json``
- ``geth account new --datadir .\datadir\``
- ``geth --datadir ./datadir --networkid 2018 --port 30306 --nodiscover --rpc --rpcapi “db,personal,eth,net,web3,debug” --rpccorsdomain=”*” --rpcaddr=”localhost” --rpcport 8545 console``