# pub
Public things to anywhere.

## Base download url:

CN: https://gitee.com/u2go/pub/raw/main/

US: https://raw.githubusercontent.com/u2go/pub/main/

## Bins

### croc

use p2p transfer file.

https://gitee.com/u2go/pub/raw/main/bin/linux-64/croc

https://raw.githubusercontent.com/u2go/pub/main/bin/linux-64/croc

### proxy

p2p http proxy

usage: https://github.com/libp2p/go-libp2p/tree/master/examples/http-proxy

on target
```text
$ proxy
Proxy server is ready
libp2p-peer addresses:
/ip4/127.0.0.1/tcp/12000/ipfs/QmbMHndMSzV9jBJzgDZcsPQzZZy7qigHbdh3zfJFf1pNRR
```

on local
```text
$ proxy -d /ip4/127.0.0.1/tcp/12000/ipfs/QmbMHndMSzV9jBJzgDZcsPQzZZy7qigHbdh3zfJFf1pNRR
Proxy server is ready
libp2p-peer addresses:
/ip4/127.0.0.1/tcp/12001/ipfs/QmRU7ea1w9P9GfCpDrLdvSQzZeULJapDcF3iK7aFjxYabA
proxy listening on  127.0.0.1:9900
```

https://gitee.com/u2go/pub/raw/main/bin/linux-64/proxy

https://raw.githubusercontent.com/u2go/pub/main/bin/linux-64/proxy

## QA

### bin can't execute on alpine docker container

```text
apk add --no-cache libc6-compat
```