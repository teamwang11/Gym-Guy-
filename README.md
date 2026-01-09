# GymScan Pro (PWA 安装版)

## 1) 如何在手机上“像 App 一样安装”
前提：必须用 **HTTPS**（或本机 localhost）打开。

### 方案 A：最快部署（推荐）
- GitHub Pages / Vercel / Netlify 任意一个都可以
- 把本目录里的文件原样上传/部署
- 得到一个 https://xxxx 的链接

iPhone（Safari）：
- 打开链接 → 分享 → “添加到主屏幕”

Android（Chrome）：
- 打开链接 → “安装应用 / Add to Home screen”

## 2) 本地测试（电脑）
在本目录运行一个静态服务器，例如：
- Python: `python -m http.server 8080`
然后手机和电脑在同一 Wi‑Fi 下访问电脑的局域网地址（注意：PWA 安装通常仍需要 https，iOS 对 http 更严格；Android 在部分情况下可用）。

## 3) 文件说明
- index.html：主页面（已加入 manifest / 全屏 / SW 注册 / 启动画面）
- manifest.json：PWA 配置
- sw.js：离线缓存 Service Worker
- icons/：图标与启动图资源（含一张 splash 参考图）
