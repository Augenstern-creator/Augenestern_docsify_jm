# 1、全文搜索
在左侧出现全文搜索框.

## 1.1、配置

```html
<script>
  window.$docsify = {
    // 全文搜索
    search: {
      paths: 'auto',
      // 搜索显示框提示语
      placeholder: '🔍 搜索',
      // 搜索不到的提示语  
      noData: '😒 找不到结果',
      // 搜索标题的最大层级, 1 - 6  
      depth: 2
    },
  }
</script>

<!-- 全文搜索 -->
<!-- <script src="//cdn.jsdelivr.net/npm/docsify/lib/docsify.min.js"></script> -->
<script src="//cdn.jsdelivr.net/npm/docsify/lib/plugins/search.min.js"></script>
```
