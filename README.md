# StarkEx

##  What is included in this repository

This repository is a single entry point to view StarkEx code starting from version 4.5 .

The submodules here are version-aligned, so you don't need to worry about synchronizing the versions
of the different submodules.

The submodules reference to the following repositories:

1. *starkex-contracts* - **StarkEx**

    This repository contains the Ethereum smart contracts code implementing the StarkEx

    on-chain contracts for both spot trading as well as perpetual trading.

2. *starkware-crypto-utils* - **StarkWare Crypto Utils**

    This repository contains STARK friendly functionalities of signatures, keys and Pedersen hash.

3. *starkex-for-spot-trading* - **StarkEx Cairo Code Repository**

    This repository contains the Cairo code (and some of the cryptographic primitives) used by StarkEx.

4. *starkex-js* - **JavaScript SDK for StarkEx**

    This repository contains  a JavaScript wrapper around the StarkEx API that can be used in
both NodeJS and Browser environments.

5. *starkex-data-availability-committee* - **StarkEx Committee**

This repository contains proposed code for running the committee service, used for data availability in StarkeEx.

## How to clone this repository
If you wish to download all submodules locally upon cloning this repository, use:

```
git clone --recurse-submodules https://github.com/starkware-libs/starkex-core
```
If you wish to download specific submodules, use:
```
git clone https://github.com/starkware-libs/starkex-core
```

Then use the following command with the list of the desired repositories:
```
git submodule update --init --recursive [SUBMODULE1 SUBMODULE2 ...]
```
