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
* 
* [18:30] - So far we figured out that our L3USD is a stablecoin present on **Polygon Network**. Also it is integrated with **UniswapV3**, paired 
  in a liquidity pool with **USDT** [990.300890161232993299 L3USD: 985.441963 USDT]. But we couldn't figure out what external application 
  stabilizes the price and hence can't define what type of stablecoin are we dealing with. The decision was made to continue implement token's core 
  functionality in Solana.
