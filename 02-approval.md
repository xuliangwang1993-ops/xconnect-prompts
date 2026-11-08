# 审批闸门移植

任务：把 OpenMausBot 的审批体系迁到 clawbot 的 delegate 层。

- 模式分 auto / ask / edits 三档
- 审批卡在读 SubRouter 密钥之前触发
- auto-approve 有 safety-floor 校验
- approval card 组件 + approval-request-contract 测试一起带上
- 开分支 approval-port
- GitHub CLI 提交如果 404 就改用 GitHub API 直接推