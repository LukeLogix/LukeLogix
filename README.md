# 李英杰 (Luke) — Backend Engineer

**資深後端工程師 · Go / Golang · 微服務・即時通訊・可靠訊息投遞 · 僅遠端**

近 10 年後端開發經驗,近 3 年以 Go 為主力。能獨立把系統從設計、實作、上線到監控維運**一人交付到生產**。近期以 AI 輔助從 0 打造並營運一套多租戶事件總線平台。

📮 benedict.lh@gmail.com　·　🌏 台灣・桃園　·　🟢 Open to remote roles
🌐 個人站建置中 · alderflux.com

---

## 🚩 旗艦作品 — MsgMesh（已上線 · public beta）

**多租戶事件總線平台**：把 Kafka 收斂在閘道之後,對外只提供 HTTP / SSE / WebSocket / MCP,讓應用與 AI agent「一句話接入」事件流;鑑權、限流、多租戶隔離全由平台收斂。Go monorepo 模組化單體,單一 binary 部署、同時保留 6 個服務邊界。

- **可靠投遞**：webhook HMAC + 重試 + 死信佇列（DLQ）+ replay,達成 at-least-once
- **即時 + 分散式狀態**：SSE / WebSocket live-tail;跨副本 presence（Redis ZSET 心跳,fail-open 回退）
- **為 k8s 水平擴充而生**：無狀態服務 + etcd 設定 + 冪等 migration（多 pod 同啟安全）
- **工程紀律**：TDD + 契約防漂移測試（實際路由 ↔ OpenAPI）+ 合併前 code-review gate

🔗 產品站 <https://msgmesh.alderflux.com>　·　即時 Demo（免註冊） <https://msgmesh-demo.alderflux.com>

`Go` · `Kafka` · `PostgreSQL` · `Redis` · `etcd` · `SSE/WebSocket` · `MCP` · `Helm/K8s` · `Prometheus`

---

## 🛠 其他開源

| Repo | 說明 |
|------|------|
| [etcd-admin](https://github.com/LukeLogix/etcd-admin) | Vue 3 + Go 的 etcd 管理平台（JSON tree 預覽、資料備份） |
| [android-display](https://github.com/LukeLogix/android-display) | 把 Android 平板當 macOS 無線延伸螢幕（Go,含觸控） |
| [msgmesh-examples](https://github.com/LukeLogix/msgmesh-examples) | 用 `@msgmesh/sdk` 的即時聊天室範例 |

---

## ⚙️ 技術

| | |
|---|---|
| **語言** | Go · PHP |
| **後端 / 通訊** | gRPC · GraphQL · REST · 微服務 · Kafka · EMQX |
| **資料儲存** | PostgreSQL · MySQL · TiDB · Redis · MongoDB · Elasticsearch · etcd |
| **平台 / 維運** | Kubernetes · Docker · Proxmox/PVE · Nginx · APISIX · Prometheus · GitLab CI/CD · Jenkins |
| **AI 輔助開發** | Claude Code · MCP · OpenAI API · AIOps / DevEx |

---

<sub>近 10 年後端 · Go 主力 · 能一個人把系統帶到生產 · 開放遠端職缺 → benedict.lh@gmail.com</sub>
