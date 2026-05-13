# 调用第三方服务翻译文字到指定的语言

**模块**: `sys:translation`

**官方文档**: https://getquicker.net/KC/Help/Doc/translation

## 概述

调用第三方服务翻译文字到指定的语言

## 输入参数

- `文本`
- `源语言`
- `目标语言`

## 输出

- `翻译结果`

---
CLI使用说明来自 _quicker_CLI_Actions

## qka文件 StepRunnerKey 速查
| 文件 | StepRunnerKey |
|------|---------------|
| 0905_调用第三方服务翻译文字到指定的语言_单厂商文字翻译_无参_sys_translation.qka | sys:translation |
| 0905_调用第三方服务翻译文字到指定的语言_单厂商文字翻译_有参_sys_translation.qka | sys:translation |
| 0905_调用第三方服务翻译文字到指定的语言_多厂商文字翻译_无参_sys_translation.qka | sys:translation |
| 0905_调用第三方服务翻译文字到指定的语言_多厂商文字翻译_有参_sys_translation.qka | sys:translation |
| 0905_调用第三方服务翻译文字到指定的语言_英汉词典_无参_sys_translation.qka | sys:translation |
| 0905_调用第三方服务翻译文字到指定的语言_英汉词典_有参_sys_translation.qka | sys:translation |

## Enum 枚举值参考

### operation 操作类型
| 值 | 说明 |
|---|---|
| single | 单厂商文字翻译 |
| multiple | 多厂商文字翻译 |
| en2zh_dict | 英汉词典 |

### vendor 厂商
| 值 | 说明 |
|---|---|
| Aliyun | 阿里云 |
| Baidu | 百度 |
| Tencent | 腾讯云 |
| Youdao | 网易有道 |
| Caiyun | 彩云 |
| Xunfei | 讯飞 |
| XunfeiNiuts | 讯飞(2代) |
| Google | 谷歌 |

### vendorList 厂商列表
| 值 | 说明 |
|---|---|
| Youdao,Baidu,Tencent,Caiyun | 默认多厂商列表 |