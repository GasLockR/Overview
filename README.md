# Overview
Description and structure of GasLockR

Our project offers a diverse range of insurance services for gas prices on Layer-2, tailored to different time periods. In addition, we are introducing advanced financial derivative products specifically targeting gas price fluctuations.

This is a brief introduction to our product: We have designed a comprehensive suite of solutions that cater to the unique needs of users in the Layer-2 ecosystem. Our insurance services provide coverage for various gas price scenarios, allowing users to hedge against potential risks and maintain the stability of their transactions. Furthermore, our innovative financial derivative products enable more sophisticated market participants to capitalize on gas price movements, creating opportunities for enhanced returns and risk management.

We believe that our product's versatility and adaptability will appeal to users who recognize the growing importance of Layer-2 solutions and the increasing demand for tools that facilitate efficient, secure, and cost-effective transactions within the Ethereum network.

Web3 adoption will take place on L2's not L1's. You will often have users and institutions submitting 100's or even 1000's of transactions per day on L2's so it's important that they are protected against the occasional event that causes gas prices to spike. For example if you are running a business on L2 that relies on submitting many transactions you would want to derisk by buying insurance.

## Features

1. Different types of insurances services.

2. Advanced financial derivative products specifically targeting gas price fluctuations.

3. Real-time calculated premium rate.

4. Intuitive line chart for available maximum coverage.

5. Aim to use Axiom as ZK proof for historical gas price.

6. Pricing model..



## Problem / existing solutions
  
  1. **Availability**: More people than ever are becoming reliant on L2's. Organisations (including DAOs) need to be able to operate through turbulent times. Services need to provide guarantees for availability through SLAs (Service Level Agreements) in order for users to trust and adopt these services. In the past base gas fees on Polygon have spiked to $200 for a simple token transfer. This makes L2's unusable at times. L2's are not currently something users and organisations can rely on all of the time.
  
  2. **Onboarding**: Users must already have tokens in their wallet to cover gas fees. This creates a chicken and egg problem where the user needs funds before they can do anything on-chain. This adds an uncessary barrier to the L2 onboarding process. Existing solutions like faucets are difficult to use and often don't provide enough to even cover the fees a lot of the time.
  
  3. **Wallet UX**: Every time a user wants to submit a transaction, they have to manually approve transactions and think about what gas price to specify. This doesn't need to be the user's concern and it often confuses new web3 users.

## The future / ideal solution
  
  1. In the future businesses will operate fully on-chain and users will use services on-chain daily. Fully on-chain DAOs will become more prevalent. They should have the confidence that they will be able to continue operating through unexpected events and volatile gas prices.
  
  2. (i) With account abstraction (ERC-4337), you can have paymasters that pay for your gas fees - someone else can do that for you. And someone else can pay the gas for you meaning you don't need any tokens. However the paymasteres need a way to protect themselves against

  2. (ii) In the future you will have much more friendly wallets where the user doesn't have to manually approve every transaction or even think about gas prices.

## What we built to address these problems / Our solution
  
  We built the first GasFi protocol that can be used as foundational on-chain infrastructure to build other services that will solve the reliability, onboarding and UX problems we face today.
  
  We provide a way to hedge against the risk of rising gas prices, allowing users and organisations to guarantee 100% reliability. Services will be able to provide SLA (Service-Level-Agreements) to their users
  
  With our financial derivatives product, other wallets or services can build abstractions for gas fees so that the user doesn't have to worry about it. For example, they can pay a monthly fee to submit up to 100 transactions in a month.
  
  We built an insurance service as a demonstration of how GasLockR can be used as financial infrastructure to build amazing services.
  
  GasLockR is an insurance service that aims to provide users with protection against Ethereum gas price fluctuations
  
  Through a simple web GUI users can purchase insurance specifying how long they would like the protection for and pay a small premium to be protected against tail risk of gas fluctuations.

## Demo

Demo video TBC.
