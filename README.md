# Dev Lab — 个人开发工具导航

由 Claude AI 驱动的个人开发工具集导航页，托管于 GitHub Pages。

## 访问方式

部署后访问：

```
https://YOUR_USERNAME.github.io/dev-hub/?user=YOUR_USERNAME
```

将 `YOUR_USERNAME` 替换为你的 GitHub 用户名，页面会自动将所有项目链接更新为你的地址。

收藏带有 `?user=` 参数的 URL，下次访问无需重新输入。

## 包含项目

| 项目 | 描述 |
|------|------|
| 🤖 AI 周刊机器人 | 每周自动抓取技术资讯，Claude 精选摘要 |
| 📡 技术雷达 | 个人技术判断可视化地图 |
| 🃏 代码学习卡片 | 每日从 Star 仓库生成学习卡片 |
| ⚰️ Bug 墓地 | Issue 关闭时 Claude 自动生成墓志铭 |

## 本地预览

直接在浏览器打开 `index.html`，或使用任意静态服务器：

```bash
npx serve .
```

## 部署

运行根目录的 `deploy-all.command` 脚本，一键部署全部项目到 GitHub Pages。
