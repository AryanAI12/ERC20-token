# ERC20-token

# Introduction 
This contract provides the basic functionality of an ERC20 token, including transferring tokens, allowing others to transfer tokens on your behalf (approve), and transferring tokens on behalf of others (transferFrom).

To deploy this contract, you can use Remix IDE or Hardhat. In Remix, you can compile and deploy directly from the browser. In Hardhat, you'll need to set up a project, compile the contract, and deploy it to the Ethereum network.

# Functionality
External Functions:

1.transfer: Allows transferring tokens from the sender's address to another address.

2.approve: Allows approving an address to spend tokens on behalf of the sender.

3.transferFrom: Allows transferring tokens on behalf of another address, given the sender has been approved to do so.

Constructor:

constructor(string memory _name, string memory _symbol, uint8 _decimals, uint256 _initialSupply) {: This is the constructor function which initializes the token with initial parameters.

These functions handle the core functionalities of an ERC20 token: transferring tokens, approving spending, and transferring tokens on behalf of another address. They include various checks to ensure the validity of transactions, such as ensuring sufficient balance and allowance.





