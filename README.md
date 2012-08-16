Finger Chart 
================================================

简介
-----------------

Finger Chart（以下简称Finger）是一个轻量级的基于Flash技术开发的图表解决方案(未来考虑扩展到HTML5平台)，由RIAMeeting社区推出，并基于LGPL协议开源。图表包括常见图表类型，包含线图，柱图，条图，饼图，区域图，散点图，气泡图等； Finger的应用目标是：Web应用和移动应用，因此也可以看出图表命名的初衷，即保持轻量级和较小的资源占用，以在有限的硬件资源下获得平稳流畅的运行。

Finger包含3个开发主体：
-----------------

*基于AS3开发的图表展现
*基于JavaScript实现的图表HTML嵌入
*针对服务器端代码开发的类库(基于使用者的贡献)

Finger具备如下的主要特点和设计初衷：
-----------------

*轻量级：图表基于纯ActionScript开发，并不断得到优化，使得图表可以保持较小的体积和较小的资源占用率。
*易用：对前端工程师而言，使用封装的JavaScript类库让您可以很方便的将图表嵌入HTML。而对于后端程序员，使用针对服务器端代码开发的类库让您可以更方便的与项目代码集成。
*灵活的外观定义方式：如果您对Finger默认的外观不满意，大可以进行自我定制。Finger的外观使用了两套彼此协作的机制：CSS和Skin，其中CSS使用网页通用的样式表属性进行描述，而Skin部分则允许您通过Flash Pro进行创建和修改。结合这两种方式，将给您的外观创建带来极大的灵活性。
*允许载入外部插件：您可以基于约定的接口创建一个插件，编译为单独的SWF文件，并在图表中载入，与图表协同工作。这种方式将让您在不需修改基本功能的条件下，完成一些额外的功能。
*可扩展的架构设计：Finger基于一个可扩展的架构来实现，各个图表组成部分都得到抽象并与具体实现相分离，图表则基于工厂模式来进行组装，在此基础上扩展其它类型的图表将会更加方便。
*可视化组件支持：未来版本将针对Flash Pro创建一个组件库，允许通过Flash Pro轻松应用图表组件并绑定数据源。

