## certikcli query shield pool-purchaser

get purchases corresponding to a given pool-purchaser pair

### Synopsis

get purchases corresponding to a given pool-purchaser pair

```
certikcli query shield pool-purchaser [pool_ID] [purchaser_address] [flags]
```

### Options

```
      --height int    Use a specific height to query state at (this can error if the node is pruning state)
  -h, --help          help for pool-purchaser
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

* [certikcli query shield](certikcli_query_shield.md)	 - Querying commands for the shield module


