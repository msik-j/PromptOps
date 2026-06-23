# PromptOps
AI 프롬프트를 위한 Git
프롬프트를 코드처럼 버전 관리하고, 성능을 추적하며, A/B 테스트를 수행할 수 있는 오픈소스 플랫폼

# PromptOps

GitOps for AI Prompts.

PromptOps is an open-source platform that helps AI teams version, evaluate, compare, and manage prompts like code.

As AI applications grow, prompts become critical assets. However, prompt changes are often undocumented, difficult to compare, and nearly impossible to reproduce.

PromptOps provides version control, experiment tracking, prompt diffing, A/B testing, evaluation workflows, and cost monitoring for prompt-driven applications.

## Features

* Prompt Version Control
* Prompt Diff Viewer
* Experiment Tracking
* Automated Evaluations
* A/B Testing
* Cost Monitoring
* Rollback Support
* Team Collaboration

## Example

Create a prompt:

```bash
promptops create customer-support
```

Commit a change:

```bash
promptops commit
```

Compare versions:

```bash
promptops diff v2 v5
```

Run evaluation:

```bash
promptops evaluate
```

Rollback:

```bash
promptops rollback v3
```
