# CopperRiver Agents

Public agent profiles for [CopperRiver](https://copperriver.ai).

## Available Agents

| Agent | Category | Description |
|-------|----------|-------------|
| code-reviewer | development | Runs tests, checks edge cases, blocks bad code |
| debugger | development | Traces bugs from symptom to root cause |
| refactorer | development | Safe refactoring backed by tests |
| test-writer | development | Meaningful tests covering edge cases |
| security-auditor | security | OWASP Top 10, dependency CVEs, misconfigurations |
| researcher | research | Cross-referenced findings with citations |
| data-analyst | data | Dataset exploration, patterns, visualizations |
| tech-writer | writing | Accurate docs by reading actual code |
| devops | operations | Deployments, server diagnosis, automation |
| planner | planning | Project breakdown with dependencies and priorities |

## Agent Format

Each agent is a markdown file with YAML frontmatter:

```yaml
---
name: my-agent
description: What this agent does
version: 1.0.0
category: development
tools:
  - bash
  - browser
skills: []
---

# Agent Name

## Role
...

## Process
...
```

## Using Agents

In CopperRiver, type `#` in the chat input to browse and select agents. You can also manage agents from the Agents screen.
