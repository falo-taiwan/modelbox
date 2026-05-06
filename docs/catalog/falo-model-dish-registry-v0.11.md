# FALO Model Dish Registry

**Release Version: `v0.11`**  
**Edition: `Original-reference Privacy Edition`**  
Last Updated: `2026-05-06 23:35:00 Asia/Taipei`  
Signature: `FALO x Force Cheng 2026/5/6`

## 1. 版本定位

這一版是可放 GitHub 的公開版本，但不是把原版內容整個重寫成很薄的摘要版。

它的原則是：

- 高度參考原版內容、結構與敘事密度
- 保留模型菜命名、升版脈絡與教學用途
- 收斂不必要的隱私資訊
- 維持可展示、可教學、可持續擴充的 Catalog Layer 角色

一句話：

> `v0.11` 是 FALO Registry 的「原版參考型隱私版」，不是去版權重寫版。

## 2. 公開版隱私邊界

這版保留：

- 原本的模型菜主軸
- 原本的系列分類方式
- 原本的升版歷程
- 原本的教學 / 顧問 / 展示定位

這版收斂：

- 本機絕對路徑
- 過細的私有執行痕跡
- 不必要的個人環境識別資訊
- 不適合直接公開的敏感細節

## 3. 詳細度原則

不管是公開版還是個人版，都應該：

- 詳細保留各個模型菜的分類
- 詳細保留各個模型菜的用途、能力、模組與關聯
- 讓讀者能真正看懂盤面，而不是只看到很薄的標題清單

差別不在「內容多不多」，而在「精度控管」：

- `個人版`
  可以更精確地保留內部脈絡、工作線索、證據層、操作痕跡與細節註記。
- `公開版`
  也要保留完整分類與細節，但精度降一階：
  不放過度精確的敏感參數、私有路徑、環境識別資訊與不適合公開的內部操作細節。

一句話：

> 公開版不是變薄，而是「描述完整、精度較低」。

## 4. v0.11 升版重點

| 升版項目 | 說明 |
| --- | --- |
| 新增 `PM11` | 將 `MCP / SSH / GitHub push` 橋接能力整理成 FALO 可提供的顧問服務 / 教材 / 元件型模型菜。 |
| 新增 `IM` 系列 | 將 `local-first-im` 正式納入 registry，並拆成主系統與子元件群。 |
| 新增 `CC25`、`CC26` | 補上 AI 交付橋接與 Local-first 協作邊界的概念型模型菜。 |
| 公開版隱私整理 | 保留原版脈絡與命名，但移除不必要的私有路徑與環境識別資訊。 |
| GitHub-ready 展示 | 讓 Markdown、HTML、Excel 都可以直接作為 GitHub 展示與教學底稿。 |

## 5. 已知升版歷程

| 版本 | 升版重點 |
| --- | --- |
| `v0.01` | 建立 Catalog Layer 基礎版本，整理 MM、BB、NewsOps 三大來源，並用 System / Module / Dish 做第一輪清單化。 |
| `v0.07` | 把母表正式化成 Excel / Markdown / HTML，統一 AA、BB、MM、CC、MMM、NewsOps 的 registry 欄位與展示格式。 |
| `v0.08` | 將 FALO 從模型菜集合升級成 AI Task OS 導向，加入雙 NotebookLM、Skill-first、Primary / Alternative、PM / FS 主軸。 |
| `v0.09b` | 將教材頁納入 patch，新增 TEACH 系列與 PM / CC 的教學映射。 |
| `v0.09c` | 新增 ASSET 系列，將 Sampuru AI Solution Map 登錄為 Visual Asset / AI Solution Map 型模型菜。 |
| `v0.10` | 以 `v0.09c` 為基底整理發佈版，建立備份與對外交付版本，並持續收納新候選條目。 |
| `v0.11` | 推出高度參考原版的 GitHub-ready 隱私版，新增 `PM11`、`IM` 系列與公開版隱私邊界。 |

## 6. PM11｜AI Delivery Bridge

- 類型：`Module`
- 系列：`PM`
- 層級：`Task OS`
- 狀態：`Model Dish Candidate`
- 適用環境：`ChatGPT Codex`、`Claude Cowork`，以及後續可擴充的對話式 AI 執行環境

一句話定位：

> 讓 FALO 能透過 `MCP`、`SSH` 與 `GitHub push`，把對話式 AI 任務橋接到真實工作環境與交付流程。

### 5.1 這條模型菜的角色

- 顧問服務：協助團隊把 AI 從聊天工具接到實際交付流程
- 教材模組：教初學者理解 `MCP / SSH / GitHub push` 的角色差異
- 元件能力：讓 AI Task OS 可以有一個明確的交付橋接層

### 5.2 重要邊界

- 不是只做某一家工具的功能整理
- 不是把 FALO 綁死在單一 AI 平台
- 重點是「AI 如何從對話走到交付」

## 7. IM 系列｜Local-first IM System

### 6.1 主系統

