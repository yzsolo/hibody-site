# HiBody 展示站

无需安装依赖或构建。首页、支持页和隐私政策均为静态文件。支持页和隐私政策沿用现有 HiBody 文案。首页插画与活动图表是概念示意，不是应用截图或医学图谱。

## 本地预览

在本目录运行 `python3 -m http.server 4173`，访问 http://localhost:4173。

## GitHub Pages

将本目录的内容作为独立仓库的根目录上传到 `main` 分支（包括 `.github`）。在仓库 Settings → Pages → Build and deployment 中选择 GitHub Actions。推送后由内置工作流自动发布。本仓库按要求保持 Private。当前账号的 Pages 设置提示需要升级套餐；请勿为启用 Pages 将仓库改为公开。升级至支持私有仓库 Pages 的套餐并配置发布源后即可发布。

工作流仅发布 HTML、CSS 和 assets，不发布说明文件或其他项目资料。所有站内链接均使用相对路径，兼容仓库子路径和独立域名。

## 自定义域名

确认域名后，在 Pages 设置中配置 Custom domain，并按 GitHub 官方文档配置 DNS、验证域名所有权和开启 HTTPS：https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site

可在根目录添加 `CNAME` 文件，内容仅为实际域名。不要写协议或路径。当前未添加虚构域名或 App Store 下载地址；获得实际商店链接后再添加下载入口。
