<div align="center">

# 🧬 Lewis OS

**首页头部 / Hero Section**

**构建你的数字身份，而不是收集你的提示词。**<br>
**Build your identity, not your prompts.**

[![Status](https://img.shields.io/badge/status-foundation-blue?style=flat-square)](#)
[![Version](https://img.shields.io/badge/version-v0.3-lightgrey?style=flat-square)](#)
[![License](https://img.shields.io/badge/license-TBD-orange?style=flat-square)](#)
[![Privacy](https://img.shields.io/badge/privacy-first-brightgreen?style=flat-square)](#)

Lewis OS 是一个 Digital Identity Framework（数字身份框架）：一种用可维护结构描述协作身份、偏好、原则和工作流的框架。它面向 Human-AI Collaboration（人机协作）：人类和 AI 持续共享上下文、分工和反馈的协作方式。<br>
Lewis OS is a Digital Identity Framework（数字身份框架）：a maintainable structure for describing collaborative identity, preferences, principles, and workflows. It is built for Human-AI Collaboration（人机协作）：a long-running way for humans and AI to share context, divide work, and exchange feedback.

</div>

---

## 🌐 项目简介 / Overview

Lewis OS 不是 Prompt Collection（提示词集合）：一组临时保存的提问文本。它更关注可复用的 Pattern（规律）：在不同任务中反复出现、可以被整理和执行的行为方式。<br>
Lewis OS is not a Prompt Collection（提示词集合）：a temporary set of saved prompts. It focuses on reusable Pattern（规律）：repeatable behavior that can be organized and executed across tasks.

> 记录规律，而不是记录个人。<br>
> Encode patterns, not people.

| 模块 / Area | 中文说明 | English |
| --- | --- | --- |
| Identity（身份） | 描述长期协作中的稳定偏好和原则。 | Describes stable preferences and principles for long-term collaboration. |
| Communication（沟通） | 统一术语、语气和协作信号。 | Aligns terminology, tone, and collaboration signals. |
| Decision（决策） | 沉淀高质量判断的通用规则。 | Captures reusable rules for better judgment. |
| Skills（技能） | 保存可重复执行的工作方法。 | Stores repeatable ways of working. |

---

## ❓ 为什么是 Lewis OS / Why Lewis OS

| 常见问题 | Lewis OS 的回答 |
| --- | --- |
| 提示词容易散落 | 把高价值 Prompt（提示词）升级为 Workflow（工作流）：可重复执行的任务过程。 |
| AI 每次都要重新理解你 | 把偏好、原则和协作协议写成公共安全的文档。 |
| 个人信息不适合公开 | 只记录可复用规律，不写入真实姓名、邮箱、公司、收入、健康、家庭或关系信息。 |
| 协作质量难以稳定 | 用 Convention（约定）：团队或系统共同遵守的规则，减少重复解释。 |

| Common Issue | Lewis OS Response |
| --- | --- |
| Prompts get scattered | Turn valuable Prompt（提示词） into Workflow（工作流）：a repeatable task process. |
| AI needs to relearn context | Encode preferences, principles, and collaboration protocols as public-safe documents. |
| Personal data should not be public | Store reusable patterns only, never private personal information. |
| Collaboration quality varies | Use Convention（约定）：shared rules followed by a team or system. |

---

## 🧭 核心理念 / Core Philosophy

| 原则 | English |
| --- | --- |
| 记录规律，而不是记录个人。 | Encode patterns, not people. |
| 真相先于迎合。 | Truth before flattery. |
| 隐私先于便利。 | Privacy before convenience. |
| 系统先于技巧。 | Systems before hacks. |
| 长期先于短期。 | Long-term over short-term. |

> Lewis OS 应该帮助协作者变得更清晰，而不是暴露更多个人细节。<br>
> Lewis OS should help collaborators become clearer, not more exposed.

---

## ✨ 核心能力 / Features

| 能力 | 中文说明 | English |
| --- | --- | --- |
| 🧩 Communication Protocol（沟通协议） | 定义协作信号、术语格式和表达习惯。 | Defines collaboration signals, term formats, and expression habits. |
| 🗣️ Bilingual Terms（双语术语） | 专业术语默认使用 `English（中文）`。 | Uses `English（中文）` for professional terms by default. |
| 🧠 Decision DNA（决策基因） | 保存可复用的长期判断原则。 | Stores reusable long-term judgment principles. |
| 🛠️ Skill Modules（技能模块） | 把写作、自动化等能力沉淀成独立文件。 | Captures abilities such as writing and automation in separate files. |
| 🔒 Privacy Boundary（隐私边界） | 明确禁止写入个人敏感信息。 | Explicitly avoids private personal information. |
| 📦 Public-Safe Structure（公开安全结构） | 适合放在公开仓库中持续维护。 | Designed for continuous maintenance in a public repository. |

---

## 🗂️ 项目结构 / Project Structure

```text
Lewis-OS/
├── AGENTS.md
├── CLAUDE.md
├── CONSTITUTION.md
├── README.md
├── README_PATCH.md
├── communication/
│   ├── lewis-protocol.yaml
│   └── term-style.md
├── decision/
│   └── decision-dna.md
├── modes/
│   ├── project.md
│   └── social.md
├── schemas/
│   └── communication-protocol.yaml
└── skills/
    ├── automation.md
    ├── investing.md
    └── writing.md
```

| 路径 | 用途 |
| --- | --- |
| `CONSTITUTION.md` | 保存不可轻易改变的核心原则。 |
| `communication/` | 保存沟通协议和术语风格。 |
| `schemas/` | 保存机器可读的协议结构。 |
| `modes/` | 保存不同协作场景下的模式。 |
| `skills/` | 保存可复用的能力模块。 |

| Path | Purpose |
| --- | --- |
| `CONSTITUTION.md` | Stores stable core principles. |
| `communication/` | Stores communication protocols and terminology style. |
| `schemas/` | Stores machine-readable protocol structure. |
| `modes/` | Stores modes for different collaboration contexts. |
| `skills/` | Stores reusable capability modules. |

---

## 💬 沟通约定 / Communication Convention

Professional Term（专业术语）：在某个领域中有稳定含义的词。第一次出现时，Lewis OS 使用简短解释帮助理解。<br>
Professional Term（专业术语）：a term with stable meaning in a specific field. On first use, Lewis OS adds a short explanation.

| 场景 | 格式 |
| --- | --- |
| 默认格式 | `English（中文）` |
| 第一次出现 | `English（中文）：一句话解释。` |
| 示例 | `Repository（仓库）：a place to store project code, documents, and history.` |

| Scenario | Format |
| --- | --- |
| Default | `English（中文）` |
| First occurrence | `English（中文）：one-sentence explanation.` |
| Example | `Workflow（工作流）：a repeatable process for completing a task.` |

协作信号：

| 中文信号 | 含义 |
| --- | --- |
| 执行 | 直接开始实现。 |
| 继续 | 沿着当前上下文推进。 |
| 改 | 保持方向，只修弱点。 |
| 定稿 | 打磨并完成最终版本。 |

Collaboration signals:

| Chinese Signal | Meaning |
| --- | --- |
| 执行 | Start implementation. |
| 继续 | Continue from current context. |
| 改 | Keep the direction and improve weak parts. |
| 定稿 | Polish and finalize. |

---

## 🛣️ 路线图 / Roadmap

- [x] 建立 Constitution（宪章）：项目不可轻易改变的核心原则。<br>
  Create Constitution（宪章）：stable core principles for the project.
- [x] 建立 Communication Protocol（沟通协议）。<br>
  Create Communication Protocol（沟通协议）.
- [x] 建立双语术语规范。<br>
  Create bilingual terminology convention.
- [ ] 增加 Schema Validation（结构校验）：检查协议文件是否符合预期结构。<br>
  Add Schema Validation（结构校验）：checks whether protocol files match the expected structure.
- [ ] 增加 Privacy Review Checklist（隐私审查清单）。<br>
  Add Privacy Review Checklist（隐私审查清单）.
- [ ] 增加更多 public-safe examples。<br>
  Add more public-safe examples.

---

## 🌱 愿景 / Vision

Lewis OS 希望把长期协作中的稳定模式，变成可阅读、可维护、可迁移的 Identity Layer（身份层）：系统用来理解协作者偏好和原则的基础结构。<br>
Lewis OS aims to turn stable collaboration patterns into a readable, maintainable, and portable Identity Layer（身份层）：the base structure a system uses to understand collaborator preferences and principles.

> 构建你的数字身份，而不是收集你的提示词。<br>
> Build your identity, not your prompts.

---

## 🤝 贡献 / Contributing

欢迎贡献可以公开维护的规则、协议、结构和工作流。<br>
Contributions are welcome when they improve public-safe rules, protocols, structures, and workflows.

| 请这样做 | 不要这样做 |
| --- | --- |
| 使用清晰的 Markdown（标记文档）：一种轻量文档格式。 | 不要写入真实姓名、邮箱、公司、收入、健康、家庭或关系信息。 |
| 保持中英文对照，中文在前，英文紧随其后。 | 不要把临时聊天内容直接堆进仓库。 |
| 优先沉淀可复用规律。 | 不要保存 API key、密码或其他密钥。 |
| 使用小而清晰的 Commit（提交）：保存一次变更到 Git 历史。 | 不要一次性混入无关改动。 |

| Do | Do Not |
| --- | --- |
| Use clear Markdown（标记文档）：a lightweight documentation format. | Do not add real names, emails, companies, income, health, family, or relationship information. |
| Keep bilingual content with Chinese first and English immediately after. | Do not dump temporary chat logs into the repository. |
| Prefer reusable patterns. | Do not store API keys, passwords, or other secrets. |
| Use small, clear Commit（提交）：one saved change in Git history. | Do not mix unrelated changes. |

---

## 📄 许可证 / License

当前仓库尚未包含正式 License（许可证）：定义他人如何使用、修改和分发项目的法律文件。添加许可证前，请不要假设本项目可自由使用、修改或分发。<br>
This repository does not yet include a formal License（许可证）：the legal file that defines how others may use, modify, and distribute the project. Until a license is added, do not assume free use, modification, or distribution.
