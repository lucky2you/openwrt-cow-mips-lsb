cow for openwrt on mt7621
=========================

[COW](https://github.com/cyfdecyf/cow) 的mt7621编译版本，适用于MIPS LSB

```bash
export GOOS=linux
export GOARCH=mipsle
export GOMIPS=softfloat
go build -ldflags '-w -s'
upx -9 cow
```

