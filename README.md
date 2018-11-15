# Optimized-ss by vn
Optimized shadowsocks server on linux.

## Download to server

ubuntu:
```
wget https://raw.githubusercontent.com/VisionNetworkProject/optimized-ss/master/optimized-ss.tar.gz
tar xzf optimized-ss.tar.gz
chmod +x optimized-ss/ss-server
cd optimized-ss
```

## Edit the `./optimized-ss/config.json` file

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

## run `ss-server`

```
cd /path/to/optimized-ss
./ss-server
```

or
```
cd /path/to/optimized-ss
./ss-server&
```
