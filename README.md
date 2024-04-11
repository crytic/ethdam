# Ethdam - Trail of Bits

During [EthDam](https://www.ethdam.com/), up to $2k are to be the won for the best project(s) using [Slither](https://github.com/crytic/slither) (see [ethdam hackathon rules](https://docs.google.com/document/d/1wpQ7XYZE5wTUW5wRCzHPaHNYfsh16xUPwf6WvlbuZlc/edit#heading=h.mzzlyq3xgrer)) 

## Ressources
- On site event
  - `Slither: introduction to custom analysis - Trail of Bits` - 3:15pm, Studio
- [Slither](https://github.com/crytic/slither) - Github repo
- [Slither API walkthrough (video)](https://www.youtube.com/watch?v=Ijf0pellvgw) ([slides](./pre-event-workshop.pdf))
- [secure-contracts.com/slither](https://secure-contracts.com/program-analysis/slither/index.html) - exercises and tutorials on Slither's API
- [Ethdam's discord]( https://discord.com/invite/XJVjpCqQBz): #trail-of-bits

## Themes

We look for projects exploring one of these themes:

- UX/UI: leverage slither through an interfaces. Ex:
  - Adapt [`slither-lsp`](https://github.com/crytic/slither-lsp) and its new vscode plugin with a new handler (see TUTO)  
- On-chain monitoring (aka [slither-read-storage](https://github.com/crytic/slither/blob/master/slither/tools/read_storage/README.md) on steroids). Ex:
  - Show the state variables evolution over time/block number
  - Show the contract relationship (caller, called, what functions are called, etc)
- Machine learning & slither. Ex: 
  - Build a RAG with langchain to do code understand / QA bot on solidity
  - Use LLM to enhance the detectors filtering

You do not need to follow the examples provided, we are also looking for ideas and exploratory projects.


## Judging critera

- Novelty
- Reliance on slither (the more the project extends and uses slither, the better)

## Registration process

Registration is optional, but we can help you better if we know about your team.

To register, send a DM on discord to `josselin_trailofbits` with the team name and the members list (ex: github username + discord usernames).


## Requirements

- Python
