## 进度条
- [ ] 99% 的功能
- [ ] 剩下的 1% (这部分最难 😭)
- [x] 添加了一个酷炫的 README

---

### 🚨 警告
本项目处于 **“理论上可行，但现实骨感”** 阶段。请自行承担使用风险。
(别问我什么时候能完成，我也不知道 🤷‍♂️)






This repository contains the configuration file for the [Surge](https://nssurge.com) app to block domains from the Steven Black’s unified [hosts](https://raw.githubusercontent.com/StevenBlack/hosts/master/hosts).

There are three ways to use this domain set:

- Download `hosts.txt` to the Surge configuration directory and add the following line

    ```
    DOMAIN-SET,hosts.txt,REJECT
    ```
    in the `[Rule]` section before the `FINAL` line of your own configuration file. There's no automatic update using this method.
    
- Download the `Firewall.conf` file and import it into Surge. The domain set is automatically updated from this repository.

- You can also add the following line 

    ```
    DOMAIN-SET,https://raw.githubusercontent.com/Taxyovio/Surge-Firewall/main/hosts.txt,REJECT
    ```
    in the `[Rule]` section before the `FINAL` line of your own configuration file. The domain set is automatically updated from this repository.