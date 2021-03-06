# ZBankNet

### Overview
In this repository we will be creating a private Blockchain run on a Proof-of-Authority consensus algorithm for ZBank, a small, innovative bank. As the main developers of the blockchain, it is imperative that it runs successfully and that we leave the correct guide for others to build on it afterwards. 

![ZBankNet_Guide](Screenshots/ZBankNet_Info.png)

The picture above should serve as a guide for accessing the blockchain, as well as the testnet network.

---

### Node Creation & Initialization
We began the process by creating two nodes (node1 & node2) because these are the two nodes that will have access to the blockchain, mine the blockchain, and keep a record of all transactions all simultaneously. In the first picture below, node1 and node2 are being created and given publick keys - which are both provided at the top of this page.


![Node_Setup1](Screenshots/Node_Setup1.png)


Following the setup, we configured the two nodes to both be pre-funded (since there will be no mining reward) and allowed access to the blockchain to mine. Once both nodes were set up, we proceeded to initialize them each which officially adds them to our ZBank blockchain. You can see that both initializations were successful in the image below.

![Node_Setup2](Screenshots/Node_Setup2.png)

---

### Mining Environment Setup

With our next step, we began mining in node1 and in node2 on the Ethereum testnet by using geth. 

![Node1_Mining](Screenshots/Node1_Mining.png)

![Node2_Mining](Screenshots/Node2_Mining.png)

---

### MyCrypto Testing
Once we officially began mining on our blockchain, we created our own custom Network to confirm that it was running successfully. In order to set up our network, it was mandatory that we had our Chain ID saved (can be found at the top of this page) and knew which port to utilize (RPC port 8545). Once the network was setup, we sent ETH from our first node's wallet to the second to make sure they ran successfully. Below you will see that our transaction was successful.

![TX_1](Screenshots/TX_1.png)

![TX_2](Screenshots/TX_2.png)
