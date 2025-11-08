# awesome solana

I mean literally, solana is awesome ! As a prior distributed/database engineer, I can't wait to explore the beauty of Solana. A good tangent move is to learn by doing(programming) on the platform. This repo is for solana enthusiasts that can utilize programs under different folders to improve solana skills. I will continue uploading my discoveries that I learnt. See subfolder README to learn commands.

## Access mainnet account cloned by surfpool

want to know how to test and debug program locally with acccounts from mainnet, just like `foundry's fork-url` ? Check this out, I went through this by [Solandy](https://x.com/heyandys) tutorial [video](https://www.youtube.com/watch?v=Flgmt2GEkks)

## counter dApp

- a counter state is created by every initalize instruction
- As comparison, a pda-counter is created by separate instruction
- show these two kinds of counter in the same UI dApp

## native solana development

- no anchor involvement (aiming to understand what's happending under the hood)
- Use borsh to serialize/deserialize the instruction data
- Mint spl token each time a movie review or comment is created

# solana commands examples

```
curl -x localhost:7897 https://api.devnet.solana.com \
                                -X POST \
                                -H "Content-Type: application/json" \
                                -d '{"id": 1, "jsonrpc": "2.0", "method": "getBlockProduction"}'

# confirm details of a given tx
solana confirm -v FRwf7PTx4EJCLB6dpQFU6RRPHGsQKMVCtKG7pKQVkZqxa8mT3rMBPtG16j3mTnB9rTRbVesB9qoY3eswziGD9w1
```