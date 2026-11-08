# Harness & Contracts 移植

任务：从 milind-soni/OpenMausBot 的 server/contracts.ts 和 server/harness 目录把 SPI 定义和事件总线抄到 xconnect-clawbot 的 server 层。

- contracts 定义驱动接口和运行时事件类型
- harness 是注册 + 扇入，新模型提供商等于加一个文件 + 一行注册
- 目标仓：xuliangwang1993-ops/xconnect-clawbot
- 开分支 harness-contracts-port
- Apache 2.0 署名保留，做适配层不要硬拷