# 飞书导出助手官网

这是飞书导出助手 Chrome 扩展的官方网站。

## 文件结构

```
├── index.html      # 主页面
├── styles.css      # 样式文件
├── script.js       # 交互脚本
├── vercel.json     # Vercel 部署配置
├── cloudflare.json # Cloudflare 部署配置
├── 404.html        # 404 页面
└── README.md       # 本文件
```

## 部署

### Vercel
直接将此仓库导入 Vercel 即可自动部署。

### Cloudflare Pages
在 Cloudflare Pages 中连接此仓库，无需额外配置。

## 本地预览

```bash
python -m http.server 8080
```

然后访问 http://localhost:8080

## 技术栈

- 纯 HTML/CSS/JS，无框架依赖
- 拟物风格设计（白玉黑墨配色）
- 响应式布局
- 优化的性能和加载速度
