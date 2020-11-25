---
name: Outsourcing
about: Outsourcing
title: "[Project Name] Function Name  | NT$ or US$ | Date From mm/dd(D) To mm/dd(D)"
labels: Project develop
assignees: ''

---

## Outsourcing Description 
### Purpose 
- To solve the problem 
   - 
   -
   -
- Benefit
   - 
   -
   -

### Project 
- name : 
- branch : 
   
### Flow chart
   -

### DB Schema
- DB Name : 
- Table Name : 
   
### Naming
- Project Package Name : 
- Class Name : 
- API URL : 

### To Do List
- Program logic Developer
  - Program, DB, and related technology
- Unit Test    
  - PostMan 
    - Unit Test and Flow Test
- Website
  - Interface operation Test
         
### Development considerations
- Naming rules
- Programming style
- Component used 

### Delivery notes 
- Reply Issue
  - Test Gif
    - Junit
    - PostMan - Collection 路徑
    - Interface operation 介面操作
- New Pull Request
  - Screenshot

### Other

## Front-end outsourcing specifications
1. No eslint warning or any error appears
2. The UI and operation process must conform to the draft content
3. Please open a branch in the project repository (one issue, one branch) and open a PR after completion
4. Need to pass code review

## Back-end outsourcing specifications
1. No eslint warning or any error appears
2. The UI and operation process must conform to the draft content
3. Please open a branch in the project repository (one issue, one branch) and open a PR after completion
4. Need to pass code review

### Git commit format regulations

Header: [server/client][type(scope)][subject]

1. server/client represents front-end or back-end | server/client 代表是前端或後端 | 
2. Type is divided into feat, fix, docs, style, refactor, test, chore | type 分為 feat, fix, docs, style, refactor, test, chore
3. Scope represents the scope affected by commit, such as the database, control layer, template layer, etc., which varies depending on the project and is an optional field. | scope 代表 commit 影響的範圍，例如資料庫、控制層、模板層等等，視專案不同而不同，為可選欄位。
4. Subject is a short description, no more than 50 words | subject 為簡短的描述，不可超過 50 字

Body: 72-character wrapped. This should answer:

* The body is a detailed description of this commit, which can be divided into multiple lines, each line should not exceed 72 characters. | body 是對本次 commit 的詳細描述，可以分成多行，每一行不要超過 72 個字元。
* Explain the items and reasons of the code changes, as well as the comparison with the previous behavior. | 說明程式碼變動的項目與原因，還有與先前行為的對比。

Footer:

* Fill in the task number (if any). | 填寫任務編號（如果有的話）.
* BREAKING CHANGE (can be ignored), record incompatible changes,
    Start with BREAKING CHANGE:, followed by a description of the change, the reason for the change and the migration method. | BREAKING CHANGE（可忽略），記錄不兼容的變動，
   以 BREAKING CHANGE: 開頭，後面是對變動的描述、以及變動原因和遷移方法。

#### type 只允許使用以下類別

* feat: new/modified features (feature). | 新增/修改功能
* fix: fix bugs (bug fix). | 修補 bug
* docs: documentation. | 文件
* style: format (white-space, formatting, missing semi colons, etc.) which do not affect the operation of the code. | 格式 (不影響程式碼運行的變動 white-space, formatting, missing semi colons, etc)。
* refactor: refactoring (neither a new feature nor a code change to fix a bug). | 重構 (既不是新增功能，也不是修補 bug 的程式碼變動)。
* perf: A code change that improves performance. | 改善效能
* test: add test | 增加測試
* chore: changes in the construction process or auxiliary tools (maintain). | 建構程序或輔助工具的變動 (maintain)。
* revert: Cancel and reply the previous commit For example: revert: type(scope): subject (reply version: xxxx). | 撤銷回覆先前的 commit 例如：revert: type(scope): subject (回覆版本：xxxx)。
