# YangMultiverse — 多元宇宙微缩生态互动小游戏

包含 **🌿 春日草原**、**🏜️ 沙漠绿洲** 与 **🌲 森林秘境** 三个独立 3D 微缩生态宇宙，可直接部署到 GitHub Pages 或通过 `<iframe>` 嵌入个人网站。

## GitHub Pages 快速部署

1. 将本压缩包解压后的全部文件（`index.html`、`.nojekyll`、`README.md`）上传到 GitHub 仓库根目录。
2. 打开仓库 **Settings → Pages**，在 **Build and deployment** 中选择 **Deploy from a branch**，分支选 `main`、目录选 `/ (root)` 并保存。
3. 等待约 1 分钟即可通过 `https://<你的用户名>.github.io/<仓库名>/` 访问。

## 支持的 URL 参数

- `?world=meadow` / `?world=desert` / `?world=forest`：指定默认进入的宇宙
- `?pure=1`：纯净嵌入模式（隐藏顶部切换栏与控制按钮，适合个人网站背景或 iframe 嵌入）
- `?zoom=1.2`：自定义初始画面缩放倍率（范围 `0.85` – `2.20`）
