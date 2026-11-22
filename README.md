# ImmortalWRT · ipq53xx 自用自动编译

本仓库是 [VIKINGYFY/immortalwrt](https://github.com/VIKINGYFY/immortalwrt) `owrt` 分支的个人 fork，
唯一用途：**每天北京时间 06:37 自动编译固件**，产物发布到 Releases。

## 编译内容
- 源码分支：`owrt`（每日追上游最新 commit）
- 配置：`config-ipq53xx.txt`（在本仓库根目录，基于上游 IPQ53XX release 的 Config，加入 lucky）
- 目标：`qualcommbe/ipq53xx`，机型 `jdcloud_re-cs-06`
- 默认 LAN：`192.168.6.1`；默认 WiFi：`OWRT`，密码 `12345678`
