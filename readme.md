### tornado实现的代理服务器 ###

本地运行  
`python localproxy.py 8888`

远端主机(国外vpn主机)(`http://www.xxx.com/`)  
`python remoteproxy.py 8889`

本地浏览器代理设置  
`127.0.0.1 8888`

settings配置  
`REMOTE_HOST = "http://www.xxx.com/"`