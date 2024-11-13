# 21.10.2024
* [14:56] - I just realized that I lost my previous diary, where a lot of contents were written about my earlier researches of **UniswapV2**, **Fountain** and Solidity syntax. That sucks, well I'll start new one
          I've got a new task. We hav a lif3 token running on Polyogn. I need to integrate it into Solana blockchain. That's not an easy task, especially considering that my **Solana Anchor** learning isn't yet over.
          I'll need to first learn current code written in Solidity and then write the same code in Rust using **Solana Anchor**
* [15:00] - The environment for **Anchor is installed**. Although Solana wasn't working in Sindows so I had to install **WSL Ubuntu** for it. Also I've got some issues when running basic hello world program by in Anchoor's **solang** project using solang compiler
          so I switched back to classical **rustc** version

* [19:10] - SetUp project for RUST Anchor Solana development, connected the wallet and check configs and compilability. Wrote some Anchor code and started learning "Token Creation Flow" in Solana Ecosystem. Will try to write and deploy MintToken tomorrow, aslo will estimate the deadline for the project

# 22.10.2024
* [11:40] - So far I am trying to create MintToken. Implemented 
* [15:30] - So Transfer, Aprove, GetBalance functions work. TotalSupply and Allowance to do
* [18:30] - Learnt some theory about stablecoin. but more info needed. Will finish TotalSupply and Allowance tomorrow and try to figure out what is     needed for our l3usd stablecoin to work



# 23.10.2024
* [18:30] - So far we figured out that our L3USD is a stablecoin present on **Polygon Network**. Also it is integrated with **UniswapV3**, paired 
  in a liquidity pool with **USDT** [990.300890161232993299 L3USD: 985.441963 USDT]. But we couldn't figure out what external application 
  stabilizes the price and hence can't define what type of stablecoin are we dealing with. The decision was made to continue implement token's core 
  functionality in Solana.

# 29.10.2024
[10:44] - I believe latest writing was deleted, but no worries I'll provide the whole update here. L3USD was created in Solana as a basic SPL Token together with it's metadata. After I was assigned to create not only L3USD as a token, but it's stabilizing mechanism too for lif3 blockchain. I successfully finished it for the Polygon Amoy testnet. DataPrice here is fetched from Chainlink which doesn't natively support lif3 blockchain, unless we create chainlink node ourselves and provide this information for lif3 blockchain. Currently waiting for team to figure out whether we have a WS protocol working in lif3 blockchain as it is neccessary to become a primary node.

# 06.11.2024
[18:16] - It has been a long week, but a very interesting one. I succcessfully set chainlink node up for both AMOY and LIF3TESTNET chains. Haven't tested data fetch result on LIF3TESTNET yet, because I am limited on contract deployment there by the devs, but everything works fine on AMOY. Moreover I integrated node with stabelcoin logic implemented earlier. Now I will beautify and clarify whole flow, write the script doing all the proccesses and write docs on it.

# 25.10.2024
* [18:55] - Generally Finished UniswapV2 learning. Built and deployed L3USD SPL-TOKEN in Solana Amoy, Market and pools yet to create.
            Now learning stablecoin creation and ways of deploying L3USD to lif3 blockchain so it acts as a stablecoin. Low priority task to learn              SAFE

# 12.11.2024
* [18:52] - I don't know why my diary entries are being deleted. Lemme write updates since the last one then. L3USD stablecoin was created and test
            deployed to lif3Testnet, everything works fine. However, some clarifications are needed from the client side to make it work                        accordingly. Now I have a task to make `Fountain` system lif3Testnet deployable where I see no problem as there is already `Uniswap`                deployed. The problem though is I can't understand where the staked tokens are farmed. There is no logic by which *Treasury* contract               should be supplied by farmed tokens. Also, the `Treasury` contract is for two tokens, not one as it is in Masonry.

# 13.11.2024
* [11:50] - Suggested single token problem solution for *Treasury Contract* and was instructed to wait until deployment will be allowed
            Now I am excited to learn multi-sig technology and implement Gnosis SAFE multi-sig wallet performance in our local lif3Testnet
