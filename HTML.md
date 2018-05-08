# HTML
嵌套的节点应该缩进；</br>
在属性上，使用双引号，不要使用单引号；</br>
属性名全小写，用中划线做分隔符；</br>
不要在自动闭合标签结尾处使用斜线</br>
不要忽略可选的关闭标签

## HTML5 doctype
在页面开头使用这个简单地doctype来启用标准模式，使其在每个浏览器中尽可能一致的展现；</br>
虽然doctype不区分大小写，但是按照惯例，doctype大写

## lang属性
根据HTML5规范：
```应在html标签上加上lang属性。这会给语音工具和翻译工具帮助，告诉它们应当怎么去发音和翻译。```
常用 `lang` 属性语言 `zh` `en` `zh-cn` `zh-hk` `zh-tw`</br>
sitepoint[语言列表](http://reference.sitepoint.com/html/lang-codes)

## 字符编码
通过声明一个明确的字符编码，让浏览器轻松、快速的确定适合网页内容的渲染方式，通常指定为'UTF-8'。

## IE兼容模式
用 `<meta>` 标签可以指定页面应该用什么版本的IE来渲染；

## 引入CSS, JS
根据HTML5规范, 通常在引入CSS和JS时不需要指明 `type` ，因为 `text/css` 和 `text/javascript` 分别是他们的默认值。