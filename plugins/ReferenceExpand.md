# 1、MarkDown引用扩展
MarkDown引用美化样式,按需配置.


## 1.1、美化前样式

> An alert of type 'note' using global style 'callout'.

> An alert of type 'tip' using global style 'callout'.

> An alert of type 'warning' using global style 'callout'.

> An alert of type 'attention' using global style 'callout'.

## 1.2、美化后样式

> [!NOTE]
> An alert of type 'note' using global style 'callout'.

> [!TIP]
> An alert of type 'tip' using global style 'callout'.

> [!WARNING]
> An alert of type 'warning' using global style 'callout'.

> [!ATTENTION]
> An alert of type 'attention' using global style 'callout'.

# 2、配置

```html
<script>
  window.$docsify = {
    'flexible-alerts': {
      style: 'flat'
    }
  };
</script>


<!-- MD引用样式美化 -->
<script src="https://unpkg.com/docsify-plugin-flexible-alerts"></script>
```

# 3、使用方式

```markdown
> [!NOTE]
> An alert of type 'note' using global style 'callout'.

> [!TIP]
> An alert of type 'tip' using global style 'callout'.

> [!WARNING]
> An alert of type 'warning' using global style 'callout'.

> [!ATTENTION]
> An alert of type 'attention' using global style 'callout'.
```

# 4、官方CDN
> [!NOTE]
> [官方CDN]:
> [docsify-plugin-flexible-alerts](https://www.jsdelivr.com/package/npm/docsify-plugin-flexible-alerts).