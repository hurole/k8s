## Ipv6

局域网设置：fd00::/8
也就是 fdxx.xxxx.xxxx.xxxx.xxxx.xxxx.xxxx.xxxx

### 配置 service-cidr

都是剩余 20 位
ipv4（32 位）: 10.96.00.00/12
ipv6（128 位）: fd00::/108

### 配置 pod-cidr

ipv4: 10.244.0.0/16
ipv6: fd00::1:0:0:0:0/64

## Monitor

### Prometheus

### Node-Exporter

### Grafana
