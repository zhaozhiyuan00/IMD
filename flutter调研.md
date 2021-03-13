# flutter调研
## 1. flutter简介
### 1.1 flutter是什么？
Flutter是谷歌的移动UI框架，可以快速在iOS和Android上构建高质量的原生用户界面。 Flutter可以与现有的代码一起工作。在全世界，Flutter正在被越来越多的开发者和组织使用，并且Flutter是完全免费、开源的。

### 1.2 flutter能做什么？
+ 对于用户来说，Flutter可以使应用界面变得美丽生动。
+ 对于开发者来说，Flutter降低了开发移动应用程序的门槛。它加速了移动应用程序的开发过程，并降低了同时开发iOS和Android两套应用程序的成本和复杂性。
+ 对于设计师来说，Flutter有助于实现原始设计愿景，高保真度、不妥协。它也是一种高效的原型工具。

### 1.3 Flutter用什么语言开发？
flutter采用了Dart作为开发框架和widget的语言。

### 1.4 目前已使用Flutter的团队有哪些？
+ 美团
+ 闲鱼
+ 京东金融
+ 腾讯NOW直播

****

## 2. 选择flutter的原因
###  2.1 flutter的sdk内容丰富
flutter的sdk中有这些：
+ 深度优化了的、移动优先的2D渲染引擎
+ 现代、响应式框架
+ 丰富的Android和iOS套件
+ 单元和集成测试的API
+ 连接到系统和第三方SDK的Interop和插件API
+ 无头的测试运行器，用于在Windows、Linux和Mac上运行测试
+ 用于创建、构建、测试和编译应用程序的命令行工具

### 2.2 flutter开发优势众多
+ flutter跨平台，同一套代码适用于Android和ios两个平台，可以节省开发资源、测试资源
+ 原生性能，使用Skia作为其2D渲染引擎，既不使用WebView，也不使用操作系统的原生控件，这样不仅可以保证在Android和iOS上UI的一致性，而且也可以避免对原生控件依赖而带来的限制及高昂的维护成本
+ 开发效率高，Flutter的热重载可以快速地进行测试、构建UI、添加功能并更快地修复错误
+ 从底层C++到高层Dart，可扩展性高
+ 整体开发环境要求不高，轻量编辑器+模拟器即可完成开发，已支持IDE:Android Studio和VSCode
