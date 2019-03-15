<title>OOAD_homework3</title>

### 1、简述瀑布模型、增量模型、螺旋模型（含原型方法）的优缺点

- 瀑布模型：
  - 项目特点：需求很明确，且不会发生变化的情况下时比较好的。它也定义了软件开发的基本流程与活动。
  - 风险特征：由于一般来说项目一开始，需求是不确定的，并且中途会有变化。如果后期需求发生变化，其工作量是无法接受的，容易导致项目延期，不可控。
  - 人力资源利用：在不同的阶段，需要的技术不同，人员数量不同，所以调配也比较困难。
- 增量模型：
  - 项目特点：可以很好的适应需求的变动，首先推出核心模块，给用户起到镇定作用，提高用户的信任度。
  - 风险特征：首先实现核心模块，验证技术的可行性，降低技术风险。如果增量包之间有相交的部分，而没有很好的处理，可能会导致项目失败。
  - 人力资源利用：一开始不需要投入太多的人力，开发出核心模块，验证技术可行性以后，投入大量人力资源，人员调配灵活。
- 螺旋模型：
  - 项目特点：需求功能复杂，在项目一开始无法得到明确的规格说明。开发周期长，用户需求经常在中途发生变化。
  - 风险特征：它强调风险分析，但是说服外部客户接受和相信分析结果并作出相应反应并不容易，因此它比较适合内部大规模软件系统的开发。但是失误的风险分析可能带来更大的风险。它结合了瀑布模型和快速原型方法，把瀑布模型的多个阶段转化到多个迭代中，以降低项目风险。
  - 人力资源利用：前期需要的人员比较少，后期需要投入大量人力资源。人员分配比较灵活。

### 2、简述统一过程三大特点，与面向对象的方法有什么关系？

- 特点：
  - 注重风险：在项目生命周期早期特别关注项目风险，在每次迭代的精化阶段必须做好选择，规避大的风险。
  - 以架构为中心：软件架构提供一个其它开发过程所涉及到的中心点，也就是系统的一个蓝图或者框架。
  - 迭代和演化：它允许一个项目在不完整或者没有很好的知识储备的时候就开始。
- 与面向对象方法的关系：
  - RUP (Rational Unified Process) 是一种基于 UML 的、以构架为中心、用例驱动与风险驱动相结合的迭代增量过程。它将软件开发过程要素和软件工件要素整合在统一的软件工程框架中，是一个面向对象的程序开发方法论 

### 3、简述统一过程四个阶段的划分准则是什么？每个阶段关键的里程碑是什么？

- 初始阶段：
  - 准则：为系统建立业务案例 (Business Case) 并确定项目的边界。 
  - 里程碑：生命周期目标里程碑，包括一些重要文档，如项目构想 (Vision)、原始用例模型、原始业务风险评估、一个或者多个原型、原始业务案例等 。
- 精华阶段：
  - 准则：分析问题领域，建立健全的体系结构基础，编制项目计划，完成项目中高风险需求部分的开发 。
  - 里程碑：生命周期体系结构里程碑，包括风险分析文档、软件体系结构基线、项目计划、可执行的进化原型、初始版本的用户手册等。通过评审确定软件体系结构已经稳定、高风险的业务需求和技术机制已经解决、修订的项目计划可行等。 
- 构建阶段 ：
  - 准则：完成所有剩余的技术构件和稳定业务需求功能的开发，并集成为产品，详细测试所有功能。 
  - 里程碑，包括可以运行的软件产品、用户手册等，它决定了产品是否可以在测试环境中进行部署。此刻，要确定软件、环境、用户是否可以开始系统的运行。 
- 移交阶段：
  - 准则：确保软件对最终用户是可用的。 
  - 产品发布 (Product Release) 里程碑，确定最终目标是否实现，是否应该开始产品下一个版本的另一个开发周期。在一些情况下这个里程碑可能与下一个周期的初始阶段相重合 

### 4、软件企业为什么能按固定节奏生产、固定周期发布软件产品？它给企业项目管理带来哪些好处？

- 原因：因为软件开发周期的确定的，每个时间段应该做什么事情，该时间段应该持续多长时间都是确定的，既然这些都确定了，按照计划来，就可以定期发布产品。
- 好处：方便项目管理，因为开发的节奏和周期已经确定了，所以只需要按照这个节奏来就可以了。不需要在做计划，管理更加容易。



### 5、TAPD

backlog是树结构，如下图：

<img src="requiments.PNG">

可以创建迭代，把需求划分到每一次迭代中去

<img src="iteration.PNG">

可以创建缺陷，直接选择缺陷在哪个版本，的哪个模块，以及它的严重程度：

<img src="bug.PNG">

kanban功能方便及时查看情况：

<img src="kanban.PNG">