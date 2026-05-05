# Codex Karpathy Coding Guidelines Skill Installer

一键安装 `karpathy-coding-guidelines` Codex skill。

## Install

```bash
curl -fsSL https://raw.githubusercontent.com/<owner>/<repo>/main/install-karpathy-coding-guidelines.sh | sh
```

## Optional env vars

- `CODEX_HOME=/path/to/.codex`
- `SKILL_DIR=/custom/path/karpathy-coding-guidelines`
- `FORCE=1` 覆盖已有安装

## Install location

默认安装到：

```text
${CODEX_HOME:-$HOME/.codex}/skills/karpathy-coding-guidelines
```
