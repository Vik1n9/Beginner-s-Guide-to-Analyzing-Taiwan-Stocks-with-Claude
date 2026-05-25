# 財經人的第一堂 AI 策略課：用 Claude 打造你的短線分析模板

> 不懂程式也能 30 分鐘上手 —— 從下載到自動抓資料，一步一步帶你做

## 📖 立即開啟指南網頁

**線上預覽（無需下載）：**

[![開啟教學網頁](https://img.shields.io/badge/📊%20開啟教學網頁-立即閱讀-f0a500?style=for-the-badge)](https://htmlpreview.github.io/?https://github.com/vik1n9/beginner-s-guide-to-analyzing-taiwan-stocks-with-claude/blob/claude/zen-maxwell-slLHu/index.html)

> 🔗 完整連結：`https://htmlpreview.github.io/?https://github.com/vik1n9/beginner-s-guide-to-analyzing-taiwan-stocks-with-claude/blob/claude/zen-maxwell-slLHu/index.html`

---

## 專案簡介

本專案是一份**完整的繁體中文單頁教學網頁**，目標讀者為熟悉股票／期貨短線操作、但完全不懂程式與 AI 的財經從業人員與投資者。

教學目標：在 30 分鐘內，利用 Claude 桌面版 App 建立自己的短線分析策略模板，並學會下指令、調整策略、整合 FinMind 台股資料庫。

## 快速開始

直接開啟 `index.html` 即可在瀏覽器中瀏覽完整教學，**無需伺服器、無需編譯、無需安裝任何套件**。

```bash
# 直接用瀏覽器開啟
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```

## 教學章節架構

| 章節 | 主題 | 重點內容 |
|------|------|----------|
| 第一章 | 為什麼需要 AI 策略模板 | 傳統 vs. AI 輔助比較表、Claude 的正確定位 |
| 第二章 | 下載與安裝 Claude | 4 步驟安裝指南、訂閱方案說明 |
| 第三章 | 第一次下命令 | 萬用短線分析 Prompt 模板、示範對話流程 |
| **第四章** | **資料來源 — FinMind** | **FinMind 註冊、API Token 取得、建立 Skill** |
| 第五章 | 聯網搜尋與上傳資料 | 啟用聯網、CSV 標準格式、上傳分析 |
| 第六章 | 調整與優化策略模板 | 追問技巧、互動式 Prompt 建構器 |
| 第七章 | 儲存為 SOP | Claude 專案設定、每日快速啟動流程 |
| 第八章 | 完成說明與注意事項 | AI 輔助定位、資料時效、風險控管 |
| 清單 | 快速檢查清單 | 互動式勾選，確認完成所有步驟 |
| FAQ | 常見問題 | 7 個常見疑問解答 |

## FinMind 整合說明

本教學第四章深度整合 [FinMind](https://finmind.github.io/) 台股資料庫，涵蓋：

### 資料來源
- **API 文件**：[https://finmind.github.io/](https://finmind.github.io/)
- **會員中心**：[https://finmindtrade.com/](https://finmindtrade.com/)
- **API 端點**：`https://api.finmindtrade.com/api/v4/data`

### 支援的資料集
| 資料集名稱 | 說明 |
|-----------|------|
| `TaiwanStockPrice` | 個股日K / 週K / 月K 股價（開高低收量） |
| `TaiwanStockInstitutionalInvestors` | 三大法人買賣超 |
| `TaiwanStockMarginPurchaseShortsale` | 融資融券餘額 |
| `TaiwanStockFinancialStatements` | 財務報表 |
| `TaiwanStockMonthRevenue` | 月營收資料 |

### 免費方案
- 每日 **600 次** API 請求
- 適合個人每日分析 10~20 支股票
- 無需信用卡即可使用

### 建立 FinMind Skill 的三種方式
1. **方法 A（推薦）**：建立 Claude Project，貼入包含 Token 的 FinMind Skill Prompt
2. **方法 B（免費版）**：使用 Claude Custom Instructions 全域設定
3. **方法 C（進階）**：請 Claude 撰寫 Python 腳本自動化抓取

## 網頁功能特色

- **一鍵複製提示詞**：所有 Prompt 範例均附複製按鈕
- **互動式 Prompt 建構器**：勾選技術/籌碼指標，自動生成客製化 Prompt
- **互動式勾選清單**：點擊確認完成進度
- **FAQ 手風琴**：展開/收合常見問題
- **淡入動畫**：瀏覽時區塊優雅淡入，不影響效能
- **響應式設計**：手機與桌面均可舒適閱讀
- **固定導覽列**：快速跳轉至任一章節，含滾動高亮

## 設計規格

- **配色**：深藍（`#0a1628`）+ 白色 + 金色點綴（`#f0a500`）
- **字型**：Noto Sans TC（Google Fonts CDN）
- **無外部框架依賴**：純 HTML + CSS + JavaScript
- **瀏覽器相容**：Chrome / Firefox / Safari / Edge 現代版本

## 重要免責聲明

> ⚠️ 本教學網頁及所有 Prompt 模板**僅供學習參考**，不構成任何投資建議。
> 
> Claude 是分析輔助工具，不是自動下單機器人。所有交易決策、資金管理、停損執行，請自行判斷並承擔責任。
> 
> AI 分析結果受資料時效性影響，關鍵數據請以券商系統報價為準。

## 授權

本教學內容以 [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) 授權分享——可自由使用、改作，但需署名，且不得用於商業目的。
