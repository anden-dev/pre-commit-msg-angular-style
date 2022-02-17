# pre-commit-msg-angular-style

pre-commit hook to check commit messages for angular commit style

Requirements
------------
  pre-commit-shell requires the following to run:

  * [pre-commit](http://pre-commit.com)
    

Install
---------

1. create .pre-commit-config.yaml in you git project
2. pre-commit install --hook-type commit-msg 
3. enjoy it

example .pre-commit-config.yaml as following:

```yaml
---
repos:
- repo: https://github.com/anden-dev/pre-commit-msg-angular-style.git
  rev: v1.0.0
  hooks:
  - id: commitmessage
    stages: [commit-msg]
```
