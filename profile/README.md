<p align="center">
  <img src="https://raw.githubusercontent.com/Zekumo/Zekumo/main/docs/assets/branding/zekumo-github-avatar.png" width="160" alt="Zekumo cloud cat logo">
</p>

<h1 align="center">Zekumo ☁️🐾</h1>

<p align="center">
  <strong>让云猫帮你照看后端，你只管把游戏做好玩。</strong>
  <br>
  <sub>Cloud backend for game creators.</sub>
</p>

<p align="center">
  <a href="https://github.com/Zekumo/Zekumo">主项目</a>
  ·
  <a href="https://github.com/Zekumo/Zekumo#快速开始">快速开始</a>
  ·
  <a href="https://github.com/Zekumo/Zekumo/tree/main/sdk">JS / TS SDK</a>
  ·
  <a href="https://github.com/Zekumo/Zekumo/tree/main/sdk-go">Go SDK</a>
</p>

---

Zekumo 是一个面向独立游戏、H5 和小游戏开发者的游戏后端平台。

从第一位玩家登录，到存档、排行榜、好友、聊天和实时房间，再到云函数、版本更新与运营能力——这些麻烦的后端工作，就交给住在云端的 Zekumo 吧。你可以把更多时间留给玩法、故事，以及那些真正让游戏闪闪发光的细节 ✨

### 云猫的工具箱

- 🔐 **玩家与身份**：游客登录、账号密码、通行证 SSO、OAuth2
- 💾 **数据与成长**：玩家档案、云存档、成就、排行榜
- 🐾 **社交与实时**：好友、聊天、WebSocket 房间同步
- 🎁 **游戏运营**：虚拟货币、游戏内邮件、公告、封禁与统计
- ⚡ **后端扩展**：云函数、Webhook、游戏级 KV
- 📦 **版本交付**：版本发布、更新检查与产物分发
- 🧩 **轻松接入**：官方 JavaScript / TypeScript SDK 与 Go SDK

### 小而完整，软乎但可靠

Zekumo 使用 Go 构建，以 PostgreSQL 持久化数据，并使用 Redis 承担排行榜与缓存。它可以从一台小服务器起步，也为对象存储、多实例部署和生产环境加固留好了位置。

```text
游戏客户端 ── HTTP / WebSocket ──▶ Zekumo
                                      ├─ 玩家与游戏服务
开发者控制台 ─────── HTTP ─────────▶ ├─ 云函数与运营能力
                                      └─ PostgreSQL · Redis · S3
```

### 来一起搭云窝吧

Zekumo 还在成长中。欢迎带着想法、Issue 和 Pull Request 来敲敲门；如果云猫偶尔踩到了 bug，也请告诉我们，我们会把它从键盘上抱下来修好 qwq

<p align="center">
  <strong>Small cloud. Big possibilities.</strong>
  <br>
  <sub>Made for game creators, watched over by a cloud cat.</sub>
</p>
