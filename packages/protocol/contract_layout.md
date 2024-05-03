## TaikoL1

| Name           | Type                   | Slot | Offset | Bytes | Contract                         |
| -------------- | ---------------------- | ---- | ------ | ----- | -------------------------------- |
| \_initialized  | uint8                  | 0    | 0      | 1     | contracts/L1/TaikoL1.sol:TaikoL1 |
| \_initializing | bool                   | 0    | 1      | 1     | contracts/L1/TaikoL1.sol:TaikoL1 |
| \_\_gap        | uint256[50]            | 1    | 0      | 1600  | contracts/L1/TaikoL1.sol:TaikoL1 |
| \_owner        | address                | 51   | 0      | 20    | contracts/L1/TaikoL1.sol:TaikoL1 |
| \_\_gap        | uint256[49]            | 52   | 0      | 1568  | contracts/L1/TaikoL1.sol:TaikoL1 |
| \_pendingOwner | address                | 101  | 0      | 20    | contracts/L1/TaikoL1.sol:TaikoL1 |
| \_\_gap        | uint256[49]            | 102  | 0      | 1568  | contracts/L1/TaikoL1.sol:TaikoL1 |
| addressManager | address                | 151  | 0      | 20    | contracts/L1/TaikoL1.sol:TaikoL1 |
| \_\_gap        | uint256[49]            | 152  | 0      | 1568  | contracts/L1/TaikoL1.sol:TaikoL1 |
| \_\_reentry    | uint8                  | 201  | 0      | 1     | contracts/L1/TaikoL1.sol:TaikoL1 |
| \_\_paused     | uint8                  | 201  | 1      | 1     | contracts/L1/TaikoL1.sol:TaikoL1 |
| lastUnpausedAt | uint64                 | 201  | 2      | 8     | contracts/L1/TaikoL1.sol:TaikoL1 |
| \_\_gap        | uint256[49]            | 202  | 0      | 1568  | contracts/L1/TaikoL1.sol:TaikoL1 |
| state          | struct TaikoData.State | 251  | 0      | 1600  | contracts/L1/TaikoL1.sol:TaikoL1 |
| \_\_gap        | uint256[50]            | 301  | 0      | 1600  | contracts/L1/TaikoL1.sol:TaikoL1 |

## TaikoL2

| Name                      | Type                        | Slot | Offset | Bytes | Contract                         |
| ------------------------- | --------------------------- | ---- | ------ | ----- | -------------------------------- |
| \_initialized             | uint8                       | 0    | 0      | 1     | contracts/L2/TaikoL2.sol:TaikoL2 |
| \_initializing            | bool                        | 0    | 1      | 1     | contracts/L2/TaikoL2.sol:TaikoL2 |
| \_\_gap                   | uint256[50]                 | 1    | 0      | 1600  | contracts/L2/TaikoL2.sol:TaikoL2 |
| \_owner                   | address                     | 51   | 0      | 20    | contracts/L2/TaikoL2.sol:TaikoL2 |
| \_\_gap                   | uint256[49]                 | 52   | 0      | 1568  | contracts/L2/TaikoL2.sol:TaikoL2 |
| \_pendingOwner            | address                     | 101  | 0      | 20    | contracts/L2/TaikoL2.sol:TaikoL2 |
| \_\_gap                   | uint256[49]                 | 102  | 0      | 1568  | contracts/L2/TaikoL2.sol:TaikoL2 |
| addressManager            | address                     | 151  | 0      | 20    | contracts/L2/TaikoL2.sol:TaikoL2 |
| \_\_gap                   | uint256[49]                 | 152  | 0      | 1568  | contracts/L2/TaikoL2.sol:TaikoL2 |
| \_\_reentry               | uint8                       | 201  | 0      | 1     | contracts/L2/TaikoL2.sol:TaikoL2 |
| \_\_paused                | uint8                       | 201  | 1      | 1     | contracts/L2/TaikoL2.sol:TaikoL2 |
| lastUnpausedAt            | uint64                      | 201  | 2      | 8     | contracts/L2/TaikoL2.sol:TaikoL2 |
| \_\_gap                   | uint256[49]                 | 202  | 0      | 1568  | contracts/L2/TaikoL2.sol:TaikoL2 |
| l2Hashes                  | mapping(uint256 => bytes32) | 251  | 0      | 32    | contracts/L2/TaikoL2.sol:TaikoL2 |
| publicInputHash           | bytes32                     | 252  | 0      | 32    | contracts/L2/TaikoL2.sol:TaikoL2 |
| gasExcess                 | uint64                      | 253  | 0      | 8     | contracts/L2/TaikoL2.sol:TaikoL2 |
| lastSyncedBlock           | uint64                      | 253  | 8      | 8     | contracts/L2/TaikoL2.sol:TaikoL2 |
| parentTimestamp           | uint64                      | 253  | 16     | 8     | contracts/L2/TaikoL2.sol:TaikoL2 |
| \_\_currentBlockTimestamp | uint64                      | 253  | 24     | 8     | contracts/L2/TaikoL2.sol:TaikoL2 |
| l1ChainId                 | uint64                      | 254  | 0      | 8     | contracts/L2/TaikoL2.sol:TaikoL2 |
| \_\_gap                   | uint256[46]                 | 255  | 0      | 1472  | contracts/L2/TaikoL2.sol:TaikoL2 |

## SignalService

| Name           | Type                                          | Slot | Offset | Bytes | Contract                                         |
| -------------- | --------------------------------------------- | ---- | ------ | ----- | ------------------------------------------------ |
| \_initialized  | uint8                                         | 0    | 0      | 1     | contracts/signal/SignalService.sol:SignalService |
| \_initializing | bool                                          | 0    | 1      | 1     | contracts/signal/SignalService.sol:SignalService |
| \_\_gap        | uint256[50]                                   | 1    | 0      | 1600  | contracts/signal/SignalService.sol:SignalService |
| \_owner        | address                                       | 51   | 0      | 20    | contracts/signal/SignalService.sol:SignalService |
| \_\_gap        | uint256[49]                                   | 52   | 0      | 1568  | contracts/signal/SignalService.sol:SignalService |
| \_pendingOwner | address                                       | 101  | 0      | 20    | contracts/signal/SignalService.sol:SignalService |
| \_\_gap        | uint256[49]                                   | 102  | 0      | 1568  | contracts/signal/SignalService.sol:SignalService |
| addressManager | address                                       | 151  | 0      | 20    | contracts/signal/SignalService.sol:SignalService |
| \_\_gap        | uint256[49]                                   | 152  | 0      | 1568  | contracts/signal/SignalService.sol:SignalService |
| \_\_reentry    | uint8                                         | 201  | 0      | 1     | contracts/signal/SignalService.sol:SignalService |
| \_\_paused     | uint8                                         | 201  | 1      | 1     | contracts/signal/SignalService.sol:SignalService |
| lastUnpausedAt | uint64                                        | 201  | 2      | 8     | contracts/signal/SignalService.sol:SignalService |
| \_\_gap        | uint256[49]                                   | 202  | 0      | 1568  | contracts/signal/SignalService.sol:SignalService |
| topBlockId     | mapping(uint64 => mapping(bytes32 => uint64)) | 251  | 0      | 32    | contracts/signal/SignalService.sol:SignalService |
| isAuthorized   | mapping(address => bool)                      | 252  | 0      | 32    | contracts/signal/SignalService.sol:SignalService |
| \_\_gap        | uint256[48]                                   | 253  | 0      | 1536  | contracts/signal/SignalService.sol:SignalService |

## Bridge

| Name           | Type                                    | Slot | Offset | Bytes | Contract                           |
| -------------- | --------------------------------------- | ---- | ------ | ----- | ---------------------------------- |
| \_initialized  | uint8                                   | 0    | 0      | 1     | contracts/bridge/Bridge.sol:Bridge |
| \_initializing | bool                                    | 0    | 1      | 1     | contracts/bridge/Bridge.sol:Bridge |
| \_\_gap        | uint256[50]                             | 1    | 0      | 1600  | contracts/bridge/Bridge.sol:Bridge |
| \_owner        | address                                 | 51   | 0      | 20    | contracts/bridge/Bridge.sol:Bridge |
| \_\_gap        | uint256[49]                             | 52   | 0      | 1568  | contracts/bridge/Bridge.sol:Bridge |
| \_pendingOwner | address                                 | 101  | 0      | 20    | contracts/bridge/Bridge.sol:Bridge |
| \_\_gap        | uint256[49]                             | 102  | 0      | 1568  | contracts/bridge/Bridge.sol:Bridge |
| addressManager | address                                 | 151  | 0      | 20    | contracts/bridge/Bridge.sol:Bridge |
| \_\_gap        | uint256[49]                             | 152  | 0      | 1568  | contracts/bridge/Bridge.sol:Bridge |
| \_\_reentry    | uint8                                   | 201  | 0      | 1     | contracts/bridge/Bridge.sol:Bridge |
| \_\_paused     | uint8                                   | 201  | 1      | 1     | contracts/bridge/Bridge.sol:Bridge |
| lastUnpausedAt | uint64                                  | 201  | 2      | 8     | contracts/bridge/Bridge.sol:Bridge |
| \_\_gap        | uint256[49]                             | 202  | 0      | 1568  | contracts/bridge/Bridge.sol:Bridge |
| \_\_reserved1  | uint64                                  | 251  | 0      | 8     | contracts/bridge/Bridge.sol:Bridge |
| nextMessageId  | uint64                                  | 251  | 8      | 8     | contracts/bridge/Bridge.sol:Bridge |
| messageStatus  | mapping(bytes32 => enum IBridge.Status) | 252  | 0      | 32    | contracts/bridge/Bridge.sol:Bridge |
| \_\_ctx        | struct IBridge.Context                  | 253  | 0      | 64    | contracts/bridge/Bridge.sol:Bridge |
| \_\_reserved2  | uint256                                 | 255  | 0      | 32    | contracts/bridge/Bridge.sol:Bridge |
| \_\_reserved3  | uint256                                 | 256  | 0      | 32    | contracts/bridge/Bridge.sol:Bridge |
| \_\_gap        | uint256[44]                             | 257  | 0      | 1408  | contracts/bridge/Bridge.sol:Bridge |

