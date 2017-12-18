The most up-to-date version of this file is here:
https://docs.google.com/document/d/1K8-1hf--uiLPKKK3xIrFXe_JjpkL6gCZctSdKMQtm8c/edit?usp=sharing

# [New coin proposal: SrcCoin (XSC)]
- Source code embedded in the blockchain
- Code included in the chain as a series of git commits


- When new commit is added to the chain in the "master" branch, auto update self
  - 50% of the voting power has to be in favor of the new update
  - Voting power is decided based on “github value”
  - Github value is derived running a pagerank-like algorithm on the people in question
  - The github accounts are nodes in the network, and followers are “links” linking to the nodes
  - The pagerank algorithm then decides how much weight to put on a specific account
  - If updated code fails to run, fallback to previous stable version


## [Possible extensions to XSC]

 - **PirateCoin**
   - Voting power based on Torrent seeding stats and Website visitors


 - **SocialCoin**
   - Voting power based on “pagerank” of various social network accounts


## [Implementation]

Encouraging multiple implementations, each having their own “master” branch within the blockchain.


## [Protocol]

Thinking of making it a stateless HTTP-based API, where you don't need to run a special client, just setup a website and you're done.

## [Discuss]

Telegram group: https://t.me/joinchat/HSq7QA9shlCcFDuniuKCdg
