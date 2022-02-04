# Tokenomics

## PiFi

![](../.gitbook/assets/pigletz-token-32.png)

PiFi is a ERC20 / BEP20 token. Its contract is [0xf7405eff16ff7e96898b6b40497a54894fc86c44](https://bscscan.com/token/0xf7405eff16ff7e96898b6b40497a54894fc86c44)

Each piglet mints internal PiFi token every 24 hours.

![PiFi Miner](../.gitbook/assets/tokenomics-step-1.png)

The amount minted is calculated by the formula

$$
mint_{24h} = mint_{base} \times \sum{boosters}
$$

<table><thead><tr><th data-type="number">Level</th><th data-type="number">Base Mint</th></tr></thead><tbody><tr><td>1</td><td>167</td></tr><tr><td>2</td><td>250</td></tr><tr><td>3</td><td>417</td></tr><tr><td>4</td><td>500</td></tr></tbody></table>

## Cap

Each Piglet has a cap of the total possible PiFi tokens to be minted which is 2,000,000 PiFi.

Getting into an account that the total supply of all Pigletz is 12,345 the max supply of the PiFi token will be:

$$
12,345 \times 2,000,000 = 24,690,000,000
$$

## Liquidity

The SalesManager allows us to mint PiFi that will be used to create the initial Liquidity Pool. The amount of PiFi we can mint is limited to the total minted Pigletz with the following formula:

We will create the Liquidity Pool at [PancakeSwap](https://pancakeswap.finance) investing BNB and PiFi once we mint at least 10% from the total supply of the Pigletz.

$$
PiFi_{max} = Pigletz_{minted} \times 10,000
$$

After creating the pool we will revoke the minting rights to the PiFi token and Pigletz will be the only generator of new PiFi tokens.&#x20;

![](../.gitbook/assets/tokenomics-diagrams.webp)
