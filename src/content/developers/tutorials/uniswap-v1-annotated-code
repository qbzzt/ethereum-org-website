---
title: "Uniswap V1 Contracts Walk-Through"
description: Explanation of the Uniswap V1 contracts
author: Ori Pomerantz
lang: en
sidebar: true
tags: ["vyper", "uniswap"]
skill: medium
published: 2021-05-01
---

## Introduction {#introduction}

One of the most common uses for Ethereum is for a group to create a tradable token, in a sense their own currency. These tokens typically follow a standard,
[ERC-20](/developers/docs/standards/tokens/erc-20/). This standard makes it possible to write tools, such as liquidity pools and wallets, that work with all ERC-20
tokens. In this article we will analyze the
[OpenZeppelin Solidity ERC20 implementation](https://github.com/OpenZeppelin/openzeppelin-contracts/blob/master/contracts/token/ERC20/ERC20.sol), as well as the
[interface definition](https://github.com/OpenZeppelin/openzeppelin-contracts/blob/master/contracts/token/ERC20/IERC20.sol).
