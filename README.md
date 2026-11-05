# 王先帅的个人主页

纯静态网页，放到任何静态托管上都能直接打开。

- `index.html`：页面本体。改内容只需编辑文件里 `PROFILE`、`CONTACTS`、`SKILLS`、`PROJECTS` 这几段。
- `avatar.jpg`：头像。
- 加视频：把 mp4 放进 `videos/` 文件夹，在对应项目里写 `video: "videos/xxx.mp4"`。

## 绑定自己的域名（GitHub Pages）
1. 新建仓库 `wateryman.github.io`，把本文件夹的内容上传到仓库根目录。
2. 仓库 Settings → Pages → Source 选 main 分支。
3. 在 Custom domain 填你的域名，`www.wangxshuai.cc`（仓库里的 CNAME 文件已经写好），并勾选 Enforce HTTPS。
4. 到域名服务商的 DNS 设置里添加记录：`www` 类型选 CNAME，值填 `wateryman.github.io`。
