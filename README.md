## SOLIDITY
This is a basic Solidity smart contract . 

## DESCIRPTION
This smart contract contains several features. It includes two public variables one for the token's name and another for its abbreviation. The contract also has a variable that keeps track of the total token supply. To manage user balances, there is a variable named "balances" that connects addresses with their corresponding token balances.
The contract provides two functions: mint and burn if we mint some tokens in then it reflects in our balance and if we want to burn tokens there is if statement which shows that the balance should be greater than the number of tokens we have to burn .

## GETTING STARTED
Use remixIDE to run and compile

## EXECUTING THE PROGRAM
* Create a new folder 
* If Remix is set to auto compile and run, the code will be automatically compiled and executed. Otherwise, manually compile and run the code by selecting the "Compile and Run" option from the left menu.
* After compiling, deploy the contract to get the account address for next steps.
* The contract gets deployed successfully.
* Initially, the account balance is zero.
* To mint tokens, click on the "Mint" button, paste the account address, enter the desired token quantity (e.g., 500), and click "Transact" to add tokens to the account.
* To check the balance, click on "Balances," paste the account address, and click "Call" to view the account balance.
* To burn tokens, click on "Burn," paste the account address, set the value to be burnt (e.g., 300), and click "Transact" to reduce tokens from the account.
* To check the balance again, press "Call" to obtain the latest balance (e.g., 500-300 = 200 tokens).
* These are all the steps involved in the contract.

## AUTHORS
OM CHINTALWAR

## License
This project is licensed under the [OM CHINTALWAR]  
   
