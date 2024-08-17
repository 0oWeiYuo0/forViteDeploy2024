--Vue--
ESLint 會讓程式碼更符合規範
Prettier 格式化工具，排版用
Vue DevTool 會讓編碼器下方出會除錯工具
public 會放一些不被編譯的東西 例如圖片
要給其他人部屬就要 build

--部屬--
npm run build 後會多一個 dist 資料夾
嵌入前記得看一下變動的檔案，以免錯誤
在 Source Control 輸入 update code 就可以嵌入了(記得按加號)
編譯後可能會換路徑，在絕對路徑上換太麻煩，可以打開 vite.config.js
在 defineConfig 裡面輸入 base: '/',(這是預設路徑)
後面會用到 Vue router 的技術，所以記得輸入完建議前後都給/ 像 base: '/Server/'
--git--

Source Control(VSCode 左邊工具覽第三個)
會有一個初始化存放庫
在 Staged Changes 旁邊會有一個加號，確認都加進去後可以初始化了
初始化　-> git init
嵌入 -> update code
