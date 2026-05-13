# 生成一个新的Guid

**模块**: `sys:newGuid`

**官方文档**: https://getquicker.net/KC/Help/Doc/newguid

## 概述

生成一个新的Guid

## 输入参数



## 输出

- `GUID`

---
CLI使用说明来自 _quicker_CLI_Actions

## qka文件 StepRunnerKey 速查
| 文件 | StepRunnerKey |
|------|---------------|
| 0303_生成一个新的Guid_生成Guid_无参_sys_newGuid.qka | sys:newGuid |
| 0303_生成一个新的Guid_生成Guid_有参_sys_assign.qka | sys:assign |

## Enum 枚举值参考

### format 格式
| 值 | 说明 |
|---|---|
| D | 默认：00000000-0000-0000-0000-000000000000 |
| N | 去除连字符：00000000000000000000000000000000 |
| B | 大括号包围：{00000000-0000-0000-0000-000000000000} |
| P | 小括号包围：(00000000-0000-0000-0000-000000000000) |
| H | 十六进制：{0x00000000, 0x0000, 0x0000, {0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00}} |