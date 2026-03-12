---
name: security-paper-writer-plus
description: 安全领域专业论文写作助手（Security Paper Writer Plus），专门针对网络安全、系统安全、AI安全等领域的顶会论文写作。支持从安全论文中持续学习写作技巧。使用场景：(1)写作："帮我写NDSS/CCS/USENIX论文"、"生成Threat Model章节"、"设计Security Evaluation"； (2)学习："学习这篇NDSS论文的写作技巧"、"提取Attack Scenario写法"； (3)查询："Security论文Introduction怎么写"、"常见Evaluation指标"。触发词："安全论文"、"Security"、"Threat Model"、"Attack"、"NDSS"、"CCS"、"USENIX"、"security-paper"。
---

# Security Paper Writer Plus

**安全领域顶会论文专业写作助手**，针对 NDSS、CCS、USENIX Security、S&P 等安全顶会论文写作优化，支持持续学习。

---

## 🎯 核心能力

### 1. 安全论文特有章节支持
- **Threat Model** - 威胁模型设计
- **Attack Scenario** - 攻击场景描述
- **Security Evaluation** - 安全性评估
- **Ethical Considerations** - 伦理考量

### 2. 顶会风格适配
- NDSS - 网络与分布式系统安全
- CCS - 计算机与通信安全
- USENIX Security - 系统安全
- S&P (Oakland) - 安全与隐私

### 3. 持续学习能力
从安全论文中自动提取：
- 攻击描述句式
- 防御方案表达
- 实验设计模式
- 安全评估指标

---

## 📂 目录结构

```
security-paper-writer-plus/
├── SKILL.md                          # 本文件
│
├── references/
│   ├── static/                       # 📘 静态参考
│   │   ├── security-sections.md      # 安全论文章节模板
│   │   ├── attack-vocabulary.md      # 攻击描述词汇库
│   │   ├── evaluation-metrics.md     # 安全评估指标
│   │   └── venue-styles.md           # 顶会风格指南
│   │
│   └── learned/                      # 📗 动态学习
│       ├── README.md                 # 学习系统说明
│       ├── papers/                   # 论文学习记录
│       │   ├── index.md              # 学习索引
│       │   ├── ndss2026-f1118.md     # NDSS论文学习
│       │   └── ...
│       └── consolidated/             # 整合pattern库
│           ├── threat-model-patterns.md
│           ├── attack-scenario-patterns.md
│           ├── security-eval-patterns.md
│           └── ethical-consideration-patterns.md
```

---

## 🔐 安全论文写作规范

### 标准结构（NDSS/CCS/USENIX）

```
1. Abstract (150-250 words)
   - Problem + Security Impact
   - Proposed Solution
   - Key Results (quantitative)
   - Significance

2. Introduction
   - Security Problem Motivation
   - Real-world Impact
   - Limitation of Existing Solutions
   - Our Approach
   - Contributions (3-4 points)
   - Paper Organization

3. Background & Motivation
   - Technical Background
   - Threat Landscape
   - Motivating Example/Case Study

4. Threat Model
   - Adversary Capabilities
   - Attack Surface
   - Assumptions
   - Out of Scope

5. System Design / Methodology
   - Overview
   - Key Components
   - Security Properties

6. Implementation
   - Prototype Details
   - Deployment Considerations

7. Security Evaluation
   - Attack Effectiveness
   - Defense Effectiveness
   - Performance Overhead

8. Discussion
   - Limitations
   - Ethical Considerations
   - Responsible Disclosure

9. Related Work
   - By Theme (not by paper)

10. Conclusion
    - Summary
    - Future Work
```

---

## 📝 安全写作特色

### 1. 攻击描述模式

**常见开头**：
- "An adversary can exploit..."
- "We identify a novel attack vector..."
- "This vulnerability allows..."

**影响描述**：
- "This can lead to..."
- "The consequences include..."
- "An attacker could..."

### 2. 防御方案表达

**建议式**：
- "We propose..."
- "Our defense mechanism..."
- "To mitigate this threat..."

**验证式**：
- "We demonstrate that..."
- "Our evaluation shows..."
- "Experimental results confirm..."

### 3. 安全评估表达

**量化描述**：
- "with X% detection rate"
- "reduces attack success by Y%"
- "introduces Z% overhead"

**对比描述**：
- "outperforms existing approaches"
- "compared to baseline methods"
- "in contrast to prior work"

---

## 🔄 持续学习流程

### 学习触发

```
您："学习这篇NDSS论文的写作技巧"
    [提供PDF路径/URL]
```

### 自动提取内容

| 章节 | 提取内容 | 最少Pattern |
|---|---|---|
| Abstract | 问题陈述、影响描述、结果表达 | 5 |
| Introduction | 动机、贡献点、过渡句式 | 10 |
| Threat Model | 攻击者模型、能力描述、假设表达 | 8 |
| Methodology | 设计描述、组件介绍、安全属性 | 10 |
| Evaluation | 指标表达、对比句式、结果描述 | 10 |
| Discussion | 局限性、伦理考量、披露说明 | 5 |

### 学习产出

每篇论文生成：
1. `papers/ndss{year}-{id}.md` - 完整学习记录
2. 更新 `consolidated/*.md` - 整合pattern库
3. 更新 `papers/index.md` - 学习索引

---

## 📊 使用示例

### 1. 写作任务

```
您："帮我写Threat Model章节，场景是Web应用XSS攻击"

我：生成包含：
- Adversary Capabilities
- Attack Surface
- Assumptions
- Out of Scope
使用 learned pattern 库中的句式
```

### 2. 学习任务

```
您："学习 /path/to/ndss-paper.pdf"

我：
1. 分析论文结构
2. 提取各章节pattern
3. 生成英文变体
4. 创建学习记录
5. 更新整合库
```

### 3. 查询任务

```
您："NDSS论文Introduction怎么写？"

我：展示：
- 标准结构
- 安全领域特色开头
- 贡献点模板
- 已学习的pattern示例
```

---

## ✅ 质量标准

### 学习质量

| 维度 | 标准 |
|---|---|
| Pattern数量 | 每章节 ≥ 5个 |
| 变体数量 | 每Pattern ≥ 10个 |
| 可复用性 | 可直接用于写作 |
| 安全特色 | 包含安全领域专属表达 |

### 写作质量

| 维度 | 标准 |
|---|---|
| 结构完整 | 符合顶会标准 |
| 表达专业 | 使用安全领域术语 |
| 逻辑清晰 | 论证链条完整 |
| 数据准确 | 量化结果明确 |

---

## 🎓 已学习论文索引

| 论文ID | 来源 | 状态 | 学习日期 |
|---|---|---|---|
| ndss2026-f1118 | Web安全 | 待学习 | - |

（随着学习进度自动更新）

---

## 🚀 快速开始

### 第一次使用

1. 提供第一篇论文开始学习
2. 或直接使用 static 目录中的预设模板

### 典型工作流

```
学习阶段：
1. 提供3-5篇目标顶会论文
2. 自动提取pattern
3. 建立写作资产库

写作阶段：
1. 指定章节和场景
2. 基于学习库生成内容
3. 迭代优化
```

---

## 📌 注意事项

1. **安全伦理**：所有攻击描述需包含防御方案
2. **责任披露**：涉及真实漏洞需说明披露流程
3. **数据隐私**：实验数据需符合隐私规范
4. **可复现性**：提供足够的实现细节

---

## 🔄 更新记录

- **v0.1.0** (2026-03-12) - 初始版本，创建基础框架

---

_最后更新：2026-03-12_
