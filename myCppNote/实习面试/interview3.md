## 元象 游戏后台实习生 一面
50分钟
1. 自我介绍
2. 介绍一下数据中心项目
    - 熟悉tcp吗，详细介绍一下，我介绍了TCP三次握手和四次挥手各种报文和状态，还有某些情况下是采用三次挥手断开连接
    - epoll原理，比select, poll快的原因是什么
    - 守护进程怎么实现？心跳机制，守护进程被杀掉怎么办？
    - 守护线程又是怎么做的？（我项目中线程池，使用了守护线程去监控其他线程）
    - 死锁是什么？怎么避免死锁？
    - 觉得守护进程，守护线程这块实现的有点问题，给了一些建议，太紧张了没听懂
    - 之后问了很多linux进程相关的（这块聊了很多记不清了，他后面建议我去APUE不要看网上博客的只言片语）
    - 项目中使用了共享内存，问：实现共享内存的方式有哪些
    - 虚拟内存, 操作系统怎么分配虚拟内存
    - 内存满了，会发生什么？
    - 在 4GB 物理内存的机器上，申请 8G 内存会怎么样？（类似于这个，具体记不清了，不太会回答
    - bash连上了来以后，父进程？（没搞懂问题
    - 为什么关掉终端，就断开了，原因
    - 进程，线程区别，问了我两遍，可能觉得第一遍答的不好，问了线程自己拥有的资源
    - 进程之间的通信方式
    - 熟悉数据库吗 （我说我不怎么熟悉这块）
    - 创建数据库的sql语句
    - sql关键字
4. 介绍一下你的go-redis项目
    - redis是单线程还是多线程
    - redis为什么要采用单线程
5. 熟悉STL吗
    - map, set底层结构——红黑树，说一下红黑树具体实现（没看这块，然后他问你不是计算机系的么，我说数据结构课学过忘了）
    - 那你说说平衡二叉树，和普通二叉树区别
6. 快速排序+单元测试
    - 以前没接触过c++的单元测试，下来得看看了，快排还是好写

> 面试完一小时左右通知参加笔试
