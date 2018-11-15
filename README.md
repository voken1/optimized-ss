# Optimized-ss by vn
Optimized shadowsocks server on linux.

## Download these `2 files`:

Right click the filename below to save/download:

- [`ss-server`](https://github.com/VisionNetworkProject/optimized-ss/blob/master/ss-server?raw=true)
- [`config.json`](https://github.com/VisionNetworkProject/optimized-ss/blob/master/config.json?raw=true)

## Edit the `config.json` file

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

## Upload them to your server, allow x

```
chmod +x ss-server
```

## run `ss-server`

```
./ss-server
```

or
```
./ss-server&
```
