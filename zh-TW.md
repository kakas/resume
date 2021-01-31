蕭錦成 (Hsiao, Chin-Cheng)
Full-Stack Web Developer
Taipei, Taiwan, shrimptrain@gmail.com

## 工作經歷

### 幫你優 (BonioO Inc.) Jan, 2017 - Present

- 開發遊戲相關功能，使用 Ruby on Rails 及 Rspec 開發後端 API，前端使用 React、Redux 開發。
- 導入 Webpack 讓前端可以使用 ES6 語法及 babel polyfill，讓開發更快、更好維護
- 審查 Pull Request，把關商業邏輯及程式碼品質
   -  從 2017/01/03 團隊共發出 9008 個 PR <sup>[1](#foot-note-1)</sup>，Code Review 數量為 2979 <sup>[2](#foot-note-2)</sup>，Review 約 33% 的 Pull Request
- 撰寫 JMeter 執行壓力測試，協助同仁估算活動舉辦時需要的 Infra 大小，確保活動順利進行
- 建置 WebSocket Server (使用 golang 撰寫)，2 * t3.medium(4 G memory, 2 CPU) 至少可承受 10,000 同時連線 (使用 JMeter 測試)
   - 使用 Golang 撰寫、使用 Docker 佈署至 AWS ECS
   - 加入 pub/sub 機制，讓 Rails 後端可以直接推送訊息給前端
   - 部分 service 死掉不會影響整個系統 (High Available)
- 將舊有 jQuery 撰寫的遊戲 UI，使用 React 改寫，增進前端效能及可維護性
- 優化後端程式維護性及效能
   - 增加必要的 DataBase index 及減少不必要的 DataBase Index
   - 使用 Template Method 重構道具使用的程式，使其更好維護
   - 導入 Form Object 讓程式更好維護
- 前端導入靜態檢查工具，減少開發時間，增進程式可維護性 (eslint + scsslint)
   - ESLint + scss-lint
- 製作各種遊戲的 UI
   - 競賽之盾：
   - 鍛造系統的：
   - 任務書：
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

footnote:
<a name="foot-note-1">1</a>: 在 Pull Request 列表搜尋 `is:pr reviewed-by:kakas`
<a name="foot-note-2">2</a>: 在 Pull Request 列表搜尋 `is:pr created:>2017-01-03`