[惯例]
#验证
DOMAIN-KEYWORD,baidu,PROXY
#联网端口
PORT,65010,PROXY
PORT,10012,PROXY
#放行端口
DOMAIN-KEYWORD,com,DIRECT
DOMAIN-KEYWORD,xin,DIRECT
DOMAIN-KEYWORD,cn,DIRECT
DOMAIN-KEYWORD,net,DIRECT
# IP处理
IP-CIDR，43.154.240.179/32，直达
IP-CIDR，43.154.240.99/32，直达
IP-CIDR，61.151.229.52/32，直达
IP-CIDR，101.89.42.96/32，直达
IP-CIDR，117.131.23.224/32，直达
IP-CIDR，183.194.238.78/32，直接
IP-CIDR，116.128.169.246/32，直达
IP-CIDR，116.128.169.179/32，直达
#拒代端口
PORT,443,REJECT
FINAL,DIRECT

[路由域策略]
AsIs 似乎不是一个完整的句子或有明确意义

[自由战略]
AsIs 似乎不是一个完整的句子或有明确意义

[地方政策]
bufferSize = 4096
connIdle = 300
downlinkOnly = 0
握手=4
uplinkOnly = 0

[DnsServer]
8.8.8.8
114.114.114.114
119.29.29.29

[DnsRule]

[DnsHost]

[DnsClientIp]

[日志]
loglevel = none

[PerAppVpn]

[PerAppMode]

[PerAppAllow]

[允许]
