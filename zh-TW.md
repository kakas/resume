蕭錦成 (Hsiao, Chin-Cheng)

Full-Stack Web Developer

Taipei, Taiwan, shrimptrain@gmail.com

## 工作經歷

### 幫你優 (BonioO Inc.) Jan, 2017 - Present

**Full-Stack Web Developer**

- 開發遊戲相關功能
   - Ruby on Rails 及 Rspec 開發後端
   - React、Redux 開發前端
- 審查 Pull Request，確保商業邏輯正確及程式碼品質優良
   -  從 2017/01/03 - 2021/01/31 團隊共發出 9008 個 PR <sup>[1](#foot-note-1)</sup>，審查 Pull Request 的數量為 2979 <sup>[2](#foot-note-2)</sup>，約 33%
- 建置可承受 10,000 人同時連線的 WebSocket Server
   - 使用 Golang 開發，佈署至 AWS Elastic Container Service (ECS)
   - High Available (部分 server 死掉不會影響整個系統)
- 優化後端程式維護性及效能
   - 增加必要的 DataBase index 及減少不必要的 DataBase Index
   - 修正 Race Condition (或在 code review 時找出 race condition 相關問題)
   - 運用 Design Pattern，增加程式可讀性及維護性
- 撰寫 JMeter 腳本執行壓力測試
   - 協助同仁估算線上賽事需要的 Infra 大小
- 導入 Webpack 讓前端可以使用 ES6 語法及 babel-polyfill，讓開發更快、更好維護
- 導入 React 至遊戲端，讓效能更好、開發更快、程式更好維護
- 前端導入靜態檢查工具，減少開發時間，讓程式更好維護
   - ESLint + scss-lint
- 製作各種遊戲的 UI
   - 範例: https://github.com/kakas/resume/issues/1
- 舉辦程式讀書加強團隊專業知識，並應用在工作上

### 自由工作者 April, 2016 ~ Dec, 2016

**Full-Stack Web Developer**

- 自學 Ruby on Rails
- 使用 Ruby on Rails 開發貸款及人員管理系統 (接案)

### 盈正豫順 (Ablerex Electronics Co., Ltd.) Dec, 2011 ~ Mar, 2016

**Firmware Engineer**

- 開發 60 KVA 三相不斷電併聯系統
   - 使用 C 語言在 TMS320F2808 平台開發
   - https://www.ablerex.com.tw/products_4.php?bgid=1&mgid=1&sgid=65
- 使 2 台穩定併聯提昇至 6 台穩定併聯，輸出功率提昇至 3 倍
- 開發 30 KVA 熱插拔三相不斷電併聯系統，可線上增減機器數量，讓現場維修更方便、快速
   - https://www.ablerex.com.tw/products_4.php?bgid=1&mgid=1&sgid=37
- 實驗各種環境下運作情形
   - 不同的電壓、負載及溫度
   - 撰寫測試報告
- 導入 git 做版本控管，讓程式更容易維護

## 學歷

高雄應用科技大學電機工程所碩士 2008 ~ 2010

高雄應用科技大學電機工程系學士 2004 ~ 2008

### footnote:

<a name="foot-note-1">1. 團隊發出的 PR 數量</a>: 在 Pull Requests 列表搜尋 `is:pr created:>2017-01-03`

<a name="foot-note-2">2. Code Review 的數量</a>: 在 Pull Requests 列表搜尋 `is:pr reviewed-by:kakas`
