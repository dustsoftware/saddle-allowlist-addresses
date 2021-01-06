# saddle-allowlist-addresses

Saddle is launching with a [guarded
launch](https://medium.com/electric-capital/derisking-defi-guarded-launches-2600ce730e0a)
called **Proof of Governance** (PoG) to protect our users with certain
limits and discourage sybil attacks.

For LPs to qualify for PoG, an address must have demonstrated active network
participation in one of the following ways:

- On-chain voting or delegation (MKR, COMP, YFI, YAM, CRV, UNI, UMA, Moloch DAO)
- Off-chain voting on [Snapshot](https://snapshot.page/#/) (all protocols)
- Staking SNX and minting sUSD (>$20)

The cutoff date for all activity is October 1st, 2020 unless otherwise noted.

## On-chain voting or delegation

On-chain voting or delegation activity in the following protocols was
considered:

| Name | Type |
| --- | --- |
| COMP | voters & delegators |
| YFI | voters |
| UNI | voters & delegators (pre January 1st, 2021) |
| UMA | voters |
| Moloch DAO | voters |
| MKR | voters |
| YAM | delegators |
| CRV | voters & escrowed voters |

This data was queried using [Dune Analytics](https://duneanalytics.com/) and
the query is available [here](https://explore.duneanalytics.com/queries/16578/source).
The query results have been exported in CSV format and are available [here](dune.csv).

Special thanks to [Jon Itzler](https://twitter.com/jonitzler) for his help with
collecting this data.

## Off-chain voting on Snapshot

The [Snapshot Labs](https://twitter.com/snapshotlabs) team was kind enough to
export this data for us, special thanks to [fabien](https://twitter.com/bonustrack87).
The data is available [here](snapshot.csv).

## Staking SNX and minting sUSD (>$20)

This data was also queried in Dune using the [Issued](https://docs.synthetix.io/contracts/source/contracts/Synth#issued)
event emitted by the Synthetix contracts.  The query is available as a subquery
[here](https://explore.duneanalytics.com/queries/16578/source).
