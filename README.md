## 串接智能合約實戰
KryptoCamp NFT 即將開賣！
智能合約已完成並部署至測試鏈上，你能幫 KryptoCamp 完成販賣 NFT 網站嗎？
在網站上線前，總共需要完成三個功能
![](https://i.imgur.com/WLDl3e2.jpg)

## 作業說明
繳交作業請做完基本題，進階題可做可不做

### 基本題
1. 使用者可以連接 Metamask 錢包
2. 讀取智能合約的 totalSupply，並寫入畫面上
3. 點擊 mint 按鈕，會呼叫智能合約的 mint Function，讓使用者可以購買 NFT

### 進階題
1. 當使用者 Metamask 錢包不在 Goerli測試鏈時，可跳出狐狸視窗半強迫性，請使用者切換至 Goerli 鏈
2. 將前端網站部署至 Vercel, Netlify 等網站，可直接透過網址進入 KryptoCamp 購買 NFT


## 作業詳細說明
1. 本作業採 React 方式，需用 git clone 下來後並安裝相依套件，在本地上跑 localhost

```bash
git clone git@github.com:Krypto-Camp/batch4-week6-mint.git // 須設定 github ssh key
cd mint-website // 移動到專案 
yarn install // 安裝相依套件
yarn start // 開啟本地
yarn build // 打包，設定部署到正式環境時需執行此指令
```

2. 智能合約已部署至鏈上，智能合約程式碼在 `contracts/KryptoCampNft.sol`
3. 前端畫面已刻完，請全域搜尋 TODO: 已標記需完成的三個 function
4. 若對 git 不熟的同學，請再回到平台複習 git 相關影片
5. 由於實體課程已結束，作業講解會以平台錄影方式教學
6. 副教練會實測專案，確認是否可完成基本功能
7. 部署部分可參考平台前面錄影的 Netlify，或自行試試部署至 Vercel

#### 繳交作業
提醒，作業標題：請填寫你的學號 （Discord KryptoCamp 的名稱），例：Hazel | C0031601

以 Hackmd 方式繳交
- 提供你的 github 連結：
- 若有部署前端，請提交你的網址：
