# FALO Model Dish Registry

**Release Version: `v0.11`**  
**Edition: `公開可讀的詳細版`**  
Last Updated: `2026-05-06 23:12:12 Asia/Taipei`  
Signature: `FALO x Force Cheng 2026/5/6`

## 1. 版本定位

這一版是可放 GitHub 的公開版本，但不是把原版內容整個重寫成很薄的摘要版。

它的原則是：

- 高度參考原版內容、結構與敘事密度
- 保留模型菜命名、升版脈絡與教學用途
- 收斂不必要的隱私資訊
- 維持可展示、可教學、可持續擴充的 Catalog Layer 角色

一句話：

> `v0.11` 是 FALO Registry 的「公開可讀的詳細版」，不是去版權重寫版。

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
| `v0.11` | 推出高度參考原版的 GitHub-ready 公開可讀詳細版，新增 `PM11`、`IM` 系列與公開版精度邊界。 |

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

## 11. 完整分類與明細列表

這一節不是升版摘要，而是把目前 `v0.11` 已知模型菜盤面，按系列完整展開。公開版也盡量保留分類、模組、能力、用途與註記；差別只在精度，不在內容厚度。

### 11.1 系列總覽

| 系列 | 條目數 | 說明 |
| --- | ---: | --- |
| `AA` | 12 | 作為模型菜總目錄的頂層樓層分類，幫助讀者先看懂盤面，再進入具體模型菜。 |
| `BB` | 13 | 偏顧問與教學展示的實戰模型菜，可直接對應方案、課程與導入情境。 |
| `MM` | 60 | 目前已成形、已命名、可教學、可產品化的既有核心模型菜資產。 |
| `CC` | 26 | 概念、洞見、設計原則與模式類模型菜，負責承接教學與方法論。 |
| `MMM` | 7 | 多模態、影音、Local AI 與前沿能力線，偏應用能力與實驗軌。 |
| `PM` | 7 | FALO 作為 AI Task OS 的主軸系列，承接任務系統、決策與交付橋接。 |
| `FS` | 0 | Ground Truth 與 Evidence Layer 的保留區，目前欄位已預留，但本版尚未展開具名條目。 |
| `TEACH` | 3 | 從教材、案例、教學頁映射出的模型菜，負責把概念轉成可教內容。 |
| `ASSET` | 1 | 展示型、視覺型、語意導航型模型菜資產，偏 showcase 與入口價值。 |
| `TRACE` | 0 | AI 學習履歷與 GitHub / Pages 資產治理保留區，本版欄位已規劃，後續再補實體條目。 |
| `NewsOps` | 18 | 專案型系統族群，涵蓋 ETL、監測、編修、輸出與審核的整條運作鏈。 |
| `IM` | 9 | Local-first IM 與協作工作台系統，承接 communication OS、prompt 管理與資料閉環。 |

### 11.2 AA 系列｜Catalog Floors / Department Categories

作為模型菜總目錄的頂層樓層分類，幫助讀者先看懂盤面，再進入具體模型菜。


| Code | 名稱 | 類型 | 層級 / 家族 | 一句話用途 | 備註 | 狀態 |
| --- | --- | --- | --- | --- | --- | --- |
| AA01 | 知識收集與整理 | Category | Catalog | 收集資料、筆記、來源、附件與初步整理 | 頂層 catalog 分類，用來整理盤面，不直接代表單一實作系統。 | Working Draft |
| AA02 | 知識庫與檢索 | Category | Catalog | 知識庫、FAQ、RAG、文件查找與檢索 | 頂層 catalog 分類，用來整理盤面，不直接代表單一實作系統。 | Working Draft |
| AA03 | Prompt 與 AI 操作輔助 | Category | Catalog | Prompt、AI 操作殼、指令與互動入口 | 頂層 catalog 分類，用來整理盤面，不直接代表單一實作系統。 | Working Draft |
| AA04 | 文件生成與寫作 | Category | Catalog | 企畫書、報告、SOP、改稿與輸出 | 頂層 catalog 分類，用來整理盤面，不直接代表單一實作系統。 | Working Draft |
| AA05 | 教學訓練與新人帶領 | Category | Catalog | onboarding、教材、主管帶員 | 頂層 catalog 分類，用來整理盤面，不直接代表單一實作系統。 | Working Draft |
| AA06 | 專案管理與協作 | Category | Catalog | 任務、專案、協作、排程 | 頂層 catalog 分類，用來整理盤面，不直接代表單一實作系統。 | Working Draft |
| AA07 | 行政營運效率 | Category | Catalog | 日常效率、行政回覆、整理 | 頂層 catalog 分類，用來整理盤面，不直接代表單一實作系統。 | Working Draft |
| AA08 | 業務行銷與對外溝通 | Category | Catalog | 對外提案、簡報、行銷文案 | 頂層 catalog 分類，用來整理盤面，不直接代表單一實作系統。 | Working Draft |
| AA09 | 治理、稽核與紀錄 | Category | Catalog | 治理、稽核、留痕、權限與追蹤 | 頂層 catalog 分類，用來整理盤面，不直接代表單一實作系統。 | Working Draft |
| AA10 | 資料保護與去識別化 | Category | Catalog | 加解密、去識別化、交換保護 | 頂層 catalog 分類，用來整理盤面，不直接代表單一實作系統。 | Working Draft |
| AA11 | AI Agent / 自動化工作流 | Category | Catalog | Agent、工作流、自動化與 orchestration | 頂層 catalog 分類，用來整理盤面，不直接代表單一實作系統。 | Working Draft |
| AA12 | 個人工作台與一人公司 | Category | Catalog | 個人知識助手、顧問工作台、一人公司 | 頂層 catalog 分類，用來整理盤面，不直接代表單一實作系統。 | Working Draft |

