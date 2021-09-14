# blockchain-developer-bootcamp-final-project

Final project of ConsenSys Academy Bootcamp 2021

DCA when Gas is low
======

Workflow:
---

![Diagram](/Final_Project.png)

1. User login into the dapp
2. Answer questionnaire to define investor profile (budget, frequency, timeframe)
3. A limit order or a batch of orders gets created
4. Wait for gas to go below certain parameter (Even using a L2 solution this dapp will wait for the best time to place orders)
5. Executed the order or batch of orders
6. Create an NFT with time lock using the info provided by user
7. Send a notification to user's wallet using EPNS to let him/her know about this
