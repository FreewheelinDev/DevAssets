## UI slides 中的一些法则和小点

* 我们的总目的是为了高效的操作和控制
* 我们交互发生的环境是在日常生活和工作中
* 关于我们的软件，就是：尽可能多的
* 要考虑多个方面的问题 也就是说inclusion 比如accessibility，用户的地理位置，经济情况，年龄，语言等，比如我们这次的国际化，一定会是一个考察inclusion的地方**（举个例子，中东的用户会从右到左来使用软件，也许我们在后面的迭代中可以设置一个反转布局，按一下就反转）****（多语言支持也许也是我们软件的重要部分）**
* 基本的可用性：充足的对比，题型和年龄相关的限制
* 基本的设计原则
  * 可感知（比如文字代替，两个物件的区分度）
  * 可操作（操作时间等等，比如我们说我们软件不会给用户留下不好操作的空间）
  * 可以理解（比如输入的助手
  * 健壮性：不同的用户都能用

* 认知影响，主要是注意accessibility
* **构建主义**（constructivism）
  * FG解释了人们区分形状和背景的方法
  * 利用相似性来构建关系 然后不同的类型会形成链接
  * **采用估计的方法，来提示（比如我们暗示用户一个地方是可以滚动的）**
  * closure（**人们看到ibm的图标虽然没有封闭但是也会下意识的闭上**）
  * 推测
* 可见性原则（Affordance theory）（**小点不用看，一个例子就是选好你的svg图标**）
  * 可察觉（比如home button）
  * 错误察觉 alert
  * hidden 察觉
  * 正确的reject（想象手机上的toggle button）

* color theory
  * **颜色来凸显定位 然后引导用户（可以和需求分析挂钩）**
* 设计合理的互动方式
* 互动方式主要有（proper selection of ）
  * issuing instruction（比如spell checker，我们软件就是）
  * conversation（帮助少部分儿童或者残障人群）
  * 直接操作
  * 探索（比如AR之类的，我们软件就是查看视频，player）
  * 我们的软件1+2+3+4都有

* 设计模式：软件组件的复用性（代码和ui都有所体现）

* 用户需求

  * 我们关注用户的需求  这就是我们的目标
  * 但是在开发的时候要找trade off
  * user-centered apporach
    * 我们很在就关注用户的行为
    * 经验注意的评估（观察用户的行为等）
    * 设计我们的交互设计lifecycle
    * 关注不同类型的需求（UX属于非功能性需求）
    * **调查需求（我们采用focus group 和问卷 以及市场调查**）
    * 我们同时要设计一个简单的help 和 doc （因为我们知道界面的affordance<signifiers<documentation）
    * 好好的管理需求 比如版本控制等
    * 充分分析需求，在数据收集结束后就开始分析
    * 分清对象
    * 所以本质上需求的过程就是数据收集和解释

* 经典的UI模型**(因为我们并不能很好的进行大规模的调研，因此实践这些UI模型是很必要的)**

  * Schneiderman's 'Eight Golden Rules

    * 统一性

    * 快捷键

    * feedback

    * Design dialogues to yield closure:

    * Offer simple error handling

    * Permit easy reversal of actions（Undo！！！）

    * Support internal locus (the place where something happens:（一**切都在掌控—很多视频软件都没做到，感觉卡顿了，或者担心视频丢了）**

    *  Reduce short-term memory load:（**比如删除不要输入，要在列表里面找）**

    *  “Golden rules” addition:

      关注新手的需求 以及用户的多样性

  * NIELSEN'S HEURISTICS 

    * https://zhuanlan.zhihu.com/p/84932306

  * Behavior model

    * predictive models
      * esitimate	
      * likeihood
      * probability
    * descriptive models(eg=>FITTS)
      * learn
      * understand
      * Describe

* Design for prototyping 

  * generate alternatives 
  * brianstroming
  * card sort 用来build structure of the UI

* **prototype**

  * can be wireframes, ppt, cardboard mock up, software with limited functionality
  * or an almost completed piece of software
  * why prototyping?=> evaluation and feedback are central to interaction design
  * 低fidelity 和高fidelity
  * skecth card paper storyboard
  * high fidelity using better software （PS,GIMP，XD，qtDesigner）(**比如我们第一次迭代出线框图就用手画，后面用高精度的工具了**)
    * All prototypes involve compromises

* evaluation（参考我第一次的文档和ppt

 