# Learned Patterns System

This directory contains patterns automatically extracted from security papers.

## Directory Structure

```
learned/
├── papers/                   # Individual paper learning records
│   ├── index.md              # Master index of all learned papers
│   └── ndss2026-xxx.md       # Example: NDSS 2026 paper record
│
└── consolidated/             # Cross-paper consolidated patterns
    ├── threat-model-patterns.md
    ├── attack-scenario-patterns.md
    ├── security-eval-patterns.md
    └── ethical-consideration-patterns.md
```

## Learning Workflow

### 1. Paper Analysis
When a new paper is provided:
- Extract section structure
- Identify security-specific patterns
- Generate sentence variations

### 2. Pattern Extraction
For each section, extract:
- Opening patterns
- Transition patterns
- Closing patterns
- Security-specific vocabulary

### 3. Consolidation
After learning multiple papers:
- Merge similar patterns
- Create comprehensive templates
- Build vocabulary database

## Quality Standards

### Pattern Requirements
- **Quantity**: ≥5 patterns per section
- **Variations**: ≥10 variations per pattern
- **Security-specific**: Must include domain terminology
- **Reusable**: Can be directly applied to new writing

### Example Pattern Format

```markdown
## Pattern: Threat Actor Description

**Original** (from Paper X):
"An adversary with network access can intercept communications."

**Variations**:
1. An attacker capable of [capability] can [action].
2. We consider adversaries who have [access level].
3. The threat model assumes an attacker with [resources].
...
```

## Usage

### Querying Patterns
```
You: "Show me threat model patterns"
AI: Loads from consolidated/threat-model-patterns.md
```

### Writing with Patterns
```
You: "Write a threat model for XSS"
AI: 
1. Loads relevant patterns
2. Customizes for XSS scenario
3. Generates section content
```

## Maintenance

- **Update frequency**: After each paper learning
- **Consolidation trigger**: Every 5 papers
- **Quality check**: Before major writing tasks

---

_Last updated: 2026-03-12_
