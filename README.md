# ai_commit

## .pre-commit-config.yaml example
```yaml
  - repo: https://github.com/sidbaskaran/ai_commit
    rev: main
    hooks:
      - id: ai-commit
        name: ai-commit
        entry: ai-commit
        language: python
        stages: [commit-msg]
```

Generate commit messages with LLM.
