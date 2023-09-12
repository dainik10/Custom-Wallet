<b>What is BIP?</b>
<br/>
    A Bitcoin Improvement Proposal (BIP) is a formal proposal to change Bitcoin. As a piece of software, Bitcoin is always undergoing upgrades—bugs need to be fixed, algorithms can be made more efficient, code can be simplified, compatibility with other software must be maintained, and new features can be added.
<br/>

<b>What is EIP</b>
<br/>
    Ethereum Improvement Proposals (EIPs)(opens in a new tab) are standards specifying potential new features or processes for Ethereum. EIPs contain technical specifications for the proposed changes and act as the “source of truth” for the community. Network upgrades and application standards for Ethereum are discussed and developed through the EIP process.
<br/>

<b>What is Mnemoic</b>
<br/>
  Mnemonics are simply songs, abbreviations and rhymes that assist in remembering something.
  In the world of cryptocurrencies, mnemonics is a group of words, usually 12 or more that are generated when a new crypto wallet is created.
  The whole point of this is to ensure crypto wallets can be accessed if the password is lost.
<br/>

<b>What is BIP32</b>
<br/>
 This proposal aimed to improve the limitations of traditional non-deterministic wallets, which required a new backup for each new address.
 all the keys and addresses stem from a single root key known as the master private key. Child keys (both private and public) are derived from this root in a deterministic way
<br/>

<b>What is BIP44</b>
<br/>
    The BIP44 standard provides a systematic method for creating multiple accounts and addresses within a single wallet. It uses the concept of a "path" that informs a 
    wallet how to derive keys from a root seed.
    <br/>

    The derivation path used in BIP44 follows this structure: m / purpose' / coin_type' / account' / change / address_index


    Each element in the path has a specific meaning:

    m: This is the master node and represents the root of your HD wallet.
 
    purpose': Always set to 44' for BIP44 compliant wallets.
 
    coin_type': Specifies the type of cryptocurrency. Each cryptocurrency has a specific number assigned, such as 0' for Bitcoin and 60' for Ethereum.
 
    account': A BIP44 wallet can have multiple accounts, and this number represents each unique account.
 
    change: This is either 0 for external (receiving) addresses or 1 for internal (change) addresses.
 
    address_index: Represents the individual addresses generated under each account.
<br/>

<b>What is BIP39</b>
<br/>
 This proposal aimed to improve the handling of wallet and how wallet can be created from mnemonic.
 https://learnmeabitcoin.com/technical/mnemonic 
<br/>
