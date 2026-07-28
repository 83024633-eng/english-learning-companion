# 英语·语文·数学 伴学应用

多学科学习陪伴软件 — 英语口语单词 + 语文古诗词 + 数学思维训练

## 部署方式

本项目为纯静态 HTML/CSS/JS 应用，通过 Vercel 部署。

### 文件说明

| 文件 | 说明 |
|------|------|
| `index.html` | 主应用文件 |
| `sw.js` | Service Worker（离线缓存） |
| `manifest.json` | PWA 配置（添加到主屏幕） |
| `qr-code.svg` | 二维码图标 |
| `vercel.json` | Vercel 部署配置 |

### 更新应用

修改 `index.html` 后，推送到 GitHub main 分支，Vercel 会自动部署。

## 版本

当前版本：v39
