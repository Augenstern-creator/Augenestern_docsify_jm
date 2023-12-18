# 1、顶部导航栏失效
官方文档中在配置顶部导航栏时，配置文件如下:
```html
<!-- index.html -->

<script>
  window.$docsify = {
    loadNavbar: true
  }
</script>
<script src="//cdn.jsdelivr.net/npm/docsify/lib/docsify.min.js"></script>
```

> [!Warning]
> 上方的`script`标签不需要加，只需添加`loadNavbar: true`，并在根目录下创建 `_navbar.md` 导航文件即可.