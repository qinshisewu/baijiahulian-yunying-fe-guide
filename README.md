# 新人指南
    这是一个新的开始 :blush:

>## 运营系统前端开发框架<br>

使用`AngularJS`作为主体架构；<br>
页面设计原则是可以使用`Bootstrap`实现的效果尽量使用它实现，注意设计出的页面应该和整个系统中的风格保持一致；<br>
css样式编写使用`Less`语言，这样可以避免系统中出现css命名冲突；<br>
使用基于AMD规范的`RequireJS`来完成整体的模块化设计。

具体开发中，需要注意一下几点：<br>
* 这里推荐使用`Homebrew`作为包管理器，用于在Mac上安装一些OS X没有的UNIX工具，<br>例如`git`、`nodejs`、`grunt`等；
   * [HomeBrew中文网]
   * [HomeBrew教程]
* 推荐使用`WebStorm`或者`Sublime`作为开发工具
* 版本管理，统一使用`Git`
* 前端开发中使用`NodeJS`模拟服务器，用`mock`数据代替真实的后台数据，这样可以方便的进行功能性测试
* 使用`grunt`作为构建工具

>## 开发规范

* [目录规范]
* [JS规范]
* [AngularJS规范]
* [HTML、Less、CSS、JSON等其他规范]

>## 快速入门资料

* Git
   * [Git教程]
* AngularJS
    * [AngularJS官网]
    * [AngularJS的API文档]
    * [AngularJS的UI组件(很重要，项目中使用的组件基本来自这里)]
    * [终端调试AngularJS应用]
    * AngularJS技术难点
        * [自定义指令中如何使用ngModelController]
        * [深入理解AngularJS中的scope]
        * [深入理解AngularJS中的$scope、$rootScope和事件机制]
        * [jQuery的deferred对象详解]
        * [promise完全解读]
        * [AngularJS指令详解]
        * ui-router指南
            * [ui-router简介]
            * [ui-router系列指南]
        * controllerAs
            * [controller as是什么]
* Bootstrap
    * [视频教程]
    * [Bootstrap表单用法(非常推荐)]
    * [Bootstrap官网]
* Less
    * [Less快速使用指南]
    * [Less中文文档]
* AMD规范
    * [AMD规范是什么]
* RequireJS
    * [RequireJS是什么]
    * [RequireJS中文网]
* Grunt
    * [Grunt指南]



[HomeBrew中文网]: http://brew.sh/index_zh-cn.html
[HomeBrew教程]: http://blog.csdn.net/maojudong/article/details/7918291
[目录规范]: https://github.com/ecomfe/spec/blob/master/directory.md
[JS规范]: https://github.com/ecomfe/spec/blob/master/javascript-style-guide.md
[AngularJS规范]: http://git.baijiahulian.com/yanlingling/yunyingFrontendStandard/wikis/angular-usage
[HTML、Less、CSS、JSON等其他规范]: https://github.com/ecomfe/spec
[Git教程]: http://git-scm.com/book/zh/v1
[AngularJS官网]: https://angularjs.org/
[AngularJS的API文档]: http://docs.angularjs.cn/api
[AngularJS的UI组件(很重要，项目中使用的组件基本来自这里)]: http://angular-ui.github.io/
[终端调试AngularJS应用]: http://www.oschina.net/translate/angularjs-console?cmp
[自定义指令中如何使用ngModelController]: http://www.chroder.com/2014/02/01/using-ngmodelcontroller-with-custom-directives/
[深入理解AngularJS中的scope]: https://github.com/angular/angular.js/wiki/Understanding-Scopes#javascript-prototypal-inheritance
[深入理解AngularJS中的$scope、$rootScope和事件机制]: http://toddmotto.com/all-about-angulars-emit-broadcast-on-publish-subscribing/
[jQuery的deferred对象详解]: http://www.ruanyifeng.com/blog/2011/08/a_detailed_explanation_of_jquery_deferred_object.html
[promise完全解读]: http://www.dwmkerr.com/promises-in-angularjs-the-definitive-guide/
[AngularJS指令详解]: http://www.undefinednull.com/2014/07/07/practical-guide-to-prelink-postlink-and-controller-methods-of-angular-directives/
[ui-router简介]: http://www.codeproject.com/Articles/842880/AngularJS-ui-router-nested-routes
[ui-router系列指南]: https://github.com/angular-ui/ui-router/wiki
[controller as是什么]: http://www.cnblogs.com/whitewolf/p/3493362.html
[视频教程]: http://www.jikexueyuan.com/course/587.html
[Bootstrap表单用法(非常推荐)]: http://www.runoob.com/bootstrap/bootstrap-forms.html
[Bootstrap官网]: http://v3.bootcss.com/
[Less快速使用指南]: http://www.bootcss.com/p/lesscss/
[Less中文文档]: http://less.bootcss.com/
[AMD规范是什么]: http://www.ruanyifeng.com/blog/2012/10/asynchronous_module_definition.html
[RequireJS是什么]: http://www.ruanyifeng.com/blog/2012/11/require_js.html
[RequireJS中文网]: http://requirejs.cn/
[Grunt指南]: http://www.w3cplus.com/tools/grunt-tutorial-start-grunt.html


