# 1、代码复制
代码右上角设置一键复制按钮,并且可设置复制成功提示.

## 1.1、配置 

```html
<script>
    window.$docsify = {
      ...
      copyCode: {
        buttonText: 'Copy to clipboard',
        errorText: 'Error',
        successText: 'Copied',
      },
    };
</script>

<!-- 代码右上角复制 -->
<script src="//cdn.jsdelivr.net/npm/docsify-copy-code/dist/docsify-copy-code.min.js"></script>
```

> [!TIP]
> [官方CDN](https://www.jsdelivr.com/package/npm/docsify-copy-code)