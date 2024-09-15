RGB++ Layer: Pioneering a New Era for the Bitcoin Ecosystem

RGB++ Layer, now an upgraded concept from the RGB++ protocol, represents a further abstraction into an inclusive layer that extends isomorphic binding, smart contract capabilities, and bridgeless cross-chain functionality to all UTXO chains. With RGB++ Layer, the Bitcoin ecosystem is bound to become significantly enriched. Particularly, the rise of Bitcoin Finance (BTCFi), driven by RGB++ Layer, will usher the Bitcoin ecosystem into a new era of prosperity.

RGB++ Layer performs multiple functions, bringing numerous exceptional features to the Bitcoin ecosystem. Its significance can be explained from the following three aspects:

RGB++ Layer is Bitcoin’s asset issuance layer.

RGB++ Layer is Bitcoin’s smart contract layer.

RGB++ Layer is the interoperability layer of the entire UTXO world.


Bitcoin’s asset issuance layer
The current asset issuance protocols on the Bitcoin chain, like Ordinals or BRC20, are far from well-designed and heavily reliant on centralized indexers. Unlike any previous solutions, RGB++ Layer can serve as a powerful asset issuance layer for Bitcoin.

RGB++ Layer supports the issuance of various RGB++ assets, including User Defined Token (UDT) equivalent to ERC20, and Digital Object (DOB) equivalent to ERC721. Different from Ethereum, where ERC20 and ERC721 are issued and stored by smart contract accounts, UDT and DOB are stored in Turing-complete UTXOs, meaning that they are first-class assets on RGB++ Layer, on par with Ether on Ethereum.

Thanks to the advantages of the UTXO model, RGB++ Layer can create a new paradigm for asset issuance — allowing the same asset to be issued on multiple chains simultaneously, with different proportions issued on each chain. This will provide asset issuers with a high degree of flexibility. When a project team issues a token, they don’t have to worry about losing users from one chain by issuing on another. Instead, they can issue a portion on BTC, a portion on BCH, and even a portion on the Dogecoin chain, extending their influence to the communities of all UTXO chains.

Furthermore, RGB++ Layer will introduce a brand new asset issuing model called Initial Bitcoin Offering (IBO). This can be understood as a launchpad for all RGB++ assets. The IBO platform supports directly creating pools on UTXOSwap, a UTXO-based decentralized exchange, allowing newly issued assets to be traded with high liquidity. The IBO issuance method strikes a balance between the VC model and the Fair Launch model, offering a more sustainable way. It avoids the problem of lack of community interest while also ensuring that the project team remains motivated.

Bitcoin’s smart contract layer
The RGB++ Layer leverages the smart contract stack of CKB to provide Bitcoin with Turing-complete programmability. With smart contracts, the Bitcoin ecosystem can build a variety of DeFi protocols, creating a unique Bitcoin Finance (BTCFi) landscape.

For example, UTXOSwap, a decentralized exchange (DEX) protocol, serve as the central hub of RGB++ Layer to aggregate the liquidity of various UTXO chains. UTXOSwap adopts intent-based trading as its core and implements an off-chain matching and on-chain verification process, leveraging the parallelism nature of UTXO to improve transaction efficiency.

If you think it’s just a Uniswap for the Bitcoin ecosystem, then you’re mistaken. In addition to standard swaps, UTXOSwap also supports limit order and Time-Weighted Average Price (TWAP) transactions because it is intent-based. For instance, users can actively express their trading intents, such as “exchange 10 A tokens for at least 20 B tokens”, instead of passively accepting the market price.

Another example is Stable++, a decentralized, over-collateralized stablecoin protocol. It issues $RUSD, the first stablecoin on RGB++ Layer. Stable++ build over-collateralized vaults and liquidation modules efficiently with the powerful Turing-complete programability of RGB++ Layer. As a user, you can collateralize $BTC or $CKB and mint $USDPP, a stablecoin compatible with all UTXO chains. You can circulate it freely within the Bitcoin ecosystem.

Overall, the atomicity of the UTXO model enables UTXOs to function like Legos, allowing assets from different chains to interact and integrate, thereby spurring more DeFi innovation. This will foster the development of BTCFi, benefiting the entire Bitcoin ecosystem.

The interoperability layer of the UTXO world
RGB++ Layer serves as an inclusive layer that can connect with all UTXO chains, creating a universal interoperability layer of the entire UTXO world. This allows various assets from UTXO chains like Cardano, Dogecoin, BSV, and BCH to seamlessly integrate into the Bitcoin ecosystem, breaking down asset silos.

The unparalleled feature of RGB++ Layer is Bridgeless Cross-chain Leap. This mechanism enables an asset on a UTXO chain to leap to another UTXO chain without bridges. For example, if Alice wants to transfer her RGB++ asset from the Bitcoin chain to the Litecoin chain, she first needs to spend the corresponding Bitcoin UTXO bound to her RGB++ asset. Then, a transaction should be constructed on RGB++ Layer to change the unlocking condition of the Turing-complete UTXO to her Litecoin UTXO. In this way, the leap from the Bitcoin chain to the Litecoin chain is successful.

