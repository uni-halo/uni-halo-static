# Uni Halo v3.x 静态资源

> 全部资源清单（含分类、加速访问与 raw 访问地址）见 [RESOURCES.md](./RESOURCES.md)

## 说明
- docs：对应 `uni-halo-docs` 中的静态资源
- author：作者资源
- images：图片资源
- screenshots：应用截图资源
- videos：视频资源

## 使用方法

以 `images/mp.jpeg` 为例。

### jsDelivr 加速（推荐方式）

**默认推荐：gcore 节点，不带分支后缀**（跟随仓库默认分支，缓存策略对更新最友好）：

```
https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/{文件路径}
例如：https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static/images/mp.jpeg
```

其他可选写法（`@` 后缀）：

```
<!-- @main / @master：锁定分支（跟随该分支最新提交） -->
https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@main/images/mp.jpeg
https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@master/images/mp.jpeg

<!-- @latest：跟随最新 Release（仓库需打 tag 发版，否则可能 404） -->
https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@latest/images/mp.jpeg

<!-- 锁定具体 tag 或 commit sha：适合生产环境长期引用 -->
https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@v1.0.0/images/mp.jpeg
https://gcore.jsdelivr.net/gh/uni-halo/uni-halo-static@<commit-sha>/images/mp.jpeg
```

### jsDelivr 官方节点（备用）

与 gcore 写法一致，仅域名不同，海外访问更稳：

```
https://cdn.jsdelivr.net/gh/uni-halo/uni-halo-static/images/mp.jpeg
```

### GitHub raw

实时生效，不经 CDN 缓存，需带分支名：

```
https://raw.githubusercontent.com/uni-halo/uni-halo-static/{分支名}/{文件路径}
例如：https://raw.githubusercontent.com/uni-halo/uni-halo-static/main/images/mp.jpeg
```

### Gitee

```
https://gitee.com/uni-halo/uni-halo-static-resources/raw/{分支名}/{文件路径}
```

> 缓存刷新：jsDelivr 有缓存，新提交后最快数分钟生效，可访问 `https://purge.jsdelivr.net/gh/uni-halo/uni-halo-static` 主动刷新。