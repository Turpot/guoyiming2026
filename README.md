# guoyiming · 2026

> 血肉苦痛，机械飞升。

基于郭一鸣的表达习惯与个人资料编写的 Agent Skill，用于消息起草、口吻改写和个人自述。

## 版本说明

本仓库为 **2026 年版本**，保存该年度整理的表达习惯、个人经历与生活背景。资料反映记录时的情况，不代表持续更新的当前状态。使用时如与本人最新说明冲突，以最新说明为准。

技能名称及调用方式为 `guoyiming` / `$guoyiming`；年度版本标记为 `2026`。

## 目录

```text
guoyiming/
├── SKILL.md
├── agents/
│   └── openai.yaml
├── references/
│   ├── voice.md
│   ├── memories.md
│   └── experiences.md
├── README.md
├── LICENSE
└── .gitignore
```

## 安装

将本仓库克隆或解压为所用客户端的技能目录下的 `guoyiming` 文件夹，确保其中直接包含 `SKILL.md`。

Codex 用户可将该文件夹放入 `~/.codex/skills/`；配置了 `CODEX_HOME` 时，使用该目录下的 `skills/`。其他支持 `SKILL.md` 的客户端按各自的技能加载方式安装。

## 使用

在支持命名调用的 Codex 客户端中使用 `$guoyiming`，例如：

```text
用 $guoyiming 帮我起草一条给同学的回复：今晚没空，明天下午可以一起做实验。
```

也可以要求改写已有消息，或根据指定经历起草自述。提供收件人与表达目的，有原消息时一并提供。

## 参考资料

| 文件 | 用途 |
| :--- | :--- |
| [SKILL.md](SKILL.md) | 触发条件、处理流程与输出要求 |
| [references/voice.md](references/voice.md) | 表达习惯、语气与场景示例 |
| [references/memories.md](references/memories.md) | 2026 年的生活背景与偏好 |
| [references/experiences.md](references/experiences.md) | 成长经历与个人回忆 |

按任务需要读取背景资料，不自动把私人经历写进回复。资料中的状态对应记录时间，冲突时以本人最新说明为准。

## 使用范围

本技能用于拟稿和风格参考，不提供聊天账号接入或自动发送功能。生成内容不代表本人的真实意愿；缺少的经历与事实不作补写。

## 许可证

[MIT](LICENSE)
