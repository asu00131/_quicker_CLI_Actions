# 文件和目录操

**模块**: `sys:fileOperation`

**官方文档**: https://getquicker.net/KC/Help/Doc/fileoperation

## 概述

文件和目录操

## 输入参数

- `操作类型`
- `源路径`
- `目标路径`

## 输出

- `是否成功`
- `结果路径`

---
CLI使用说明来自 _quicker_CLI_Actions

## qka文件 StepRunnerKey 速查
| 文件 | StepRunnerKey |
|------|---------------|
| 1110_文件和目录操作_创建文件夹_无参_sys_fileOperation.qka | sys:fileOperation |
| 1110_文件和目录操作_创建文件夹_有参_sys_fileOperation.qka | sys:fileOperation |
| 1110_文件和目录操作_创建空文件_无参_sys_fileOperation.qka | sys:fileOperation |
| 1110_文件和目录操作_创建空文件_有参_sys_fileOperation.qka | sys:fileOperation |
| 1110_文件和目录操作_删除文件_不支持文件夹_无参_sys_fileOperation.qka | sys:fileOperation |
| 1110_文件和目录操作_删除文件_不支持文件夹_有参_sys_fileOperation.qka | sys:fileOperation |
| 1110_文件和目录操作_删除空文件夹_无参_sys_fileOperation.qka | sys:fileOperation |
| 1110_文件和目录操作_删除空文件夹_有参_sys_fileOperation.qka | sys:fileOperation |
| 1110_文件和目录操作_复制为_指定结果名称或路径_无参_sys_fileOperation.qka | sys:fileOperation |
| 1110_文件和目录操作_复制为_指定结果名称或路径_有参_sys_fileOperation.qka | sys:fileOperation |
| 1110_文件和目录操作_复制到指定目录下_Windows_无参_sys_fileOperation.qka | sys:fileOperation |
| 1110_文件和目录操作_复制到指定目录下_Windows_有参_sys_fileOperation.qka | sys:fileOperation |
| 1110_文件和目录操作_复制文件_文件夹（自动）_不建议使用_无参_sys_fileOperation.qka | sys:fileOperation |
| 1110_文件和目录操作_复制文件_文件夹（自动）_不建议使用_有参_sys_fileOperation.qka | sys:fileOperation |
| 1110_文件和目录操作_移入回收站_无参_sys_fileOperation.qka | sys:fileOperation |
| 1110_文件和目录操作_移入回收站_有参_sys_fileOperation.qka | sys:fileOperation |
| 1110_文件和目录操作_移入回收站（安静模式，自动确认操作）_无参_sys_fileOperation.qka | sys:fileOperation |
| 1110_文件和目录操作_移入回收站（安静模式，自动确认操作）_有参_sys_fileOperation.qka | sys:fileOperation |
| 1110_文件和目录操作_移动_重命名为_指定结果名称或完整路径_无参_sys_fileOperation.qka | sys:fileOperation |
| 1110_文件和目录操作_移动_重命名为_指定结果名称或完整路径_有参_sys_fileOperation.qka | sys:fileOperation |
| 1110_文件和目录操作_移动_重命名文件_夹）（自动）_不建议使用_无参_sys_fileOperation.qka | sys:fileOperation |
| 1110_文件和目录操作_移动_重命名文件_夹）（自动）_不建议使用_有参_sys_fileOperation.qka | sys:fileOperation |
| 1110_文件和目录操作_移动到指定目录下_Windows_无参_sys_fileOperation.qka | sys:fileOperation |
| 1110_文件和目录操作_移动到指定目录下_Windows_有参_sys_fileOperation.qka | sys:fileOperation |
| 1110_文件和目录操作_移动到指定目录下_无参_sys_fileOperation.qka | sys:fileOperation |
| 1110_文件和目录操作_移动到指定目录下_有参_sys_fileOperation.qka | sys:fileOperation |
| 1110_文件和目录操作_获取文件夹内的子文件夹_无参_sys_fileOperation.qka | sys:fileOperation |
| 1110_文件和目录操作_获取文件夹内的子文件夹_有参_sys_fileOperation.qka | sys:fileOperation |
| 1110_文件和目录操作_获取文件夹内的文件_无参_sys_fileOperation.qka | sys:fileOperation |
| 1110_文件和目录操作_获取文件夹内的文件_有参_sys_fileOperation.qka | sys:fileOperation |

## Enum 枚举值参考

### type 操作类型
| 值 | 说明 |
|---|---|
| copyInto | 复制到指定目录下 |
| copyIntoWithShell | 复制到指定目录下(Windows) |
| copyTo | 复制为（指定结果名称或路径） |
| moveInto | 移动到指定目录下 |
| moveIntoWithShell | 移动到指定目录下(Windows) |
| rename | 移动/重命名为（指定结果名称或完整路径） |
| deleteFile | 删除文件（不支持文件夹） |
| recycle | 移入回收站 |
| recycleNoUi | 移入回收站（安静模式，自动确认操作） |
| makeDir | 创建文件夹 |
| createFile | 创建空文件 |
| enumFiles | 获取文件夹内的文件 |
| enumDirs | 获取文件夹内的子文件夹 |
| copyFile | 复制文件/文件夹（自动）【不建议使用】 |
| moveFile | 移动/重命名文件(夹)（自动）【不建议使用】 |