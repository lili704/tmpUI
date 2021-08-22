# 概览

tmpUI 帮助你快速把一些基于后端模板体系（比如 PHP），以 MVC 模式构建的网站，转换成前后端完全分离的现代化架构。   
你不需要学习诸如 “组件状态”，“JSX” 之类的新概念和技术。你只需要学习如何编写基于 tmpUI 的应用程序配置，以帮助你实现最有用的 include，模板标签等你之前用到的技术，在 tmpUI 中，它有另外一种表现形式，但是基本一致。   
至于此前用到的其它技术和插件，一切照旧，无需作出任何改变。

## tmpUI 的一些特性

### 1，不需要安装任何附加的组件，爽
tmpUI 基于 ES6 编写，因此它可以直接运行在浏览器中。你不需要安装任何命令行工具，基于 tmpUI 编写的程序也无需编译，可以直接在浏览器中运行。

### 2，以 `?` 作为路由符号，而不是 `#`
本质上来说，用户丝毫不关心你的网页是如何运行的。   
使用 # 符号进行路由处理，会遇到一些问题：
* 在服务端日志没有记录。
* 在某些客户端复制链接时，无法正确地处理网址。
* 查询参数与路由参数混乱。

### 3，实时的加载进度和先进的缓冲机制
由于你已将应用进行了完全的前后端分离和模块化，因此 tmpUI 在加载网页时可以根据分离程度，来显示一个加载进度条，以优化用户体验。  
tmpUI 提供与 MVC 架构下一致的网页体验：只加载必须的部分，并且还会缓存它，下一次加载时无需再次加载。

### 4，内置的多语言支持
为你的国际化应用节约开发时间。

### 5，完整的文档
tmpUI 使用指南(中文) 现在已经发布了预览版本。  
https://raw.githubusercontent.com/tmplink/tmpUI/master/doc/tmpUI%20User's%20Guide.cn.preview.pdf


# 案例

目前已有这些网站是使用tmpUI进行构建的，如果你也使用了 tmpUI 构建了项目，欢迎提交 issue，我们会将它放在这里陈列。  
https://app.tmp.link 一个好用的网盘。  
http://bs4.vx.link Bootstrap 4 中文文档。  
https://www.vx.link 微林。  

# 版权

tmpUI 基于 GNU General Public License v3.0 发布  