### 11.3 BB 系列｜Consulting / Teaching Use Cases

偏顧問與教學展示的實戰模型菜，可直接對應方案、課程與導入情境。


| Code | 名稱 | 類型 | 層級 / 家族 | 一句話用途 | 備註 | 狀態 |
| --- | --- | --- | --- | --- | --- | --- |
| BB01 | 公司知識庫建立（KM） | System | Execution | 企業知識庫建立與累積 | 偏教學與顧問展示，適合直接轉成方案、課程與對外說明。 | Working Draft |
| BB02 | 投標企畫加速（ETL） | System | Execution | 投標文件與提案內容加速生成 | 偏教學與顧問展示，適合直接轉成方案、課程與對外說明。 | Working Draft |
| BB03 | 新人快速上手（Onboarding） | System | Execution | 新進人員學習與上手系統 | 偏教學與顧問展示，適合直接轉成方案、課程與對外說明。 | Working Draft |
| BB04 | 主管帶員減壓（管理） | System | Execution | 減輕主管反覆帶員負擔 | 偏教學與顧問展示，適合直接轉成方案、課程與對外說明。 | Working Draft |
| BB05 | 員工效率提升（日常） | System | Execution | 用 AI 提升日常工作效率 | 偏教學與顧問展示，適合直接轉成方案、課程與對外說明。 | Working Draft |
| BB06 | 專案問題解決（AI 陪跑） | System | Execution | 專案問題拆解與 AI 陪跑 | 偏教學與顧問展示，適合直接轉成方案、課程與對外說明。 | Working Draft |
| BB07 | 結案報告生成（ETL） | System | Execution | 專案結案報告生成 | 偏教學與顧問展示，適合直接轉成方案、課程與對外說明。 | Working Draft |
| BB08 | Source Inbox（資料收件匣） | Module | Execution | 外部資料與輸入內容收件匣 | 偏教學與顧問展示，適合直接轉成方案、課程與對外說明。 | Working Draft |
| BB09 | Prompt Manager | Module | Execution | 教學與顧問場景的 Prompt 資產管理 | 偏教學與顧問展示，適合直接轉成方案、課程與對外說明。 | Working Draft |
| BB10 | KM Lite | Module | Execution | 輕量知識管理能力 | 偏教學與顧問展示，適合直接轉成方案、課程與對外說明。 | Working Draft |
| BB11 | Logging Shell | Module | Execution | 操作流程記錄與追蹤 | 偏教學與顧問展示，適合直接轉成方案、課程與對外說明。 | Working Draft |
| BB12 | 輸出引擎 | Module | Execution | 輸出文件、報告與交付成果 | 偏教學與顧問展示，適合直接轉成方案、課程與對外說明。 | Working Draft |
| BB13 | Cloud Calendar PM | System | Execution | 以 Google Calendar 為核心的輕量雲 PM 中樞 | 偏教學與顧問展示，適合直接轉成方案、課程與對外說明。 | Working Draft |

### 11.4 MM 系列｜Core Named Model Dishes

目前已成形、已命名、可教學、可產品化的既有核心模型菜資產。


