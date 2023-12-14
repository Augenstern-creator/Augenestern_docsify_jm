# 1、阅读进度条
阅读文章浏览器上方显示绿色进度条，按需配置即可

```html
<script>
window.$docsify = {
    progress: {
        position: "top",
        color: "var(--theme-color,#42b983)",
        height: "3px",
    }
}
</script>

<!--阅读进度条美化-->
<script src="https://cdn.jsdelivr.net/npm/docsify-progress@latest/dist/progress.min.js"></script>
```

> [!NOTE]
> [官方CDN]:
> [docsify-progress](https://www.jsdelivr.com/package/npm/docsify-progress)