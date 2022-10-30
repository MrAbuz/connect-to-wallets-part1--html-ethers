In this "Connect to wallet series" we are following the video:
https://www.youtube.com/watch?v=pdsYCkUWrgQ, from Patrick Collins.

In this repo we are gonna do everything in HTML / JS.
In the following "Connect to wallet series" we are gonna try the following ways to connect to a wallet:

1. NextJS / React and "raw" ethers
   Then we're gonna get more advanced, and use some more advanced tooling for the web3 space (NextJS and a package):
2. NextJS & "web3-react"
3. NextJS & "react-moralis"
4. NextJS & "web3Modal"
5. NextJS & "useDapp"

Simple process to try this repo:

```
git clone https://github.com/MrAbuz/connect-to-wallets-part1--html-ethers
yarn
```

Then open a new terminal, and:

```
cd ..
git clone https://github.com/MrAbuz/connect-to-wallets-part0--just-to-get-hardhat-sol-code
yarn
yarn hardhat node
```

Install the vs code extension "Live Server", and click in "Go live" in the bottom right corner. Then:

Copy the rpc url provided in the hardhat node that you created, then go to your metamask, add a new network, and create a new network with that rpc url and chainid: 31337.
Then pick one private key from the ones provided in hardhat node and import it to your metamask.

With all of this you should be able to test this repo! have fun! :)
