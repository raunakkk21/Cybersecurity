# *Cryptocurrency*
<img width="850" alt="Screenshot 2024-03-08 212430" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/9c543faf-2fc6-42f8-bf61-02ec459340e1">      

-  Coins are any cryptocurrency that has a standalone independent blockchain (Bitcoin, Ethereum, Ripple…)
-  Tokens are digital assets that operate on an existing blockchain network instead of on their own. This gives them some interesting properties relating to interoperability.

<img width="850" alt="Screenshot 2024-03-08 233040" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/b72c306a-5dd5-45bf-9742-df439b4dd8b2">  

### *Bitcoin monetary policy*
<img width="850" alt="Screenshot 2024-03-08 233248" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/327f9e06-c752-4c4e-b2a7-efc04a870a28">  
<img width="850" alt="Screenshot 2024-03-08 233959" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/e04887dc-3be3-4cf2-a51c-b01b18ac9e8d">   

- You can get more info on "blockchain.com"


### *How Mining Works:The Nonce*  
- It is a random number that bitcoin miners try to find in order to mine a new block in the Bitcoin blockchain and receive a block reward for their efforts.
<img width="850" alt="Screenshot 2024-03-08 234924" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/15059b94-e23b-44d1-9cbd-f839a873fcd8">
<img width="850" alt="Screenshot 2024-03-08 235433" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/cd9ed375-4870-4169-8a21-3b11f8258ea9">
<img width="846" alt="Screenshot 2024-03-09 000420" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/a9860249-6a44-45d7-9a66-89151c97f2f4">


- Target value changes every two weeks which leads to increasing or decreasing difficulty levels.

  
------------

  
### *CPU | GPU | ASCIs*    
<img width="850" alt="Screenshot 2024-03-09 002752" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/5c8dd4dc-1642-44d4-a88b-09f3c5bb4657">  

--------  


### *Mining Pools*    
- A mining pool is a group of cryptocurrency miners who connect their mining machines over a network to increase their chances of earning rewards.
- Rewards are given according to their use of  hashing power
- Each miner computer work on different problems to optimize their hasing power
<img width="850" alt="Screenshot 2024-03-09 003930" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/c016d9ca-16db-4a2a-b2c0-dce21f32575a">
<img width="850" alt="Screenshot 2024-03-09 004451" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/b9540890-2ac0-4c89-a2d6-f0755d53efa3">

----------  

### *Nonce Range*    
<img width="850" alt="Screenshot 2024-03-09 004736" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/9c712d69-c459-48e7-adbd-d9bdb5786231">    
<img width="850" alt="Screenshot 2024-03-09 004851" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/53d1d426-e570-4e07-b03a-5ac020e75b56">  
<img width="850" alt="Screenshot 2024-03-09 005134" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/5753f203-c9d3-4a07-ba6f-158881fdec37">  
<img width="850" alt="Screenshot 2024-03-09 005446" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/1872e889-4b05-4297-9f06-845b41ef7a2d">  

- All the nonces will be exhausted in only 40 seconds and remaining hashes never hit the target which will create a problem, which leads us to a new concept called Timestamp



### *Timestamp*    
- In each second as the time changes hash value also changes due to avlanche effect(unix time).
- But in every 1 second miner can only use 0.1 billion nonce in 1 second after which timestamp changes which results in change of hash value
- As the hash value changes, the nonces that we used can be used once again and can be utilised according to machine efficiency at current time
- And nonces can be used again and again

<img width="850" alt="Screenshot 2024-03-09 153102" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/f258574e-2334-4276-9033-51bf3de920dc">  
<img width="850" alt="Screenshot 2024-03-09 153045" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/66f28ca6-dadf-44b4-80d8-a0c0c56cb773">  
<img width="850" alt="Screenshot 2024-03-09 154151" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/87276b90-c138-4479-ae78-b2138fb8bb83">    

- But if we see in whole network the nonces exhaust in a very less period of time which is far less than 1 second


  
----------    

###  *Mempool*    
- A mempool is a temporary storage area for transactions in a cryptocurrency network
- Miners take any number of transactions and keep in their ledger
- When nonces get over in a very less time, then the miners change the transaction to slight smaller values which change the hash value and nonces which got exhausted can be used once again.
- After this timstamp again changes and  this cycle repeats again.

<img width="850" alt="Screenshot 2024-03-09 155414" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/3db3e944-c100-45fb-8458-c575302ac771">   
<img width="850" alt="Screenshot 2024-03-09 174536" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/1fe4c69c-b992-4ee4-937e-d82ba7af8faa">  
<img width="850" alt="Screenshot 2024-03-09 175004" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/085ac599-bd04-4fb5-9335-9f4d604ee516">  


### *Transactions and UTXOs(Unspent transaction output)*  
- When a Bitcoin transaction takes place, it creates one or more outputs, which are essentially the destination addresses where the Bitcoins are being sent. These outputs are assigned a value, which is the amount of Bitcoins being transferred.
<img width="850" alt="Screenshot 2024-03-09 175930" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/23d116d5-5679-4e83-83b9-5600f193315c">
<img width="850" alt="Screenshot 2024-03-09 180303" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/c1ef2d5b-b7b4-422f-a93b-ef07dfe35ea5">

- Finaaly we are left with bob's UTXO
<img width="850" alt="Screenshot 2024-03-09 180756" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/5e7f2545-a4d9-42af-99f0-28e3ce9b837b">
<img width="850" alt="Screenshot 2024-03-09 181539" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/e2ad329d-8d46-4c9f-a17b-85aee9785d65">
<img width="850" alt="Screenshot 2024-03-09 181644" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/926e2d2a-adb8-4eae-9c4a-143295268934">

- Wallet fetches UTXOs and then calculates how much balance are we left with.






