| Code | 名稱 | 類型 | 層級 / 家族 | 一句話用途 | 備註 | 狀態 |
| --- | --- | --- | --- | --- | --- | --- |
| MM01 | 新聞探索與知識流動系統 | System | Execution | 整理新聞蒐集、理解與知識流動的完整系統 | 既有資產主幹，後續可延伸為產品、教材與 ModelBox 條目。 | Working Draft |
| MM02 | AI 操作殼（Logging Shell） | Module | Execution | AI 操作過程的記錄、追蹤與操作介面 | 既有資產主幹，後續可延伸為產品、教材與 ModelBox 條目。 | Working Draft |
| MM03 | Local Data Hub | Module | Execution | 本地資料管理中心／資料底盤 | 既有資產主幹，後續可延伸為產品、教材與 ModelBox 條目。 | Working Draft |
| MM04 | Google AI Search Logging | Dish | Execution | 記錄 Google AI Search 查詢與結果 | 既有資產主幹，後續可延伸為產品、教材與 ModelBox 條目。 | Working Draft |
| MM05 | 雲指令小幫手（Cloud Prompt Assistant） | Dish | Execution | 快速調用與管理雲端提示詞或指令 | 既有資產主幹，後續可延伸為產品、教材與 ModelBox 條目。 | Working Draft |
| MM06 | Prompt 管理器（Prompt Asset Manager） | Module | Execution | Prompt 資產整理、重用與教學化 | 既有資產主幹，後續可延伸為產品、教材與 ModelBox 條目。 本版補充：若延伸為 Prompt Workbench，定位應視為 Module，負責 Task → Prompt 的編譯，而非核心系統。 | Working Draft |
| MM07 | Source Inbox | Module | Execution | 外部來源資料入口 | 既有資產主幹，後續可延伸為產品、教材與 ModelBox 條目。 | Working Draft |
| MM08 | Smart KM Core | System | Execution | 知識管理核心系統 | 既有資產主幹，後續可延伸為產品、教材與 ModelBox 條目。 | Working Draft |
| MM09 | Local RAG Lite | Module | Execution | 輕量版本地 RAG 能力 | 既有資產主幹，後續可延伸為產品、教材與 ModelBox 條目。 | Working Draft |
| MM10 | Trusted Session Governance | Module | Execution | AI session 的可信邊界與使用規則 | 既有資產主幹，後續可延伸為產品、教材與 ModelBox 條目。 | Working Draft |
| MM11 | Query Governance | Dish | Execution | 查詢行為與檢索規範管理 | 既有資產主幹，後續可延伸為產品、教材與 ModelBox 條目。 | Working Draft |
| MM12 | AI 對話紀錄與治理系統 | System | Execution | 對話內容記錄、追蹤、稽核與教學 | 既有資產主幹，後續可延伸為產品、教材與 ModelBox 條目。 | Working Draft |
| MM13 | Sidebar Logging Shell | Module | Execution | 側邊欄形式的操作殼 | 既有資產主幹，後續可延伸為產品、教材與 ModelBox 條目。 | Working Draft |
| MM14 | 去識別化 / 加解密系統 | System | Execution | 資料去識別化與加解密保護 | 既有資產主幹，後續可延伸為產品、教材與 ModelBox 條目。 | Working Draft |
| MM15 | AI Usage Governance | System | Execution | AI 使用方式、風險與治理規則 | 既有資產主幹，後續可延伸為產品、教材與 ModelBox 條目。 | Working Draft |
| MM16 | Information Collection Center | System | Execution | 資訊搜集中樞 | 既有資產主幹，後續可延伸為產品、教材與 ModelBox 條目。 | Working Draft |
| MM17 | NewsOps System | System | Execution | 新聞 ETL + Scheduler + Monitor 聯合作戰系統 | 既有資產主幹，後續可延伸為產品、教材與 ModelBox 條目。 | Working Draft |
| MM18 | Crawler Center | Module | Execution | 抓取外部新聞或資訊來源 | 既有資產主幹，後續可延伸為產品、教材與 ModelBox 條目。 | Working Draft |
| MM19 | Scheduler Center | Module | Execution | 排程與任務執行時機管理 | 既有資產主幹，後續可延伸為產品、教材與 ModelBox 條目。 | Working Draft |
| MM20 | Monitor Center | Module | Execution | 監控系統狀態、流程與異常 | 既有資產主幹，後續可延伸為產品、教材與 ModelBox 條目。 | Working Draft |
| MM21 | Crawler Result Center（CRC） | Module | Execution | 集中管理爬取結果 | 既有資產主幹，後續可延伸為產品、教材與 ModelBox 條目。 | Working Draft |
| MM22 | Intake Layer | Module | Execution | 原始輸入資料的接收與分流 | 既有資產主幹，後續可延伸為產品、教材與 ModelBox 條目。 | Working Draft |
| MM23 | Translation Layer | Dish | Execution | 翻譯內容 | 既有資產主幹，後續可延伸為產品、教材與 ModelBox 條目。 | Working Draft |
| MM24 | Summarization Layer | Dish | Execution | 內容摘要 | 既有資產主幹，後續可延伸為產品、教材與 ModelBox 條目。 | Working Draft |
| MM25 | Rewrite Layer | Dish | Execution | 改寫內容 | 既有資產主幹，後續可延伸為產品、教材與 ModelBox 條目。 | Working Draft |
| MM26 | Proposal / Rollback Layer | Dish | Execution | 提案與回退能力 | 既有資產主幹，後續可延伸為產品、教材與 ModelBox 條目。 | Working Draft |
| MM27 | Duplicate Detection Layer | Dish | Execution | 重複內容檢查 | 既有資產主幹，後續可延伸為產品、教材與 ModelBox 條目。 | Working Draft |
| MM28 | Queue / Processing View Layer | Dish | Execution | 任務排隊與處理狀態視圖 | 既有資產主幹，後續可延伸為產品、教材與 ModelBox 條目。 | Working Draft |
| MM29 | Export Layer | Dish | Execution | 結果輸出 | 既有資產主幹，後續可延伸為產品、教材與 ModelBox 條目。 | Working Draft |
| MM30 | Delivery Layer | Dish | Execution | 將內容送往目標端 | 既有資產主幹，後續可延伸為產品、教材與 ModelBox 條目。 | Working Draft |
| MM31 | Action Log / Audit Layer | Dish | Execution | 操作與審核軌跡 | 既有資產主幹，後續可延伸為產品、教材與 ModelBox 條目。 | Working Draft |
| MM32 | Browser AI Workbench | System | Execution | 瀏覽器內 AI 前處理工作台 | 既有資產主幹，後續可延伸為產品、教材與 ModelBox 條目。 | Working Draft |
| MM33 | Content Extraction Engine | Module | Execution | DOM / 選取 / HTML / 圖片擷取 | 既有資產主幹，後續可延伸為產品、教材與 ModelBox 條目。 | Working Draft |
| MM34 | Task-first UI Engine | Module | Execution | 以任務卡為主入口的側邊 UI | 既有資產主幹，後續可延伸為產品、教材與 ModelBox 條目。 | Working Draft |
| MM35 | Built-in AI Adapter | Module | Execution | 內建 AI 優先、本地先、必要時升級雲端 | 既有資產主幹，後續可延伸為產品、教材與 ModelBox 條目。 | Working Draft |
| MM36 | KM Index Connector | Module | Execution | Source / Index / Card / Relation 連接 | 既有資產主幹，後續可延伸為產品、教材與 ModelBox 條目。 | Working Draft |
| MM37 | Workbench Buffer | Module | Execution | 人機協作的中間緩衝區 | 既有資產主幹，後續可延伸為產品、教材與 ModelBox 條目。 | Working Draft |
| MM38 | Structured Export Engine | Module | Execution | JSON / CSV / Markdown / HTML 匯出 | 既有資產主幹，後續可延伸為產品、教材與 ModelBox 條目。 | Working Draft |
| MM39 | Knowledge Card Generator | Dish | Execution | 知識卡生成 | 既有資產主幹，後續可延伸為產品、教材與 ModelBox 條目。 | Working Draft |
| MM40 | Metadata Extractor | Dish | Execution | metadata 與欄位抽取 | 既有資產主幹，後續可延伸為產品、教材與 ModelBox 條目。 | Working Draft |
| MM41 | Multi-mode Content Cleaner | Dish | Execution | 精確版 / 完整版內容清理 | 既有資產主幹，後續可延伸為產品、教材與 ModelBox 條目。 | Working Draft |
| MM42 | Image Selection & Export | Dish | Execution | 圖片擷取、勾選與輸出 | 既有資產主幹，後續可延伸為產品、教材與 ModelBox 條目。 | Working Draft |
| MM43 | LAN Secure Agent Mesh | System | Execution | 內部協作型 Agent Mesh 與操作中控 | 既有資產主幹，後續可延伸為產品、教材與 ModelBox 條目。 | Working Draft |
| MM44 | Extension Client Layer | Module | Execution | Chrome Extension 節點入口 | 既有資產主幹，後續可延伸為產品、教材與 ModelBox 條目。 | Working Draft |
| MM45 | Task Router Hub | Module | Execution | 中央任務分派與資料整流 | 既有資產主幹，後續可延伸為產品、教材與 ModelBox 條目。 | Working Draft |
| MM46 | Agent Logging & Audit Hub | Module | Execution | 集中 log、audit、trace | 既有資產主幹，後續可延伸為產品、教材與 ModelBox 條目。 | Working Draft |
| MM47 | Trust Mode / Secure Channel Layer | Module | Execution | 一般/保護/管制模式與輕量安全 | 既有資產主幹，後續可延伸為產品、教材與 ModelBox 條目。 | Working Draft |
| MM48 | Prompt Governance Module | Module | Execution | Prompt 治理與權限 | 既有資產主幹，後續可延伸為產品、教材與 ModelBox 條目。 | Working Draft |
| MM49 | Knowledge Package Exchange Module | Module | Execution | zip + 密碼的模組／知識包交換 | 既有資產主幹，後續可延伸為產品、教材與 ModelBox 條目。 | Working Draft |
| MM50 | Task Routing Capability | Dish | Execution | 任務跨節點流動能力 | 既有資產主幹，後續可延伸為產品、教材與 ModelBox 條目。 | Working Draft |
| MM51 | Human-in-the-loop Confirmation | Dish | Execution | AI 先做、人確認 | 既有資產主幹，後續可延伸為產品、教材與 ModelBox 條目。 | Working Draft |
| MM52 | ZIP Package Delivery | Dish | Execution | 模組包／知識包／更新包交付 | 既有資產主幹，後續可延伸為產品、教材與 ModelBox 條目。 | Working Draft |
| MM53 | Lightweight Encryption / Encoding Mode | Dish | Execution | 輕量加密與編碼模式 | 既有資產主幹，後續可延伸為產品、教材與 ModelBox 條目。 | Working Draft |
| MM54 | LAN Node Discovery / Registration | Dish | Execution | 區網節點發現與註冊 | 既有資產主幹，後續可延伸為產品、教材與 ModelBox 條目。 | Working Draft |
| MM55 | AI Usage Traceability | Dish | Execution | AI 使用追蹤 | 既有資產主幹，後續可延伸為產品、教材與 ModelBox 條目。 | Working Draft |
| MM56 | Rule-based Action Decision | Dish | Execution | 規則式任務決策 | 既有資產主幹，後續可延伸為產品、教材與 ModelBox 條目。 | Working Draft |
| MM57 | Cross-device Task Handoff | Dish | Execution | 跨裝置任務交接 | 既有資產主幹，後續可延伸為產品、教材與 ModelBox 條目。 | Working Draft |
| MM65 | AI Auto Filing | Module | Execution | 把 Search 與內容判讀延伸成 AI 自動歸檔能力。 | 對應從手動整理升級為 Search -> AI 自動歸檔。 | Working Draft |
| MM68 | Knowledge Audio Export Engine | Module | Execution | 把知識內容轉成可發布、可教學的 Audio Asset。 | 把原本偏 TTS 功能，提升為 Knowledge -> Audio Asset 的輸出引擎。 | Working Draft |
| MM69 | HITL Markdown Memory System | System | Execution | 把 Markdown 升級為 AI 協作的外部記憶與檢核工作表：程式負責穩定拆解，AI / SLM 負責輔助檢查，人類負責最後確認。 | 不是單純 Markdown 文件產生器，也不是完整資料庫或全自動 AI 決策系統。核心是人可讀、程式可拆、AI 可輔助檢核的外部記憶工作系統。適合 SOP、狀態表、檢核表、工作紀錄、AI 協作交接資料。 | Candidate |

