# 1、字数统计
文章右上角显示字数，阅读时间.

## 1.1、配置

```html
<script>
window.$docsify = {
    // 字数统计
    count:{
        countable:true,
        fontsize:'0.9em',
        color:'rgb(90,90,90)',
        language:'chinese'
    }
}
</script>

<!--字数统计-->
<script src="https://cdn.jsdelivr.net/npm/docsify-count@1.1.0/dist/countable.min.js"></script>
```