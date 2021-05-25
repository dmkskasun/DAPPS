# DAPPS
![Image](Images/ethereum_solidity.jpg)
-----
### Ethereum APIs 
#### Two type of APIs
01.Management APIs
The Managemet API support methods for management of geth node. 
![Image](Images/ethereum_solidity.jpg)

02.Web3 APIS. 
The Web3 APIs support methods for development of Dapps.
![Image](Images/ethereum_solidity.jpg)

#### APIs in detail. 

###01.Admin API

Example: admin.addPeer()
         admin.nodeInfo()

Admin, the Admin API allows you to use functions to work with your Geth instance, including network peer and the RPC endpoint management. Examples, admin.addPeer(), admin.nodeInfo(). In this case, admin is the API, and addPeer and nodeInfo are functions of the admin API. You can observe that admin supports functions for management of the node. Debug API, example, Debug.dumpBlock(16). This will display the block header details of block 16. You can observe that the debug API provides you the ability to peek into the blockchain, study it, and debug any issues by looking at the block.
