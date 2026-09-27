# w0nderful666 个人主页

极简终端风静态个人主页：默认英文和深色，支持中英文与深浅主题切换。无构建依赖，不调用外部 API，不加载外部字体。

## 内容

项目介绍根据 2026-09-27 的公开仓库 README 整理：

- [AeMusic](https://github.com/w0nderful666/AeMusic)
- [WF-1000XM5 Spatial Audio](https://github.com/w0nderful666/wf1000xm5-spatial-audio-android)
- [FxxKPDF](https://github.com/w0nderful666/FxxKPDF)

项目为手动精选，不自动同步 GitHub。技术栈依据项目整理，不代表职业履历。

## 预览

直接用浏览器打开 `index.html`，或执行 `python3 preview_server.py` 后访问 `http://localhost:8080/`。服务监听所有 IPv4 网卡，仅提供首页，不提供目录列表。

## 发布与维护

阅读 [DEPLOYMENT.md](DEPLOYMENT.md)。仓库包含 GitHub Pages Actions 配置，推送至 main 可触发部署；须先在仓库设置启用 GitHub Actions 作为 Pages 来源。只有 `index.html` 被发布，说明文档和预览服务不进入站点产物。

新项目需修改页面和双语字典；自动部署不等于自动添加项目。
