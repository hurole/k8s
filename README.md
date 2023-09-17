## Ipv6
局域网设置：fd00::/8
也就是fdxx.xxxx.xxxx.xxxx.xxxx.xxxx.xxxx.xxxx

### 配置 service-cidr
都是剩余20位
ipv4（32位）: 10.96.00.00/12
ipv6（128位）: fd00::/108

### 配置pod-cidr
128-16=112
ipv4: 10.244.0.0/16
ipv6: fd00::1:0/112