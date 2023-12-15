# 1、Loading提示
在网络不好,文档加载时,出现的Loading提示.

# 1.1、配置
示例:配置`加载中`
```html
<div id="main">加载中</div>

<script>
    window.$docsify = {
        el: '#main'
    }
</script>
```