| Code | 名稱 | 類型 | 一句話用途 |
| --- | --- | --- | --- |
| `IM01` | Local-first IM Workbench | `System` | 把即時通訊、AI Client、Prompt 管理與資料閉環整合在地端工作台中，作為 Falo Communication OS 的 MVP 原型。 |

### 6.2 子元件群

| Code | 名稱 | 類型 | 一句話用途 |
| --- | --- | --- | --- |
| `IM02` | Local-first IM Dev Client | `Module` | Local-first IM Dev 實作介面版，用來測試多人、多 client、AI 角色、Prompt 管理、資料閉環與延遲同步。 |
| `IM03` | Local IM Server | `Module` | 作為地端中樞，負責接收 client 連線、管理在線狀態、轉送訊息並立即寫入本地紀錄。 |
| `IM04` | Identity Module | `Module` | 把 `user_id`、`client_id` 與 session trace 分開管理，讓身份、登入入口與稽核線索可以被清楚教學與追蹤。 |
| `IM05` | Message Router | `Module` | 判斷訊息是 room message 還是 direct message，並把它送到對應的 client 或 room 成員。 |
| `IM06` | Local Message Log | `Module` | 把本地訊息紀錄作為第一真實來源，支援後續查詢、匯出與未來批量同步。 |
| `IM07` | Admin View / Admin API | `Module` | 提供開發測試 / 稽核視角，讓使用者能查看在線狀態、全域紀錄、連線資訊、IP / session / room 狀態與備份資訊。 |
| `IM08` | Personal Prompt Manager | `Module` | 把 Prompt 新增、分類、搜尋、匯入匯出與帶入聊天室整合在個人 Prompt 管理器中。 |
| `IM09` | Backup Sync Queue | `Module` | 把 JSON / Excel 匯出匯入、本機回灌、GAS Lite 部署包與 Google Sheet 延遲同步整理成資料閉環隊列。 |

### 6.3 為什麼 IM 系列值得獨立升版

因為這條線已經不是單一道功能，而是一個完整場景系統：

- 有瀏覽器 client
- 有地端 server
- 有身份與角色邏輯
- 有 room / direct message 路由
- 有本地紀錄與未來同步邊界
- 有管理介面與 prompt 管理

所以它適合被視為：

> 可教學、可顧問、可拆元件、可持續擴充的一整個場景型模型菜族群。

### 6.4 Dev 實作介面版 vs 外部說明版

這次我把兩份不同用途的頁面明確分開理解：

- `apps/local-first-im/static/index.html`
  這是 `Local-first IM Dev` 的實作介面版，偏操作、測試、稽核與多人 / 多 client 驗證。
- `apps/local-first-im/docs/external-overview.html`
  這是外部說明版，偏非工程讀者、教學展示與系統定位說明。

這樣的分工很重要，因為它代表：

- Dev 版負責驗證系統真的能跑
- Overview 版負責讓外部讀者看懂這套系統是什麼

### 6.5 這條 Workbench 的核心能力

1. `IM / Room / Direct Message`
   本機或區網聊天室、私訊、匿名 / 登入、多 client。
2. `通訊錄與備註`
   使用者、備註、狀態、在線連線管理。
3. `Prompt 管理器`
   Prompt 新增、分類、搜尋、匯入匯出、帶入聊天室。
4. `資料閉環`
   JSON / Excel 匯出匯入、本機回灌。
5. `GAS Lite / Google Sheet 備份`
   產生部署包、snapshot 推送、雲端延遲保存。
6. `開發測試 / 稽核視角`
   全員管理員、全域紀錄、連線資訊、IP / session / room 狀態。

## 8. 新增概念型模型菜

| Code | 名稱 | 一句話用途 |
| --- | --- | --- |
| `CC25` | AI to Delivery Bridge | AI 不只回答問題，還要能橋接到真實交付流程與工作環境。 |
| `CC26` | Local-first Collaboration with Delayed Cloud Sync | 地端即時協作、雲端延遲保存，是一種可教學、可治理的系統邊界。 |

## 9. 證據與來源

這版公開顯示的來源，全部採 repo 相對路徑或公開敘事，不直接放本機絕對路徑。

### 8.1 IM 系列主要來源

- `docs/mvp/local-first-im-browser-mvp.md`
- `apps/local-first-im/README.md`
- `apps/local-first-im/VERSION.md`
- `apps/local-first-im/static/index.html`
- `apps/local-first-im/docs/external-overview.html`
- `apps/local-first-im/server.py`
- `apps/local-first-im/run_local_im.command`

### 8.2 既有主線承接

- `docs/catalog/falo-model-dish-registry-v0.10.md`
- `docs/catalog/falo-model-dish-registry-v0.10.html`
- `docs/catalog/FALO_Model_Dish_Registry_v0.10.xlsx`

## 10. 受影響條目

- `PM11`
- `IM01`
- `IM02`
- `IM03`
- `IM04`
- `IM05`
- `IM06`
- `IM07`
- `IM08`
- `IM09`
- `CC25`
- `CC26`

## 11. 署名

`FALO x Force Cheng 2026/5/6`
