# Liquidity Providing

Abundant liquidity is essential to create a slippage-free trading environment in DEX. Users who provide such liquidity are called Liquidity Providers (LPs). When NEURONswap provides liquidity to the pool, a Liquidity Pool(LP) token is created as proof of this, and the LP token is deposited in the pair through staking. The amount a user stakes divided by total staking amount indicates your stake in the pair. To withdraw assets deposited in the pool, the assets are returned from the protocol’s contract through Unstake.

Liquidity providers are rewarded with NR tokens and fees as a reward for providing liquidity to the pool through staking for the staking period. Transaction fees are credited to the pool, and when it is withdrawn, fees are included according to the exchange rate.

The liquidity pool of NEURONswap can be freely created by any protocol participant, and is divided into NR_2, NR_1, NR_0, depending on the amount of neuron token distribution. It is classified according to the importance of the tokens provided by the liquidity pool and their contribution to the protocol. Users can receive a larger distribution of NR tokens for NR_2 than other pairs. NR tokens are not distributed for NR\*0 which is new projects or pairs that contribute relatively little to the protocol.

If liquidity is supplied to a pool that is undergoing a token airdrop, airdrop tokens are distributed according to the share.

### **Impermanent Loss(IL)**

Impermanent loss occurs when the price of the two deposited tokens changes. In general, as the price difference between the two tokens increases, the size of the non-permanent loss increases proportionally. In the case of liquidity providers, there are cases in which the loss of token quantity due to token price fluctuations is greater than the profits obtained from pool fees and token rewards. If the price of one token increases by 1.25 times, the LP will lose 0.6% of the original quantity, and if it increases by 5 times, the LP will lose 25% of the original quantity.

* 1.25x price change = 0.6% loss
* 1.5x price change = 2.0% loss
* 1.75x price change = 3.8% loss
* 2x price change = 5.7% loss
* 3x price change = 13.4% loss
* 4x price change = 20.0% loss
* 5x price change = 25.5% loss
