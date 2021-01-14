![visitor badge](https://visitor-badge.laobi.icu/badge?page_id=keyword&title=viewers) ![GitHub all releases](https://img.shields.io/github/downloads/stephensund/OpenWrt-AutoBuild/total?style=flat-square)

编译个人自用的设备的OpenWrt固件

在[stephensund/OpenWrt-AutoBuild](https://github.com/stephensund/OpenWrt-AutoBuild)的基础上修改   
感谢[P3TERX/Actions-Openwrt](https://github.com/P3TERX/Actions-OpenWrt)提供的脚本    
感谢Lean [coolsnowwolf/lede](https://github.com/coolsnowwolf/lede)和CTCGFW's Team [project-openwrt/openwrt](https://github.com/project-openwrt/openwrt)

源码均使用[project-openwrt/openwrt](https://github.com/project-openwrt/openwrt) openwrt-18.06-k5.4分支

默认LAN IP:192.168.2.1

默认用户名root，密码password

## 编译设备
|   设备   |  编译状态  |  对应Actions链接  |
|  ----  |  ----  |  ----  |
|  X86_64  | ![X86_64](https://img.shields.io/github/workflow/status/stephensund/Actions-OpenWrt/X86_64-Openwrt?style=flat-square) |  <a href="https://github.com/stephensund/Actions-OpenWrt/actions?query=workflow%3AX86_64-Openwrt"><img src="https://img.shields.io/badge/Actions-x86__64-blueviolet?style=flat-square" alt="x86_64"></a>  |
|  Nanopi-R2S |  ![Nanopi-R2S](https://img.shields.io/github/workflow/status/stephensund/Actions-OpenWrt/Nanopi-R2S-Openwrt?style=flat-square)  |  <a href="https://github.com/stephensund/Actions-OpenWrt/actions?query=workflow%3ANanopi-R2S-Openwrt"><img src="https://img.shields.io/badge/Actions-R2S-blueviolet?style=flat-square" alt="R2S"></a>  |
|  Nanopi-R4S  |  ![Nanopi-R4S](https://img.shields.io/github/workflow/status/stephensund/Actions-OpenWrt/Nanopi-R4S-Openwrt?style=flat-square)  |  <a href="https://github.com/stephensund/Actions-OpenWrt/actions?query=workflow%3ANanopi-R4S-Openwrt"><img src="https://img.shields.io/badge/Actions-R4S-blueviolet?style=flat-square" alt="R4S"></a>  |
|  Gl-iNet/GL-1300  |   |   |

## 主要包含插件列表
固件满足基本的上网/代理需求，暂不过多添加其他功能。

* Luci-app-ssr-plus [fw876/helloworld](https://github.com/fw876/helloworld)

* Luci-app-passwall [xiaorouji/openwrt-passwall](https://github.com/xiaorouji/openwrt-passwall)

* Luci-app-openclash [vernesong/Openclash](https://github.com/vernesong/OpenClash)

* Luci-app-smartdns [pymumu/smartdns](https://github.com/pymumu/smartdns)

* Luci-app-adguardhome及其核心文件 [rufengsuixing/luci-app-adguardhome](https://github.com/rufengsuixing/luci-app-adguardhome) [AdguardTeam/AdGuardHome](https://github.com/AdguardTeam/AdGuardHome)

* Luci-app-unblockmusic

* Luci-app-https-dns-proxy 其可在指定端口上运行指定服务商的DoH DNS服务，可以与代理配合使用

* Luci-theme-argon以及用于主题自定义设置的Luci-app-argon-config [jerrykuku/luci-theme-argon](https://github.com/jerrykuku/luci-theme-argon)
