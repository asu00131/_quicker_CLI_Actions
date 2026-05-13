# 等待剪贴板内容改变

**模块**: `sys:waitClipboardChange`

**官方文档**: https://getquicker.net/KC/Help/Doc/waitclipboardchange

## 概述

等待剪贴板内容改变

## 输入参数

- `最长等待时间`
- `等待窗口关闭时取消`
- `失败后中止动作`

## 输出

- `是否改变`

## 注意事项

等待剪贴板改变后尽量不要立即使用模拟按键功能，建议增加100-200ms延迟

---
CLI使用说明来自 _quicker_CLI_Actions

## qka文件 StepRunnerKey 速查
| 文件 | StepRunnerKey |
|------|---------------|
| 0101_等待剪贴板内容改变_无参_sys_waitClipboardChange.qka | sys:waitClipboardChange |
| 0101_等待剪贴板内容改变_有参_sys_waitClipboardChange.qka | sys:waitClipboardChange |