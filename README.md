# be0x74a krew index

Custom [krew](https://krew.sigs.k8s.io/) index for kubectl plugins by be0x74a.

## Setup

Add this index once:

```bash
kubectl krew index add be0x74a https://github.com/be0x74a/krew-index
```

## Available plugins

| Plugin | Description |
|--------|-------------|
| [xctx](plugins/xctx.yaml) | Execute kubectl commands across multiple contexts matching a regex |

## Install a plugin

```bash
kubectl krew install be0x74a/xctx
```

## Update plugins

```bash
kubectl krew update
kubectl krew upgrade
```
