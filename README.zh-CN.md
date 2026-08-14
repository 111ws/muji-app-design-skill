# 无印风 App 设计 Skill

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

<a href="./README.md" style="display:inline-block; padding:8px 16px; background-color:#2196F3; color:white; text-align:center; text-decoration:none; border-radius:4px; font-weight:bold; margin:5px;">🇬🇧 English</a>

一个可移植的 AI skill，编码了无印风移动应用的设计原则。  
将这个 skill 加载到任何兼容的 AI 工具中，即可获得关于极简 App 设计的专家建议。

## 这是什么？

本仓库包含一个 **skill** —— 一组结构化的指令和知识，可以加载到 AI 助手（如 Claude、ChatGPT 或自定义代理）中。  
加载后，AI 可以：

- 根据无印风原则评估你的 App 信息架构。
- 建议导航结构、内容优先级和启动页策略。
- 为极简移动应用提供可操作的设计建议。

## 如何使用

### 用于 AI 工具

1. 下载或克隆本仓库。
2. 复制 [`skill/SKILL.md`](./skill/SKILL.md) 的内容。
3. 将其粘贴到你的 AI 工具中作为系统提示或知识库。
4. 开始提问，例如：
   - “我应该如何设计我的极简购物 App 的导航？”
   - “我应该把折扣信息放在哪里？”
   - “对于高频积分功能，最好的启动页策略是什么？”

### 用于人类

你也可以直接阅读 skill 文件作为一份全面的设计指南。  
完整内容见 [`skill/SKILL.md`](./skill/SKILL.md)。

## 仓库结构

- `skill/SKILL.md` —— 核心 skill（指令 + 知识）。
- `examples/` —— 展示 skill 效果的示例对话。
- `LICENSE` —— MIT 许可证。

## 贡献

欢迎贡献！请提交 issue 或 pull request 来改进这个 skill。

## 许可证

MIT
