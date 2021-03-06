# GraphQL

- [GraphQL | 一種為你的API 而生的查詢語言](https://graphql.cn/)
- GraphQL 既是一種用於 API 的查詢語言也是一個滿足你數據查詢的運行時。 GraphQL 對你的 API 中的數據提供了一套易於理解的完整描述，使得客戶端能夠準確地獲得它需要的數據，而且沒有任何冗餘，也讓 API 更容易地隨著時間推移而演進，還能用於構建強大的開發者工具。
- GraphQL 的出現主要是為了要解決 Web/Mobile 端不斷增加的 API 請求所衍生的問題。由於 RESTful 最大的功能在於很有效的前後端分離和建立 stateless 請求，然而 RESTful API 的資源設計上比較偏向單方面的互動，若是有著複雜資源間的關聯就會出現請求次數過多，遇到不少的瓶頸。
- 根據 GraphQL 官方網站的定義，GraphQL 是一個資料查詢語言和 runtime。Query responses 是由 client 所宣告決定，而非 server 端，且只會回傳 client 所宣告的內容。此外，GraphQL 是強型別（strong type）且可以容易使用階層（hierarchical）和處理複雜的資料關連性，並更容易讓前端工程師和產品工程師定義 Schema 來使用，賦予前端對於資料的制定能力。
  
# GraphQL 主要由以下元件構成：

1. 類別系統（Type System）
2. 查詢語言（Query Language）：在 Operations 中 query 只讀取資料而 mutation 寫入操作
3. 執行語意（Execution Semantics）
4. 靜態驗證（Static Validation）
5. 類別檢查（Type Introspection）

- 一般 RESTful 在取用資源時會對應到 HTTP 中 GET、POST、DELETE、PUT 等方法，並以 URL 對應的方式去取得資源，
- 例如：取得 id 為 3500401 的使用者資料：GET /users/3500401

- [Apollo Client ](https://www.apollographql.com/client)
- Apollo Client 則是中型的 GraphQL Client，支援 React、Vue、Angular 2 等等的框架。它是由目前 GraphQL 最大的社群組織 - Apollo 所維護，這個社群組織囊跨前後端以及工具的開發，並擁抱開源，他們最早的架構設計圖稿也能在 Github 上看到。
- [透過 apollo-server 在 10 分鐘內打造你的第一個 GraphQL server](https://jigsawye.com/2018/07/22/getting-started-apollo-server/)
- [從零開始學 ReactJS（ReactJS 101）是一本希望讓初學者一看就懂的 ReactJS 中文入門教學書，由淺入深學習 ReactJS 生態系 (Flux, Redux, React Router, ImmutableJS, React Native, Relay/GraphQL etc.)](https://github.com/kdchang/reactjs101)

### 以下是 GraphQL 入門系列的目錄：
1. [GraphQL 入門 Part I - 從 REST 到 GraphQL](https://ithelp.ithome.com.tw/articles/10188294)
2. [GraphQL 入門 Part II - 實作 Schema & Type](http://ithelp.ithome.com.tw/articles/10188388)
3. [GraphQL 入門 Part III - Query](http://ithelp.ithome.com.tw/articles/10188417)
4. [GraphQL 入門 Part IV - Mutation](http://ithelp.ithome.com.tw/articles/10188475)
5. [GraphQL 入門 Part V - Fragment](http://ithelp.ithome.com.tw/articles/10188571)