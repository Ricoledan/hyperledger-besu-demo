# hyperledger-besu-demo

## Description

Hyperledger Besu is an open source Ethereum client

## Prerequisites

## Commands

### Set Up

Run docker compose 

```bash
docker-compose up -d
```

### Besu

Returns the chain ID of the network

```bash
curl -X POST --data '{"jsonrpc":"2.0","method":"eth_chainId","params":[],"id":1}' localhost:8545
```

Returns the starting, current, and highest block

```bash
curl -X POST --data '{"jsonrpc":"2.0","method":"eth_syncing","params":[],"id":1}' localhost:8545
```

### 



## Architecture

![Hyperledger Besu Arch Diagram](assets/private-architecture.jpeg?raw=true "Architecture")


## Features
- [ ] Configure Network Params
- [ ] Enforce Free Gas Price
