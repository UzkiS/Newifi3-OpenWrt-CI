# 新路由 3（Newifi-D2）自动编译最新版 OpenWrt（Lede）

_每 12 小时自动编译一次，在 Action 中下载_

## 特性

- 主题: argon
- 开源 WIFI 驱动（支持 802.11kvr）
- 外挂存储:exfat, ntfs, ext4

## 插件

- aliddns
- aria2
- easymesh
- eqos // IP 网速控制
- frpc/frps // 内网穿透客户端+服务端
- helloworld
- hd-idle // 硬盘休眠
- mwan3/mwan3helper/syncdial // 均衡负载及多拨
- openvpn/openvpn-server
- qos
- samba // Samba 文件共享
- ttyd //网页终端
- turboacc // Turbo ACC 网络加速
- vlmcsd // KMS 服务器
- wolplus
- xlnetacc //迅雷快鸟
- zerotier

## 网关地址

- IP 192.168.1.1
- Username root
- Password password

## 也可以编译 K2 的固件

> 8M 的固件，要啥啥没有，删了挺多功能的，还没有实际上机测试过能不能跑，自己测试哈

## 编译思路

当从路由 mesh 用，也能勉强当当主路由

## 特性

- 多拨
- mesh

## 插件

- easymesh
- eqos // IP 网速控制
- mwan3/mwan3helper/syncdial // 均衡负载及多拨
- turboacc // Turbo ACC 网络加速

## 没有的功能

- curl
- dropbear
- opkg
- luci-app-filetransfer
- luci-app-nlbwmo
- luci-app-vsftpd
- luci-app-wol

## Credits

- [coolsnowwolf/lede](https://github.com/coolsnowwolf/lede)
- [KFERMercer/OpenWrt-CI](https://github.com/KFERMercer/OpenWrt-CI)
