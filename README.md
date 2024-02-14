# OpenWrt 官方 + LuCI
https://firmware-selector.openwrt.org/

## dnsmasq
```Diff
-dnsmasq
+dnsmasq-full
```


## Base LuCI
```
block-mount luci-base luci-compat luci-app-opkg luci-app-upnp
```
```
luci-i18n-base-zh-cn luci-i18n-firewall-zh-cn luci-i18n-opkg-zh-cn luci-i18n-upnp-zh-cn
```
## MultiWAN
```
luci-app-mwan3 luci-i18n-mwan3-zh-cn
```

# squashfs 扩容
https://kzpu.com/archives/5330.html

https://www.izilzty.com/?post=5
