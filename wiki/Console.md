***
The **Console** allows you to see the status of the blockchain, including the number of blocks created, transactions that are pending, peers on the network and throughput of transactions. It also allows you to manage your node, including starting and stopping it, pausing block creation or changing the logging level.
***

![](https://github.com/jpmorganchase/cakeshop-docs/blob/master/images/console.png)

## Widgets & Functionality 

### 'Node Info' widget
<em>Shows various attributes of the current node, including IP address, peer count, pending transaction count and RPC url</em>

![](https://github.com/jpmorganchase/cakeshop-docs/blob/master/images/node-info-widget.png)

* **Node URL**: The enode id used to connect to peers.  Add another node's Node URL in the ![](Peers|Peers) tab to connect to their network
* **RPC URL**: The RPC port of the underlying node
* **Quorum Info**: When connected to a Quorum node, displays the relevant info about that node, including blockMaker status, voting status and voting strategy times
* **Quorum**: True when connected to a Quorum node

***

### 'Node Control' widget
<em>Provides the ability to bring the node up and down or reset it</em>

![](https://github.com/jpmorganchase/cakeshop-docs/blob/master/images/node-control-widget.PNG)

* **Restart Node**: Stops and then starts the underlying node. Upon restart, the node will resync with the network.
* **Stop Node**: Temporarily pauses the node. Note that when a node is stopped, Cakeshop continues to try to connect to the underlying node, resulting in connection exception errors being logged.
* **Start Node**: Starts node that was previously stopped
* **Create New Chain** : Deletes the existing chain and creates a new one from the genesis block.

***

### 'Node Settings' widget
<em>Provides the ability to set various node configurations and view the genesis block</em>

![](https://github.com/jpmorganchase/cakeshop-docs/blob/master/images/node-settings-widget.png)

* **Committing Transactions**: 
 * Yes: blocks are created
 * No: blocks are not created, transactions build up in the memory pool
* **Network ID**: The Network ID specified when the underlying node was started, this can be changed from the Console. When starting Cakeshop in ![]('Default' mode|Getting Started#running-cakeshop), the Network ID will be taken from the **application.properties** files
* **Log Level**: Toggle to specify the verbosity of the underlying Ethereum node logs
* **Genesis Block**: Displays the configuration of the genesis.json file for the network

***
