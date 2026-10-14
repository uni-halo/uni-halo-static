# Uni Halo 静态资源清单

本文件列出 `uni-halo-static` 中**全部已入库资源**，按用途分类，并给出每条资源的**加速访问（CDN）**与 **raw 访问**地址。

- 仓库：`https://github.com/uni-halo/uni-halo-static`
- 默认分支：`main`
- 统计时间：2026-10-15

## 一、地址规则

把下表中的 `{文件路径}` 替换为资源在仓库内的相对路径（如 `logo/uni-logo-v3.png`）即可。

| 类型 | 地址模板 | 说明 |
|---|---|---|
| **加速访问**（推荐） | `https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/{文件路径}` | jsDelivr + Gcore 节点，国内访问更快；后缀可省略（跟随默认分支） |
| 加速访问（备用） | `https://cdn.jsdelivr.net/gh/uni-halo/uni-halo-static/{文件路径}` | jsDelivr 官方节点；后缀可省略（跟随默认分支），也可加 `@<tag>` / `@<sha>` 做版本锁定 |
| **raw 访问** | `https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/{文件路径}` | GitHub 原始文件，实时生效，不经 CDN 缓存 |
| 仓库页面 | `https://github.com/uni-halo/uni-halo-static/blob/main/{文件路径}` | GitHub 文件浏览页 |

> **注意**
> 1. 中文文件名在 URL 中需做 percent-encoding，例如 `author/rewards/赞赏码.jpg` → `https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/author/rewards/%E8%B5%9E%E8%B5%8F%E7%A0%81.jpg`。下表链接均已编码。
> 2. jsDelivr 有缓存：新提交后最快数分钟生效，也可访问 `https://purge.jsdelivr.net/gh/uni-halo/uni-halo-static` 主动刷新；`raw` 地址无此问题。
> 3. 生产环境请勿依赖默认分支的「最新」语义做长期引用，重要资源建议锁定 tag 或 commit sha（如 `https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@<sha>/logo.png`）。

## 二、资源总览

| 分类 | 文件数 | 体积 |
|---|---|---|
| 品牌标识 / 根目录 | 4 | 592.0 KB |
| 品牌 Logo / logo | 5 | 633.0 KB |
| 作者资源 / author | 13 | 2.7 MB |
| 文档站运行时数据 / docs/data | 5 | 17.0 KB |
| 文档站配图 / docs/app-release | 15 | 4.1 MB |
| 用户案例截图 / docs/useage-examples | 11 | 686.8 KB |
| 通用图片 / images | 10 | 8.4 MB |
| 应用截图 / screenshots/app | 43 | 22.1 MB |
| 插件截图 / screenshots/plugin | 17 | 2.8 MB |
| **合计** | **123** | **约 42.0 MB** |

## 三、资源明细

### 品牌标识 / 根目录

站点 favicon、主 Logo 与公众号二维码。

| 文件路径 | 说明 | 大小 | 加速访问 | raw 访问 |
|---|---|---|---|---|
| `logo.png` | 主 Logo（当前使用） | 412.5 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/logo.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/logo.png) |
| `favicon.ico` | 站点 favicon | 16.6 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/favicon.ico) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/favicon.ico) |
| `gh_qrcode.jpg` | GitHub 公众号二维码（主用） | 94.7 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/gh_qrcode.jpg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/gh_qrcode.jpg) |
| `gh_qrcode-1.jpg` | GitHub 公众号二维码（备用） | 68.2 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/gh_qrcode-1.jpg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/gh_qrcode-1.jpg) |

### 品牌 Logo / logo

各尺寸品牌 Logo 与历史版本。

| 文件路径 | 说明 | 大小 | 加速访问 | raw 访问 |
|---|---|---|---|---|
| `logo/logo-100.png` | 100px 尺寸 Logo | 12.3 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/logo/logo-100.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/logo/logo-100.png) |
| `logo/logo-200.png` | 200px 尺寸 Logo | 40.0 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/logo/logo-200.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/logo/logo-200.png) |
| `logo/logo-400.png` | 400px 尺寸 Logo | 155.1 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/logo/logo-400.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/logo/logo-400.png) |
| `logo/uni-logo-v2.png` | v2.x 版本 Logo | 12.9 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/logo/uni-logo-v2.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/logo/uni-logo-v2.png) |
| `logo/uni-logo-v3.png` | v3.x 版本 Logo | 412.5 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/logo/uni-logo-v3.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/logo/uni-logo-v3.png) |

### 作者资源 / author

作者头像、Logo 与赞赏收款码。

