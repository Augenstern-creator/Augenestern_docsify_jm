# 1、添加页脚
给网页添加页脚.

## 1.1、配置

```html
<script>
    window.$docsify = {
        // 页脚
        footer: {
            copy: '<span>Copyright &copy; 2025 &nbsp 💖 &nbsp</span>',
            auth: ' <strong><a href="https://blog.csdn.net/Augenstern_QXL" target="_blank">Mr.Augenestern</a></strong>',
            pre: '<hr/>',
            style: 'font-size: 18px; text-align: center;',
        },
    }
</script>

<!-- 页脚 -->
<script src="https://cdn.jsdelivr.net/npm/docsify-footer-enh@0.0.9/dist/docsify-footer-enh.min.js"></script>
```