# 假勤追蹤器

員工假勤紀錄追蹤工具，支援假別管理與出勤狀況一覽。

**線上版本：** https://ll-rd-a392c.web.app

## 技術架構

- 純靜態單頁應用（HTML / JavaScript）
- 託管於 Firebase Hosting

## 自動部署

本專案透過 GitHub Actions 自動部署至 Firebase Hosting：

- **push 到 `master`** → 自動部署至正式環境
- **開 Pull Request** → 自動建立預覽連結（顯示於 PR 留言）

## 本地開發

直接用瀏覽器開啟 `index.html`，或透過本地伺服器：

```bash
npx serve .
```
