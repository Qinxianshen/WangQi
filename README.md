# WangQi


[android 商城](https://github.com/Qinxianshen/WangQi-android)


#### 核心框架 

1.example android 库

2. wangqi_annotations java 库

3. wangqi_compiler java库

4.wangqi_core android 库

5.wangqi_Ec android 库


依赖关系如下:

example 依赖 wangqi_Ec 与 wangqi_compiler

wangqi_Ec 依赖 wangqi_core

wangqi_core 依赖 wangqi_annotations


#### 配置类初始化

在Core库里添加配置类

1.枚举类ConfigType 保存需要的配置信息
2.Configurator 初始化要采用静态内部类单例模式的初始化 与下面的getInstance方法组成线程安全的单例懒汉模式
3.WangQi 配置类真正的对外开发工具类




#### Tips

(1) .gitignore file 用来标记不需要提交的类型文件  项目根目录有即可 分目录可以不需要

(2) 两个Android库 如果有依赖关系 一定不能包名相同

(3) File->Project Struct 里去添加modlue 间依赖关系

(4) [什么是annotationProcessor与apt](https://blog.csdn.net/xx326664162/article/details/68490059)

(5) EC依赖core core包含过的库EC都可以不用在包含了  这样重复  example同理

(6) VCS 里 允许用git托管 主要是在 .gitignore file 里添加bulid(编译时候的中间产物) .idea（AS自带的配置文件） 和 .gradle（太大不需要） local.properties即可

(7)[在AS里用Git管理 ](https://www.jianshu.com/p/b67ed0ec496f)

(8)WeakHashMap比HashMap的优点在于 可以更为及时的回收没有被使用的对象 避免内存溢出

(10) Static Final类请用全大写命名 这样符合规范

(11)添加iconify库 让App可以选择自己要用的字体样式 模仿它的代码FontAwesomeModule 与 FontAwesomeIcons类 我们可以自定义自己需要ttf字体图标类

(12)FrontAwesome网站和阿里图标库有大量实用的图标

 


 