## DelegateOwner

| Name           | Type        | Slot | Offset | Bytes | Contract                                     |
| -------------- | ----------- | ---- | ------ | ----- | -------------------------------------------- |
| \_initialized  | uint8       | 0    | 0      | 1     | contracts/L2/DelegateOwner.sol:DelegateOwner |
| \_initializing | bool        | 0    | 1      | 1     | contracts/L2/DelegateOwner.sol:DelegateOwner |
| \_\_gap        | uint256[50] | 1    | 0      | 1600  | contracts/L2/DelegateOwner.sol:DelegateOwner |
| \_owner        | address     | 51   | 0      | 20    | contracts/L2/DelegateOwner.sol:DelegateOwner |
| \_\_gap        | uint256[49] | 52   | 0      | 1568  | contracts/L2/DelegateOwner.sol:DelegateOwner |
| \_pendingOwner | address     | 101  | 0      | 20    | contracts/L2/DelegateOwner.sol:DelegateOwner |
| \_\_gap        | uint256[49] | 102  | 0      | 1568  | contracts/L2/DelegateOwner.sol:DelegateOwner |
| addressManager | address     | 151  | 0      | 20    | contracts/L2/DelegateOwner.sol:DelegateOwner |
| \_\_gap        | uint256[49] | 152  | 0      | 1568  | contracts/L2/DelegateOwner.sol:DelegateOwner |
| \_\_reentry    | uint8       | 201  | 0      | 1     | contracts/L2/DelegateOwner.sol:DelegateOwner |
| \_\_paused     | uint8       | 201  | 1      | 1     | contracts/L2/DelegateOwner.sol:DelegateOwner |
| lastUnpausedAt | uint64      | 201  | 2      | 8     | contracts/L2/DelegateOwner.sol:DelegateOwner |
| \_\_gap        | uint256[49] | 202  | 0      | 1568  | contracts/L2/DelegateOwner.sol:DelegateOwner |
| l1ChainId      | uint64      | 251  | 0      | 8     | contracts/L2/DelegateOwner.sol:DelegateOwner |
| nextTxId       | uint64      | 251  | 8      | 8     | contracts/L2/DelegateOwner.sol:DelegateOwner |
| realOwner      | address     | 252  | 0      | 20    | contracts/L2/DelegateOwner.sol:DelegateOwner |
| \_\_gap        | uint256[48] | 253  | 0      | 1536  | contracts/L2/DelegateOwner.sol:DelegateOwner |

## GuardianProver

| Name           | Type                                           | Slot | Offset | Bytes | Contract                                               |
| -------------- | ---------------------------------------------- | ---- | ------ | ----- | ------------------------------------------------------ |
| \_initialized  | uint8                                          | 0    | 0      | 1     | contracts/L1/provers/GuardianProver.sol:GuardianProver |
| \_initializing | bool                                           | 0    | 1      | 1     | contracts/L1/provers/GuardianProver.sol:GuardianProver |
| \_\_gap        | uint256[50]                                    | 1    | 0      | 1600  | contracts/L1/provers/GuardianProver.sol:GuardianProver |
| \_owner        | address                                        | 51   | 0      | 20    | contracts/L1/provers/GuardianProver.sol:GuardianProver |
| \_\_gap        | uint256[49]                                    | 52   | 0      | 1568  | contracts/L1/provers/GuardianProver.sol:GuardianProver |
| \_pendingOwner | address                                        | 101  | 0      | 20    | contracts/L1/provers/GuardianProver.sol:GuardianProver |
| \_\_gap        | uint256[49]                                    | 102  | 0      | 1568  | contracts/L1/provers/GuardianProver.sol:GuardianProver |
| addressManager | address                                        | 151  | 0      | 20    | contracts/L1/provers/GuardianProver.sol:GuardianProver |
| \_\_gap        | uint256[49]                                    | 152  | 0      | 1568  | contracts/L1/provers/GuardianProver.sol:GuardianProver |
| \_\_reentry    | uint8                                          | 201  | 0      | 1     | contracts/L1/provers/GuardianProver.sol:GuardianProver |
| \_\_paused     | uint8                                          | 201  | 1      | 1     | contracts/L1/provers/GuardianProver.sol:GuardianProver |
| lastUnpausedAt | uint64                                         | 201  | 2      | 8     | contracts/L1/provers/GuardianProver.sol:GuardianProver |
| \_\_gap        | uint256[49]                                    | 202  | 0      | 1568  | contracts/L1/provers/GuardianProver.sol:GuardianProver |
| guardianIds    | mapping(address => uint256)                    | 251  | 0      | 32    | contracts/L1/provers/GuardianProver.sol:GuardianProver |
| \_approvals    | mapping(uint32 => mapping(bytes32 => uint256)) | 252  | 0      | 32    | contracts/L1/provers/GuardianProver.sol:GuardianProver |
| guardians      | address[]                                      | 253  | 0      | 32    | contracts/L1/provers/GuardianProver.sol:GuardianProver |
| version        | uint32                                         | 254  | 0      | 4     | contracts/L1/provers/GuardianProver.sol:GuardianProver |
| minGuardians   | uint32                                         | 254  | 4      | 4     | contracts/L1/provers/GuardianProver.sol:GuardianProver |
| \_\_gap        | uint256[46]                                    | 255  | 0      | 1472  | contracts/L1/provers/GuardianProver.sol:GuardianProver |
| \_\_gap        | uint256[50]                                    | 301  | 0      | 1600  | contracts/L1/provers/GuardianProver.sol:GuardianProver |

## TaikoToken

| Name                                                  | Type                                                          | Slot | Offset | Bytes | Contract                                |
| ----------------------------------------------------- | ------------------------------------------------------------- | ---- | ------ | ----- | --------------------------------------- |
| \_initialized                                         | uint8                                                         | 0    | 0      | 1     | contracts/tko/TaikoToken.sol:TaikoToken |
| \_initializing                                        | bool                                                          | 0    | 1      | 1     | contracts/tko/TaikoToken.sol:TaikoToken |
| \_\_gap                                               | uint256[50]                                                   | 1    | 0      | 1600  | contracts/tko/TaikoToken.sol:TaikoToken |
| \_owner                                               | address                                                       | 51   | 0      | 20    | contracts/tko/TaikoToken.sol:TaikoToken |
| \_\_gap                                               | uint256[49]                                                   | 52   | 0      | 1568  | contracts/tko/TaikoToken.sol:TaikoToken |
| \_pendingOwner                                        | address                                                       | 101  | 0      | 20    | contracts/tko/TaikoToken.sol:TaikoToken |
| \_\_gap                                               | uint256[49]                                                   | 102  | 0      | 1568  | contracts/tko/TaikoToken.sol:TaikoToken |
| addressManager                                        | address                                                       | 151  | 0      | 20    | contracts/tko/TaikoToken.sol:TaikoToken |
| \_\_gap                                               | uint256[49]                                                   | 152  | 0      | 1568  | contracts/tko/TaikoToken.sol:TaikoToken |
| \_\_reentry                                           | uint8                                                         | 201  | 0      | 1     | contracts/tko/TaikoToken.sol:TaikoToken |
| \_\_paused                                            | uint8                                                         | 201  | 1      | 1     | contracts/tko/TaikoToken.sol:TaikoToken |
| lastUnpausedAt                                        | uint64                                                        | 201  | 2      | 8     | contracts/tko/TaikoToken.sol:TaikoToken |
| \_\_gap                                               | uint256[49]                                                   | 202  | 0      | 1568  | contracts/tko/TaikoToken.sol:TaikoToken |
| \_\_slots_previously_used_by_ERC20SnapshotUpgradeable | uint256[50]                                                   | 251  | 0      | 1600  | contracts/tko/TaikoToken.sol:TaikoToken |
| \_balances                                            | mapping(address => uint256)                                   | 301  | 0      | 32    | contracts/tko/TaikoToken.sol:TaikoToken |
| \_allowances                                          | mapping(address => mapping(address => uint256))               | 302  | 0      | 32    | contracts/tko/TaikoToken.sol:TaikoToken |
| \_totalSupply                                         | uint256                                                       | 303  | 0      | 32    | contracts/tko/TaikoToken.sol:TaikoToken |
| \_name                                                | string                                                        | 304  | 0      | 32    | contracts/tko/TaikoToken.sol:TaikoToken |
| \_symbol                                              | string                                                        | 305  | 0      | 32    | contracts/tko/TaikoToken.sol:TaikoToken |
| \_\_gap                                               | uint256[45]                                                   | 306  | 0      | 1440  | contracts/tko/TaikoToken.sol:TaikoToken |
| \_hashedName                                          | bytes32                                                       | 351  | 0      | 32    | contracts/tko/TaikoToken.sol:TaikoToken |
| \_hashedVersion                                       | bytes32                                                       | 352  | 0      | 32    | contracts/tko/TaikoToken.sol:TaikoToken |
| \_name                                                | string                                                        | 353  | 0      | 32    | contracts/tko/TaikoToken.sol:TaikoToken |
| \_version                                             | string                                                        | 354  | 0      | 32    | contracts/tko/TaikoToken.sol:TaikoToken |
| \_\_gap                                               | uint256[48]                                                   | 355  | 0      | 1536  | contracts/tko/TaikoToken.sol:TaikoToken |
| \_nonces                                              | mapping(address => struct CountersUpgradeable.Counter)        | 403  | 0      | 32    | contracts/tko/TaikoToken.sol:TaikoToken |
| \_PERMIT_TYPEHASH_DEPRECATED_SLOT                     | bytes32                                                       | 404  | 0      | 32    | contracts/tko/TaikoToken.sol:TaikoToken |
| \_\_gap                                               | uint256[49]                                                   | 405  | 0      | 1568  | contracts/tko/TaikoToken.sol:TaikoToken |
| \_delegates                                           | mapping(address => address)                                   | 454  | 0      | 32    | contracts/tko/TaikoToken.sol:TaikoToken |
| \_checkpoints                                         | mapping(address => struct ERC20VotesUpgradeable.Checkpoint[]) | 455  | 0      | 32    | contracts/tko/TaikoToken.sol:TaikoToken |
| \_totalSupplyCheckpoints                              | struct ERC20VotesUpgradeable.Checkpoint[]                     | 456  | 0      | 32    | contracts/tko/TaikoToken.sol:TaikoToken |
| \_\_gap                                               | uint256[47]                                                   | 457  | 0      | 1504  | contracts/tko/TaikoToken.sol:TaikoToken |
| \_\_gap                                               | uint256[50]                                                   | 504  | 0      | 1600  | contracts/tko/TaikoToken.sol:TaikoToken |

