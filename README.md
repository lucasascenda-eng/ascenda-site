# Ascenda Site

静态官网，托管在 GitHub Pages，绑定自定义域名 `ascenda.asia`。

- 入口：`index.html`
- 产品图：`assets/web/`
- `CNAME`：GitHub Pages 自定义域名配置（内容为 ascenda.asia）
- `.nojekyll`：跳过 Jekyll 处理，按原样发布

## 更新流程

改完文件后：

```bash
git add -A && git commit -m "update" && git push
```

GitHub Pages 会在约 1 分钟内自动重新发布。