| 文件路径 | 说明 | 大小 | 加速访问 | raw 访问 |
|---|---|---|---|---|
| `author/favicon.ico` | 作者站点 favicon | 16.6 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/author/favicon.ico) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/author/favicon.ico) |
| `author/logo.png` | 作者 Logo | 278.6 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/author/logo.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/author/logo.png) |
| `author/logo-console.jpeg` | 控制台展示形象图 | 500.5 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/author/logo-console.jpeg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/author/logo-console.jpeg) |
| `author/xiaomo.jpg` | 作者头像（当前使用） | 19.4 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/author/xiaomo.jpg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/author/xiaomo.jpg) |
| `author/xiaomo2.jpg` | 作者头像（备用） | 83.9 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/author/xiaomo2.jpg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/author/xiaomo2.jpg) |
| `author/xiaomo3.jpg` | 作者头像（备用 2） | 81.4 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/author/xiaomo3.jpg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/author/xiaomo3.jpg) |
| `author/xiaomo-logo.png` | 个人品牌 Logo | 197.0 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/author/xiaomo-logo.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/author/xiaomo-logo.png) |
| `author/xiaomo-logo-round.png` | 个人品牌 Logo（圆形） | 282.6 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/author/xiaomo-logo-round.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/author/xiaomo-logo-round.png) |
| `author/rewards/QQRewardCode.png` | QQ 收款码 | 213.8 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/author/rewards/QQRewardCode.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/author/rewards/QQRewardCode.png) |
| `author/rewards/WXRewardCode.png` | 微信收款码 | 146.5 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/author/rewards/WXRewardCode.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/author/rewards/WXRewardCode.png) |
| `author/rewards/ZFBRewardCode.png` | 支付宝收款码 | 134.2 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/author/rewards/ZFBRewardCode.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/author/rewards/ZFBRewardCode.png) |
| `author/rewards/赞赏码.jpg` | 赞赏码（三合一，圆角） | 400.2 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/author/rewards/%E8%B5%9E%E8%B5%8F%E7%A0%81.jpg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/author/rewards/%E8%B5%9E%E8%B5%8F%E7%A0%81.jpg) |
| `author/rewards/赞赏码-无圆角.jpg` | 赞赏码（三合一，无圆角） | 402.8 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/author/rewards/%E8%B5%9E%E8%B5%8F%E7%A0%81-%E6%97%A0%E5%9C%86%E8%A7%92.jpg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/author/rewards/%E8%B5%9E%E8%B5%8F%E7%A0%81-%E6%97%A0%E5%9C%86%E8%A7%92.jpg) |

### 文档站运行时数据 / docs/data

供 `uni-halo-doc`（VitePress）运行时拉取的 JSON 数据，**生产环境经 jsDelivr 读取本目录**，改动需先改这里再生效。

| 文件路径 | 说明 | 大小 | 加速访问 | raw 访问 |
|---|---|---|---|---|
| `docs/data/ads.json` | 站长推荐 / 广告位数据（弹窗、侧栏） | 4.0 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/docs/data/ads.json) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/docs/data/ads.json) |
| `docs/data/examples.json` | 示例站点 / 用户案例列表 | 2.2 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/docs/data/examples.json) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/docs/data/examples.json) |
| `docs/data/links.json` | 友情链接 + 赞助打赏榜单数据 | 5.5 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/docs/data/links.json) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/docs/data/links.json) |
| `docs/data/notify.json` | 文档站消息通知卡片配置 | 415 B | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/docs/data/notify.json) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/docs/data/notify.json) |
| `docs/data/team.json` | 团队成员介绍数据 | 4.8 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/docs/data/team.json) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/docs/data/team.json) |

### 文档站配图 / docs/app-release

`uni-halo-doc` 发布 APP 指南（`deploy/app-release.md`）使用的步骤配图。

