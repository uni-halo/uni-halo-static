# Uni Halo 静态资源清单

本文件由仓库实际文件自动生成，列出 `uni-halo-static` 中**全部已入库资源**，按用途分类，并给出每条资源的**加速访问（CDN）**与 **raw 访问**地址。

- 仓库：`https://github.com/uni-halo/uni-halo-static`
- 默认分支：`main`
- 统计时间：2026-09-14 16:38

## 一、地址规则

把下表中的 `{文件路径}` 替换为资源在仓库内的相对路径（如 `logo/uni-logo-v3.png`）即可。

| 类型 | 地址模板 | 说明 |
|---|---|---|
| **加速访问**（推荐） | `https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/{文件路径}` | jsDelivr + Gcore 节点，国内访问更快 |
| 加速访问（备用） | `https://cdn.jsdelivr.net/gh/uni-halo/uni-halo-static@main/{文件路径}` | jsDelivr 官方节点；`@main` 可省略（默认分支）或换成 tag / commit sha 做版本锁定 |
| **raw 访问** | `https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/{文件路径}` | GitHub 原始文件，实时生效，不经 CDN 缓存 |
| 仓库页面 | `https://github.com/uni-halo/uni-halo-static/blob/main/{文件路径}` | GitHub 文件浏览页 |

> **注意**
> 1. 中文文件名在 URL 中需做 percent-encoding，例如 `author/rewards/赞赏码.jpg` → `https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/author/rewards/%E8%B5%9E%E8%B5%8F%E7%A0%81.jpg`。下表链接均已编码。
> 2. jsDelivr 有缓存：新提交后最快数分钟生效，也可访问 `https://purge.jsdelivr.net/gh/uni-halo/uni-halo-static` 主动刷新；`raw` 地址无此问题。
> 3. 生产环境请勿依赖 `main` 分支的「最新」语义做长期引用，重要资源建议锁定 tag 或 commit sha（如 `https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@<sha>/logo.png`）。

## 二、资源总览

| 分类 | 文件数 | 体积 |
|---|---|---|
| 品牌标识 / Logo & Favicon | 4 | 855 KB |
| 文档站运行时数据 / docs/data | 5 | 16 KB |
| 通用图片 / images | 7 | 7.9 MB |
| 应用截图 / screenshots | 25 | 12.8 MB |
| 作者资源 / author | 7 | 1.4 MB |
| **合计** | **48** | **23.0 MB** |

## 三、资源明细

### 品牌标识 / Logo & Favicon

站点与文档站使用的品牌图标。

| 文件路径 | 说明 | 大小 | 加速访问 | raw 访问 |
|---|---|---|---|---|
| `logo.png` | 主 Logo（当前使用） | 412.5 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/logo.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/logo.png) |
| `favicon.ico` | 站点 favicon | 16.6 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/favicon.ico) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/favicon.ico) |
| `logo/uni-logo-v2.png` | v2.x 版本 Logo | 12.9 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/logo/uni-logo-v2.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/logo/uni-logo-v2.png) |
| `logo/uni-logo-v3.png` | v3.x 版本 Logo | 412.5 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/logo/uni-logo-v3.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/logo/uni-logo-v3.png) |

### 文档站运行时数据 / docs/data

供 `uni-halo-doc`（VitePress）运行时拉取的 JSON 数据，**生产环境经 jsDelivr 读取本目录**，改动需先改这里再生效。

| 文件路径 | 说明 | 大小 | 加速访问 | raw 访问 |
|---|---|---|---|---|
| `docs/data/ads.json` | 站长推荐 / 广告位数据（弹窗 dialog、侧栏 asideNavAfter） | 4.0 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/docs/data/ads.json) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/docs/data/ads.json) |
| `docs/data/links.json` | 友情链接 + 赞助打赏榜单数据 | 5.5 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/docs/data/links.json) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/docs/data/links.json) |
| `docs/data/notify.json` | 文档站消息通知卡片配置 | 415 B | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/docs/data/notify.json) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/docs/data/notify.json) |
| `docs/data/team.json` | 团队成员介绍数据 | 4.8 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/docs/data/team.json) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/docs/data/team.json) |
| `docs/data/examples.json` | 示例站点 / 用户案例列表 | 1.7 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/docs/data/examples.json) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/docs/data/examples.json) |

### 通用图片 / images

文档站与 README 复用的通用图片素材。

