

     /⬢⬢   /⬢⬢ /⬢⬢                     /⬢⬢⬢⬢⬢⬢⬢                         /⬢⬢                                            |⬢⬢
    | ⬢⬢  /⬢⬢/|__/                    | ⬢⬢__  ⬢⬢                     |     ⬢⬢                                            |⬢⬢ 
    | ⬢⬢ /⬢⬢/  /⬢⬢ /⬢⬢⬢⬢⬢⬢⬢       | ⬢⬢  \ ⬢⬢ /⬢⬢⬢⬢⬢⬢   /⬢⬢⬢⬢⬢⬢  /⬢⬢⬢⬢⬢⬢    /⬢⬢⬢⬢⬢⬢   /⬢⬢⬢⬢⬢⬢  /⬢⬢⬢⬢⬢⬢ |⬢⬢ 
    | ⬢⬢⬢⬢⬢/  | ⬢⬢| ⬢⬢__  ⬢⬢       | ⬢⬢⬢⬢⬢⬢//⬢⬢__  ⬢⬢ /⬢⬢__  ⬢⬢|_   ⬢⬢_/    /⬢⬢__  ⬢⬢  /⬢⬢_____/ /⬢⬢__   ⬢⬢| |⬢⬢
    | ⬢⬢  ⬢⬢  | ⬢⬢| ⬢⬢  \ ⬢⬢        | ⬢⬢____/| ⬢⬢  \__/ |⬢⬢  \   ⬢⬢  | ⬢⬢     | ⬢⬢  \ ⬢⬢| |⬢⬢      | ⬢⬢  \  ⬢⬢| |⬢⬢ 
    | ⬢⬢\  ⬢⬢ | ⬢⬢| ⬢⬢  | ⬢⬢        | ⬢⬢     | ⬢⬢       |⬢⬢  |   ⬢⬢  | ⬢⬢ /⬢⬢| ⬢⬢  | ⬢⬢| |⬢⬢      | ⬢⬢  |  ⬢⬢| |⬢⬢  
    | ⬢⬢ \  ⬢⬢| ⬢⬢| ⬢⬢  | ⬢⬢        | ⬢⬢     | ⬢⬢       | ⬢⬢⬢⬢⬢⬢/  |  ⬢⬢⬢⬢/|  ⬢⬢⬢⬢⬢⬢/| |⬢⬢⬢⬢⬢⬢⬢|  ⬢⬢⬢⬢⬢⬢/ |⬢⬢  
    |__/   \__/ |__/|__/    |__/        |__/       \__/         \______/    \_______/ \______/       \_________/ \_______/   |__/  
                                                      

# Kin Protocol V1

A high level repo to lay out a proposed governance system for the Kin Ecosystem

## What is Kin?

