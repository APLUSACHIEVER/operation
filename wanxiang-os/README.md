# 万象 OS｜个人数字工具箱

品牌口号：你的数字世界，由你定义。

本应用独立放在 `wanxiang-os/` 目录，不修改运营中心原有首页和功能。

## 文件
- `index.html`：工具箱前端
- `manifest.webmanifest`：PWA 安装信息
- `icon.svg`：网络节点品牌图标
- `sw.js`：应用外壳离线缓存

## 使用
部署后访问 `/operation/wanxiang-os/`。手机浏览器可通过“添加到主屏幕”安装。

## 数据
工具数据保存在当前浏览器 localStorage；使用页面内“导出”生成 JSON 备份。不会跨设备自动同步。外部网站和 AI 服务仍需要网络。

## 注意
GitHub Pages 必须启用 HTTPS。请在部署后验证 PWA 安装和离线启动；浏览器对 SVG 应用图标的安装支持可能因平台而异。