### 11.5 CC 系列｜Concept / Insight / Pattern / Principle

概念、洞見、設計原則與模式類模型菜，負責承接教學與方法論。


| Code | 名稱 | 類型 | 層級 / 家族 | 一句話用途 | 備註 | 狀態 |
| --- | --- | --- | --- | --- | --- | --- |
| CC01 | 架構分離 × 體驗整合 | Concept | Concept | 系統分層設計，但使用體驗可整合 | 屬於抽象概念型條目，可作為教學原則、設計視角與說明骨架。 | Working Draft |
| CC02 | Calendar-first | Concept | Concept | 任務最終落到時間管理 | 屬於抽象概念型條目，可作為教學原則、設計視角與說明骨架。 | Working Draft |
| CC03 | Generate → Refine | Pattern | Concept | 不同模型分工生成與收斂 | 屬於抽象概念型條目，可作為教學原則、設計視角與說明骨架。 | Working Draft |
| CC04 | AI Operation Layer | Concept | Concept | AI 工具與企業系統之間的操作層 | 屬於抽象概念型條目，可作為教學原則、設計視角與說明骨架。 | Working Draft |
| CC05 | Local AI × Cloud AI × Human 三層架構 | Concept | Concept | 本地、雲端、顧問 / 人的分工 | 屬於抽象概念型條目，可作為教學原則、設計視角與說明骨架。 | Working Draft |
| CC06 | ModelBox 是索引層，不是加工層 | Concept | Concept | ModelBox 偏索引與編目，不是重加工 | 屬於抽象概念型條目，可作為教學原則、設計視角與說明骨架。 | Working Draft |
| CC07 | 先流程，後工具 | Principle | Concept | 流程先跑通，工具再升級 | 屬於抽象概念型條目，可作為教學原則、設計視角與說明骨架。 | Working Draft |
| CC08 | Task-first Interaction | Concept | Concept | 任務為入口，不是聊天 | 屬於抽象概念型條目，可作為教學原則、設計視角與說明骨架。 | Working Draft |
| CC09 | Chat-assisted Design | Concept | Concept | Chat 是附屬，不是主體 | 屬於抽象概念型條目，可作為教學原則、設計視角與說明骨架。 | Working Draft |
| CC10 | Cloud-escalation Principle | Principle | Concept | 先 local，再必要時升級雲端 | 屬於抽象概念型條目，可作為教學原則、設計視角與說明骨架。 | Working Draft |
| CC11 | AI Preprocessing Layer | Concept | Concept | AI 先把資料轉成可用素材 | 屬於抽象概念型條目，可作為教學原則、設計視角與說明骨架。 | Working Draft |
| CC12 | Index-first KM | Concept | Concept | 先建索引，不做重推理 | 屬於抽象概念型條目，可作為教學原則、設計視角與說明骨架。 | Working Draft |
| CC13 | PiP Router Concept | Concept | Concept | PiP 是總機，不是工作區 | 屬於抽象概念型條目，可作為教學原則、設計視角與說明骨架。 | Working Draft |
| CC14 | PiP Router | Concept | Concept | 最上層輕量總機 UI | 屬於抽象概念型條目，可作為教學原則、設計視角與說明骨架。 | Working Draft |
| CC15 | Skill-first with External Options | Concept | Concept | 先遵循既有 skill，再由 AI 提供外部可選方案。 | 代表 Primary 是你的方法，Alternative 是 AI 建議，不做覆蓋式替代。 | Working Draft |
| CC16 | Non-destructive AI Guidance | Concept | Concept | AI 提供建議時不覆蓋原決策，而是保留使用者主方法與替代方案。 | 對應多方案輸出原則，強調 non-destructive guidance。 | Working Draft |
| CC17 | Full-context Storage | Concept | Ground Truth | 把完整脈絡保留在檔案系統與版本記錄中，作為後續判讀與追溯依據。 | 對應 FS Ground Truth 強化，強調 full-context storage、data lineage 與 audit evidence。 | Working Draft |
| CC18 | Ground Truth First | Concept | Ground Truth | 先確認檔案系統與版本證據，再進行 AI 推論、摘要與決策。 | 強化 FS 不只是資料來源，而是 evidence / ground truth layer。 | Working Draft |
| CC19 | Task -> Prompt Compiler | Concept | Concept | 把 Prompt Workbench 重新理解為 Task 到 AI 行為的編譯器，而不是獨立核心系統。 | 用來修正 Prompt Workbench 的定位：應視為 Module。 | Working Draft |
| CC20 | FALO Consulting Center | Concept | Concept | 把 FALO 從 AI 工具集合升級為 AI 模型菜諮詢中心的商業定位。 | 對外商業定位主軸，用來承接顧問、課程、展示與服務設計。 | Working Draft |
| CC21 | Expert Experience to AI Knowledge | Concept | Concept | 專家經驗可以透過資料化、模型化、流程化與任務化，轉成系統能力。 | 由 AI 知識工程教材頁映射而來，維持原貌保存，不重寫教材內容。 | Working Draft |
| CC22 | Prompt to Skill | Concept | Concept | Prompt 解決單次溝通，Skill 解決可重複能力。 | 由 AI 知識工程教材頁映射而來，維持原貌保存，不重寫教材內容。 | Working Draft |
| CC23 | Workflow to MCP | Concept | Concept | Workflow 解決流程理解，MCP 解決工具連接與邊界治理。 | 由 AI 知識工程教材頁映射而來，維持原貌保存，不重寫教材內容。 | Working Draft |
| CC24 | AI Task OS as Teaching Bridge | Concept | Concept | AI Task OS 可作為初學者理解 Agent 工作方式的橋樑。 | 由 AI 知識工程教材頁映射而來，維持原貌保存，不重寫教材內容。 | Working Draft |
| CC25 | AI to Delivery Bridge | Concept | Concept | AI 不只回答問題，還要能橋接到真實交付流程與工作環境。 | 用來承接顧問與教材定位，讓初學者理解「對話式 AI -> 可交付工作」之間還有一層橋接能力。 | Working Draft |
| CC26 | Local-first Collaboration with Delayed Cloud Sync | Concept | Concept | 地端即時協作、雲端延遲保存，是一種可教學、可治理的系統邊界。 | 這不是技術細節而已，而是 FALO 在場景系統中可反覆重用的設計原則。 | Working Draft |

