# 順序

npm init --yes
npm i -D eslint nodemon
npm i linebot axios dotenv  
初始化 eslint=> 資料夾下直接是 package.json => 可以直接按 f1 eslint /另外包資料夾的話 => npx eslint --init
npm i cheerio
連接傅 3000 的地址 更新 lineURL

npm i node-schedule

# 筆記

package.json 裡的陣列 'script'
predev
dev
postdev

在終端機打 npm run dev
會先執行 predev
在執行 dev
最後執行 postdev

bot.listen('/', process.env.PORT || 3000, () => {
console.log('機器人啟動')
})

npn i cheerio =>用 jq 語法在 node.js 環境下解析 html
event.reply 只能用一次
所以先提取成一個陣列再一次 reply

new URL(相對路徑,主網域網址).href =>把兩個路徑串聯再一起

npm i node-schedule => 自己更新程式碼套件

# crontab => The quick and simple editor for cron schedule expressions by Cronitor -> 快速找出生成更新碼的語法

https://crontab.guru/

# 雲端

https://render.com/
