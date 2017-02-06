
# Scope

This is not a full audit of ChronoBank platform. Only the parts consider the crowdsale token (TIME) were audited.

Covered

* ChronoBankAsset.sol
* ChronoBankPlatform.sol
* ChronoBankAssetProxy.sol
* ChronoBankAssetInterface.sol
* TIME.sol
* Owned.sol

Not covered

* ChronoBankAssetProxyInterface.sol
* ChronoBankAssetWithFee.sol
* ChronoBankAssetWithFeeProxy.sol
* ChronoBankPlatformEmitter.sol
* ChronoMint.sol
* ChronoMintConfigurable.sol
* Configurable.sol
* ConvertLib.sol
* ERC20Interface.sol
* EventsHistory.sol
* Exchange.sol
* LHT.sol
* LibCLLi.sol
* LOC.sol
* Managed.sol
* Migrations.sol
* Owners.sol
* Rewards.sol
* Rooted.sol
* StringLib.sol
* helpers
* helpers/ChronoBankPlatformTestable.sol
* helpers/FakeCoin.sol
* helpers/FakeCoin2.sol
* helpers/FakeCoin3.sol
* helpers/Stub.sol

## Applied design patterns

No throws used. Instead of an error event is emitted and boolean false returned. [This is due to a limitation for a current EVM](https://github.com/ethereum/EIPs/issues/62).

## Walkthrough

* ChronoBankAsset.init
* etc...