### 11.6 MMM 系列｜Multimodal / Local AI Track

多模態、影音、Local AI 與前沿能力線，偏應用能力與實驗軌。


| Code | 名稱 | 類型 | 層級 / 家族 | 一句話用途 | 備註 | 狀態 |
| --- | --- | --- | --- | --- | --- | --- |
| MMM0 | 本書學習資源頁（教材入口） | Entry | MultiModal | 教材網址／資源入口 | 偏能力線與應用線，後續可視需求拆為更獨立的子清單。 | Working Draft |
| MMM10 | WebLLM Client-side AI | Capability | Local AI | 本地 / 瀏覽器端 AI 能力模組 | 偏能力線與應用線，後續可視需求拆為更獨立的子清單。 | POC Verified |
| MMM11 | Text Search Local AI | Application | Local AI | 本地 AI × 文字搜尋導覽 | 偏能力線與應用線，後續可視需求拆為更獨立的子清單。 | POC Verified |
| MMM5 | 轉場觸發機制 | Capability | MultiModal | 影片節奏與轉場邏輯控制 | 偏能力線與應用線，後續可視需求拆為更獨立的子清單。 | Working Draft |
| MMM7 | 文字轉語音（TTS） | Capability | MultiModal | Canva 內建 TTS 等語音輸出 | 偏能力線與應用線，後續可視需求拆為更獨立的子清單。 | Working Draft |
| MMM8 | 影片自動上字幕 | Capability | MultiModal | 影音內容理解與字幕生成 | 偏能力線與應用線，後續可視需求拆為更獨立的子清單。 | Working Draft |
| MMM9 | 多螢幕與多來源錄製 | Capability | MultiModal | 攝影機＋螢幕＋音訊整合 | 偏能力線與應用線，後續可視需求拆為更獨立的子清單。 | Working Draft |

