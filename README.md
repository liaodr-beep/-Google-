# 抓寶中醫師｜Google 智慧早報設定精靈

開啟 `index.html` 即可使用。此網站是靜態、無後端的設定導引頁；使用者填入的設定只用於產生可複製的 ChatGPT 指令，不會送至網站伺服器。

## 公開網址
將 `index.html` 部署到 GitHub Pages、Netlify 或其他靜態網站主機，即可取得公開連結。此 ZIP 本身不是已發布的網址。

## 自訂 GPT
在 https://chatgpt.com/gpts/editor 建立自訂 GPT，名稱設為「抓寶中醫師｜Google 智慧早報設定精靈」，將 `SKILL.md` 的指示貼入 GPT Instructions，測試後依帳號支援情況發布分享連結。自訂 GPT 不等於可直接存取所有使用者的 Google 資料，亦不保證能自動寄出排程郵件。

## 注意
網站不會連接 Google Calendar、Gmail 或建立排程。這些操作需使用者在 ChatGPT 內自行授權並核實工具支援；必要時改用 Google Apps Script 等實際可執行的排程寄信方式。
