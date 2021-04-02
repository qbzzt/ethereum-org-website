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

[Uniswap](https://uniswap.org/), which allows for decentralized trading between any two ERC-20 currencies, is one of the basic 
building blocks for defi, decentralized finance. In this article we'll go over the [Vyper](https://vyper.readthedocs.io/en/latest/)
source code for [Uniswap V1](https://github.com/Uniswap/uniswap-v1).

### Why? Later Versions are Available {#why-v1}

As I am writing this Uniswap v1.0 is already over two years old, v2.0 is the one in most common use, and 
[v3.0 is almost ready](https://uniswap.org/blog/uniswap-v3/). Why then explain the old version? 
Because it is simpler. 
