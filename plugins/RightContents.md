# 1、右侧目录
使屏幕右侧出现文章的目录,按需配置即可.

## 1.1、配置

```markdown
<script>
window.$docsify = {
  toc: {
    tocMaxLevel: 5,
    target: 'h2, h3, h4, h5, h6',
    ignoreHeader:  ['<!-- {docsify-ignore} -->', '<!-- {docsify-ignore-all} -->']
  },
}
</script>

<!-- 文章内右侧目录 -->
<link rel="stylesheet" href="https://unpkg.com/docsify-plugin-toc@1.3.1/dist/light.css">
<!-- 文章内右侧目录 -->
<script src="https://unpkg.com/docsify-plugin-toc@1.3.1/dist/docsify-plugin-toc.min.js"></script>
```



