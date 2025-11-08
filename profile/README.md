## Hi, Everyone ![](https://user-images.githubusercontent.com/18350557/176309783-0785949b-9127-417c-8b55-ab5a4333674e.gif)

Everything that happens here is my personal wish. Software makes it happen, but much is still unfinished, so let's see what still needs to be done:  
`ทุกอย่างที่เกิดขึ้นในที่นี้เป็นความอยากได้ส่วนตัวของผมล้วนๆ ซอฟต์แวร์หลายๆ ตัวก็เลยเกิดขึ้น แต่ก็ไม่เสร็จอีกเยอะเช่นกัน เพราะงั้นเรามาดูสิ่งที่ยังต้องทำต่อกัน`

# Todo (สิ่งที่ต้องทำ)

#### gokub-mcp (MCP Server for Bitkub Tools)
![last (main)](https://img.shields.io/github/last-commit/dvgamerr-app/gokub-mcp/main.svg?style=flat-square)
![status](https://img.shields.io/badge/version-internal_dev-yellow?style=flat-square)

- [x] Core MCP server built with Go  
- [x] Integrated with `go-bitkub` SDK  
- [x] Supports HTTP + SSE transport  
- [x] Implemented tools: `get_wallet_balance`, `get_ticker`, `get_market_depth`, `get_my_open_orders`, `get_symbols`  
- [ ] Add Docker/K8s deployment  
- [ ] Add WebSocket data stream  
- [ ] Implement trading bot framework  

📖 [MCP-Go Framework](https://github.com/modelcontextprotocol/spec)  
💎 [Go-Bitkub SDK](https://github.com/dvgamerr-app/go-bitkub)

---

#### go-bitkub (Go SDK สำหรับ Bitkub API)
![last (main)](https://img.shields.io/github/last-commit/dvgamerr-app/go-bitkub/main.svg?style=flat-square)
![release](https://img.shields.io/github/v/release/dvgamerr-app/go-bitkub?style=flat-square)

- [x] Released **v1.2.0** — Full Bitkub API V3/V4 coverage  
- [x] Added CLI (`bitkub`) built with Cobra + Zerolog  
- [x] Implemented WebSocket streams (`trade`, `ticker`, `orderbook`)  
- [x] Improved SDK structure and test coverage  
- [ ] Add gRPC and GraphQL layers  
- [ ] Implement auto-trading modules (momentum, grid, arbitrage)  

📦 [View Release v1.2.0](https://github.com/dvgamerr-app/go-bitkub/releases/tag/v1.2.0)

---

#### go-hoyolab (Hoyolab Daily Check-in Automation)
![last (main)](https://img.shields.io/github/last-commit/dvgamerr-app/go-hoyolab/main.svg?style=flat-square)
![release](https://img.shields.io/github/v/release/dvgamerr-app/go-hoyolab?style=flat-square)

- [x] Released **v1.4** — Supports Genshin Impact, Honkai StarRail, Honkai Impact 3  
- [x] Auto check-in using Chrome profiles  
- [x] Supports LINE Notify & Discord Notify  
- [x] Multi-account & cross-platform (Windows/macOS/Linux)  
- [ ] Add Zenless Zone Zero support  
- [ ] Add Docker container version  
- [ ] Add cross-browser session support  
- [ ] Add Windows scheduled task installer  

📦 [View Release v1.4](https://github.com/dvgamerr-app/go-hoyolab/releases/tag/hoyolab-v1.4)

---

#### hentai-downloader (โปรแกรมดาวน์โหลดมังงะจากเว็บ e-hentai/exhentai)
![last (main)](https://img.shields.io/github/last-commit/dvgamerr-app/hentai-downloader/main.svg?style=flat-square)
![release](https://img.shields.io/github/v/release/dvgamerr-app/hentai-downloader?style=flat-square)

- [x] Released **v2.2.1** — Electron-based Manga Downloader  
- [x] Supports **e-hentai.org** & **exhentai.org**  
- [x] Clipboard auto-detection and queue management  
- [x] Fixes corrupted images via re-download  
- [x] Persistent queue saving  
- [x] Cross-platform (Windows/Mac/Linux)  
- [ ] Refactor UI with new Electron engine  
- [ ] Add parallel download feature with throttling  
- [ ] Add Docker build and CLI mode  

📦 [View Release v2.2.1](https://github.com/dvgamerr-app/hentai-downloader/releases/tag/v2.2.1)

---

# Contribution guidelines (อยากช่วยเหรอ ได้เลย)
1. Fork the project.  
2. Start coding.  
3. Create a pull request and describe your changes clearly.  

# Useful resources
- If you want help, you can join Discord  

[![Join Us?](https://discordapp.com/api/guilds/475720106471849996/widget.png?style=banner2)](https://discord.gg/QDccF497Mw)
