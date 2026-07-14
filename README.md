# GitHub Pages 部署方式

1. 將 `index.html` 與 `.nojekyll` 上傳到 GitHub Repository 根目錄。
2. 進入 Repository 的 **Settings → Pages**。
3. 在 **Build and deployment** 選擇 **Deploy from a branch**。
4. Branch 選擇 `main`，資料夾選擇 `/(root)`，按 **Save**。
5. 等待約 1–3 分鐘後，使用 GitHub Pages 提供的網址開啟。

請勿使用下列網址作為網站網址：
- `github.com/.../blob/.../index.html`（這是程式碼檢視頁）
- `raw.githubusercontent.com/...`（可能以純文字或下載方式顯示）

正確網址通常為：
`https://<帳號>.github.io/<Repository名稱>/`
