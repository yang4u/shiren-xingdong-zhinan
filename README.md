# 识人行动指南

把“理解他人”变成下一次对话中能实际尝试的一个动作。

这是一个基于 David Brooks《How to Know a Person》实践方法编写的 AI Agent Skill，用来准备真实沟通、模拟对话和复盘经历。默认中文交互，也支持英文练习。目录和调用标识为 `shiren-xingdong-zhinan`。

## 有什么用途

| 场景 | 它能帮助你做什么 |
| --- | --- |
| 和客户、同事、朋友或家人沟通前 | 明确一个目标，选择一个动作，准备自然的开场和后续问法 |
| 想练习倾听与提问 | 逐轮扮演虚构对话对象，等你回答后再继续，并给具体反馈 |
| 聊完觉得没听懂或说得不合适 | 区分原话与推断，找一个错过的时刻，设计下一次小实验 |
| 对方难过，不知道怎么支持 | 练习询问对方需要倾听、共同思考还是具体帮助 |
| 有分歧或需要表达反馈 | 练习澄清意图、确认共同目的，以及描述行为和影响 |
| 想用英语练习沟通 | 使用 12 张实践卡中的英文示例，或进行全英文演练 |

每次只练一个动作，默认一次只问一个问题。观察自己是否完成动作、对方是否纠正或补充信息；不以“让对方同意我”为成功标准。

这里的“识人”指通过倾听与校准逐步理解一个人，不从几句话给人贴标签或预测内心。

## 使用示例

```text
用 $shiren-xingdong-zhinan 帮我准备和客户的一次困难沟通，一次问我一个问题。
```

```text
用 $shiren-xingdong-zhinan 模拟一个同事抱怨被忽视的场景，我想练习复述校准。
```

```text
用 $shiren-xingdong-zhinan 复盘这段聊天，找出一个我急着给建议的时刻。
```

```text
Use $shiren-xingdong-zhinan to help me practice active listening in English, one turn at a time.
```

## 安装到 Codex

下载或克隆本仓库，把包含 `SKILL.md` 的整个文件夹放入：

```text
~/.codex/skills/shiren-xingdong-zhinan/
```

保留 `references/` 和 `agents/` 两个子目录。技能无需 API 密钥、额外脚本运行环境或其他技能。

```text
shiren-xingdong-zhinan/
├── SKILL.md
├── agents/openai.yaml
└── references/practices.md
```

其他支持 Agent Skills 格式的工具可以读取 `SKILL.md`；本项目尚未逐个平台验证兼容性。

## 方法与来源

实践卡覆盖专注、具体经历、追问意义、接收视角、复述校准、不抢故事、容许停顿、按需支持、修复分歧、更新理解、人生故事和诚实反馈。

来源：David Brooks, *How to Know a Person: The Art of Seeing Others Deeply and Being Deeply Seen*, Random House, 2023。

本项目为独立的实践改写，与作者和出版社无隶属关系。只提供原创技能指令、意译总结和原创英文示例，不提供书籍文件或原文长篇摘录。准备／演练／复盘流程和观察标准为本项目的设计，不是书中原样课程。

## 边界与验证

技能不作心理诊断，不保证真人按模拟方式回应，不用沟通技巧逼迫披露或操控他人。调用技能不自动授权发送消息、记录隐私、修改笔记或创建提醒。

YAML、技能命名、界面元数据与引用路径已检查；实际关系效果和多平台自动触发行为尚未验证。根据真实使用反馈逐步改进。
