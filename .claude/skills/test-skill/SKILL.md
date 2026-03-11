---
name: test-skill
description: 这是一个测试技能，用于验证手动添加的技能是否能被自动加载。当用户说"测试技能"或使用 /test-skill 命令时触发。
---

# 测试技能

这是一个简单的测试技能，用于验证 ~/.claude/skills 目录下手动添加的技能是否能被 Claude Code 自动加载。

## 功能说明

当这个技能被触发时，Claude 会回复：
- ✅ 技能加载成功
- 📂 技能位置：~/.claude/skills/test-skill/

## 使用方式

你可以通过以下方式触发这个技能：
1. 直接说："测试技能"
2. 使用斜杠命令：`/test-skill`

## 技能内容

这个技能的作用是验证 Claude Code 确实会：
1. 自动扫描 ~/.claude/skills 目录
2. 加载目录下所有包含 SKILL.md 的文件夹
3. 根据 description 中的描述自动触发

如果你看到这条消息，说明技能加载成功了！
