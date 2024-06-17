# SubQuery Common API - Polkadot Transactions

ubQuery API data sources are grouped based on the following features:

📚 Operation History - Transfers and Extrinsics for Utility (main) token of the network
✨ Multi-asset transfers - Support for transfer history for tokens from ORML and Assets pallets
🥞 Staking rewards - Rewards history and accumulated total rewards, supports both Staking and ParachainStaking pallets
📈 Staking analytics - Queries for current stake, validators statistics, and stake change history

# Get Started

### For local run you can use special script in each network directory

```shell
sh local-runner.sh ${project_file}.yaml
```

### In order to deploy new project

```shell
./node_modules/.bin/subql publish -f ${project_file}.yaml
```

## License

SubQuery Nova is available under the Apache 2.0 license. See the LICENSE file for more info.
© Novasama Technologies GmbH 2023