| 文件路径 | 说明 | 大小 | 加速访问 | raw 访问 |
|---|---|---|---|---|
| `docs/app-release/01-微信开发者工具-导入.png` | 微信开发者工具导入项目入口 | 19.5 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/docs/app-release/01-%E5%BE%AE%E4%BF%A1%E5%BC%80%E5%8F%91%E8%80%85%E5%B7%A5%E5%85%B7-%E5%AF%BC%E5%85%A5.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/docs/app-release/01-%E5%BE%AE%E4%BF%A1%E5%BC%80%E5%8F%91%E8%80%85%E5%B7%A5%E5%85%B7-%E5%AF%BC%E5%85%A5.png) |
| `docs/app-release/02-HBuilderX-从本地目录导入.png` | HBuilderX 从本地目录导入项目 | 49.4 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/docs/app-release/02-HBuilderX-%E4%BB%8E%E6%9C%AC%E5%9C%B0%E7%9B%AE%E5%BD%95%E5%AF%BC%E5%85%A5.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/docs/app-release/02-HBuilderX-%E4%BB%8E%E6%9C%AC%E5%9C%B0%E7%9B%AE%E5%BD%95%E5%AF%BC%E5%85%A5.png) |
| `docs/app-release/03-HBuilderX-重新识别项目类型.png` | HBuilderX 重新识别项目类型 | 30.1 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/docs/app-release/03-HBuilderX-%E9%87%8D%E6%96%B0%E8%AF%86%E5%88%AB%E9%A1%B9%E7%9B%AE%E7%B1%BB%E5%9E%8B.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/docs/app-release/03-HBuilderX-%E9%87%8D%E6%96%B0%E8%AF%86%E5%88%AB%E9%A1%B9%E7%9B%AE%E7%B1%BB%E5%9E%8B.png) |
| `docs/app-release/04-运行到iOS模拟器基座.png` | HBuilderX 运行到 iOS 模拟器基座菜单 | 50.3 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/docs/app-release/04-%E8%BF%90%E8%A1%8C%E5%88%B0iOS%E6%A8%A1%E6%8B%9F%E5%99%A8%E5%9F%BA%E5%BA%A7.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/docs/app-release/04-%E8%BF%90%E8%A1%8C%E5%88%B0iOS%E6%A8%A1%E6%8B%9F%E5%99%A8%E5%9F%BA%E5%BA%A7.png) |
| `docs/app-release/05-选择iOS模拟器设备.png` | 选择 iOS 模拟器设备弹窗 | 84.3 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/docs/app-release/05-%E9%80%89%E6%8B%A9iOS%E6%A8%A1%E6%8B%9F%E5%99%A8%E8%AE%BE%E5%A4%87.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/docs/app-release/05-%E9%80%89%E6%8B%A9iOS%E6%A8%A1%E6%8B%9F%E5%99%A8%E8%AE%BE%E5%A4%87.png) |
| `docs/app-release/06-HBuilderX-从本地目录导入-大图.png` | HBuilderX 从本地目录导入（大图） | 244.8 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/docs/app-release/06-HBuilderX-%E4%BB%8E%E6%9C%AC%E5%9C%B0%E7%9B%AE%E5%BD%95%E5%AF%BC%E5%85%A5-%E5%A4%A7%E5%9B%BE.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/docs/app-release/06-HBuilderX-%E4%BB%8E%E6%9C%AC%E5%9C%B0%E7%9B%AE%E5%BD%95%E5%AF%BC%E5%85%A5-%E5%A4%A7%E5%9B%BE.png) |
| `docs/app-release/07-发行-原生App云打包.png` | HBuilderX 发行原生App云打包菜单 | 32.7 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/docs/app-release/07-%E5%8F%91%E8%A1%8C-%E5%8E%9F%E7%94%9FApp%E4%BA%91%E6%89%93%E5%8C%85.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/docs/app-release/07-%E5%8F%91%E8%A1%8C-%E5%8E%9F%E7%94%9FApp%E4%BA%91%E6%89%93%E5%8C%85.png) |
| `docs/app-release/08-云打包配置-Android.png` | 云打包面板 Android 配置 | 236.2 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/docs/app-release/08-%E4%BA%91%E6%89%93%E5%8C%85%E9%85%8D%E7%BD%AE-Android.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/docs/app-release/08-%E4%BA%91%E6%89%93%E5%8C%85%E9%85%8D%E7%BD%AE-Android.png) |
| `docs/app-release/09-manifest-基础配置-AppID.png` | manifest 基础配置中的 DCloud AppID | 641.5 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/docs/app-release/09-manifest-%E5%9F%BA%E7%A1%80%E9%85%8D%E7%BD%AE-AppID.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/docs/app-release/09-manifest-%E5%9F%BA%E7%A1%80%E9%85%8D%E7%BD%AE-AppID.png) |
| `docs/app-release/10-env-VITE_UNI_APPID.png` | env 文件中的 VITE_UNI_APPID 配置 | 888.3 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/docs/app-release/10-env-VITE_UNI_APPID.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/docs/app-release/10-env-VITE_UNI_APPID.png) |
| `docs/app-release/11-manifest-Android设置-minSdkVersion.png` | manifest Android 设置 minSdkVersion | 704.7 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/docs/app-release/11-manifest-Android%E8%AE%BE%E7%BD%AE-minSdkVersion.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/docs/app-release/11-manifest-Android%E8%AE%BE%E7%BD%AE-minSdkVersion.png) |
| `docs/app-release/12-依赖版本-uni-app-SDK.png` | package.json 中 uni-app SDK 版本 | 32.8 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/docs/app-release/12-%E4%BE%9D%E8%B5%96%E7%89%88%E6%9C%AC-uni-app-SDK.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/docs/app-release/12-%E4%BE%9D%E8%B5%96%E7%89%88%E6%9C%AC-uni-app-SDK.png) |
| `docs/app-release/13-HBuilderX版本与SDK不匹配.png` | HBuilderX 版本与 SDK 不匹配弹窗 | 485.3 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/docs/app-release/13-HBuilderX%E7%89%88%E6%9C%AC%E4%B8%8ESDK%E4%B8%8D%E5%8C%B9%E9%85%8D.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/docs/app-release/13-HBuilderX%E7%89%88%E6%9C%AC%E4%B8%8ESDK%E4%B8%8D%E5%8C%B9%E9%85%8D.png) |
| `docs/app-release/14-真机提示-版本不匹配.png` | 真机运行版本不匹配提示 | 201.7 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/docs/app-release/14-%E7%9C%9F%E6%9C%BA%E6%8F%90%E7%A4%BA-%E7%89%88%E6%9C%AC%E4%B8%8D%E5%8C%B9%E9%85%8D.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/docs/app-release/14-%E7%9C%9F%E6%9C%BA%E6%8F%90%E7%A4%BA-%E7%89%88%E6%9C%AC%E4%B8%8D%E5%8C%B9%E9%85%8D.png) |
| `docs/app-release/15-Mac多版本HBuilderX.png` | macOS 多版本 HBuilderX 共存 | 483.7 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/docs/app-release/15-Mac%E5%A4%9A%E7%89%88%E6%9C%ACHBuilderX.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/docs/app-release/15-Mac%E5%A4%9A%E7%89%88%E6%9C%ACHBuilderX.png) |

### 用户案例截图 / docs/useage-examples

文档站「用户案例」页使用的站点截图，对应 `docs/data/examples.json` 中的 `image` 字段。

