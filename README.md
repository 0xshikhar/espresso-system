# Espresso Rollup for Cross-Chain NFTs

## Overview

The Espresso Rollup is designed to facilitate cross-chain NFT transactions, providing a scalable and efficient solution for managing NFTs across different blockchain networks.

## Local Development Setup

To set up the local development environment, run the following command:

```
$ docker compose up
```

## Common Errors

If you encounter the following error:

```
error acting as staker                   
err="error advancing stake from node 2 (hash 0xee288c5dcc61206e6868fa7a01da6abaabe22d6c849718a47eb361857b7e8dd8): error generating node action: block validation is still pending"
```

This error is expected when running a newly deployed rollup with no recent activity. It occurs because there are no new nodes to stake on or no new batches have been posted. Simply let the system continue running.

## Main Contracts Data

### Deployed Contracts

- **RollupProxy Contract**: created at address: `0x9002432Cb8728e236Ec56657f92c70D5cb373f0D`
- **Inbox (proxy) Contract**: created at address: `0xA13a71A6995254950BcdE216F675B867C7EB9882`
- **Outbox (proxy) Contract**: created at address: `0xA3b0CFEb2e8198A58525AE7401a3097Fa4f4c4c0`
- **rollupEventInbox (proxy) Contract**: created at address: `0x5215cA06FfEc5Ca7117896bbf7695c3E4e2A0F2B`
- **challengeManager (proxy) Contract**: created at address: `0xAF9280C88e2491c1d019e1149A05f54D630911A1`
- **AdminProxy Contract**: created at address: `0x2a1A72B0479b778741f09e85d2Cd01c7e68EDe2D`
- **SequencerInbox (proxy)**: created at address: `0xF25D2E13a698B9BB9BB5dC0e0A9b2fEc28E4B68C`
- **Bridge (proxy) Contract**: created at address: `0x89D595aC37C114d7CeC41bC10b18F95b240AdF15`
- **ValidatorUtils Contract**: created at address: `0x3Ed87E3969F5d28a3DC9889b70eff21B8Df5d2aF`
- **ValidatorWalletCreator Contract**: created at address: `0x41ab8cf665f931B010d13D46b5178551594EE2DA`
- **UpgradeExecutor**: `0x58a37b72660839D3B1007CF418425e936AAf8A5f`
