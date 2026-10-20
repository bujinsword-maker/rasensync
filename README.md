# 夜雷 SQL 学习页 · GitHub Pages 发布包

## 首次发布

1. 使用现有公开仓库 https://github.com/bujinsword-maker/rasensync 。已检查：该仓库当前为空。
2. 将此文件夹内的 index.html、content.js、app.js 和 .nojekyll 上传到仓库根目录。不要把 ZIP 本身上传当作网站，也不要再套一层目录。
3. 在仓库 Settings → Pages 中，选择 Deploy from a branch，分支选 main，目录选 / (root)，点击 Save。
4. 等待发布完成，打开 https://bujinsword-maker.github.io/rasensync/。

GitHub Free 的此方案使用公开仓库，网页源文件会公开。仅上传本发布包内的网站文件。

## 绑定自己的域名

先在 GitHub 验证域名，再到仓库 Settings → Pages → Custom domain 保存域名，随后配置域名商的 DNS。
完整域名和 GitHub 用户名确认前，不创建 CNAME 文件，避免配置到错误的域名。
根域名使用 GitHub 官方文档给出的 A 记录；www 使用 CNAME 指向“bujinsword-maker.github.io”（不加 https://，不加路径）。
证书可用后勾选 Enforce HTTPS。不要影响已有邮箱的 MX/TXT 记录。

官方说明：
https://docs.github.com/en/pages/quickstart
https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site

## 更新内容

修改 content.js 中的章节数据并重新上传。index.html 是页面样式，app.js 是交互逻辑。
学习进度与草稿保存在访客当前浏览器；它们不是账号云端数据。
本页没有在线 SQL 执行服务。MySQL 存储过程专题仅供学习，未实机执行验证。