| 文件路径 | 说明 | 大小 | 加速访问 | raw 访问 |
|---|---|---|---|---|
| `docs/useage-examples/小莫唐尼.png` | 小莫唐尼 站点截图 | 62.8 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/docs/useage-examples/%E5%B0%8F%E8%8E%AB%E5%94%90%E5%B0%BC.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/docs/useage-examples/%E5%B0%8F%E8%8E%AB%E5%94%90%E5%B0%BC.png) |
| `docs/useage-examples/小陈子的站点.png` | 小陈子的站点 站点截图 | 88.9 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/docs/useage-examples/%E5%B0%8F%E9%99%88%E5%AD%90%E7%9A%84%E7%AB%99%E7%82%B9.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/docs/useage-examples/%E5%B0%8F%E9%99%88%E5%AD%90%E7%9A%84%E7%AB%99%E7%82%B9.png) |
| `docs/useage-examples/鲨鱼辣椒的Blog.png` | 鲨鱼辣椒的Blog 站点截图 | 90.3 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/docs/useage-examples/%E9%B2%A8%E9%B1%BC%E8%BE%A3%E6%A4%92%E7%9A%84Blog.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/docs/useage-examples/%E9%B2%A8%E9%B1%BC%E8%BE%A3%E6%A4%92%E7%9A%84Blog.png) |
| `docs/useage-examples/柳意梧情博客.png` | 柳意梧情博客 站点截图 | 52.0 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/docs/useage-examples/%E6%9F%B3%E6%84%8F%E6%A2%A7%E6%83%85%E5%8D%9A%E5%AE%A2.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/docs/useage-examples/%E6%9F%B3%E6%84%8F%E6%A2%A7%E6%83%85%E5%8D%9A%E5%AE%A2.png) |
| `docs/useage-examples/芈亓的Blog.png` | 芈亓的Blog 站点截图 | 84.1 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/docs/useage-examples/%E8%8A%88%E4%BA%93%E7%9A%84Blog.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/docs/useage-examples/%E8%8A%88%E4%BA%93%E7%9A%84Blog.png) |
| `docs/useage-examples/皮皮猪.png` | 皮皮猪 站点截图 | 51.1 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/docs/useage-examples/%E7%9A%AE%E7%9A%AE%E7%8C%AA.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/docs/useage-examples/%E7%9A%AE%E7%9A%AE%E7%8C%AA.png) |
| `docs/useage-examples/听闻的Blog.png` | 听闻のBlog 站点截图 | 53.1 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/docs/useage-examples/%E5%90%AC%E9%97%BB%E7%9A%84Blog.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/docs/useage-examples/%E5%90%AC%E9%97%BB%E7%9A%84Blog.png) |
| `docs/useage-examples/梦荟楼的后花园.jpg` | 梦荟楼的后花园 站点截图 | 48.3 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/docs/useage-examples/%E6%A2%A6%E8%8D%9F%E6%A5%BC%E7%9A%84%E5%90%8E%E8%8A%B1%E5%9B%AD.jpg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/docs/useage-examples/%E6%A2%A6%E8%8D%9F%E6%A5%BC%E7%9A%84%E5%90%8E%E8%8A%B1%E5%9B%AD.jpg) |
| `docs/useage-examples/谜叶象限.jpg` | 谜叶象限 站点截图 | 78.4 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/docs/useage-examples/%E8%B0%9C%E5%8F%B6%E8%B1%A1%E9%99%90.jpg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/docs/useage-examples/%E8%B0%9C%E5%8F%B6%E8%B1%A1%E9%99%90.jpg) |
| `docs/useage-examples/Dominic Blog.png` | Dominic Blog 站点截图 | 29.7 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/docs/useage-examples/Dominic%20Blog.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/docs/useage-examples/Dominic%20Blog.png) |
| `docs/useage-examples/yusuble特效.png` | yusuble特效 站点截图 | 48.3 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/docs/useage-examples/yusuble%E7%89%B9%E6%95%88.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/docs/useage-examples/yusuble%E7%89%B9%E6%95%88.png) |

### 通用图片 / images

文档站与 README 复用的通用图片素材。

| 文件路径 | 说明 | 大小 | 加速访问 | raw 访问 |
|---|---|---|---|---|
| `images/mp.jpeg` | 小程序 / 公众号二维码 | 147.2 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/images/mp.jpeg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/images/mp.jpeg) |
| `images/mp.png` | 小程序 / 公众号二维码（PNG 版） | 143.1 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/images/mp.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/images/mp.png) |
| `images/mp/小莫唐尼.jpg` | 小程序码（小莫唐尼） | 94.7 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/images/mp/%E5%B0%8F%E8%8E%AB%E5%94%90%E5%B0%BC.jpg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/images/mp/%E5%B0%8F%E8%8E%AB%E5%94%90%E5%B0%BC.jpg) |
| `images/qqqun.jpeg` | QQ 交流群二维码 | 169.0 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/images/qqqun.jpeg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/images/qqqun.jpeg) |
| `images/qqqun.png` | QQ 交流群二维码（高清 PNG） | 3.0 MB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/images/qqqun.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/images/qqqun.png) |
| `images/notices/release.png` | 版本发布公告配图 | 3.7 MB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/images/notices/release.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/images/notices/release.png) |
| `images/iframe/iPhone13.png` | 文档站 iframe 预览用的 iPhone13 外框 | 16.9 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/images/iframe/iPhone13.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/images/iframe/iPhone13.png) |
| `images/material/uni_halo_about_wave.gif` | 「关于」页波浪动效 | 955.6 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/images/material/uni_halo_about_wave.gif) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/images/material/uni_halo_about_wave.gif) |
| `images/material/uni_halo_img_lazyload.gif` | 图片懒加载占位动效 | 93.3 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/images/material/uni_halo_img_lazyload.gif) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/images/material/uni_halo_img_lazyload.gif) |
| `images/material/uni_halo_profile_bg.jpg` | 个人资料页默认背景图 | 17.9 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/images/material/uni_halo_profile_bg.jpg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/images/material/uni_halo_profile_bg.jpg) |

