* [How do I call contracts or send Transactions to existing contracts?](#faq1)
* [How do I find existing contracts?](#faq2)
* [How do I deploy contracts to my network using Cakeshop?](#faq3)
* [How do I run Cakeshop on any Ethereum build or on my private Ethereum network?](#faq4)
* [How do I run Cakeshop on many nodes?](#faq5)
* [How do I save the solidity files that I have written in the Sandbox?](#faq6)
* [What is an 'Ethereum-like' ledger/node?](#faq7)

***

### <a name="faq1"></a>How do I call contracts or send Transactions to existing contracts?
The [[Sandbox|Sandbox]] provides the ability to load up a contract that has been deployed using Cakeshop or the Cakeshop APIs and to make Read calls or submit Transactions to those contracts.  See the [[Sandbox section|Sandbox]] for further details.

### <a name="faq2"></a> How do I find existing contracts? 
The [[Contracts|Contracts]] explorer lists all public contracts that have been deployed using Cakeshop or the Cakeshop APIs.

### <a name="faq3"></a>How do I deploy contracts to my network using Cakeshop?
The [[Sandbox|Sandbox]] provides the ability to write and deploy contracts onto your chain. See the [[Sandbox section|Sandbox]] for further details.

### <a name="faq4"></a>How do I run Cakeshop on any Ethereum build or on my private Ethereum network?
See the [[Attach Mode|Getting Started#attach-mode]] instructions for using Cakeshop with your Ethereum-like node.  This provides you the ability to start Cakeshop without auto-starting a geth node, and then attach it to your already-running node.

### <a name="faq5"></a> How do I run Cakeshop on many nodes?
See the [[Multi-Instance Setup|Getting Started#multi-instance-setup]] instructions for managing multiple nodes that you control on an Ethereum-based network. 

### <a name="faq6"></a> How do I save the solidity files that I have written in the Sandbox?
You can't explicitly save these files at the moment, but they are auto-saved to your browser cache. For this reason, you shouldn't use Cakeshop as your version management system and you should definitely ensure you save them in a proper VCS outside of Cakeshop.

### <a name="faq7"></a> What is an 'Ethereum-like' ledger/node?
An 'Ethereum-like' ledger/node is one that uses the Ethereum JSON RPC API. The Ethereum clients and [Quorum](https://github.com/jpmorganchase/quorumhttps://github.com/jpmorganchase/quorum) are examples.

<em>Note that if an Ethereum-forked ledger forks too far away from base Ethereum then there may be some issues with using Cakeshop on top of it.</em>
