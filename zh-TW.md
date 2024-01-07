## 基本資訊

- **姓名：** 蕭錦成 (Hsiao, Chin-Cheng), 你也可以叫我 Kakas
- **應徵職位：** Ruby on Rails Developer
- **居住地：** 新北淡水
- **電子郵件：** shrimptrain@gmail.com

## 工作經歷

### FARIA EDUCATION GROUP (May,  2021 - Present)

**Full-Stack Developer**

- 開發及維護維 OpenApply 系統 (https://www.openapply.com/) 
  - **開發及維護後端 API**：設計、開發和維護 OpenApply 應用程式的後端 API，優化程式碼以提高可讀性和效能。
  - **重構寄信模板功能**：提高程式可讀性及效能，並支援使用者在對應的欄位
  - **設計及開發 Advancement Module 自動標記系統**： 負責設計並開發 Advancement 模組的自動標記系統，有效地提高了相應流程的效率。
  - **導入 Coverband 協助移除 Dead Code**： 引入 Coverband 工具，協助識別並移除不再使用的程式碼，提高代碼清晰度和減少冗餘。
  - **使用 devise-two-factor 開發 2FA 功能**：提高 App 的安全性
  - 效能優化：
    - 匯出功能：6.6 秒/請求 -> 3.8 秒/請求
    - 學生編輯頁面：前端速度提升 10 倍，後端 2 倍
    - 優化資料同步 API，提升回應速度 2.38 倍，提高數據同步的效率
  - 技術遷移：
    -  Rails autoloader 從 classic 至 zeitwerk
    - feature test 工具鏈，從 PhantomJS 至 selenium + headless chrome
    - 成功將部分頁面改爲 Vue2.js 實作，使程式更好維護並減少伺服器負擔
- 領導和培訓
  - **領導程式讀書會及 Code Review 讀書會：** 組織並主持專業技能提升活動，加強團隊的專業知識。
  - **新進人員帶領：** 成功帶領新進人員，協助他們順利融入團隊並熟悉工作流程。
  - **規劃修正 Coding Style：** 領導團隊進行 coding style 的修正和規劃，確保代碼風格的一致性和提高整體代碼品質。

### 幫你優 BonioO Inc. (Jan, 2017 - April 2021)

**Full-Stack Web Developer**

- 開發及維護 PaGamO https://www.pagamo.org/
   - 後端使用 Ruby on Rails 及 Rspec
   - 導入 React，重構既有遊戲原件，讓原件模組化，更易維護，效能也更好
- 建置可承受 10,000 人同時連線的 WebSocket Server
   - 使用 Golang 開發，佈署至 AWS Elastic Container Service (ECS)
   - High Available (部分 server 死掉不會影響整個系統)
- 審查 Pull Request，確保商業邏輯正確及程式碼品質優良
   -  從 2017/01/03 - 2021/01/31 團隊共發出 9008 個 PR <sup>[1](#foot-note-1)</sup>，審查 Pull Request 的數量為 2979 <sup>[2](#foot-note-2)</sup>，約 33%
- 優化後端程式維護性及效能
   - 增加必要的 DataBase index 及減少不必要的 DataBase Index
   - 修正 Race Condition (或在 code review 時找出 race condition 相關問題)
   - 運用 Design Pattern，增加程式可讀性及維護性
- 撰寫 JMeter 腳本執行壓力測試
   - 協助同仁估算線上賽事需要的 Infra 大小
- 前端導入靜態檢查工具，減少開發時間，讓程式更好維護
- 製作各種遊戲的 UI
   - 範例: https://github.com/kakas/resume/issues/1
- 舉辦程式讀書加強團隊專業知識，並應用在工作上

### 自由工作者 (April, 2016 ~ Dec, 2016)

**Full-Stack Web Developer**

- 自學 Ruby on Rails
- 使用 Ruby on Rails 開發貸款及人員管理系統 (接案)
  - 兩位後端一位切版工程師，後端使用 Ruby on Rails 前端使用 React


### 盈正豫順 Ablerex Electronics Co., Ltd. (Dec, 2011 ~ Mar, 2016)

**Firmware Engineer**

- 開發 60 KVA 三相不斷電併聯系統
   - 使用 C 語言在 TMS320F2808 平台開發
   - https://www.ablerex.com.tw/products_4.php?bgid=1&mgid=1&sgid=65
- 使 2 台穩定併聯提昇至 6 台穩定併聯，輸出功率提昇至 3 倍
- 開發 30 KVA 熱插拔三相不斷電併聯系統
   - 開機、關機程序撰寫
   - 開發熱插拔程序，使機器可以在運轉中增減機器數量。防止用電設備中斷產出，並增加現在維護人員的方便性
   - https://www.ablerex.com.tw/products_4.php?bgid=1&mgid=1&sgid=37
   
- 測試機器反應能力、可靠度及報告撰寫
   - 不同的電壓、負載及溫度
- 導入 git 做版本控管，讓程式更容易維護

## 學歷

高雄應用科技大學電機工程所碩士 2008 ~ 2010

高雄應用科技大學電機工程系學士 2004 ~ 2008

### footnote:

<a name="foot-note-1">1. 團隊發出的 PR 數量</a>: 在 Pull Requests 列表搜尋 `is:pr created:>2017-01-03`

<a name="foot-note-2">2. Code Review 的數量</a>: 在 Pull Requests 列表搜尋 `is:pr reviewed-by:kakas`
