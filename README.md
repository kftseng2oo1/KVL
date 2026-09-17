# 迴路求解 KVL/KCL PWA

檔案：index.html、manifest.json、sw.js、icon-192.png、icon-512.png（扁平結構）。

## 部署到 GitHub Pages
1. 把五個檔案放到 repo 根目錄（或任一子資料夾，路徑全為相對路徑）。
2. Settings → Pages 啟用後開啟網址，iOS Safari 用「加入主畫面」即可離線使用。

## 更新
修改 index.html 後把 sw.js 裡的 `CACHE='kvlkcl-v1'` 版本號加一，舊快取會在下次開啟時清除。
