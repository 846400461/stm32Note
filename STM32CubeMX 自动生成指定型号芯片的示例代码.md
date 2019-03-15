接下来介绍的是stm32三个软件工具。

[TOC]

## STM32CubeMX 自动生成指定型号芯片的示例代码

*创建project*

在搜索栏内输入指定芯片型号

点击 Start Project按钮

![](<https://raw.githubusercontent.com/846400461/stm32Note/master/images/MXcreate.png>)



进去之后的界面

![](<https://raw.githubusercontent.com/846400461/stm32Note/master/images/config.png>)



直接点击图中芯片的管脚，就可以配置芯片的管脚功能

![](https://raw.githubusercontent.com/846400461/stm32Note/master/images/MXconfig2.png)

时钟配置也是类似。。。

接下来就是示例代码的配置

![](<https://raw.githubusercontent.com/846400461/stm32Note/master/images/MXconfig3.png>)

生成后会提示你打开工程

## truestudio软件（编辑代码和调试代码，也可以烧录程序）

![1552656314419](<https://raw.githubusercontent.com/846400461/stm32Note/master/images/openProject.png>)

调试配置

![](<https://raw.githubusercontent.com/846400461/stm32Note/master/images/openProject2.png>)



调试代码

![](<https://raw.githubusercontent.com/846400461/stm32Note/master/images/openProject3.png>)

## STM32CubeProgrammer（用于烧写程序，烧写方面比truestudio强，可用于批量烧写）

官方有中文文档，所以不作详细描述。。。