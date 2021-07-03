# Actions-OpenWrt

[![LICENSE](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square&label=LICENSE)](https://github.com/P3TERX/Actions-OpenWrt/blob/master/LICENSE)
![GitHub Stars](https://img.shields.io/github/stars/P3TERX/Actions-OpenWrt.svg?style=flat-square&label=Stars&logo=github)
![GitHub Forks](https://img.shields.io/github/forks/P3TERX/Actions-OpenWrt.svg?style=flat-square&label=Forks&logo=github)

使用 GitHub Actions 编译 X86OpenWrt

[Read the details in my blog (in Chinese) | 中文教程](https://p3terx.com/archives/build-openwrt-with-github-actions.html)

## Usage

- 单击 [Use this template](https://github.com/P3TERX/Actions-OpenWrt/generate) 按钮创建一个新的仓库.
-  `.config` 文件使用 [Lean's OpenWrt](https://github.com/coolsnowwolf/lede) 源代码生成文件。（您可以通过工作流文件中的环境变量进行更改。）
- 将 `.config` 文件上传到 GitHub 仓库.
-  `Build OpenWrt` 在操作页面上选择.
- 单击 `Run workflow` 按钮.
- 编译完成后, 单击 `Artifacts` 操作页面右上角的按钮下载编译后的固件.

## 固件介绍

![插件列表](https://cdn.jsdelivr.net/gh/wxfyes/x86openwrt/img/l.png)
![插件列表](https://cdn.jsdelivr.net/gh/wxfyes/x86openwrt/img/2.png)
![插件列表](https://cdn.jsdelivr.net/gh/wxfyes/x86openwrt/img/3.png)
![插件列表](https://cdn.jsdelivr.net/gh/wxfyes/x86openwrt/img/4.png)
![插件列表](https://cdn.jsdelivr.net/gh/wxfyes/x86openwrt/img/5.png)
![插件列表](https://cdn.jsdelivr.net/gh/wxfyes/x86openwrt/img/6.png)

## 固件使用说明
- 包含软件：PassWall、ShadowSocksR Plus+、AdGuard Home、OpenClah、SmartDNS、bypass等
- 默认IP 192.168.1.1  密码 password
# 自动更新说明
固件采用自动编译，Acrions将会在每天监控上游代码是否更新，如passwall ssrp等，一旦检测到上游代码更加将会自动编译打包，也就是说L大只要已更新，就会触发脚本自动编译最新版固件！
# 更多内容请移驾博客网站[晓峰部落阁](https://wxf2088.xyz)

## 感谢

- [Microsoft Azure](https://azure.microsoft.com)
- [GitHub Actions](https://github.com/features/actions)
- [OpenWrt](https://github.com/openwrt/openwrt)
- [Lean's OpenWrt](https://github.com/coolsnowwolf/lede)
- [tmate](https://github.com/tmate-io/tmate)
- [mxschmitt/action-tmate](https://github.com/mxschmitt/action-tmate)
- [csexton/debugger-action](https://github.com/csexton/debugger-action)
- [Cowtransfer](https://cowtransfer.com)
- [WeTransfer](https://wetransfer.com/)
- [Mikubill/transfer](https://github.com/Mikubill/transfer)
- [softprops/action-gh-release](https://github.com/softprops/action-gh-release)
- [ActionsRML/delete-workflow-runs](https://github.com/ActionsRML/delete-workflow-runs)
- [dev-drprasad/delete-older-releases](https://github.com/dev-drprasad/delete-older-releases)
- [peter-evans/repository-dispatch](https://github.com/peter-evans/repository-dispatch)

## 原作者

[MIT](https://github.com/P3TERX/Actions-OpenWrt/blob/main/LICENSE) © P3TERX
