# Changelog

## :page\_facing\_up: List of changes

* New [EthPillar](../ethpillar.md) - a friendly TUI for node management! Command line use is greatly reduced. Update your software with a keystroke. Automatically install a minority client (Nethermind + Nimbus) node in minutes!
*

    <figure><img src="../../../.gitbook/assets/ethpillar.png" alt=""><figcaption><p>ethpillar</p></figcaption></figure>
* Add Nimbus and Teku standalone beacon node/validator configurations
  * Useful for [rescuenode](https://rescuenode.com/docs/) failover setups or pointing a single validator client at multiple EL/CL nodes for extra redundancy and minimizing supermajority risks
* Added [Switching / Migration Execution Client guide](part-iii-tips/switching-execution-client.md) for both V2 and V1 staking setups
* Added [Reth Execution Client](../testnet-holesky-validator/step-3-installing-execution-client/reth.md) - Alpha software, yet functional
* Created guide on how to [connect your wallet software to your own Node's RPC](part-iii-tips/using-staking-node-as-rpc-url-endpoint.md)
* Added [Holesky testnet staking guide](../testnet-holesky-validator/)
* Re-worked adding [new validator keys to existing setup](part-iii-tips/adding-a-new-validator-to-an-existing-setup.md).
* Added new Geth [how-to for enabling path based state storage](https://www.coincashew.com/coins/overview-eth/guide-or-how-to-setup-a-validator-on-eth2-mainnet/part-iii-tips/geth-enabling-path-based-storage). Automated pruning!
* Staking setups prior to July 2023: V1 guides (using eth1 and beacon-chain, as systemd service names) can be accessed in the [archive section.](https://www.coincashew.com/coins/overview-eth/archived-guides/guide-or-how-to-setup-a-validator-on-eth2-mainnet)
* Major Version 2 Guides released!&#x20;
  * Notable changes include:
    * Dedicated service account users for execution / consensus / validator
    * Binaries deployed to /usr/local/bin
    * Data directory files stored in /var/lib
    * Options to download pre-built binaries or build from source
    * Simplified steps for full node non-staking users
    * Streamlined pre-requisites and node configuration steps
* Created guide for [How to re-sync using checkpoint sync](part-iii-tips/how-to-re-sync-using-checkpoint-sync.md)
* Created guide to [Updating 0x00 -> 0x01 Withdrawal keys with Ethdo for Shapella Upgrade](../update-withdrawal-keys-for-ethereum-validator-bls-to-execution-change-or-0x00-to-0x01-with-ethdo.md)
* Added [disk usage numbers by EL CL combination](../archived-guides/guide-or-how-to-setup-a-validator-on-eth2-mainnet/part-iii-tips/disk-usage-by-execution-consensus-client.md)
* Include ETH Withdrawals address as default during validator key generation.
* Added [MEV-boost guide.](../mev-boost/)
* Updated to be mainnet merge ready.
* Are you ready for the Merge? [**Ethereum Merge Upgrade Checklist for Home Stakers and Validators**](https://www.coincashew.com/coins/overview-eth/ethereum-merge-upgrade-checklist-for-home-stakers-and-validators)
* Updated to use staking-deposit-cli
* \#TestingTheMerge on Ropsten: New Automated Install Script for the [Most Diverse Client: Besu+Lodestar](https://github.com/coincashew/ethereum-scripts/blob/main/README.md)
* Guides for Ropsten and [Kiln "Merge Testnets"](https://www.coincashew.com/coins/overview-eth/guide-or-besu-+-lodestar-or-most-viable-diverse-client-or-staking-ethereum-on-kiln-testnet)
* \#TestingTheMerge Guide on [Pithos Testnet](https://www.coincashew.com/coins/overview-eth/guide-or-how-to-setup-a-validator-for-ethereum-staking-on-pithos-testnet-in-10-minutes-or-less)
* Migration Guide with the goal of increasing ClientDiversity: [**Operation Client Diversity: Migrate Prysm to Teku**](https://www.coincashew.com/coins/overview-eth/guide-or-operation-client-diversity-migrate-prysm-to-teku)
* Updated besu execution client to use BONSAI format
* Restructured guide for improved speed and readability
* Added how to check your [Validator's Sync Committee duties](part-ii-maintenance/checking-my-eth-validators-sync-committee-duties.md)
* Added new Formatting fixes and updated Teku initial state API.
* Updated with consensus layer (CL), the execution layer (EL), formerly known as eth2 and eth1.
* Added erigon build dependencies.
* Added Teku and Lodestar Checkpoint Sync feature, the quickest way to sync a Ethereum beacon chain client.
* geth + erigon pruning / Altair hard fork changes / nimbus eth1 fallback
* lighthouse + prysm doppelganger protection enabled. Doppelganger protection intentionally misses an epoch on startup and listens for attestations to make sure your keys are not still running on the old validator client.
* OpenEthereum will no longer be supported post London hard fork. Gnosis, maintainers of OpenEthereum, suggest users migrate to their new Erigon Ethererum client. Added setup instructions for **Erigon** under eth1 node section.
* Added [Mobile App Node Monitoring by beaconcha.in](part-i-installation/mobile-app-node-monitoring-by-beaconchain.md)
* Updated staking-deposit-cli and added section on eth1 withdrawal address
* Added generating mnemonic seeds on **Tails OS** by [punggolzenith](https://github.com/punggolzenith)
* Iancoleman.io BLS12-381 Key Generation Tool [how-to added](part-iii-tips/eip2333-key-generator-by-iancoleman-io.md)
* Testnet guide forked for [Prater testnet](../guide-or-how-to-setup-a-validator-on-eth2-testnet-prater/) staking
* [Geth pruning guide](part-ii-maintenance/pruning-the-execution-client-to-free-up-disk-space.md) created
* Major changes to Lodestar guide
* Additional [Grafana Dashboards](part-i-installation/monitoring-your-validator-with-grafana-and-prometheus.md) for Prysm, Lighthouse and Nimbus
* [Validator Security Best Practices added](broken-reference)
* Translations now available for Japanese, Chinese and Spanish (access by changing site language)
* Generate keystore files on [Ledger Nano X, Nano S and Trezor Model T](broken-reference) with tool from [allnodes.com](https://twitter.com/Allnodes/status/1390020240541618177?s=20)
* [Batch deposit tool](broken-reference) by [abyss.finance](https://twitter.com/AbyssFinance/status/1379732382044069888) now added
