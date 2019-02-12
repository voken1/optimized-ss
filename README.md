# Optimized shadowsocks

Optimized shadowsocks server on linux.


## Download to server

ubuntu:
```console
$ wget https://github.com/VisionNetworkProject/optimized-ss/releases/download/v1.2.2/ss-server-v1.2.2.tar.gz
$ tar xzf ss-server-v1.2.2.tar.gz
$ cd ss-server
$ chmod +x ss-server
```

## Edit the config file

```
{
    "port_password": {
        "80": "yourPassword1",
        "443": "yourPassword2"
    },
    "method": "chacha20-ietf",
    "timeout": 600
}
```

## Make it running

```console
$ cd /path/to/ss-server
$ ./ss-server
```

or
```console
$ cd /path/to/ss-server
$ ./ss-server&
```
