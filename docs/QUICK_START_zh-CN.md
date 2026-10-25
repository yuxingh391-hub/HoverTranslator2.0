# HoverTranslator · 快速开始（Windows）

> **当前状态：发行说明预备稿。** 截至 `v0.7.21-rc.1`，公开仓库尚未提供下载。请勿使用来源不明的第三方安装包。本文供未来获准发行的版本使用。

## 运行条件

- Windows 64 位系统；具体兼容版本与最低硬件要求尚待跨设备验证。
- 未来提供的版本为 **Portable（便携版）**，无需安装项目的 Python 或 Conda 环境。
- 本地模型和必要 DLL 等资源必须与 `HoverTranslator.exe` 一起保留，**不要只复制 EXE 文件**。

## 使用方法

1. 从官方 GitHub **Releases** 页面取得已获准发行的 Windows ZIP；目前尚无可下载版本。
2. 完整解压 ZIP 至普通文件夹，例如 `D:\Apps\HoverTranslator`。
3. 运行解压目录中的 `HoverTranslator.exe`。
4. 按住 **Ctrl**，把鼠标悬停在英文单词上，查询词义及音标。
5. 按住 **Alt**，把鼠标悬停在英文句子上，触发 OCR 识别与中文翻译。

## 快捷键

| 操作 | 效果 |
|---|---|
| Ctrl + 鼠标悬停 | 查询单词/短语 |
| Alt + 鼠标悬停 | 翻译英文句子 |
| Ctrl + Alt + A | 显示/隐藏控制面板 |
| Ctrl + Alt + H | 暂停/恢复 |
| Ctrl + Alt + Q | 退出 |
| 连续按两次 Esc | 退出 |

默认悬停等待时间约为 **400 毫秒**；实际行为可能因配置或版本而变化。

## 设置和数据

用户配置、个人术语及日志通常保存在：`%LOCALAPPDATA%\HoverTranslator`。
更新或更换电脑前，先备份你的个人设置和术语；切勿将包含隐私内容的日志直接公开。

## 安全说明

如系统安全软件警告或阻止执行，**不要关闭防护或添加白名单来强制运行**。请记录告警详情，参照 [反馈指南](FEEDBACK_zh-CN.md) 联系维护者。

[发布状态](RELEASE_STATUS.md) · [授权说明](LICENSING_AND_THIRD_PARTIES.md) · [项目首页](../README.md)
