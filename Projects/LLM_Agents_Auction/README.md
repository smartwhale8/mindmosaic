# Implementation of a Vickery Auction Platform using Large Language Model (LLM)
## Objective
The goal of this project is to implement a Vickrey auction [1](https://en.wikipedia.org/wiki/Vickrey_auction) using Microsoft Autogen [2](https://github.com/microsoft/autogen)
. 

We will be leveraging LLMs [3](https://en.wikipedia.org/wiki/Large_language_model) (Large Language Model) to create auctioneers and bidders in the intelligent auction environment.

The implementation of the project includes the following:
1.  A base task - implementing an auction between multiple agents
2.  A challenge - running multiple auctions simultaneously where the agents get to select the auction of their interest.

## Implementation Plan
1. Gain familiarity with Microsoft Autogen: First, we’ll create a simple agent and communicate with it with
Microsoft Autogen to become familiar with the platform. (This step has already been completed)
2. Implement simple communication between agents: Next, we’ll create multiple agents and develop
communication between them.
3. Implement FIPA communication between agents: We’ll then implement communication using the fipacontract-net protocol.
4. Implement a Vickrey auction: Once communication has been established, we can implement an auction
using the same base logic developed for assignment 2.
5. Implement multiple Vickrey auctions: Once we have one auction working, we can expand the logic to
multiple auctions.
6. Clean up output logs: Clean up our code and make sure that the logs displayed by our code are useful and
formatted in a clear way.

## Challenges and Mitigation
1. Working with Autogen: Having never worked with Autogen before and learning a new platform can be challenging. However, there seems to be tutorials and documentation online for us to learn how to use it efficiently.
2. Implementing multiple agents and ensuring proper communication between them: Sometimes when using LLMs such as ChatGPT, it unilateraly decides to change/simplify the output or skips certain repetitive parts. We will have to make sure that it communicates always using the proper protocols as specified in the auction. 

## Expected Outcome
A fully functioning LLM-based agent communication system for running one or more Vickrey auctions. The code will
also be properly formatted with insightful outputs to the console. 

## Conclusion
Through the implementation of Vickrey auction protocol, this project aims to provide insights into the dynamics of
truthful bidding and the outcomes of this specific auction format. 

Further, it shall highlight the potential of LLMs in intelligent auction environments.

## References
1. Vickery Auction, https://en.wikipedia.org/wiki/Vickrey_auction
2. Microsoft Autogen, https://github.com/microsoft/autogen
3. Large Langugage Models (LLMs), https://en.wikipedia.org/wiki/Large_language_model