## BridgedTaikoToken

| Name                                                  | Type                                                          | Slot | Offset | Bytes | Contract                                              |
| ----------------------------------------------------- | ------------------------------------------------------------- | ---- | ------ | ----- | ----------------------------------------------------- |
| \_initialized                                         | uint8                                                         | 0    | 0      | 1     | contracts/tko/BridgedTaikoToken.sol:BridgedTaikoToken |
| \_initializing                                        | bool                                                          | 0    | 1      | 1     | contracts/tko/BridgedTaikoToken.sol:BridgedTaikoToken |
| \_\_gap                                               | uint256[50]                                                   | 1    | 0      | 1600  | contracts/tko/BridgedTaikoToken.sol:BridgedTaikoToken |
| \_owner                                               | address                                                       | 51   | 0      | 20    | contracts/tko/BridgedTaikoToken.sol:BridgedTaikoToken |
| \_\_gap                                               | uint256[49]                                                   | 52   | 0      | 1568  | contracts/tko/BridgedTaikoToken.sol:BridgedTaikoToken |
| \_pendingOwner                                        | address                                                       | 101  | 0      | 20    | contracts/tko/BridgedTaikoToken.sol:BridgedTaikoToken |
| \_\_gap                                               | uint256[49]                                                   | 102  | 0      | 1568  | contracts/tko/BridgedTaikoToken.sol:BridgedTaikoToken |
| addressManager                                        | address                                                       | 151  | 0      | 20    | contracts/tko/BridgedTaikoToken.sol:BridgedTaikoToken |
| \_\_gap                                               | uint256[49]                                                   | 152  | 0      | 1568  | contracts/tko/BridgedTaikoToken.sol:BridgedTaikoToken |
| \_\_reentry                                           | uint8                                                         | 201  | 0      | 1     | contracts/tko/BridgedTaikoToken.sol:BridgedTaikoToken |
| \_\_paused                                            | uint8                                                         | 201  | 1      | 1     | contracts/tko/BridgedTaikoToken.sol:BridgedTaikoToken |
| lastUnpausedAt                                        | uint64                                                        | 201  | 2      | 8     | contracts/tko/BridgedTaikoToken.sol:BridgedTaikoToken |
| \_\_gap                                               | uint256[49]                                                   | 202  | 0      | 1568  | contracts/tko/BridgedTaikoToken.sol:BridgedTaikoToken |
| \_\_slots_previously_used_by_ERC20SnapshotUpgradeable | uint256[50]                                                   | 251  | 0      | 1600  | contracts/tko/BridgedTaikoToken.sol:BridgedTaikoToken |
| \_balances                                            | mapping(address => uint256)                                   | 301  | 0      | 32    | contracts/tko/BridgedTaikoToken.sol:BridgedTaikoToken |
| \_allowances                                          | mapping(address => mapping(address => uint256))               | 302  | 0      | 32    | contracts/tko/BridgedTaikoToken.sol:BridgedTaikoToken |
| \_totalSupply                                         | uint256                                                       | 303  | 0      | 32    | contracts/tko/BridgedTaikoToken.sol:BridgedTaikoToken |
| \_name                                                | string                                                        | 304  | 0      | 32    | contracts/tko/BridgedTaikoToken.sol:BridgedTaikoToken |
| \_symbol                                              | string                                                        | 305  | 0      | 32    | contracts/tko/BridgedTaikoToken.sol:BridgedTaikoToken |
| \_\_gap                                               | uint256[45]                                                   | 306  | 0      | 1440  | contracts/tko/BridgedTaikoToken.sol:BridgedTaikoToken |
| \_hashedName                                          | bytes32                                                       | 351  | 0      | 32    | contracts/tko/BridgedTaikoToken.sol:BridgedTaikoToken |
| \_hashedVersion                                       | bytes32                                                       | 352  | 0      | 32    | contracts/tko/BridgedTaikoToken.sol:BridgedTaikoToken |
| \_name                                                | string                                                        | 353  | 0      | 32    | contracts/tko/BridgedTaikoToken.sol:BridgedTaikoToken |
| \_version                                             | string                                                        | 354  | 0      | 32    | contracts/tko/BridgedTaikoToken.sol:BridgedTaikoToken |
| \_\_gap                                               | uint256[48]                                                   | 355  | 0      | 1536  | contracts/tko/BridgedTaikoToken.sol:BridgedTaikoToken |
| \_nonces                                              | mapping(address => struct CountersUpgradeable.Counter)        | 403  | 0      | 32    | contracts/tko/BridgedTaikoToken.sol:BridgedTaikoToken |
| \_PERMIT_TYPEHASH_DEPRECATED_SLOT                     | bytes32                                                       | 404  | 0      | 32    | contracts/tko/BridgedTaikoToken.sol:BridgedTaikoToken |
| \_\_gap                                               | uint256[49]                                                   | 405  | 0      | 1568  | contracts/tko/BridgedTaikoToken.sol:BridgedTaikoToken |
| \_delegates                                           | mapping(address => address)                                   | 454  | 0      | 32    | contracts/tko/BridgedTaikoToken.sol:BridgedTaikoToken |
| \_checkpoints                                         | mapping(address => struct ERC20VotesUpgradeable.Checkpoint[]) | 455  | 0      | 32    | contracts/tko/BridgedTaikoToken.sol:BridgedTaikoToken |
| \_totalSupplyCheckpoints                              | struct ERC20VotesUpgradeable.Checkpoint[]                     | 456  | 0      | 32    | contracts/tko/BridgedTaikoToken.sol:BridgedTaikoToken |
| \_\_gap                                               | uint256[47]                                                   | 457  | 0      | 1504  | contracts/tko/BridgedTaikoToken.sol:BridgedTaikoToken |
| \_\_gap                                               | uint256[50]                                                   | 504  | 0      | 1600  | contracts/tko/BridgedTaikoToken.sol:BridgedTaikoToken |

## ERC20Vault

