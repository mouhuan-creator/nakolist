# NAKOLIST
极简个人域名米表／导航页
快速查看效果（cloudflare版）：[nakolist.pages.dev](https://nakolist.pages.dev)

## 特点：
- 单 HTML　静态文件，大小不足5KB，可轻松部署至　Github Pages或Cloudflare Pages。
- 极简设计，无繁杂CSS，加载快，滑动顺畅。
- 无内置统计，隐私友好。

## 不足：
- 无主题切换，部分场景下可能视觉效果差。
- 未进行分页设计，域名多时页面过长。
- 无分类、标签、搜索筛选功能。
- 纯静态页面，欲编辑只能修改文件。

## 一些参数释义：
1. 页面标题
`<h1>替换部分</h1>`

2.　域名数据
>　const domains=[
{name:"域名１",price:"具体售价或询价或保留自用或已售",intro:"简介",detail:"展开后的长文本，无字数限制，支持 Markdown"},
{name:"域名２",price:"询价",intro:"简介",detail:"详情"}
];
//最后一个不用加,

3.　Contact
>　const contact=`Email: [xx@xx.xx](mailto:xx@xx.xx)
Telegram: [@username](https://t.me/username)
WeChat: [wxid](weixin://)
Mastodon: [@user@mastodon.social](https://mastodon.social/@user)`;

4.　末尾的 Powered by部分，建议保留此版权说明
>　Powered by <a href="https://https://github.com/mouhuan-creator/nakolist">NAKOLIST</a>

5. 颜色（`:root`后部分，填入你喜欢的颜色的色值）
>　`--bg`	背景	`#0a0a0a`	
>　`--text`	正文	`#D6D6D6`	
>　`--muted`	价格/简介	`#666`	
>　`--accent`	标题/Contact/图标	`#E0FFFF`	
>　`--link`	下划线	`#FFD700`	

6.域名颜色需单独设置
>　.domain-name{color:#fff}

7.不清楚的话拿去喂给AI，反正就只是个单页。



