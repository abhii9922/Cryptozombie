# To run this application

1. Install the dependencies using `npm install`

2. Install Ganache and add this project to the workspace using the `truffle-config.js` file in the root directory.

3. Compile the contracts using `truffle compile`.

4. Migrate the contracts using `truffle migrate`.

5. Copy the ZombieOwnership Deployed contract address and update it in index.html (line 34. under startApp function).

6. Install Metamask and connect to the Ganache network using the following details:
    - Network Name: Ganache
    - New RPC URL: http://localhost:7545
    - Chain ID: 1337 
    - Symbol: ETH

7. Copy the private key of any account from Ganache (except the 1st one) and add a new account in Metamask using the private key.

8. Run `npm start`
