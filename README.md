# AgentDock

AgentDock 桌面应用发布仓库。

## 版本发布

每次发布新版时：
1. 使用 AgentDock 发布工具上传新版 exe；
2. 自动创建 GitHub Release 并更新 version.json（供应用内自动更新检查）。

version.json 格式：

```json
{ "version": "1.0.4", "url": "https://github.com/haoranbai0719/agentdock/releases/download/v1.0.4/AgentDock-1.0.4.exe", "notes": "更新说明" }
```
