# 🏛️ Bill | Staff Backend Engineer & Tech Lead

資深後端工程師 / 技術主管，專精於複雜系統重構、資料庫效能調校與高壓環境下的故障診斷救援。具備高合規環境與零信任安全架構實務經驗，資安專著《數位地堡：2026 數據主權與資安建築實戰》作者。

---

### 🚀 核心成效 | Key Achievements

* **200x 查詢效能優化**：重構 WinUI 3 / SQLite 索引路徑與**非同步（Asynchronous）**查詢邏輯，將 5 萬筆 **Metadata** 的檢索延遲從 **100 秒壓縮至 0.5 秒內**。
* **97% 全局資料救援**：維運服務 10 萬+ 用戶之政府級平台，於系統崩潰及**全域資料**污染的極端狀態下，獨立執行日誌逆向回溯與斷點分析，**成功將受損帳務資料修復至 97% 以上**。
* **80% 研發流程自動化**：整合 **ClickUp API** 與 Google Apps Script (GAS) 開發自動化工作流，徹底消除團隊 80% 的人工重複性行政與管理損耗。
* **底層物理級資料隔離**：於 SaaS 架構遷移中實作 **PostgreSQL RLS (Row Level Security)**，從資料庫引擎層根除橫向越權 (IDOR) 漏洞，落實零信任防禦。

---

### 🛠️ 技術堆疊 | Tech Stack

* **後端與系統架構**：Node.js (Next.js / TypeScript), PHP (Laravel), C# (.NET 8)
* **資料庫治理與調校**：PostgreSQL (RLS), MariaDB, MS SQL, SQLite 執行計畫優化
* **安全防護與自動化維運**：零信任架構、RBAC 權限控管、Docker 容器化、GitHub Actions CI/CD、Linux 系統硬化加固
* **工作流治理**：**ClickUp Certified Expert**，專精於研發流程自動化與團隊 DX (開發者體驗) 治理

---

### 📂 精選專案 | Featured Projects

* **[travelroute-studio]** (Private) ── **已上架 Steam 平台**
    * 獨立開發並上架至 **Steam 平台** 的跨平台桌面軟體。採用 **HTML/JS** 技術堆疊搭配桌面包裝引擎，完成從產品開發、**Steamworks SDK** 整合、跨平台效能優化到平台上架發行的完整產品生命週期。

* **[historyPhoto]** (Private) ── **已上架 Microsoft Store**
    * 已上架至 **Microsoft Store** 的高效能本地相簿瀏覽器。採用 **C# (WinUI 3)** 與本地 **SQLite** 實作，針對 5 萬張歷史照片的 **Metadata** 進行索引重構與非同步查詢優化，將檢索延遲從 100 秒壓縮至 0.5 秒內，解決高頻磁碟 I/O 瓶頸。

* **[cryptable]** (Private)
    * 零知識加密關係型表格實作。在應用程式端即採用 **AES-256** 對敏感欄位進行加解密後才寫入資料庫，確保雲端託管服務商在零知識（**Zero-Knowledge**）前提下完全無法窺探內容，從根源落實端到端（E2E）資料主權防護。

* **[shared-expense-book-v3]** (Private)
    * **Next.js (TypeScript)** 與 **Supabase** 共同記帳系統。於資料庫層實作 **PostgreSQL RLS (Row Level Security)** 物理級資料隔離，並優化 B-Tree 索引與執行計畫調校，從底層根除橫向越權（IDOR）安全性弱點。

* **[gas-line-bot-assistant-multiplayer]** (Private)
    * 台鐵誤點通知多人版 **LINE Bot**。針對 LINE 平台與 **TDX API** 嚴苛的呼叫配額與執行時間限制，手動實作流量削峰（**Traffic Shaving**）與多層快取機制，在零預算架構下穩定承載通勤族的高頻查詢。

---

### ✍️ 技術著作與專欄 | Publications & Columns

* **📖 專業著作**：《數位地堡：2026 數據主權與資安建築實戰》—— 系統性梳理多年資安架構與強合規環境之**資料**防禦實績。（註：書名依原著保留，說明文字已在地化）
* **📝 技術專欄**：[方格子 (Vocus)](https://vocus.cc/) —— 深度解析後端異質系統整合、資料庫底層安全加固與 FinOps 雲端成本精算。

---

[![ClickUp Certified](https://img.shields.io/badge/Certification-ClickUp_Certified_Expert-7b68ee?style=for-the-badge&logo=clickup)](https://clickup.com)
