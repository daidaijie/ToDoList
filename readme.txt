J2SE基础

1. 九种基本数据类型的大小，以及他们的封装类。

2. Switch能否用string做参数？

3. equals与==的区别。

4. Object有哪些公用方法？

5. Java的四种引用，强弱软虚，用到的场景。

6. Hashcode的作用。

7. ArrayList、LinkedList、Vector的区别。

8. String、StringBuffer与StringBuilder的区别。

9. Map、Set、List、Queue、Stack的特点与用法。

10. HashMap和HashTable的区别。

11. HashMap和ConcurrentHashMap的区别，HashMap的底层源码。

12. TreeMap、HashMap、LindedHashMap的区别。

13. Collection包结构，与Collections的区别。

14. try catch finally，try里有return，finally还执行么？

15. Excption与Error包结构。OOM你遇到过哪些情况，SOF你遇到过哪些情况。

16. Java面向对象的三个特征与含义。

17. Override和Overload的含义去区别。

18. Interface与abstract类的区别。

19. Static class 与non static class的区别。

20. java多态的实现原理。

21. 实现多线程的两种方法：Thread与Runable。

22. 线程同步的方法：sychronized、lock、reentrantLock等。

23. 锁的等级：方法锁、对象锁、类锁。

24. 写出生产者消费者模式。

25. ThreadLocal的设计理念与作用。

26. ThreadPool用法与优势。

27. Concurrent包里的其他东西：ArrayBlockingQueue、CountDownLatch等等。

28. wait()和sleep()的区别。

29. foreach与正常for循环效率对比。

30. Java IO与NIO。

31. 反射的作用于原理。

32. 泛型常用特点，List<String>能否转为List<Object>。

33. 解析XML的几种方式的原理与特点：DOM、SAX、PULL。

34. Java与C++对比。

35. Java1.7与1.8新特性。

36. 设计模式：单例、工厂、适配器、责任链、观察者等等。

37. JNI的使用。

JVM

1. 内存模型以及分区，需要详细到每个区放什么。

2. 堆里面的分区：Eden，survival from to，老年代，各自的特点。

3. 对象创建方法，对象的内存分配，对象的访问定位。

4. GC的两种判定方法：引用计数与引用链。

5. GC的三种收集方法：标记清除、标记整理、复制算法的原理与特点，分别用在什么地方，如果让你优化收集方法，有什么思路？

6. GC收集器有哪些？CMS收集器与G1收集器的特点。

7. Minor GC与Full GC分别在什么时候发生？

8. 几种常用的内存调试工具：jmap、jstack、jconsole。

9. 类加载的五个过程：加载、验证、准备、解析、初始化。

10. 双亲委派模型：Bootstrap ClassLoader、Extension ClassLoader、ApplicationClassLoader。

11. 分派：静态分派与动态分派。

JVM过去过来就问了这么些问题，没怎么变，内存模型和GC算法这块问得比较多，可以在网上多找几篇博客来看看。

推荐书籍：《深入理解java虚拟机》

操作系统

1. 进程和线程的区别。

2. 死锁的必要条件，怎么处理死锁。

3. Window内存管理方式：段存储，页存储，段页存储。

4. 进程的几种状态。

5. IPC几种通信方式。

6. 什么是虚拟内存。

7. 虚拟地址、逻辑地址、线性地址、物理地址的区别。
 

TCP/IP

1. OSI与TCP/IP各层的结构与功能，都有哪些协议。

2. TCP与UDP的区别。

3. TCP报文结构。

4. TCP的三次握手与四次挥手过程，各个状态名称与含义，TIMEWAIT的作用。

5. TCP拥塞控制。

6. TCP滑动窗口与回退N针协议。

7. Http的报文结构。

8. Http的状态码含义。

9. Http request的几种类型。

10. Http1.1和Http1.0的区别

11. Http怎么处理长连接。

12. Cookie与Session的作用于原理。

13. 电脑上访问一个网页，整个过程是怎么样的：DNS、HTTP、TCP、OSPF、IP、ARP。

14. Ping的整个过程。ICMP报文是什么。

15. C/S模式下使用socket通信，几个关键函数。

16. IP地址分类。

17. 路由器与交换机区别。

网络其实大体分为两块，一个TCP协议，一个HTTP协议，只要把这两块以及相关协议搞清楚，一般问题不大。

推荐书籍：《TCP/IP协议族》 


数据结构与算法

1. 链表与数组。

2. 队列和栈，出栈与入栈。

3. 链表的删除、插入、反向。

4. 字符串操作。

5. Hash表的hash函数，冲突解决方法有哪些。

6. 各种排序：冒泡、选择、插入、希尔、归并、快排、堆排、桶排、基数的原理、平均时间复杂度、最坏时间复杂度、空间复杂度、是否稳定。

7. 快排的partition函数与归并的Merge函数。

8. 对冒泡与快排的改进。

9. 二分查找，与变种二分查找。

10. 二叉树、B+树、AVL树、红黑树、哈夫曼树。

11. 二叉树的前中后续遍历：递归与非递归写法，层序遍历算法。

12. 图的BFS与DFS算法，最小生成树prim算法与最短路径Dijkstra算法。

13. KMP算法。

14. 排列组合问题。

15. 动态规划、贪心算法、分治算法。（一般不会问到）

16. 大数据处理：类似10亿条数据找出最大的1000个数.........等等

Android

1. Activity与Fragment的生命周期。

2. Acitivty的四中启动模式与特点。

3. Activity缓存方法。

4. Service的生命周期，两种启动方法，有什么区别。

5. 怎么保证service不被杀死。

6. 广播的两种注册方法，有什么区别。

7. Intent的使用方法，可以传递哪些数据类型。

8. ContentProvider使用方法。

9. Thread、AsycTask、IntentService的使用场景与特点。

10. 五种布局： FrameLayout 、 LinearLayout 、 AbsoluteLayout 、 RelativeLayout 、TableLayout 各自特点及绘制效率对比。

11. Android的数据存储形式。

12. Sqlite的基本操作。

13. Android中的MVC模式。

14. Merge、ViewStub的作用。

15. Json有什么优劣势。

16. 动画有哪两类，各有什么特点？

17. Handler、Loop消息队列模型，各部分的作用。

18. 怎样退出终止App。

19. Asset目录与res目录的区别。

20. Android怎么加速启动Activity。

21. Android内存优化方法：ListView优化，及时关闭资源，图片缓存等等。

22. Android中弱引用与软引用的应用场景。

23. Bitmap的四中属性，与每种属性队形的大小。

24. View与View Group分类。自定义View过程：onMeasure()、onLayout()、onDraw()。

25. Touch事件分发机制。

26. Android长连接，怎么处理心跳机制。

27. Zygote的启动过程。

28. Android IPC:Binder原理。

29. 你用过什么框架，是否看过源码，是否知道底层原理。

30. Android5.0、6.0新特性。
