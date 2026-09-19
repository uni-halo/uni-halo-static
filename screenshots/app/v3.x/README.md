# 截图资源清单（RESOURCE）

> 本清单列出 `screenshots/` 目录下**约定使用**的截图文件名与对应的功能/页面名称，用于各项目（应用 README、文档站、官网 showcase）引用。
>
> **补图约定**：按下方文件名命名图片放入对应目录即可被自动引用，无需改动代码。
> - 应用截图目录：`screenshots/app/v3.x/`
> - 插件控制台截图目录：`screenshots/plugin/v3.x/`
> - 应用截图在官网的自动展示逻辑见 `uni-halo-website/src/data/showcase.ts`（按页面 key 拼接文件名）。

**访问地址模板**（`{文件路径}` 为下方表格中「文件路径」列的值，中文需 percent-encoding）：

| 类型 | 地址模板 |
|---|---|
| **加速访问**（推荐） | `https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/{文件路径}` |
| **raw 访问** | `https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/{文件路径}` |

## 一、应用截图（app/v3.x/）

### TabBar 页面

| 文件名 | 功能名称 | 说明 | 文件路径 | raw 地址 | CDN |
|--------|----------|------|----------|----------|----------|
| `首页.png` | 首页 | 轮播图、快捷导航、分类入口、公告 | `screenshots/app/v3.x/首页.png` | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v3.x/%E9%A6%96%E9%A1%B5.png) | [CDN](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v3.x/%E9%A6%96%E9%A1%B5.png) |
| `分类.png` | 分类 | 全部分类聚合，支持筛选与订阅 | `screenshots/app/v3.x/分类.png` | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v3.x/%E5%88%86%E7%B1%BB.png) | [CDN](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v3.x/%E5%88%86%E7%B1%BB.png) |
| `图库.png` | 图库 | 我的图库与收藏 | `screenshots/app/v3.x/图库.png` | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v3.x/%E5%9B%BE%E5%BA%93.png) | [CDN](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v3.x/%E5%9B%BE%E5%BA%93.png) |
| `瞬间.png` | 瞬间 | 瞬间列表（说说/动态） | `screenshots/app/v3.x/瞬间.png` | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v3.x/%E7%9E%AC%E9%97%B4.png) | [CDN](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v3.x/%E7%9E%AC%E9%97%B4.png) |
| `博主.png` | 博主 | 博主主页（blogger tab，登录后可进入个人中心） | `screenshots/app/v3.x/博主.png` | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v3.x/%E5%8D%9A%E4%B8%BB.png) | [CDN](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v3.x/%E5%8D%9A%E4%B8%BB.png) |

### 登录与个人界面

| 文件名 | 功能名称 | 说明 | 文件路径 | raw 地址 | CDN |
|--------|----------|------|----------|----------|----------|
| `用户侧边栏.png` | 用户侧边栏 | 登录后的用户弹层（uh-user-popup，含个人中心/管理入口） | `screenshots/app/v3.x/用户侧边栏.png` | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v3.x/%E7%94%A8%E6%88%B7%E4%BE%A7%E8%BE%B9%E6%A0%8F.png) | [CDN](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v3.x/%E7%94%A8%E6%88%B7%E4%BE%A7%E8%BE%B9%E6%A0%8F.png) |
| `我的主页.png` | 我的主页 | 博主 tab 内的个人主页（登录态） | `screenshots/app/v3.x/我的主页.png` | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v3.x/%E6%88%91%E7%9A%84%E4%B8%BB%E9%A1%B5.png) | [CDN](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v3.x/%E6%88%91%E7%9A%84%E4%B8%BB%E9%A1%B5.png) |
| `个人资料.png` | 我的资料 | 我的资料编辑（my-profile） | `screenshots/app/v3.x/个人资料.png` | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v3.x/%E4%B8%AA%E4%BA%BA%E8%B5%84%E6%96%99.png) | [CDN](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v3.x/%E4%B8%AA%E4%BA%BA%E8%B5%84%E6%96%99.png) |
| `用户主页.png` | 用户主页 | 他人用户主页（user-profile） | `screenshots/app/v3.x/用户主页.png` | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v3.x/%E7%94%A8%E6%88%B7%E4%B8%BB%E9%A1%B5.png) | [CDN](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v3.x/%E7%94%A8%E6%88%B7%E4%B8%BB%E9%A1%B5.png) |
| `登录.png` | 登录 | 账号密码登录 | `screenshots/app/v3.x/登录.png` | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v3.x/%E7%99%BB%E5%BD%95.png) | [CDN](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v3.x/%E7%99%BB%E5%BD%95.png) |
| `注册.png` | 注册 | 账号注册 | `screenshots/app/v3.x/注册.png` | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v3.x/%E6%B3%A8%E5%86%8C.png) | [CDN](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v3.x/%E6%B3%A8%E5%86%8C.png) |
| `微信绑定.png` | 微信绑定 | 微信账号绑定管理 | `screenshots/app/v3.x/微信绑定.png` | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v3.x/%E5%BE%AE%E4%BF%A1%E7%BB%91%E5%AE%9A.png) | [CDN](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v3.x/%E5%BE%AE%E4%BF%A1%E7%BB%91%E5%AE%9A.png) |

