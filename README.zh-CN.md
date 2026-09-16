# Professional Title Engine · 标题大师版

> 先挖内容内核，再做平台分发；标题可以冲，但不能编。

`professional-title-engine` 是一个面向公众号、小红书、知乎、头条、抖音、视频号及其他内容平台的专业标题 Skill，支持中英文自动语言匹配。

## 核心能力

- 标题生成、诊断、改写、候选比较
- 多平台标题矩阵
- 六类内容内核：意外事实、反转、真实代价、冲突、改变判断的数字、读者切身利害
- 六类零编造承诺校验：数字、实体、身份、结果、路径/篇幅、程度词
- 稳妥 / 有点冲 / 顶格三档力度
- 历史标题表现复盘
- 个人 Title DNA 学习
- 外部优秀标题机制反推：学机制，不抄句式
- CASE / TENTATIVE / STABLE 三档证据置信度

## 快速使用

```text
使用 $professional-title-engine，基于下面文章生成 9 个公众号标题。
先提炼内容内核，再给稳妥 / 有点冲 / 顶格三档。
```

学习账号标题 DNA：

```text
这是我过去 50 篇公众号标题和 24 小时数据。
先检查哪些数据可比，再学习我的标题 DNA，不要把相关性写成因果。
```

反推优秀标题：

```text
分析下面这批优秀标题为什么有网感，只学习机制，不要照抄句式。
然后用我的正文重新生成一组。
```

## 安装

### Codex

复制整个目录：

```text
skills/professional-title-engine/
```

不要只复制 `SKILL.md`，因为 Skill 还使用 `references/` 与 `templates/`。

### Claude Code

仓库包含 `.claude-plugin/plugin.json`，可作为 Claude Code 插件仓库加载。

## 语言

主入口 `SKILL.md` 自动匹配用户语言：

- 中文输入 → 中文输出
- English input → English output
- 明确要求双语 → 中英双语

完整本地化文件：

- `SKILL.zh-CN.md`
- `SKILL.en.md`

## 核心模型

**标题 = 内容内核 × 真实承诺 × 读者状态 × 平台分发 × 表达力度 × 个人标题DNA**

标题不能保证阅读量、点击率或平台推荐。历史数据用于发现账号内的相关性与偏好，没有实验设计时不做因果断言。
