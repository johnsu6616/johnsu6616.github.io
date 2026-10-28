# johnsu6616.github.io

個人 GitHub Pages 網站，使用 [Jekyll](https://jekyllrb.com/) 搭配 [Midnight](https://github.com/pages-themes/midnight) 主題建置。

🌐 網站網址：<https://johnsu6616.github.io>

## 專案結構

```
.
├── _config.yml          # Jekyll 設定（使用 remote theme：pages-themes/midnight）
├── Gemfile              # Ruby 套件設定（github-pages）
├── index.md             # 首頁
├── another-page.md      # 範例子頁面
├── 231228.md            # 文章／筆記
├── _layouts/            # 頁面版型
├── _includes/           # 共用 HTML 片段（head、GA、主題色）
├── _sass/               # 樣式（SCSS）
├── assets/              # CSS、JS、字型、圖片
├── script/              # 主題附帶的建置／驗證腳本
└── docs/                # 主題附帶的貢獻與支援說明
```

## 新增頁面

在根目錄建立 `.md` 檔，開頭加上 front matter：

```markdown
---
layout: default
title: 頁面標題
---

這裡寫內容。
```

推送到 `main` 分支後，GitHub Pages 會自動建置並發布，網址為 `https://johnsu6616.github.io/檔名.html`。

## 本機預覽

需先安裝 Ruby 與 Bundler：

```bash
bundle install
bundle exec jekyll serve
```

接著開啟 <http://localhost:4000>。

## 授權

主題程式碼來自 [pages-themes/midnight](https://github.com/pages-themes/midnight)，依 [CC0 1.0](LICENSE) 授權。
