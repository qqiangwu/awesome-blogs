# Coordination
+ [Zookeeper: 分布式过程协同技术详解](http://www.dengshenyu.com/%E5%88%86%E5%B8%83%E5%BC%8F%E7%B3%BB%E7%BB%9F/2017/11/01/zookeeper.html)：ZK概览，入门值得一看，中间选举与原子广播讨论得不太清楚。

# Distributed System
+ [**Introduction to Distributed System Design**](http://www.hpcs.cs.tsukuba.ac.jp/~tatebe/lecture/h23/dsys/dsd-tutorial.html)
+ [Understanding CAP](http://henryr.github.io/cap-faq/)
+ [Building Globally Distributed, Mission Critical Applications](http://highscalability.com/blog/2015/8/31/building-globally-distributed-mission-critical-applications.html)
+ [CAP Twelve Years Later: How the "Rules" Have Changed](http://www.infoq.com/articles/cap-twelve-years-later-how-the-rules-have-changed)
+ [The Consistency Alphabet Soup](http://hackingdistributed.com/2013/03/23/consistency-alphabet-soup/): What does C in CAP and ACID mean?
+ [CAP理论的质疑](http://blog.csdn.net/chen77716/article/details/30635543)

# Paper
+ Consistency and availability
    + [Coda File System](https://www.cs.cmu.edu/~satya/docdir/satya-ieeetc-coda-1990.pdf)
        + How to achieve HA at the expense of consistency
        + How disconnected operations work
    + [Bayou](http://dl.acm.org/citation.cfm?id=224070)
+ Replication
    + [The Dangers of Replication and a Solution](http://dl.acm.org/citation.cfm?id=233330)

# Storage
+ [The Design and Implementation of a Log-Structured File System](https://www.cs.berkeley.edu/~brewer/cs262/LFS.pdf)
+ [Percolator导读](http://www.importnew.com/2896.html)：TiKV的灵感来源之一

# HBase
+ [HBase高性能随机查询之道 – HFile原理解析](http://www.nosqlnotes.com/technotes/hbase/hfile/): 读代码之前，一定要先知道，我需要解决这个问题，应该写什么样的代码；而不是，这段代码在解决什么问题