### 内容页面

| 文件名 | 功能名称 | 说明 | 文件路径 | raw 地址 | CDN |
|--------|----------|------|----------|----------|----------|
| `文章列表.png` | 文章列表 | 全部文章 | `screenshots/app/v3.x/文章列表.png` | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v3.x/%E6%96%87%E7%AB%A0%E5%88%97%E8%A1%A8.png) | [CDN](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v3.x/%E6%96%87%E7%AB%A0%E5%88%97%E8%A1%A8.png) |
| `文章详情.png` | 文章详情 | 文章阅读页 | `screenshots/app/v3.x/文章详情.png` | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v3.x/%E6%96%87%E7%AB%A0%E8%AF%A6%E6%83%85.png) | [CDN](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v3.x/%E6%96%87%E7%AB%A0%E8%AF%A6%E6%83%85.png) |
| `归档.png` | 归档 | 文章时间归档 | `screenshots/app/v3.x/归档.png` | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v3.x/%E5%BD%92%E6%A1%A3.png) | [CDN](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v3.x/%E5%BD%92%E6%A1%A3.png) |
| `标签.png` | 标签 | 标签聚合 | `screenshots/app/v3.x/标签.png` | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v3.x/%E6%A0%87%E7%AD%BE.png) | [CDN](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v3.x/%E6%A0%87%E7%AD%BE.png) |
| `标签详情.png` | 标签详情 | 某标签下的文章 | `screenshots/app/v3.x/标签详情.png` | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v3.x/%E6%A0%87%E7%AD%BE%E8%AF%A6%E6%83%85.png) | [CDN](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v3.x/%E6%A0%87%E7%AD%BE%E8%AF%A6%E6%83%85.png) |
| `分类详情.png` | 分类详情 | 某分类下的文章 | `screenshots/app/v3.x/分类详情.png` | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v3.x/%E5%88%86%E7%B1%BB%E8%AF%A6%E6%83%85.png) | [CDN](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v3.x/%E5%88%86%E7%B1%BB%E8%AF%A6%E6%83%85.png) |
| `搜索.png` | 内容搜索 | 关键词搜索文章 / 瞬间 / 图库 | `screenshots/app/v3.x/搜索.png` | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v3.x/%E6%90%9C%E7%B4%A2.png) | [CDN](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v3.x/%E6%90%9C%E7%B4%A2.png) |
| `轮播详情.png` | 轮播详情 | 首页轮播点击后的落地页 | `screenshots/app/v3.x/轮播详情.png` | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v3.x/%E8%BD%AE%E6%92%AD%E8%AF%A6%E6%83%85.png) | [CDN](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v3.x/%E8%BD%AE%E6%92%AD%E8%AF%A6%E6%83%85.png) |
| `瞬间详情.png` | 瞬间详情 | 单条瞬间的大图与详情 | `screenshots/app/v3.x/瞬间详情.png` | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v3.x/%E7%9E%AC%E9%97%B4%E8%AF%A6%E6%83%85.png) | [CDN](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v3.x/%E7%9E%AC%E9%97%B4%E8%AF%A6%E6%83%85.png) |
| `公告中心.png` | 公告中心 | 站点公告列表 | `screenshots/app/v3.x/公告中心.png` | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v3.x/%E5%85%AC%E5%91%8A%E4%B8%AD%E5%BF%83.png) | [CDN](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v3.x/%E5%85%AC%E5%91%8A%E4%B8%AD%E5%BF%83.png) |
| `公告详情.png` | 公告详情 | 公告内容页 | `screenshots/app/v3.x/公告详情.png` | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v3.x/%E5%85%AC%E5%91%8A%E8%AF%A6%E6%83%85.png) | [CDN](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v3.x/%E5%85%AC%E5%91%8A%E8%AF%A6%E6%83%85.png) |
| `友情链接.png` | 友情链接 | 友链分组展示与投稿申请 | `screenshots/app/v3.x/友情链接.png` | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v3.x/%E5%8F%8B%E6%83%85%E9%93%BE%E6%8E%A5.png) | [CDN](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v3.x/%E5%8F%8B%E6%83%85%E9%93%BE%E6%8E%A5.png) |
| `投票中心.png` | 投票中心 | 投票列表 | `screenshots/app/v3.x/投票中心.png` | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v3.x/%E6%8A%95%E7%A5%A8%E4%B8%AD%E5%BF%83.png) | [CDN](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v3.x/%E6%8A%95%E7%A5%A8%E4%B8%AD%E5%BF%83.png) |
| `投票详情.png` | 投票详情 | 投票参与页 | `screenshots/app/v3.x/投票详情.png` | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v3.x/%E6%8A%95%E7%A5%A8%E8%AF%A6%E6%83%85.png) | [CDN](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v3.x/%E6%8A%95%E7%A5%A8%E8%AF%A6%E6%83%85.png) |
| `数据看板.png` | 数据看板 | 站点数据统计可视化 | `screenshots/app/v3.x/数据看板.png` | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v3.x/%E6%95%B0%E6%8D%AE%E7%9C%8B%E6%9D%BF.png) | [CDN](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v3.x/%E6%95%B0%E6%8D%AE%E7%9C%8B%E6%9D%BF.png) |
| `联系博主.png` | 联系博主 | 留言/联系表单 | `screenshots/app/v3.x/联系博主.png` | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v3.x/%E8%81%94%E7%B3%BB%E5%8D%9A%E4%B8%BB.png) | [CDN](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v3.x/%E8%81%94%E7%B3%BB%E5%8D%9A%E4%B8%BB.png) |
| `免责声明.png` | 免责声明 | 免责声明页 | `screenshots/app/v3.x/免责声明.png` | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v3.x/%E5%85%8D%E8%B4%A3%E5%A3%B0%E6%98%8E.png) | [CDN](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v3.x/%E5%85%8D%E8%B4%A3%E5%A3%B0%E6%98%8E.png) |
| `收藏.png` | 我的收藏 | 收藏内容列表 | `screenshots/app/v3.x/收藏.png` | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v3.x/%E6%94%B6%E8%97%8F.png) | [CDN](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v3.x/%E6%94%B6%E8%97%8F.png) |
| `偏好设置.png` | 偏好设置 | 应用偏好设置 | `screenshots/app/v3.x/偏好设置.png` | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v3.x/%E5%81%8F%E5%A5%BD%E8%AE%BE%E7%BD%AE.png) | [CDN](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v3.x/%E5%81%8F%E5%A5%BD%E8%AE%BE%E7%BD%AE.png) |
| `维护模式.png` | 维护模式 | 站点维护提示页 | `screenshots/app/v3.x/维护模式.png` | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v3.x/%E7%BB%B4%E6%8A%A4%E6%A8%A1%E5%BC%8F.png) | [CDN](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v3.x/%E7%BB%B4%E6%8A%A4%E6%A8%A1%E5%BC%8F.png) |

