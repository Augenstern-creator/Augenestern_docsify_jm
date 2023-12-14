# 1、回到顶部
网站右下角有回到网页最顶部的按钮手势.

## 1.1、配置

```html
<script>
    window.$docsify = {
        // 回到顶部
        scrollToTop: {
            auto: true,
            text: '🔼',
            right: 12,
            bottom: 52,
            offset: 25
        },
    }
</script>

<!-- 回到顶部功能 -->
<script src="https://cdn.jsdelivr.net/npm/docsify-scroll-to-top@1.0.2/dist/docsify-scroll-to-top.min.js"></script>
```