| Name               | Type                                                 | Slot | Offset | Bytes | Contract                                       |
| ------------------ | ---------------------------------------------------- | ---- | ------ | ----- | ---------------------------------------------- |
| \_initialized      | uint8                                                | 0    | 0      | 1     | contracts/tokenvault/ERC20Vault.sol:ERC20Vault |
| \_initializing     | bool                                                 | 0    | 1      | 1     | contracts/tokenvault/ERC20Vault.sol:ERC20Vault |
| \_\_gap            | uint256[50]                                          | 1    | 0      | 1600  | contracts/tokenvault/ERC20Vault.sol:ERC20Vault |
| \_owner            | address                                              | 51   | 0      | 20    | contracts/tokenvault/ERC20Vault.sol:ERC20Vault |
| \_\_gap            | uint256[49]                                          | 52   | 0      | 1568  | contracts/tokenvault/ERC20Vault.sol:ERC20Vault |
| \_pendingOwner     | address                                              | 101  | 0      | 20    | contracts/tokenvault/ERC20Vault.sol:ERC20Vault |
| \_\_gap            | uint256[49]                                          | 102  | 0      | 1568  | contracts/tokenvault/ERC20Vault.sol:ERC20Vault |
| addressManager     | address                                              | 151  | 0      | 20    | contracts/tokenvault/ERC20Vault.sol:ERC20Vault |
| \_\_gap            | uint256[49]                                          | 152  | 0      | 1568  | contracts/tokenvault/ERC20Vault.sol:ERC20Vault |
| \_\_reentry        | uint8                                                | 201  | 0      | 1     | contracts/tokenvault/ERC20Vault.sol:ERC20Vault |
| \_\_paused         | uint8                                                | 201  | 1      | 1     | contracts/tokenvault/ERC20Vault.sol:ERC20Vault |
| lastUnpausedAt     | uint64                                               | 201  | 2      | 8     | contracts/tokenvault/ERC20Vault.sol:ERC20Vault |
| \_\_gap            | uint256[49]                                          | 202  | 0      | 1568  | contracts/tokenvault/ERC20Vault.sol:ERC20Vault |
| \_\_gap            | uint256[50]                                          | 251  | 0      | 1600  | contracts/tokenvault/ERC20Vault.sol:ERC20Vault |
| bridgedToCanonical | mapping(address => struct ERC20Vault.CanonicalERC20) | 301  | 0      | 32    | contracts/tokenvault/ERC20Vault.sol:ERC20Vault |
| canonicalToBridged | mapping(uint256 => mapping(address => address))      | 302  | 0      | 32    | contracts/tokenvault/ERC20Vault.sol:ERC20Vault |
| btokenBlacklist    | mapping(address => bool)                             | 303  | 0      | 32    | contracts/tokenvault/ERC20Vault.sol:ERC20Vault |
| lastMigrationStart | mapping(uint256 => mapping(address => uint256))      | 304  | 0      | 32    | contracts/tokenvault/ERC20Vault.sol:ERC20Vault |
| \_\_gap            | uint256[46]                                          | 305  | 0      | 1472  | contracts/tokenvault/ERC20Vault.sol:ERC20Vault |

## ERC721Vault

| Name               | Type                                                 | Slot | Offset | Bytes | Contract                                         |
| ------------------ | ---------------------------------------------------- | ---- | ------ | ----- | ------------------------------------------------ |
| \_initialized      | uint8                                                | 0    | 0      | 1     | contracts/tokenvault/ERC721Vault.sol:ERC721Vault |
| \_initializing     | bool                                                 | 0    | 1      | 1     | contracts/tokenvault/ERC721Vault.sol:ERC721Vault |
| \_\_gap            | uint256[50]                                          | 1    | 0      | 1600  | contracts/tokenvault/ERC721Vault.sol:ERC721Vault |
| \_owner            | address                                              | 51   | 0      | 20    | contracts/tokenvault/ERC721Vault.sol:ERC721Vault |
| \_\_gap            | uint256[49]                                          | 52   | 0      | 1568  | contracts/tokenvault/ERC721Vault.sol:ERC721Vault |
| \_pendingOwner     | address                                              | 101  | 0      | 20    | contracts/tokenvault/ERC721Vault.sol:ERC721Vault |
| \_\_gap            | uint256[49]                                          | 102  | 0      | 1568  | contracts/tokenvault/ERC721Vault.sol:ERC721Vault |
| addressManager     | address                                              | 151  | 0      | 20    | contracts/tokenvault/ERC721Vault.sol:ERC721Vault |
| \_\_gap            | uint256[49]                                          | 152  | 0      | 1568  | contracts/tokenvault/ERC721Vault.sol:ERC721Vault |
| \_\_reentry        | uint8                                                | 201  | 0      | 1     | contracts/tokenvault/ERC721Vault.sol:ERC721Vault |
| \_\_paused         | uint8                                                | 201  | 1      | 1     | contracts/tokenvault/ERC721Vault.sol:ERC721Vault |
| lastUnpausedAt     | uint64                                               | 201  | 2      | 8     | contracts/tokenvault/ERC721Vault.sol:ERC721Vault |
| \_\_gap            | uint256[49]                                          | 202  | 0      | 1568  | contracts/tokenvault/ERC721Vault.sol:ERC721Vault |
| \_\_gap            | uint256[50]                                          | 251  | 0      | 1600  | contracts/tokenvault/ERC721Vault.sol:ERC721Vault |
| bridgedToCanonical | mapping(address => struct BaseNFTVault.CanonicalNFT) | 301  | 0      | 32    | contracts/tokenvault/ERC721Vault.sol:ERC721Vault |
| canonicalToBridged | mapping(uint256 => mapping(address => address))      | 302  | 0      | 32    | contracts/tokenvault/ERC721Vault.sol:ERC721Vault |
| \_\_gap            | uint256[48]                                          | 303  | 0      | 1536  | contracts/tokenvault/ERC721Vault.sol:ERC721Vault |
| \_\_gap            | uint256[50]                                          | 351  | 0      | 1600  | contracts/tokenvault/ERC721Vault.sol:ERC721Vault |

## ERC1155Vault

| Name               | Type                                                 | Slot | Offset | Bytes | Contract                                           |
| ------------------ | ---------------------------------------------------- | ---- | ------ | ----- | -------------------------------------------------- |
| \_initialized      | uint8                                                | 0    | 0      | 1     | contracts/tokenvault/ERC1155Vault.sol:ERC1155Vault |
| \_initializing     | bool                                                 | 0    | 1      | 1     | contracts/tokenvault/ERC1155Vault.sol:ERC1155Vault |
| \_\_gap            | uint256[50]                                          | 1    | 0      | 1600  | contracts/tokenvault/ERC1155Vault.sol:ERC1155Vault |
| \_owner            | address                                              | 51   | 0      | 20    | contracts/tokenvault/ERC1155Vault.sol:ERC1155Vault |
| \_\_gap            | uint256[49]                                          | 52   | 0      | 1568  | contracts/tokenvault/ERC1155Vault.sol:ERC1155Vault |
| \_pendingOwner     | address                                              | 101  | 0      | 20    | contracts/tokenvault/ERC1155Vault.sol:ERC1155Vault |
| \_\_gap            | uint256[49]                                          | 102  | 0      | 1568  | contracts/tokenvault/ERC1155Vault.sol:ERC1155Vault |
| addressManager     | address                                              | 151  | 0      | 20    | contracts/tokenvault/ERC1155Vault.sol:ERC1155Vault |
| \_\_gap            | uint256[49]                                          | 152  | 0      | 1568  | contracts/tokenvault/ERC1155Vault.sol:ERC1155Vault |
| \_\_reentry        | uint8                                                | 201  | 0      | 1     | contracts/tokenvault/ERC1155Vault.sol:ERC1155Vault |
| \_\_paused         | uint8                                                | 201  | 1      | 1     | contracts/tokenvault/ERC1155Vault.sol:ERC1155Vault |
| lastUnpausedAt     | uint64                                               | 201  | 2      | 8     | contracts/tokenvault/ERC1155Vault.sol:ERC1155Vault |
| \_\_gap            | uint256[49]                                          | 202  | 0      | 1568  | contracts/tokenvault/ERC1155Vault.sol:ERC1155Vault |
| \_\_gap            | uint256[50]                                          | 251  | 0      | 1600  | contracts/tokenvault/ERC1155Vault.sol:ERC1155Vault |
| bridgedToCanonical | mapping(address => struct BaseNFTVault.CanonicalNFT) | 301  | 0      | 32    | contracts/tokenvault/ERC1155Vault.sol:ERC1155Vault |
| canonicalToBridged | mapping(uint256 => mapping(address => address))      | 302  | 0      | 32    | contracts/tokenvault/ERC1155Vault.sol:ERC1155Vault |
| \_\_gap            | uint256[48]                                          | 303  | 0      | 1536  | contracts/tokenvault/ERC1155Vault.sol:ERC1155Vault |
| \_\_gap            | uint256[50]                                          | 351  | 0      | 1600  | contracts/tokenvault/ERC1155Vault.sol:ERC1155Vault |
| \_\_gap            | uint256[50]                                          | 401  | 0      | 1600  | contracts/tokenvault/ERC1155Vault.sol:ERC1155Vault |
| \_\_gap            | uint256[50]                                          | 451  | 0      | 1600  | contracts/tokenvault/ERC1155Vault.sol:ERC1155Vault |

## BridgedERC20

