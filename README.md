# vue-router-sourcecode-analysis
阅读完vue-router源码后对vue-router源码的详细解读

vue-router是vue的一个插件，可以非常方便的实现前端路由，使用vue-router是非常简单的，我们需要做的是，将组件(components)映射到路由(routes)，然后告诉 vue-router 在哪里渲染它们。

本书将尝试从源码角度来看一看vue-router的实现，基于的是3.0.1版本。全书将从11个章节进行讲述，分别如下：

1. 概述。 本章将从整体上讲解vue-router源码的构成，形成一个初步的认识。
2. router-view组件。本章将介绍router-view组件的实现。
3. router-link组件。本章将介绍router-link组件的实现。
4. History类。本章将介绍History类的实现，History类是vue-router三种路由模式的基础。
5. HTML5History类。本章将介绍HTML5History类的实现，HTML5History类继承自History类。
6. HashHistory类。本章将介绍HashHistory类的实现，HashHistory类继承自History类。
7. AbstractHsitory类。本章将介绍AbstractHsitory类的实现，AbstractHsitory类继承自History类。
8. VueRouter类。本章将介绍VueRouter类，该类是最终导出的类。
9. install方法。本章将介绍vue-router插件的install方法。
10. 辅助函数。本章将介绍vue-router中定义的辅助函数，主要有断言、警告、错误。
11. 总结。本章将对全文进行总结。



###### 整理人： 林雨

###### 首次整理时间： 2017-11-06

###### 最后整理时间： 2017-11-08
