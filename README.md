# Kin Protocol V1

A high level repo to lay out a proposed governance system for the Kin Ecosystem

## What is Kin?

Kin is a token but more importantly an idea that was originally conceptualized by Ted Livingston and members of Kik Interactive in the white paper [Kin: a decentralized 
ecosystem of digital services for daily life](https://whitepaper.io/document/71/kin-whitepaper) The white paper lays out an idea to create a decentralized digital economy and shift the paradigm towards an economy of creators and developers and not of centralized companies that control the means for monetization for all. 

## History of Kin

Kin was promptly put into action in 2017 and through multiple iterations, ups and downs, nearly 6 years had past since the whitepaper was drafted and there was a small but vibrant economy of apps.  However, growth remained stagnant and the inital goal of decentralizing appeared to become further and further away.  This was due to a number of factors but at the center of it was the Kin Foundation, which was always the ones creating the rules and calling the shots.  The intial concept that was laid out by the whitepaper had assumed that the Kin Foundation was a temporary measure and would eventually automate their own jobs away and decentralize the governance. Unfortunately over 5 years had passed and this did not happen.

## Documentation

The documentation of the Protocol and Governance exists at TBD (put link here)

## Tokenomics

This is a formal path to decentralization and autonomy of Kin.

### **Context**

There needs to be a lower level inventive system and structure outlined in order to move forward.  This should solve only for the problem of how the incentive system needs to be structred to get the right participation in voting.  We want maximum participation but we also want the incentives to encourage people to consider the consequences of voting. A base for this model could be the [Solana Governance Program Examples](https://github.com/solana-labs/solana-program-library/tree/master/governance)

(insert chart)

## KIP

### **What is a KIP?**
A Kin Improvement Proposal.  It is a suggestion for changes that would be made to the ecosystem.  This is a low level proposal system that we can build voting mechanisms on top of.  Examples of things that could be voted on is - How the KRE should work, Allocation of Kin Reserves, Election of governance roles, modifications to the governance protocol, etc.

## Staking

In order to cast a vote your Kin must be locked in the staking module and will be subject to slashing to rectify negative repercussions of governance votes.  Staking by definition comes with risks.  Prior to implementation of an incentive system the risk will be the slashing and the reward will be your influence over the ecosystem.

## Incentives

To incentivize voting it is likely that a proposal must be made to provide staking emissions.  Emissions should be decided by the governance process and should optimize for health and security of the protocol, the Kin Ecosystem and the Kin token respectively.  Stakers would earn a percentage of protocol emissions.  This will likely come from a portion of the Kin reserves.  This will give smaller holders the opportunity to earn additional kin while having no disincentive to participate in governance.  

## Slashing

The additional incentive to participate if you are staking is that a stable system will keep you from losing Kin via slashing.  If a governance vote is deemed a failure after its implementation and requires resources to rectify a portion of the staked kin can be slashed to rectify the damage caused by a failure. **Slashing does not exist but will be decided upon and introduced in a KIP**

## Kin Reserves

TBD

## Protocol Governance 

Changes to the ecosystem, whether it be the KRE or proposals to for Kin reserves, will be ratified through onchain Kin Improvement Proposals (KIPs) using the Governance portal. This process is to ensure extensive discussion is had on proposals prior to being pushed to the blockchain.  Any kin staked via the staking module will be able to vote on KIPs.

### Governance Process

### KIP Creation &rarr; KIP Feedback &rarr; Signal Collection &rarr; Implementation &rarr; Review & Final Vote

<ins>**KIP Creation**</ins> - A community member submits a KIP

<ins>**KIP Feedback**</ins> - The community evaluates the KIP, discusses potential modification or improvements to be made, feedback collected and ultimately it becomes in a closed status 

<ins>**Signal Collection**</ins> - Votes are cast on the KIP

<ins>**Implementation**</ins> - Development takes place and a final version of the code will be submitted at the end for Governance review.  

<ins>**Final Review and vote**</ins> - Initially this will just be a vote.  In later iterations this could be review by some trusted developers who have been assigned roles of reviewer.  If vote does not pass it will get recycled for revision and the governance reviewers, when they exist as roles would give feedback to the team and community of the changes that must take place to pass their review or alternatively if it failed the vote then they willgather community feedback on it to return to the development team.  An example of how roles can work would be [Dapp Hub's DS Role Repo](https://github.com/dapphub/ds-roles/) and [DS Auth Repo](https://github.com/dapphub/ds-auth/)  which are used on many Ethereum governance projects such as AAVE, E.

## Kin Reserves

The Kin Reserves according to [the whitepaper](https://whitepaper.io/document/71/kin-whitepaper) is meant to mandate promoting adoption and growth of the Kin Ecosystem.  This has mostly been allocated in the past towards the Foundation.  That pot of funds can be used in whatever way would best suit the growth of the ecosystem and whatever people can imagine for the best method to do so. Kin Reserves would be allocated by creating governance proposals.  This could initially start small as just a suggestion to its current custodians but the intent is that eventually the governance system and its security and roles apartus would control the wallet that holds the Kin reserves.

## KRE 

Similar to the Kin reserves, it would have to start as a suggestion to current custodians of the KRE that money be allocated to this governance mechanism.  Eventually the KRE can be decided upon by community members via the goverance protocol.

## Audits
TBD

## Connect with the community

You can join the Kin [Community Discord](https://discord.gg/9Nr2V7UBAT), [KinShips](https://t.co/woIKtqPpHU), and [PumpkinLabs](https://discord.gg/Ppu2vesW)
