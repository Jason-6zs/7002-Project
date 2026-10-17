# Ganga Pharmaceuticals — Careers

印度至俄罗斯制药本土化项目的互动招聘网站。包含复古招聘广告、Niraj 印度英语配音、背景音乐、公司介绍、奥美拉唑产品互动展示、俄罗斯项目与招聘岗位页面。

## 上传到 GitHub（直接照着操作）

1. **先解压 ZIP**。上传解压后里面的文件和 `assets`、`docs` 文件夹，不要只上传 ZIP 文件。
2. 在 GitHub 新建仓库，名称可用 `ganga-careers`，可见性选择 **Public**。
3. 点击 **Add file → Upload files**（空仓库也可点 **uploading an existing file**），将解压目录内的文件与文件夹拖入上传区。
4. 检查 `index.html` 与 `assets` 位于仓库最外层，然后点击 **Commit changes** 保存。
5. 打开仓库 **Settings → Pages**。
6. **Source** 选择 **Deploy from a branch**，分支选择 **main**，文件夹选择 **/(root)**，点击 **Save**。如果默认分支名称不同，选择实际上传文件的分支。
7. 发布完成后，在 Pages 页面点击 **Visit site**，复制该地址分享。通常地址为 `https://你的GitHub用户名.github.io/ganga-careers/`。首次发布可能需要几分钟。

**Public 仓库让别人看到项目文件；启用 GitHub Pages 后，别人才能通过网址直接打开互动网站。**

GitHub 官方说明：[创建 Pages 网站](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site) · [设置发布来源](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)

## 文件结构

```text
index.html          网站入口（必须放在仓库根目录）
styles.css          现代企业网站样式
app.js              页面导航、产品旋转与互动
ad.css              复古广告主要样式
ad-green.css        绿色点缀、电视转场和结尾入口
ad.js               广告时间轴、配音、音乐和结束转场
assets/             全部网站所需图片、配音、音乐和音效
docs/               制作说明、分镜与音乐处理记录
.nojekyll           静态站点发布标记
```

无需安装软件包、构建步骤、服务器程序或 API 密钥。图片和音频均随项目附带，页面使用相对路径，可在 GitHub Pages 的仓库子路径下运行。Google Fonts 需要网络；不可用时自动使用系统字体。

## 预览与体验

- 本地预览：保持文件结构完整，双击 `index.html`。
- 正常网址：首次访问播放广告，本次浏览会话中完成后可以直接进入主页。
- 强制重播广告：在网址末尾加 `?intro=1`。
- 浏览器默认静音预览，点击 **PLAY WITH SOUND** 开启配音与音乐。
- 广告结尾：宣传单飞落、镜头贴近、约 0.45 秒电视雪花、简洁结束画面。点击结束画面进入主页。
- 主页、公司、产品、俄罗斯项目与招聘通过导航切换；产品包装支持拖动旋转。

## 素材与项目说明

公司、项目和药品包装沿用本项目的展示设定。医学与行业资料及照片来源可在网站的 References & Credits 中查看。

- HR 角色、招聘宣传单和印度／俄罗斯场景基于用户提供的素材；六个人物透明姿态由参考素材衍生。
- 配音：ElevenLabs，Niraj。
- BGM：用户提供的《Aankhein Khuli》，原曲 00:45 起选段，经人声分离、降速与音量处理。来源及编辑参数见 `docs/music-edit-notes.json` 和 `docs/production-notes.txt`。
- 电话音效和合成模拟电视噪声随网站附带。
- 第三方素材的权利归原权利人所有；此包不附加授予第三方素材的授权。

这是最终确认版的网站文件包，未包含旧版截图、试听版本、模型缓存或账号凭据。