### 11.7 PM 系列｜AI Task OS / Platform Mainline

FALO 作為 AI Task OS 的主軸系列，承接任務系統、決策與交付橋接。


| Code | 名稱 | 類型 | 層級 / 家族 | 一句話用途 | 備註 | 狀態 |
| --- | --- | --- | --- | --- | --- | --- |
| PM01 | AI Task OS | System | Task OS | 以任務狀態為核心，統一追蹤 Goal、State、Decision 與 Next Step 的 AI 任務作業系統。 | 本次升級主軸之一，代表 FALO 從模型菜集合收斂到 AI 任務作業系統。 本版補入 AI 知識工程教材頁，作為 PM01 的教學素材來源。 | Working Draft |
| PM02 | Prompt / Skill / MCP / Agent Evolution | Module | Task OS | 將 Prompt -> Skill、Workflow -> MCP、Assistant -> Agent 的能力演進整理為教學素材。 | 由 index.html 映射而來，用來幫初學者理解能力演進與邊界治理。 | Model Dish Candidate |
| PM07 | Layered NotebookLM System | System | Task OS | 把 Source Notebook 與 Rule Notebook 分層，將資料理解與決策邏輯拆開管理。 | Source Notebook 負責 PDF、OCR、文件摘要與比對；Rule Notebook 負責 decision、pattern、模型菜與顧問邏輯。 | Working Draft |
| PM08 | HITL Rapid Interface Generator | Module | Task OS | 讓 AI 依任務快速生成可操作的 HITL 介面，支援 vibe coding 式的人機協作。 | 本次將 HITL 從人工介入升級為 AI 可生成的人機協作 UI。 | Working Draft |
| PM09 | AI Interaction Platform | System | Task OS | 作為統一對話入口與操作平台，串接所有系統、規則與工作流。 | 承接原本 Task OS / Workbench 的入口角色，現在更明確定位為 AI Interaction Platform。 | Working Draft |
| PM10 | Skill-first Decision Engine | Module | Task OS | 依照 Skill -> Rule -> Source -> FS 的優先順序進行決策，並保留 Primary 與 Alternative 兩種輸出。 | 核心原則是不覆蓋使用者方法，而是先尊重 skill，再提供外部選項。 | Working Draft |
| PM11 | AI Delivery Bridge | Module | Task OS | 讓 FALO 能透過 MCP、SSH 與 GitHub push，把對話式 AI 任務橋接到真實工作環境與交付流程。 | 面向顧問服務、教材模組與可組件化能力。適用於 ChatGPT Codex、Claude Cowork 等對話式 AI 執行環境，但不綁定單一平台。 | Model Dish Candidate |

