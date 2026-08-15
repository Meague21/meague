# 烧脑数学 · GitHub Pages 部署

这个文件夹用于把「烧脑数学」部署到 GitHub Pages，得到一个固定网址，刷新即可用最新版。

## 一次性设置（需要你操作）
1. 在 GitHub 新建一个仓库（如 `shaonao-math`），Settings → Pages → Source 选 `main` 分支 / `/ (root)`。
2. 生成一个 Personal Access Token（Settings → Developer settings → Personal access tokens，勾选 `repo` 权限）。
3. 把仓库地址和 Token 告诉千问办公助理，之后每次迭代它会自动推送，你只需刷新网址。

## 文件说明
- `index.html`：应用本体（单文件，离线也能打开）。每次迭代会被更新。
