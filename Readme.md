# 教學
需安裝 nodedjs
```bash
node -v # 查看 nodejs 版本
v16.13.2
```

## 開始
假設今天要發行五張 NFT，並擁有開關，可自由切換盲盒功能，我們要進階處理圖片部分
會配合使用到 Pinate

1. 蒐集五張圖片放到 image 資料夾，並依序命名檔案 0.jpg, 1.jpg, 2.jpg... 5.jpg
圖片副檔案都要一致，如果是 jpg，全部都要是 jpg

2. 蒐集一張盲盒圖
專案有放一張 unpack.jpg 盲盒圖

3. 自訂盲盒時的 json
unpack.json：當發行 NFT 仍尚未解盲狀態，會讀取此 json 格式

4. 編輯 `gereratorJson.js`
5. 執行 node gereratorJson.js，會自動產生五組 NFT json
6. 打包上傳到 Pinate

- image資料夾
- 單獨上傳一張盲盒圖
- 單圖上傳一張盲盒 json

7. 部署智能合約
