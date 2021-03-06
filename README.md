<h1 align=center><code>Pool Management</code></h1>

Pool management interface for users to add and remove liquidity to Balancer pools.


## Development

-   Copy .env.example -> .env
-   Configure backup node urls

```
# Backup node url
REACT_APP_RPC_URL_1="https://mainnet.infura.io/v3/{apiKey}"
REACT_APP_RPC_URL_42="https://kovan.infura.io/v3/{apiKey}"
REACT_APP_RPC_URL_LOCAL="http://localhost:8545"
```

-   Configure supported network

```
# Supported Network ID (e.g. mainnet = 1, rinkeby = 4, kovan = 42)
REACT_APP_SUPPORTED_NETWORK_ID="42"
```

-   Build & run locally

```
yarn build
yarn start
```