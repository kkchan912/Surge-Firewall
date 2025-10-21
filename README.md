![代码质量](https://img.shields.io/badge/Code_Quality-Spaghetti-red)
![Bug 数量](https://img.shields.io/badge/Bugs_Found-Too_Many_To_Count-orange)
![维护者](https://img.shields.io/badge/Maintained_By-Coffee_and_Tears-blue)
</p>

`linux` `Surge5`
> *Talk is cheap. Show me the code.* — Linus Torvalds  

# 💡 项目特色
## Surge-Firewall 个人防火墙配置

这是一个个人使用的 [Surge 5](https://nssurge.com/) 防火墙与分流配置文件，旨在提供一个开箱即用的网络管理方案。

本项目包含一个主配置文件 (`Surge.conf`) 以及所有依赖的规则列表 (`.list`) 和规则集 (`CN-Ruleset`)。

## 🚀 如何使用 (一键导入)

您无需下载单独的规则文件，可以直接通过 URL 导入本仓库的**主配置文件**。
输入以下链接：

https://raw.githubusercontent.com/kkchan912/Surge-Firewall/refs/heads/main/Firewall.conf

导入后，您可能需要根据自己的节点（代理服务器）信息，在策略组 (Proxy Group) 中进行设置。

`⚠️注意事项`
* 本配置为个人自用，请根据您自己的网络环境和需求进行调整
* 导入配置后，**务必检查策略组**，并添加您自己的代理服务器节点，否则可能无法上网
* 作者不对使用本配置可能导致的任何问题负责

