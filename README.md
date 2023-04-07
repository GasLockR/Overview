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


- Problem / existing solutions
  -> 1. No way to edge against on-chain risk of gas price spike and ensure stability of their transactions. This is about businesses not being able to operate because gas prices went up. Or users not being able to use services for the same reason.
  
  -> 2. UX is terrible right now for on-chain transactions: 
    
    i. You have to manually approve transactions and have ethereum to cover fees
      With account abstraction (EIP-4337), you can have paymasters that pay for your gas fees so transactions are more flexible - you don't have to sign and submit yourself - someone else can do that for you. And someone else can pay the gas for you meaning you don't need any tokens.
    
    ii. You have to think about what gas price to specify which shouldn't be the user's concerns and it often confuses new web3 users. With our financial derivatives product, other wallets or services can build abstractions for gas fees so that the user doesn't have to worry about it. For example, they can pay a monthly fee to submit up to 100 transactions in a month.

- The future / ideal solution
  
  -> 1 (i) In the future businesses will operate fully on-chain and users will use many services on-chain.
  
  -> 2 (i) In the future we'll have account abstraction with paymasters so this will exist in some shape or form. We are building an efficient protocol that is close to optimal because it tracks gas prices in realtime so this can be used as infrastructure to build paymaster services.
  
  -> 2 (ii) In the future you will have much more friendly wallets where the user doesn't have to think about gas prices.

- What we built to address these problems / Our solution
  
  -> We built the first gasFi protocol that can be used as a foundation to build other services. We built an insurance service as a demonstration how GasLockR can be used as financial infrastructure to build amazing services.
  
  -> GasLockR is an insurance service that aims to provide users with protection against Ethereum gas price fluctuations
  
  -> Through a simple web GUI users can purchase insurance specifying how long they would like the protection for and pay a small premium to be protected against tail risk of gas fluctuations.

- Demo
