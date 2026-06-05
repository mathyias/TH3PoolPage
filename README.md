# TH3PoolPage

Mining pool frontend for TH3Chain.

## Live site

https://miner.th3chain.cloud

## Pool endpoint

```text
stratum+tcp://pool.th3chain.cloud:3333
```

## Miner example

```bat
rigel.exe -a kawpow -o stratum+tcp://pool.th3chain.cloud:3333 -u YOUR_TH3_ADDRESS -p x
pause
```

## Features

- Pool overview
- Start mining guide
- Miner address panel
- Worker status
- Accepted and rejected shares
- Pending rewards
- Recent payouts
- Pool statistics
- Automatic payout information

## Pool rules

- Algorithm: KAWPOW
- Pool fee: 1.5%
- Minimum payout: 500 TH3
- Payout cron: every 10 minutes
- Reward per block: 2137 TH3

## API dependency

https://pool.th3chain.cloud/api/pool/stats

## Miner panel endpoint

```text
https://pool.th3chain.cloud/api/miner/:AdDRESS
```
