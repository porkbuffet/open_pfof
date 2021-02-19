# open_pfof
open payment for order flow

open source project intended to democratize information in financial markets

general idea:
Client will send a copy of every order to open_pfof, which will be exchanged for payment via smart contract.  This idea is more naturally suited towards API brokerages (specifically the case where the client is generating a steady stream of orders which can then be exchanged p2p over tcp, more thought will need to be put into how to handle human orders).  A cloud server (run by a non-profit org) will optionally paper trade every order received & display a public track record of order flows for each opt in contributor.  Alternatively, data producers can place the burden of validation on data consumers, who then must validate the returns of the order flow themselves (I know Alpaca has free paper trading accounts, but that is just one example).  Data producers set the price of their order flow.  If we go with the cloud server idea, one idea is to tax the minimum amount necessary on each transaction to cover cloud hosting fees.    

general goals:
1.  Archtitect & implement smart contract
2.  Architect & implement data transfer

If you would like to contribute, just leave your mark somewhere on this repo :)
