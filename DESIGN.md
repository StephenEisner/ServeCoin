# Guidelines
Things must be effectively modularized. In a rapidly changing ecosystem it must be easy to stay current fixing components that become dated.

# Core Interaction
1. ### Share Identifying Information
In this stage information is posted to some market record. This would include all relevant information to the transaction
- Identifing information
    - license [D]
    - license plate [D]
    - some sort of proof of no criminal record 
    - pictures
    - social media?
    - Information stored from part 5
    - number of passengers [P]
    - willing to have other passengers [P]
    - space in car [D]
- Transaction Informaton
    - Ride path [P]
    - Payment offering [P]
    - Current location [D]
    - Payment request [D]


2. ### Agree to Transact
A driver and a passenger who have entered the market will match, and the exact transaction rules worked out

3. ### Execute Transaction
Whatever actions need to be completed to execute the transaction is here.
During this period parts of the payment may be executed
   #### for example 
        - when the driver and passenger agree a fee is already payed so if the passenger cancels the driver is protected
        - as the ride continues some of the main payment may get executed

4. ### Verify Complete Transaction
At this step all payment should be executed.
The mechanism for this is hard to design, maybe will use location to verify or something like that.

5. ### Share Qualitative Information
Optionally leave a review for the passenger or driver.
This could be standardized by the market as being stars, or qualitative categories or any number of things.

# The Exchange
This part needs some very clear design and consideration before being built. This exchange has to be something that can be easily supported by a distributed ledger. 



# Design TODO
- [] Decide if this should be built on the EVM, using plutus or marlowe, or be a new chain
  - [] Investigate EVM and Solidity
  - [] Investigate Plutus and Marlowe

- [] Design complete transaction contract and all the phases (step 3)

- [] Determine how to verify a complete transaction (step 4)

- [] Finish Design Sheet

- [] Read through p2p ride-matching document and figure out which algorithms are best

