# Ranked Choice Delegation

Delegation is a great way to extend your voting power to someone that aligns with your values. However, it’s not great if your delegate doesn’t vote on proposals! Ranked choice delegation allows you to specify an ordered set of delegates, adjusting your votes down the list to an active delegate if your top choices misses a proposal.

Rancho Del is lets you delegate your voting power to a set of addresses. If A delegates to B, C, and D and everyone votes on a proposal, then A’s voting power remains with A. If A and C do not vote, but B and D do vote, all voting power is given to B. This strategy could also be extended to weight the votes between B and D in this scenario, if preferred.

In this strategy, the sub strategies defined in params are used to delegate vote from one address to another.

Here is an example of parameters:

```json
{
  "address": "0x6b175474e89094c44da98b954eedeac495271d0f",
  "symbol": "RANK",
  "decimals": 18
}
```
