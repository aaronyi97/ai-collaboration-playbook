# 示例：软件项目接棒

## 目标

修复导出按钮的加载状态。

## 当前状态

- 阶段：验证。
- 分支：`feature/export-loading`。
- 状态：已有本地改动，但还没跑完整测试。

## 已完成

- 给导出按钮增加了本地 `isExporting` 状态。  
  证据：`src/components/ExportButton.tsx`
- 补了失败后恢复状态的测试。  
  证据：`tests/export-button.test.tsx`

## 关键决定

- 加载态保持在组件本地。  
  原因：全局 loading store 对这个任务来说范围太大。

## 改动文件

| 文件 | 改动 | 状态 |
|---|---|---|
| `src/components/ExportButton.tsx` | 导出中禁用按钮 | 未验证 |
| `tests/export-button.test.tsx` | 增加失败恢复测试 | 未验证 |

## 废弃路线

- 用 `setTimeout` 假装加载。  
  原因：会掩盖真实请求状态。
- 做全局 loading store。  
  原因：小组件修复不需要扩大范围。

## 风险与未知

### 已验证事实

- 两个文件有改动。  
  证据：来源对话摘要。新 AI 应该用 `git status --short` 复查。

### 未确认

- 对应测试是否通过。  
  怎么确认：运行相关测试命令。
- 加载中按钮宽度是否抖动。  
  怎么确认：浏览器或截图检查。

## 下一步

```text
先运行 git status --short，确认改动范围，再决定是否编辑文件。
```

## 先读文件

1. `src/components/ExportButton.tsx` — 组件行为。
2. `tests/export-button.test.tsx` — 预期行为。

