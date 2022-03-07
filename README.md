说明：luci-app-accesscontrol上网时间控制

luci-app-adguardhome广告过滤。若luci界面里配置完成，启动后显示”未运行 未重定向“，是因为编译时没有加入权限。

ssh登录openwrt后台，运行以下命令即可

chmod 755 /etc/init.d/AdGuardHome && service AdGuardHome restart