### 应用截图 / screenshots/app

按应用大版本归档的功能截图。

#### v1.x（含恋爱模块）

| 文件路径 | 说明 | 大小 | 加速访问 | raw 访问 |
|---|---|---|---|---|
| `screenshots/app/v1.x/001.jpg` | v1.x 应用截图 01 | 1165.3 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/app/v1.x/001.jpg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v1.x/001.jpg) |
| `screenshots/app/v1.x/002.jpg` | v1.x 应用截图 02 | 741.7 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/app/v1.x/002.jpg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v1.x/002.jpg) |
| `screenshots/app/v1.x/003.jpg` | v1.x 应用截图 03 | 1061.6 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/app/v1.x/003.jpg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v1.x/003.jpg) |
| `screenshots/app/v1.x/004.jpg` | v1.x 应用截图 04 | 505.9 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/app/v1.x/004.jpg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v1.x/004.jpg) |
| `screenshots/app/v1.x/005.jpg` | v1.x 应用截图 05 | 790.8 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/app/v1.x/005.jpg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v1.x/005.jpg) |
| `screenshots/app/v1.x/006.jpg` | v1.x 应用截图 06 | 529.7 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/app/v1.x/006.jpg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v1.x/006.jpg) |
| `screenshots/app/v1.x/007.jpg` | v1.x 应用截图 07 | 707.2 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/app/v1.x/007.jpg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v1.x/007.jpg) |
| `screenshots/app/v1.x/008.jpg` | v1.x 应用截图 08 | 614.5 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/app/v1.x/008.jpg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v1.x/008.jpg) |
| `screenshots/app/v1.x/009.jpg` | v1.x 应用截图 09 | 331.1 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/app/v1.x/009.jpg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v1.x/009.jpg) |
| `screenshots/app/v1.x/010.jpg` | v1.x 应用截图 10 | 760.7 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/app/v1.x/010.jpg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v1.x/010.jpg) |
| `screenshots/app/v1.x/love/love_001.jpg` | v1.x 恋爱日记模块截图 01 | 947.0 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/app/v1.x/love/love_001.jpg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v1.x/love/love_001.jpg) |
| `screenshots/app/v1.x/love/love_002.jpg` | v1.x 恋爱日记模块截图 02 | 546.8 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/app/v1.x/love/love_002.jpg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v1.x/love/love_002.jpg) |
| `screenshots/app/v1.x/love/love_003.jpg` | v1.x 恋爱日记模块截图 03 | 691.4 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/app/v1.x/love/love_003.jpg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v1.x/love/love_003.jpg) |

#### v2.x

| 文件路径 | 说明 | 大小 | 加速访问 | raw 访问 |
|---|---|---|---|---|
| `screenshots/app/v2.x/首页.png` | v2.x 首页 | 331.1 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/app/v2.x/%E9%A6%96%E9%A1%B5.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v2.x/%E9%A6%96%E9%A1%B5.png) |
| `screenshots/app/v2.x/分类.jpg` | v2.x 分类页 | 215.1 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/app/v2.x/%E5%88%86%E7%B1%BB.jpg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v2.x/%E5%88%86%E7%B1%BB.jpg) |
| `screenshots/app/v2.x/图库.jpg` | v2.x 图库页 | 336.1 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/app/v2.x/%E5%9B%BE%E5%BA%93.jpg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v2.x/%E5%9B%BE%E5%BA%93.jpg) |
| `screenshots/app/v2.x/瞬间.jpg` | v2.x 瞬间页 | 211.9 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/app/v2.x/%E7%9E%AC%E9%97%B4.jpg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v2.x/%E7%9E%AC%E9%97%B4.jpg) |
| `screenshots/app/v2.x/文章归档.jpg` | v2.x 文章归档页 | 264.7 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/app/v2.x/%E6%96%87%E7%AB%A0%E5%BD%92%E6%A1%A3.jpg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v2.x/%E6%96%87%E7%AB%A0%E5%BD%92%E6%A1%A3.jpg) |
| `screenshots/app/v2.x/文章投票.png` | v2.x 文章投票 | 712.5 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/app/v2.x/%E6%96%87%E7%AB%A0%E6%8A%95%E7%A5%A8.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v2.x/%E6%96%87%E7%AB%A0%E6%8A%95%E7%A5%A8.png) |
| `screenshots/app/v2.x/投票列表.png` | v2.x 投票列表页 | 253.8 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/app/v2.x/%E6%8A%95%E7%A5%A8%E5%88%97%E8%A1%A8.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v2.x/%E6%8A%95%E7%A5%A8%E5%88%97%E8%A1%A8.png) |
| `screenshots/app/v2.x/投票详情.png` | v2.x 投票详情页 | 322.3 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/app/v2.x/%E6%8A%95%E7%A5%A8%E8%AF%A6%E6%83%85.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v2.x/%E6%8A%95%E7%A5%A8%E8%AF%A6%E6%83%85.png) |
| `screenshots/app/v2.x/恋爱日记.jpg` | v2.x 恋爱日记模块 | 306.2 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/app/v2.x/%E6%81%8B%E7%88%B1%E6%97%A5%E8%AE%B0.jpg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v2.x/%E6%81%8B%E7%88%B1%E6%97%A5%E8%AE%B0.jpg) |
| `screenshots/app/v2.x/友情链接.jpg` | v2.x 友情链接页 | 309.9 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/app/v2.x/%E5%8F%8B%E6%83%85%E9%93%BE%E6%8E%A5.jpg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v2.x/%E5%8F%8B%E6%83%85%E9%93%BE%E6%8E%A5.jpg) |
| `screenshots/app/v2.x/联系博主.jpg` | v2.x 联系博主页 | 187.1 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/app/v2.x/%E8%81%94%E7%B3%BB%E5%8D%9A%E4%B8%BB.jpg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v2.x/%E8%81%94%E7%B3%BB%E5%8D%9A%E4%B8%BB.jpg) |
| `screenshots/app/v2.x/关于.jpg` | v2.x 关于页 | 295.5 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/app/v2.x/%E5%85%B3%E4%BA%8E.jpg) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v2.x/%E5%85%B3%E4%BA%8E.jpg) |