### 恋爱日记

| 文件名 | 功能名称 | 说明 | 文件路径 | raw 地址 | CDN |
|--------|----------|------|----------|----------|----------|
| `恋爱日记.jpg` | 恋爱日记 | 恋爱模块主页（README 使用，保持此文件名） | `screenshots/app/v3.x/恋爱日记.jpg` | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v3.x/%E6%81%8B%E7%88%B1%E6%97%A5%E8%AE%B0.jpg) | [CDN](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v3.x/%E6%81%8B%E7%88%B1%E6%97%A5%E8%AE%B0.jpg) |
| `恋爱日记.png` | 恋爱日记 | 恋爱模块主页（展示用） | `screenshots/app/v3.x/恋爱日记.png` | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v3.x/%E6%81%8B%E7%88%B1%E6%97%A5%E8%AE%B0.png) | [CDN](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v3.x/%E6%81%8B%E7%88%B1%E6%97%A5%E8%AE%B0.png) |
| `恋爱相册.png` | 恋爱相册 | 情侣相册列表（支持密码锁定） | `screenshots/app/v3.x/恋爱相册.png` | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v3.x/%E6%81%8B%E7%88%B1%E7%9B%B8%E5%86%8C.png) | [CDN](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v3.x/%E6%81%8B%E7%88%B1%E7%9B%B8%E5%86%8C.png) |
| `恋爱清单.png` | 恋爱清单 | 想一起完成的事 | `screenshots/app/v3.x/恋爱清单.png` | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v3.x/%E6%81%8B%E7%88%B1%E6%B8%85%E5%8D%95.png) | [CDN](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v3.x/%E6%81%8B%E7%88%B1%E6%B8%85%E5%8D%95.png) |
| `恋爱故事.png` | 我们的故事 | 恋爱故事图文记录 | `screenshots/app/v3.x/恋爱故事.png` | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v3.x/%E6%81%8B%E7%88%B1%E6%95%85%E4%BA%8B.png) | [CDN](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v3.x/%E6%81%8B%E7%88%B1%E6%95%85%E4%BA%8B.png) |

