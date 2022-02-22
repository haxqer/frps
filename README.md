# frps
---
frp 服务端一键安装脚本(最简单的，没有之一)
+ 自动拉取最新版的 frps
+ frps 使用 systemctl 管理
+ 支持的操作系统: CentOS/Debian/Ubuntu/Fedora (32bit/64bit)

---
安装 frps
```bash
bash -c "$(curl -fsSL https://raw.githubusercontent.com/haxqer/frps/master/install_frps.sh)"
```

如果你在墙内，安装 frps

```bash
bash -c "$(curl -fsSL https://gitee.com/haxqer/frps/raw/master/install_frps_china.sh)"
```

启动
```bash
systemctl start frps
```

查看状态
```bash
systemctl status frps
```

开机自启
```bash
systemctl enable frps
```


配置文件: `/usr/local/etc/frp/frps.ini`


---


参考项目:
+ frps-onekey(https://github.com/MvsCode/frps-onekey)
