# DEVELOPMENT

Firstly, clone and link the trident repository as follows

```sh
git clone https://github.com/sushiswap/trident.git && cd trident && yarn link
```

Secondly, link trident repository to this repository.

```sh
git clone https://github.com/sushiswap/sushiswap-sdk.git && cd sushiswap-sdk && git checkout trident && yarn link
```
