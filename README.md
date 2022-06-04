# PRNG-Beacon-using-Blockchain
Public randomness is a critical component in many (distributed) protocols. 
Generating public randomness is hard when there is no trusted party, and active adversaries may behave dishonestly to bias the randomness toward their advantage. 
This implementation generatess continuous public randomness using Blockchain as a source of entropy and also leveraging the randomness provided by multiple volunteer users (delegates) to mitigate the biasing attacks. 

We use the Ethereum development environment, Truffle suite, with Ganache as a personal Ethereum Blockchain, to implement the smart contracts of, 
(i) the scheme which is based on secret sharing and threshold cryptosystem and 
(ii) the new scheme that is based on Caucus leader election.

We will provide the smart contract codes. The smart contracts are written in Solidity language and were first tested on Remix Ethereum(Remix) and eventually we tested them using Truffle suite and Ganache blockchain.

