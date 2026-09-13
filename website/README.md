# tCam 官网源码

`website/tcam/` 管理 aizst.com/tcam 的静态源码。2026-09-13 从 tCam 仓库未跟踪的同名目录复制 11 个文件，SHA-256 逐一匹配；原件保留。本次入库不代表已部署。

- 根目录 `privacy-policy.md` 继续用于 GitHub Pages 的现有隐私政策 URL；不要移动或删除。
- `website/` 已从 Jekyll 输出排除。推送 main 仍会触发 Pages 构建，但官网源码不应作为 Pages 新页面发布。
- aizst 部署按原渠道单独授权；历史目标为 `/var/www/aizst/`，操作前重新核实。GitHub 推送不等于 aizst 部署。
- 隐私政策有 Pages Markdown、官网 HTML 和 tCam 的 `docs/privacy-policy.md` 三份表现；修订时同时核对正文，保留 Pages 的 front matter，避免只改其中一份。本次未变更政策正文。
- 不在本目录保存签名材料、安装包、交接 ZIP 或构建缓存。
