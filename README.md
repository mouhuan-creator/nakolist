# NAKOLIST
开源轻量个人域名米表／导航页。
快速体验：[nakolist.pages.dev](https://nakolist.pages.dev)

## 特点：
- 零成本部署：纯静态 HTML，可托管于　GitHub Pages/Cloudflare Pages。
- 维护成本低：仅有一个 `index.html`，不到5KB，不依赖其他服务，迁移方便	。
- 采用极简设计，一目了然，让人专注内容本身。
- 适应广泛：PC/手机自适应，单行布局显示一致。
- 体验流畅：无框架，无繁复的CSS，加载快，滑动顺畅。
- Markdown　支持。
- 隐私友好：无内置统计，无外部资源加载。

## 不足：
- 无搜索、标签、分类、筛选功能。
- 未进行分页设计，域名过多时页面过长。	
- 纯静态文件，修改只能编辑文件。
- 无后端功能，无访客统计、在线报价功能。
- 图片支持弱，未内置域名Whois截图/Logo展示位
- 多语言缺失，仅中文界面，国际化不便。
- 无主题切换按钮，部分情况下可能视觉效果差。

## 使用方法：
目前有两种零成本部署方式：Github Pages 和　Cloudflare Pages。
您也可以下载源码至本地，并部署到您的服务器上。

修改`index.html`，替换如下参数：

＊页面标题
># NAKOLIST
－－－开源轻量个人域名米表／导航页。
快速体验：[nakolist.pages.dev](https://nakolist.pages.dev)

## 特点：
- 零成本部署：纯静态 HTML，可托管于　GitHub Pages/Cloudflare Pages。
- 维护成本低：仅有一个 `index.html`，不到5KB，不依赖其他服务，迁移方便	。
- 采用极简设计，一目了然，让人专注内容本身。
- 适应广泛：PC/手机自适应，单行布局显示一致。
- 体验流畅：无框架，无繁复的CSS，加载快，滑动顺畅。
- Markdown　支持。
- 隐私友好：无内置统计，无外部资源加载。

## 不足：
- 无搜索、标签、分类、筛选功能。
- 未进行分页设计，域名过多时页面过长。	
- 纯静态文件，修改只能编辑文件。
- 无后端功能，无访客统计、在线报价功能。
- 图片支持弱，未内置域名Whois截图/Logo展示位
- 多语言缺失，仅中文界面，国际化不便。
- 无主题切换按钮，部分情况下可能视觉效果差。

## 部署：
目前有两种部署方式：Github Pages 和　Cloudflare Pages。
您也可以下载源码至本地，并部署到您的服务器上。

###　Github Pages
1. Fork此仓库，并命名为`username.github.io`
2. 修改`index.html`，替换如下参数：

＊页面标题
> <h1>替换成你的标题</h1>

＊域名数据
> const domains=[
{name:"域名１",price:"价格（可填具体价格／询价／保留自用等",intro:"简介",detail:"展开后的文本，可以说一说这个域名的来历，故事等，不限制长度，支持 Markdown"},
{name:"域名２",price:"同上",intro:"简介",detail:"详情"}
];
//最后一个不用加,

＊Contact　手机端单点或PC端鼠标悬停展示全屏联系方式。
> const contact=`Email: [xx@xx.xx](mailto:xx@xx.xx)
Telegram: [@username](https://t.me/username)
WeChat: [wxid](weixin://)
Mastodon: [@user@mastodon.social](https://mastodon.social/@user)`;

＊Powered by 部分建议保留此署名
>　Powered by <a href="https://github.com/mouhuan-creator/nakolist">NAKOLIST</a>

＊颜色（`:root`后面部分）
>　`--bg`	背景	`#0a0a0a`	
`--text`	正文	`#D6D6D6`	
`--muted`	价格/简介	`#666`	
`--accent`	标题/Contact/图标	`#E0FFFF`	
`--link`	下划线	`#FFD700`

＊域名需单独修改
>　.domain-name{color:#fff}


const domains=[
{name:"example.com",price:"¥12,000",intro:"15字简介",deail:"长文本，支持**粗体** *斜体* `代码`"},
{name:"第二个.com",price:"询价",intro:"简介",detail:"详情"}
];
<h1>替换成你的标题</h1>

＊域名数据
> const domains=[
{name:"域名１",price:"价格（可填具体价格／询价／保留自用等",intro:"简介",detail:"展开后的文本，可以说一说这个域名的来历，故事等，不限制长度，支持 Markdown"},
{name:"域名２",price:"同上",intro:"简介",detail:"详情"}
];
//最后一个不用加,

＊Contact　手机端单点或PC端鼠标悬停展示全屏联系方式。
> const contact=`Email: [xx@xx.xx](mailto:xx@xx.xx)
Telegram: [@username](https://t.me/username)
WeChat: [wxid](weixin://)
Mastodon: [@user@mastodon.social](https://mastodon.social/@user)`;

＊Powered by 部分建议保留此署名
>　Powered by <a href="https://github.com/mouhuan-creator/nakolist">NAKOLIST</a>

＊颜色（`:root`后面部分）
>　`--bg`	背景	`#0a0a0a`	
> `--text`	正文	`#D6D6D6`	
> `--muted`	价格/简介	`#666`	
> `--accent`	标题/Contact/图标
> `#E0FFFF`	
> `--link`	下划线	`#FFD700`

＊域名需单独修改
>　.domain-name{color:#fff}


