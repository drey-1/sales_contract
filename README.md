# sales_contract
smart contract for sales

Steps to use the application:

Install TestRPC  

     npm install -g ganache-cli
Run ganache-cli(specify the mining interval at two seconds), ten accounts will be allocated with 100 ethers in each account. Further details please refer to here.

    Install Truffle npm install -g truffle
Run truffle init to initiate a new smart contract, and create a new

    .sol 
 file in /contract.
Paste the contract code to this .sol file, and modify the migration files (please refer to the truffle documents here).
Run 
     
     truffle compile
 , start the testrpc network(ganache-cli) after 
  ![alt text](https://github.com/drey-1/sales_contract/blob/master/Screenshot%20(38).png)
       
  sales_contract/Screenshot (38).png
      truffle migrate 
Use truffle console to interact with the smart contract. Get the contract address and abi file from this console.
(please refer to the truffle documents here).
   After truffle migrate 
    ![alt text](https://github.com/drey-1/sales_contract/blob/master/Screenshot%20(39).png)
       
