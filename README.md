# async-java-sidecar.rs

k8s sidecar for async-java.

Inherits [`ores-otel-sidecar`](https://github.com/ores-otel/ores-otel-sidecar.rs).
Bind with `ASYNC_JAVA_SIDECAR_BIND` (default `127.0.0.1:9090`).

```sh
cargo run --bin async-java-sidecar
```
