# Quorum 5nodesRTGS WebUI
Quorum is an Ethereum-based distributed ledger protocol with transaction/contract privacy and new consensus mechanisms.

Quorum is a fork of [go-ethereum](https://github.com/ethereum/go-ethereum) and is updated in line with go-ethereum releases.

Key enhancements over go-ethereum:

* __Privacy__ - Quorum supports private transactions and private contracts through public/private state separation, and utilises peer-to-peer encrypted message exchanges (see [Constellation](https://github.com/jpmorganchase/constellation) and [Tessera](https://github.com/jpmorganchase/tessera)) for directed transfer of private data to network participants
* __Alternative Consensus Mechanisms__ - with no need for POW/POS in a permissioned network, Quorum instead offers multiple consensus mechanisms that are more appropriate for consortium chains:
    * __Raft-based Consensus__ - a consensus model for faster blocktimes, transaction finality, and on-demand block creation
    * __Istanbul BFT__ - a PBFT-inspired consensus algorithm with transaction finality, by AMIS.
* __Peer Permissioning__ - node/peer permissioning using smart contracts, ensuring only known parties can join the network
* __Higher Performance__ - Quorum offers significantly higher performance than public geth

## Architecture

![Quorum Tessera Privacy Flow](https://raw.githubusercontent.com/jpmorganchase/quorum-docs/master/images/QuorumTransactionProcessing.JPG)

The above diagram is a high-level overview of the privacy architecture used by Quorum.


# Pre-reqs:

- Lab 1 
- Lab 2

# 1. Interacting with the Blockchain

Move into following directory:
`cd /lab/quorum-examples/examples/5nodesRTGS/1-interacting-with-the-blockchain`

1. Run `quorum`, deploy and provision 5nodesRTGS contracts (complete Lab 1 and Lab 2).
2. Edit app.js and set your ip and port of quorum RPC on line 6
3. Run `npm install` and `npm install --save connect serve-static`
4. Run `npm start`. After `bundle.js` is compiled and message is printed. Press `Ctrl+C` to exit.
5. Run `node server.js` and open `host-ip:9615` in browser 
6. Enter a Bank Contract address and press the button. The bank balance will be shown


# 2. Interacting with a contracts

Move into following directory:
`cd /lab/quorum-examples/examples/5nodesRTGS/2-interacting-with-a-contract`

1. Run `raft-init.sh` `raft-start.sh` in the geth node (complete Lab 1 and Lab 2).
2. Run `npm install` and `npm install --save connect serve-static`
3. Deploy and provision the contracts following the 5nodesRTGS README, steps 4-10. The HTML file has the same contract addresses of a freshly initiated 5NodesRTGS example, change if necessary
4. Replace the IP address from lines `5-8` in `app.js` file. 
5. Run `npm start`. After `bundle.js` is compiled and message is printed. Press `Ctrl+C` to exit.
6. Run `node server.js` and open `host-ip:9615` in browser and start playing.

It is a good example of a javascript page interacting with Quorum using private transactions.

