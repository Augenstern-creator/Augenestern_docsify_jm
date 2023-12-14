# 1、复制提醒
复制成功提示弹框，按需配置即可。

## 1.1、配置
1. 修改`index.html` 文件，先在 `<head></head>` 加上 :

```html
<head>
  <link rel="stylesheet" href="https://cdn.bootcss.com/sweetalert/1.1.3/sweetalert.min.css" type='text/css' media='all' />
</head>
```

2. 再在`<body></body>` 中加上

```html
<body>
    ...

    <script>
        window.$docsify = {
            ...
        }
    </script>

    <!-- 复制提醒 -->
    <script src="https://cdn.bootcss.com/sweetalert/1.1.3/sweetalert.min.js"></script>
    <script>
        document.body.oncopy = function () {
            swal("复制成功 ",
                 "若要转载或引用请务必保留原文链接，并申明来源。",
                 "success"); };
    </script>
</body>
```
> [!INFO]
> 官方CDN:
>   [sweetalert](https://www.jsdelivr.com/package/npm/sweetalert)
