## Bot-hosting 自动续期

| Secret 名称 | 是否必填 | 说明 |
|---|---|---|
| `DISCORD_TOKEN` | 必填 | Discord Token |
| `SINGBOX_NODE` | 必填 | sing-box 节点链接，支持 `anytls://`、`hy2://`、`hysteria2://` |
| `SESSION_TOKEN` | 可选 | Bot-hosting `session_token` |
| `EMAIL` | 可选 | 通知邮箱 |
| `GH_TOKEN` | 可选 | 用于自动更新 `SESSION_TOKEN` 的 GitHub Token |
| `NODE_LINK` | 可选 | 旧代理 Secret 名称；未配置 `SINGBOX_NODE` 时使用 |
| `TG_BOT_TOKEN` | 可选 | Telegram Bot Token |
| `TG_CHAT_ID` | 可选 | Telegram Chat ID |
