# Waline Backend

部署到 Vercel 的 Waline 评论后端（无依赖版本）

## 部署

1. GitHub 推送此仓库
2. Vercel 导入仓库
3. 自动部署（无需环境变量）
4. 获取分配的 URL

## 使用

在 Jekyll 博客的 `_config.yml` 中配置：

```yaml
comments:
  waline: true
  waline_serverUrl: 'https://your-vercel-url.vercel.app'
```
