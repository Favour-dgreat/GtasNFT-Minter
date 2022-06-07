
<!-- ABOUT THE PROJECT -->
[Give Them a Smile NFT Markeplace Logo](https://i.ibb.co/rc7Yf20/smil.jpg)

## About The Project

Give them a SMILE NFT Marketplace is a decentralized application that provides donation to indigent children as you buy their images as NFTs.
This Project is for Celo Development 201 - Build an NFT Minter with Hardhat and React
Submission

Project Link: [GTAS NFT Marketplace](https://favour-dgreat.github.io/GtasNFT-Minter/)


### Technologies used

Frameworks and libraries used in this project include:

* [React.js](https://reactjs.org/)
* [Hardhat](https://hardhat.org/getting-started/)
* [Solidity](https://docs.soliditylang.org/en/v0.8.11/)
* [Openzeppelin](https://openzeppelin.com/)
* [Bootstrap](https://getbootstrap.com)
* [Celo-tools](https://docs.celo.org/learn/developer-tools)


## :point_down: Getting Started

To get this project up running locally, follow these simple example steps.

### Prerequisites

You will need node and yarn installed.

### Installation

Step-by-step guide to running this NFT minter locally;

1. Clone the repo
   ```sh
   git clone [Give them a SMILE NFT Marketplace](https://github.com/Favour-dgreat/GtasNFT-Minter.git)
   ```
2. Install NPM packages
   ```sh
   npm install
   ```

3. Run your application
   ```sh
   npm start
   ```

### Smart-Contract-Deployment

Step-by-step guide to redeploying the NFT smart contract using your address to enable you mint NFTs.

1. Compile the smart contract
   ```sh
   npx hardhat compile
   ```
2. Run tests on smart contract
   ```sh
   npx hardhat test
   ```
3. Update env file

* Create a file in the root directory called ".env"
* Create a key called MNEMONIC and paste in your mnemonic key. e.g
     ```js
   MNEMONIC="xxxx ggg hhhhh hhhff hhhh hijj cddd hill"
   ```
You can get your MNEMONIC from Metamask Recovery security phrase in settings

4. Deploy the smart contract
   ```sh
    npx hardhat run scripts/deploy.js
   ```
5. Run the project
   ```sh
    npm start
   ```

## :writing_hand: Contributing

Contributions are welcomed for this project, especially on the UI and the Contract development. 

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also
simply open an issue with the tag "enhancement". Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch 
3. Commit your Changes 
4. Push to the Branch 
5. Open a Pull Request



