# Team BlockWizards

1. Akash Butala - 885193201 - akbutala@csu.fullerton.edu

2. Abhishek Shinde - 885513457 - Ashinde813@csu.fullerton.edu

3. Soham Kulkarni - 884237404 - Kulkarni.soham@csu.fullerton.edu

4. Jeet Hirakani - 885189175 - jeethirakani@csu.fullerton.edu

# Repo Link

https://github.com/abhii9922/Cryptozombie

# Improvments

1. Built a nicer website for the DApp.

2. Added images to demo zombies in a better way.

3. User can develop multiple zombies. 

4. Added the attack zombies functionality.

5. Updated the starter code and made it dynamic.

6. Deployed the DApp to Sepolia.
   
7. Added the level down functionality.

8. Can change the name of the Zombies.


# To run this application

1. Install the dependencies using `npm install`

2. Install Ganache and update the `truffle-config.js` file with the its network configuration.

3. Compile all the contracts using `truffle compile`.

4. Migrate all the contracts using `truffle migrate`.

5. Create a secrets.json file. Put the contract address from ZombieOwnership there. Here's the format.
   '{
    "passphrase":"",
    "apiKey": ""
   }'

6. Create a key.json file. Put the transaction address there.
'{
    "transactionAddress": ""
}
'
7. Install Metamask and connect to the Ganache network using the following details:
    - Network Name: Ganache
    - New RPC URL: http://localhost:7545
    - Chain ID: 1337 (if your network id is different, change it to 1337)
    - Symbol: ETH

8. Copy the private key of any account from Ganache (copy a key from any account) and add a new account (import account) in Metamask using the private key.

9. Run `npm start`



# Instructions to deploy on Sepolia

1. Create an account on [Infura](https://www.infura.io/).
2. Configure the API to Sepolia, and copy the API-key.

    `npm i @truffle/hdwallet-provider`

3. Deploy using command `truffle migrate --network sepolia`

4. Update secrets.json with your passphrase from metamask, apikey from Infura, and contract address after deploying/

5. Run `npm start`

