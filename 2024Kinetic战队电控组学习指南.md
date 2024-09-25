# 2024Kinetic战队电控组学习指南

## 写在前面

- 嵌入式学习的正向反馈可能比较慢，尤其是前期学习阶段，导致没有什么成就感，也就坚持不下去了，所以往往就弃坑了，这里分享一下我曾经在CSDN上的看到一位嵌入式大佬的话：**以输出为目的的学习才是高效率的学习**

- 嵌入式的学习任重而道远，它涉及的知识面广，学习内容多且周期长，所以请在学习的过程中请**做好笔记**

- 如果你在学习及实验过程中遇到了困难, 并打算向我们寻求帮助, **请先阅读** [提问的智慧_Dev-Liangjian的博客-CSDN博客](https://blog.csdn.net/qq_34804120/article/details/89117072?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522169537214416800186565016%2522%252C%2522scm%2522%253A%252220140713.130102334..%2522%257D&request_id=169537214416800186565016&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~sobaiduend~default-1-89117072-null-null.142^v94^chatsearchT3_1&utm_term=%E6%8F%90%E9%97%AE%E7%9A%84%E6%99%BA%E6%85%A7&spm=1018.2226.3001.4187) 和 [别像〝弱智〞一样提问！-CSDN博客](https://blog.csdn.net/mingongge/article/details/107455088?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522169537222116800211587388%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=169537222116800211587388&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~rank_v31_ecpm-1-107455088-null-null.142^v94^chatsearchT3_1&utm_term=%E5%88%AB%E5%83%8F%E5%BC%B1%E6%99%BA%E2%BC%80%E6%A0%B7%E6%8F%90%E9%97%AE&spm=1018.2226.3001.4187) 这两篇⽂章（（无恶意

## 学习习惯 

-  学会科学上网

- 养成学习记录的习惯，自己可以在CSDN写博客，记录学习经历 ，没准自己以前所踩过的坑还会再次遇见，并且也能够帮助到其他人 //Shion


- 不想写博客也要自己对自己的学习经历有记录，不限内容和方法，你记录的学习经历或许会有一天在奇怪的地方派上用场   <span style="color:green">//tty

- **学会自己去解决问题**，遇到问题可以先自己去CSDN、github、Google、古月居、博客园、百度、知乎等搜索引擎查找，不要过于依赖同学或者学长，学会自己分析并解决问题

- Bilibili也是一个非常不错的选择，B站大学不是吹出来的 <span style="color:green">//tty
 
## C语言部分 
  
> 学习链接: B站 - 小甲鱼: [【C语言】《带你学C带你飞》](https://www.bilibili.com/video/BV17s411N78s)

> 学习链接: Mooc - 翁恺: [程序设计入门——C语言](https://www.icourse163.org/course/ZJU-199001?from=searchPage)

> 学习链接: Mooc - 翁恺(进阶): [C语言程序设计进阶](https://www.icourse163.org/learn/ZJU-200001?tid=1471612444#/learn/content)

> 学习链接: B站 - 宋红康: [尚硅谷C语言零基础入门教程](https://www.bilibili.com/video/BV1Bh4y1q7Nt/?spm_id_from=333.999.0.0&vd_source=f05f46375164cde4c681a9478bf5d9bd)

>学习链接: B站 - 千锋教育: [千锋教育新版C语言程序设计基础入门视频](https://www.bilibili.com/video/BV1n34y1k7Y8/?spm_id_from=333.999.0.0&vd_source=f05f46375164cde4c681a9478bf5d9bd)

>学习文档  菜鸟教程：
https://www.runoob.com/   

>相关书籍推荐 
 《C Primer Plus》
 《C和指针》 
 《C语言，从入门到精通》

## 笔记部分

推荐使用<span style="color:red">markdown</span>、onenote、LaTex等软件，如果自己喜欢，用word、txt文档都行，看你喜欢  

做笔记真的很重要，可能很多时候就会用上(特别是记不清楚的时候)((来自某学长的血泪教训))(((已老实)))

## 学习内容（基本）
 - 基础语法 
 - 数组 
 - 函数 
 - 指针  
 - 结构体 
 - 宏定义 
 - 动态内存分配 


## 单片机部分

 **首先再上手搞懂一些概念再上手**
 
 - 什么是单片机，这是用来干什么的
 
 - Hal库与标准库是什么？ 区别?
 
 - 单片机有什么种类
 
 - 如何运用stm32中文手册

### 硬件 

  - **STM32开发板**：STM32F103 、正点原子开发板、野火开发板反正什么都行（真炜是从51单片机开始学，然后再上手F1；我当时就买了一块野火的霸天虎F407<span style="color:red">(FZL)</span>）总之看自己经济实力购买 推荐购买STM32F103C8T6 经济实惠
 
  - 面包板 
  
  - 杜邦线若干(公对公10根左右，公对母20根左右，母对母10根左右)  
  
  - USB转TTL 
  
  - 舵机SG90  
  
  - ST-Link 

### 驱动

- ST-link的驱动的安装

- 串口ch340的驱动安装

### 软件（keil5）
前言：Hal库的环境搭建比较简单，建议大家可以优先学习Hal库
#### Hal库
[【STM32】教程01如何开始准备hal库的开发环境_stm32的hal库安装-CSDN博客](https://blog.csdn.net/windyhigh/article/details/131775345?ops_request_misc=%7B%22request_id%22%3A%22169537701516800184165104%22%2C%22scm%22%3A%2220140713.130102334..%22%7D&request_id=169537701516800184165104&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~sobaiduend~default-1-131775345-null-null.142%5Ev94%5EchatsearchT3_1&utm_term=hal%E5%BA%93%E5%AE%89%E8%A3%85&spm=1018.2226.3001.4187)

[【STM32】HAL库 STM32CubeMX系列学习教程_百度网盘stm32cubemx 学习教程-CSDN博客](https://blog.csdn.net/as480133937/article/details/99935090?ops_request_misc=%7B%22request_id%22%3A%22169726562016777224477333%22%2C%22scm%22%3A%2220140713.130102334..%22%7D&request_id=169726562016777224477333&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~top_positive~default-1-99935090-null-null.142%5Ev96%5Epc_search_result_base2&utm_term=hal%E5%BA%93&spm=1018.2226.3001.4187)
#### 标准库


##### 参考教程
[keil5软件安装&开发环境搭建教程（mdk,c51通用）_怎么在keil5中添加c51_东湖西泽的博客-CSDN博客](https://blog.csdn.net/m0_73994912/article/details/129734540?ops_request_misc=&request_id=&biz_id=102&utm_term=%E6%90%AD%E5%BB%BAkeil5%E7%8E%AF%E5%A2%83&utm_medium=distribute.pc_search_result.none-task-blog-2~all~sobaiduweb~default-1-129734540.142^v94^chatsearchT3_1&spm=1018.2226.3001.4187)
##### **学习视频** 
标准库 
https://www.bilibili.com/video/BV1th411z7sn?vd_source=c030bdc5c53c1790e638bec4426ead60 


#### 需要学习的外设（做好笔记）

- GPIO调用
 
- 串口收发、中断

- 定时器中断

- TIM定时器

- PWM控制舵机

- CAN通讯,SPI通讯，I2C通讯

- ADC电压采集（各种传感器的使用）

- 陀螺仪

#### 后期需要另外学习的技能 //嵌入式硬件部分
- 电子元件、电线的焊接（不短路，不虚焊）

- 电路的设计，布线    （不容易出故障，后期容易维护）

- 电路故障的排查和维修 （通过调试来确认故障部分）

- 原理图设计和PCB的Layout（不会画但是最起码能看得懂）

### 功在当代，利在千秋
- 本学习指南是真炜和我一拍即合，写下Kinetic战队电控组的第一份指南，我们尽力为小白提供有用的信息和建议，希望这个指南能够成为您学习旅程的一个有用的起点，我们想说的是这份指南还有很多需要改进的地方，学习是一个不断积累的过程，这份指南也需要不断的迭代，希望你们在借助这份指南学有所获时，可以回过头来继续完善这份指南，我们也会把它放在飞书上，时不时的进行更新，你们也可以把你们的想法写在上面，让我们的指南亿点亿点的不一样吧！！最后希望大家無限進步！！

【2024  2.0版本】
- 本学习指南加入了新东西，虽然改动不大，但还是希望对你们有帮助。我们想说的是这份指南还是有很多需要改进的地方，学习是一个不断积累的过程，这份指南也需要不断的迭代，接下来就交给你们了，希望你们可以继续完善，让它成为一份真正全面的指南，最后希望大家保持热爱，無限進步！！


## 贡献人员
### 2023.9.23
冯梓朗 陈真炜
### 2024.9.22
谭天越(tty) 阴宇阳(yyy) 徐文俊（Shion）
### 未完待续...

