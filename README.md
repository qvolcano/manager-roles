# 角色卡（公开只读）

BOT 流程的角色身份卡，从私有仓库 `qvolcano/manager` 的 `roles/` 同步而来。
公开是为了让 bot 用一个普通 HTTP GET 就能读到自己的身份文档，不需要 token。

文件与 URL：

| 角色 | 文件 | raw URL |
|---|---|---|
| 调度者 | 调度者.md | `https://raw.githubusercontent.com/qvolcano/manager-roles/main/调度者.md` |

其余角色同理，中文文件名原样保留（浏览器/HTTP 会自动 URL 编码）。

> 源在 `qvolcano/manager/roles/`。那边改了角色卡，记得同步到这里。
