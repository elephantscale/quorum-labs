***
Cakeshop comes with a suite of RESTful APIs that make interacting with an Ethereum-like node simple.  The **API** tab provides the full documentation for the APIs that Cakeshop exposes, including example usage and response formats.
***

![](https://github.com/jpmorganchase/cakeshop-docs/blob/master/images/api.PNG)

## Sample APIs

![](https://github.com/jpmorganchase/cakeshop-docs/blob/master/images/api-expanded.png)

### block
* **/block/get**: Retrieve a block by id, number or tag

### contract
* **/contract/compile**: Compile the given source code into EVM binary
* **/contract/create**: Deploy the given contract onto the chain and add it to the Contract Registry
* **/contract/get**: Get information about the contract at the given address
* **/contract/list**: List all deployed contracts on the chain
* **/contract/read**: Read contract data using the given method and arguments (does not create a transaction). Optionally read historical state data by passing a block number in the past.
* **/contract/transact**: Call a transactional method on the given contract. No state will change until the transaction is committed into a Block.

### transaction
* **/transaction/get**: Get transaction information for the given ID

### node
* **/node/get**: Get node information
* **/node/peers**: Retrieve information on the peers connected to the node.
* **/node/start**: Start node
* **/node/stop**: Stop node
* **/node/reset**: Reset the chain to block zero
* **/node/update**: Update node configuration. May cause node to restart or even reset.

