[![GitHub Release](https://img.shields.io/github/release/openwrt-xiaomi/kmod-xmir-patcher)](https://github.com/openwrt-xiaomi/kmod-xmir-patcher/releases)
[![Github All Releases](https://img.shields.io/github/downloads/openwrt-xiaomi/kmod-xmir-patcher/total)](https://github.com/openwrt-xiaomi/kmod-xmir-patcher/releases)
[![Github Latest Release](https://img.shields.io/github/downloads/openwrt-xiaomi/kmod-xmir-patcher/latest/total)](https://github.com/openwrt-xiaomi/kmod-xmir-patcher/releases)
[![ViewCount](https://views.whatilearened.today/views/github/openwrt-xiaomi/kmod-xmir-patcher.svg)](https://github.com/openwrt-xiaomi/kmod-xmir-patcher/releases)
[![Hits](https://hits.sh/github.com/openwrt-xiaomi/kmod-xmir-patcher.svg?color=79C83D)](https://hits.sh/github.com/openwrt-xiaomi/kmod-xmir-patcher/)
[![Donations Page](https://github.com/andry81-cache/gh-content-static-cache/raw/master/common/badges/donate/donate.svg)](https://github.com/remittor/donate)

# kmod-XMiR-Patcher
Linux kernel module for hacking xq kernel


## Usage

```
insmod /tmp/xmir_patcher.ko

echo 'get_mtd_info|bdata' > /sys/module/xmir_patcher/parameters/cmd
cat /sys/module/xmir_patcher/parameters/cmd

echo 'set_mtd_rw|bdata' > /sys/module/xmir_patcher/parameters/cmd
cat /sys/module/xmir_patcher/parameters/cmd
```

## Donations

[![Donations Page](https://github.com/andry81-cache/gh-content-static-cache/raw/master/common/badges/donate/donate.svg)](https://github.com/remittor/donate)
