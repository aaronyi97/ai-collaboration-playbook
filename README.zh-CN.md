# AI Collaboration Playbook

[English README](README.md)

这是一个给 AI 编程工具、OpenClaw 和长期 AI 工作流使用的开源协作工具包。

每一期视频会对应一个可复用 Kit：视频讲问题，GitHub 放通用解决方案，不懂编程的人可以直接复制一段 Prompt 到 AI 编程工具里使用。

## 已有 Kit

| Kit | 解决的问题 | 适合场景 |
|---|---|---|
| [001 AI 接棒卡](kits/001-context-handoff/README.zh-CN.md) | 新 AI 对话接不上旧任务 | 换对话、换模型、换工具、多 AI 接力时不想重新解释项目 |

## 快速使用

如果你用的是 OpenClaw、Cursor、Claude Code、Codex 或其他 AI 编程工具，直接从这里开始：

[中文视频置顶评论版](kits/001-context-handoff/PINNED.zh-CN.md)

注意：不要只把 GitHub 链接发给 AI。请打开上面的文件，复制代码块里的整段启动词，再粘贴到 AI 编程工具。

如果你想看完整说明：

[AI 接棒卡 Kit](kits/001-context-handoff/README.zh-CN.md)

## 这个仓库怎么用

懂 GitHub 的人：

1. 打开对应 Kit。
2. 阅读 README 和 template。
3. 复制 START Prompt 到你的 AI 编程工具。
4. 按模板生成自己的交接卡。

不懂 GitHub 的人：

1. 打开视频置顶评论里的 `PINNED.zh-CN.md`。
2. 复制代码块里的整段启动词。
3. 粘贴到 OpenClaw / Cursor / Claude Code / Codex。
4. 让 AI 一步步问你问题，并生成可复制到新对话的接棒卡。

## 仓库结构

```text
.
├── README.md                 # 英文首页
├── README.zh-CN.md            # 中文首页
├── kits/
│   └── 001-context-handoff/
│       ├── README.md          # 英文说明
│       ├── README.zh-CN.md    # 中文说明
│       ├── START.md           # 英文一键启动 Prompt
│       ├── START.zh-CN.md     # 中文一键启动 Prompt
│       ├── PINNED.md          # 英文视频置顶评论版
│       ├── PINNED.zh-CN.md    # 中文视频置顶评论版
│       ├── template.md        # 英文模板
│       ├── template.zh-CN.md  # 中文模板
│       └── examples/
└── docs/
```

## 设计原则

1. **每期视频一个 Kit**：每个 Kit 只解决一个具体问题。
2. **优先服务 AI 编程工具**：Prompt 默认写给 OpenClaw / Cursor / Claude Code / Codex，不是普通网页版聊天。
3. **中英文双入口**：英文是 GitHub 默认入口，中文文件统一用 `.zh-CN.md`。
4. **先能用，再完善**：小而清楚的模板，比大而复杂的体系更重要。
5. **不暴露私有体系**：只公开通用方法，不公开个人治理配置、私密路径、对话记录和内部项目状态。

## License

MIT.
