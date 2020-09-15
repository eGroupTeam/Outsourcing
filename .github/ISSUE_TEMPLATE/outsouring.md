---
name: Outsourcing
about: Outsourcing
title: "[項目名稱]] 功能名稱 UI | NT$ | 日期 mm/dd(D) ~ mm/dd(D)"
labels: Project develop
assignees: ''

---

## 外包任務說明
### 目的
- 要解決問題
   - 
   -
   -
- 效益
   - 
   -
   -

### 專案
- 專案名稱 : 
- 分支名稱 : 
   
### 程式流程圖
   -

### DB Schema
- DB Name : 
- Table Name : 
   
### 命名
- Project Package Name : 
- Class Name : 
- API URL : 

### 需完成事項
- 程式邏輯
  - 程式、DB、相關需要的技術
- 單元測試    
  - PostMan 
    - 單元測試與流程測試
- 網站
  - 介面操作測試
         
### 開發注意事項
- 命名規則
- 程式風格
- 元件使用

### 交付注意事項
- 回覆至此Isuue 
  - 測試Gif影像檔
    - Junit
    - PostMan - Collection 路徑
    - 介面操作
- 開立PR
  - 截圖

### 其他備註事項

## 前端外包規範

1. 不能有 eslint warning 或是任何的 error 出現
1. UI 和操作流程需符合草稿內容
1. 請在專案的 repository 開分支（一個 issue 一個分支）完成後開 PR
1. 需通過 code review

## 後端外包規範

1. 不能有 checkstyle warning 或是任何的 error 出現
1. api 撰寫須符合 UI 介面和操作流程
1. 請在專案的 repository 開分支（一個 issue 一個分支）完成後開 PR
1. 需通過 code review

### Git commit 格式規定

Header: [server/client][type(scope)][subject]

1. server/client 代表是前端或後端
1. type 分為 feat, fix, docs, style, refactor, test, chore
1. scope 代表 commit 影響的範圍，例如資料庫、控制層、模板層等等，視專案不同而不同，為可選欄位。
1. subject 為簡短的描述，不可超過 50 字

Body: 72-character wrapped. This should answer:

* body 是對本次 commit 的詳細描述，可以分成多行，每一行不要超過 72 個字元。
* 說明程式碼變動的項目與原因，還有與先前行為的對比。

Footer:

* 填寫任務編號（如果有的話）.
* BREAKING CHANGE（可忽略），記錄不兼容的變動，
   以 BREAKING CHANGE: 開頭，後面是對變動的描述、以及變動原因和遷移方法。

#### type 只允許使用以下類別

* feat: 新增/修改功能 (feature)。
* fix: 修補 bug (bug fix)。
* docs: 文件 (documentation)。
* style: 格式 (不影響程式碼運行的變動 white-space, formatting, missing semi colons, etc)。
* refactor: 重構 (既不是新增功能，也不是修補 bug 的程式碼變動)。
* perf: 改善效能 (A code change that improves performance)。
* test: 增加測試 (when adding missing tests)。
* chore: 建構程序或輔助工具的變動 (maintain)。
* revert: 撤銷回覆先前的 commit 例如：revert: type(scope): subject (回覆版本：xxxx)。
