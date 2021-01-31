蕭錦成 (Hsiao, Chin-Cheng)

Full-Stack Web Developer

Taipei, Taiwan, shrimptrain@gmail.com

## 工作經歷

### 幫你優 (BonioO Inc.) Jan, 2017 - Present

- 開發遊戲相關功能，使用 Ruby on Rails 及 Rspec 開發後端 API，前端使用 React、Redux 開發
- 審查 Pull Request，把關商業邏輯及程式碼品質
   -  從 2017/01/03 - 2021/01/31 團隊共發出 9008 個 PR <sup>[1](#foot-note-1)</sup>，有經過我 Code Review 的數量為 2979 <sup>[2](#foot-note-2)</sup>，約 33%
- 建置可承受 10,000 人同時連線的 WebSocket Server
   - 使用 Golang 撰寫、使用 Docker 佈署至 AWS Elastic Container Service (ECS)
   - 利用 Redis 加上 pub/sub 功能，讓 Rails 後端可以直接推送訊息給前端
   - 部分 service 死掉不會影響整個系統 (High Available System)
- 優化後端程式維護性及效能
   - 增加必要的 DataBase index 及減少不必要的 DataBase Index
   - 處理 Race Condition
   - 導入 Design Pattern 重構程式，增加可維護性
- 撰寫 JMeter 腳本執行壓力測試，協助同仁估算活動舉辦時需要的 Infra 大小，確保活動順利進行
- 導入 Webpack 讓前端可以使用 ES6 語法及 babel polyfill，讓開發更快、更好維護
- 導入 React 至遊戲端，讓效能更好、開發更快、程式更好維護
- 前端導入靜態檢查工具，減少開發時間，讓程式更好維護
   - ESLint + scss-lint
- 製作各種遊戲的 UI
   - 競賽之盾的教師設定：
   - 鍛造系統：
   - 任務書右半部及動畫：
   - 累計登入：
- 舉辦程式讀書加強團隊專業知識

### 自由工作者 April, 2016 ~ Dec, 2016

- 自學 Ruby on Rails
- 使用 Ruby on Rails 開發貸款及人員管理系統 (接案)

### 盈正豫順 Dec, 2011 ~ Mar, 2016

- 開發 60kw 三相不斷電併聯系統
   - 使用 c 語言在 TMS320F2808 平台開發
- 使 2 台穩定併聯提昇至 6 台穩定併聯，輸出功率提昇至 3 倍
- 開發 20kw 熱插拔三相不斷電併聯系統，可線上增減機器數量，讓現場維修更方便、快速
- 進行實驗及撰寫測試報告，確保系統可以在高低電壓、負載、溫度等等情境正常運作
- 導入 git 做版本控管，讓程式更容易維護

## 學歷

高雄應用科技大學電機工程所碩士 2008 ~ 2010

高雄應用科技大學電機工程系學士 2004 ~ 2008

### footnote:

<a name="foot-note-1">1</a>: 在 Pull Request 列表搜尋 `is:pr reviewed-by:kakas`

<a name="foot-note-2">2</a>: 在 Pull Request 列表搜尋 `is:pr created:>2017-01-03`
