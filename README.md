# UAV Lab Wiki｜實驗室新生無人機入門筆記

這是一個準備給剛加入實驗室、第一次接觸 UAV（無人飛行載具）的學弟妹看的技術筆記網站。內容從 Pixhawk、ArduPilot、飛行模式這些常遇到的名詞開始，盡量用簡單但可查證的方式說明。

這個專案也用來練習第九週課程的 **Agentic Work（代理式工作）**：把網站的規則寫成 `AGENTS.md`，讓 AI 之後能照著同一套方法新增頁面，並更新首頁索引。

## 看網站

- 本機：下載或解壓縮專案後，直接開啟 `index.html`。
- GitHub Pages：[開啟 UAV Lab Wiki 公開網站](https://cyw-ericw.github.io/uav-lab-wiki/)

## 已發布文章

- [Pixhawk 是什麼？](pages/pixhawk.html) — 認識飛控硬體、韌體與地面站的分工。
- [Stabilize、AltHold、Loiter 差在哪？](pages/flight-modes.html) — 從姿態、高度到位置控制的差異。

- [Pre-Arm 錯誤排查入門](pages/prearm.html) — 解鎖前檢查、常見錯誤類型與官方排查入口。

> 第二階段已依照 AGENTS.md 新增 Pre-Arm 文章，並同步更新首頁卡片、文章數量及本清單。

> 第三階段（已完成）：已將完整專案上傳 GitHub，並透過 GitHub Pages 公開網站。已確認公開首頁及三篇技術文章可以正常瀏覽。
## 專案結構

```text
.
├── AGENTS.md
├── README.md
├── index.html
├── pages/
│   ├── pixhawk.html
│   ├── flight-modes.html
│   └── prearm.html
└── assets/
    ├── css/style.css
    └── img/uav-mark.svg
```

## 後續如何新增文章

1. 先請 AI 閱讀根目錄 `AGENTS.md`。
2. 再提出文章名稱，並確認沒有重複主題（Pre-Arm 已有文章）。
3. AI 應建立 `pages/` 新頁面、更新根目錄 `index.html` 的文章卡片，並更新這份 README。
4. 在瀏覽器逐頁檢查後，再將完整專案提交 GitHub。

## 使用與安全提醒

這是個人整理的入門學習筆記，不是 ArduPilot、Holybro 的官方操作手冊。涉及接線、電池、解鎖或實際飛行時，請以對應型號、韌體版本的官方文件及實驗室安全規範為準。
