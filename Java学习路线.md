## Java学习路线

### 介绍

个人背景：双非本末九硕，秋招面了5家拿了 **腾讯**ssp、**拼多多**sp、**快手**sp、**阿里**sp和**美团**的offer，实习拿了  **阿里**、**拼多多**、**快手**、**美团**、**华为**和**携程**的offer，暑期选择去拼多多实习了两个半月左右，秋招最终选择签约腾讯了。

ps：美团感觉最少应该开个sp的，所有面试中表现最好的就是美团，结果给我开个大白菜，有可能是觉得我不会去？？？

个人GitHub：https://github.com/Wuxinyue1999 （没啥东西，平时间不怎么用，把项目和一些资料上传到这了，hhh）

![image-20231106130909903](asset\邮件.png)

对应我项目的面经基本上都发在了牛客上：https://www.nowcoder.com/users/715322843

### 学习内容

学习内容主要有：**Java基础**、**MySQL**、**Spring**、Mybatis、**SpringBoot**、SpringCloud、**Redis**、**RabbitMQ**、**JUC**、**JVM**、Netty、Zookeeper、Dubbo、GIt、Maven、计算机网络、操作系统、设计模式、Elasticsearch、Docker、MongoDB；

----

最好要养成边看视频边做笔记的习惯，我个人不太喜欢做笔记，所以一般都找的有配套资料的视频来看，然后稍微加点自己认为重要的内容。

#### Java基础

Java基础我个人是没看过啥教学视频，本科的时候都学过，科班的估计大部分人也都会，如果说要看的话，可以推荐看黑马或者尚硅谷的视频：

