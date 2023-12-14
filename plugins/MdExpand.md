# 1、MD语法`====`扩展
使得文章内支持MarkDown语法的 `====` 符号高亮.

## 1.1、配置

```html
<script>
    window.$docsify = {
      // markdown 语法高亮
      plugins: [
        function(hook, vm) {
          hook.init(function() {
            // 初始化完成后调用，只调用一次，没有参数。
          });

          hook.beforeEach(function(html) {
            // 每次开始解析 Markdown 内容时调用
            //适配Markdown的====高亮语法
            let res = html.match(/==(.+?)==/g);
            if(res) {
              for (var i = 0; i < res.length; i++) {
                html = html.replace(res[i], `<mark>` + res[i].replace(/==/g, "") + `</mark>`);
              }
            }
            return html;

          });

          hook.afterEach(function(html, next) {
            // 解析成 html 后调用。
            // beforeEach 和 afterEach 支持处理异步逻辑
            // ...
            // 异步处理完成后调用 next(html) 返回结果
            next(html);
          });

          hook.doneEach(function() {
            // 每次路由切换时数据全部加载完成后调用，没有参数。
            // ...
          });

          hook.mounted(function() {
            // 初始化并第一次加载完成数据后调用，只触发一次，没有参数。
          });

          hook.ready(function() {
            // 初始化并第一次加载完成数据后调用，没有参数。
          });
        }
      ]
    };
</script>
```
