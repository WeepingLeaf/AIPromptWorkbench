# AIPromptWorkbench

AIPromptWorkbench 是一款面向 AI 创作流程的 Windows 桌面工具，用于整理、管理、检索和复用提示词资产。它适合经常使用 AI 图像生成、AI 视频生成、文本生成、角色设定、分镜设计和镜头描述的用户。

软件的核心目标是把零散的提示词片段整理成可维护、可搜索、可复用的结构化素材库，让提示词不再只是临时复制粘贴的文本，而是可以长期积累和分发的创作资产。

## 主要功能

- 管理普通提示词词条，例如角色、场景、动作、风格、镜头、光影、负面提示词等内容。
- 管理 AI 系统提示词方案，用于保存完整的任务规则、工作流提示词和系统提示词配置。
- 支持提示词超市，方便快速浏览、搜索和复制常用提示词。
- 支持悬浮窗快捷面板，可在其它创作软件前台工作时快速调用提示词。
- 支持视频模板与场景详细编辑，便于拆分和组合复杂的视频生成提示词。
- 支持变量化模板，提高同类提示词在不同角色、地点、镜头和风格之间的复用效率。
- 支持 Git 提示词仓库，可从远程仓库同步提示词资源，并与本地私有内容分开管理。
- 支持提示词可见性、许可信息和加密分发相关设置。
- 支持应用内检查更新。

## 官方提示词仓库

AIPromptWorkbench 可订阅 Git 提示词仓库。官方提示词仓库地址：

```text
https://gitee.com/WeepingLeaf/AI-Prompt-Repository.git
```

用户可以通过该仓库获取公开提示词资源，也可以根据相同结构维护自己的私有或团队提示词仓库。

## 下载与安装

请从官方 GitHub 或 Gitee Release 页面下载安装器：

```text
https://github.com/WeepingLeaf/AIPromptWorkbench/releases
https://gitee.com/WeepingLeaf/AIPromptWorkbench/releases
```

安装包文件名通常为：

```text
AIPromptWorkbench_Setup_<version>.exe
```

当前安装器尚未进行代码签名，Windows SmartScreen 可能显示安全提示。请确认下载来源为官方发布页面后再安装。

## 更新与校验

发布页通常包含：

- `AIPromptWorkbench_Setup_<version>.exe`：Windows 安装器。
- `latest.json`：应用内更新检查使用的版本清单。
- `SHA256SUMS.txt`：发布文件的 SHA256 校验信息。
- `CHANGELOG.md`：版本更新日志。

如果需要确认安装包完整性，可以对下载的安装器计算 SHA256，并与 `SHA256SUMS.txt` 中的记录进行比对。

## 数据存储

AIPromptWorkbench 会在本机保存用户的提示词、设置、仓库缓存、密钥文件和项目数据。默认数据目录位于：

```text
%LOCALAPPDATA%\AIPromptWorkbench
```

卸载软件时可以选择是否删除本地用户数据。选择保留后，重新安装仍可继续使用原有配置和素材。

## 适用人群

- AI 图像、AI 视频创作者。
- 需要长期维护提示词库的用户。
- 经常制作角色设定、场景描述、镜头提示词和风格提示词的创作者。
- 需要管理个人或团队提示词资产的用户。
- 希望通过 Git 仓库同步、分发和更新提示词资源的用户。

## 版本记录

完整版本变化请查看：

```text
CHANGELOG.md
```
