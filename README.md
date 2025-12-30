# Landing

一頁式「D博士數位行銷顧問」網站，包含 Hero、關於、服務、專長、案例與聯絡區塊，採用淺色風格並準備好部署到 GitHub Pages。

## 本機預覽

直接以瀏覽器開啟 `index.html`，或使用簡單的靜態伺服器：

```bash
python -m http.server 8000
```

再造訪 http://localhost:8000。

## 部署

每次推送到 `work` 分支會透過 [`.github/workflows/deploy.yml`](.github/workflows/deploy.yml) 自動發布至 GitHub Pages。

1. 在 repository Settings 中啟用 GitHub Pages 並選擇「GitHub Actions」來源。
2. 推送到 `work`（或手動觸發 workflow），網站會部署到 `github-pages` 環境，網址會顯示在 workflow summary。
