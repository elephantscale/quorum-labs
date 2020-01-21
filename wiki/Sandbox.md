The **Sandbox** provides a Solidity Smart Contract compiler, Solidity IDE and REPL. It allows you to develop Smart Contracts from within Cakeshop, deploy them to your blockchain network and interact with them.

The Sandbox is made up of the **Contract Editor** and the **Sandbox Console**.

![](https://github.com/jpmorganchase/cakeshop-docs/blob/master/images/sandbox-main.png)

## Contract Editor
As expected, the editor is where you write your Solidity Contracts.  You can create new .sol files and view .sol files that are stored in the Cakeshop contract library.

> NOTE: Solidity contracts are currently saved in the browser's local cache.  It is not guaranteed that they will be accessible if you upgrade to a new version of Cakeshop or clear out your browser cache.  You should continue to use standard version management software for your contracts and use Cakeshop primarily as a rapid development environment.

![](https://github.com/jpmorganchase/cakeshop-docs/blob/master/images/sandbox-editor.PNG)

## Sandbox Console

The Sandbox Console provides the ability to deploy contracts, send transactions, view compiler and debug info, access a library of pre-deployed sample contracts and set various Contract Editor settings.

It contains:

* Transaction Playground
* Contract Library
* Compiler Output
* Settings

![](https://github.com/jpmorganchase/cakeshop-docs/blob/master/images/sandbox-menu.png)


### Transaction Playground

<em>The Transaction Playground allows you to deploy your contract code to your network, make calls to contracts and send Transactions to contracts.</em>

![](https://github.com/jpmorganchase/cakeshop-docs/blob/master/images/sandbox-transaction-panel.png)

***

#### Deploying Contracts

To deploy a contract to the network, select the relevant file in the editor and then select the relevant contract within that file from the 'Deploy from Editor' widget. The constructor params will be available to populate.

![](https://github.com/jpmorganchase/cakeshop-docs/blob/master/images/sandbox-deploy2.png)

**private for**: For Quorum nodes, specify the constellation public key(s) of the counterparties you would like the contract to be private for.

> Note: When switching between contract files on the Contract Editor, the 'Or Deploy From Editor' dropdown will be updated to the contract file that is currently in focus.  Wait until the refresh icon (circular arrows) disappears before selecting your contract from the dropdown.  The dropdown will be populated with all of the contracts defined in the given contract file.

***

#### Transacting with Contracts
To send a Transaction to a contract, first choose the contract you are interested in.  To do this you can either:
* Select a contract from the list of deployed contracts
* Provide the address of the contract you want to call/transact with

![](https://github.com/jpmorganchase/cakeshop-docs/blob/master/images/sandbox-choose2.png)

Once a contract has been selected, its methods will be displayed in the **Transact** widget, indicating whether they can be called or transacted with:

![](https://github.com/jpmorganchase/cakeshop-docs/blob/master/images/sanbox-transact.png)

* **From Address**: choose the Ethereum account to make the call/send the Transaction from.
* **Private For**: For Quorum nodes, specify the constellation public key(s) of the counterparties you would like the Transaction to be private for.

***

#### Paper Tape
<em>View the audit trail of transactions sent to a given contract</em>

![](https://github.com/jpmorganchase/cakeshop-docs/blob/master/images/sandbox-paper-tape.png)

* Clear the Paper Tape within the Sandbox by clicking the ![](https://github.com/jpmorganchase/cakeshop-docs/blob/master/images/trashcan.PNG) icon.  This will only clear the local history from the Transaction Playground, nothing will be cleared from the underlying blockchain.

***

### Contract Library
<em> Holds the sample contracts that are deployed with Cakeshop</em>

Selecting a contract from the Contract Library will add it to the Contract Editor.

![](https://github.com/jpmorganchase/cakeshop-docs/blob/master/images/contract-library.PNG)

***

### Compiler Output
<em> Real Time compiler of the code that is currently in-focus in the Contract Editor</em>

![](https://github.com/jpmorganchase/cakeshop-docs/blob/master/images/compiler-output.PNG)

***

### Sandbox Settings
<em>Fine tune certain editor settings</em>

![](https://github.com/jpmorganchase/cakeshop-docs/blob/master/images/sandbox-settings.PNG)