#### v3.x

| 文件路径 | 说明 | 大小 | 加速访问 | raw 访问 |
|---|---|---|---|---|
| `screenshots/app/v3.x/首页.png` | v3.x 首页（轮播、快捷导航、分类入口） | 853.5 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/app/v3.x/%E9%A6%96%E9%A1%B5.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v3.x/%E9%A6%96%E9%A1%B5.png) |
| `screenshots/app/v3.x/首页-公告弹窗.png` | v3.x 首页公告弹窗 | 892.9 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/app/v3.x/%E9%A6%96%E9%A1%B5-%E5%85%AC%E5%91%8A%E5%BC%B9%E7%AA%97.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v3.x/%E9%A6%96%E9%A1%B5-%E5%85%AC%E5%91%8A%E5%BC%B9%E7%AA%97.png) |
| `screenshots/app/v3.x/分类.png` | v3.x 分类页（全部分类聚合，支持筛选与订阅） | 684.1 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/app/v3.x/%E5%88%86%E7%B1%BB.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v3.x/%E5%88%86%E7%B1%BB.png) |
| `screenshots/app/v3.x/图库.png` | v3.x 图库页（我的图库与收藏） | 1151.3 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/app/v3.x/%E5%9B%BE%E5%BA%93.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v3.x/%E5%9B%BE%E5%BA%93.png) |
| `screenshots/app/v3.x/瞬间.png` | v3.x 瞬间页（瞬间列表） | 747.0 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/app/v3.x/%E7%9E%AC%E9%97%B4.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v3.x/%E7%9E%AC%E9%97%B4.png) |
| `screenshots/app/v3.x/博主.png` | v3.x 博主主页 | 636.5 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/app/v3.x/%E5%8D%9A%E4%B8%BB.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v3.x/%E5%8D%9A%E4%B8%BB.png) |
| `screenshots/app/v3.x/用户侧边栏.png` | 登录后的用户弹层 | 413.4 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/app/v3.x/%E7%94%A8%E6%88%B7%E4%BE%A7%E8%BE%B9%E6%A0%8F.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v3.x/%E7%94%A8%E6%88%B7%E4%BE%A7%E8%BE%B9%E6%A0%8F.png) |
| `screenshots/app/v3.x/恋爱日记.png` | 恋爱模块主页 | 652.8 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/app/v3.x/%E6%81%8B%E7%88%B1%E6%97%A5%E8%AE%B0.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v3.x/%E6%81%8B%E7%88%B1%E6%97%A5%E8%AE%B0.png) |
| `screenshots/app/v3.x/恋爱相册.png` | 情侣相册列表（支持密码锁定） | 452.9 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/app/v3.x/%E6%81%8B%E7%88%B1%E7%9B%B8%E5%86%8C.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v3.x/%E6%81%8B%E7%88%B1%E7%9B%B8%E5%86%8C.png) |
| `screenshots/app/v3.x/恋爱相册-照片.png` | 恋爱相册照片列表 | 522.9 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/app/v3.x/%E6%81%8B%E7%88%B1%E7%9B%B8%E5%86%8C-%E7%85%A7%E7%89%87.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v3.x/%E6%81%8B%E7%88%B1%E7%9B%B8%E5%86%8C-%E7%85%A7%E7%89%87.png) |
| `screenshots/app/v3.x/恋爱相册-解锁.png` | 恋爱相册密码解锁 | 371.3 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/app/v3.x/%E6%81%8B%E7%88%B1%E7%9B%B8%E5%86%8C-%E8%A7%A3%E9%94%81.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v3.x/%E6%81%8B%E7%88%B1%E7%9B%B8%E5%86%8C-%E8%A7%A3%E9%94%81.png) |
| `screenshots/app/v3.x/恋爱清单.png` | 恋爱清单（想一起完成的事） | 550.5 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/app/v3.x/%E6%81%8B%E7%88%B1%E6%B8%85%E5%8D%95.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v3.x/%E6%81%8B%E7%88%B1%E6%B8%85%E5%8D%95.png) |
| `screenshots/app/v3.x/恋爱故事.png` | 恋爱故事图文记录 | 287.3 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/app/v3.x/%E6%81%8B%E7%88%B1%E6%95%85%E4%BA%8B.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v3.x/%E6%81%8B%E7%88%B1%E6%95%85%E4%BA%8B.png) |
| `screenshots/app/v3.x/相册管理.png` | 移动端恋爱相册管理 | 322.2 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/app/v3.x/%E7%9B%B8%E5%86%8C%E7%AE%A1%E7%90%86.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v3.x/%E7%9B%B8%E5%86%8C%E7%AE%A1%E7%90%86.png) |
| `screenshots/app/v3.x/日记管理.png` | 移动端恋爱清单/日记管理 | 127.2 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/app/v3.x/%E6%97%A5%E8%AE%B0%E7%AE%A1%E7%90%86.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v3.x/%E6%97%A5%E8%AE%B0%E7%AE%A1%E7%90%86.png) |
| `screenshots/app/v3.x/故事管理.png` | 移动端恋爱故事管理 | 123.8 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/app/v3.x/%E6%95%85%E4%BA%8B%E7%AE%A1%E7%90%86.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v3.x/%E6%95%85%E4%BA%8B%E7%AE%A1%E7%90%86.png) |
| `screenshots/app/v3.x/瞬间管理.png` | 移动端瞬间发布与管理 | 124.0 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/app/v3.x/%E7%9E%AC%E9%97%B4%E7%AE%A1%E7%90%86.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v3.x/%E7%9E%AC%E9%97%B4%E7%AE%A1%E7%90%86.png) |
| `screenshots/app/v3.x/偏好设置-弹窗.png` | 应用偏好设置弹窗 | 548.3 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/app/v3.x/%E5%81%8F%E5%A5%BD%E8%AE%BE%E7%BD%AE-%E5%BC%B9%E7%AA%97.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v3.x/%E5%81%8F%E5%A5%BD%E8%AE%BE%E7%BD%AE-%E5%BC%B9%E7%AA%97.png) |

