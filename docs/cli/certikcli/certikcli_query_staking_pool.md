## certikcli query staking pool

Query the current staking pool values

### Synopsis

Query values for amounts stored in the staking pool.

Example:
$ certikcli query staking pool

```
certikcli query staking pool [flags]
```

### Options

```
      --height int    Use a specific height to query state at (this can error if the node is pruning state)
  -h, --help          help for pool
      --indent        Add indent to JSON response
      --ledger        Use a connected Ledger device
      --node string   <host>:<port> to Tendermint RPC interface for this chain (default "tcp://localhost:26657")
      --trust-node    Trust connected full node (don't verify proofs for responses)
```

### Options inherited from parent commands

```
      --chain-id string   Chain ID of tendermint node
  -e, --encoding string   Binary encoding (hex|b64|btc) (default "hex")
      --home string       directory for config and data (default "~/.certikcli")
  -o, --output string     Output format (text|json) (default "text")
      --trace             print out full stack trace on errors
```

### SEE ALSO

* [certikcli query staking](certikcli_query_staking.md)	 - Querying commands for the staking module