With this feature available, technically all RGB++ assets can be regarded as universal assets of the entire UTXO world because there are no longer barriers between chains, allowing assets to move freely.

Imagine this: you can use A token issued on the BTC chain and exchange it for B token on the Cardano chain through a decentralized exchange. You can use a meme coin from the Dogecoin chain to play GameFi on a Bitcoin Layer 2 DApp chain. You can use a DOB from the CKB chain to subscribe to services on Nostr, and more. This elevates the interoperability of RGB++ assets within the UTXO world to unprecedented heights.

Vision for the future
Looking ahead, the Bitcoin ecosystem will be connected into a cohesive whole because of RGB++ Layer. Various UTXO-based assets, including inscriptions and runes, will flow seamlessly on RGB++ Layer, significantly enhancing the liquidity of the Bitcoin ecosystem. Innovations in BTCFi protocols such as decentralized trading, lending, and farming based on UTXO model will continually emerge. Ultimately, BTCFi will flourish, leading the Bitcoin ecosystem into a new era of prosperity.

# Fiber Network: A Lightning Network Based on CKB

## Overview

Fiber Network is a next-generation, common lightning network built on Nervos CKB and off-chain channels. It is designed to provide fast, low-cost, and decentralized multi-token payments and peer-to-peer transactions for RGB++ assets.

## Background

### Evolution and Challenges of Blockchain Technology

Blockchain technology has undergone rapid evolution since the inception of Bitcoin. Initially designed for simple payments, it has gradually expanded into various domains such as smart contracts, decentralized finance (DeFi), and non-fungible tokens (NFTs). Despite its significant advantages in security, transparency, and decentralization, blockchain technology faces several challenges in scalability and transaction speed.

1. Scalability. Traditional blockchains like Bitcoin and Ethereum face significant bottlenecks in transaction throughput. Due to Bitcoin's block size limit and 10-minute block generation time, its network can only process about 7 transactions per second; Ethereum, despite improvements, still has a transaction processing capacity far below traditional payment networks.

2. High transaction fees. As network congestion increases, transaction fees rise significantly. For instance, gas fees on the Ethereum network during peak times may exceed the transaction amount itself, severely affecting user experience and reducing the feasibility of micropayments.

3. Long transaction confirmation times. In traditional blockchain networks, transactions need to wait for multiple block confirmations to be considered final. This process can take minutes to hours, making it unsuitable for instant payment scenarios.

Although Nervos CKB has made improvements in terms of performance and confirmation times, it still needs to further increase transaction speed and reduce transaction costs to meet the demands of micropayments and instant payments.


### Inspiration from the Lightning Network

The Lightning Network, a layer 2 scaling solution for the Bitcoin network, has successfully achieved fast, low-cost micropayments through off-chain transactions and payment channels. Its core concepts include:

1. Payment channels: Users create payment channels on-chain. Once a channel is opened, both parties can conduct unlimited off-chain transactions, only settling on-chain when the channel is closed. This significantly reduces the number of on-chain transactions, improves transaction speed, and lowers transaction fees.

2. Hash Time-Locked Contracts (HTLC): Through HTLCs, the Lightning Network ensures secure fund transfers, mitigating counterparty risk. Even if off-chain transactions fail, users can still secure their funds through on-chain contracts.

3. Routing mechanism: The Lightning Network uses multi-hop routing, allowing users to complete payments without opening direct channels with recipients, thus enhancing network flexibility and usability.


## Advantages of Nervos CKB

Nervos CKB is a blockchain platform focused on versatility and security. Its unique design offers distinct advantages in addressing blockchain scalability and interoperability issues:

