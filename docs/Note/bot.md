# 复刻思路

> 以后如果chatGPT开放接口一定会兼容的。

受限于模型的输入限制。在设计上，我采用基于上下文检索的记忆池作为增强手段，来实现 80 轮上下的检索技巧。

## 信息层次

`x>80` 忘记
`4<x<80` 中间记忆
`x<4` 强记忆

目前改进方向有：关联度计算。

## Model Support

选型 `graia-saya` 作为插件管理器。