Kin is a token but more importantly an idea that was originally conceptualized by Ted Livingston and members of Kik Interactive in the white paper [Kin: a decentralized 
ecosystem of digital services for daily life](https://whitepaper.io/document/71/kin-whitepaper) The white paper lays out an idea to create a decentralized digital economy and shift the paradigm towards an economy of creators and developers and not of centralized companies that control the means for monetization for all. 

## History of Kin

Kin was promptly put into action in 2017 and through multiple iterations, ups and downs, nearly 6 years had past since the whitepaper was drafted and there was a small but vibrant economy of apps.  However, growth remained stagnant and the inital goal of decentralizing appeared to become further and further away.  This was due to a number of factors but at the center of it was the Kin Foundation, which was always the ones creating the rules and calling the shots.  The intial concept that was laid out by the whitepaper had assumed that the Kin Foundation was a temporary measure and would eventually automate their own jobs away and decentralize the governance. Unfortunately over 5 years had passed and this did not happen.

## Why Kin Protocol?

This model is a very open ended suggestion for how governance voting could work that solves for the basic issues of game theory and prevents centralization.  The inspiration for it was [Vitalik Butrin's 2021 article - Moving beyond coin voting governance](https://vitalik.ca/general/2021/08/16/voting3.html) but it uses concepts and ideas from [Compound Comet](https://github.com/compound-finance/comet), [MakerDAO Governance](https://github.com/makerdao/chief-keeper) and [AAVE's AAVEnomics](https://github.com/aave/aavenomics)

## Documentation

The documentation of the Protocol and Governance exists at TBD (put link here)

## Tokenomics

This is a formal path to decentralization and autonomy of Kin.

### **Context**

There needs to be a lower level inventive system and structure outlined in order to move forward.  This should solve only for the problem of how the incentive system needs to be structred to get the right participation in voting.  We want maximum participation but we also want the incentives to encourage people to consider the consequences of voting. A base for this model could be the [Solana Governance Program Examples](https://github.com/solana-labs/solana-program-library/tree/master/governance)

![image](https://user-images.githubusercontent.com/6373607/218552911-de19e635-ca5d-4645-b15e-bb146f92a9b0.png)

## KIP

### **What is a KIP?**
A Kin Improvement Proposal.  It is a suggestion for changes that would be made to the ecosystem.  This is a low level proposal system that we can build voting mechanisms on top of.  Examples of things that could be voted on is - How the KRE should work, Allocation of Kin Reserves, Election of governance roles, modifications to the governance protocol, etc.

## Staking

In order to cast a vote your Kin must be locked in the staking module and will be subject to slashing to rectify negative repercussions of governance votes.  Staking by definition comes with risks.  Prior to implementation of an incentive system the risk will be the slashing and the reward will be your influence over the ecosystem.  Upon staking you would be given an amount of stKin (staked kin) that can be exchanged for kin via the staking module after a period of 30 days of cooldown. An example of how this could look is [Dapp Hub DSChief Program](https://github.com/dapphub/ds-chief) which is used on applications such as MakerDAO.

## Incentives

To incentivize voting it is likely that a proposal must be made to provide staking emissions.  Emissions should be decided by the governance process and should optimize for health and security of the protocol, the Kin Ecosystem and the Kin token respectively.  Stakers would earn a percentage of protocol emissions.  This will likely come from a portion of the Kin reserves.  This will give smaller holders the opportunity to earn additional kin while having no disincentive to participate in governance.  

## Slashing

All good governance systems need a way to hold people accountable for their actions.  Anyone who is staking will be individually responsible, will reap the rewards but may also be subject to consequnces via a maximum slash rate.  This creates individual responsibility amongst stakeholders.  If a governance vote is deemed a failure after its implementation and requires resources to rectify a portion of the staked kin can be slashed to rectify the damage caused by a failure. **Slashing does not exist but will be decided upon and introduced in a KIP**

## Burning 

Another form of suggested slashing is to destroy the locked coins for a malicious vote. If you vote for the failed proposal, in a catastrophic event such as an attack on the network, then the entirety of your coins will be burned.  The voting period should leave enough time that a user can unstake their tokens if they are concerned of the consequences of an upcoming proposal.

## Protocol Governance 

Changes to the ecosystem, whether it be the KRE or proposals to for Kin reserves, will be ratified through onchain Kin Improvement Proposals (KIPs) using the Governance portal. This process is to ensure extensive discussion is had on proposals prior to being pushed to the blockchain.  Any kin staked via the staking module will be able to vote on KIPs.

### Governance Process

![Kin_Protocol_Drawing](https://user-images.githubusercontent.com/6373607/218377833-7cca8bb3-f7fd-4a42-b874-dcf59ad297df.jpg)

<ins>**KIP Creation**</ins> - A community member submits a KIP

<ins>**KIP Feedback**</ins> - The community evaluates the KIP, discusses potential modification or improvements to be made, feedback collected and ultimately it becomes in a closed status 

<ins>**Signal Collection**</ins> - Votes are cast on the KIP

<ins>**Implementation**</ins> - Development takes place and a final version of the code will be submitted at the end for Governance review.  

<ins>**Final Review and vote**</ins> - Initially this will just be a vote.  In later iterations this could be review by some trusted developers who have been assigned roles of reviewer.  If vote does not pass it will get recycled for revision and the governance reviewers, when they exist as roles would give feedback to the team and community of the changes that must take place to pass their review or alternatively if it failed the vote then they willgather community feedback on it to return to the development team.  An example of how roles can work would be [Dapp Hub's DS Role Repo](https://github.com/dapphub/ds-roles/) and [DS Auth Repo](https://github.com/dapphub/ds-auth/)  which are used on many Ethereum governance projects such as AAVE, MakerDao, Compound, etc.

## Kin Reserves

The Kin Reserves according to [the whitepaper](https://whitepaper.io/document/71/kin-whitepaper) is meant to mandate promoting adoption and growth of the Kin Ecosystem.  This has mostly been allocated in the past towards the Foundation.  That pot of funds can be used in whatever way would best suit the growth of the ecosystem and whatever people can imagine for the best method to do so. Kin Reserves would be allocated by creating governance proposals.  This could initially start small as just a suggestion to its current custodians but the intent is that eventually the governance system and its security and roles apartus would control the wallet that holds the Kin reserves.

## KRE 

According to the orignal [whitepaper](https://whitepaper.io/document/71/kin-whitepaper) KRE is meant to constitute 20% of the Kin Reserves.  The method  Similar to the Kin reserves, it would have to start as a suggestion to current custodians of the KRE that money be allocated to this governance mechanism.  Eventually the KRE can be decided upon by community members via the goverance protocol.  A DAO structure is highly recommended.

## Audits
TBD

## Connect with the community

You can join the Kin [Community Discord](https://discord.gg/9Nr2V7UBAT), [KinShips](https://t.co/woIKtqPpHU), and [PumpkinLabs](https://discord.gg/KzHqr9csrh)
Tag @mocolicious#9242 if you have any questions or suggestions.
