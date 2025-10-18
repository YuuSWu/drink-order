Firebase Realtime Database 版部署說明 (雙加料下拉選項)
包含檔案：order.html, admin.html, firebase.rules.json, README.txt

要點：
- 兩個加料下拉皆預設為「不加料」，可選相同或不同的加料，系統會把兩個加料價格相加。
- admin.html 用來新增飲品、尺寸、加料、甜度與冰塊（會寫入 settings/*）。
- order.html 從 settings/* 讀取設定，顧客可下單，訂單寫入 orders/*。

快速測試：
1. 在 Firebase Console > Realtime Database，貼上 firebase.rules.json 的內容（或暫時開寫入）。
2. 開啟 admin.html，新增一兩個飲品（帶尺寸與價格）、新增 1~3 個加料（含價格）、新增甜度與冰塊選項。
3. 另開瀏覽器或裝置開 order.html，確認能選商品並送出訂單，後台會即時顯示。

如需我：
A) 幫你把檔案打包成 ZIP 並給下載（我會再嘗試）
B) 幫你把 order.html 部署到 Netlify（我會提供步驟或代為示範）
C) 幫你做 admin 前端密碼保護或示範如何設定 admin custom claim
請回覆 A / B / C / 無。
