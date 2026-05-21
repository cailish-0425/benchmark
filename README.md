# benchmark

AI 评测与学习工具集。包含可复用的方法论框架，用于评测集设计和课程笔记整理。

## 包含的 Skill

### [eval-dataset-design](./eval-dataset-design/)
AI 模型评测集设计框架。输入项目信息，输出构建原则、评测维度、打分规则和 case 样例。

### [course-notes](./course-notes/)
课程笔记整理框架。从录音转写和个人笔记中提炼结构化高质量笔记。

---

每个 Skill 都是独立的 SKILL.md 文件，可以单独使用。

## 使用方式

这些是 [Hermes Agent](https://github.com/NousResearch/hermes-agent) 的 Skill 文件。

```bash
# 复制到 Hermes 全局 skills 目录
cp -r eval-dataset-design ~/.hermes/skills/productivity/
cp -r course-notes ~/.hermes/skills/productivity/
```

也可以不通过 Hermes，直接按各 SKILL.md 的流程手动执行。

## License

MIT
