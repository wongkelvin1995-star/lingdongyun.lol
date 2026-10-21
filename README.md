# 灵动云官网 · lingdongyun.lol

灵动云（lingdongyun）官网落地页，纯静态网页，无需构建。

## 文件

| 文件 | 说明 |
|---|---|
| `index.html` | 首页（含 SEO 标签、结构化数据、10 条常见问题） |
| `robots.txt` | 搜索引擎抓取规则 |
| `sitemap.xml` | 站点地图，提交到 Google Search Console 与百度搜索资源平台 |
| `logo.svg` / `logo-512.png` | 品牌 LOGO（矢量 / 512px） |
| `favicon.svg` / `apple-touch-icon.png` | 浏览器标签页图标 / iPhone 主屏幕图标 |
| `CNAME` | GitHub Pages 自定义域名（lingdongyun.lol） |

## 部署

- **GitHub Pages**：仓库 Settings → Pages → Source 选 `main` 分支根目录；在域名服务商把 lingdongyun.lol 解析到 GitHub Pages。
- **其他主机 / Cloudflare Pages / Vercel**：直接部署仓库根目录即可。

## 修改订购链接

所有「注册 / 登录」「选择套餐」「选择流量包」「前往官网获取客户端」按钮都指向同一个订购地址，在 `index.html` 中全局替换即可。