| 文件路径 | 说明 | 大小 | 加速访问 | raw 访问 |
|---|---|---|---|---|
| `images/material/uni_halo_about_wave.gif` | 「关于」页波浪动效 | 955.6 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/images/material/uni_halo_about_wave.gif) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/images/material/uni_halo_about_wave.gif) |
| `images/material/uni_halo_img_lazyload.gif` | 图片懒加载占位动效 | 93.3 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/images/material/uni_halo_img_lazyload.gif) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/images/material/uni_halo_img_lazyload.gif) |
| `images/material/uni_halo_profile_bg.jpg` | 个人资料页默认背景图 | 17.9 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/images/material/uni_halo_profile_bg.jpg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/images/material/uni_halo_profile_bg.jpg) |
| `images/notices/release.png` | 版本发布公告配图 | 3.8 MB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/images/notices/release.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/images/notices/release.png) |
| `images/qqqun.png` | QQ 交流群二维码 | 3.0 MB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/images/qqqun.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/images/qqqun.png) |
| `images/mp.png` | 小程序 / 公众号二维码 | 30.3 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/images/mp.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/images/mp.png) |
| `images/iframe/iPhone13.png` | 文档站 iframe 预览用的 iPhone13 外框 | 16.9 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/images/iframe/iPhone13.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/images/iframe/iPhone13.png) |

### 应用截图 / screenshots

按应用大版本归档的功能截图。

| 文件路径 | 说明 | 大小 | 加速访问 | raw 访问 |
|---|---|---|---|---|
| `screenshots/app/v1.x/001.jpg` | v1.x 截图 01 | 1.1 MB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v1.x/001.jpg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v1.x/001.jpg) |
| `screenshots/app/v1.x/002.jpg` | v1.x 截图 02 | 741.7 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v1.x/002.jpg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v1.x/002.jpg) |
| `screenshots/app/v1.x/003.jpg` | v1.x 截图 03 | 1.0 MB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v1.x/003.jpg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v1.x/003.jpg) |
| `screenshots/app/v1.x/004.jpg` | v1.x 截图 04 | 505.9 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v1.x/004.jpg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v1.x/004.jpg) |
| `screenshots/app/v1.x/005.jpg` | v1.x 截图 05 | 790.8 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v1.x/005.jpg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v1.x/005.jpg) |
| `screenshots/app/v1.x/006.jpg` | v1.x 截图 06 | 529.7 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v1.x/006.jpg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v1.x/006.jpg) |
| `screenshots/app/v1.x/007.jpg` | v1.x 截图 07 | 707.2 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v1.x/007.jpg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v1.x/007.jpg) |
| `screenshots/app/v1.x/008.jpg` | v1.x 截图 08 | 614.5 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v1.x/008.jpg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v1.x/008.jpg) |
| `screenshots/app/v1.x/009.jpg` | v1.x 截图 09 | 331.1 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v1.x/009.jpg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v1.x/009.jpg) |
| `screenshots/app/v1.x/010.jpg` | v1.x 截图 10 | 760.7 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v1.x/010.jpg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v1.x/010.jpg) |
| `screenshots/app/v1.x/love/love_001.jpg` | v1.x 恋爱日记模块 01 | 947.0 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v1.x/love/love_001.jpg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v1.x/love/love_001.jpg) |
| `screenshots/app/v1.x/love/love_002.jpg` | v1.x 恋爱日记模块 02 | 546.8 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v1.x/love/love_002.jpg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v1.x/love/love_002.jpg) |
| `screenshots/app/v1.x/love/love_003.jpg` | v1.x 恋爱日记模块 03 | 691.4 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v1.x/love/love_003.jpg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v1.x/love/love_003.jpg) |
| `screenshots/app/v2.x/首页.png` | v2.x 首页 | 331.1 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v2.x/%E9%A6%96%E9%A1%B5.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v2.x/%E9%A6%96%E9%A1%B5.png) |
| `screenshots/app/v2.x/分类.jpg` | v2.x 分类页 | 215.1 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v2.x/%E5%88%86%E7%B1%BB.jpg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v2.x/%E5%88%86%E7%B1%BB.jpg) |
| `screenshots/app/v2.x/图库.jpg` | v2.x 图库页 | 336.1 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v2.x/%E5%9B%BE%E5%BA%93.jpg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v2.x/%E5%9B%BE%E5%BA%93.jpg) |
| `screenshots/app/v2.x/瞬间.jpg` | v2.x 瞬间页 | 211.9 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v2.x/%E7%9E%AC%E9%97%B4.jpg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v2.x/%E7%9E%AC%E9%97%B4.jpg) |
| `screenshots/app/v2.x/文章归档.jpg` | v2.x 文章归档页 | 264.7 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v2.x/%E6%96%87%E7%AB%A0%E5%BD%92%E6%A1%A3.jpg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v2.x/%E6%96%87%E7%AB%A0%E5%BD%92%E6%A1%A3.jpg) |
| `screenshots/app/v2.x/文章投票.png` | v2.x 文章投票 | 712.5 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v2.x/%E6%96%87%E7%AB%A0%E6%8A%95%E7%A5%A8.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v2.x/%E6%96%87%E7%AB%A0%E6%8A%95%E7%A5%A8.png) |
| `screenshots/app/v2.x/投票列表.png` | v2.x 投票列表页 | 253.8 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v2.x/%E6%8A%95%E7%A5%A8%E5%88%97%E8%A1%A8.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v2.x/%E6%8A%95%E7%A5%A8%E5%88%97%E8%A1%A8.png) |
| `screenshots/app/v2.x/投票详情.png` | v2.x 投票详情页 | 322.3 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v2.x/%E6%8A%95%E7%A5%A8%E8%AF%A6%E6%83%85.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v2.x/%E6%8A%95%E7%A5%A8%E8%AF%A6%E6%83%85.png) |
| `screenshots/app/v2.x/恋爱日记.jpg` | v2.x 恋爱日记模块 | 306.2 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v2.x/%E6%81%8B%E7%88%B1%E6%97%A5%E8%AE%B0.jpg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v2.x/%E6%81%8B%E7%88%B1%E6%97%A5%E8%AE%B0.jpg) |
| `screenshots/app/v2.x/友情链接.jpg` | v2.x 友情链接页 | 309.9 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v2.x/%E5%8F%8B%E6%83%85%E9%93%BE%E6%8E%A5.jpg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v2.x/%E5%8F%8B%E6%83%85%E9%93%BE%E6%8E%A5.jpg) |
| `screenshots/app/v2.x/联系博主.jpg` | v2.x 联系博主页 | 187.1 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v2.x/%E8%81%94%E7%B3%BB%E5%8D%9A%E4%B8%BB.jpg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v2.x/%E8%81%94%E7%B3%BB%E5%8D%9A%E4%B8%BB.jpg) |
| `screenshots/app/v2.x/关于.jpg` | v2.x 关于页 | 295.5 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v2.x/%E5%85%B3%E4%BA%8E.jpg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v2.x/%E5%85%B3%E4%BA%8E.jpg) |

