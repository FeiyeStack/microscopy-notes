# 光学显微镜原理 · 图文电子书

本目录是 `build_pages.py` 生成的静态站，可托管到 Cloudflare Pages / GitHub Pages / Gitee Pages。

## 部署

**Cloudflare Pages（推荐，免费无限带宽）**

- Git 集成：把本仓库推到 GitHub/GitLab，Pages 里选该仓库，Build command 留空，Output directory 填 `/`。
- 直接上传：`pnpm dlx wrangler pages deploy <不含 .git 的目录> --project-name microscopy-book`。

## 素材说明

- 视频与幻灯片截图来自 [iBiology Microscopy Series](https://www.ibiology.org/online-biology-courses/microscopy-series/)，许可 CC BY-NC-ND 3.0；
- 中文解说、排版、9 张关系图为本次整理所写/所绘；
- 仅供个人学习，不做商业使用。
