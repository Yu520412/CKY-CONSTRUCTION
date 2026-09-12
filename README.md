# CKY Construction Website

CKY Construction 的完整三语静态官网源码，可直接在本地打开，也可以部署到 GitHub Pages。

网站语言：

- Bahasa Melayu（首次访问默认显示）
- English
- 中文

访客切换语言后，浏览器会记住该选择。页面标题、导航、内容、图片说明及 WhatsApp 预填文字都会同步切换。

## 本地查看

直接双击项目根目录的 `index.html` 即可。

网站的 HTML、CSS、JavaScript、LOGO 和工程照片都包含在本项目内，不需要安装 Node.js、Python 或其他依赖。

电话、WhatsApp、Facebook 和商业资料按钮属于外部链接，使用时需要网络连接。

## 上传到 GitHub

1. 在 GitHub 新建一个 repository。
2. 将本文件夹内的所有文件和 `assets` 文件夹上传到 repository 根目录。
3. 确保 `index.html` 和 `CNAME` 位于 repository 根目录，不要只上传 ZIP 文件。
4. 打开 repository 的 **Settings → Pages**。
5. 在 **Build and deployment** 中选择 **Deploy from a branch**。
6. Branch 选择 `main`，文件夹选择 `/ (root)`，然后保存。
7. 等待 GitHub 完成部署，Pages 页面会显示网站地址。

## 项目结构

```text
CKY-Construction-Website/
├── index.html       # 网站页面及文字内容
├── styles.css       # 视觉设计与手机适配
├── script.js        # 三语切换、菜单、动画和图片加载
├── CNAME            # GitHub Pages 自定义域名
├── assets/          # LOGO 与全部工程照片
└── README.md        # 使用及部署说明
```

## 更新现有 GitHub 网站

1. 解压下载的 ZIP。
2. 打开解压后的 `CKY-Construction-Website` 文件夹。
3. 将文件夹里面的所有内容上传到现有 `CKY-CONSTRUCTION` 仓库根目录并覆盖同名文件。
4. 不要把 ZIP 文件本身上传到仓库，也不要在仓库里再套一层项目文件夹。
5. 提交后等待 GitHub Pages 自动重新部署；DNS 和 HTTPS 无需重新设置。

## 修改联系方式

当前电话及 WhatsApp：`010-776 8278` / `+60 10-776 8278`

如果以后要更换号码，请在 `index.html` 中同时替换：

- 页面显示号码：`010-776 8278`
- 国际电话号码：`+60107768278`
- WhatsApp 地址中的号码：`60107768278`

## 技术说明

- 纯静态 HTML、CSS、JavaScript
- 所有网站图片使用相对路径
- 无数据库、无服务器端代码
- 无第三方程序依赖
- 支持桌面与手机屏幕
- 可部署到 GitHub Pages、Cloudflare Pages、Netlify 或普通虚拟主机
