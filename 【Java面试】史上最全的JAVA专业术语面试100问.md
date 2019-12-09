# [【Java面试】史上最全的JAVA专业术语面试100问](https://blog.csdn.net/qq_26465035/article/details/103160711)

**春风如贵客，一到便繁华。各位看官<font color='red'>点赞</font>再看，养成好习惯(●´∀｀●)**

**之后还会推出JAVA面试系列文章，敬请关注！**

> **gitee上已经开源 https://gitee.com/Li-Ren/blog 有我的联系方式和一线大厂面试点脑图，欢迎Star和留下你认为重要的知识点。**
>
> **话外音：最近收到很多私信，除了感谢和讨论的留言之外，本篇博客也被业内的一个大厂给翻牌子了。哈哈感谢肯定哦๑乛◡乛๑**
>
> **努力做到一周一更新吧，因为周六周天我要约小姐姐(逃..[.Java中的逃逸分析](https://www.cnblogs.com/javastack/p/11023044.html))。**

**<font color='red'>按照技术模块：Java热点技术、多线程、微服务、JVM、Redis、消息队列、SQL相关的面试题。不要走开，稍后更精彩！</font>**

------

**1、面向对象的特点有哪些?**

> **抽象、继承、封装、多态。**

[**2、接口和抽象类有什么联系和区别?**](https://blog.csdn.net/qq_26465035/article/details/103161542)

[**3、重载和重写有什么区别?**](https://blog.csdn.net/houwanle/article/details/82107161)

[**4、java有哪些基本数据类型?**](https://blog.csdn.net/qq_26465035/article/details/103161881)

**5、数组有没有length()方法?String有没有length()方法?**

> **数组没有length()方法，它有length属性。**
>
> **String有length()方法。**
>
> **集合求长度用size()方法。**

[**6、Java支持的数据类型有哪些?什么是自动拆装箱?**](https://blog.csdn.net/qq_26465035/article/details/103161881)

[**7、int 和 Integer 有什么区别?**](https://blog.csdn.net/cf082430/article/details/90740291)

[**8、Java类的实例化顺序?**](https://www.cnblogs.com/linliquan/p/11254138.html)

> **父类静态成员和静态代码块 -> 子类静态成员和静态代码块 -> 父类非静态成员和非静态代码块 -> 父类构造方法 -> 子类非静态成员和非静态代码块 -> 子类构造方法**

[**9、什么是值传递和引用传递?**](https://blog.csdn.net/qq_40574571/article/details/90765349)

[**10、String能被继承吗?为什么?**](https://blog.csdn.net/qq_26465035/article/details/103162903)

**11、String和StringBuilder、StringBuffer的区别?**

> - StringBuilder：适用于单线程下在字符缓冲区进行大量操作的情况**（是线程不安全的）**
> - StringBuffer：适用多线程下在字符缓冲区进行大量操作的情况（一般很少）**（是线程安全的）**
> - 首先说运行速度，或者说是执行速度，在这方面运行速度快慢为：**StringBuilder > StringBuffer > String**

[**12、Java集合框架的基础接口有哪些?**](http://gzhimages.paidanzi.com/Img/91d0b730-3d88-4330-811f-0d8870e69f82/1574234990453.png)

[**13、Java集合框架是什么?说出一些集合框架的优点?**](https://blog.csdn.net/qq_26465035/article/details/103164167)

[**14、HashMap 与HashTable有什么区别?**](https://blog.csdn.net/qq_26465035/article/details/103164167)

[**15、ArrayList 和 LinkedList 有什么区别?**](https://blog.csdn.net/qq_26465035/article/details/103164167)

[**16、简单介绍Java异常框架?Error与Exception有什么区别?**](https://blog.csdn.net/iblade/article/details/78196016)

[**17、java中的throw 和 throws关键字有什么区别?**](https://blog.csdn.net/qq_35370263/article/details/79539110)

[**18、列举几个你了解的几个常见的运行时异常?**](https://blog.csdn.net/iblade/article/details/78196016)

[**19、final, finally, finalize有什么区别?**](https://www.cnblogs.com/ktao/p/8586966.html)

[**20、描述Java内存模型?**](https://blog.csdn.net/wangnanwlw/article/details/86466782)

[**21、java中垃圾收集的方法有哪些?**](https://www.cnblogs.com/wangqingming/p/9766803.html)

[**22、如何判断一个对象是否存活?(或者GC对象的判定方法)?**](https://www.cnblogs.com/wangqingming/p/9766803.html)

[**23、Java GC是在什么时候，对什么东西，做了什么事情?**](https://www.cnblogs.com/wangqingming/p/9766803.html)

[**24、什么是类加载器双亲委派模型机制?**](https://blog.csdn.net/zhangjingao/article/details/86680206)

[**25、类加载器有哪些?**](https://blog.csdn.net/zhangjingao/article/details/86680206)

[**26、描述类加载器工作机制?**](https://blog.csdn.net/zhangjingao/article/details/86680206)

[**27、分别写出堆内存溢出与栈内存溢出的程序?**](https://www.cnblogs.com/wylwyl/p/10500607.html)

[**28、Java 8 内存模型进行了哪些改进?**](https://www.cnblogs.com/aflyun/p/10575740.html)

[**29、简述java内存分配与回收策率以及Minor GC和Major GC?**](https://www.liangzl.com/get-article-detail-145652.html)

[**30、JVM，JDK和JRE有什么区别与联系?**](https://blog.csdn.net/ancientear/article/details/79483592)

[**31、Java线程同步的方式有哪些?**](https://www.cnblogs.com/xiaoxi/p/7679470.html)

[**32、解释一下锁的一些基本概念：可重入锁、可中断锁、公平锁、读写锁?**](http://www.k6k4.com/simple_question/qshow/aaqfmycjp1538295839067)

**33、synchronized什么情况下会释放锁?**

> 1. 获取锁的线程执行完了该代码块，然后线程释放对锁的占有；
> 2. 线程执行发生异常，此时JVM会让线程自动释放锁。
> 3. 调用wait方法,在等待的时候立即释放锁,方便其他的线程使用锁.

[**34、synchronized和lock有什么区别?**](http://www.k6k4.com/simple_question/qshow/aaqfoowbd1538292817708)

[**35、使用过哪些数据库连接池，分别有什么优点和缺点?**](https://www.cnblogs.com/xdp-gacl/p/4002804.html)

**36、Java CAS（Compare And Swap） 无锁算法?**

> **CAS（Compare And Swap）** 无锁算法： CAS是乐观锁技术，当多个线程尝试使用CAS同时更新同一个变量时，只有其中一个线程能更新变量的值，而其它线程都失败，失败的线程并不会被挂起，而是被告知这次竞争中失败，并可以再次尝试。CAS有3个操作数，内存值V，旧的预期值A，要修改的新值B。当且仅当预期值A和内存值V相同时，将内存值V修改为B，否则什么都不做。

**37、线程池的作用有哪些?**

> 线程池的作用： 在程序启动的时候就创建若干线程来响应处理，它们被称为线程池，里面的线程叫工作线程
>
> 1. 降低资源消耗。通过重复利用已创建的线程降低线程创建和销毁造成的消耗。
> 2. 提高响应速度。当任务到达时，任务可以不需要等到线程创建就能立即执行。
> 3. 提高线程的可管理性。
>
> 常用线程池：ExecutorService 是主要的实现类，其中常用的有
>
> - Executors.newSingleThreadPool(),
> - newFixedThreadPool(),
> - newCachedTheadPool(),
> - newScheduledThreadPool()。

[**38、反射创建类实例的三种方式?**](http://www.k6k4.com/simple_question/qshow/aaqqcirdi1537970656160)

[**39、反射机制有哪些优点和缺点?**](http://www.k6k4.com/simple_question/qshow/aaqgktmbe1537970213935)

**40、哪些项目中用到了Java反射机制?**

> ```
> jdbc中有一行代码：Class.forName('com.MySQL.jdbc.Driver.class').newInstance();
> 很多框架都用到反射机制，hibernate，struts都是用反射机制实现的。
> ```
>
> ![点击并拖拽以移动](data:image/gif;base64,R0lGODlhAQABAPABAP///wAAACH5BAEKAAAALAAAAAABAAEAAAICRAEAOw==)

[**41、Java 反射机制的作用?**](https://www.cnblogs.com/liyuanhong/articles/10219124.html)

[**42、你了解哪些设计模式，列举几个?jdk中用到了哪些设计模式?**](https://msd.misuland.com/pd/3255817997595447420)

[**43、单例模式用java有哪几种实现方式?**](https://blog.csdn.net/sofeware333/article/details/92831408)

[**44、Java元注解有哪些，都有什么作用?**](https://blog.csdn.net/melody_susan/article/details/48050015)

[**45、jdk自带了哪些注解，有什么作用?**](http://www.k6k4.com/simple_question/qshow/aaqosfbjz1537972831150)

[**46、Java8有哪些新特性?**](https://blog.csdn.net/qq_26465035/article/details/82856292)

**47、简单介绍原生jdbc执行sql过程?**

> 1. class.forName()加载数据驱动
> 2. DriverManager.getConnection()获取数据库连接对象。
> 3. 根据SQL或sql会话对象，有两种方式Statement、PreparedStatement。
> 4. 执行sql处理结果集，如果有参数就设置参数。
> 5. 关闭结果集，关闭会话，关闭资源。

**48、char 型变量中能不能存贮一个中文汉字，为什么?**

> char类型可以存储一个中文汉字，因为Java中使用的编码是Unicode，一个char类型占2个字节（16比特），所以放一个中文是没问题的。

[**49、两个对象值相同(x.equals(y) == true)，但却可有不同的hash code，这句话对不对?**](https://www.cnblogs.com/jxxblogs/p/10827664.html)

**50、构造器（constructor）是否可被重写（override）?**

> “Constructor(构造器)不能被继承,所以不能被override(重写),但是可以被overloading(重载)。

[**51、什么是线程安全？**](https://www.cnblogs.com/molao-doing/articles/8908239.html)

[**52、什么是死锁？**](https://blog.csdn.net/baidu_38634017/article/details/88395287)

[**53、synchronized的实现原理是什么？**](https://blog.csdn.net/qq_41701956/article/details/83660927)

[**54、有了synchronized，还需要volatile做什么事？**](https://blog.csdn.net/xlgen157387/article/details/78327228)

[**55、synchronized的锁优化是怎么处理的？**](https://blog.csdn.net/xlgen157387/article/details/78327228)

> **（强烈推荐两本书《[java并发编程的艺术](https://search.jd.com/Search?keyword=java%E5%B9%B6%E5%8F%91%E7%BC%96%E7%A8%8B%E7%9A%84%E8%89%BA%E6%9C%AF&enc=utf-8&wq=java%E5%B9%B6%E5%8F%91%E7%BC%96%E7%A8%8B%E7%9A%84%E8%89%BA%E6%9C%AF&pvid=5639acc43ddb4e53aad30eb0cdfb644c)》、《[深入理解Java虚拟机](https://search.jd.com/Search?keyword=%E6%B7%B1%E5%85%A5%E7%90%86%E8%A7%A3Java%E8%99%9A%E6%8B%9F%E6%9C%BA&enc=utf-8&wq=%E6%B7%B1%E5%85%A5%E7%90%86%E8%A7%A3Java%E8%99%9A%E6%8B%9F%E6%9C%BA&pvid=fa6b3db2e2144a69944178f3fa4ff645)》）**
>
>   Synchronized和Volatile的区别：
>
> ​    1、Volatile 仅能使用在变量级别；
>     Synchronized则可以使用在变量、方法、和同步代码块等类级别的。
>     2、Volatile仅能实现变量的修改可见性和有序性，并不能保证原子性(复合操作的原子性)；
>     Synchronized则可以保证变量的可见性、有序性、原子性。
>     3、Volatile不会造成线程的阻塞；
>     Synchronized可能会造成线程的阻塞。
>     4、Volatile标记的变量不会被编译器优化（因为这是由cpu指令完成）；
>     Synchronized标记的变量可以被编译器优化（JAVA1.6后性能优化很多）。

[**56、JMM是什么？**](https://www.cnblogs.com/lfs2640666960/p/11019798.html)

[**57、Java并发包都有哪些？**](https://segmentfault.com/a/1190000015558984)

[**58、什么是fail-fast？**](https://www.cnblogs.com/songanwei/p/9387745.html)

[**59、什么是fail-safe？**](https://www.cnblogs.com/songanwei/p/9387745.html)

[**60、什么是CopyOnWrite？**](https://blog.csdn.net/xixingzhe2/article/details/82826188)

[**61、什么是AQS呢？**](https://www.jianshu.com/p/0f876ead2846)

[**62、什么是CAS呢？**](https://developer.aliyun.com/ask/257382)

[**63、乐观锁是怎样的？**](https://www.jianshu.com/p/01d550967663)

[**64、乐观锁悲观锁区别是什么？**](https://www.jianshu.com/p/01d550967663)

[**65、数据库如何实现悲观锁和乐观锁？**](https://www.iteye.com/blog/chenzhou123520-1860954)

[**66、数据库锁和隔离级别有什么关系？**](https://www.cnblogs.com/zsychanpin/p/7395635.html)

[**67、数据库锁和索引有什么关系？**](https://www.cnblogs.com/charlesblc/p/6288254.html)

[**68、什么是聚簇索引？**](https://www.cnblogs.com/charlesblc/p/6288254.html)

[**69、什么是非聚簇索引？**](https://www.cnblogs.com/charlesblc/p/6288254.html)

[**70、索引最左前缀是什么？**](https://www.cnblogs.com/kkbill/p/11354685.html)

[**71、什么是B+树索引？（有点长，值得一看）**](https://www.cnblogs.com/aspirant/p/9214485.html)

[**72、什么是联合索引？**](https://www.cnblogs.com/kkbill/p/11354685.html)

[**73、什么是回表？**](https://developer.aliyun.com/ask/257394)

[**74、分布式锁有了解吗？**](https://www.jianshu.com/p/31d3de863ff7)

[**75、Redis怎么实现分布式锁？**](https://blog.csdn.net/kongmin_123/article/details/82080962)

**76、为什么要用Redis?**

> 因为传统的关系型数据库如Mysql已经不能适用所有的场景了，比如秒杀的库存扣减，APP首页的访问流量高峰等等，都对数据库提出了更高的要求，所以引入了缓存中间件，目前市面上比较常用的缓存中间件有Redis 和 Memcached 不过中和考虑了他们的优缺点，最后选择了Redis。

[**77、Redis和memcache区别是什么？**](https://www.cnblogs.com/djj123/p/10996636.html)

[**78、Zookeeper怎么实现分布式锁？**](https://www.cnblogs.com/ysw-go/p/11444993.html)

[**79、什么是Zookeeper？（漫画版）**](https://www.jianshu.com/p/e2c3caa80e8e)

[**80、什么是CAP？**](https://blog.csdn.net/jerry010101/article/details/90025398)

[**81、什么是BASE？和CAP什么区别？**](https://blog.csdn.net/jerry010101/article/details/90025398)

[**82、CAP怎么推导？如何取舍？**](https://blog.csdn.net/jerry010101/article/details/90025398)

[**83、分布式系统怎么保证数据一致性？**]()

[**84、什么是分布式事务？分布式事务方案？**](https://www.cnblogs.com/rainydayfmb/p/8416762.html)

[**85、线程安全的单例？**](https://www.cnblogs.com/x_wukong/p/3962315.html)

[**86、不用synchronized和lock能实现线程安全的单例吗？**](http://ddrv.cn/a/163815)

[**87、什么是Paxos算法？**](https://www.jianshu.com/p/369d528f0729)

[**88、ArrayList和LinkedList和Vector的区别·**](https://blog.csdn.net/virtiL33/article/details/89378232)

[**89、谈一下计模式遵循的面向对象设计原则！**](https://mp.weixin.qq.com/s?__biz=MzAxODcyNjEzNQ==&mid=2247488408&idx=3&sn=908cbbefbb5bfdf1fc30e114b9efb1a9&chksm=9bd0be00aca73716439144a7280079e1d516d3ce6b328363333f4b418ba4e0e7cd216d5f1e45&scene=21#wechat_redirect)

[**90、Arrays.asList获得的List使用时需要注意什么**](https://www.jianshu.com/p/0817239db610)

**91、List和原始类型List之间的区别?**

> 在编译时编译器不会对原始类型进行类型安全检查，却会对带参数的类型进行检查。

[**92、List<?>和List<T>之间的区别是什么?](https://www.cnblogs.com/stitchZsx/p/9883410.html)**

[**93、synchronized是如何实现的？**](https://blog.csdn.net/javazejian/article/details/72828483)

[**94、BIO、NIO和AIO的区别、三种IO的用法与原理**](https://blog.csdn.net/u010541670/article/details/91890649)

[**95、ConcurrentSkipListMap**](https://www.cnblogs.com/skywang12345/p/3498556.html)

[**96、String.valueOf和Integer.toString的区别**](https://www.jianshu.com/p/a22b95e48a15)

[**97、Integer的缓存机制**](https://www.cnblogs.com/rouqinglangzi/p/8848607.html)

[**98、Set如何保证元素不重复?**](https://www.cnblogs.com/mianduijifengba/p/10461865.html)

[**99、Java中如何保证线程安全？**](https://blog.csdn.net/qq_26545305/article/details/79516610)

[**100、你使用过JVM相关的参数，列举几个**](https://www.liangzl.com/get-article-detail-124122.html)

------

创作不易，各位的支持和认可，就是我创作的最大动力，

【转载请联系本人】 如有问题，请联系我。欢迎斧正！不胜感激 ！

**求点赞👍** **求关注❤️** **求分享👥 求留言📪**