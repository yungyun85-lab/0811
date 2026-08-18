# 🎧 FocusLingua | 為特殊神經多元學習者打造的 90 秒微型英語學習 App

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![PRD Version](https://img.shields.io/badge/PRD-v2.1-brightgreen.svg)](app_model/app_design_blueprint_v3.md)
[![Target Audience](https://img.shields.io/badge/Audience-ADHD%20%7C%20Dyslexia-orange.svg)](01_product_definition.md)

> **「以感官協同取代死記硬背，用多巴胺循環縮短注意力鴻溝。」**  
FocusLingua 專門為非標準腦（Neurodivergent，如 ADHD / ADD / 閱讀障礙）學習者設計，將學習啟動成本降至最低。

---

## ✨ 核心特色與亮點 (Core Features)

* ⏱️ **90 秒微型關卡 (Micro-learning)**：每堂課強制限制 90 秒，每次僅教授 3 個核心單字，極大幅度降低心理負擔與認知負荷。
* 👁️ **閱讀障礙友善介面 (Dyslexia-Friendly)**：支援開放式閱讀障礙專用字體 (OpenDyslexic)、擴大字距與列高、防止視錯覺與跳行。
* 🎵 **多感官輔助與白噪音 (Multisensory Sync)**：整合低頻白噪音聲波 (BGM) 與輕微觸覺回饋 (Haptic Feedback)，穩定神經專注力。
* 🎯 **無挫折自適應演算法 (Errorless Learning)**：實時監測點擊反應時間 (Reaction Latency)，自動彈性調整關卡難度與提醒機制。
* 👩‍🏫 **教師端分流與句子上傳 (Teacher Gateway)**：提供教師自訂詞彙清單與情境輔助句上傳功能。

---

## 📁 專案結構與文件指南 (Project Structure)

本倉庫包含 FocusLingua 之完整產品需求文件 (PRD)、資料庫模型與 UI 介面設計規格：

```text
FocusLingua_PRD_0811/
├── app_model/                               # 📱 App 介面與模型設計規格
│   ├── app_design_blueprint_v3.md           # App 介面設計規格藍圖 v3 (包含教師端與分流)
│   └── focuslingua_stitch_prompts.md        # Stitch UI Prompt 指南彙整 (中英對照)
├── 01_product_definition.md                # 📘 項目一：產品定義書 (受眾與痛點)
├── 02_user_stories.md                      # 📘 項目二：使用者故事 (User Stories)
├── 03_functional_specifications.md         # 📘 項目三：功能詳細規格
├── 04_architecture_and_data_model.md       # 📘 項目四：系統架構與 PostgreSQL Schema
├── 05_state_flows_and_mockups.md           # 📘 項目五：狀態流程與 Mockup
├── 06_asset_inventory.md                   # 📘 項目六：靜態資源清單
├── prd_combined.md                         # 📄 完整 PRD 合併文件
├── prd_printable.html                      # 🖨️ 格式化 PRD 列印與預覽網頁
└── index.html                              # 🌐 FocusLingua PRD 儀表板
```

---

## 🛠️ 系統架構概要 (Architecture Overview)

* **展示層 (Client)**: HTML5 / CSS3 / React Native（離線優先、零卡頓動態渲染、Web Audio 白噪音引擎）
* **服務層 (Server)**: Node.js API Gateway / Go 微服務（專注力反應延遲計算演算法）
* **資料層 (Database)**: PostgreSQL（靜態進度與使用者偏好） + ClickHouse（即時行為與 Latency 大數據）

---

## 🚀 預覽與使用 (Preview & Documentation)

要預覽 PRD 儀表板或 HTML 版本文件：
- 可以在本機瀏覽器開啟 [index.html](file:///Users/annamei/notes/FocusLingua_PRD_0811/index.html) 或 [prd_printable.html](file:///Users/annamei/notes/FocusLingua_PRD_0811/prd_printable.html) 進行內容瀏覽。

---

## 📜 授權條款 (License)

本專案文件與設計模型採用 MIT License 授權。
