# *Ethereum*
- Ethereum is a decentralized, open-source platform that uses blockchain technology to create a permanent, tamper-proof record of transactions.
<img width="850" alt="Screenshot 2024-03-09 235732" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/db0c352a-42eb-41bb-a492-7d0d270887dd">
<img width="850" alt="Screenshot 2024-03-10 000106" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/fddcf4c2-917d-406e-a2b1-47736b2c9b5b">

- *Ethereum Nodes*
   - *Full Node*
      - Stores copy of entire blockchain
      - Verfies and validates the block
   - *Light Node*
      - Stores only the block header, depends on full node
      - For low capacity devices which cannot afford to store gigabytes of data
   - *Archive Node*
      - Stores everything kept in the full node and built an archieve of historical data
      - Requires terabytes of space
     
### *Ethereum Accounts*
- It is an entity with an ether(ETH) balance that can send or receive transactions on Ethereum
- An EOA is controlled by a private key, has no associated code, and can send transactions.
- A contract account has an associated code that executes when it receives a transaction from an EOA
- Smart contract is a program that runs on ethereum blockchain
- Bitcoin is made by Bitcoin script(No turing complete-Loops cannot be used)
- Ethereum is made by solidity(Turing complete-We can execute any code according to our logic,loops are present)
- Each node has following:
   - Currrent state of all smart contracts
   - History of both transaction and smart contract

<img width="850" alt="Screenshot 2024-03-10 001402" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/9828d630-384a-44da-b392-905e0c18ce59">  
<img width="850" alt="Screenshot 2024-03-10 002201" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/66ba3f95-47a2-44ff-9205-55062a8517ca">    
<img width="850" alt="Screenshot 2024-03-10 002654" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/3aaed8f2-093e-4195-a870-1a6c379de01c">  
<img width="850" alt="Screenshot 2024-03-10 003637" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/ad48c112-122a-4914-9f0f-ca4b8338db6f">  

-------------  


### *Decentralized applications(Dapps)*
<img width="850" alt="Screenshot 2024-03-10 004708" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/5cb0f675-c584-4bd7-8826-1a7c7c7430fe">  
<img width="850" alt="Screenshot 2024-03-10 004834" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/ec0f0cce-9cf7-4cfc-9095-a4a4b6936999">  
<img width="850" alt="Screenshot 2024-03-10 004905" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/fb107fbd-1565-4235-aba1-1c128a803d70">  


### *Ethereum Virtual Machine(EVM)*  
- It is designed as the runtime environment for smart contracts in Ethereum. It is sandboxed and isolated from the other parts of the system. This means that any operation on EVM should not affect your data or programs in any way, no matter how many times you call a particular function on it.

### *Ethereum Gas*  
<img width="850" alt="Screenshot 2024-03-10 010258" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/82625dd8-7e02-4efa-87c4-765e1397cc52">    

- Find more info at "https://github.com/djrtwo/evm-opcode-gas-costs"
- Any transaction that modifies the blockchain costs gas
- The user that generated the transaction pays for the gas
- The higher tha gas price, the faster the transaction will be mined
- Gas limit can prevent cyberattacks by limiting use of gas 

<img width="850" alt="Screenshot 2024-03-10 011119" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/a50254f9-5236-4799-b1eb-c3aaa73aac79">  
<img width="850" alt="Screenshot 2024-03-10 011645" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/8a186436-c130-4163-9167-845d002295a6">    
<img width="850" alt="Screenshot 2024-03-10 011845" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/5e2ef4e8-84fe-41ef-a09b-f8135c40ff93">    

- Find more info at "ethereum.io"
  
<img width="850" alt="Screenshot 2024-03-10 180512" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/6d129170-e0b4-4770-8776-acfcaa20eafd">  
<img width="850" alt="Screenshot 2024-03-10 180558" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/4e925e49-7e6a-44a3-ad0b-db61781b822e">    
<img width="850" alt="Screenshot 2024-03-10 180858" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/60158876-aad6-48b2-a440-de94928b9ede">   

  

### *The DAO Attack* 
- DAO attack was due to a bug in smart contract which ran over ethereum blockchain
<img width="850" alt="Screenshot 2024-03-10 191153" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/085863c0-32d5-43f9-a08a-125df0848aaf">   
<img width="850" alt="Screenshot 2024-03-10 192952" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/73f75d32-e512-473b-b4b9-4829cc6bb1e3">  
<img width="850" alt="Screenshot 2024-03-10 193110" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/ec559c96-1ee3-4cff-9790-c1320bd1c37e">  

- After DAO attack, due to hard fork ethereum blockchain was divide into ethereum classic and ethereum
- Attackers started to steal ethers and investers came at loss


### *Hard Fork*
- Ethereum classic followed traditional principles which beleived that no need to change the existing methods
- Ethereum new version beleived that they need to change the existing principles
- Parallely both branches were working
- Hard fork also occured in bitcoin also

<img width="850" alt="Screenshot 2024-03-10 202106" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/976a27d0-1893-4f08-a704-2824c8d3788f">  
<img width="850" alt="Screenshot 2024-03-10 203434" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/ba043a3e-f9d6-4a62-920f-c1f20bcadaf3">  

### *Soft fork*  
<img width="850" alt="Screenshot 2024-03-10 225834" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/5ee0efaf-a8ef-46e2-8854-af5840f7b3a6">  
<img width="855" alt="Screenshot 2024-03-10 230411" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/c63c2e07-c957-4828-b30c-b3bb7be7c8f8">  


### *ICO(Initial Coin offering)*  
<img width="805" alt="Screenshot 2024-03-10 231955" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/baca7e75-64ed-4b2f-9f63-6da778332b33">  



### *Ethereum 2.0 or Serenity*  
- Scalibility
- Security
- Sustainiblity
- Major upgrades
  - Sharding
  - Proof of Stake(POS)

<img width="850" alt="Screenshot 2024-03-10 232652" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/c3e01c7b-d398-4813-b73b-cfe5f6f6745f">    

- Minimum requirement is of 32 ETH to become a validator

<img width="850" alt="Screenshot 2024-03-10 233216" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/f36e7cd6-c903-4551-a59a-dbdab4c81418">  
<img width="850" alt="Screenshot 2024-03-10 233310" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/5e4b3710-daf9-4813-8aff-b7c0ca65a4b4">  

- *Sharding*
  - In Ethereum, sharding is a scaling solution that involves dividing the network into multiple shards. Each shard has its own state, set of account balances, and smart contracts.
<img width="850" alt="Screenshot 2024-03-10 233902" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/8d751204-0f65-4a59-a247-6d1f70b5f240">
<img width="850" alt="Screenshot 2024-03-10 234104" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/8a8a476c-5ef6-493f-ac2c-a26ba83e0b4c">
<img width="850" alt="Screenshot 2024-03-10 234241" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/5e2e3db0-3b0f-42b5-81cf-d6e8902b155d">


### *Alt coins*
- All coins which are not bitcoins are called alt coins
<img width="850" alt="Screenshot 2024-03-10 234341" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/61fc9097-f519-42b1-9df3-392cd2cd0cfe">
<img width="850" alt="Screenshot 2024-03-10 234504" src="https://github.com/raunakkk21/Cybersecurity/assets/143111163/12ca1c7e-1043-4f5d-83d2-6cc6646caaf1">





























































