# Ascenda Site

静态官网源码，托管在 **Cloudflare Pages**，绑定自定义域名 `ascenda.asia`。

- 入口：`index.html`
- 产品图：`assets/web/`
- 联系表单：接入 Web3Forms，提交后邮件发送至 sales@ascenda.asia

## 部署方式

Cloudflare Pages 已连接本仓库，推送到 main 分支会自动构建部署，约 1 分钟全球生效。

## 更新流程

```bash
git add -A && git commit -m "update" && git push
```
