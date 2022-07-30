# Tesnet

### Explorer

{% embed url="https://testnet-explorer.publicawesome.dev/stargaze" %}

### Faucet

Join our discord and request tokens in our #faucet channel, you will need the developer role from #pick-a-role



### Endpoints

RPC: https://rpc.elgafar-1.stargaze-apis.com

LCD: https://rest.elgafar-1.stargaze-apis.com



### Deploying a contract&#x20;

```
starsd tx wasm store conctract.wasm --from [key-name] \
    --gas-prices 0.025ustars --gas-adjustment 1.7 \
    --gas auto --chain-id elgafar-1 --node https://rpc.elgafar-1.stargaze-apis.com:443
    

```


