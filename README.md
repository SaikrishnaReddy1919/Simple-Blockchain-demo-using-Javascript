## getBalanceOfAddress()

unlike tradational method of getting a balance of an account, in blockchain we have to loop through every block in the blockchain. While looping, if txn is 'from' that address then we hv to reduce to the amount otherwise if txn is 'to' that address then we have to add that amount to that address and return the result.

To run this ->

### -> npm install
### -> node block.js

after entering above commands try playing with this.