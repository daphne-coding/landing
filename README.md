# Landing

一頁式數位行銷作品集，風格參考 Browny Demo，並預設部署至 GitHub Pages。

## 本機預覽

直接開啟 `index.html` 或啟動簡易靜態伺服器：

```bash
python -m http.server 8000
```

接著造訪 http://localhost:8000。

## 部署

GitHub Actions 會在 `work` 分支每次推送時透過 [`.github/workflows/deploy.yml`](.github/workflows/deploy.yml) 發布至 GitHub Pages。

1. 在 repo 設定中啟用 GitHub Pages，來源選擇「GitHub Actions」。
2. 推送到 `work`（或手動觸發 workflow）。頁面會部署到 `github-pages` 環境，網址會顯示在工作流程摘要。
