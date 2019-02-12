# optimized shadowsocks

Optimized shadowsocks server on linux.


## Download to server

ubuntu:
```console
$ wget ..
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
    "method": "aes-256-cfb",
    "timeout": 600
}
```

## Make it running

```
cd /path/to/ss-server
./ss-server
```

or
```
cd /path/to/ss-server
./ss-server&
```
