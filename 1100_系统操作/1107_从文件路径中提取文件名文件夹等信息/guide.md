# 从文件路径中提取文件名、文件夹等信

**模块**: `sys:pathExtraction`

**官方文档**: https://getquicker.net/KC/Help/Doc/pathextraction

## 概述

从文件路径中提取文件名、文件夹等信

## 输入参数

- `路径`
- `提取类型`

## 输出

- `结果`

---
CLI使用说明来自 _quicker_CLI_Actions

## qka文件 StepRunnerKey 速查
| 文件 | StepRunnerKey |
|------|---------------|
| 1107_从文件路径中提取文件名文件夹等信息_合并路径_拼接_无参_sys_pathExtraction.qka | sys:pathExtraction |
| 1107_从文件路径中提取文件名文件夹等信息_合并路径_拼接_有参_sys_pathExtraction.qka | sys:pathExtraction |
| 1107_从文件路径中提取文件名文件夹等信息_提取文件路径信息_无参_sys_pathExtraction.qka | sys:pathExtraction |
| 1107_从文件路径中提取文件名文件夹等信息_提取文件路径信息_有参_sys_pathExtraction.qka | sys:pathExtraction |
| 1107_从文件路径中提取文件名文件夹等信息_更改所在目录，文件名不变_无参_sys_pathExtraction.qka | sys:pathExtraction |
| 1107_从文件路径中提取文件名文件夹等信息_更改所在目录，文件名不变_有参_sys_pathExtraction.qka | sys:pathExtraction |
| 1107_从文件路径中提取文件名文件夹等信息_更改扩展名，其它不变_无参_sys_pathExtraction.qka | sys:pathExtraction |
| 1107_从文件路径中提取文件名文件夹等信息_更改扩展名，其它不变_有参_sys_pathExtraction.qka | sys:pathExtraction |
| 1107_从文件路径中提取文件名文件夹等信息_更改文件名_不含扩展名和所在目录_无参_sys_pathExtraction.qka | sys:pathExtraction |
| 1107_从文件路径中提取文件名文件夹等信息_更改文件名_不含扩展名和所在目录_有参_sys_pathExtraction.qka | sys:pathExtraction |
| 1107_从文件路径中提取文件名文件夹等信息_更改文件名_含扩展名_，所在目录不变_无参_sys_pathExtraction.qka | sys:pathExtraction |
| 1107_从文件路径中提取文件名文件夹等信息_更改文件名_含扩展名_，所在目录不变_有参_sys_pathExtraction.qka | sys:pathExtraction |

## Enum 枚举值参考

### operation 操作类型
| 值 | 说明 |
|---|---|
| getInfo | 提取文件路径信息 |
| changeExt | 更改扩展名，其它不变 |
| changeName | 更改文件名(含扩展名)，所在目录不变 |
| changeNameWithoutExt | 更改文件名(不含扩展名和所在目录) |
| changeDir | 更改所在目录，文件名不变 |
| combine | 合并路径 (拼接) |