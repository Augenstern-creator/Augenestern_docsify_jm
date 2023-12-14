# 1、分页导航
在文章末尾增加上一章节导航、下一章节导航，按需配置.

# 1.1、配置

```html
<script>
window.$docsify = {
  // 分页导航
  pagination: {
    previousText: '上一章节',
    nextText: '下一章节',
    crossChapter: true,
    crossChapterText: true,
  },
}

</script>

<!--分页导航-->
<script src="//unpkg.com/docsify-pagination/dist/docsify-pagination.min.js"></script>
```

> [!NOTE]
> [官方CDN]:
> [docsify-pagination](https://www.jsdelivr.com/package/npm/docsify-pagination)