1. Consensus mechanism: Based on the [NC-Max](https://eprint.iacr.org/2020/1101) consensus protocol, it combines Proof of Work (PoW) with state rent mechanisms, ensuring network security and effective resource utilization.

2. Powerful smart contract capabilities: CKB's unique Cell model and RISC-V instruction set virtual machine significantly enhance the capabilities of the UTXO model. This not only supports Turing-complete smart contracts but also easily implements features such as account abstraction and covenants, providing more flexible programmability, better interoperability, and scalability for decentralized applications.

3. Tokenomics: CKB's tokenomics encourages long-term holding and rational use of network resources, providing a secure and sustainable decentralized environment for applications, developers, and users.

## Significance of the Fiber Network Project

By building off-chain channels on Nervos CKB, we aim to combine the successful experience of the Lightning Network with CKB's technical advantages to create a fast, low-cost, and decentralized multi-asset real-time payment network. Specifically:

1. Solving scalability issues: Through off-chain payment channels and multi-hop routing, Fiber Network can achieve high-throughput transaction processing, meeting the needs of large-scale users.

2. Reducing transaction costs: By reducing the frequency of on-chain transactions, it lowers transaction fees, making micropayments feasible and efficient.

3. Improving transaction speed: The instant confirmation of off-chain transactions provides a split second payment confirmation experience suitable for various instant payment scenarios.

4. Multi-asset support: Fiber Network supports payments in a variety of digital assets, offering users a broader range of payment options.

5. Interoperability: Fiber Network supports interoperability with the Bitcoin Lightning Network, providing support for cross-chain payments and asset transfers.


## Architecture Design

### Overall Architecture

The overall architecture of Fiber Network includes the following core modules:

1. Off-Chain Payment Channels (Fiber Channels)

2. On-Chain Contracts (HTLC)

3. Multi-Hop Routing

4. Watchtower Service

### Off-chain Payment Channels

Off-chain payment channels are the core of Fiber Network, enabling multiple off-chain transactions with on-chain settlement only when the channel is closed. This mechanism significantly reduces the number of on-chain transactions, improves transaction speed, and lowers transaction fees.
The general workflow is as follows:

1. Opening a Channel: Two parties open a payment channel on-chain, locking a certain amount of CKB or RGB++ assets.

2. Off-chain transactions: When the channel is open, both parties can conduct an unlimited number of off-chain transactions, updating the channel state with each transaction without immediate broadcasting to the chain.

3. Closing the Channel: When either party decides to close the channel, the final channel state is broadcasted on-chain for settlement, ensuring the final balances of both parties are confirmed.

The message interaction format can be referenced in the [Fiber Network P2P Message Protocol](./specs/p2p-message.md).

### On-Chain Contracts

Currently, we use Hash Time-Locked Contracts (HTLC) to ensure the security of off-chain transactions and maintain compatibility with the Lightning Network. This mitigates counterparty risk, ensuring that even if off-chain transactions fail, users can still secure their funds through on-chain contracts.

The general workflow is as follows:

1. Transaction initiation: The payment initiator creates a transaction with hashlock and timelock, and locks a certain amount of CKB.

2. Hash verification: The payment recipient must provide the correct hash preimage within the specified time to unlock the transaction and complete the fund transfer.

3. Timeout refund: If the recipient fails to provide the correct hash preimage within the specified time, the transaction will automatically unlock and refund to the payment initiator.

Thanks to CKB's Turing completeness, we can implement more flexible and secure on-chain contracts. We will further expand the contract's functionality in the future, such as introducing a version-based revocation mechanism and more secure Point Time-Locked Contracts.

### Multi-hop Routing

Multi-hop routing allows users to complete payments through multiple intermediate nodes without establishing direct payment channels with the counterparty. This mechanism enhances the network's flexibility and coverage.

The general workflow is as follows:

1. Path discovery: The payment initiator discovers the optimal path from themselves to the payment recipient through the routing module.

2. Path locking: Each node on the path creates corresponding HTLC contracts, ensuring secure fund transfers.

3. Payment completion: The payment recipient unlocks the HTLC, and funds are transferred sequentially to each node on the path.

We will also implement cross-chain payments here using HTLC contracts, supporting interoperability with the Lightning Network through the cross-chain hub service. For more details, please refer to [Payment Channel Cross-Chain Protocol with HTLC](./specs/cross-chain-htlc.md).

### Watchtower Service

The watchtower service is an essential component of Fiber Network, responsible for monitoring the state of off-chain payment channels and ensuring the security of channels and funds. Its functions and roles are as follows:

1. Channel monitoring: Real-time monitoring of the payment channel state of all participating users, including opening, updating, and closing channels.

2. Anomaly detection: Detecting abnormal activities in channels, such as malicious users attempting to close channels with old states or double-spending attacks.

3. Proactive response: When anomalies are detected, promptly broadcasting the latest channel state to the blockchain network to prevent fund losses due to malicious behavior.

## Current Progress and Future Plans

We have currently completed a prototype of Fiber Network, implementing basic functions of opening, updating, and closing channels between two nodes, and also verifying cross-chain functionality with the Bitcoin Lightning Network. The project code can be found in the following GitHub repositories:

1. https://github.com/nervosnetwork/fiber

2. https://github.com/nervosnetwork/fiber-scripts

Our next steps include completing multi-hop routing and watchtower services, as well as improving the RPC interface and SDK to facilitate easier access for developers to Fiber Network.

The multi-hop routing protocol is based on the Dijkstra algorithm to search for payment paths, thereby reducing routing fees and improving the success rate of multi-hop path payments. After Fiber Network goes live, we will optimize the routing algorithm based on network traffic and operational conditions. We expect to provide 2 or 3 path search strategies to adapt to users' different routing preferences and needs. Fiber Network will also introduce multi-path payment strategies, dividing larger payment amounts into multiple parts, each transmitted through different paths, further increasing the probability of successful payments.

The watchtower service will be provided by some nodes in Fiber Network. These nodes will stay online, monitor abnormal situations in the network, and help protect assets in channels. The monitoring service will also track the cross-chain hub service. Even if users are offline for a period, the monitoring service can ensure successful exchanges with the Lightning Network.

Additionally, we will consider adding more features to Fiber Network, such as implementing privacy protection algorithms leveraging CKB's programmability, and based on this, optimizing routing algorithms and watchtower services to enhance the security and privacy of users’ payment information.

# Payment Channel Cross-Chain Protocol with HTLC

## Synopsis

In the rapidly evolving world of blockchain technology, interoperability between different networks is becoming increasingly crucial. One of the most promising solutions to this challenge is the use of payment channel cross-chain protocols based on Hash Time-Locked Contracts (HTLCs). This post will delve into how HTLCs can be used to ensure atomic payments across different blockchain networks using the same preimage.

## What is HTLC?

Hash Time-Locked Contracts (HTLCs) are a type of smart contract used to facilitate conditional payments. They are designed to ensure that a transaction is either completed within a specified timeframe or canceled. The key components of an HTLC are:

1. **Hashlock**: A cryptographic hash of a secret (preimage) that must be revealed to complete the transaction.
2. **Timelock**: A time constraint that ensures the transaction is either completed within a certain period or reverted.

## Cross-Chain Payments with HTLC

Cross-chain payments involve transferring value across different blockchain networks, which can be difficult due to the absence of direct interoperability. To address this challenge, Hashed Time Lock Contracts (HTLCs) offer a solution by facilitating atomic swaps. These swaps guarantee that transactions are either executed in full or not at all, eliminating the possibility of partial transfers.

To ensure stability in cross-chain payments, the assets utilized in different blockchain networks must maintain a fixed swap ratio. For instance, the Bitcoin payment channel exclusively supports BTC. Meanwhile, CKB can incorporate a wrapped BTC token via the UDT channel, establishing a consistent 1:1 ratio with Bitcoin.

Another requirement is that the two networks must use the same hash algorithm for HTLCs.

## Specification

The protocol has three actors:

- Alice in the Blockchain A who wants to send funds to Bob.
- Bob in the Blockchain B who wants to receive funds from Alice.
- Ingrid is the cross-chain hub service provider who runs the payment channel nodes for both Blockchain A and Blockchain B.

To understand how HTLCs can be used for cross-chain payments, let's break down the process:

1. **Negotiating**:
   - Bob wants to receive $N_b$ amount of asset $T_b$ in the Blockchain B.
   - Alice negotiates with Ingrid that if Alice pays $N_a$ amount of asset $T_a$ in the Blockchain A to Ingrid, Ingrid will send $N_b$ amount of asset $T_b$ to Bob in the Blockchain B.

2. **Offering HTLCs**:
   - Alice offers an HTLC with $N_a$ amount of $T_a$ on Blockchain A to Ingrid, locking her funds with a hashlock and a timelock. The hashlock is derived from a secret preimage $S$ that only Bob knows.
   - Ingrid, upon receiving the hashlock from Alice, creates a corresponding HTLC on Blockchain B with $N_b$ amount of $T_b$, locking his funds with the same hashlock and a timelock.

3. **Revealing the Preimage**:
   - To claim the funds on Blockchain B, Bob must reveal the preimage to Ingrid.
   - Once Ingrid has the preimage, he can use it to unlock the funds on Blockchain A.
   - Both transactions are completed atomically, meaning either both are completed, or neither is.

## Example Between Bitcoin and CKB

### Setup

- Alice is in the Blockchain CKB and runs a FNN (Fiber Network Node).
- Bob is in the Blockchain Bitcoin and runs any BOLT compatible lightning node.
- Ingrid is the cross-chain hub service provider who runs both a FNN in CKB and a BOLT lighting node in Bitcoin.
- The asset used in Blockchain Bitcoin ($T_b$) is BTC.
- Ingrid configures a UDT asset $T_a$ in CKB as the wrapped BTC.

### From CKB to Bitcoin

- Bob wants to receive $X$ BTC in Bitcoin.
- Alice negotiates the swap with Ingrid that if Alice sends $X+F$ wrapped BTC in CKB to Ingrid, Ingrid with send $X$ BTC in Bitcoin to Bob. Ingrid will keep $F$ BTC as the fee.

### From Bitcoin to CKB

- Alice wants to receive $X$ wrapped BTC in CKB.
- Alice negotiates the swap with Ingrid that if Bob sends $X+F$ BTC in Bitcoin to Ingrid, Ingrid with send $X$ wrapped BTC in CKB to Alice. Ingrid will keep $F$ wrapped BTC as the fee.

## Benefits of Using HTLC for Cross-Chain Payments

1. **Security**: The use of cryptographic hash functions ensures that the transactions are secure and tamper-proof.
2. **Atomicity**: The all-or-nothing nature of HTLCs ensures that funds are not lost or stuck in limbo.
3. **Interoperability**: HTLCs enable seamless value transfer between different blockchain networks without the need for a trusted third party.
4. **Compatibility**: The HTLC cross-chain protocol can seamlessly integrate with the existing Bitcoin payment channel network without requiring any modifications.

## Future Works

While HTLCs have proven to be a valuable tool for enabling secure cross-chain payments, future research is exploring the potential of Point Time-Locked Contracts (PTLCs) as an improvement over the current HTLC design. PTLCs replace the hash function used in HTLCs with a public key cryptography scheme, offering several advantages:

- Improved privacy: PTLCs hide the payment hash, making it more difficult for observers to link payments across different hops in the network.
- Reduced on-chain footprint: By using adaptor signatures, PTLCs can reduce the amount of data that needs to be stored on-chain, leading to lower transaction fees and improved scalability.
- Enhanced security: PTLCs are less vulnerable to certain types of attacks, such as the wormhole attack, which can be used to steal funds in HTLC-based payment channels.

Migrating from HTLCs to PTLCs could potentially unlock new possibilities for cross-chain protocols, enabling more private, efficient, and secure value transfer across different blockchain networks. As the technology matures and wildly adopted in Bitcoin, it is likely that more projects will explore the use of PTLCs to enhance their cross-chain payment capabilities and drive further innovation in the blockchain ecosystem.

# Fiber Network P2P Message Protocol

This document describes the protocol between nodes of the fiber network on CKB, used to establish payment channels, construct transactions, close channels, and perform payment operations. Essentially, it is an adaptation and simplification of [BOLT 02] to suit the transaction structure of CKB.

Please note that BOLT 02 uses HTLC (Hashed Time Locked Contract) for payment operations, and many message definitions use HTLC as field names and descriptions. In this document, we will use TLC instead of HTLC to facilitate future support for PTLC (Point Time Locked Contract). Additionally, this protocol will use [Molecule] to define message formats, making it easier to integrate with CKB.

***This document is a work in progress and may be updated at any time.***

## Channel Establishment

We use a protocol similar to BOLTS 02 Channel Establishment v2 to establish payment channels, an example process is as follows:

```
    +-------+                              +-------+
    |       |--(1)--- OpenChannel     ---->|       |
    |       |<-(2)--- AcceptChannel   -----|       |
    |       |                              |       |
--->|       |      <tx collaboration>      |       |
|   |       |                              |       |
|   |       |--(3)--  commitment_signed -->|       |
|   |       |<-(4)--  commitment_signed ---|       |
|   |   A   |                              |   B   |
|   |       |<-(5)--  tx_signatures -------|       |
|   |       |--(6)--  tx_signatures ------>|       |
|   |       |                              |       |
|   |       |--(a)--- tx_init_rbf -------->|       |
----|       |<-(b)--- tx_ack_rbf ----------|       |
    |       |                              |       |
    |       |    <tx rbf collaboration>    |       |
    |       |                              |       |
    |       |--(c)--  commitment_signed -->|       |
    |       |<-(d)--  commitment_signed ---|       |
    |       |                              |       |
    |       |<-(e)--  tx_signatures -------|       |
    |       |--(f)--  tx_signatures ------>|       |
    |       |                              |       |
    |       |--(7)--- channel_ready  ----->|       |
    |       |<-(8)--- channel_ready  ------|       |
    +-------+                              +-------+

    - where node A is *opener*/*initiator* and node B is
      *accepter*/*non-initiator*
```
### OpenChannel

`OpenChannel` is sent by the initiator of the channel to the receiver of the channel to request the establishment of a payment channel.

```
table OpenChannel {
    chain_hash:                  Byte32,
    channel_id:                  Byte32,
    funding_type_script:         ScriptOpt,
    funding_amount:              Uint128,
    funding_fee_rate:            Uint64,
    commitment_fee_rate:         Uint64,
    max_tlc_value_in_flight:     Uint128,
    max_num_of_accept_tlcs:      Uint64,
    min_tlc_value:               Uint128,
    to_self_delay:               Uint64,
    funding_pubkey:              Byte33,
    revocation_basepoint:        Byte33,
    payment_basepoint:           Byte33,
    delayed_payment_basepoint:   Byte33,
    first_per_commitment_point:  Byte33,
    second_per_commitment_point: Byte33,
    next_local_nonce:            Byte66,
    channel_flags:               Byte,
}
```

- chain_hash: Chain genesis block hash
- channel_id: The ID of the channel, which is a temporary ID derived from the revocation_basepoint before the channel is officially established. After the channel is established, it will be replaced with the actual channel ID, derived from a blake2b hash of the sorted revocation_basepoints of both parties.
- funding_type_script: Specifies the asset type of the channel. If empty, it indicates using CKB native token as the asset.
- funding_amount: The amount of assets the channel initiator wants to contribute.
- funding_fee_rate: Funding transaction fee rate, in shannons per kilo-bytes.
- commitment_fee_rate: Commitment transaction fee rate, in shannons per kilo-bytes.
- max_tlc_value_in_flight: The maximum total value of unconfirmed TLCs (Time Locked Contracts) that the channel initiator can accept in this channel.
- max_num_of_accept_tlcs: The maximum number of unconfirmed TLCs that the channel initiator can accept in this channel.
- min_tlc_value: The minimum value of TLCs that the channel initiator can accept.
- to_self_delay: The delay time for the channel initiator to unlock the outputs from the commitment transaction, in EpochNumberWithFraction.
- funding_pubkey: The pubkey of the channel initiator, used for generating 2-2 multisig contracts.
- revocation_basepoint: See further description below.
- payment_basepoint:
- delayed_payment_basepoint:
- first_per_commitment_point:
- second_per_commitment_point:
- next_local_nonce: Used for generating partial signatures for unlocking 2-2 Schnorr multisig.
- channel_flags: Channel flags, currently only using one bit to indicate whether to broadcast this channel information on the P2P network.

The xxx_basepoints here are master keys used to derive child keys required for different types of transactions. For example, they can be used with per_commitment_point to derive commitment transactions keys. We will use the same method as lightning network to derive these keys, see [Secret Derivations] for more details.

### AcceptChannel

`AcceptChannel` is sent by the receiver of the channel to the initiator of the channel to accept the establishment of a payment channel.

```
table AcceptChannel {
    channel_id:                  Byte32,
    funding_amount:              Uint128,
    max_tlc_value_in_flight:     Uint128,
    max_num_of_accept_tlcs:      Uint64,
    min_tlc_value:               Uint128,
    to_self_delay:               Uint64,
    funding_pubkey:              Byte33,
    revocation_basepoint:        Byte33,
    payment_basepoint:           Byte33,
    delayed_payment_basepoint:   Byte33,
    first_per_commitment_point:  Byte33,
    second_per_commitment_point: Byte33,
    next_local_nonce:            Byte66,
}
```

- channel_id: The ID of the channel, must match the channel_id in OpenChannel.
- funding_amount: The amount of assets the channel receiver wants to contribute, can be 0, indicating no contribution.
- max_tlc_value_in_flight: The maximum total value of unconfirmed TLCs that the channel receiver can accept in this channel.
- max_num_of_accept_tlcs: The maximum number of unconfirmed TLCs that the channel receiver can accept in this channel.
- min_tlc_value: The minimum value of TLCs that the channel receiver can accept.
- to_self_delay: The delay time for the channel receiver to unlock the outputs from the commitment transaction, in EpochNumberWithFraction.
- funding_pubkey: The pubkey of the channel receiver, used for generating 2-2 multisig contracts.
- revocation_basepoint: See the description in `OpenChannel` message.
- payment_basepoint:
- delayed_payment_basepoint:
- tlc_basepoint:
- first_per_commitment_point:
- second_per_commitment_point:
- next_local_nonce: Used for generating partial signatures for unlocking 2-2 Schnorr multisig.

### CommitmentSigned

After both parties establish the funding transaction and complete the signing of the commitment transaction in the [Transaction Collaboration](#Transaction-Collaboration) process, they will send CommitmentSigned messages to each other.

```
table CommitmentSigned {
    channel_id:        Byte32,
    partial_signature: Byte32,
    next_local_nonce:  Byte66,
}
```

The meaning of each field is as follows:

- partial_signature: The partial signature for unlocking the 2-2 Schnorr multisig.
- next_local_nonce: Used for generating the next commitment transaction partial signature.

### TxSignatures

After both parties have signed the commitment transaction and verified the correctness of each other's signatures, they need to send TxSignatures messages to each other to complete the signing of the funding transaction.

```
table TxSignatures {
    channel_id: Byte32,
    tx_hash:    Byte32,
    witnesses:  BytesVec,
}
```

Here, tx_hash is the hash of the corresponding funding transaction, and witnesses corresponds to the signed witnesses of all inputs of the contributor. If a party's contribution is 0 (i.e., no inputs), an empty witnesses message should also be sent to complete the message exchange.

In addition, in order to simplify the message interaction process, we defined that the party with the lesser amount of funding must send the
TxSignatures message first, in the case of the same amount, the one with the smaller funding_pubkey must send the TxSignatures message first. This avoids deadlocks caused by both parties waiting for the other party's TxSignatures message at the same time.

### ChannelReady

After completing the signing and broadcasting the funding transaction, both parties send ChannelReady messages to each other to indicate the channel is ready.

```
table ChannelReady {
    channel_id: Byte32,
}
```

## Transaction Collaboration

In the fiber network, the channel initiator begins the transaction construction protocol using the TxUpdate message. The responder replies with either TxUpdate or TxComplete messages. The transaction construction process is completed when both nodes have sent and received consecutive TxComplete messages.

Here is the `Dual Funding` example, A initially funds part of the channel (2 inputs), then B adds their contribution (1 input). A replies with TxComplete, and B responds with TxComplete, completing the transaction construction process.

```
    +-------+                       +-------+
    |       |--(1)- tx_update   --->|       |
    |       |<-(2)- tx_update   ----|       |
    |   A   |--(3)- tx_complete --->|   B   |
    |       |<-(4)- tx_complete ----|       |
    +-------+                       +-------+
```

Since CKB's transaction structure is more complex than Bitcoin's, the message structure is simplified compared to BOLT 02 interactive transaction construction. We use the full CKB transaction structure for transaction collaboration, without defining separate messages like tx_add_input, tx_add_output, tx_remove_input, and tx_remove_output. Nodes are required to parse the inputs of the transactions and do not need to provide previous tx in the messages. The specific message definitions are as follows:

### TxUpdate

The TxUpdate message is used by the channel initiator to start the transaction construction protocol.

```
table TxUpdate {
    channel_id: Byte32,
    tx:         Transaction,
}
```

Both parties must save the funding tx field of the previous message to compare it with the latest message field. They must also mark which inputs/outputs belong to their side. If a TxUpdate message from the other party removes or modifies inputs/outputs from their side, it is considered an illegal operation, and the entire process should be terminated.

### TxComplete

After successfully exchanging TxComplete messages, both parties should have constructed the transaction and move to the next part of the protocol to exchange signatures for the commitment transaction.


```
table TxComplete {
    channel_id: Byte32,
}
```

### TxAbort

During the transaction collaboration process, a node can send a TxAbort message to terminate the collaboration before sending the TxSignatures message.

```
table TxAbort {
    channel_id: Byte32,
    message:    Bytes,
}
```

### TxInitRbf

After broadcasting the funding transaction, if the channel initiator finds that the fee is insufficient, they can send a TxInitRbf message to request the other party's cooperation in performing RBF (Replace-By-Fee) operation to increase the fee and rebroadcast the funding transaction.

```
table TxInitRBF {
    channel_id: Byte32,
    fee_rate:   Uint64,
}
```

### TxAckRbf

Upon receiving a TxInitRbf message, the channel responder can send a TxAckRbf message to agree to the RBF operation.

```
table TxAckRBF {
    channel_id: Byte32,
}
```

After receiving the TxAckRbf message from the other party, the channel initiator can restart the process of funding transaction collaboration with the new fee rate. It should be noted that the new funding transaction must have overlapping inputs with the previous funding transaction to ensure it meets the RBF rules.

## Channel Closing

Nodes can negotiate to close a channel mutually, unlike a unilateral close, which allows nodes to immediately obtain funds. The process of closing a channel is as follows:

```
    +-------+                             +-------+
    |       |--(1)- shutdown           -->|       |
    |       |<-(2)- shutdown           ---|       |
    |   A   | <complete all pending TLCs> |   B   |
    |       |<-(3)- closing_signed     ---|       |
    |       |--(4)- closing_signed     -->|       |
    +-------+                             +-------+
```

### Shutdown

Any node can send a Shutdown message to request the closure of the channel.

```
table Shutdown {
    channel_id:   Byte32,
    close_script: Script,
    fee_rate:     Uint64,
}
```

The close_script specifies the lock script to which the assets will be sent when the channel is closed.

### ClosingSigned

After completing all pending Time Locked Contracts (TLCs) in the channel, either party can send a ClosingSigned message to sign the close transaction.

```
table ClosingSigned {
    channel_id:         Byte32,
    partial_signature:  Byte32,
}
```

If the receiver verified the correctness of the signature, they will respond with a ClosingSigned message, completing the channel closure.

## Payment Operation

After establishing a channel, nodes can perform payment operations by sending AddTlc messages for payment requests and then updating the commitment transactions through CommitmentSigned and RevokeAndAck messages. Here is an example process:

```
    +-------+                               +-------+
    |       |--(1)---- add_tlc         ---->|       |
    |       |                               |       |
    |       |--(2)---- commitment_signed -->|       |
    |       |<-(3)---- revoke_and_ack  -----|       |
    |   A   |                               |   B   |
    |       |<-(4)---- remove_tlc      -----|       |
    |       |                               |       |
    |       |<-(5)---- commitment_signed ---|       |
    |       |--(6)---- revoke_and_ack  ---->|       |
    +-------+                               +-------+
```

### AddTlc

Either node can send an AddTlc message to the other party to initiate a payment operation. This message can also be used to forward payment requests from other nodes.

```
table AddTlc {
    channel_id:     Byte32,
    tlc_id:         Uint64,
    amount:         Uint128,
    payment_hash:   Byte32,
    expiry:         Uint64,
}
```

- channel_id: ID of the channel.
- tlc_id: ID of the TLC (Time Locked Contract), used to uniquely identify a TLC. The first TLC in the channel has an ID of 0, and subsequent IDs increment by 1.
- amount: Amount of assets requested for payment.
- payment_hash: Hash value used to identify the payment request for subsequent payment verification.
- expiry: Expiry time of the payment request, specified as an absolute timestamp. When forwarding a payment request, this field should be decremented appropriately.

## RevokeAndAck

Upon receiving the CommitmentSigned message and verifying the signature, the node may reveal the previous commitment transaction secret to the other party by sending a RevokeAndAck message.

```
table RevokeAndAck {
    channel_id:                 Byte32,
    per_commitment_secret:      Byte32,
    next_per_commitment_point:  Byte33,
    next_local_nonce:           Byte66,
}
```

- per_commitment_secret: Secret used to generate the revocation secret key for the previous commitment transaction.
- next_per_commitment_point: Point used to generate the next revocation public key.
- next_local_nonce: Used for generating the partial signature for the next commitment transaction.

Upon receiving the RevokeAndAck message, the node should update the remote commitment transaction.

## RemoveTlc

To simplify the implementation, only the recipient of the AddTkc message can remove the TLC.

```
table RemoveTlc {
    channel_id:         Byte32,
    tlc_id:             Uint64,
    reason:             RemoveTlcReason
}

union RemoveTlcReason {
    RemoveTlcFulfill,
    RemoveTlcFail,
}

struct RemoveTlcFulfill {
    payment_preimage:   Byte32,
}

struct RemoveTlcFail {
    error_code:         Uint32,
}
```

- channel_id: ID of the channel.
- tlc_id: ID of the TLC being removed.
- reason: Reason for removing the TLC, which can be either RemoveTlcFulfill or RemoveTlcFail.
    - RemoveTlcFulfill: Contains the payment_preimage required to fulfill the payment.
    - RemoveTlcFail: Contains an error_code indicating the reason for failure.

[BOLT 02]: https://github.com/lightning/bolts/blob/master/02-peer-protocol.md#channel-establishment-v2
[Molecule]: https://github.com/nervosnetwork/molecule
[Secret Derivations]: https://github.com/lnbook/lnbook/blob/54453c7b1cf82186614ab929b80876ba18bdc65d/07_payment_channels.asciidoc#revocation_sidebar

# Fiber Network Invoice Protocol

## Overall Design

Fiber network invoice will be generated and parsed by Fiber Node, we referred to the design of [BOLT 11](https://github.com/lightning/bolts/blob/master/11-payment-encoding.md), and made some adjustments from an implementation perspective.

- The invoice is encode/decoded base on [molecule](https://github.com/nervosnetwork/molecule), which is widely used in the CKB projects.
- Instead of using `bech32`, we switch to `bech32m`.
- The interface and usage is similar to [lightning-invoice](https://github.com/lightningdevkit/rust-lightning/tree/main/lightning-invoice/src) as possible, but not compatible with lightning invoice, any cross-chain compatibility needs will be handled through the hub in FNN.

## Human-readable part

The human-readable part contains these two most important fields:

1. `prefix`: [mandatory] Specify the currency and network of payment
    - `fibb` for the CKB mainnet,  `fibb` means `fiber bytes`, since in CKB ecosystem 1 CKB equals 1 Byte.
    - `fibt` for the CKB testnet
    - `fibd` for the CKB dev
2. `amount`: [optional] An optional number in that currency.
    - A standalone number, means the amount of CKB or UDT, for CKB it will be in unit of `shannon`, 1 CKB = 10^8 shannon
    - An empty value for this field means the amount of payment is not specified, which maybe used in the scenario of donation.

## Encoding and Decoding

With `molecule`, the data part can be easily converted to bytes. Considering that the bytes generated by molecule are not optimized for space and may contain consecutive zeros when certain fields are empty, the result from `bechm32` encoding is relatively long. We use [arcode-rs](https://github.com/cgbur/arcode-rs) to compress the bytes losslessly before `bechm32` encoding, resulting in a length reduction of almost half:

`data = compressed(data part molecule bytes) + signature`

`encode(&hrp, data, Variant::Bech32m)`

For decoding, we simply perform the inverse decompression operation.

The `signature` field: [optional] with type of `[u8; 65]` = 520 bits

- The secp256k1 signature of the entire invoice, can be used to verify the integrity and correctness of the invoice, may also be used to imply the generator node of this invoice.
By default, this filed is none, the method to generate signature:
  - `message_hash = SHA256-hash (((human-readable part) → bytes) + (data bytes))`
       then sign it with `Secp256k1`
  - It may use a customized sign function: `Secp256k1::new().sign_ecdsa_recoverable(hash, &private_key)`

## Data Part

The data part is designed to add non-mandatory fields easily, and it is very likely that new field will be added in the future:

1. `timestamp`: [mandatory] 128 bits
    - milliseconds since 1970
    - The time the invoice was generated
2. `payment_hash`: [mandatory] 256 bits
    - SHA256 payment_hash, could specified when creating a invoice, but we need to make sure `payment_hash` is the unique identifier of a invoice.
    - If creating a `HODL` invoice, a `preimage` parameter must be provided, and the `payment_hash` is generated using `blake2b_256(preimage)` when the invoice is created.
    - For `AMP invoices` (Atomic Multi-path Payments), the `payment_hash` is randomly generated.
3. `expiry`: [optional] 32 bits
    - `timestamp + expiry` is the expiration time of the invoice
    - Unit: seconds
4. `description`: [optional] variable length
    - A string of UTF-8 text to display payment information, such as "a cup of coffee"
5. `final htlc timeout`: [optional] 32 bits
    - Specifies the final htlc timeout, which may be longer because it may take more hops to reach CKB network
    - Unit: seconds
6. `fallback`: [optional] variable length
    - A CKB address used for fallback in case the invoice payment fails
7. `feature`: [optional] 32 bits
    - Feature flag to specify features supported by the payment
8. `payee_public_key`: [optional] 33 bytes
    - The public key of the payee
9. `udt_script`: [optional] variable length
    - The script specified for the UDT token
10. `hash_algorithm`: [optional] 1 byte
    - The hash algorithm used to generate the `payment_hash` from the preimage. When this is missing, the default hash algorithm ckb hash is used.
        - 0: ckb hash
        - 1: sha256
