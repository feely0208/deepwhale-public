# 深鲸 DSH 插件清单

> 插件安装在 DeepWhale Desktop / DSH profile 中使用；以下为公开插件，源码与版本以各仓库/npm 为准。

## 法律工具

| 插件 | 用途 |
|---|---|
| `@deepwhale-cn/dsh-legal-viz` | 诉讼可视化：时间轴、法律关系图、证据矩阵、争点对照 |
| `@deepwhale-cn/dsh-legal-damages` | 损害赔偿计算：人身损害、劳动、利息、违约金 |
| `@deepwhale-cn/dsh-legal-deadline` | 诉讼期限与费用计算：上诉/答辩/举证/执行期限、受理费/保全费/执行费 |
| `@deepwhale-cn/dsh-legal-cite-check` | 法律引用核验：法条、案例引用是否真实、现行有效 |
| `@deepwhale-cn/dsh-contract-check` | 合同体检：必备条款齐备性初筛 |
| `@deepwhale-cn/dsh-compliance-doc` | 合规文书生成 |
| `@deepwhale-cn/dsh-cn-doc-formatter` | 中文公文排版（GB/T 9704） |
| `@deepwhale-cn/dsh-doc-batch` | Word / Excel / PDF 批量处理 |

## 通用工具

| 插件 | 用途 |
|---|---|
| `@deepwhale-cn/dsh-badge` | 对外内容统一加 powered by dwh 徽章 |
| `dsh-memory-doctor` | 长会话记忆维护与压缩 |
| `@deepwhale-cn/dsh-token-cost` | Token 花费统计 |
| `@deepwhale-cn/dsh-qq-bridge` | QQ 消息桥接 |

## 安装示例

```bash
pnpm add @deepwhale-cn/dsh-legal-viz
```

安装后在 DSH 的插件面板启用；需要重启的插件会在 README 中注明。

---

powered by dwh · https://deepwhale.org.cn