### 作者资源 / author

作者个人形象与赞赏收款码。

| 文件路径 | 说明 | 大小 | 加速访问 | raw 访问 |
|---|---|---|---|---|
| `author/xiaomo.jpg` | 作者头像 | 81.4 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/author/xiaomo.jpg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/author/xiaomo.jpg) |
| `author/xiaomo2.jpg` | 作者头像（备用） | 83.9 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/author/xiaomo2.jpg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/author/xiaomo2.jpg) |
| `author/rewards/赞赏码.jpg` | 赞赏码（三合一，圆角） | 400.2 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/author/rewards/%E8%B5%9E%E8%B5%8F%E7%A0%81.jpg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/author/rewards/%E8%B5%9E%E8%B5%8F%E7%A0%81.jpg) |
| `author/rewards/赞赏码-无圆角.jpg` | 赞赏码（三合一，无圆角） | 402.8 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/author/rewards/%E8%B5%9E%E8%B5%8F%E7%A0%81-%E6%97%A0%E5%9C%86%E8%A7%92.jpg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/author/rewards/%E8%B5%9E%E8%B5%8F%E7%A0%81-%E6%97%A0%E5%9C%86%E8%A7%92.jpg) |
| `author/rewards/WXRewardCode.png` | 微信收款码 | 146.5 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/author/rewards/WXRewardCode.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/author/rewards/WXRewardCode.png) |
| `author/rewards/QQRewardCode.png` | QQ 收款码 | 213.8 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/author/rewards/QQRewardCode.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/author/rewards/QQRewardCode.png) |
| `author/rewards/ZFBRewardCode.png` | 支付宝收款码 | 134.2 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/author/rewards/ZFBRewardCode.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/author/rewards/ZFBRewardCode.png) |

## 四、预留目录（暂无文件）

这些目录目前只有占位文件（`.gitkeep`），用于后续资源归档：

| 目录 | 用途 |
|---|---|
| `videos/` | 演示视频资源 |
| `screenshots/app/v3.x/` | v3.x 应用截图 |
| `screenshots/plugin/v3.x/` | v3.x Halo 插件截图 |
| `docs/` | 文档站静态资源根目录（运行时数据位于 `docs/data/`） |

## 五、维护约定

1. **新增 / 删除资源后，请同步更新本文件**，保持清单与实际文件一致。
2. `docs/data/*.json` 是**线上文档站的运行时数据源**（`uni-halo-doc` 生产环境 base 为 `https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/docs`），改动会直接影响线上；DEV 环境读本地 `uni-halo-doc/src/public/data/*.json`，两边需保持一致。
3. 大文件优先放 `images/`、`videos/`，并注意 jsDelivr 单文件 20 MB 限制。
4. `docs/data/ads.json` 中的 `cover` 字段为 `/ads/**` 站内路径，对应图片**尚未入库**，引用前需补传，否则线上会 404。
5. `README.md` 里的 Gitee 地址指向 `gitee.com/uni-halo/uni-halo-static-resources`，该镜像未经核实（当前远端只有 GitHub），引用前请自行确认。
