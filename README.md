# ImmortalWRT · ipq53xx 自用自动编译

本仓库是 [VIKINGYFY/immortalwrt](https://github.com/VIKINGYFY/immortalwrt) `owrt` 分支的个人 fork，
唯一用途：**每天北京时间早 8 点自动编译固件**，产物发布到 Releases。

## 拿固件
进入 [Releases](../../releases)，下载最新的：
- `*-squashfs-sysupgrade.bin` —— 已是 ImmortalWRT 时用这个（保留/不保留配置按需）
- `*-squashfs-factory.bin` —— 原厂固件首次刷入用

## 编译内容
- 源码分支：`owrt`（每次追上游最新 commit）
- 配置：v6 配置包（在本仓库根目录 `v6-config-pack.tar.gz`，含 .config / 自定义包）
- 目标：`qualcommbe/ipq53xx`，机型 `jdcloud_re-cs-06`
- 已含插件：nikki / mihomo-meta / lucky / vantage / fullconenat / logrotate 等
- 默认 LAN：`192.168.6.1`；默认 WiFi：`OWRT-2.4G` / `OWRT-5.2G`，密码 `12345678`

## 手动触发
Actions → `Build ImmortalWRT ipq53xx` → Run workflow（已开启每日定时）。

## 工作流配置
`.github/workflows/build.yml`（ccache 加速，产物自动上传 Release）。

部分源码取自以下项目：

https://github.com/JiaY-shi/openwrt.git

https://github.com/JuliusBairaktaris/openwrt-ppe-nss.git

https://github.com/pbs05/ponwrt.git

https://github.com/perceival/openwrt-flint3.git

## Star History

<a href="https://www.star-history.com/?repos=vikingyfy%2Fimmortalwrt&type=date&legend=top-left">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=vikingyfy/immortalwrt&type=date&theme=dark&legend=top-left" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=vikingyfy/immortalwrt&type=date&legend=top-left" />
   <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=vikingyfy/immortalwrt&type=date&legend=top-left" />
 </picture>
</a>
