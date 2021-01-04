frps一键安装脚本，更新版本号到 v0.34.3

frp：https://github.com/fatedier/frp

引用脚本：https://github.com/clangcn/onekey-install-shell/blob/master/frps/install-frps.sh

frp 是一个高性能的反向代理应用，可以帮助您轻松地进行内网穿透，对外网提供服务，支持 tcp, http, https 等协议类型，并且 web 服务支持根据域名进行路由转发。

安装平台：CentOS、Debian、Ubuntu

Server
------

### Install

```Bash
wget --no-check-certificate https://raw.githubusercontent.com/pen9un/onekey-install-shell/master/frps/install-frps.sh -O ./install-frps.sh
chmod 700 ./install-frps.sh
./install-frps.sh install
```

### UnInstall
```Bash
    ./install-frps.sh uninstall
```
### Update
```Bash
    ./install-frps.sh update
```
### 服务器管理
```Bash
    Usage: /etc/init.d/frps {start|stop|restart|status|config|version}
```

