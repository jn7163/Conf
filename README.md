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

##Rule
优酷
###方法一：  
下载 whitelist.pac或whiteiplist.pac或proxy.pac 文件后，修改代理服务器的 ip 地址和代理类型。然后将浏览器的代理设置中指向 whitelist.pac或whiteiplist.pac。

	var wall_proxy = 'PROXY www.abc.com:443;'; 
	以上需要更换成有效的代理地址，代理类型还可以为'SOCKS5'或'HTTPS'
	多个代理之间使用分号分隔，如'PROXY a.com:80;SOCKS5 a.com:1080;'

当 `proxy` 的代理类型为 `HTTPS` 时，此 pac 文件适合用于 [Google Chrome 的安全代理](http://www.chromium.org/developers/design-documents/secure-web-proxy)。
##URL Rewrite