### 移动端管理（管理员）

| 文件名 | 功能名称 | 说明 | 文件路径 | raw 地址 | CDN |
|--------|----------|------|----------|----------|----------|
| `相册管理.png` | 相册管理 | 移动端恋爱相册管理 | `screenshots/app/v3.x/相册管理.png` | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v3.x/%E7%9B%B8%E5%86%8C%E7%AE%A1%E7%90%86.png) | [CDN](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v3.x/%E7%9B%B8%E5%86%8C%E7%AE%A1%E7%90%86.png) |
| `日记管理.png` | 日记管理 | 移动端恋爱清单/日记管理 | `screenshots/app/v3.x/日记管理.png` | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v3.x/%E6%97%A5%E8%AE%B0%E7%AE%A1%E7%90%86.png) | [CDN](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v3.x/%E6%97%A5%E8%AE%B0%E7%AE%A1%E7%90%86.png) |
| `故事管理.png` | 故事管理 | 移动端恋爱故事管理 | `screenshots/app/v3.x/故事管理.png` | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v3.x/%E6%95%85%E4%BA%8B%E7%AE%A1%E7%90%86.png) | [CDN](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v3.x/%E6%95%85%E4%BA%8B%E7%AE%A1%E7%90%86.png) |
| `瞬间管理.png` | 瞬间管理 | 移动端瞬间发布与管理 | `screenshots/app/v3.x/瞬间管理.png` | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/app/v3.x/%E7%9E%AC%E9%97%B4%E7%AE%A1%E7%90%86.png) | [CDN](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/app/v3.x/%E7%9E%AC%E9%97%B4%E7%AE%A1%E7%90%86.png) |

## 二、插件控制台截图（plugin/v3.x/）

### 恋爱日记前台模板（主题接入，共 4 页）

| 文件名 | 功能名称 | 说明 | 文件路径 | raw 地址 | CDN |
|--------|----------|------|----------|----------|----------|
| `前台模板.png` | 恋爱日记主页 | 前台模板：恋爱日记主页效果 | `screenshots/plugin/v3.x/前台模板.png` | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/plugin/v3.x/%E5%89%8D%E5%8F%B0%E6%A8%A1%E6%9D%BF.png) | [CDN](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/plugin/v3.x/%E5%89%8D%E5%8F%B0%E6%A8%A1%E6%9D%BF.png) |
| `前台模板-恋爱相册.png` | 恋爱相册 | 前台模板：恋爱相册页效果 | `screenshots/plugin/v3.x/前台模板-恋爱相册.png` | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/plugin/v3.x/%E5%89%8D%E5%8F%B0%E6%A8%A1%E6%9D%BF-%E6%81%8B%E7%88%B1%E7%9B%B8%E5%86%8C.png) | [CDN](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/plugin/v3.x/%E5%89%8D%E5%8F%B0%E6%A8%A1%E6%9D%BF-%E6%81%8B%E7%88%B1%E7%9B%B8%E5%86%8C.png) |
| `前台模板-恋爱清单.png` | 恋爱清单 | 前台模板：恋爱清单页效果 | `screenshots/plugin/v3.x/前台模板-恋爱清单.png` | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/plugin/v3.x/%E5%89%8D%E5%8F%B0%E6%A8%A1%E6%9D%BF-%E6%81%8B%E7%88%B1%E6%B8%85%E5%8D%95.png) | [CDN](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/plugin/v3.x/%E5%89%8D%E5%8F%B0%E6%A8%A1%E6%9D%BF-%E6%81%8B%E7%88%B1%E6%B8%85%E5%8D%95.png) |
| `前台模板-恋爱故事.png` | 我们的故事 | 前台模板：恋爱故事页效果 | `screenshots/plugin/v3.x/前台模板-恋爱故事.png` | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/plugin/v3.x/%E5%89%8D%E5%8F%B0%E6%A8%A1%E6%9D%BF-%E6%81%8B%E7%88%B1%E6%95%85%E4%BA%8B.png) | [CDN](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/plugin/v3.x/%E5%89%8D%E5%8F%B0%E6%A8%A1%E6%9D%BF-%E6%81%8B%E7%88%B1%E6%95%85%E4%BA%8B.png) |

