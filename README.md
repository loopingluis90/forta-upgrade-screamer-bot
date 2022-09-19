# Upgrade Screamer Bot: Real-time monitoring of tokens upgrades

Upgrade Screamer Bot monitors changes in the code of token contracts (also known as upgrades). It also analyses the actions executed together with this change. Modifications of token code can affect the behaviour and economics of the asset, crucial information for users and protocols which work with them on a daily basis.

[Forta](https://forta.org/) is a real-time detection network for security & operational monitoring of blockchain activity. This bot allows users and protocols to get notified (via Email, Telegram, Discord, Slack or Webhook) about upgrades of tokens, so they can react to the changes accordingly. Forta supports a great variety of notification channels, so users can receive alerts via their preferred means.


## The problem

Upgradeability is a bug! This is one of the most controversial and recurrent topics in the ecosystem. Upgradeability mechanisms allow developers to adjust and change contracts code according to market, business and user requirements. However, it introduces a great risk vector since developers can change the behaviour of their contracts at their will. This is particularly important for token contracts because these are used by millions of users and thousands of applications every day across the ecosystem.

Code changes can alter the contract behaviour, modify the economics of the token, introduce new features, include unintentional vulnerabilities and even affect other contracts' functionality and security (integrators, like protocols, aggregators, wallets, etc).


## The proposal

This proposal aims to develop a Forta bot that monitors on-chain token contract upgrades. Each time a token performs a contract upgrade, the bot will raise an alert providing useful information about the change. The bot can analyse a variety of aspects:
 - Who was the executor of the upgrade: EOA, contract or governance system (e.g. DAO).
 - Differences in code size between new and old implementation contracts.
 - Changes in holdings of the contract (ETH and token balances).
 - Detection of tokenomics changes: total supply change, mints, burns or transfers.
 - Detection of role changes: granting or revoking new roles in the system.
 
 With Forta, Protocol users can subscribe to alerts so they can be notified when one of the tracking tokens has changed. As soon as these changes happen, users and protocols will be notified so they can react accordingly. 
 
 
Upgrade Screamer Bot is a step ahead in the safety frontier. It helps users and protocols to monitor changes in the tokens they work with, increasing their reaction and safety capacity. It become a crucial tool for any application in the ecosystem because it helps to mitigate incompatibility issues in integrations (especially in DeFi, aka money legos).
 

## About me

Spanish backend developer with great experience in building TypeScript applications. Learning Solidity in his free time and eager to contribute to the space.
