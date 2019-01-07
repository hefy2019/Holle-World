# Holle-World
2019年，这个世界的成长之路。


ren sheng jiu xiang shi yi kuai qiao ke li.
yang guang sha jian tou ,fan fu zi you ren.

2019/01/02, ri zi dei xu yao yi ge ming que de fang xiang !

2019/1/3 （入职第四十五天）
hefy
初识
    前端主流框架webpack
    组件化（功能封装、跨项目复用）模块化
    UI界面生命周期（初始化、渲染、存活期、销毁）
    前端框架angular
    计算机领域最底层（算法、数据结构、设计模式）
    技术框架核心：概念模式（mental model）
   
切换ecms分支时，报错...
Error:Module 'std' production: java.lang.ClassCastException: org.jetbrains.jps.builders.java.dependencyView.TypeRepr$PrimitiveType cannot be cast to org.jetbrains.jps.builders.java.dependencyView.TypeRepr$ClassType
怎么解决？（15：05）
    
2019/1/7 
hefy
遇到一个难题: NoSuchMethodError  
错误可能的原因：
1.有这个类，该类真的没有这个方法
2.有这个类，而且有好几个，他们之间发生了冲突
接触的方法：（debug）
找到报错行的类全限定名称，删掉多余的jar包版本