### 11.8 FS 系列｜Ground Truth / Evidence Layer

Ground Truth 與 Evidence Layer 的保留區，目前欄位已預留，但本版尚未展開具名條目。


目前此系列在 `v0.11` 沒有具名條目，先保留為分類與欄位預留區。


### 11.9 TEACH 系列｜Teaching Materials

從教材、案例、教學頁映射出的模型菜，負責把概念轉成可教內容。


| Code | 名稱 | 類型 | 層級 / 家族 | 一句話用途 | 備註 | 狀態 |
| --- | --- | --- | --- | --- | --- | --- |
| TEACH01 | AI Knowledge Engineering Intro | System | Teaching | 把專家經驗轉成 AI 知識工程的入門教材。 | 主軸是把專家經驗、工作流、Prompt / Skill / MCP / Agent 轉成 AI 可學習、可教學、可運用的知識工程。 | Model Dish Candidate |
| TEACH02 | Workflow Decomposition Teaching Case | Module | Teaching | 以空氣鼓棒、設備維修、客服、作文診斷、餐廳出餐等案例，教 AI 如何拆解與優化工作流。 | 對應 index.html 中的主案例與遷移案例，強調從專家經驗中拆出流程。 | Model Dish Candidate |
| TEACH03 | Resource-bounded AI Task Application | Module | Teaching | 說明 AI 如何在既有資料、規則、案例與工具內完成任務。 | 對應資源限定任務應用與工具邊界的教學說明。 | Model Dish Candidate |

### 11.10 ASSET 系列｜Visual Assets

展示型、視覺型、語意導航型模型菜資產，偏 showcase 與入口價值。


| Code | 名稱 | 類型 | 層級 / 家族 | 一句話用途 | 備註 | 狀態 |
| --- | --- | --- | --- | --- | --- | --- |
| ASSET01 | Sampuru AI Solution Map | Visual Asset / Model Dish | Visual Navigation / Showcase / Semantic Map | Sampuru AI Solution Map 是一張可互動的 AI Solution 語意地圖，用四個圖像區域呈現 FALO 模型菜與 Visual Asset 的展示型態。 | 這不是資料庫系統，也不是一般網站分類頁。它是 Step 3 的影像式分類地圖 MVP，用來讓使用者透過地圖理解 FALO AI 解決方案分布。 | POC complete / MVP usable |

### 11.11 TRACE 系列｜AI Learning Trace

AI 學習履歷與 GitHub / Pages 資產治理保留區，本版欄位已規劃，後續再補實體條目。


目前此系列在 `v0.11` 沒有具名條目，先保留為分類與欄位預留區。


### 11.12 NewsOps 系列｜Project Model Dishes

專案型系統族群，涵蓋 ETL、監測、編修、輸出與審核的整條運作鏈。


| Code | 名稱 | 類型 | 層級 / 家族 | 一句話用途 | 備註 | 狀態 |
| --- | --- | --- | --- | --- | --- | --- |
| NO01 | Information Collection Center | System | NewsOps | 資訊入口的統一中控 | 專案族群模型菜，目前先收錄於總表，後續可獨立整理為專門 catalog。 | Working Draft |
| NO02 | NewsOps System | System | NewsOps | ETL + Scheduler + Monitor 聯合作戰系統 | 專案族群模型菜，目前先收錄於總表，後續可獨立整理為專門 catalog。 | Working Draft |
| NO03 | Crawler Center | Module | NewsOps | Extract / Transform / Load 與卡帶式來源 | 專案族群模型菜，目前先收錄於總表，後續可獨立整理為專門 catalog。 | Working Draft |
| NO04 | Scheduler Center | Module | NewsOps | cron 到 heartbeat / orchestration | 專案族群模型菜，目前先收錄於總表，後續可獨立整理為專門 catalog。 | Working Draft |
| NO05 | Monitor Center | Module | NewsOps | log、狀態監測、事件追蹤 | 專案族群模型菜，目前先收錄於總表，後續可獨立整理為專門 catalog。 | Working Draft |
| NO06 | Crawler Result Center（CRC） | Module | NewsOps | 結果管理、編修、匯出、queue / proposal / rollback | 專案族群模型菜，目前先收錄於總表，後續可獨立整理為專門 catalog。 | Working Draft |
| NO07 | Intake Layer | Module | NewsOps | Event-driven intake / localhost / UI / extension 接口 | 專案族群模型菜，目前先收錄於總表，後續可獨立整理為專門 catalog。 | Working Draft |
| NO08 | Translation Layer | Dish | NewsOps | 翻譯 | 專案族群模型菜，目前先收錄於總表，後續可獨立整理為專門 catalog。 | Working Draft |
| NO09 | Summarization Layer | Dish | NewsOps | 摘要 | 專案族群模型菜，目前先收錄於總表，後續可獨立整理為專門 catalog。 | Working Draft |
| NO10 | Rewrite Layer | Dish | NewsOps | 改稿 | 專案族群模型菜，目前先收錄於總表，後續可獨立整理為專門 catalog。 | Working Draft |
| NO11 | Proposal / Rollback Layer | Dish | NewsOps | 提案 / 回退 | 專案族群模型菜，目前先收錄於總表，後續可獨立整理為專門 catalog。 | Working Draft |
| NO12 | Duplicate Detection Layer | Dish | NewsOps | 重複檢測 | 專案族群模型菜，目前先收錄於總表，後續可獨立整理為專門 catalog。 | Working Draft |
| NO13 | Queue / Processing View Layer | Dish | NewsOps | 排程與處理視圖 | 專案族群模型菜，目前先收錄於總表，後續可獨立整理為專門 catalog。 | Working Draft |
| NO14 | Export Layer | Dish | NewsOps | CSV / Excel / JSON 匯出 | 專案族群模型菜，目前先收錄於總表，後續可獨立整理為專門 catalog。 | Working Draft |
| NO15 | Delivery Layer | Dish | NewsOps | email / 通知交付 | 專案族群模型菜，目前先收錄於總表，後續可獨立整理為專門 catalog。 | Working Draft |
| NO16 | Orchestration Layer | Dish | NewsOps | 未來 orchestration | 專案族群模型菜，目前先收錄於總表，後續可獨立整理為專門 catalog。 | Working Draft |
| NO17 | Heartbeat Layer | Dish | NewsOps | 未來 heartbeat | 專案族群模型菜，目前先收錄於總表，後續可獨立整理為專門 catalog。 | Working Draft |
| NO18 | Action Log / Audit Layer | Dish | NewsOps | 操作與審核層 | 專案族群模型菜，目前先收錄於總表，後續可獨立整理為專門 catalog。 | Working Draft |

