### 先弃更，最近编译出来的没有wifi，我还没找到解决方案
大家可以转去
https://github.com/Hyy2001X/AutoBuild-Actions
这个也挺好用的！

# 新路由3（Newifi-D2）自动编译最新版OpenWrt（Lede）

*每12小时自动编译一次，在Action中下载*

## 编译特性
- 默认主题为argon
- 默认使用开源WIFI驱动（支持802.11kvr）
- 默认启用helloworld
- 外挂存储支持格式exfat, ntfs, ext4

## 插件列表

| 插件名                  | 说明               |
| ---------------------- | ----------------- | 
| aliddns                | 阿里云DDNS         |  
| aria2                  | Aria2下载工具       |
| frpc/frps              | 内网穿透客户端/服务端 |
| hd-idle                | 硬盘休眠            |
| openvpn/openvpn-server | OpenVPN客户端/服务端 |
| samba                  | Samba文件共享       |
| ttyd                   | 网页终端            |
| xlnetacc               | 迅雷快鸟            |
| helloworld             | -                  |


*如需多拨功能，取消`.github/workflows/NEWIFI-D2.yml`中如下三行的注释*
```
# CONFIG_PACKAGE_luci-app-mwan3=y
# CONFIG_PACKAGE_luci-app-mwan3helper=y
# CONFIG_PACKAGE_luci-app-syncdial=y
```
## 网关地址
- IP 192.168.1.1
- Username root
- Password password

## Credits
- [coolsnowwolf/lede](https://github.com/coolsnowwolf/lede)
- [KFERMercer/OpenWrt-CI](https://github.com/KFERMercer/OpenWrt-CI)
