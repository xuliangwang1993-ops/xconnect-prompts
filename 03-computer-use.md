# Computer-Use Egress 移植

任务：把 browser-control、browser-stream-v1、computer-ask、computer-step、computer-panel 那套挂到 clawbot-api 的出站请求上。

- SOCKS5 egress gate 管 bot 浏览器流量
- 没配代理地址就禁用
- browser 和 proxy 改成必填配置
- agent 断线时硬阻断
- 开分支 computer-use-port