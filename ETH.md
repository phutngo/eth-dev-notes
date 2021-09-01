# Ethereumn Devevelopment Knowledge Base

- [Ethereumn Devevelopment Knowledge Base](#ethereumn-devevelopment-knowledge-base)
  - [Overview](#overview)
  - [Topics](#topics)
  - [To Do](#to-do)
  - [Typical Interview Process](#typical-interview-process)
  - [Other](#other)
  - [Basic](#basic)
  - [NFT](#nft)
  - [Defi](#defi)
  - [Security](#security)
  - [Gas Optimization](#gas-optimization)
  - [Practical Usage Details](#practical-usage-details)

## Overview

This document is for me to capture notes of key concepts that will help provide a knowledge base for years to come as well as help prepare for interviews.

It should be concise and help jog my memory.
It will link to other documentations that would detailed out these concepts.

## Topics

1. Walkthrough of codebase I developed.
   1. This means that for each of my bigger projects such as Kaura, NFT, I need to architect it well, have tests, and have a summary doc of key architectural decisions or tradeoffs that I've made.
2. Creating basic contracts
   1. Escrow
   2. Contract Wallet with features
3. Tests
4. EVM
   1. CREATE2
   2. SSTORE/SLOAD, bytes, strings
   3. GAS Optimisation

## To Do

1. [x] [Concensys Basic Training](https://github.com/ConsenSys-Academy/basic-training)
2. [ ] [Eth Yellow Paper](https://ethereum.github.io/yellowpaper/paper.pdf)
3. [ ] Testing

## Typical Interview Process

[reddit](https://www.reddit.com/r/ethdev/comments/pf09ke/what_are_ethdev_job_interviews_like/)

1. Cultural fit and experience.
2. Take home test or walkthrough of codebase you've developed. Tests have been based around creating a basic contract (e.g. escrow, contract wallet with features) and tests to validate.
3. Tech interview asking questions about the test and the EVM. For example have had questions regarding CREATE2, SSTORE/SLOAD, bytes/strings, gas optimisation.
4. Offer/no offer!

## Other

:scroll: [emojis cheatsheet](https://www.webfx.com/tools/emoji-cheat-sheet/)

## Basic

## NFT

## Defi

## Security

## Gas Optimization

## Practical Usage Details

[Scaffold-eth](https://github.com/austintgriffith/scaffold-eth) is a great Javascript framework for Ethereum developers as it’s written using React.js and Hardhat. However, note the above warning about the difficulties of altering React.js application if you’re not comfortable!

Other framework options for blockchain development you’ll see are:

Truffle Boxes (Check out this Truffle + Infura + React box, for example)
[Create-eth-app](https://github.com/paulrberg/create-eth-app), a variation of the very popular create-react-app setup command for React projects
