## Deploying to a Testnet ETH

Make sure you have a [Metamask](https://metamask.io/) or other wallet, and export the private key.

**IMPORTANT!**

USE A METAMASK THAT DOESN'T HAVE ANY REAL FUNDS IN IT. Just in case you accidentally push your private key to a public place. I highly recommend you use a different metamask or wallet when developing.

1. [Export your private key](https://metamask.zendesk.com/hc/en-us/articles/360015289632-How-to-Export-an-Account-Private-Key) and place it in your `.env` file.

2. Go to [Alchemy](https://www.alchemy.com/) and create a new project on the testnet of choice (ie, kovan or Rinkeby).

3. Grab your URL associated with the testnet, and place it into your `.env` file.

4. Make sure you have [Testnet ETH](https://faucets.chain.link/) in your account. You can [get some here](https://faucets.chain.link/). You should get testnet ETH for the same testnet that you made a project in Alchemy (ie, Rinkeby or Kovan).

5. Run

```
node deploy.js
```
