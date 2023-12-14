# 1、最近更新时间
文章末尾显示最近更新的时间，按需配置即可.

## 1.1、配置
```html
<script>
window.$docsify = {
    // 最后更新时间
    timeUpdater: {
    text: ">最后更新时间: {docsify-updated}",
    formatUpdated: "{YYYY}/{MM}/{DD}",
    whereToPlace: "bottom",  // "top" or "bottom", default to "bottom"
    },
};

</script>

<!--更新时间-->
<script src="https://cdn.jsdelivr.net/npm/docsify-updated/src/time-updater.js"></script>
```

> [!NOTE]
> [官方CDN]:
> [docsify-updated](https://www.jsdelivr.com/package/npm/docsify-updated)