### 插件截图 / screenshots/plugin

Halo 插件控制台与前台模板截图。

#### v3.x

| 文件路径 | 说明 | 大小 | 加速访问 | raw 访问 |
|---|---|---|---|---|
| `screenshots/plugin/v3.x/控制台首页.png` | 插件控制台首页 | 122.0 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/plugin/v3.x/%E6%8E%A7%E5%88%B6%E5%8F%B0%E9%A6%96%E9%A1%B5.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/plugin/v3.x/%E6%8E%A7%E5%88%B6%E5%8F%B0%E9%A6%96%E9%A1%B5.png) |
| `screenshots/plugin/v3.x/应用管理.png` | 应用管理页 | 27.4 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/plugin/v3.x/%E5%BA%94%E7%94%A8%E7%AE%A1%E7%90%86.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/plugin/v3.x/%E5%BA%94%E7%94%A8%E7%AE%A1%E7%90%86.png) |
| `screenshots/plugin/v3.x/公告管理.png` | 公告管理页 | 31.6 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/plugin/v3.x/%E5%85%AC%E5%91%8A%E7%AE%A1%E7%90%86.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/plugin/v3.x/%E5%85%AC%E5%91%8A%E7%AE%A1%E7%90%86.png) |
| `screenshots/plugin/v3.x/横幅管理.png` | 横幅管理页 | 33.7 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/plugin/v3.x/%E6%A8%AA%E5%B9%85%E7%AE%A1%E7%90%86.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/plugin/v3.x/%E6%A8%AA%E5%B9%85%E7%AE%A1%E7%90%86.png) |
| `screenshots/plugin/v3.x/友链管理.png` | 友情链接管理页 | 35.1 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/plugin/v3.x/%E5%8F%8B%E9%93%BE%E7%AE%A1%E7%90%86.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/plugin/v3.x/%E5%8F%8B%E9%93%BE%E7%AE%A1%E7%90%86.png) |
| `screenshots/plugin/v3.x/恋爱管理.png` | 恋爱模块管理页 | 152.7 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/plugin/v3.x/%E6%81%8B%E7%88%B1%E7%AE%A1%E7%90%86.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/plugin/v3.x/%E6%81%8B%E7%88%B1%E7%AE%A1%E7%90%86.png) |
| `screenshots/plugin/v3.x/审核配置.png` | 投稿内容审核策略配置 | 41.4 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/plugin/v3.x/%E5%AE%A1%E6%A0%B8%E9%85%8D%E7%BD%AE.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/plugin/v3.x/%E5%AE%A1%E6%A0%B8%E9%85%8D%E7%BD%AE.png) |
| `screenshots/plugin/v3.x/功能配置.png` | 功能开关配置 | 51.5 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/plugin/v3.x/%E5%8A%9F%E8%83%BD%E9%85%8D%E7%BD%AE.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/plugin/v3.x/%E5%8A%9F%E8%83%BD%E9%85%8D%E7%BD%AE.png) |
| `screenshots/plugin/v3.x/插件设置-基本设置.png` | 插件基本设置 | 28.3 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/plugin/v3.x/%E6%8F%92%E4%BB%B6%E8%AE%BE%E7%BD%AE-%E5%9F%BA%E6%9C%AC%E8%AE%BE%E7%BD%AE.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/plugin/v3.x/%E6%8F%92%E4%BB%B6%E8%AE%BE%E7%BD%AE-%E5%9F%BA%E6%9C%AC%E8%AE%BE%E7%BD%AE.png) |
| `screenshots/plugin/v3.x/插件设置-安全控制.png` | 验证码等安全控制 | 38.0 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/plugin/v3.x/%E6%8F%92%E4%BB%B6%E8%AE%BE%E7%BD%AE-%E5%AE%89%E5%85%A8%E6%8E%A7%E5%88%B6.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/plugin/v3.x/%E6%8F%92%E4%BB%B6%E8%AE%BE%E7%BD%AE-%E5%AE%89%E5%85%A8%E6%8E%A7%E5%88%B6.png) |
| `screenshots/plugin/v3.x/插件设置-平台接入.png` | 平台接入配置 | 25.2 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/plugin/v3.x/%E6%8F%92%E4%BB%B6%E8%AE%BE%E7%BD%AE-%E5%B9%B3%E5%8F%B0%E6%8E%A5%E5%85%A5.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/plugin/v3.x/%E6%8F%92%E4%BB%B6%E8%AE%BE%E7%BD%AE-%E5%B9%B3%E5%8F%B0%E6%8E%A5%E5%85%A5.png) |
| `screenshots/plugin/v3.x/插件设置-主题展示.png` | 主题组件（应用展示）配置 | 34.9 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/plugin/v3.x/%E6%8F%92%E4%BB%B6%E8%AE%BE%E7%BD%AE-%E4%B8%BB%E9%A2%98%E5%B1%95%E7%A4%BA.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/plugin/v3.x/%E6%8F%92%E4%BB%B6%E8%AE%BE%E7%BD%AE-%E4%B8%BB%E9%A2%98%E5%B1%95%E7%A4%BA.png) |
| `screenshots/plugin/v3.x/插件设置-移动端登录.png` | 移动端登录开关 | 41.5 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/plugin/v3.x/%E6%8F%92%E4%BB%B6%E8%AE%BE%E7%BD%AE-%E7%A7%BB%E5%8A%A8%E7%AB%AF%E7%99%BB%E5%BD%95.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/plugin/v3.x/%E6%8F%92%E4%BB%B6%E8%AE%BE%E7%BD%AE-%E7%A7%BB%E5%8A%A8%E7%AB%AF%E7%99%BB%E5%BD%95.png) |
| `screenshots/plugin/v3.x/前台模板.png` | 恋爱日记前台模板主页 | 582.1 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/plugin/v3.x/%E5%89%8D%E5%8F%B0%E6%A8%A1%E6%9D%BF.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/plugin/v3.x/%E5%89%8D%E5%8F%B0%E6%A8%A1%E6%9D%BF.png) |
| `screenshots/plugin/v3.x/前台模板-恋爱相册.png` | 前台模板：恋爱相册 | 572.2 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/plugin/v3.x/%E5%89%8D%E5%8F%B0%E6%A8%A1%E6%9D%BF-%E6%81%8B%E7%88%B1%E7%9B%B8%E5%86%8C.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/plugin/v3.x/%E5%89%8D%E5%8F%B0%E6%A8%A1%E6%9D%BF-%E6%81%8B%E7%88%B1%E7%9B%B8%E5%86%8C.png) |
| `screenshots/plugin/v3.x/前台模板-恋爱清单.png` | 前台模板：恋爱清单 | 562.2 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/plugin/v3.x/%E5%89%8D%E5%8F%B0%E6%A8%A1%E6%9D%BF-%E6%81%8B%E7%88%B1%E6%B8%85%E5%8D%95.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/plugin/v3.x/%E5%89%8D%E5%8F%B0%E6%A8%A1%E6%9D%BF-%E6%81%8B%E7%88%B1%E6%B8%85%E5%8D%95.png) |
| `screenshots/plugin/v3.x/前台模板-恋爱故事.png` | 前台模板：恋爱故事 | 484.8 KB | [加速](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/screenshots/plugin/v3.x/%E5%89%8D%E5%8F%B0%E6%A8%A1%E6%9D%BF-%E6%81%8B%E7%88%B1%E6%95%85%E4%BA%8B.png) | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/plugin/v3.x/%E5%89%8D%E5%8F%B0%E6%A8%A1%E6%9D%BF-%E6%81%8B%E7%88%B1%E6%95%85%E4%BA%8B.png) |

