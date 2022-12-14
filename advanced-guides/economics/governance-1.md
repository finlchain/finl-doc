# Token Economy

## Reward Policy

The currency supplied by year is diverse for the expansion of the Final Chain ecosystem, reserve, team, marketing, sales, etc. used In addition, a certain amount may be incinerated at the discretion of the DGOS Foundation to maintain its value.

## Fee Policy

Fees are used for deflationary purposes. In other words, all fees are incinerated. Ecosystem members must submit a fee each time a contract is generated.

### Transaction model

Transactions consume network resources. Costs are incurred to consume these network resources. In t he case of network resources, since they are public goods, the minimum cost is reasonable in actual use . In order to minimize these costs, 5,000 network points are paid per day at the time a transaction occur s. After one day, the remaining network points cannot be used and a new 5,000 network points will be paid. A day is from 00:00:00 to 24:00:00 UTC time. 1 network point equals 1 goofy. However, this network point cannot be changed to a token.

By staking Fins, the cost of network resource consumption can also be reduced. If Fins are staked for 3 days, 10 additional network points can be used per 1 fin per day after 3 days (72 hours) have elapsed. This network point cannot be changed with a token (Fin). After one day, the existing network points cannot be used and are recharged at 10 network points per Fin.

In order to consume network resources, network points can also be purchased using Fin. At this time, 1 Fin = 1,000,000 network points are charged, and all used Fins are burned. Charged network points cannot be changed to tokens.

The transaction fee rate can be obtained according to the first byte unit amount. The unit of Fee is goof y, and it is expressed as 1 Byte = 10 goofy. For example, if a transaction with a size of 100 bytes is genera ted, the fee will be 1,000 goofy.

In addition, when a transaction between clusters occurs, the fee rate is weighted. Each cluster receives user registrations according to local distances. Transactions that occur between clusters have strong long-distance transactions.

When a transaction occurs, check whether there are enough network points to transmit the transaction according to the following priorities.

1. Check 5,000 network points that are automatically recharged per day.
2. Check the network points generated by staking.
3. Check if there are network points purchased from the transaction originating wallet.

If all are not enough, the transaction transfer fails.

### Contract model

The contract consumes CPU and Memory of mainnet participating nodes. In the case of CPU, resource consumption occurs whenever a contract is executed, and in the case of memory, consumption occurs w hen a contract is saved. CPU andIn the case of memory, since it is a consumer product, it must be handl ed separately from transactions. The fee for such consumption is expressed as Power. 1 Power equals 1 0 goofy. CPU consumption is expressed as Execution Power, and Memory consumption is expressed as S tack Power.

Power is not automatically recharged like network points and must be purchased using Fin. After purchasing 100,000 Power with 1 Fin, you can use it immediately. Power can be converted into tokens (Fin) as needed. However, the conversion from Power to Fin takes 3 days (72 hours).

### Memory consumption

Since the contract once stored in the memory must be stored permanently, the corresponding fee must also be quite large. This fee is incinerated in its entirety and is a fixed value as shown below.

1. Token Generation: 1000 Fin (100,000,000 Stack Power)
2. Account Creation: 1 Fin (Activation Fee, 10 0,000 Stack Power) - Minimum Maintenance Cost

### CPU consumption

Each time the contract is executed, 100 Execution Power is used. At this time, all the power used is incinerated.