### 插件控制台

| 文件名 | 功能名称 | 说明 | 文件路径 | raw 地址 | CDN |
|--------|----------|------|----------|----------|----------|
| `控制台首页.png` | 欢迎页 | 插件概览与快捷入口 | `screenshots/plugin/v3.x/控制台首页.png` | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/plugin/v3.x/%E6%8E%A7%E5%88%B6%E5%8F%B0%E9%A6%96%E9%A1%B5.png) | [CDN](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/plugin/v3.x/%E6%8E%A7%E5%88%B6%E5%8F%B0%E9%A6%96%E9%A1%B5.png) |
| `功能配置.png` | 功能配置 | 应用、页面、恋爱、维护等全局配置分组 | `screenshots/plugin/v3.x/功能配置.png` | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/plugin/v3.x/%E5%8A%9F%E8%83%BD%E9%85%8D%E7%BD%AE.png) | [CDN](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/plugin/v3.x/%E5%8A%9F%E8%83%BD%E9%85%8D%E7%BD%AE.png) |
| `应用管理.png` | 应用管理 | 应用信息、应用版本维护 | `screenshots/plugin/v3.x/应用管理.png` | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/plugin/v3.x/%E5%BA%94%E7%94%A8%E7%AE%A1%E7%90%86.png) | [CDN](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/plugin/v3.x/%E5%BA%94%E7%94%A8%E7%AE%A1%E7%90%86.png) |
| `横幅管理.png` | 横幅管理 | 小程序轮播图配置 | `screenshots/plugin/v3.x/横幅管理.png` | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/plugin/v3.x/%E6%A8%AA%E5%B9%85%E7%AE%A1%E7%90%86.png) | [CDN](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/plugin/v3.x/%E6%A8%AA%E5%B9%85%E7%AE%A1%E7%90%86.png) |
| `友链管理.png` | 友链管理 | 友链分组、友链信息、投稿审核 | `screenshots/plugin/v3.x/友链管理.png` | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/plugin/v3.x/%E5%8F%8B%E9%93%BE%E7%AE%A1%E7%90%86.png) | [CDN](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/plugin/v3.x/%E5%8F%8B%E9%93%BE%E7%AE%A1%E7%90%86.png) |
| `公告管理.png` | 公告管理 | 公告类型、公告内容维护 | `screenshots/plugin/v3.x/公告管理.png` | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/plugin/v3.x/%E5%85%AC%E5%91%8A%E7%AE%A1%E7%90%86.png) | [CDN](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/plugin/v3.x/%E5%85%AC%E5%91%8A%E7%AE%A1%E7%90%86.png) |
| `恋爱管理.png` | 恋爱管理 | 恋爱相册、恋爱清单、我们的故事 | `screenshots/plugin/v3.x/恋爱管理.png` | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/plugin/v3.x/%E6%81%8B%E7%88%B1%E7%AE%A1%E7%90%86.png) | [CDN](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/plugin/v3.x/%E6%81%8B%E7%88%B1%E7%AE%A1%E7%90%86.png) |
| `审核配置.png` | 审核配置 | 投稿内容的候选与审核策略 | `screenshots/plugin/v3.x/审核配置.png` | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/plugin/v3.x/%E5%AE%A1%E6%A0%B8%E9%85%8D%E7%BD%AE.png) | [CDN](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/plugin/v3.x/%E5%AE%A1%E6%A0%B8%E9%85%8D%E7%BD%AE.png) |
| `插件设置-基本设置.png` | 基本设置 | 邮件通知等基本配置 | `screenshots/plugin/v3.x/插件设置-基本设置.png` | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/plugin/v3.x/%E6%8F%92%E4%BB%B6%E8%AE%BE%E7%BD%AE-%E5%9F%BA%E6%9C%AC%E8%AE%BE%E7%BD%AE.png) | [CDN](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/plugin/v3.x/%E6%8F%92%E4%BB%B6%E8%AE%BE%E7%BD%AE-%E5%9F%BA%E6%9C%AC%E8%AE%BE%E7%BD%AE.png) |
| `插件设置-安全控制.png` | 安全控制 | 验证码配置 | `screenshots/plugin/v3.x/插件设置-安全控制.png` | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/plugin/v3.x/%E6%8F%92%E4%BB%B6%E8%AE%BE%E7%BD%AE-%E5%AE%89%E5%85%A8%E6%8E%A7%E5%88%B6.png) | [CDN](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/plugin/v3.x/%E6%8F%92%E4%BB%B6%E8%AE%BE%E7%BD%AE-%E5%AE%89%E5%85%A8%E6%8E%A7%E5%88%B6.png) |
| `插件设置-平台接入.png` | 平台接入 | 第三方插件（Tools 工具箱）配置 | `screenshots/plugin/v3.x/插件设置-平台接入.png` | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/plugin/v3.x/%E6%8F%92%E4%BB%B6%E8%AE%BE%E7%BD%AE-%E5%B9%B3%E5%8F%B0%E6%8E%A5%E5%85%A5.png) | [CDN](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/plugin/v3.x/%E6%8F%92%E4%BB%B6%E8%AE%BE%E7%BD%AE-%E5%B9%B3%E5%8F%B0%E6%8E%A5%E5%85%A5.png) |
| `插件设置-主题展示.png` | 主题展示 | 主题悬浮窗配置 | `screenshots/plugin/v3.x/插件设置-主题展示.png` | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/plugin/v3.x/%E6%8F%92%E4%BB%B6%E8%AE%BE%E7%BD%AE-%E4%B8%BB%E9%A2%98%E5%B1%95%E7%A4%BA.png) | [CDN](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/plugin/v3.x/%E6%8F%92%E4%BB%B6%E8%AE%BE%E7%BD%AE-%E4%B8%BB%E9%A2%98%E5%B1%95%E7%A4%BA.png) |
| `插件设置-移动端登录.png` | 移动端登录 | 登录开关与微信密钥配置 | `screenshots/plugin/v3.x/插件设置-移动端登录.png` | [raw](https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/screenshots/plugin/v3.x/%E6%8F%92%E4%BB%B6%E8%AE%BE%E7%BD%AE-%E7%A7%BB%E5%8A%A8%E7%AB%AF%E7%99%BB%E5%BD%95.png) | [CDN](https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/screenshots/plugin/v3.x/%E6%8F%92%E4%BB%B6%E8%AE%BE%E7%BD%AE-%E7%A7%BB%E5%8A%A8%E7%AB%AF%E7%99%BB%E5%BD%95.png) |

