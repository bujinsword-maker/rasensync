# 夜雷网站更新包

将本文件夹内的内容上传到 rasensync 仓库最外层，不要把 website 文件夹本身套在外面。

根目录应直接出现：
- index.html：新的封面首页
- style.css：门户页面样式
- library/：资料库，其中 sql/ 是已有 SQL 学习页，python/ 与 exam/ 是待整理页面
- games/：游戏资料待整理页
- guides/：游戏攻略待整理页
- CNAME：保留自定义域名 rasensync.com
- .nojekyll：使用普通静态文件发布

首页 → 资料库 → SQL / Python / 考公。
SQL 页面是独立完整页面，原有章节、练习和进度功能保留。
旧版最外层 app.js、content.js 及 github-pages/ 文件夹可先保留，不影响新首页。
SQL 后续学习进度沿用原版浏览器存储，未更换域名和浏览器时已有进度可继续读取。

上线步骤：
1. 解压 ZIP。
2. 在 GitHub 仓库选择 Add file → Upload files。
3. 进入解压后的 website 文件夹，选择里面的文件与文件夹一起上传，提交。
4. Settings → Pages 保持 main / (root)，自定义域名保持 rasensync.com。
5. Actions 最新发布完成后刷新网站。

本版本已检查本地页面链接；未完成浏览器视觉验证，也尚未直接推送到 GitHub。
