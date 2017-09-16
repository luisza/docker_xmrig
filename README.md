# What is XMRig?

XMRig is the console miner provided by [XMRig](https://github.com/xmrig/xmrig).

XMRig supports Cryptonight, and Cryptonight-lite.

# How to use this image

Run in background:

```console
$ docker run -d --name YOUR_CONTAINER_NAME calvintam236/xmrig -a YOUR_ALGO -o YOUR_POOL_ADDRESS -u YOUR_USERNAME.YOUR_WORKER_NAME -p YOUR_WORKER_PASSWORD
```

Get `xmrig` options with:

```console
$ docker run --rm calvintam236/xmrig
```

Fetch logs of a container:

```console
$ docker logs YOUR_CONTAINER_NAME
```
