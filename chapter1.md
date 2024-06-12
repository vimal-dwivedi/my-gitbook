# 1. Introduction

Kaon.one is a novel blockchain project with the goal to considerably improve decentralized cross-blockchain interactions for asset exchanges. Built on the foundation of the [UniLayer system](https://unilayer.io), the successor Kaon.one system comprises innovative technological innovations to offer a seamless, secure, and efficient system for decentralized applications (dApp). Kaon.one provides cross-blockchain transactions with interoperability capabilities for asset exchanges between different blockchain networks. The core architecture of Kaon.one combines the advantages of Bitcoin's [Unspent Transaction Output](https://coincentral.com/utxo-beginners-explainer/) (UTXO) protocol and the Ethereum Virtual Machine (EVM) models. 

**UTXO Protocol**

To understand the key principles of how Kaon.one performs operations it is important to firstexpand on fundamental principles of how UTXO transactions are carried out versus the Ethereum account model. Briefly, the UTXO protocol is a foundational part of many blockchain systems, including the first usecase of modern blockchain, i.e., Bitcoin. The UTXO protocol denotes the state of a blockchain by tracking unspent transaction outputs that are the remaining portions of a cryptocurency transaction. This unspet transaction output is available as inputs for future transactions.

For carrying out a transaction that involves the UTXO model, a user first selects one or more unspent transaction outputs (UTXOs) in their ownership. Note that the user of, e.g., bitcoin, is not necessarily aware of the background mechanism triggered by a crypto wallet in combination of the decentralised bitcoin blockchain protocol that occurs during a transaction. Thus, the accumulated value of these selected UTXOs must be equal to or greater than the amount a user aims to spend via a crypto payment dApp. Consequently, the user creates the transaction by which the selected input UTXOs are specified. The defined new outputs include the recipient addresses and the amounts to be transferred.

The created UTXO transaction is broadcast to the network that validates the former by checking the signatures and ensuring that the inputs are factually unspent. A valid transaction is consequently propagated through the blockchain protocol and miners include the transaction in a block, which is finally added to the blockchain. At this point, the inputs of the transaction are marked as spent, and the outputs turn into new UTXOs available for the next transactions.

An advantage of the UTXO protocol is the enhanced validation security that is established by explicitly defining the inputs and outputs of respective transactions. Furthermore, the UTXO protocol also established transparency by creating an auditable transaction trail of the asset transfers. Finally, since each respective transaction is independent, the UTXO protocol supports parallel validation. Thus, multiple transactions can be validated and processed simultaneously, which improves scalability.

**Account-Based Model**

[Ethereum](https://www.horizen.io/academy/utxo-vs-account-model/) uses an account model to manage transactions and correspondign states on the blockchain. This account model differs from Bitcoin's UTXO model and supports Ethereum's functionalities such as smart contracts. Two types of accounts exist in the Ethereum account model, namely externally owned accounts (EOAs) and contract accounts. The former are controlled by private keys and can initiate transactions, while the latter are governed by smart contract code that is executed when they receive transactions. Each account has a unique address, which serves as a unique identifier on the blockchain.

In the account-based model, a user initiates a transaction in which the amount of ETH is specified that must be transferred. Additionally delivered are the recipient's account address, and optionally, data to trigger specific contract functions. The sender's private key is used to sign a transaction, which clarifies the authenticity and ensures security. The transaction itself is validated by the nodes after being broadcast to network. The nodes check the signature, also check if the sender has enough ETH to pay the transaction fee, and update the state of both the sender's and recipient's accounts.

The account model also has several advantages. First, this is a fairly simple and efficient model for the execution of smart contracts.  Second, the account model allows for direct state updates and thereby simplifies contract executions and state management. Additionally, the account model supports the concept of gas being a unit to measure the computational operations-execution effort. Gas fees are paid in ETH and incentivce the miners to include transactions in blocks. Gas is also a mechanism that prevents the abuse of computational resources on the Ethereum network.

**Decentralized Finance (DeFi)**

Blockchain technologies are used to create a parallel emerging financial system as an improved decantralized versus versus the traditional legacy financial system. [DeFi](https://aws.amazon.com/blockchain/what-is-defi/) aims to eliminate the need for trusted third-party intermediaries such as banks, brokers, and exchanges. Instead, DeFi provides peer-to-peer (P2P) financial services that are accessible to anyone with an internet connection. Allegorically expressed, while legacy finance takes over the control of the customers' private keys in a centralized business model, DeFi gives the private keys back to the customers into their respective control. 

## 1.1 Overview of Kaon.one

As stated above, the primary goal of Kaon.one is to considerably improve and extend decentralized cross-blockchain interactions, which enables seamless asset exchanges across diverse blockchain networks. <!-- Thereby, Kaon.one addresses the inherent limitations of existing blockchain solutions by integrating unique technological advancements designed to improve security, efficiency, and scalability. -->
Thus, Kaon.one combines in a specific way the strengths of the UTXO protocol and the Ethereum account-based model. This hybrid architecture leverages the UTXO model's enhanced security and parallel validation capabilities with the account-based models smart contract functionalities. Consequently, Kaon.one offers a versatile platform that supports complex decentralized dApps with cross-blockchainchain interaction capabilities.

<p align="center">
  <img src="images/Kaon_architecture.png" alt="Kaon.one Architecture" width="600">
</p>

Kaon.one's architecture is specifically designed to facilitate interoperability, allowing assets to move seamlessly between different blockchain networks. This capability is vital for the growing ecosystem of decentralized finance (DeFi) applications. In such DeFi ecosystems, cross-blockchain asset transfers are increasingly common. Additionally, Kaon.one's integration of advanced features such as mirrorBTC, UTXO-EMV combination, and cross-contract functionality further solidifies its position as a leader in the blockchain innovation space.

The platform's commitment to providing a user-friendly and secure environment is evident in its design. By ensuring that each transaction is transparent and auditable, Kaon.one enhances trust among users and stakeholders. Furthermore, its ability to handle multiple transactions in parallel not only improves scalability but also ensures that the system can accommodate a growing number of users and transactions without compromising performance.


## 1.2 Rebranding from UniLayer to Kaon.one


## 1.3 Objectives and Vision


## 1.4 Innovations of Kaon.one