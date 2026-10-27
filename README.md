# 吸引力🧲单词 · Again

第二次遇见，就值得记住。

第一次遇见陌生单词时，先在脑海里留意，也可以不查；第二次在生活中遇见，再来词本记录。

本包独立完整，包含网页、桌面图标和离线缓存文件，不需要任何旧版文件或额外安装依赖。

## 免费发布到 GitHub Pages

1. 在电脑上登录 GitHub，打开 https://github.com/new 。没有账号时先注册。
2. Repository name 填 `again-words`，可见性选 Public，打开 Add README，再点 Create repository。
3. 进入仓库，点 Add file → Upload files。将本包解压后的文件上传，确保 `index.html` 直接位于仓库首页，没有套在第二层文件夹里。不要只上传 ZIP 文件。
4. 必须上传的六个文件：`index.html`、`manifest.webmanifest`、`sw.js`、`icon.svg`、`icon-192.png`、`icon-512.png`。README.md 可以一起上传；`.nojekyll` 是可选辅助文件，不影响这些纯静态文件的使用。
5. 在上传页面底部点 Commit changes，将文件保存到 main 分支。
6. 进入 Settings → Pages，在 Build and deployment 中将 Source 选为 Deploy from a branch，Branch 选 main，文件夹选 /(root)，点 Save。
7. 等待发布完成（GitHub 官方说明可能需要最多约 10 分钟），回到 Pages 页面点 Visit site，复制实际生成的网址。
8. 网址通常是 https://你的GitHub用户名.github.io/again-words/ 。以 Pages 页显示的实际地址为准。

GitHub Free 可以免费为公开仓库提供 Pages，网址由 GitHub 提供，无需购买域名。公开的是网页程序文件；你的个人单词不在程序包里，只保存在自己手机上。

官方说明：
https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages
https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## 添加到手机桌面并离线使用

1. 首次打开必须能正常访问你自己的 GitHub Pages 地址。GitHub 在不同网络下的可达性可能不同，请用手机的实际网络测试。
2. iPhone 用 Safari 打开，点分享（或先点地址栏旁的「…」再点分享）→ 添加到主屏幕。如果出现「作为网页 App 打开」，保持开启。
3. Android 用 Chrome 打开，点右上角「⋮」→ 安装应用 / 添加到主屏幕，按提示确认。
4. 从桌面图标联网打开一次，等待页面下方出现「已可离线使用」。
5. 关闭网页，开启飞行模式，再从桌面图标打开，试着录入和复习。这一步用来验证你手机上的离线使用。

本版优先读取已缓存的网页，已缓存的词本页面与必要文件不会先等待网络响应。首次安装、缓存被系统清理以及获取更新时，仍需能访问原网页。图片和 33 台词搜索需要联网。

## 词本功能

- 录入一次直接收入词本，重复单词会提示。
- 首页显示全部单词，默认从新到旧，可切换从旧到新。
- 单词旁的铅笔可修改拼写与加入日期，也可删除。修改保留复习进度。可填写 Memo，记录例句和自己的理解；列表中的笔记默认仅显示一行，点击展开全文，再点收起。笔记随词本一起本地保存、导出和导入。
- 每行右侧直接搜索 Bing 图片和 33 台词。
- 点今日复习，看到词后选记得 / 不记得。
- 记得后依次间隔 1、3、7、14、30、60 天，之后每 60 天。不记得则 10 分钟后再见，并从头安排间隔。
- 到期单词在打开词本时显示，不发送后台推送。

## 本地记录与备份

每个人的词本只保存在当前浏览器中，各自独立；浏览器、桌面网页入口、设备和网址之间不会自动同步。

建议添加到桌面后固定从桌面图标使用。使用与备份中可以导出 / 导入 JSON。清理浏览器数据、更换设备或更换网址前先导出；迁移到 GitHub 后可导入旧版备份。分享程序文件，不必分享私人词本备份。

## 检查范围

已检查记录、修改拼写与日期、两种排序、保存与旧版备份迁移，以及离线缓存的安装和优先读取逻辑。已验证缓存页面和必要文件的读取不发起联网请求，并避免干扰同一 GitHub 用户其他网页的缓存。

尚未在你的实际手机上验证安装和飞行模式操作，请按上面的步骤实测。本包尚未发布到你的 GitHub 账号。

## 更新已有 GitHub 仓库

上传新版时，将解压后的文件直接上传到仓库首页，覆盖同名文件。不要拖入外层文件夹。确认首页能直接看到 index.html。完成后等 GitHub Pages 发布，联网重新打开；如仍显示旧版，等待片刻后关闭并重新打开。保持原来的网址和浏览器可保留原有词本；建议更新前先导出备份。
