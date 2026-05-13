# 运行脚本

**模块**: `sys:runScript`

**官方文档**: https://getquicker.net/KC/Help/Doc/runscript

## 概述

运行脚本

## 输入参数

- `脚本内容`
- `脚本类型`

## 输出

- `结果`

---
CLI使用说明来自 _quicker_CLI_Actions

## qka文件 StepRunnerKey 速查
| 文件 | StepRunnerKey |
|------|---------------|
| 0704_运行脚本_AutoHotKey脚本_ahk_无参_sys_runScript.qka | sys:runScript |
| 0704_运行脚本_AutoHotKey脚本_ahk_有参_sys_runScript.qka | sys:runScript |
| 0704_运行脚本_BAT批处理脚本_bat_无参_sys_runScript.qka | sys:runScript |
| 0704_运行脚本_BAT批处理脚本_bat_有参_sys_runScript.qka | sys:runScript |
| 0704_运行脚本_CMD命令_完成后保留窗口_无参_sys_runScript.qka | sys:runScript |
| 0704_运行脚本_CMD命令_完成后保留窗口_有参_sys_runScript.qka | sys:runScript |
| 0704_运行脚本_CMD命令_完成后关闭窗口_无参_sys_runScript.qka | sys:runScript |
| 0704_运行脚本_CMD命令_完成后关闭窗口_有参_sys_runScript.qka | sys:runScript |
| 0704_运行脚本_CMD命令_隐藏命令行窗口_无参_sys_runScript.qka | sys:runScript |
| 0704_运行脚本_CMD命令_隐藏命令行窗口_有参_sys_runScript.qka | sys:runScript |
| 0704_运行脚本_CMD批处理脚本_cmd_无参_sys_runScript.qka | sys:runScript |
| 0704_运行脚本_CMD批处理脚本_cmd_有参_sys_runScript.qka | sys:runScript |
| 0704_运行脚本_PowerShell脚本_ps1_无参_sys_runScript.qka | sys:runScript |
| 0704_运行脚本_PowerShell脚本_ps1_有参_sys_runScript.qka | sys:runScript |

## Enum 枚举值参考

### type 脚本类型
| 值 | 说明 |
|---|---|
| CMD_K | CMD命令 (完成后保留窗口) |
| CMD_C | CMD命令 (完成后关闭窗口) |
| CMD_H | CMD命令 (隐藏命令行窗口) |
| BAT | BAT批处理脚本(.bat) |
| CMD_F | CMD批处理脚本(.cmd) |
| PS | PowerShell脚本(.ps1) |
| AHK | AutoHotKey脚本(.ahk) |
| CUSTOM | 自定义脚本类型 |

### encoding 文件编码
| 值 | 说明 |
|---|---|
| utf-8 | UTF8 |
| utf-16 | UTF-16 LE |
| utf-16BE | UTF-16 BE |
| us-ascii | ASCII |
| utf-7 | UTF7 |
| utf-32 | UTF32 |
| default | 系统默认(gb2312) |

### outputEncoding 控制台输出编码
| 值 | 说明 |
|---|---|
| utf8 | UTF8 |
| oem | OEM |