# ups-poweroff
用于非智能 UPS 环境下，局域网络断开时自动关闭设备。

## make 

```bash
go build .
```

## edit config 

```bash
vim config.toml
```
> 配置文件和编译好的程序需要放在同一个目录下

# add crontab 

```
* * * * * * /path/ups-poweroff
```
