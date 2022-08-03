# juno-beaker-test


Run juno locally for testing

```sh
docker run -it \
  --name juno_node_1 \
  -p 1317:1317 \
  -p 26656:26656 \
  -p 26657:26657 \
  -p 9090:9090 \
  -e STAKE_TOKEN=ujunox \
  -e UNSAFE_CORS=true \
  ghcr.io/cosmoscontracts/juno:v9.0.0 \
  ./setup_and_run.sh juno16g2rahf5846rxzp3fwlswy08fz8ccuwk03k57y
```