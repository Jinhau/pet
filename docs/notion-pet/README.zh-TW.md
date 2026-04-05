# Notion 可嵌入版電子寵物

這個資料夾已經整理成 GitHub Pages 可直接發布的靜態 widget。

- 網頁入口：`docs/notion-pet/index.html`
- GitHub Pages workflow：`.github/workflows/pages.yml`
- Pages 根入口：`docs/index.html`
- 儲存方式：瀏覽器 `localStorage`
- 介面語言：繁體中文
- 支援功能：改名、切換型態、餵食、玩耍、休息、清潔、重置

## GitHub Pages 發布方式

1. 把這個 repo 推到你的 GitHub。
2. 到專案的 `Settings > Pages`。
3. 把來源設成 `GitHub Actions`。
4. 推送到 `main` 後，`Deploy GitHub Pages` workflow 會自動發布 `docs/`。

## 公開網址怎麼算

如果你的 GitHub 使用者名稱是：

`Jinhau`

repo 名稱是：

`pet`

那 GitHub Pages 會是：

`https://jinhau.github.io/pet/`

電子寵物頁面就是：

`https://jinhau.github.io/pet/notion-pet/`

嵌入 Notion 建議用這個版本：

`https://jinhau.github.io/pet/notion-pet/?compact=1`

## Notion 使用方式

1. 複製公開網址。
2. 到 Notion 頁面輸入 `/embed`。
3. 貼上 `https://jinhau.github.io/pet/notion-pet/?compact=1`。

## 注意

- Notion 只能嵌入公開 `https` 網址，不能直接嵌本機檔案。
- 這個 widget 的狀態存在當前瀏覽器的 `localStorage`，不會和桌面版共用。
