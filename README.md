# Claude Code Skills

Claude Code 自定义 Skills 集合，包含多个提升开发效率的技能。

## 包含 Skills

### 1. guide - 真人感教程/科普写作
让 AI 写出像真人写的教程和科普文章，彻底告别 AI 味。

**触发关键词**：教程、科普、tutorial、guide、simplifying

**使用方式**：`/guide`

### 2. program-learning - 高级源码教学/架构解析
深入讲解代码实现细节，带你达到独立修改、重构、扩展模块的能力。

**触发条件**：想学习源码、理解代码架构、需要深入讲解代码实现细节时

**使用方式**：`/program-learning`

---

## 安装方法

### 克隆到本地

```bash
git clone https://github.com/MEKOELITE/claude-code-skill.git

# 复制需要的 skill 到 Claude Code skills 目录
cp -r claude-code-skill/guide ~/.claude/skills/
cp -r claude-code-skill/program-learning ~/.claude/skills/
```

### 使用符号链接

```bash
# 在你的项目根目录下
mkdir -p .claude/skills
ln -s /path/to/claude-code-skill/guide .claude/skills/guide
ln -s /path/to/claude-code-skill/program-learning .claude/skills/program-learning
```

## 文件结构

```
claude-code-skill/
├── README.md                    # 本文件
├── SKILL.md                     # guide skill 入口
├── guide/
│   └── SKILL.md                 # guide 核心文件
└── program-learning/
    └── SKILL.md                 # program-learning 核心文件
```

## 许可证

MIT License - 欢迎自由使用、修改和分享。

---

如果对你有帮助，欢迎 ⭐ Star！
