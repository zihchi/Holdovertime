# Holdovertime

FAA Holdover Time (HOT) 計算器 — 資料版本：**FAA Holdover Time Guidelines, Winter 2026-2027 (Original Issue, August 11, 2026)**。

- `index.html`：網頁介面與計算邏輯
- `data/hot-2026-27.js`：由 FAA PDF 解析產生的資料（Table 1、2、3、20–52、55、56、57）
- `images/2026-27/`：FAA 原始表格頁面圖片（依 Table 編號命名）

涵蓋：
- SAE Type I（Aluminum / Composite，Table 2 / 3）
- SAE Type IV Generic（Table 20）及全部 32 種 fluid-specific Type IV（Table 21–52）
- Active Frost（Table 1）、Allowance Times（Table 53 驗證狀態、Table 55 EG / Table 56 PG）、降雪強度（Table 57）

未包含：Type II、Type III，以及 Appendix A（flaps/slats 預先放下的 Adjusted HOT）。
