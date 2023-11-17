一个 HTML 页面主要由以下几个基本部分组成：

1. **文档类型声明（Doctype）**：
   - 位于 HTML 文档的最顶部，用于告诉浏览器文档使用哪个 HTML 版本。例如，`<!DOCTYPE html>` 表示文档是 HTML5。

2. **HTML 元素（HTML Element）**：
   - 包裹整个文档的根元素，用 `<html>` 开始，`</html>` 结束。

3. **头部（Head）区域**：
   - 由 `<head>` 和 `</head>` 标签定义。包含文档的元数据（metadata），如文档的标题（`<title>`）、样式表的链接（`<link>`）、脚本（`<script>`）、字符集声明（`<meta charset="utf-8">`）等。
   - <font color = red><b>注意，Head区域不会在页面中显示，是用来保存元数据的</b></font>

4. **主体（Body）区域**：
   - 由 `<body>` 和 `</body>` 标签定义。这是所有可见内容的所在地，如文本、图片、链接、表格、列表等。

5. **注释（Comments）**：
   - 用 `<!-- 注释内容 -->` 形式添加，帮助开发者理解代码，但不会在浏览器中显示。

6. **元素（Elements）**：
   - 如段落（`<p>`）、标题（`<h1>` 至 `<h6>`）、链接（`<a>`）、列表（`<ul>`、`<ol>`）、表格（`<table>`）等。这些元素构成了网页的主要内容和结构。

7. **属性（Attributes）**：
   - 提供了关于 HTML 元素的额外信息，例如，`<a href="url">` 中的 `href` 属性定义了链接的目的地。

一个基本的 HTML 页面结构示例：

```html
<!DOCTYPE html> <!-- 标定文件类型是html -->
<html> <!-- 标定html页面代码 -->
<head>
    <title>页面标题</title>
    <meta charset="utf-8">
    <!-- 链接 CSS 文件和 JavaScript 文件等 -->
    <!-- head part不会被显示，所以是专门用来doing setting的 -->
</head>
<body>
    <!-- body part是真正显示的part -->
    <h1>这是一个标题</h1>
    <p>这是一个段落。</p>
    <!-- 更多内容 -->
</body>
</html
```

在这个结构中，`<head>` 部分包含了文档的头部信息，而 `<body>` 部分则包含了网页的主体内容，用户在浏览器中看到的大部分内容都来自这里。