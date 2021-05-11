# Envoy Proxy

```bash
docker run --rm -it \
    -p 9901:9901 -p 10000:10000 \
    -v $PWD/envoy-demo.yaml:/envoy-demo.yaml \
    envoyproxy/envoy:v1.18.2 -c /envoy-demo.yaml
```
