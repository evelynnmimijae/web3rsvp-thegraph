# web3rsvp-thegraph
Project subgraph 

This repo is part of the Web3rsvp functionality. 
The subgraph allowed me to connect the frontend of the Web3rsvp website to the contract Web3RSVP.sol so event details, including attendees and hosts can be displayed. 
The subgraph allows users to:
- search events by title, description
- filter events by date and/or date range
- fetch current user's hosted events by date (upcoming vs past)
- fetch current user's rsvp'd events by date (upcoming vs past)
- sort events by most number of rsvps
- sort events by date
- check if current user has rsvp'd to the event
- check if current user has attended the event
- fetch event details

Once the aforementioned user features are laid out, the next part of this project is to define the subgraph's settings. 
Then we go through mappings right before deploying the subgraph to the contract

For more information and context, please see Section 5 of the #30DaysOfWeb3 course by Women Build Web3 https://www.30daysofweb3.xyz/en/curriculum/5-creating-your-subgraph/0-intro-to-the-graph

Tools = @graphprotocol, The Graph, @protofire, AssemblyScript, 
