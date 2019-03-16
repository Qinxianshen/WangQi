# WangQi

android 商城

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





#### Tips

(1) .gitignore file 用来标记不需要提交的类型文件  项目根目录有即可 分目录可以不需要

(2) 两个Android库 如果有依赖关系 一定不能包名相同

(3) File->Project Struct 里去添加modlue 间依赖关系

(4) [什么是annotationProcessor与apt](https://blog.csdn.net/xx326664162/article/details/68490059)

(5) EC依赖core core包含过的库EC都可以不用在包含了  这样重复  example同理
 