## 四、预留目录（暂无文件）

该目录目前只有占位文件（`.gitkeep`），用于后续资源归档：

| 目录 | 用途 |
|---|---|
| `videos/` | 演示视频资源 |

## 五、维护约定

1. **新增 / 删除资源后，请同步更新本文件**，保持清单与实际文件一致。
2. `docs/data/*.json` 是**线上文档站的运行时数据源**（`uni-halo-doc` 生产环境 base 为 `https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/docs`），改动会直接影响线上；DEV 环境读本地 `uni-halo-doc/src/public/data/*.json`，两边需保持一致。
3. 大文件优先放 `images/`、`videos/`，并注意 jsDelivr 单文件 20 MB 限制。
4. `docs/data/ads.json` 中的 `cover` 字段为 `/ads/**` 站内路径，对应图片**尚未入库**，引用前需补传，否则线上会 404。
5. `README.md` 里的 Gitee 地址指向 `gitee.com/uni-halo/uni-halo-static-resources`，该镜像未经核实（当前远端只有 GitHub），引用前请自行确认。
6. 文档站 `design/pages.md` 中引用的 `screenshots/app/v3.x/登录.png`、`注册.png`、`微信绑定.png` 等文件**尚未入库**（本清单中不存在），引用前需补传，否则线上会 404。
