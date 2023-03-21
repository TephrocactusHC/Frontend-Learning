# HTML5
制定了Web应用开发的一系列标准，成为第一个将Web做为应用开发平台的HTML语言。
## 标签语义化
能够便于开发者阅读和写出更优雅的代码。

同时让浏览器或是网络爬虫可以很好地解析，从而更好分析其中的内容。

更好地搜索引擎优化。

总结：HTML的职责是描述一块内容是什么（或其意义），而不是它长什么样子；它的外观应该由CSS来决定。

# H5中新增的语义标签
- `<section>` 表示区块

- `<article>` 表示文章。如文章、评论、帖子、博客

- `<header>` 表示页眉

- `<footer>` 表示页脚

- `<nav>` 表示导航

- `<aside>` 表示侧边栏。如文章的侧栏

- `<figure>` 表示媒介内容分组。

- `<mark>` 表示标记 (用得少)

- `<progress>` 表示进度 (用得少)

- `<time>` 表示日期

# 多媒体
音频
HTML5通过<audio>标签来解决音频播放的问题。

使用举例：
```html
<audio src="music/yinyue.mp3" autoplay controls> </audio>
```
我们可以通过附加属性，来更友好地控制音频的播放，如：

- autoplay 自动播放。写成autoplay 或者 autoplay = ""，都可以。

- controls 控制条。（建议把这个选项写上，不然都看不到控件在哪里）

- loop 循环播放。

- preload 预加载 同时设置 autoplay 时，此属性将失效。

