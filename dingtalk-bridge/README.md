# DingTalk Bridge

DingTalk group chat bridge for Claude Code.

**Full repository:** https://github.com/mguozhen/dingtalk-bridge

## What it does

- Send rich Markdown or plain text messages to DingTalk groups via OpenAPI
- 24/7 Stream bot: receive @mentions, auto-execute via `claude -p`, reply with results
- 20s WebSocket keepalive, crash recovery with exponential backoff
- Zero hardcoded secrets, one-command install
- 27 regression tests

## Install

```bash
git clone https://github.com/mguozhen/dingtalk-bridge.git ~/.claude/skills/dingtalk-bridge
bash ~/.claude/skills/dingtalk-bridge/scripts/install.sh
```

## Requirements

- Python 3.9+
- DingTalk Enterprise App (Stream mode enabled)
- `dingtalk_stream` + `websockets` Python packages

## License

MIT
