# ImmortalWRT · ipq53xx 自用自动编译

本仓库是 [VIKINGYFY/immortalwrt](https://github.com/VIKINGYFY/immortalwrt) `owrt` 分支的个人 fork，
唯一用途：**每天北京时间早 7 点自动编译固件**，产物发布到 Releases。

## 编译内容
- 源码分支：`owrt`（每日追上游最新 commit）
- 配置：v6 配置包（在本仓库根目录 `v6-config-pack.tar.gz`，含 .config / 自定义包）
- 目标：`qualcommbe/ipq53xx`，机型 `jdcloud_re-cs-06`
- 已含插件：nikki / lucky / 等
- 默认 LAN：`192.168.6.1`；默认 WiFi：`OWRT`，密码 `12345678`
