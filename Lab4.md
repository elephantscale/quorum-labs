# Cakeshop

An integrated development environment and SDK for Ethereum-like ledgers

![screenshot](images/console.png "screenshot")

![screenshot](images/sandbox.png "sandbox screenshot")

Overview
========

[Cakeshop](https://github.com/jpmorganchase/cakeshop) is a set of tools
and APIs for working with [Ethereum](https://ethereum.org/)-like
ledgers, packaged as a Java web application archive (WAR) that gets you
up and running in under 60 seconds.

Cakeshop can either start up a geth node, which you can then interact
with using the Cakeshop front-end, or it can be connected to an
Ethereum-like node, such as Quorum, that you already have running. A
given Cakeshop instance connects with one node on the blockchain network
you connect to.

# Running via Docker

Run via docker and access UI on http://localhost:8080/

`docker run -p 8080:8080 quorumengineering/cakeshop`

Out of the box you get:

-   **Node Management** - Fully functioning Ethereum node (via geth),
    setting up a cluster
-   **Blockchain Explorer** - view transactions, blocks and contracts,
    and see historical contract state at a point in time
-   **Admin Console** - start & stop nodes, create a cluster and view
    the overall status of your network
-   **Peer Management** - easily discover, add and remove peers
-   **Solidity Sandbox** - develop, compile, deploy and interact with
    Solidity smart contracts

It provides tools for managing a local blockchain node, setting up
clusters, exploring the state of the chain, and working with contracts.

The Cakeshop package includes the
[tessera](https://github.com/jpmorganchase/tessera) and
[constellation](https://github.com/jpmorganchase/constellation)
transaction managers, a
[Solidity](https://solidity.readthedocs.org/en/latest/) compiler, and
all dependencies. Cakeshop will download the latest version of
[quorum](https://github.com/jpmorganchase/quorum) and bootnode from
[geth](https://github.com/ethereum/go-ethereum)



The linked pages below provide an overview of each of the Tabs in Cakeshop.  

## [Console](./wiki/Console.md)
![](https://github.com/jpmorganchase/cakeshop-docs/blob/master/images/consoleTab-btn-out.PNG)

## [Contracts](./wiki/Contracts.md)
![](https://github.com/jpmorganchase/cakeshop-docs/blob/master/images/contractsTab-btn-out.PNG)

## [Sandbox](./wiki/Sandbox.md)
![](https://github.com/jpmorganchase/cakeshop-docs/blob/master/images/sandboxTab-btn-out.PNG)

## [Chain Explorer](./wiki/Chain Explorer.md)
![](https://github.com/jpmorganchase/cakeshop-docs/blob/master/images/explorerTab-btn-out.PNG)

## [Wallet](./wiki/Wallet.md)
![](https://github.com/jpmorganchase/cakeshop-docs/blob/master/images/walletTab-btn-out.PNG)

## [Peers](./wiki/Peers.md)
![](https://github.com/jpmorganchase/cakeshop-docs/blob/master/images/peersTab-btn-out.PNG)

## [API](./wiki/API.md)
![](https://github.com/jpmorganchase/cakeshop-docs/blob/master/images/apiTab-btn-out.PNG)