| Name             | Type                                            | Slot | Offset | Bytes | Contract                                           |
| ---------------- | ----------------------------------------------- | ---- | ------ | ----- | -------------------------------------------------- |
| \_initialized    | uint8                                           | 0    | 0      | 1     | contracts/tokenvault/BridgedERC20.sol:BridgedERC20 |
| \_initializing   | bool                                            | 0    | 1      | 1     | contracts/tokenvault/BridgedERC20.sol:BridgedERC20 |
| \_\_gap          | uint256[50]                                     | 1    | 0      | 1600  | contracts/tokenvault/BridgedERC20.sol:BridgedERC20 |
| \_owner          | address                                         | 51   | 0      | 20    | contracts/tokenvault/BridgedERC20.sol:BridgedERC20 |
| \_\_gap          | uint256[49]                                     | 52   | 0      | 1568  | contracts/tokenvault/BridgedERC20.sol:BridgedERC20 |
| \_pendingOwner   | address                                         | 101  | 0      | 20    | contracts/tokenvault/BridgedERC20.sol:BridgedERC20 |
| \_\_gap          | uint256[49]                                     | 102  | 0      | 1568  | contracts/tokenvault/BridgedERC20.sol:BridgedERC20 |
| addressManager   | address                                         | 151  | 0      | 20    | contracts/tokenvault/BridgedERC20.sol:BridgedERC20 |
| \_\_gap          | uint256[49]                                     | 152  | 0      | 1568  | contracts/tokenvault/BridgedERC20.sol:BridgedERC20 |
| \_\_reentry      | uint8                                           | 201  | 0      | 1     | contracts/tokenvault/BridgedERC20.sol:BridgedERC20 |
| \_\_paused       | uint8                                           | 201  | 1      | 1     | contracts/tokenvault/BridgedERC20.sol:BridgedERC20 |
| lastUnpausedAt   | uint64                                          | 201  | 2      | 8     | contracts/tokenvault/BridgedERC20.sol:BridgedERC20 |
| \_\_gap          | uint256[49]                                     | 202  | 0      | 1568  | contracts/tokenvault/BridgedERC20.sol:BridgedERC20 |
| \_balances       | mapping(address => uint256)                     | 251  | 0      | 32    | contracts/tokenvault/BridgedERC20.sol:BridgedERC20 |
| \_allowances     | mapping(address => mapping(address => uint256)) | 252  | 0      | 32    | contracts/tokenvault/BridgedERC20.sol:BridgedERC20 |
| \_totalSupply    | uint256                                         | 253  | 0      | 32    | contracts/tokenvault/BridgedERC20.sol:BridgedERC20 |
| \_name           | string                                          | 254  | 0      | 32    | contracts/tokenvault/BridgedERC20.sol:BridgedERC20 |
| \_symbol         | string                                          | 255  | 0      | 32    | contracts/tokenvault/BridgedERC20.sol:BridgedERC20 |
| \_\_gap          | uint256[45]                                     | 256  | 0      | 1440  | contracts/tokenvault/BridgedERC20.sol:BridgedERC20 |
| srcToken         | address                                         | 301  | 0      | 20    | contracts/tokenvault/BridgedERC20.sol:BridgedERC20 |
| \_\_srcDecimals  | uint8                                           | 301  | 20     | 1     | contracts/tokenvault/BridgedERC20.sol:BridgedERC20 |
| srcChainId       | uint256                                         | 302  | 0      | 32    | contracts/tokenvault/BridgedERC20.sol:BridgedERC20 |
| migratingAddress | address                                         | 303  | 0      | 20    | contracts/tokenvault/BridgedERC20.sol:BridgedERC20 |
| migratingInbound | bool                                            | 303  | 20     | 1     | contracts/tokenvault/BridgedERC20.sol:BridgedERC20 |
| \_\_gap          | uint256[47]                                     | 304  | 0      | 1504  | contracts/tokenvault/BridgedERC20.sol:BridgedERC20 |

## BridgedERC721

| Name                | Type                                         | Slot | Offset | Bytes | Contract                                             |
| ------------------- | -------------------------------------------- | ---- | ------ | ----- | ---------------------------------------------------- |
| \_initialized       | uint8                                        | 0    | 0      | 1     | contracts/tokenvault/BridgedERC721.sol:BridgedERC721 |
| \_initializing      | bool                                         | 0    | 1      | 1     | contracts/tokenvault/BridgedERC721.sol:BridgedERC721 |
| \_\_gap             | uint256[50]                                  | 1    | 0      | 1600  | contracts/tokenvault/BridgedERC721.sol:BridgedERC721 |
| \_owner             | address                                      | 51   | 0      | 20    | contracts/tokenvault/BridgedERC721.sol:BridgedERC721 |
| \_\_gap             | uint256[49]                                  | 52   | 0      | 1568  | contracts/tokenvault/BridgedERC721.sol:BridgedERC721 |
| \_pendingOwner      | address                                      | 101  | 0      | 20    | contracts/tokenvault/BridgedERC721.sol:BridgedERC721 |
| \_\_gap             | uint256[49]                                  | 102  | 0      | 1568  | contracts/tokenvault/BridgedERC721.sol:BridgedERC721 |
| addressManager      | address                                      | 151  | 0      | 20    | contracts/tokenvault/BridgedERC721.sol:BridgedERC721 |
| \_\_gap             | uint256[49]                                  | 152  | 0      | 1568  | contracts/tokenvault/BridgedERC721.sol:BridgedERC721 |
| \_\_reentry         | uint8                                        | 201  | 0      | 1     | contracts/tokenvault/BridgedERC721.sol:BridgedERC721 |
| \_\_paused          | uint8                                        | 201  | 1      | 1     | contracts/tokenvault/BridgedERC721.sol:BridgedERC721 |
| lastUnpausedAt      | uint64                                       | 201  | 2      | 8     | contracts/tokenvault/BridgedERC721.sol:BridgedERC721 |
| \_\_gap             | uint256[49]                                  | 202  | 0      | 1568  | contracts/tokenvault/BridgedERC721.sol:BridgedERC721 |
| \_name              | string                                       | 251  | 0      | 32    | contracts/tokenvault/BridgedERC721.sol:BridgedERC721 |
| \_symbol            | string                                       | 252  | 0      | 32    | contracts/tokenvault/BridgedERC721.sol:BridgedERC721 |
| \_owners            | mapping(uint256 => address)                  | 253  | 0      | 32    | contracts/tokenvault/BridgedERC721.sol:BridgedERC721 |
| \_balances          | mapping(address => uint256)                  | 254  | 0      | 32    | contracts/tokenvault/BridgedERC721.sol:BridgedERC721 |
| \_tokenApprovals    | mapping(uint256 => address)                  | 255  | 0      | 32    | contracts/tokenvault/BridgedERC721.sol:BridgedERC721 |
| \_operatorApprovals | mapping(address => mapping(address => bool)) | 256  | 0      | 32    | contracts/tokenvault/BridgedERC721.sol:BridgedERC721 |
| \_\_gap             | uint256[44]                                  | 257  | 0      | 1408  | contracts/tokenvault/BridgedERC721.sol:BridgedERC721 |
| srcToken            | address                                      | 301  | 0      | 20    | contracts/tokenvault/BridgedERC721.sol:BridgedERC721 |
| srcChainId          | uint256                                      | 302  | 0      | 32    | contracts/tokenvault/BridgedERC721.sol:BridgedERC721 |
| \_\_gap             | uint256[48]                                  | 303  | 0      | 1536  | contracts/tokenvault/BridgedERC721.sol:BridgedERC721 |

## BridgedERC1155

| Name                | Type                                            | Slot | Offset | Bytes | Contract                                               |
| ------------------- | ----------------------------------------------- | ---- | ------ | ----- | ------------------------------------------------------ |
| \_initialized       | uint8                                           | 0    | 0      | 1     | contracts/tokenvault/BridgedERC1155.sol:BridgedERC1155 |
| \_initializing      | bool                                            | 0    | 1      | 1     | contracts/tokenvault/BridgedERC1155.sol:BridgedERC1155 |
| \_\_gap             | uint256[50]                                     | 1    | 0      | 1600  | contracts/tokenvault/BridgedERC1155.sol:BridgedERC1155 |
| \_owner             | address                                         | 51   | 0      | 20    | contracts/tokenvault/BridgedERC1155.sol:BridgedERC1155 |
| \_\_gap             | uint256[49]                                     | 52   | 0      | 1568  | contracts/tokenvault/BridgedERC1155.sol:BridgedERC1155 |
| \_pendingOwner      | address                                         | 101  | 0      | 20    | contracts/tokenvault/BridgedERC1155.sol:BridgedERC1155 |
| \_\_gap             | uint256[49]                                     | 102  | 0      | 1568  | contracts/tokenvault/BridgedERC1155.sol:BridgedERC1155 |
| addressManager      | address                                         | 151  | 0      | 20    | contracts/tokenvault/BridgedERC1155.sol:BridgedERC1155 |
| \_\_gap             | uint256[49]                                     | 152  | 0      | 1568  | contracts/tokenvault/BridgedERC1155.sol:BridgedERC1155 |
| \_\_reentry         | uint8                                           | 201  | 0      | 1     | contracts/tokenvault/BridgedERC1155.sol:BridgedERC1155 |
| \_\_paused          | uint8                                           | 201  | 1      | 1     | contracts/tokenvault/BridgedERC1155.sol:BridgedERC1155 |
| lastUnpausedAt      | uint64                                          | 201  | 2      | 8     | contracts/tokenvault/BridgedERC1155.sol:BridgedERC1155 |
| \_\_gap             | uint256[49]                                     | 202  | 0      | 1568  | contracts/tokenvault/BridgedERC1155.sol:BridgedERC1155 |
| \_\_gap             | uint256[50]                                     | 251  | 0      | 1600  | contracts/tokenvault/BridgedERC1155.sol:BridgedERC1155 |
| \_balances          | mapping(uint256 => mapping(address => uint256)) | 301  | 0      | 32    | contracts/tokenvault/BridgedERC1155.sol:BridgedERC1155 |
| \_operatorApprovals | mapping(address => mapping(address => bool))    | 302  | 0      | 32    | contracts/tokenvault/BridgedERC1155.sol:BridgedERC1155 |
| \_uri               | string                                          | 303  | 0      | 32    | contracts/tokenvault/BridgedERC1155.sol:BridgedERC1155 |
| \_\_gap             | uint256[47]                                     | 304  | 0      | 1504  | contracts/tokenvault/BridgedERC1155.sol:BridgedERC1155 |
| srcToken            | address                                         | 351  | 0      | 20    | contracts/tokenvault/BridgedERC1155.sol:BridgedERC1155 |
| srcChainId          | uint256                                         | 352  | 0      | 32    | contracts/tokenvault/BridgedERC1155.sol:BridgedERC1155 |
| symbol              | string                                          | 353  | 0      | 32    | contracts/tokenvault/BridgedERC1155.sol:BridgedERC1155 |
| name                | string                                          | 354  | 0      | 32    | contracts/tokenvault/BridgedERC1155.sol:BridgedERC1155 |
| \_\_gap             | uint256[46]                                     | 355  | 0      | 1472  | contracts/tokenvault/BridgedERC1155.sol:BridgedERC1155 |

