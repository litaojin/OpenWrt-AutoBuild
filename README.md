# Actions-OpenWrt
编译个人自用的设备以及部分热门设备的OpenWrt固件，有需要的朋友请移步actions页面[Github Actions](https://github.com/stephensund/Openwrt-Actions/actions)自行下载，同时对应的Workflow页面会有奶牛快传和WeTransfer的下载链接，但是都只有7天有效期。

**个人无偿兴趣项目，不提供任何技术支持，请多动手上网搜寻相关知识，插件等问题请直接向源码维护者反馈，简介后面贴了一些主要插件的仓库地址**

感谢[P3TERX/Actions-Openwrt](https://github.com/P3TERX/Actions-OpenWrt)提供的脚本

感谢Lean [coolsnowwolf/lede](https://github.com/coolsnowwolf/lede)和CTCGFW's Team [project-openwrt/openwrt](https://github.com/project-openwrt/openwrt)维护的源码

本项目编译源码均使用：[project-openwrt/openwrt](https://github.com/project-openwrt/openwrt) openwrt-18.06-k5.4分支

各设备的Workflow会在周五CST 8:00自动触发

默认LAN IP:192.168.2.1

默认用户名root，密码password

## 编译设备
X86_64（含Luci-app-dockerman)

ASUS RT-ACRH17

G-Dock/P&W R619AC

XIAOMI/REDMI AC2100

FriendlyARM Nanopi-R2S（含Luci-app-dockerman)

FriendlyARM Nanopi-R4S（含Luci-app-dockerman) 

ARMv8通用镜像

## 主要包含插件列表
固件满足基本的上网/代理需求，暂不过多添加其他功能。

1.Luci-app-ssr-plus [fw876/helloworld](https://github.com/fw876/helloworld)

2.Luci-app-passwall [xiaorouji/openwrt-passwall](https://github.com/xiaorouji/openwrt-passwall)

3.Luci-app-openclash [vernesong/Openclash](https://github.com/vernesong/OpenClash)

4.Luci-app-smartdns [pymumu/smartdns](https://github.com/pymumu/smartdns)

5.Luci-app-adguardhome及其核心文件 [rufengsuixing/luci-app-adguardhome](https://github.com/rufengsuixing/luci-app-adguardhome) [AdguardTeam/AdGuardHome](https://github.com/AdguardTeam/AdGuardHome)

6.Luci-app-unblockmusic

7.Luci-app-https-dns-proxy 其可在指定端口上运行指定服务商的DoH DNS服务，可以与代理配合使用

8.Luci-theme-argon以及用于主题自定义设置的Luci-app-argon-config [jerrykuku/luci-theme-argon](https://github.com/jerrykuku/luci-theme-argon)
