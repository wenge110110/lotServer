常规自动安装

bash <(wget --no-check-certificate -qO- https://raw.githubusercontent.com/wenge110110/lotServer/master/lotServerInstall.sh) install

指定内核安装

bash <(wget --no-check-certificate -qO- https://raw.githubusercontent.com/wenge110110/lotServer/master/lotServerInstall.sh) install <Kernel Version>

完全卸载

bash <(wget --no-check-certificate -qO- https://raw.githubusercontent.com/wenge110110/lotServer/master/lotServerInstall.sh) uninstall

Debian / Unbuntu更换自动内核（运行后需重启）

bash <(wget --no-check-certificate -qO- 'https://moeclub.org/attachment/LinuxShell/Debian_Kernel.sh')

调教手册

https://github.com/wenge110110/lotServer/blob/master/lotServer.pdf

备注：锐速状态查询以及一些配置文件位置。修改配置文件在/appex/etc下的config文件。

使用方法

启动命令：/appex/bin/lotServer.sh start

停止加速：/appex/bin/lotServer.sh stop

状态查询：/appex/bin/lotServer.sh status

重新启动：/appex/bin/lotServer.sh restart

更新许可：/appex/bin/serverSpeeder.sh renewLic

ServerSpeeder：/serverspeeder/bin/serverSpeeder.sh restart

LotServer：/appex/bin/serverSpeeder.sh restart
