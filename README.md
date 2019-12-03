# k8s-ethereum

> Ethereum + Kubernetes = Heaven.

`k8s-ethereum` is a collection of [Helm](https://helm.sh) charts related to Ethereum services.

## Adding this hub to Helm

Just issue the following command on your terminal in order to add this repository to your Helm repository lists (keep in mind that this repository uses the new V2 version format):

```console
helm repo add k8s-ethereum https://raw.githubusercontent.com/41North/k8s-ethereum/master/charts/
```

## Current supported services

- [Aleth Lite Explorer](https://lite-explorer.aleth.io/): Alethio's Light Weight Open Source Ethereum Explorer.
- [Besu](https://besu.hyperledger.org): An enterprise-grade Java-based, Apache 2.0 licensed Ethereum client.
- [EthStats](https://github.com/Alethio/ethstats-network-server): Ethereum network stats server.

## Work in progress...

We need more useful Helm charts! Feel free to create a PR in order to contribute with a new one not listed before.

## Acknowledgements

- [Alen Komljen](https://github.com/komljen): To whom I copied shamelessly [his Makefile](https://github.com/komljen/helm-charts) to generate a Helm chart repository directly on the repository.

## License

This project is licensed under the Apache 2.0 license. See [LICENSE](LICENSE) for more details.