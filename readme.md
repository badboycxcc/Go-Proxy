# Go-Proxy 重构版

配置好config.ini中关于fofa的参数\
usage:
>   -f	使用-f参数指定读取文件，获取其中的代理使用\
-fofa  使用-fofa参数可从fofa收集资产获取公开代理使用\
> -c    使用-c参数可设置验证代理的协程数量，默认为200\
> -t    使用-t参数可设置验证代理的超时时间，默认为10秒\
> 成功后socks代理监听1080端口即可

计划修改Socks5来源，从Fofa爬取到Github下载
