# 操作Excel的某个区域或单元

**模块**: `sys:excelRange`

**官方文档**: https://getquicker.net/KC/Help/Doc/excelrange

## 概述

操作Excel的某个区域或单元

## 输入参数

- `工作表`
- `范围`
- `操作类型`
- `值`

## 输出

- `结果`

---
CLI使用说明来自 _quicker_CLI_Actions

## qka文件 StepRunnerKey 速查
| 文件 | StepRunnerKey |
|------|---------------|
| 0208_操作Excel的某个区域或单元格_替换内容_无参_sys_excelRange.qka | sys:excelRange |
| 0208_操作Excel的某个区域或单元格_替换内容_有参_sys_excelRange.qka | sys:excelRange |
| 0208_操作Excel的某个区域或单元格_获取区域信息_无参_sys_excelRange.qka | sys:excelRange |
| 0208_操作Excel的某个区域或单元格_获取区域信息_有参_sys_excelRange.qka | sys:excelRange |
| 0208_操作Excel的某个区域或单元格_行高_列宽_无参_sys_excelRange.qka | sys:excelRange |
| 0208_操作Excel的某个区域或单元格_行高_列宽_有参_sys_excelRange.qka | sys:excelRange |
| 0208_操作Excel的某个区域或单元格_设置值_无参_sys_excelRange.qka | sys:excelRange |
| 0208_操作Excel的某个区域或单元格_设置值_有参_sys_excelRange.qka | sys:excelRange |
| 0208_操作Excel的某个区域或单元格_设置公式_无参_sys_excelRange.qka | sys:excelRange |
| 0208_操作Excel的某个区域或单元格_设置公式_有参_sys_excelRange.qka | sys:excelRange |
| 0208_操作Excel的某个区域或单元格_设置数值格式_无参_sys_excelRange.qka | sys:excelRange |
| 0208_操作Excel的某个区域或单元格_设置数值格式_有参_sys_assign.qka | sys:assign |
| 0208_操作Excel的某个区域或单元格_调用方法_无参_sys_excelRange.qka | sys:excelRange |
| 0208_操作Excel的某个区域或单元格_调用方法_有参_sys_excelRange.qka | sys:excelRange |

## Enum 枚举值参考

### subRange 限定子范围
| 值 | 说明 |
|---|---|
| FullArea | 整个区域 |
| FirstRow | 区域内的第一行 |
| FirstColumn | 区域内的第一列 |
| LastRow | 区域内最后一行 |
| LastColumn | 区域内最后一列 |
| ActiveCell | 活动单元格 |
| EntireRow | 整行(包含区域外) |
| EntireColumn | 整列(包含区域外) |
| Rows | 所有行(区域范围内) |
| Columns | 所有列(区域范围内) |

### operation 操作类型
| 值 | 说明 |
|---|---|
| SetValue | 设置值 |
| SetFormula | 设置公式 |
| SetNumberFormat | 设置数值格式 |
| SetCellSize | 行高,列宽 |
| SetStyle | 设置格式 |
| CallMethod | 调用方法 |
| Replace | 替换内容 |
| GetRangeInfo | 获取区域信息 |