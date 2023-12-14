# 1、代码高亮
docsify内置的代码高亮工具是[Prism](https://github.com/PrismJS/prism)，Prism默认支持的语言如下:
- html、xml、svg、
- css
- javascript

若需要其他语言的代码高亮,需要通过CDN添加相应的语法文件,步骤如下：
## 1.1、配置 

- 在`index.html`中进行配置


```html
<!-- Java代码高亮 -->
<script src="//cdn.jsdelivr.net/npm/prismjs@1/components/prism-java.min.js"></script>
<!-- bash代码高亮 -->
<script src="//cdn.jsdelivr.net/npm/prismjs/components/prism-bash.min.js"></script>
<!-- python代码高亮 -->
<script src="//cdn.jsdelivr.net/npm/prismjs/components/prism-python.min.js"></script>
<!-- C++代码高亮 -->
<script src="//cdn.jsdelivr.net/npm/prismjs/components/prism-cpp.min.js"></script>
<!-- C代码高亮 -->
<script src="//cdn.jsdelivr.net/npm/prismjs/components/prism-c.min.js"></script>
<!-- javascript代码高亮 -->
<script src="//cdn.jsdelivr.net/npm/prismjs/components/prism-javascript.min.js"></script>
<!--css代码高亮 -->
<script src="//cdn.jsdelivr.net/npm/prismjs/components/prism-css.min.js"></script>
<!--powershell代码高亮 -->
<script src="//cdn.jsdelivr.net/npm/prismjs/components/prism-powershell.min.js"></script>
<!--sql代码高亮 -->
<script src="//cdn.jsdelivr.net/npm/prismjs/components/prism-sql.min.js"></script>
<!--yaml代码高亮 -->
<script src="//cdn.jsdelivr.net/npm/prismjs/components/prism-yaml.min.js"></script>
<!--properties代码高亮 -->
<script src="//cdn.jsdelivr.net/npm/prismjs/components/prism-properties.min.js"></script>
<!--matlab代码高亮 -->
<script src="//cdn.jsdelivr.net/npm/prismjs/components/matlab.min.js"></script>
```


> [!WARNING]
> 按需添加CDN即可,添加过多可能会使渲染速度变慢！

