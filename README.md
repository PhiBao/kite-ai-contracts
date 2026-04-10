# Kite AI — Verified Contract Sources

Solidity source code extracted from [kitescan.ai](https://kitescan.ai/) verified contracts on Kite AI chain (Chain ID 2366).

These files are used as references for a Code4rena bug bounty submission. All source is publicly verified on-chain.

## Contract Addresses

| File | Address | Explorer |
|------|---------|----------|
| StakingVault.sol | `0x23f7b52E2830C66f88EFc1f35b8a6a4AAe218dCA` | [kitescan](https://kitescan.ai/address/0x23f7b52E2830C66f88EFc1f35b8a6a4AAe218dCA?tab=contract) |
| StakingVaultOperations.sol | `0x6b5ef85BED3FB78bdFC50417555011A22616d169` | [kitescan](https://kitescan.ai/address/0x6b5ef85BED3FB78bdFC50417555011A22616d169?tab=contract) |
| StakingVaultStorage.sol | (library, bundled with above) | — |
| StakingVaultInternals.sol | (library, bundled with above) | — |
| KiteStakingManager.sol | `0x4fA25b3be31A915EE3b7d021aC657702C3e72e74` | [kitescan](https://kitescan.ai/address/0x4fA25b3be31A915EE3b7d021aC657702C3e72e74?tab=contract) |
| StakingManager.sol | (base contract of KiteStakingManager) | — |
| RewardVault.sol | (referenced by KiteStakingManager) | — |

## Source Attribution

- `StakingManager.sol` is modified from [ava-labs/icm-contracts](https://github.com/ava-labs/icm-contracts/blob/main/contracts/validator-manager/StakingManager.sol)
- `StakingVault*.sol` are original Kite AI contracts (BUSL-1.1)
- `KiteStakingManager.sol` and `RewardVault.sol` are original Kite AI contracts (MIT)
