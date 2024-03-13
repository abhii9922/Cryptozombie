# To run this application

1. Install the dependencies using `npm install`

2. Install Ganache and update the `truffle-config.js` file with the its network configuration.

3. Compile all the contracts using `truffle compile`.

4. Migrate all the contracts using `truffle migrate`.

5. Copy the ZombieOwnership Deployed contract address and update it in index.html (line 34. under startApp function).

6. Install Metamask and connect to the Ganache network using the following details:
    - Network Name: Ganache
    - New RPC URL: http://localhost:7545
    - Chain ID: 1337 (if your network id is different, change it to 1337)
    - Symbol: ETH

7. Copy the private key of any account from Ganache (copy a key from any account) and add a new account (import account) in Metamask using the private key.

8. Run `npm start`