## AssignmentHook

| Name           | Type        | Slot | Offset | Bytes | Contract                                             |
| -------------- | ----------- | ---- | ------ | ----- | ---------------------------------------------------- |
| \_initialized  | uint8       | 0    | 0      | 1     | contracts/L1/hooks/AssignmentHook.sol:AssignmentHook |
| \_initializing | bool        | 0    | 1      | 1     | contracts/L1/hooks/AssignmentHook.sol:AssignmentHook |
| \_\_gap        | uint256[50] | 1    | 0      | 1600  | contracts/L1/hooks/AssignmentHook.sol:AssignmentHook |
| \_owner        | address     | 51   | 0      | 20    | contracts/L1/hooks/AssignmentHook.sol:AssignmentHook |
| \_\_gap        | uint256[49] | 52   | 0      | 1568  | contracts/L1/hooks/AssignmentHook.sol:AssignmentHook |
| \_pendingOwner | address     | 101  | 0      | 20    | contracts/L1/hooks/AssignmentHook.sol:AssignmentHook |
| \_\_gap        | uint256[49] | 102  | 0      | 1568  | contracts/L1/hooks/AssignmentHook.sol:AssignmentHook |
| addressManager | address     | 151  | 0      | 20    | contracts/L1/hooks/AssignmentHook.sol:AssignmentHook |
| \_\_gap        | uint256[49] | 152  | 0      | 1568  | contracts/L1/hooks/AssignmentHook.sol:AssignmentHook |
| \_\_reentry    | uint8       | 201  | 0      | 1     | contracts/L1/hooks/AssignmentHook.sol:AssignmentHook |
| \_\_paused     | uint8       | 201  | 1      | 1     | contracts/L1/hooks/AssignmentHook.sol:AssignmentHook |
| lastUnpausedAt | uint64      | 201  | 2      | 8     | contracts/L1/hooks/AssignmentHook.sol:AssignmentHook |
| \_\_gap        | uint256[49] | 202  | 0      | 1568  | contracts/L1/hooks/AssignmentHook.sol:AssignmentHook |
| \_\_gap        | uint256[50] | 251  | 0      | 1600  | contracts/L1/hooks/AssignmentHook.sol:AssignmentHook |

## DevnetTierProvider

| Name           | Type        | Slot | Offset | Bytes | Contract                                                     |
| -------------- | ----------- | ---- | ------ | ----- | ------------------------------------------------------------ |
| \_initialized  | uint8       | 0    | 0      | 1     | contracts/L1/tiers/DevnetTierProvider.sol:DevnetTierProvider |
| \_initializing | bool        | 0    | 1      | 1     | contracts/L1/tiers/DevnetTierProvider.sol:DevnetTierProvider |
| \_\_gap        | uint256[50] | 1    | 0      | 1600  | contracts/L1/tiers/DevnetTierProvider.sol:DevnetTierProvider |
| \_owner        | address     | 51   | 0      | 20    | contracts/L1/tiers/DevnetTierProvider.sol:DevnetTierProvider |
| \_\_gap        | uint256[49] | 52   | 0      | 1568  | contracts/L1/tiers/DevnetTierProvider.sol:DevnetTierProvider |
| \_pendingOwner | address     | 101  | 0      | 20    | contracts/L1/tiers/DevnetTierProvider.sol:DevnetTierProvider |
| \_\_gap        | uint256[49] | 102  | 0      | 1568  | contracts/L1/tiers/DevnetTierProvider.sol:DevnetTierProvider |
| addressManager | address     | 151  | 0      | 20    | contracts/L1/tiers/DevnetTierProvider.sol:DevnetTierProvider |
| \_\_gap        | uint256[49] | 152  | 0      | 1568  | contracts/L1/tiers/DevnetTierProvider.sol:DevnetTierProvider |
| \_\_reentry    | uint8       | 201  | 0      | 1     | contracts/L1/tiers/DevnetTierProvider.sol:DevnetTierProvider |
| \_\_paused     | uint8       | 201  | 1      | 1     | contracts/L1/tiers/DevnetTierProvider.sol:DevnetTierProvider |
| lastUnpausedAt | uint64      | 201  | 2      | 8     | contracts/L1/tiers/DevnetTierProvider.sol:DevnetTierProvider |
| \_\_gap        | uint256[49] | 202  | 0      | 1568  | contracts/L1/tiers/DevnetTierProvider.sol:DevnetTierProvider |
| \_\_gap        | uint256[50] | 251  | 0      | 1600  | contracts/L1/tiers/DevnetTierProvider.sol:DevnetTierProvider |

## TierProviderV1

| Name           | Type        | Slot | Offset | Bytes | Contract                                             |
| -------------- | ----------- | ---- | ------ | ----- | ---------------------------------------------------- |
| \_initialized  | uint8       | 0    | 0      | 1     | contracts/L1/tiers/TierProviderV1.sol:TierProviderV1 |
| \_initializing | bool        | 0    | 1      | 1     | contracts/L1/tiers/TierProviderV1.sol:TierProviderV1 |
| \_\_gap        | uint256[50] | 1    | 0      | 1600  | contracts/L1/tiers/TierProviderV1.sol:TierProviderV1 |
| \_owner        | address     | 51   | 0      | 20    | contracts/L1/tiers/TierProviderV1.sol:TierProviderV1 |
| \_\_gap        | uint256[49] | 52   | 0      | 1568  | contracts/L1/tiers/TierProviderV1.sol:TierProviderV1 |
| \_pendingOwner | address     | 101  | 0      | 20    | contracts/L1/tiers/TierProviderV1.sol:TierProviderV1 |
| \_\_gap        | uint256[49] | 102  | 0      | 1568  | contracts/L1/tiers/TierProviderV1.sol:TierProviderV1 |
| addressManager | address     | 151  | 0      | 20    | contracts/L1/tiers/TierProviderV1.sol:TierProviderV1 |
| \_\_gap        | uint256[49] | 152  | 0      | 1568  | contracts/L1/tiers/TierProviderV1.sol:TierProviderV1 |
| \_\_reentry    | uint8       | 201  | 0      | 1     | contracts/L1/tiers/TierProviderV1.sol:TierProviderV1 |
| \_\_paused     | uint8       | 201  | 1      | 1     | contracts/L1/tiers/TierProviderV1.sol:TierProviderV1 |
| lastUnpausedAt | uint64      | 201  | 2      | 8     | contracts/L1/tiers/TierProviderV1.sol:TierProviderV1 |
| \_\_gap        | uint256[49] | 202  | 0      | 1568  | contracts/L1/tiers/TierProviderV1.sol:TierProviderV1 |
| \_\_gap        | uint256[50] | 251  | 0      | 1600  | contracts/L1/tiers/TierProviderV1.sol:TierProviderV1 |

## TierProviderV2

| Name           | Type        | Slot | Offset | Bytes | Contract                                             |
| -------------- | ----------- | ---- | ------ | ----- | ---------------------------------------------------- |
| \_initialized  | uint8       | 0    | 0      | 1     | contracts/L1/tiers/TierProviderV2.sol:TierProviderV2 |
| \_initializing | bool        | 0    | 1      | 1     | contracts/L1/tiers/TierProviderV2.sol:TierProviderV2 |
| \_\_gap        | uint256[50] | 1    | 0      | 1600  | contracts/L1/tiers/TierProviderV2.sol:TierProviderV2 |
| \_owner        | address     | 51   | 0      | 20    | contracts/L1/tiers/TierProviderV2.sol:TierProviderV2 |
| \_\_gap        | uint256[49] | 52   | 0      | 1568  | contracts/L1/tiers/TierProviderV2.sol:TierProviderV2 |
| \_pendingOwner | address     | 101  | 0      | 20    | contracts/L1/tiers/TierProviderV2.sol:TierProviderV2 |
| \_\_gap        | uint256[49] | 102  | 0      | 1568  | contracts/L1/tiers/TierProviderV2.sol:TierProviderV2 |
| addressManager | address     | 151  | 0      | 20    | contracts/L1/tiers/TierProviderV2.sol:TierProviderV2 |
| \_\_gap        | uint256[49] | 152  | 0      | 1568  | contracts/L1/tiers/TierProviderV2.sol:TierProviderV2 |
| \_\_reentry    | uint8       | 201  | 0      | 1     | contracts/L1/tiers/TierProviderV2.sol:TierProviderV2 |
| \_\_paused     | uint8       | 201  | 1      | 1     | contracts/L1/tiers/TierProviderV2.sol:TierProviderV2 |
| lastUnpausedAt | uint64      | 201  | 2      | 8     | contracts/L1/tiers/TierProviderV2.sol:TierProviderV2 |
| \_\_gap        | uint256[49] | 202  | 0      | 1568  | contracts/L1/tiers/TierProviderV2.sol:TierProviderV2 |
| \_\_gap        | uint256[50] | 251  | 0      | 1600  | contracts/L1/tiers/TierProviderV2.sol:TierProviderV2 |

