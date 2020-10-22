# 高级数据库中文课件

#### 中文课件阅览链接：
[https://alqin.gitbook.io/chinese-docs/](https://alqin.gitbook.io/chinese-docs/)

课件是中国科学技术大学-计算机科学与技术学院-软件工程-高级数据库上课用的英文PPT。

本项目是想为上这门课的同学提供一个中文课件，方便大家复习学习，通过该门课程。

## 翻译流程

### 第一阶段 

先将[英文课件](http://222.195.93.99:82/db/#/ppt)的内容按现有的目录结构翻译成中文，其中：

- 文章正文内容均放在 `md` 目录下，采用 `md` 格式。
- 文章中所用到的图片资源暂时先放在 `images`目录下，后续托管到第三方平台。
- 图片按照文档的 `主目录-副目录-编号`的格式命名。

#### 文件命名规则

- 文件名为[英文课件](http://222.195.93.99:82/db/#/ppt)对应文章标题（即下面列出的项目翻译目录）的`翻译名称`。
- 对于下级子页面文档，将其放在以父级文档名称命名的文件夹下面。

例如：`基础-Introduction and Conceptual Modeling` 这节内容，对应 `md/基础` 这个文件夹下的 `简介和概念模型.md` 文件。

### 第二阶段

根据英文PPT，制作成类似在线文档，方便大家参阅。

## 参与项目

欢迎你参与翻译本项目，在翻译的过程中，可以锻炼你的英语能力和对数据库的理解。

一个个 commit 堆积起来就是一个了不起的  repository，欢迎你 Fork 并提交 Pull Request 或者 Issue ，哪怕是改正一个错别字、修正一个病句，我们都非常感谢您的贡献。

参与方法和步骤如下：

* 登录 https://github.com

* Fork `git@github.com:SuperBugs/USTC-database-zh-cn.git` 或者点[仓库地址](https://github.com/SuperBugs/USTC-database-zh-cn.git)
* 克隆您的远程仓库到您的本地工作目录：`git clone <remote>`

* 创建您的特性分支 `git checkout -b feature-new`

* 提交您的改动 `git commit -m 'Added some features or fixed a bug or change a text'`

* 将您的改动记录提交到远程git仓库 `git push origin feature-new`

* 然后到 github 网站的该 git 远程仓库的 feature 分支下发起 Pull Request

如果你有任何疑问或者建议、技巧，欢迎提出Issues，大家一起交流。

## 英文PPT课件链接

* [http://222.195.93.99:82/db/#/ppt](http://222.195.93.99:82/db/#/ppt)

## 正在翻译文章+作者

* AllOfIt+Al

## 项目翻译目录
* 基础
  * ~~Introduction and Conceptual Modeling~~
* DB系统结构
  * Database System Concepts and Architecture
  
* ER图 (Data Modeling Using the Entity-Relationship (ER) Model)
  * Example Database Application (COMPANY)
  * ER Model Concepts
  * ER Diagrams - Notation
  * ER Diagram for COMPANY Schema
  * Alternative Notations – UML class diagrams, others
  
* 增强ER图(Enhanced Entity-Relationship and UML Modeling)
  * Part I
  * Part II
  
* 关系模型(The Relational Data Model and Relational Database Constraints)
  * Relational Model Concepts
  * Relational Model Constraints and Relational Database Schemas
  * Update Operations and Dealing with Constraint Violations

* 关系代数(The Relational Algebra and Calculus)	
  * Example Database Application (COMPANY)
  * Relational Algebra
  * Relational Calculus
  *Overview of the QBE language (appendix D)

* ER图与关系DB(Relational Database Design by ER- and EERR-to-Relational Mapping)
  * ER-to-Relational Mapping Algorithm
  * Mapping EER Model Constructs to Relations 

* SQL
* SQL进阶	
* 规范化	
* 磁盘与文件
* 文件索引	
* 查询优化	
* DB设计实践
* 事务	
* 并发控制	
* 恢复技术
* NoSQL（TBA）

因为PPT分节并不明确，请翻译者自行酌情分节，并且将翻译结束的章节使用删除线划去。

如第一章第一节：

    *  ~~Introduction and Conceptual Modeling~~

## 贡献者（按参与时间排序）

- [Al](https://github.com/SuperBugs)
（Fork 之后自行添加到最后）

## 开源协议

 - [MIT](LICENSE)