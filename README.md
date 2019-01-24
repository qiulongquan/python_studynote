python_studynote
===========================
python学习笔记
	
* 现在   python后端开发   大数据处理hadoop  数据分析   +   AWS 掌握

* 将来目标   机器学习      数据挖掘  

===========================

* 每天  写一些代码   并且 发布到github上去
	* GitHubを用いたチーム開発の実務経験
	* github 使用方法 http://blog.sina.com.cn/s/blog_4d9c3fec0102w7g9.html

* 平时多刷刷leetcode，看看剑指offer/面试金典，都是套路啊~~
![description1](https://github.com/qiulongquan/python_studynote/blob/master/image/11.JPG "description1")
	* 剑指offer牛客网      面试题目 刷题练习
	* https://www.nowcoder.com/courses/10
	


## Python（Django）のご経験     重要
麦子学院
http://www.maiziedu.com/line/python/#
django项目实战之购物系统
本课程将使用Python语言与Django Web开发框架搭建一个强大的购物系统。通过本项目的学习，全面系统地掌握使用Django开发出功能强大的网站， 更重要地是让学员掌握Web开发从设计到部署的一整套流程，有能力根据自身需求去实现功能或者在现有基础上进行扩展。

### web开发框架   django
	 M:模型（Model）,负责业务对象和数据库的关系映射。
	 T:模板（Template）,负责如何把页面展示给用户。
	 V:视图（View）,负责业务逻辑，并在适当时候调用模型和模板。
![description2](https://github.com/qiulongquan/python_studynote/blob/master/image/mtv结构图.jpg "description2")

### django环境搭建
	Python==3.6.4
	Django==2.1.1 
	要使用新版本的django 2.1.1

### linux 下 安装python3 和 django环境
1. 错误：no acceptable C compiler found in $PATH
	* 解决办法：安装GCC软件套件   yum install gcc
2. 安装方法
	* https://www.cnblogs.com/freeweb/p/5181764.html
	* 需要注意的地方看自己录制的视频  linux环境python3和django安装
3. root权限
	* 不能直接root 进去后 sudo su即可
	* AWS的ec2-user切换到root登陆后直接sudo -i
	* 表示以root身份登录，进程的实际用户ID和有效用户ID都变成了root，主目录也切换为root的主目录。
4. Django model select获取数据详细讲解 主要是程序中使用到的一些sql文的使用方法
	* https://segmentfault.com/a/1190000016053857
5. Django数据库操作之save与update
	* 使用save:
		* k = Example.objects.get(id=481)
		* k.total_calories = 12
		* k.save()
	* 使用 update
		* Example.objects.filter(id=481).update(total_calories = 10)
	* 从SQL的执行情况来看,使用upate是要优于save方式的。
		* 从使用情境上看，update更加适用于批量数据更新，而save则更适合当然也只适合做单条记录的数据更新操作了。

你看过django的admin源码么;    
看过flask的源码么;你如何理解开源;    
CSRF是什么，django是如何避免的;   
XSS呢;
- test1
- test2

# フレームワーク　　web开发框架   Flask    framwork  
Flask框架开发
轻量级的Web开发框架Flask的学习，很多公司都需要这样的轻量级开发工程师，我们通过Flask的学习也会完整了解和使用Python的Web开发



# 全栈工程师是指掌握多种技能，并能利用多种技能独立完成产品的人。
 [1]  也叫全端工程师(同时具备前端和后台能力)，英文Full Stack engineer。


## Linux基础

(1) 文件处理命令
(2) 权限管理命令
(3) 帮助命令
(4) 文件搜索命令
(5) 压缩解压命令
(6) 命令使用技巧
(7) VIM使用
(8) 软件包管理
(9) 用户和用户组管理
(10) Linux Shell开发　　shell的编写开发要看一下  版本要注意一下  实验楼的是ubuntu dash  有些shell执行有错误
gcc工具链
centOS 软件安装与卸载
常用服务器 ssh  ftp
网络管理
进程管理
shell 操作
磁盘管理

   Linux基本操作(bash, vi)     重要
   Linuxなどの各種サーバ設計、構築、運用経験者

Linux运维自动化开发
(1) Python开发Linux运维

04. Linux相关
如何查看剩余内存
如何查看端口是否被占用
如何查看一个程序的PID以及它的所有子进程
如何为一个目录下的所有文件添加权限
如果你对一个目录具有写权限，那么你是否具有对这个目录下的所有文件具有删除权限？
对Linux多路复用的理解
修改IP地址的方法

讲一下你常用的Linux/git命令和作用;


## python数据分析
https://www.shiyanlou.com/courses/764   Python 数据分析入门与进阶
https://www.shiyanlou.com/courses/780   Python 气象数据分析：《Python 数据分析实战》
(1) numpy数据处理
(2) pandas数据分析
(3) matplotlib数据可视化
(4) scipy数据统计分析
(5) python 金融数据分析
・大規模な開発や分析および分散処理の実務経験   ・大規模データの分析経験がある方
・アクセス数やデータ量が多いサービスの開発や運用の実務経験
ビッグデータ解析     データ分析
データ分析・アルゴリズム開発
TreasureData、TreasureWorkflowを利用した集計処理の開発経験 


## python大数据
(1) Hadoop HDFS
(2) python Hadoop MapReduce
(3) python Spark core
(4) python Spark SQL
(5) python Spark MLlib

## python机器学习
(1) 机器学习基础知识简介
(2) KNN算法
(3) 线性回归
(4) 逻辑斯蒂回归算法
(5) 决策树算法
(6) 朴素贝叶斯算法
(7) 支持向量机
(8) 聚类k-means算法



csdn学院    很不错的网络全方面教学 包括python
* https://edu.csdn.net/courses/o317_k
![description2](https://github.com/qiulongquan/python_studynote/blob/master/image/2.jpg "description2")

## Python大数据

第四至第五阶段为Python全栈工程师后端，主要学习Django、 Flask以及Tornado，学员需要完成对应的实战项目

第六阶段为Linux基础，主要学习Linux相关的各种命令，如文件处理命令、压缩解压命令、权限管理以及Linux Shell开发等;
 

第七阶段为Linux运维自动化开发，主要学习Python开发Linux运维、Linux运维报警工具开发、Linux运维报警安全审计开发、Linux业务质量报表工具开发、Kali安全检测工具检测以及Kali 密码破解实战;


第八阶段为Python数据分析，主要学习numpy数据处理、pandas数据分析、matplotlib数据可视化、scipy数据统计分析以及python 金融数据分析;
 

第九阶段为Python大数据，主要学习Hadoop HDFS、python Hadoop MapReduce、python Spark core、python Spark SQL以及python Spark MLlib;
 

第十阶段为Python机器学习，主要学习KNN算法、线性回归、逻辑斯蒂回归算法、决策树算法、朴素贝叶斯算法、支持向量机以及聚类k-means算法。


## Python相关知识点
https://www.shiyanlou.com/courses/764   Python 数据分析入门与进阶
https://baijiahao.baidu.com/s?id=1612813358659183691&wfr=spider&for=pc   python 知识点
设计模式   
1. 实现一个单例模式
* 基本原理
	* 拦截类的创建
	* 修改类的定义
	* 返回修改后的类
* Python 的模块是天然的单例模式，这在大部分情况下应该是够用的，当然，我们也可以使用装饰器、元类等方法
	* 使用模块
	* 使用 __new__
	* 使用装饰器（decorator）
	* 使用元类（metaclass）

2. 工厂模式
	* 工厂方法模式去掉了简单工厂模式中工厂方法的静态属性，使得它可以被子类继承。对于python来说，就是工厂类被具体工厂继承。这样在简单工厂模式里集中在工厂方法上的压力可以由工厂方法模式里不同的工厂子类来分担。也就是工厂外面再封装一层。

## 开发框架
### RDBMSを用いた開発経験
    类与对象，继承，多态
### Python线程、进程    介绍下协程，为何比线程还快;
    模块制作  发布    安装  使用
### 实现一个装饰器 decorator  手写个使用装饰器实现的单例模式;
    装饰器本质上就是闭包,装饰器在不改变原函数的定义的条件下,给原函数扩展功能. 
	* 装饰器 解释 https://blog.csdn.net/u010358168/article/details/77773199
	* 第6种：装饰器 decorator的知识点 闭包
 	* 闭包能够完成较为复杂的功能,包含功能和数据,传递的是数据+功能(即外层函数能保存接收的数据给里面的函数使用) 
 	* 闭包也具有提高代码可复用性的作用.    

### 用Python实现快排   
	1. 手写快排;
		* 先从待排序的数组中找出一个数作为基准数（取第一个数即可），然后将原来的数组划分成两部分：小于基准数的左子数组和大于等于基准数的右子数组。然后对这两个子数组再递归重复上述过程，直到两个子数组的所有数都分别有序。最后返回“左子数组” + “基准数” + “右子数组”，即是最终排序好的数组。
	2. 堆排;
	3. 几种常用排序的算法复杂度是多少;
![description1](https://github.com/qiulongquan/python_studynote/blob/master/image/各种排序算法时间复杂度.jpeg "description1")
![description1](https://github.com/qiulongquan/python_studynote/blob/master/image/时间复杂度线性函数.jpeg "description1")
![description1](https://github.com/qiulongquan/python_studynote/blob/master/image/时间复杂度线性函数2.jpeg "description1")
	4. 快排平均复杂度多少，最坏情况如何优化;
		* 快速排序和冒泡排序是经常使用的排序方法 但是快速排序的效率更高 
		* 快速排序最优的情况下时间复杂度为：O( nlogn )
		* 快速排序最差的情况下时间复杂度为：O( n^2 )
	5. 如果系统中需要很多个Python版本，如何进行Python版本的管理
	    * https://blog.csdn.net/qq_22194315/article/details/77968609
	    * 我们在安装Python3（>=3.3）时，Python的安装包实际上在系统中安装了一个启动器py.exe，默认放置在文件夹C:\Windows\下面。   
	    这个启动器允许我们指定使用Python2还是Python3来运行代码（当然前提是你已经成功安装了Python2和Python3）。
	    * py -2 tab.py 
	        * python2版本启动   #! python2      
	    * py -3 tab.py  
	        * python3版本启动   #! python3
	    * 当Python2和Python3同时存在于windows上时，它们对应的pip都叫pip.exe，所以不能够直接使用 pip install 命令来安装软件包。    
	    而是要使用启动器py.exe来指定pip的版本。    
	    命令如下： 
		    py -2 -m pip install XXXX       
	            py -3 -m pip install XXXX    
	
	6. 如何实现一个全局变量？(除了global,还可以通过单例模式)
		* 总结：如果要在函数中给全局变量赋值，需要用global关键字声明。
![description1](https://github.com/qiulongquan/python_studynote/blob/master/image/global全局变量.jpg "description1")
![description1](https://github.com/qiulongquan/python_studynote/blob/master/image/global全局变量1.jpg "description1")
	

数据库CRUD操作/查询优化以及数据库知识量
框架的对比和了解/项目具体模块的业务逻辑描述
常见排序算法
Linux系统的常用命令和Linux系统了解程度考核   Linux系统的底层原理和了解程度
项目部署用到的服务器的配置和了解程度
数据库基本功必须掌握但同时更重要的是理解为什么和是如何实现的，拓展自己知识面
目前Golang在后端中也逐渐流行，有时间还是需要去掌握


# 02. 数据库
数据库的数据是实时更新的吗？每点击一次，数据库数据修改一次？
Redis hash的个数
如何修改Redis数据库的库的个数？
Redis数据库如何实现持久化
Redis数据库支持的数据类型
Redis使用AOF方式持久化，aof文件不断增大，如何处理？
Redis数据库如何设置密码
hash表是如何生成的
MySQL数据库如何使用sql语句插入一条数据
MySQL数据库的慢查询有了解过吗
MySQL数据库如何进行查询优化
如何很多请求同时对Redis的同一个键进行访问，如何保证数据安全
说说Redis的淘汰机制
我的MySQL数据库每天晚上12点进行全备份。第二天有员工在9点钟误删除了一个数据库，但在10点钟才被发现。问如何进行恢复被误删除的数据库并同时保留9点到10点钟新增的数据同时不影响业务的正常运行?
当数据越来越多，如何避免hash槽中key出现相同的情况?
MongoDB在哪些场合使用过？
NoSQL了解么，和关系数据库的区别;redis有几种常用存储类型;


# 03. 项目部署
大家都说Nginx快？快的原因是什么？
对RPC了解吗?
如何在服务器上设置业务进程数？
说说正向代理和反向代理


# 06. 网络编程
说一下实现TCP建立连接的过程以及当时进入了什么状态？
为什么建立连接只需要3次，断开连接需要4次？
为什么断开连接时第二次和第三次要分开，不能合在一起吗？
TCP UDP区别
http一次连接的全过程：你来说下从用户发起request——到用户接收到response;
http连接方式。get和post的区别，你还了解其他的方式么;
restful你知道么;
TIME_WAIT过多是因为什么;
状态码你知道多少，比如200/403/404/504等等;
session和cookie的联系与区别;session为什么说是安全的;


# 07. 项目相关
说一下一个请求过来到返回response的过程
如何实现单点登录
JWT token是如何进行生成和校验的
了解过哪些后端框架？Tornado了解吗?
了解过webapp2吗
Django如何实现csrf攻击保护
说说你项目中遇到的困难以及如何解决
说说你认为自己最有成就感或最深刻的项目
对KAFKA了解吗？用过哪些消息队列？使用过RabbitMQ吗?
项目团队几个人？开发多长时间？


# 08. 版本控制
如何从远程仓库拉取分支到本地
如何进行版本回退 09. 其他内容
Celery的原理和应用场景
Elasticsearch 的原理
平时是如何学习的?有关注哪些技术?
Docker的了解，常用命令，如何暴露端口
对ERP了解吗？Odoo了解吗?



# AWSもしくはGCPのいずれかを使用した開発経験    
GoogleBigQueryの経験
  AWS使用経験　　重要
  AWSを使った環境構築及び監視設定等のご経験    重要
  AWSを使ったインフラ構築、及び運用に携わっていただきます。
AWSを用いたインフラ構築経験   重要
51cto学院
http://edu.51cto.com/course/15086.html
 数据分析 > AWS 峰会-大数据系列课程 
http://edu.51cto.com//center/course/lesson/index?id=304661
http://edu.51cto.com/course/2925.html
深入剖析Amazon公有云（AWS）【第一季】—构建云解决方案 
使用AWS SAM构建AWS Lambda应用视频课程 
http://edu.51cto.com/course/12331.html


# 爬虫
3.伪装成浏览器访问
某些网站反感爬虫的到访，于是对爬虫一律拒绝请求。这时候我们需要伪装成浏览器，这可以通过修改http包中的header来实现：
4.页面解析
对于页面解析最强大的当然是正则表达式
5.验证码的处理
google那种验证码， 没办法。
简单的验证码：字符个数有限，只使用了简单的平移或旋转加噪音而没有扭曲的，这种还是有可能可以处理的，一般思路是旋转的转回来，噪音去掉，然后划分单个字符，划分好了以后再通过特征提取的方法(例如PCA)降维并生成特征库，然后把验证码和特征库进行比较。这个比较复杂，这里就不展开了，具体做法请弄本相关教科书好好研究一下。
6. gzip/deflate支持
现在的网页普遍支持gzip压缩，这往往可以解决大量传输时间，以VeryCD的主页为例，未压缩版本247K，压缩了以后45K，为原来的1/5。这就意味着抓取速度会快5倍。
然而python的urllib/urllib2默认都不支持压缩，要返回压缩格式，必须在request的header里面写明'accept-encoding'，然后读取response后更要检查header查看是否有'content-encoding'一项来判断是否需要解码，很繁琐琐碎。如何让urllib2自动支持gzip,defalte呢?
7、多线程并发抓取
单线程太慢的话，就需要多线程了，这里给个简单的线程池模板这个程序只是简单地打印了1-10，但是可以看出是并发的。
虽然说Python的多线程很鸡肋，但是对于爬虫这种网络频繁型，还是能一定程度提高效率的。


# Sparkの実務経験 　重要
* Spark是一个用来实现快速而通用的集群计算的平台。扩展了广泛使用的MapReduce计算模型，而且高效地支持更多的计算模式，包括交互式查询和流处理。在处理大规模数据集的时候，速度是非常重要的。Spark的一个重要特点就是能够在内存中计算，因而更快。即使在磁盘上进行的复杂计算，Spark依然比MapReduce更加高效。
* Spark编程模型(一) https://www.cnblogs.com/miqi1992/p/5621268.html
* Sparkなどの大規模分散処理技術を用いたデータ分析の実務経験　
http://edu.51cto.com/course/12824.html
* 【Python版pyspark】Spark大数据基础入门视频课程 
https://www.shiyanlou.com/courses/1003   Spark机器学习--运用逻辑回归分析银行营销数据 


# ・ビッグデータ(Hadoop)の経験
 数据分析 > 大数据分析入门视频课程    hadoop
http://edu.51cto.com/center/course/lesson/index?id=226836  
https://www.shiyanlou.com/courses/1167  Python玩转Hadoop之MRjob入门

# ・Hiveの実務経験

# ・データマイニングの実務経験         数据挖掘

# ・DMP構築の実務経験　　　DMP構築　重要

# フロントエンド（Angular.js、React.js,、Vue.js等）の開発経験　　知見



# ・機械学習の実務経験     重要
機械学習ライブラリの実務経験
https://www.shiyanlou.com/courses/814#    使用 Python 实现深度神经网络
https://www.shiyanlou.com/courses/863   决策树实战项目-鸢尾花分类
https://www.shiyanlou.com/courses/1162   Python 使用机器学习玩转 Flappy Bird 游戏
Tableau/PowerBIなど、BIツールの実務経験 
　-機械学習手法の実サービスへの適用
 　-効果予測
 　-属性推定
 　-関連分野の研究や調査および大規模データ分析によるサービスの改善
・ RDBMSを用いた開発経験
・APIの実装経験


ロジスティック回帰モデル
-決定木
-混合分布
-最尤推定
-EMアルゴリズム
-情報量規準

・サーバ構築経験がある方



# 実務経験に基づく年収の目安（週5日作業の場合）

・Pythonの実務経験1年未満：35万円/月
・Pythonの実務経験1年～2年：50万円/月
・Pythonの実務経験2年～3年：60万円/月
・Pythonの実務経験3年～5年：65万円/月
・Pythonの実務経験5年以上：70万円/月

https://freelance.levtech.jp/project/skill-7/p4/

https://agency-star.com/



程序员35岁以后一定不能还是在玩底层的码农，或者至少不能重复的工作，可以尝试架构，可以是尝试管理，可以尝试运营！但是就是不能年复一年日复一日的重复coding,没有提高没有突破，你只是10年经历而不是10年工作经验！ 


# 专业名词解释


云计算    AI时代

IaaS，PaaS，SaaS 的区别
http://www.ruanyifeng.com/blog/2017/07/iaas-paas-saas.html
* SaaS（Software As A Service，软件即服务）的观念
http://edu.51cto.com/course/15008.html
企业级客户管理SaaS服务——企点产品使用介绍 
* PaaS（Platform As A Service，平台即服务）的观念
* IaaS：基础设施服务，Infrastructure-as-a-service


Yarn
* Apache Hadoop YARN （Yet Another Resource Negotiator，另一种资源协调者）是一种新的 Hadoop 资源管理器，它是一个通用资源管理系统，可为上层应用提供统一的资源管理和调度，它的引入为集群在利用率、资源统一管理和数据共享等方面带来了巨大好处。


Zookeeper做了什么？
* 1.命名服务   2.配置管理   3.集群管理   4.分布式锁  5.队列管理
* 最终一致性：client不论连接到哪个Server，展示给它都是同一个视图，这是zookeeper最重要的性能。 


Tornado
* Tornado是一种 Web 服务器软件的开源版本。Tornado 和现在的主流 Web 服务器框架（包括大多数 Python 的框架）有着明显的区别：它是非阻塞式服务器，而且速度相当快。
* 得利于其非阻塞的方式和对epoll的运用，Tornado 每秒可以处理数以千计的连接，因此 Tornado 是实时 Web 服务的一个 理想框架。


epoll
* epoll是Linux内核为处理大批量文件描述符而作了改进的poll，是Linux下多路复用IO接口select/poll的增强版本，它能显著提高程序在大量并发连接中只有少量活跃的情况下的系统CPU利用率。


Dockerを利用したサービス運用経験
* 原理
Docker核心解决的问题是利用LXC来实现类似VM的功能，从而利用更加节省的硬件资源提供给用户更多的计算资源。同VM的方式不同, LXC 其并不是一套硬件虚拟化方法 - 无法归属到全虚拟化、部分虚拟化和半虚拟化中的任意一个，而是一个操作系统级虚拟化方法, 理解起来可能并不像VM那样直观。


Redis   了解
	性能极高 
	Redis 是完全开源免费的，遵守BSD协议，是一个高性能的key-value数据库。
	丰富的数据类型 
	原子 – Redis的所有操作都是原子性的，意思就是要么成功执行要么失败完全不执行。
	丰富的特性 – Redis还支持 publish/subscribe, 通知, key 过期等等特性。


Swiftを用いた開発経験   了解
	Swift 是一种支持多编程范式和编译式的开源编程语言,苹果于2014年WWDC（苹果开发者大会）发布	用于开发 iOS，OS X 和 watchOS 应用程序。


海量数据处理分成两块，一是系统建设技术，二是海量数据应用。
先说系统建设现在主流的技术是HADOOP，主要基于mapreduce的分布式框架。目前可以先学习这个。但是我的观点，在分布式系统出来之前，主要是集中式架构，如DB2，oracle。为什么现在用分布式架构，那是因为现在集中式架构受限于IO性能，出来速度慢，如果又一种硬件技术，可以很快地处理海量数据，性能上能满足需求，那么集中式架构优于分布式架构，因为集中式架构稳定，运维压力小。现在的集中式架构要么性能达不到要求，要么就是过于昂贵。我期待一种技术出现，可以非常快地传输和处理数据，那么集中式架构将再次进入人们眼球。再说海量数据应用。海量数据应用主要是数据挖掘和机器算法。具体有不同的应用场景，如个性化搜索和推荐，社交网络发现，精准营销，精准广告，实时最优路径，人工智能等等。



总结   数据是根本   数据从哪里来   来了以后怎么快速储存读取    储存后怎么利用分析


在国内的环境下，似乎还是Hadoop用得更多，其他更fancy的东西比如presto/spark什么的，湾区也算是新鲜事物，并不是很多公司都在用（也有原因是真的适用的公司也不算太多了）。更实际节省的做法是，学Hadoop，至少要了解系统架构和数据的流向，比如怎么partition，怎么shuffle，combiner怎么work之类的大概念，对入门人士面试官大多也就是面这些，不会问太深，再深入的问题，是留给有行业经验的人的。对刚入门想入行的人，知道上面这些，再写写类似Word Count（大数据版的helloworld），之类的有个实际概念，就可以找公司面着玩看了。其他东西可以都了解个皮毛，跟上社群的演进。大数据更多是工程的东西，不是那么学术，多看看比深挖一个对初学者更有好处。每个工具被发明，都是解决一个特定问题的，大数据没有一个产品是万能的，都是解决某个特定问题来的，看到新鲜事物就想想为什么需要这样的工具，背后有什么需求。
