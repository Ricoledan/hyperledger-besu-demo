# hyperledger-besu-demo

## Description

Hyperledger Besu is an open source Ethereum client

## Prerequisites

## Commands

### Application

Run docker compose 

```bash
docker-compose up -d
```

Run docker compose with build for dev testing changes

```bash
docker-compose up --build -d

```

###

Returns the chain ID of the network

```bash
curl -X POST --data '{"jsonrpc":"2.0","method":"eth_chainId","params":[],"id":1}' localhost:8545
```

Returns the starting, current, and highest block

```bash
curl -X POST --data '{"jsonrpc":"2.0","method":"eth_syncing","params":[],"id":1}' localhost:8545
```

### 

```bash
besu operator generate-blockchain-config --config-file=qbftConfigFile.json --to=networkFiles --private-key-file-name=key
```

## Architecture

![Hyperledger Besu Arch Diagram](assets/private-architecture.jpeg?raw=true "Architecture")


## Features
- [ ] Configure Network Params
- [ ] Enforce Free Gas Price
