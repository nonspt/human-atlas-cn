# 人体解剖图谱 · GitHub Pages 发布目录

此目录是可直接发布的静态站点，独立于本地的 `human/human-atlas-cn` 源码目录。它包含中文界面及两套完整的三维解剖模型。目标仓库为 `nonspt/human-atlas-cn`，页面地址为 `https://nonspt.github.io/human-atlas-cn/`。

发布时将本目录作为新仓库的根目录，默认分支设为 `main`，然后在仓库 **Settings → Pages → Build and deployment** 中选择 **GitHub Actions**。首次推送及后续推送会触发 `.github/workflows/pages.yml`。工作流从固定版本的原项目获取三维模型，因此仓库本身只需保存页面文件；部署后的站点包含完整模型。

网页代码遵循 [MIT 许可证](LICENSE)。三维数据的来源与许可见 [ATTRIBUTION.md](ATTRIBUTION.md)。本图谱仅供学习，不用于临床诊断或手术规划。
