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
    以上需要更换成有效的代理地址，代理类型还可以为'SOCKS5'或'HTTPS'
    多个代理之间使用分号分隔，如'PROXY a.com:80;SOCKS5 a.com:1080;'
	
爱奇艺

    [Rule]
    var wall_proxy = 'PROXY www.abc.com:443;'; 
    以上需要更换成有效的代理地址，代理类型还可以为'SOCKS5'或'HTTPS'
    多个代理之间使用分号分隔，如'PROXY a.com:80;SOCKS5 a.com:1080;'
	
