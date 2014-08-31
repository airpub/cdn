# Airpub CDN 服务列表

a collection of Airpub CDN service

### 多说 CDN
多说 CDN 提供 `.css` 和 `.js` CDN，也提供主题文件 CDN，我们推荐你使用多说 CDN 用以实现最快的静态资源加载速度

```html
<!-- Airpub 相关依赖的打包文件 -->
<link rel="stylesheet" href="http://static.duoshuo.com/airpub/airpub-dependencies.min.css?v=0.2.2">
<script src="http://static.duoshuo.com/airpub/airpub-dependencies.min.js?v=0.2.2"></script>
<!-- 默认主题 Chill 的样式表文件 -->
<link rel="stylesheet" href="http://static.duoshuo.com/airpub/themes/chill/0.2.0/css/chill.min.css" />
<link rel="shortcut icon" type="image/x-icon" href="http://static.duoshuo.com/airpub/themes/chill/0.2.0/favicon.ico" />
```

### Airpub.io CDN

Airpub.io CDN 基于 GitHub Pages，只 `.css` 与 `.js` CDN，由于 GitHub Pages 不支持 CORS，因此暂时不提供主题文件 CDN。适合在本地托管主题的用户使用。但由于基于 GitHub，该 CDN 上的静态资源在国外访问的速度较慢。

```html
<!-- Airpub 相关依赖的打包文件 -->
<link rel="stylesheet" href="http://cdn.airpub.io/airpub-dependencies.min.css?v=0.2.2">
<script src="http://cdn.airpub.io/airpub-dependencies.min.js?v=0.2.2"></script>
<!-- Airpub 应用文件 -->
<script src="http://cdn.airpub.io/airpub.min.js?v=0.2.2"></script>
```

### 七牛 CDN

七牛 CDN 是 Airpub 的第一个完整 CDN 服务。但因为 URL 变更原因，暂时不提供新版本的 CDN 服务。