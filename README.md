# To run this application

1. Install the dependencies using `npm install`

2. Install Ganache and update the `truffle-config.js` file with the its network configuration.

3. Compile all the contracts using `truffle compile`.

4. Migrate all the contracts using `truffle migrate`.

5. Create a secrets.json file. Put the contract address from ZombieOwnership there.

5. Copy the ZombieOwnership Deployed contract address and update it in index.html (line 34. under startApp function).

6. Install Metamask and connect to the Ganache network using the following details:
    - Network Name: Ganache
    - New RPC URL: http://localhost:7545
    - Chain ID: 1337 (if your network id is different, change it to 1337)
    - Symbol: ETH

7. Copy the private key of any account from Ganache (copy a key from any account) and add a new account (import account) in Metamask using the private key.

8. Run `npm start`


# Improvments

1. Built a nicer website for the DApp.

2. Added images to demo zombies in a better way.

3. User can develop multiple zombies. 

4. Added the attack zombies functionality.

5. Updated the starter code and made it dynamic.

6. Deployed the testnet to Sepolia. 

# Deploying on Sepolia

## Instructions to Deploy on Sepolia

1. Create an account on [Infura](https://www.infura.io/).
2. Configure the API to Sepolia, and copy the API-key.

    `npm i @truffle/hdwallet-provider`

3. Deploy using command `truffle migrate --network sepolia`

4. Update secrets.json with your passphrase from metamask, apikey from Infura, and contract address after deploying/

5. Run `npm start`

