# 🔤 AI Regex Tools

AI正则表达式工具，支持正则生成、解释、测试。

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue?logo=python" />
  <img src="https://img.shields.io/badge/OpenAI-API-green?logo=openai" />
  <img src="https://img.shields.io/badge/License-MIT-yellow" />
</p>

## ✨ 特性

- 🔤 正则生成
- 📖 正则解释
- ✅ 正则测试
- ⚡ 正则优化
- 🔍 模式提取
- 📝 从示例生成

## 🚀 快速开始

```bash
pip install openai

python tools.py
```

## 📖 使用

```python
from ai_regex_tools import create_tools

tools = create_tools()

# 生成正则
result = tools.generate_regex("匹配手机号", ["13812345678"])

# 解释正则
explanation = tools.explain_regex(r"1[3-9]\d{9}")

# 测试正则
test = tools.test_regex(r"\d+", ["abc123", "xyz"])

# 优化正则
optimized = tools.optimize_regex(r"[0-9][0-9][0-9]")

# 提取模式
emails = tools.extract_patterns(text, "email")

# 从示例生成
result = tools.from_examples(["test@email.com"], ["not-email"])
```

## 📁 项目结构

```
ai-regex-tools/
├── tools.py       # 正则工具核心
└── README.md
```

## 📄 许可证

MIT License
