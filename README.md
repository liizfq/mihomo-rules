# mihomo-rules

armbian (.31) mihomo 的自维护规则集，由 mihomo rule-provider 直接订阅本仓库。

| 文件 | 用途 | 规则数 |
|---|---|---|
| `world-deny.yaml` | 🛑 全球拦截（广告/追踪） | ~592 |
| `reject.yaml` | REJECT 拦截（两字段，provider policy 生效） | ~1746 |
| `ai-reject.yaml` | AI/字节系广告 REJECT（AI-audit 管理，定期合并 anti-AD） | ~93 |
| `appclear.yaml` | 🍃 应用净化（国内 App 广告/遥测） | ~1017 |

更新方式：直接 PR/commit 到本仓库，armbian 按 interval 自动拉取。
