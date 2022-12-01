```
'''
The copyright always belongs to Freewheelin'.

Sharing is forbidden.

Author: Zihan Zhou
Date: 01-12-2022
'''
```
## Extracted

* 我们要有5次迭代

* 总的一些产出

  * 需求文档（在前期先打草搞）
  * use case

  * 两分钟的演示视频
  * 总文档
  * 实景看板
  * 测试文档
  * 每次的会议记录
  * **软件**
  * 时间安排（总的和具体的=>{makeup}）

* 每次迭代都有的产出

  * 线框图
  * 软件设计图
  * 可执行软件
  * 文档 =>{按照结构}
  * 短视频
  * 看板的更新

* 每次要做的

  * **代码部分** 

    * 架构的设计 => designer<交互>backend
    * 代码的实现：交互和实现

  * Git 

    * master + dev + tmp

    * 小的commit到tmp里面
    * 写好了就合并到dev

  * 文件备份以及代码备份（本地+云盘）

  * 文档

    * 每次都有会议记录(模版化)
    * 大的迭代的记录（包含在每次的产出里）
    * 总产出文档的草稿等等（use case的草稿 需求的草稿 test的草稿）

  * 视频制作
  * 看板和to do list的更新
  * 每次eval的部分（问卷 自己评估等）

## 迭代文档(process doc)



### 编写之前...

> You will create process documentation throughout the project that will be the foundation of your report - detailing the design processes with a range of the following suggested approaches:

正如每次文档中所说的，我们发现 这个每次的“process doc”是最后**大报告的基础**

我在第一次写好模版，后面我们就只需要**按图索骥的来查找，替换信息**就好

在开始之前，我们再来确认编写process doc (AKA iteration doc) 的规则，并且在编写文档的时候**反复问自己**：我的文档是否符合下面的标准

*  文档要基于UI课上的一些理念来制作，同时好好考虑**use case的情形以及相关限制**，这样能够更好的refine**迭代需求**

* 明确我们的应用潜在的应用平台（desktop, mobile,web,etc...）  然后需要一些**图片在文档里来作为支撑**
* 明确我们用qt/c++ 开发 同时为**多个平台设计**（硬件->不同尺寸的屏幕, 软件-> 不同的操作系统）
* 最后，记住每次迭代我们都是有一个新的原型的，它包含一些提升，我们要从不同的角度去**evaluate**他（队内评估，user评估，同类产品对比）

```c
isStandardized?rethink-and-refine:proceeding
```

### 文档结构

>  原型，代码，评估

* 模版说明

```markdown
1.prototypes
	1.1 Goal of current cycle and priority selections
	<本次迭代的目标以及对于各个目标优先级的选择>
	1.2 Prototyping techniques and software utilizations
	<用到的原型技术的方法和用到的软件>
	<technique: sketch, wireframes, video, native...>
	<software: Photoshop, Gimp, Qt Designer, etc...>
	1.3 Theoretical motivations
	<我们原型中出现相关设计的理论动机>
	<IMPORTANT:这一点应该与ppt中的某一点相呼应>
	1.4 Working technique chosen
		<讲述选择的合作工作技术>
		1.4.1 Justifications
		<给出原因，比如为什么选agile，为什么选scrum>
		1.4.2 Evidence
		<给出证明，比如截屏，拍照，miro/kanban>
	1.5 Exploration and discussions
		1.5.1 The Design
		<调查相关的设计>
		<including photos, screenshots of wireframes,
		paper prototypes, etc..>
		1.5.2 The Process and evolution
		<调查相关的开发流程和迭代，进化过程>
2.code
	2.1 Illustrating the UI improvements
	<证明写出来的产品在ui上的提升：代码简图，UI简图>
	2.2 Scrutinize the differences
	<列一个表 说明写出来的程序和原型设计的区别>
	<1.improvement
	2.time constraints
	3.technical difficulites>
3.evaluation
	3.1 Evaluation techniques
	<用到了那些评估方法->来源自ppt 比如heuristic evaluation, cognitive walkthrough, questionnaire, etc>
	3.2 Justifications on evaluation techniques
	<使用这个评估方法的原因>
	3.3 Outcomes of the evaluation
	<accepted or reject 给出这次cycle的总评价>
	3.4 Evidence of the evaluation
	<评价方法的证据>
	<table of the results, anonymised images of the evaluations, etc...>
```



## 一些值得提醒的点

> 大家多注意要求里没发现的，因为这份takeaway tips 不会覆盖文档里的所有点

>因此 队内任何队员如果有好的点子的话，可以在github上修改这份文件，并且在teams内进行广播
