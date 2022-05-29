# Golang Blockchain

## HOw TO USE ON WINDOW

### Initialize Blockchain
#### Open cmd and run `set NODE_ID=3000` to set up host 3000 for node, you also 
#### Run `go run main.go createwallet` to create wallet for each host created
#### Run `go run main.go createblockchain` to create new blockchain with first address
#### Run `cd tmp` to move to tmp folder
#### Run `xcopy blocks_3000\ blocks_{NODE_ID} /E/H` to copy the block in first block to 
#### Run `xcopy blocks_3000\ blocks_gen /E/H` to copy block to blocks_gen which
#### Run `cd ..` to back to root folder

------

### General command
#### Run `go run main.go send -from {FROM} -to {TO} -amount {AMOUNT} -mine` to send amount of coins. Then -mine flag is set, mine off of this node
#### Run `go run main.go startnode -miner {ADDRESS}` to start a node with ID specified in NODE_ID env. var. -miner enables mining
#### Run `go run main.go}` to know another command