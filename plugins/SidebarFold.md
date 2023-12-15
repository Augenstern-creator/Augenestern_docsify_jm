# 1、左侧边栏目录可折叠
按需配置即可.

# 1.1、配置

```html
<script>
    window.$docsify = {
      name: '',
      repo: '',
      // 开启侧边栏
      loadSidebar: true,
      // 侧边栏目录,设置6层目录
      subMaxLevel: 6,  
    }
</script>

<!-- 侧边栏可折叠 -->
<script src="//cdn.jsdelivr.net/npm/docsify-sidebar-collapse/dist/docsify-sidebar-collapse.min.js"></script>
```