## 三、使用位置对照

| 引用方 | 引用文件 | 使用的截图 |
|--------|----------|------------|
| `uni-halo/README.md` | 应用主 README | `app/v3.x/`：首页、分类、图库、瞬间、博主、恋爱日记、恋爱相册、恋爱清单、恋爱故事、相册管理、瞬间管理；`plugin/v3.x/`：前台模板 4 页（恋爱日记主页、恋爱相册、恋爱清单、我们的故事） |
| `uni-halo-doc/README.md` | 文档站主 README | `app/v3.x/首页.png`、`分类`、`博主`、`恋爱日记.jpg` |
| `uni-halo-plugin/README.md` | 插件主 README | `app/v3.x/首页.png`、`分类`、`博主`、`恋爱日记.jpg` |
| `uni-halo-doc/src/index.md` | 文档首页「界面预览」块 | `app/v3.x/`：主界面 5 图 + 特色功能 4 图；`plugin/v3.x/`：前台模板 4 页 |
| `uni-halo-doc/src/design/pages.md` | 界面预览页（案例→界面预览） | 全功能模块截图（主界面 / 恋爱日记 / 前台模板 4 页 / 内容页 / 登录个人 / 移动端管理） |
| `uni-halo-plugin/ui/src/views/WelcomeView.vue` | 插件控制台欢迎页「界面预览」 | 同文档首页预览块（主界面 5 图 + 特色功能 4 图 + 前台模板 4 页） |
| `uni-halo-website/src/data/showcase.ts` | 官网功能展示 | `app/v3.x/{页面key}.png`（自动拼接） |
| `uni-halo-doc/src/plugin/console.md` | 文档站控制台功能页 | `plugin/v3.x/` 下的控制台截图（截图占位待补） |
| `uni-halo-doc/src/deploy/config.md` | 文档站插件配置页 | `plugin/v3.x/插件设置-*.png`（截图占位待补） |