## TierProviderV3

| Name           | Type        | Slot | Offset | Bytes | Contract                                             |
| -------------- | ----------- | ---- | ------ | ----- | ---------------------------------------------------- |
| \_initialized  | uint8       | 0    | 0      | 1     | contracts/L1/tiers/TierProviderV3.sol:TierProviderV3 |
| \_initializing | bool        | 0    | 1      | 1     | contracts/L1/tiers/TierProviderV3.sol:TierProviderV3 |
| \_\_gap        | uint256[50] | 1    | 0      | 1600  | contracts/L1/tiers/TierProviderV3.sol:TierProviderV3 |
| \_owner        | address     | 51   | 0      | 20    | contracts/L1/tiers/TierProviderV3.sol:TierProviderV3 |
| \_\_gap        | uint256[49] | 52   | 0      | 1568  | contracts/L1/tiers/TierProviderV3.sol:TierProviderV3 |
| \_pendingOwner | address     | 101  | 0      | 20    | contracts/L1/tiers/TierProviderV3.sol:TierProviderV3 |
| \_\_gap        | uint256[49] | 102  | 0      | 1568  | contracts/L1/tiers/TierProviderV3.sol:TierProviderV3 |
| addressManager | address     | 151  | 0      | 20    | contracts/L1/tiers/TierProviderV3.sol:TierProviderV3 |
| \_\_gap        | uint256[49] | 152  | 0      | 1568  | contracts/L1/tiers/TierProviderV3.sol:TierProviderV3 |
| \_\_reentry    | uint8       | 201  | 0      | 1     | contracts/L1/tiers/TierProviderV3.sol:TierProviderV3 |
| \_\_paused     | uint8       | 201  | 1      | 1     | contracts/L1/tiers/TierProviderV3.sol:TierProviderV3 |
| lastUnpausedAt | uint64      | 201  | 2      | 8     | contracts/L1/tiers/TierProviderV3.sol:TierProviderV3 |
| \_\_gap        | uint256[49] | 202  | 0      | 1568  | contracts/L1/tiers/TierProviderV3.sol:TierProviderV3 |
| \_\_gap        | uint256[50] | 251  | 0      | 1600  | contracts/L1/tiers/TierProviderV3.sol:TierProviderV3 |

## ERC20Airdrop

| Name           | Type                     | Slot | Offset | Bytes | Contract                                             |
| -------------- | ------------------------ | ---- | ------ | ----- | ---------------------------------------------------- |
| \_initialized  | uint8                    | 0    | 0      | 1     | contracts/team/airdrop/ERC20Airdrop.sol:ERC20Airdrop |
| \_initializing | bool                     | 0    | 1      | 1     | contracts/team/airdrop/ERC20Airdrop.sol:ERC20Airdrop |
| \_\_gap        | uint256[50]              | 1    | 0      | 1600  | contracts/team/airdrop/ERC20Airdrop.sol:ERC20Airdrop |
| \_owner        | address                  | 51   | 0      | 20    | contracts/team/airdrop/ERC20Airdrop.sol:ERC20Airdrop |
| \_\_gap        | uint256[49]              | 52   | 0      | 1568  | contracts/team/airdrop/ERC20Airdrop.sol:ERC20Airdrop |
| \_pendingOwner | address                  | 101  | 0      | 20    | contracts/team/airdrop/ERC20Airdrop.sol:ERC20Airdrop |
| \_\_gap        | uint256[49]              | 102  | 0      | 1568  | contracts/team/airdrop/ERC20Airdrop.sol:ERC20Airdrop |
| addressManager | address                  | 151  | 0      | 20    | contracts/team/airdrop/ERC20Airdrop.sol:ERC20Airdrop |
| \_\_gap        | uint256[49]              | 152  | 0      | 1568  | contracts/team/airdrop/ERC20Airdrop.sol:ERC20Airdrop |
| \_\_reentry    | uint8                    | 201  | 0      | 1     | contracts/team/airdrop/ERC20Airdrop.sol:ERC20Airdrop |
| \_\_paused     | uint8                    | 201  | 1      | 1     | contracts/team/airdrop/ERC20Airdrop.sol:ERC20Airdrop |
| lastUnpausedAt | uint64                   | 201  | 2      | 8     | contracts/team/airdrop/ERC20Airdrop.sol:ERC20Airdrop |
| \_\_gap        | uint256[49]              | 202  | 0      | 1568  | contracts/team/airdrop/ERC20Airdrop.sol:ERC20Airdrop |
| isClaimed      | mapping(bytes32 => bool) | 251  | 0      | 32    | contracts/team/airdrop/ERC20Airdrop.sol:ERC20Airdrop |
| merkleRoot     | bytes32                  | 252  | 0      | 32    | contracts/team/airdrop/ERC20Airdrop.sol:ERC20Airdrop |
| claimStart     | uint64                   | 253  | 0      | 8     | contracts/team/airdrop/ERC20Airdrop.sol:ERC20Airdrop |
| claimEnd       | uint64                   | 253  | 8      | 8     | contracts/team/airdrop/ERC20Airdrop.sol:ERC20Airdrop |
| \_\_gap        | uint256[47]              | 254  | 0      | 1504  | contracts/team/airdrop/ERC20Airdrop.sol:ERC20Airdrop |
| token          | address                  | 301  | 0      | 20    | contracts/team/airdrop/ERC20Airdrop.sol:ERC20Airdrop |
| vault          | address                  | 302  | 0      | 20    | contracts/team/airdrop/ERC20Airdrop.sol:ERC20Airdrop |
| \_\_gap        | uint256[48]              | 303  | 0      | 1536  | contracts/team/airdrop/ERC20Airdrop.sol:ERC20Airdrop |

## AutomataDcapV3Attestation

| Name                      | Type                                            | Slot | Offset | Bytes | Contract                                                                               |
| ------------------------- | ----------------------------------------------- | ---- | ------ | ----- | -------------------------------------------------------------------------------------- |
| \_initialized             | uint8                                           | 0    | 0      | 1     | contracts/automata-attestation/AutomataDcapV3Attestation.sol:AutomataDcapV3Attestation |
| \_initializing            | bool                                            | 0    | 1      | 1     | contracts/automata-attestation/AutomataDcapV3Attestation.sol:AutomataDcapV3Attestation |
| \_\_gap                   | uint256[50]                                     | 1    | 0      | 1600  | contracts/automata-attestation/AutomataDcapV3Attestation.sol:AutomataDcapV3Attestation |
| \_owner                   | address                                         | 51   | 0      | 20    | contracts/automata-attestation/AutomataDcapV3Attestation.sol:AutomataDcapV3Attestation |
| \_\_gap                   | uint256[49]                                     | 52   | 0      | 1568  | contracts/automata-attestation/AutomataDcapV3Attestation.sol:AutomataDcapV3Attestation |
| \_pendingOwner            | address                                         | 101  | 0      | 20    | contracts/automata-attestation/AutomataDcapV3Attestation.sol:AutomataDcapV3Attestation |
| \_\_gap                   | uint256[49]                                     | 102  | 0      | 1568  | contracts/automata-attestation/AutomataDcapV3Attestation.sol:AutomataDcapV3Attestation |
| addressManager            | address                                         | 151  | 0      | 20    | contracts/automata-attestation/AutomataDcapV3Attestation.sol:AutomataDcapV3Attestation |
| \_\_gap                   | uint256[49]                                     | 152  | 0      | 1568  | contracts/automata-attestation/AutomataDcapV3Attestation.sol:AutomataDcapV3Attestation |
| \_\_reentry               | uint8                                           | 201  | 0      | 1     | contracts/automata-attestation/AutomataDcapV3Attestation.sol:AutomataDcapV3Attestation |
| \_\_paused                | uint8                                           | 201  | 1      | 1     | contracts/automata-attestation/AutomataDcapV3Attestation.sol:AutomataDcapV3Attestation |
| lastUnpausedAt            | uint64                                          | 201  | 2      | 8     | contracts/automata-attestation/AutomataDcapV3Attestation.sol:AutomataDcapV3Attestation |
| \_\_gap                   | uint256[49]                                     | 202  | 0      | 1568  | contracts/automata-attestation/AutomataDcapV3Attestation.sol:AutomataDcapV3Attestation |
| sigVerifyLib              | contract ISigVerifyLib                          | 251  | 0      | 20    | contracts/automata-attestation/AutomataDcapV3Attestation.sol:AutomataDcapV3Attestation |
| pemCertLib                | contract IPEMCertChainLib                       | 252  | 0      | 20    | contracts/automata-attestation/AutomataDcapV3Attestation.sol:AutomataDcapV3Attestation |
| \_checkLocalEnclaveReport | bool                                            | 252  | 20     | 1     | contracts/automata-attestation/AutomataDcapV3Attestation.sol:AutomataDcapV3Attestation |
| \_trustedUserMrEnclave    | mapping(bytes32 => bool)                        | 253  | 0      | 32    | contracts/automata-attestation/AutomataDcapV3Attestation.sol:AutomataDcapV3Attestation |
| \_trustedUserMrSigner     | mapping(bytes32 => bool)                        | 254  | 0      | 32    | contracts/automata-attestation/AutomataDcapV3Attestation.sol:AutomataDcapV3Attestation |
| \_serialNumIsRevoked      | mapping(uint256 => mapping(bytes => bool))      | 255  | 0      | 32    | contracts/automata-attestation/AutomataDcapV3Attestation.sol:AutomataDcapV3Attestation |
| tcbInfo                   | mapping(string => struct TCBInfoStruct.TCBInfo) | 256  | 0      | 32    | contracts/automata-attestation/AutomataDcapV3Attestation.sol:AutomataDcapV3Attestation |
| qeIdentity                | struct EnclaveIdStruct.EnclaveId                | 257  | 0      | 128   | contracts/automata-attestation/AutomataDcapV3Attestation.sol:AutomataDcapV3Attestation |
| \_\_gap                   | uint256[39]                                     | 261  | 0      | 1248  | contracts/automata-attestation/AutomataDcapV3Attestation.sol:AutomataDcapV3Attestation |

