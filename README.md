##Surge Configs
FileName|UpdateTime|QrCode
:---------:|:---------:|:---------:
[zCloud.conf](https://raw.githubusercontent.com/Brywmzl/Conf/master/File/Surge/zCloud.conf) |2017-2-10|[Show](http://qr.liantu.com/api.php?&w=500&text=https://raw.githubusercontent.com/Brywmzl/Conf/master/File/Surge/zCloud.conf)
[zCloud_Global.conf](https://raw.githubusercontent.com/Brywmzl/Conf/master/File/Surge/zCloud_Global.conf)|2017-2-10|[Show](http://qr.liantu.com/api.php?&w=500&text=https://raw.githubusercontent.com/Brywmzl/Conf/master/File/Surge/zCloud_Global.conf)
[SSEncrypt.module](https://github.com/Brywmzl/Conf/raw/master/File/Surge/SSEncrypt.module)||[Show](http://qr.liantu.com/api.php?&w=500&text=https://github.com/Brywmzl/Conf/raw/master/File/Surge/SSEncrypt.module)
##Shadowrocket Rule
FileName|UpdateTime|QrCode
:---------:|:---------:|:---------:
[zCloud.conf](https://github.com/Brywmzl/Conf/raw/master/File/Shadowrocket/zCloud.conf) |2017-2-10|[Show](http://qr.liantu.com/api.php?&w=500&text=https://github.com/Brywmzl/Conf/raw/master/File/Shadowrocket/zCloud.conf)
[zCloud_Global.conf](https://github.com/Brywmzl/Conf/raw/master/File/Shadowrocket/zCloud_Global.conf) |2017-2-10|[Show](http://qr.liantu.com/api.php?&w=500&text=https://github.com/Brywmzl/Conf/raw/master/File/Shadowrocket/zCloud_Global.conf)

##Update Content
优酷

    [Rule]
    DOMAIN,ad.mobile.youku.com,REJECT
    DOMAIN,ad.api.3g.youku.com,REJECT
    [URL Rewrite]
    ^http://api.mobile.youku.com/adv/* _reject
    ^http://home.mobile.youku.com/laout/* _reject
爱奇艺

    [Rule]
    DOMAIN-SUFFIX,qiyi.com,DIRECT
    DOMAIN-SUFFIX,iqiyi.com,DIRECT
    IP-CIDR,112.17.1.75/32,REJECT,no-resolve
    IP-CIDR,112.17.1.76/32,REJECT,no-resolve
    IP-CIDR,112.17.1.193/32,REJECT,no-resolve
    IP-CIDR,112.17.1.194/32,REJECT,no-resolve
    IP-CIDR,112.17.1.195/32,REJECT,no-resolve
    IP-CIDR,112.17.1.196/32,REJECT,no-resolve
    [URL Rewrite]
    ^http://iface.iqiyi.com/api/getNewAdInfo* _reject
    ^http://pic?(\d{1}).qiyipic.com/common/?(\d{8})/?([a-z0-9]{32}).jpg _reject
