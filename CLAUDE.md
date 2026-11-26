# 給在這個專案工作的 AI 助手

這個專案只剩一個轉址頁：`index.html` 把舊網址導到 **books.twranger.com**。購書系統真正的程式在 `twranger/Haidian-Library-Book-Purchase-System-Private`，要改功能或畫面請到那裡。

這個專案不是網站，twranger 的《網站製作規範》（`WEB-STANDARDS.md`，放在各網站專案裡，例如 `twranger/haidian-soundscape`）大部分用不到。
以下幾條是所有專案共通的，這裡一樣適用：

- 金鑰、密碼、授權碼不放進專案，用 GitHub Secrets 或環境變數。
- 產生出來的檔案不要手動改，改來源再重新產生。
- 回報時說清楚哪些實際驗證過、哪些沒有；量不到的數字不要報。
- 之後如果加上給人看的畫面，就把 `WEB-STANDARDS.md` 複製進來並在這一頁用 `@WEB-STANDARDS.md` 載入。

## 這個專案怎麼運作

- 只有 `index.html`，部署在 GitHub Pages。除非轉址的目的地改了，否則不需要動。

## 和其他對話串協調

對話串之間不能直接傳訊息。做了會影響別人的決定就寫進這一頁；合併前先把 `origin/main` 併進自己的分支再測一次。
推到 `main` 就會直接上線，要等使用者明確說「合併」。
