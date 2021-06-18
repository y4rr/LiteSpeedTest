# LiteSpeedTest

LiteSpeedTest is a simple tool for batch test ss/ssr/v2ray/trojan servers. 

 ![build](https://github.com/xxf098/LiteSpeedTest/workflows/test.yaml/badge.svg?branch=master&event=push) 

### Usage
```
Run as speed test tool:
    ./lite
    ./lite -p 10889

Run as http/socks5 proxy:
    ./lite vmess://aHR0cHM6Ly9naXRodWIuY29tL3h4ZjA5OC9MaXRlU3BlZWRUZXN0
    ./lite ssr://aHR0cHM6Ly9naXRodWIuY29tL3h4ZjA5OC9MaXRlU3BlZWRUZXN0
    ./lite -p 8091 vmess://aHR0cHM6Ly9naXRodWIuY29tL3h4ZjA5OC9MaXRlU3BlZWRUZXN0
```

### Build
```bash
    #require go>=1.16
    GOOS=js GOARCH=wasm go get -u ./...
    GOOS=js GOARCH=wasm go build -o ./web/main.wasm ./wasm
    go build -o lite
```

## Credits

- [clash](https://github.com/Dreamacro/clash)
- [stairspeedtest-reborn](https://github.com/tindy2013/stairspeedtest-reborn)
- [gg](https://github.com/fogleman/gg)

## Developer
```golang
// TODO
```
