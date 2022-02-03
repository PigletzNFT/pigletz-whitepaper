---
description: >-
  Piglets feature DeFi elements. On a first place the Piglet itself mints its
  own token called PiFi. We  offer all Pigletz owners the following additional
  services:
---

# DeFi

### Staking

![Staking](../.gitbook/assets/defi-piglet-staking.svg)

It allows Pigletz to be staked into the staking contract for a specified period. During that period a special booster with 50% boost will be activated. After unstaking the booster will be deactivated.&#x20;

While staked the Pigletz will be out of the market, locked into the contract so no one can transfer them or break them. However they will continue to produce PiFi tokens.

### Lending

![Lending](../.gitbook/assets/defi-lending.svg)

Lending allows Pigletz owners to use their piglet as a collateral and to lend PiFi tokens.&#x20;

This works in the following way:

1. First we evaluate all tokens inside the piglets using their BUSD value in PancakeSwap.
2. The total value of the loan cannot exceed <mark style="color:yellow;">80%</mark> of the total piglet evaluation. The percentage is not fixed yet.&#x20;
3. The user chooses amount and a period.
4. The PiFi for the loan comes from Liquidity Providers.&#x20;
5. The user is obliged to return the PiFi loan with interest within the specified period.&#x20;
6. In a case the user returns the correct PiFi amount the piglet locked into the Lending Contract is transferred back to the user.
7. Otherwise if the PiFis are not returned within the predefined period the Piglet is broken automatically by the contract and all the tokens within it are swapped in PancakeSwap for PiFi tokens which are later distributed as rewards to the Liquidity Providers.
