# 鸿玄紫微排盘 · 条款与隐私在线版

HarmonyOS 应用「鸿玄紫微排盘」（包名 `com.hongxuanziweipan.lanfeng`）的两份法律文本在线版，
用于填写 AppGallery Connect 后台要求的「隐私政策」可访问链接（华为审核指南 7.1）。

| 页面 | 地址 |
|---|---|
| 站点入口 | `https://<域名>/` |
| 隐私政策 | `https://<域名>/privacy.html` |
| 用户协议 | `https://<域名>/terms.html` |

正文的唯一来源是应用工程里的 `entry/src/main/ets/common/LegalText.ets`（应用内页面渲染的就是它），
本仓库的 HTML 与之逐段对应；改动先改应用侧再同步到这里。两页互链用相对路径，换域名不用改正文。

托管：Cloudflare Pages。根目录的 `index.html` 不要删——Pages 靠它识别静态发布目录。
