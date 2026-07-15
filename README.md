# 🏛️ Bill | Staff Backend Engineer & Tech Lead

資深後端工程師 / 技術主管，專精於複雜系統重構、資料庫效能調校、線上緊急故障排除與災難復原。具備高合規環境與零信任安全架構實務經驗。

---

### 🚀 核心成效 | Key Achievements

* **200x 查詢效能重構**：重構 WinUI 3 / SQLite 索引路徑與非同步（Asynchronous）查詢邏輯，將 5 萬筆 Metadata 查詢延遲從 100 秒縮短至 0.5 秒內。
* **97% 資料災難搶修**：維運服務 10 萬+ 用戶之政府級平台，於系統崩潰及全域資料污染的極端狀態下，獨立透過日誌逆向回溯與斷點分析，將受損帳務資料修復至 97% 以上。
* **80% 研發流程自動化**：整合 ClickUp API 與 Google Apps Script (GAS) 實作自動化工作流程，排除團隊 80% 重複性行政與管理庶務。
* **底層資料物理隔離**：於 SaaS 架構遷移中實作 PostgreSQL RLS (Row Level Security)，從資料庫引擎層根除橫向越權 (IDOR) 漏洞，落實零信任防禦。

---

### 🛠️ 技術堆疊 | Tech Stack

* **後端與系統架構**：Node.js (Next.js / TypeScript), PHP (Laravel), C# (.NET 8)
* **資料庫治理與調校**：PostgreSQL (RLS), MariaDB, MS SQL, SQLite 執行計畫優化
* **安全防護與自動化維運**：零信任架構、RBAC 權限控管、Docker 容器化、GitHub Actions CI/CD、Linux 系統安全強化
* **工作流程自動化**：ClickUp Certified Expert，專精於研發流程自動化與團隊 DX (開發者體驗) 優化

---

### 📂 精選專案 | Featured Projects

* **[travelroute-studio]** (Private) ── **已上架 Steam 平台**
    * 連結：https://store.steampowered.com/app/4409090?snr=5000_5100__
    * **已發行的跨平台桌面應用**。獨立負責產品架構設計、Steamworks SDK 整合與跨平台效能調校，並自主完成整體商店審查與發行流程。

* **[historyPhoto]** (Private) ── **已上架 Microsoft Store**
    * 連結：https://www.microsoft.com/store/productId/9NL8S4587L5W?ocid=libraryshare
    * **高效能本地相簿瀏覽器**。採用 C# (WinUI 3) 與 SQLite 實作，重構索引路徑與非同步查詢邏輯，優化大圖預覽時的本地 I/O 吞吐量瓶頸，將 5 萬張照片的 Metadata 檢索延遲降至 0.5 秒內。

* **[PetPhotoSorter]** (Public)
    * 連結：https://github.com/bill86854238/PetPhotoSorter
    * **完全離線（Offline-first）的 Edge AI 照片整理工具**。串接 YOLOv8 物件偵測與 CLIP 語意特徵分類，並在本地端（NAS/PC）部署 Ollama (Qwen2.5-VL) 進行多模態 AI 管道（Pipeline）整合，在保障資料主權的前提下實現自動化標記。

* **[shared-expense-book-v3]** (Private)
    * **採用多租戶架構的共同記帳系統**。在資料庫層實作 PostgreSQL RLS (Row Level Security) 進行資料隔離，並透過 B-Tree 索引與執行計畫（Execution Plan）優化，解決查詢瓶頸並根除橫向越權（IDOR）安全性弱點。

* **[gas-line-bot-assistant-multiplayer]** (Private)
    * **高併發多人版台鐵誤點通知 LINE Bot**。針對 TDX API 的呼叫配額與執行時間限制，自行設計流量削峰（Traffic Shaving）與多層快取機制，在零成本預算限制下穩定承載通勤族的高頻查詢。

---

### ✍️ 技術著作與專欄 | Publications & Columns

* **《數位地堡》系列著作** (2026)：
    * [《數位地堡：2026 數據主權與資安建築實戰》](https://readmoo.com/book/2104525760001) ── 探討後端安全強化、強合規資料保護與零信任防禦。
    * [《數位地堡 Vol.2：跨界防禦專場》](https://readmoo.com/book/2104555700001) ── 聚焦於異質系統整合安全、邊緣運算與實務防護策略。
    * [《數位地堡 Vol.3：職場資安博弈》](https://readmoo.com/book/2104595650001) ── 剖析企業安全決策、風險評估與社交工程防禦。
* [**方格子 (Vocus) 技術隨筆**](https://vocus.cc/) ── 紀錄後端開發、系統設計與資料庫調校之實務經驗歸檔。

---

[![ClickUp Certified](https://img.shields.io/badge/Certification-ClickUp_Certified_Expert-7b68ee?style=for-the-badge&logo=clickup)](https://clickup.com)
