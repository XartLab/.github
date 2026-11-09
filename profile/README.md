<div align="center">

# XartLab

**Tooling for AI coding agents — give the agent a map, a spec and an evidence gate before it writes.**

给 AI Agent 用的工程底座：先有地图、有规格、有证据门禁，再动手。

</div>

---

## 开源项目 · Projects

| 项目 | 做什么 | 语言 |
| --- | --- | --- |
| [**code-intel-pipeline**](https://github.com/XartLab/code-intel-pipeline) | 本地代码理解管线：架构地图、热点、变更影响面、结构回归门禁，在 Agent 改代码之前产出。基于 `rg` + Repowise + Understand + Sentrux。 | Rust |
| [**design-pipeline**](https://github.com/XartLab/design-pipeline) | 前端设计管线：先写 `DESIGN.md` / `MOTION.md`，经 job 分发、OpenSpec 与证据门禁再写代码；内置风格包与模板。 | JavaScript |
| [**dream-harness**](https://github.com/XartLab/dream-harness) | Agent 驱动的短剧创作 harness：故事、剧本、资产、提示词、生成与验收，全程契约化（Apache-2.0）。 | JavaScript |

## 共同思路 · Principles

- **先看清再动手** — 让 Agent 先读结构、依据和契约，而不是直接改。
- **证据门禁** — 完成与否看命令输出、检查结果和产物，不看自述。
- **本地优先** — 分析与生成都在你自己的机器上完成。
- **人工验收** — 关键节点留给人点头。

## 快速开始 · Get started

```bash
# 代码仓结构地图 / repo map for your agent
git clone https://github.com/XartLab/code-intel-pipeline

# Claude Code 里安装设计管线 / install design-pipeline
/plugin marketplace add 2233admin/design-pipeline
/plugin install design-pipeline@design-pipeline
```

各项目的安装与用法见各自 README。

## 参与 · Contributing

欢迎 Issue 与 PR。提交前请先读对应仓库的 `README` 和 `AGENTS.md` / `CLAUDE.md`；Bug 请附复现命令与实际输出。
