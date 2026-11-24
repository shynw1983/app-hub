# App Labs — 个人兴趣软件发布下载中心

极简零依赖的静态发布站，专为部署在 Vercel 上统一分发所有个人兴趣 App（Android APK / macOS / Web 工具等）。

## 如何上架新 App 或发新版

1. 上传新安装包（推荐放 Vercel Blob 或 GitHub Releases；≤ 100MB 也可直接放入 `downloads/` 目录）。
2. 编辑 `data/apps.json`，在 `apps` 数组中添加或更新版本号、下载链接与更新日志。
3. 执行部署命令：
   ```bash
   npx vercel --prod
   ```