1、[黑马Java入门基础视频教程](https://www.bilibili.com/video/BV1Cv411372m/?vd_source=8f6745987f6d9c4a333570852e433d6c)

个人感觉稍微看看就行了，因为后面做项目和学其他东西会大量涉及编码，这里记这么深用处不大，后期开始背八股的时候才是重基础的环节。

#### MySQL

MySQL是面试中最重要的一个知识点，面什么厂都必会问，教学视频可以看黑马的：

1、[MySQL数据库入门到精通](https://www.bilibili.com/video/BV1Kr4y1i7ru/?vd_source=8f6745987f6d9c4a333570852e433d6c)

看完之后，大部分面试基本上都没啥大问题，特别是学完之后后期要多看多复习他的pdf文档，总共有三个

- MySQL-基础篇.pdf
- MySQL-进阶篇.pdf
- MySQL-运维篇.pdf

#### Spring

Spring这一块需要认真学，不要跳过Spring直接去学SpringBoot，而是先学Spring再学Boot，循序渐进，从而对Java生态中的王者框架有一个深入的认识，这一块不仅是面试的重点，更是平时工作的重点，所以建议这一块内容可以多花些时间学学，IOC、AOP、DI这些，推荐的教学视频有：

1、[SSM框架教程+SpringBoot](https://www.bilibili.com/video/BV1Fi4y1S7ix/?vd_source=8f6745987f6d9c4a333570852e433d6c)

2、[Spring高级教程](https://www.bilibili.com/video/BV1P44y1N7QG/?vd_source=8f6745987f6d9c4a333570852e433d6c) （学有余力可以看）

#### Redis

基本上看完 Java基础+MySQL+Spring+SpringBoot 就可以开始看一些中间件的教学视频同时结合着一些小demo项目去学习，Redis是最重要的中间件之一，这个时候推荐看黑马的黑马点评，这个项目是专门针对Redis的教学视频，同时以一个技术点比较多的项目来进行讲解的，学完这个项目对Redis的原理和应用都有非常深的了解，也可以完整的做出一个项目，这里的秒杀抢购可以自己去进行优化，在后续项目章节中会有说明：

1、[Redis入门到实战教程](https://www.bilibili.com/video/BV1cr4y1671t/?vd_source=8f6745987f6d9c4a333570852e433d6c)

这里的入门篇、实战篇、高级篇、原理篇都建议看一看，非常有帮助，特别是**实战篇**和**原理篇**，并且都有配套的教学资料，学完之后可以方便复习。

#### RabbitMQ

消息中间件目前也是比较主流的和重要的，RabbitMQ和Kafka用的最多，这里推荐去学习RabbitMQ，简单易上手，教学视频：

1、[RabbitMQ入门到实战教程](https://www.bilibili.com/video/BV1mN4y1Z7t9/?vd_source=8f6745987f6d9c4a333570852e433d6c)

同样也有配套资料，方便学完后后续进行复习。

#### JUC

juc在面试中也是高频和重点，同时实际开发中也经常需要用到，所以，这一步可以开始学习JUC，教学视频推荐黑马的并发编程，内容多并且质量比较高，既有原理又有应用篇，课讲得也很好，也有配套资料：

1、[Java并发编程](https://www.bilibili.com/video/BV16J411h7Rd/?spm_id_from=333.337.search-card.all.click)

#### Netty

netty不是必须学的，如果想做rpc项目的，就需要学习高性能网络开发框架Netty，这个一般简历上有相关内容一般都会问，所以如果有想写rpc的需要认真学，视频推荐看：

1、[Netty全套教程](https://www.bilibili.com/video/BV1py4y1E7oA/?spm_id_from=333.337.search-card.all.click)

主要内容就是：Netty线程模型，零拷贝等；

#### Zookeeper

同样，zk也不是必须学的，如果说要做rpc项目或者是简历上有相关内容，就需要学一下zk的使用，这里推荐：

1、[zookeeper教学视频](https://www.bilibili.com/video/BV1M741137qY/?spm_id_from=333.337.search-card.all.click&vd_source=8f6745987f6d9c4a333570852e433d6c)

其实主要是学习zk的使用，然后重点背zk相关的八股，zab协议，选主、脑裂，应用等。

#### SpringCloud

SpringCloud面试过程中其实问的比较少，但是如果说自己想做一个微服务的项目的话，就需要先有SpringCloud的学习，这里推荐黑马的SpringCloud教程：

1、[SpringCloud微服务技术栈实战教程](https://www.bilibili.com/video/BV1kH4y1S7wz/?vd_source=8f6745987f6d9c4a333570852e433d6c)

#### Dubbo

dubbo其实也非必须学的，如果做rpc，可以先学习一下dubbo的应用和原理，然后对自己写rpc项目还是很有帮助的，推荐视频：

1、[Dubbo快速入门](https://www.bilibili.com/video/BV1VE411q7dX/?vd_source=8f6745987f6d9c4a333570852e433d6c)

#### Elasticsearch

Es一般也少问，简历上有可能会被问到，重点其实也就是倒排索引，教学视频推荐：

1、[Elasticsearch教程入门到精通](https://www.bilibili.com/video/BV1Gh411j7d6/?spm_id_from=333.337.search-card.all.click&vd_source=8f6745987f6d9c4a333570852e433d6c)

其实上面的SpringCloud教学视频里面包括了es的学习，所以学了cloud之后可以不用额外花时间学了。

#### JVM

jvm面试也是高频内容，看的顺序可以偏后一点，这里推荐的是尚硅谷的视频：

1、[JVM全套教程](https://www.bilibili.com/video/BV1PJ411n7xZ/?spm_id_from=333.337.search-card.all.click&vd_source=8f6745987f6d9c4a333570852e433d6c)

#### Git

Git&Maven&Docker&MongoDB 这些中间件大致了解一下如何使用就差不多了，教学视频推荐如下，基本都有配套资料：

[Git全套教程](https://www.bilibili.com/video/BV1MU4y1Y7h5/?vd_source=8f6745987f6d9c4a333570852e433d6c)

#### Maven

[Maven全套教程](https://www.bilibili.com/video/BV1Ah411S7ZE/?vd_source=8f6745987f6d9c4a333570852e433d6c)

#### Docker

[Docker快速入门](https://www.bilibili.com/video/BV1HP4118797/?vd_source=8f6745987f6d9c4a333570852e433d6c)

#### MongoDB

[MongoDB基础入门到高级进阶](https://www.bilibili.com/video/BV1bJ411x7mq/?vd_source=8f6745987f6d9c4a333570852e433d6c)

#### 其他

操作系统、计算机网络可以在b站找课看，也可以直接看小林coding，我是直接看的小林coding，一般字节和腾讯比较喜欢问计网和操作系统。

### 项目

项目这里推荐一个轮子项目+一个业务项目，这样的话找工作的时候匹配的业务方向面更广；

1、手写RPC项目，可以参考：https://github.com/Wuxinyue1999/wxy-rpc；

2、在线教育平台项目，可以参考：https://github.com/Wuxinyue1999/xuecheng-plus-project，教学视频[学成在线](https://www.bilibili.com/video/BV1j8411N7Bm/?spm_id_from=333.337.search-card.all.click&vd_source=8f6745987f6d9c4a333570852e433d6c)；

3、黑马点评，可以参考：https://github.com/Wuxinyue1999/xy-dianping；

实际上可以把黑马点评中的技术要求高的模块结合到学成在线里面，我是把 秒杀业务 放到了学成在线中，学成在线还有很多配套资料很全面；

简历可以参考如下写法：

![image-20231106155341175](asset\简历1.png)

![image-20231106155353828](asset\简历2.png)

### 八股文

八股文推荐如下网站：

1、自己学习的笔记以及所有视频的配套资料；

2、[JavaGuide](https://javaguide.cn/)：这个适合突击背诵，内容涉及面广但是都不深入，都停留在表面，可以用来和自己的笔记、配套资料结合背诵；

3、[小林coding](https://xiaolincoding.com/)：主要是和用来看 **计算机网络** 和 **操作系统**，同时也可以看看里面的 **Redis** 和 **MySQL**，个人感觉这个网站质量非常高；

4、[拓跋阿秀](https://interviewguide.cn/)：这里主要看的是 **智力题** 和 **场景题** 以及 **海量数据处理**；

5、一些额外的八股文pdf, md文档等，可以访问：https://github.com/Wuxinyue1999/JavaWxy，这里是对上述内容的一些补充，记录了一些比较重要和比较偏的面试题，*markdown文件下载下来可以访问图片*；

八股文背熟之后，还是靠自己理解，把这些知识都能串联起来，形成自己的一套知识体系，达到问一个点就能把这个点相关的内容全部都说出来，基本上面试这一块就没什么问题了。

### 面试

面试的话，首先就是不要紧张，把每一次面试都当作一次对话，结果不就是两种：过 和 不过，面试过程中面对面试官问的一个问题，不要就简单的把这个问题的答案机械式的将八股重复一遍就行了，你可以把这个点相关的所有知识点都从头到尾讲一遍，这个时候一般情况下面试官是不会打断你的，而且也可以让他看到你的广度和深度，一个面试下来都按这样回答，基本上十个问题之内就能结束这场面试，而且面试通过率会非常大，当然前提是你自己真的有东西。

### 算法

算法主要还是得多刷，特别是力扣上的 **剑指offer** 和 **hot100** 题，大部分面试的算法都可能是上面的原题，所以，这两个背都得背下来，其他的就靠自己多刷题多积累了，一些常见的：dp、滑动窗口、双指针、前缀和、回溯等等。

----

暂时先写这么多了，后续有想到要补充的再继续完善了~~~