### 11.13 IM 系列｜Local-first Collaboration Systems

Local-first IM 與協作工作台系統，承接 communication OS、prompt 管理與資料閉環。


| Code | 名稱 | 類型 | 層級 / 家族 | 一句話用途 | 備註 | 狀態 |
| --- | --- | --- | --- | --- | --- | --- |
| IM01 | Local-first IM Workbench | System | Collaboration System | 把即時通訊、AI Client、Prompt 管理與資料閉環整合在地端工作台中，作為 Falo Communication OS 的 MVP 原型。 | 建議名稱可理解為 Local-first IM Workbench，也可視為 AI Client Communication Workbench。它介於 System / Module 之間，但目前以系統級模型菜原型收錄。Dev 版 index.html 偏實作介面；external-overview.html 偏外部說明版。 | MVP usable |
| IM02 | Local-first IM Dev Client | Module | Collaboration System | Local-first IM Dev 實作介面版，用來測試多人、多 client、AI 角色、Prompt 管理、資料閉環與延遲同步。 | 這份 index.html 是 Dev 實作介面版，偏操作與測試；external-overview.html 則是對外說明版，偏非工程讀者。 | MVP usable |
| IM03 | Local IM Server | Module | Collaboration System | 作為地端中樞，負責接收 client 連線、管理在線狀態、轉送訊息並立即寫入本地紀錄。 | 公開版只保留架構角色與能力摘要，不暴露不必要的環境細節。 | MVP usable |
| IM04 | Identity Module | Module | Collaboration System | 把 user_id、client_id 與 session trace 分開管理，讓身份、登入入口與稽核線索可以被清楚教學與追蹤。 | 第一版重點是教學與稽核，不是複雜權限系統。 | MVP usable |
| IM05 | Message Router | Module | Collaboration System | 判斷訊息是 room message 還是 direct message，並把它送到對應的 client 或 room 成員。 | 適合拿來教初學者理解最小可行的訊息轉送邏輯。 | MVP usable |
| IM06 | Local Message Log | Module | Collaboration System | 把本地訊息紀錄作為第一真實來源，支援後續查詢、匯出與未來批量同步。 | 公開版保留資料角色說明，不暴露 runtime data 本身。 | MVP usable |
| IM07 | Admin View / Admin API | Module | Collaboration System | 提供開發測試 / 稽核視角，讓使用者能查看在線狀態、全域紀錄、連線資訊、IP / session / room 狀態與備份資訊。 | 目前偏全員管理員視角，方便展示、測試與稽核；與 Communication OS、AI Logging Shell、Local Data Hub 有高度關聯。 | MVP usable |
| IM08 | Personal Prompt Manager | Module | Collaboration System | 把 Prompt 新增、分類、搜尋、匯入匯出與帶入聊天室整合在個人 Prompt 管理器中。 | 這一模組讓 IM 不只是聊天，而是可承接 AI 指令、Prompt 治理與教學資產。 | MVP usable |
| IM09 | Backup Sync Queue | Module | Collaboration System | 把 JSON / Excel 匯出匯入、本機回灌、GAS Lite 部署包與 Google Sheet 延遲同步整理成資料閉環隊列。 | 核心邊界是 Local-first、Cloud delayed save；同時支援資料閉環與 GAS / Google Sheet 備份路線。 | MVP usable |

## 12. 署名

`FALO x Force Cheng 2026/5/6`
