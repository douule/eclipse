# eclipse
it just discribe how to use it.......

eclipse入门
-

给我自己看的，若哪个大哥碰巧看到了，有什么不懂的地方留个言，我只是保证自己能看懂。
首先用这个要准备两个东西一个eclipse，还有就是要配置jdk，这个自行处理。网上教程很多很简单。后期如果我不用windows的用linux的版本的话我会往这里面加。
eclipse是用来干嘛的？
-

Eclipse 是一个开放源代码的、基于 Java 的可扩展开发平台。

Eclipse 是 Java 的集成开发环境（IDE），当然 Eclipse 也可以作为其他开发语言的集成开发环境，如C，C++，PHP，和 Ruby 等。

Eclipse 附带了一个标准的插件集，包括Java开发工具（Java Development Kit，JDK）。

他和idea其实一个用处，但我暂时更偏向idea一点，因为简单方便。

eclipse基本概述：
-

工作区（workspace）

工作区是一个目录，程序和程序所需要用到的资源都在workspace里，中间缓存文件也存在工作区中。安装的时候选择好工作区
项目（Project）
为一个需求所服务的代码文件，一个workspace 可以拥有个项目，而你的代码必须有归属于某个项目的，不能单独存在。

三、Eclipse创建Java文件

●创建项目

1、File-New-Project

![](https://pic1.zhimg.com/80/v2-5f7542885bf672306513f76b36babbac_1440w.jpg)

2、点击Java Project，然后Next

![](https://pic4.zhimg.com/80/v2-8a456e40f9fd2fbc81dd444124a94063_1440w.jpg)

3、编辑项目名称点击Finish

![](https://pic1.zhimg.com/80/v2-742172fd0c95bc83a92596c6d2752850_1440w.jpg)

![](https://pic4.zhimg.com/80/v2-9b2d8835eb993f16b8d2d4c9914fcd67_1440w.jpg)

●在项目下创建包和类
>>>>分步创建包和类

![](https://pic2.zhimg.com/80/v2-963c44c01102427de421f8338e352bc1_1440w.jpg)

![](https://pic3.zhimg.com/80/v2-03f1d047b216531a122aeeb83384eb56_1440w.jpg)

包创建成功

![](https://pic2.zhimg.com/80/v2-b645d4d0c67093b31da95c6c95ee2cc1_1440w.jpg)

在包那里单击右键New-Class创建类

![](https://pic4.zhimg.com/80/v2-d440e511d8c8a559298dc0ad39aae053_1440w.jpg)

编辑类名-Finish

![](https://pic3.zhimg.com/80/v2-3ecbcec750a73f9f8507448051241fca_1440w.jpg)

创建成功，源程序文件名与创建的类名相同Test.java，编译器会给出类的主体部分

![](https://pic4.zhimg.com/80/v2-75c1aeb43cab77cce1115784c85b92ef_1440w.jpg)

>>>>直接一步创建类和包

![](https://pic2.zhimg.com/80/v2-127f196cd27f1070581b2a1690d0dee5_1440w.jpg)

![](https://pic4.zhimg.com/80/v2-10d4e44efdcfa87f695c99dd026b34ef_1440w.jpg)

●编译

![](https://pic2.zhimg.com/80/v2-5322c905363234a4ad423851ea09cd49_1440w.jpg)

![](https://pic3.zhimg.com/80/v2-3543b0b47307f840cb1c35a7f741ffba_1440w.jpg)

![](https://pic3.zhimg.com/80/v2-87cc4b232cf8c27cd00d4e0791ddb76a_1440w.jpg)

![](https://pic3.zhimg.com/v2-0288a4f2de57e2901cc3573f4230ba4a_r.jpg)

![](https://pic4.zhimg.com/v2-4215994e3d134ab0f40f1d1cdfe3159b_r.jpg)

![](https://pic4.zhimg.com/80/v2-0464915634abb36466ab97d1560c8387_1440w.jpg)

![](https://pic1.zhimg.com/80/v2-288e6bed59c263100e50ced4d8d3a8a0_1440w.jpg)

字节码文件和源程序文件存储
![](https://pic2.zhimg.com/80/v2-014e753edd47193c32b08d8119d54e1d_1440w.jpg)

![](https://pic4.zhimg.com/80/v2-ea70bd12c7a4dbe4446eccebf03bbbf7_1440w.jpg)

●常用操作（删除更名），在对应包、类、文件等鼠标右击

![](https://pic3.zhimg.com/v2-607c456ccabb4a0be557af00246e8eae_r.jpg)

四、查看源码

准备工作
步骤一

![](https://pic1.zhimg.com/80/v2-29158bb7bc736458318dfa2af05842b0_1440w.jpg)

步骤二

![](https://pic1.zhimg.com/80/v2-4037eaa05f7152e5b625044c590dab7c_1440w.jpg)

步骤三

![](https://pic1.zhimg.com/80/v2-a254d21bbd96f5d6679c8768ca804ae0_1440w.jpg)

步骤四

![](https://pic2.zhimg.com/80/v2-ad070ab2f8c3a2dc07c1cf5dcc5a6da5_1440w.jpg)

![](https://pic2.zhimg.com/80/v2-ad070ab2f8c3a2dc07c1cf5dcc5a6da5_1440w.jpg)

完成上述准备工作后，查看源码最快捷方式，按住键盘ctrl键鼠标选择你想要查看源码的类或者方法名即可。或者选中对应方法或类，鼠标置于其上点击查看

若要查看API，首先准备好网页版的API，然后按照上面的步骤三开始导入。感觉感慨是这个一般不太用。
【上面这些介绍是一些基本的操作，Eclipes的功能其实很强大，自己可以平时去大胆尝试，有问题了随时网上咨询，将编译器的最大化的利用】

![](https://pic3.zhimg.com/80/v2-611dd8c99749cabb134387a2c7cef602_1440w.jpg)

![](https://pic2.zhimg.com/80/v2-db1cf59af1ad1ac6948ad656bbb1262d_1440w.jpg)

原文：https://zhuanlan.zhihu.com/p/146333721


