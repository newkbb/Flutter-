[TOC]
##### Table of Contents  
[Headers](#headers)  
[Emphasis](#emphasis)  
...snip...    
<a name="headers"/>
## Headers

## **1. Flutter是什么?**

### ​1.1 基本概念

​	由谷歌开发的开源移动SDK，用于为Android和iOS开发应用，也将是Google Fuchsia（Google开发的 操作系统）下开发应用的主要工具。

​	说白了，就是谷歌开发的能跨平台（安卓/iOS/Fuchsia……）的一款移动应用程序SDK，让一份代码同时适应两种平台，产出同样高性能、高保真的应用程序。

### 1.2 引擎、基础库和组件

​	`Flutter第一个版本支持Android系统，被称为“天空”。它于2015年的Flutter开发者会议上被公布，宣称其目标为实现120FPS的渲染性能。`

​	Flutter的引擎使用C++开发，通过谷歌Skia图形库提供底层渲染支持，也提供平台相关的SDK比如Android和iOS。

​	Flutter的基础库由Dart编写，提供了用Flutter构建应用所需的基本的类和函数，例如与引擎通讯的API。

​	Flutter中，一个组件代表用户界面中不可变的一部分；包括文本、多边形以及动画在内的所有图形都是用组件创建的。复杂的组件由简单的组件结合而成。

## **2. 为什么要用Flutter?**

前面说了，Flutter可以让一份代码做更多的事情，即：

### 2.1 提高开发效率

​首先是iOS和Android可以通用。

其次是​轻松迭代：

  a) 在应用程序运行时更改代码并重新加载（热重载）

  b) 修复崩溃并从停止处bug调试

### ​2.2 用户体验好，高度定制

​	因为使用Flutter框架有丰富的资源设计和iOS风格的小组件（widget），不受原生控件的限制。

## **3. 核心思想**

​	Flutter包括一个现代的响应式框架、一个2D渲染引擎、现成的widget和开发工具。这些组件可以帮助您快速地设计、构建、测试和调试应用程序。

### 3.1 Widget又是什么？

Widget是Flutter应用程序用户界面的基本构建块。每个Widget都是用户界面一部分的不可变声明。 与其他将视图、控制器、布局和其他属性分离的框架不同，Flutter具有一致的统一对象模型：widget。

Widget可以被定义为:

- 一个结构元素（如按钮或菜单）

- 一个文本样式元素（如字体或颜色方案）

- 布局的一个方面（如填充）

- 等等…

  Widget根据布局形成一个层次结构。每个widget嵌入其中，并继承其父项的属性。没有单独的“应用程序”对象，相反，根widget扮演着这个角色。

  您可以通过告诉框架使用另一个widget替换层次结构中的widget来响应事件，例如用户交互，替换后框架会比较新的和旧的widget，并高效地更新用户界面。

### 3.2 构建Widget

详见Flutter中文网。

https://flutterchina.club/technical-overview/


