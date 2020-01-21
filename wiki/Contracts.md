***
The **Contracts** explorer lets you see the contracts that have been deployed to your chain using Cakeshop or the Cakeshop APIs. In addition to the contracts themselves, you can view all of their relevant details, including state & transaction history, the current state, the bytecode, ABI & Solidity code.
***

![](https://github.com/jpmorganchase/cakeshop-docs/blob/master/images/contracts.png)

## Widgets & Functionality
### 'Deployed Contract List' widget
<em>Shows the list of contracts that have been deployed to your chain using Cakeshop or the Cakeshop APIs.</em>

![](https://github.com/jpmorganchase/cakeshop-docs/blob/master/images/deployed-contracts-widget.PNG)

* Clicking on the ![detailsButton](https://github.com/jpmorganchase/cakeshop-docs/blob/master/images/details-btn.PNG) button will pop up the ![](Contract|Contracts#contract-widget) widget
* Clicking on the ![paperTapeButton](https://github.com/jpmorganchase/cakeshop-docs/blob/master/images/paperTape-btn.PNG) button will pop up the ![](Paper Tape|Contracts#paper-tape-widget) widget
* Clicking on the ![currentStateButton](https://github.com/jpmorganchase/cakeshop-docs/blob/master/images/currentState-btn.PNG) button will pop up the ![](State|Contracts#state-widget) widget.

***


### 'Contract' widget
<em>Shows the low level details for the relevant contract that you have selected, including the bytecode, ABI & Solidity code.</em>

![](https://github.com/jpmorganchase/cakeshop-docs/blob/master/images/contract-widget.PNG)

* **ID**: Contract Address 
* **Name**: Name of the Contract as defined in the .sol file that was compiled and deployed 

***

### 'Paper Tape' widget 
<em>Shows the history of transactions sent to the contract that you have selected</em>

![](https://github.com/jpmorganchase/cakeshop-docs/blob/master/images/paper-tape-widget.PNG)
![](https://github.com/jpmorganchase/cakeshop-docs/blob/master/images/paperTapeDetail.PNG)

* Clicking the Block Number hyperlink will bring up the Block widget, showing the details of the Block in which the Transaction was committed. 
* Clicking the TXN hyperlink will bring up the Transaction widget, showing the details of Transaction that resulted in the given state. 

***

### 'State' widget
<em>Shows the current state of the relevant contract that you have selected</em>

![](https://github.com/jpmorganchase/cakeshop-docs/blob/master/images/state-widget.PNG)

* **Method**: The list of public variables and methods on the contract
* **Result**: The current state/return results for those variables/methods

***