## SgxVerifier

| Name              | Type                                            | Slot | Offset | Bytes | Contract                                        |
| ----------------- | ----------------------------------------------- | ---- | ------ | ----- | ----------------------------------------------- |
| \_initialized     | uint8                                           | 0    | 0      | 1     | contracts/verifiers/SgxVerifier.sol:SgxVerifier |
| \_initializing    | bool                                            | 0    | 1      | 1     | contracts/verifiers/SgxVerifier.sol:SgxVerifier |
| \_\_gap           | uint256[50]                                     | 1    | 0      | 1600  | contracts/verifiers/SgxVerifier.sol:SgxVerifier |
| \_owner           | address                                         | 51   | 0      | 20    | contracts/verifiers/SgxVerifier.sol:SgxVerifier |
| \_\_gap           | uint256[49]                                     | 52   | 0      | 1568  | contracts/verifiers/SgxVerifier.sol:SgxVerifier |
| \_pendingOwner    | address                                         | 101  | 0      | 20    | contracts/verifiers/SgxVerifier.sol:SgxVerifier |
| \_\_gap           | uint256[49]                                     | 102  | 0      | 1568  | contracts/verifiers/SgxVerifier.sol:SgxVerifier |
| addressManager    | address                                         | 151  | 0      | 20    | contracts/verifiers/SgxVerifier.sol:SgxVerifier |
| \_\_gap           | uint256[49]                                     | 152  | 0      | 1568  | contracts/verifiers/SgxVerifier.sol:SgxVerifier |
| \_\_reentry       | uint8                                           | 201  | 0      | 1     | contracts/verifiers/SgxVerifier.sol:SgxVerifier |
| \_\_paused        | uint8                                           | 201  | 1      | 1     | contracts/verifiers/SgxVerifier.sol:SgxVerifier |
| lastUnpausedAt    | uint64                                          | 201  | 2      | 8     | contracts/verifiers/SgxVerifier.sol:SgxVerifier |
| \_\_gap           | uint256[49]                                     | 202  | 0      | 1568  | contracts/verifiers/SgxVerifier.sol:SgxVerifier |
| nextInstanceId    | uint256                                         | 251  | 0      | 32    | contracts/verifiers/SgxVerifier.sol:SgxVerifier |
| instances         | mapping(uint256 => struct SgxVerifier.Instance) | 252  | 0      | 32    | contracts/verifiers/SgxVerifier.sol:SgxVerifier |
| addressRegistered | mapping(address => bool)                        | 253  | 0      | 32    | contracts/verifiers/SgxVerifier.sol:SgxVerifier |
| \_\_gap           | uint256[47]                                     | 254  | 0      | 1504  | contracts/verifiers/SgxVerifier.sol:SgxVerifier |

## RiscZeroVerifier

| Name            | Type                              | Slot | Offset | Bytes | Contract                                                  |
| --------------- | --------------------------------- | ---- | ------ | ----- | --------------------------------------------------------- |
| \_initialized   | uint8                             | 0    | 0      | 1     | contracts/verifiers/RiscZeroVerifier.sol:RiscZeroVerifier |
| \_initializing  | bool                              | 0    | 1      | 1     | contracts/verifiers/RiscZeroVerifier.sol:RiscZeroVerifier |
| \_\_gap         | uint256[50]                       | 1    | 0      | 1600  | contracts/verifiers/RiscZeroVerifier.sol:RiscZeroVerifier |
| \_owner         | address                           | 51   | 0      | 20    | contracts/verifiers/RiscZeroVerifier.sol:RiscZeroVerifier |
| \_\_gap         | uint256[49]                       | 52   | 0      | 1568  | contracts/verifiers/RiscZeroVerifier.sol:RiscZeroVerifier |
| \_pendingOwner  | address                           | 101  | 0      | 20    | contracts/verifiers/RiscZeroVerifier.sol:RiscZeroVerifier |
| \_\_gap         | uint256[49]                       | 102  | 0      | 1568  | contracts/verifiers/RiscZeroVerifier.sol:RiscZeroVerifier |
| addressManager  | address                           | 151  | 0      | 20    | contracts/verifiers/RiscZeroVerifier.sol:RiscZeroVerifier |
| \_\_gap         | uint256[49]                       | 152  | 0      | 1568  | contracts/verifiers/RiscZeroVerifier.sol:RiscZeroVerifier |
| \_\_reentry     | uint8                             | 201  | 0      | 1     | contracts/verifiers/RiscZeroVerifier.sol:RiscZeroVerifier |
| \_\_paused      | uint8                             | 201  | 1      | 1     | contracts/verifiers/RiscZeroVerifier.sol:RiscZeroVerifier |
| lastUnpausedAt  | uint64                            | 201  | 2      | 8     | contracts/verifiers/RiscZeroVerifier.sol:RiscZeroVerifier |
| \_\_gap         | uint256[49]                       | 202  | 0      | 1568  | contracts/verifiers/RiscZeroVerifier.sol:RiscZeroVerifier |
| receiptVerifier | contract IRiscZeroReceiptVerifier | 251  | 0      | 20    | contracts/verifiers/RiscZeroVerifier.sol:RiscZeroVerifier |
| isImageTrusted  | mapping(bytes32 => bool)          | 252  | 0      | 32    | contracts/verifiers/RiscZeroVerifier.sol:RiscZeroVerifier |
| \_\_gap         | uint256[48]                       | 253  | 0      | 1536  | contracts/verifiers/RiscZeroVerifier.sol:RiscZeroVerifier |

## QuotaManager

| Name           | Type                                          | Slot | Offset | Bytes | Contract                                       |
| -------------- | --------------------------------------------- | ---- | ------ | ----- | ---------------------------------------------- |
| \_initialized  | uint8                                         | 0    | 0      | 1     | contracts/bridge/QuotaManager.sol:QuotaManager |
| \_initializing | bool                                          | 0    | 1      | 1     | contracts/bridge/QuotaManager.sol:QuotaManager |
| \_\_gap        | uint256[50]                                   | 1    | 0      | 1600  | contracts/bridge/QuotaManager.sol:QuotaManager |
| \_owner        | address                                       | 51   | 0      | 20    | contracts/bridge/QuotaManager.sol:QuotaManager |
| \_\_gap        | uint256[49]                                   | 52   | 0      | 1568  | contracts/bridge/QuotaManager.sol:QuotaManager |
| \_pendingOwner | address                                       | 101  | 0      | 20    | contracts/bridge/QuotaManager.sol:QuotaManager |
| \_\_gap        | uint256[49]                                   | 102  | 0      | 1568  | contracts/bridge/QuotaManager.sol:QuotaManager |
| addressManager | address                                       | 151  | 0      | 20    | contracts/bridge/QuotaManager.sol:QuotaManager |
| \_\_gap        | uint256[49]                                   | 152  | 0      | 1568  | contracts/bridge/QuotaManager.sol:QuotaManager |
| \_\_reentry    | uint8                                         | 201  | 0      | 1     | contracts/bridge/QuotaManager.sol:QuotaManager |
| \_\_paused     | uint8                                         | 201  | 1      | 1     | contracts/bridge/QuotaManager.sol:QuotaManager |
| lastUnpausedAt | uint64                                        | 201  | 2      | 8     | contracts/bridge/QuotaManager.sol:QuotaManager |
| \_\_gap        | uint256[49]                                   | 202  | 0      | 1568  | contracts/bridge/QuotaManager.sol:QuotaManager |
| tokenQuota     | mapping(address => struct QuotaManager.Quota) | 251  | 0      | 32    | contracts/bridge/QuotaManager.sol:QuotaManager |
| \_\_gap        | uint256[49]                                   | 252  | 0      | 1568  | contracts/bridge/QuotaManager.sol:QuotaManager |