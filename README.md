# 智慧文具店資料庫管理系統

這是一個以 SQLite 為基礎的文具店資料庫學習專題，整合會員、商品分類、商品、訂單、訂單明細與庫存異動。

## 線上操作

開啟 GitHub Pages 部署後的網站即可練習 SQL。網站使用 SQL.js，需連接網路以載入執行引擎。

## 專案內容

- `index.html`：互動式資料庫教學網頁，可編輯並執行 SELECT 查詢。
- `database/stationery.db`：SQLite 範例資料庫。
- `sql/create_tables.sql`：資料表結構與關聯。
- `sql/sample_data.sql`：虛構示範資料。

## 資料表

MEMBERS、CATEGORIES、PRODUCTS、ORDERS、ORDER_DETAILS、INVENTORY_LOG。

## 本機使用

可使用 DB Browser for SQLite 開啟 `database/stationery.db`，或以 SQLite 執行 `sql/create_tables.sql` 與 `sql/sample_data.sql`。

> 本專題的會員與訂單資料皆為虛構範例。
