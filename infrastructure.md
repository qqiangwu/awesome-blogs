# Container
+ [Docker in the Real World at Yelp](http://engineeringblog.yelp.com/2015/08/docker-in-the-real-world-at-yelp.html)
+ [Tutorial by serversforhackers](https://serversforhackers.com/getting-started-with-docker/)
+ [The Docker Book](http://www.dockerbook.com/)
+ [Docker 从入门到实践](http://www.douban.com/group/topic/70402682/)
+ [精简Docker镜像](http://www.alauda.cn/2015/07/10/docker-image-as-small-as-possible/)
+ [Creating a Distributed System in 300 Lines With Mesos, Docker, and Go](https://dzone.com/articles/creating-a-distributed-system-in-300-lines-with-me)
+ [Docker基础技术](http://coolshell.cn/?s=docker%E5%9F%BA%E7%A1%80%E6%8A%80%E6%9C%AF)
+ [10 things to avoid in docker containers](http://developerblog.redhat.com/2016/02/24/10-things-to-avoid-in-docker-containers/)
+ [Measuring Percona Server Docker CPU/network overhead](https://www.percona.com/blog/2016/02/05/measuring-docker-cpu-network-overhead/)
+ [Measuring Docker IO overhead](https://www.percona.com/blog/2016/02/11/measuring-docker-io-overhead/)
+ [An Updated Performance Comparison of Virtual Machines and Linux Containers](http://domino.research.ibm.com/library/cyberdig.nsf/papers/0929052195DD819C85257D2300681E7B/$File/rc25482.pdf)

# CaaS
+ [Swarm v. Fleet v. Kubernetes v. Mesos](http://radar.oreilly.com/2015/10/swarm-v-fleet-v-kubernetes-v-mesos.html)
+ [浅谈Borg/YARN/Mesos/Torca/Corona一类系统](http://dongxicheng.org/mapreduce-nextgen/borg-yarn-mesos-torca-corona/)
+ [Torca：Typhoon上的分布式集群调度系统](http://djt.qq.com/article/view/329)
+ [Borg和Kubernetes有什么不同以及未来的云需要什么？](http://dockone.io/article/784?hmsr=toutiao.io&utm_medium=toutiao.io&utm_source=toutiao.io)

# PaaS
+ [为什么我们抛弃ECS而选择了Kubernetes](https://www.cppfans.org/2078.html)
+ [Inside Yelp's SOA Infrastructure](http://www.infoq.com/presentations/yelp-infrastructure): Every team needs PaaS.
+ [The PaaSTA Contract](http://paasta.readthedocs.org/en/latest/about/contract.html)
+ [PaaSTA Principles](http://paasta.readthedocs.org/en/latest/about/paasta_principles.html)
+ [Return of the Borg: How Twitter Rebuilt Google’s Secret Weapon](http://www.wired.com/2013/03/google-borg-twitter-mesos/)
+ [DINP](http://dinp.qiniudn.com/dinp.final.pdf): 一个极简的PaaS实现
+ [IaaS之后](http://www.jianshu.com/p/6f6e48717bc4)

# Service Discovery
+ [Open-Source Service Discovery](http://jasonwilder.com/blog/2014/02/04/service-discovery-in-the-cloud/)
+ [Cluster: Provision & Discovery with Ansible & Consul](https://medium.com/@name_alari/cluster-provision-discovery-with-ansible-consul-377b473c934c)
+ [从理论到实践，全方位认识DNS（理论篇）](http://selfboot.cn/2015/11/05/dns_theory/)
+ [从理论到实践，全方位认识DNS（实践篇）](http://selfboot.cn/2015/11/14/dns_practice/)
+ [Docker Service Discovery Using Etcd and Haproxy](http://jasonwilder.com/blog/2014/07/15/docker-service-discovery/)

# Beauty of architecture
+ [bfs:支撑Bilibili的小文件存储系统](https://mp.weixin.qq.com/s?__biz=MzAwMDU1MTE1OQ==&mid=406016886&idx=1&sn=f5aa286373fb981c9de904568fe7ddb2)

# Paper
+ [Borg](http://research.google.com/pubs/pub43438.html):
    + A datacenter is a single computer! This is what Google and Twitter do!  
    + We can pack multiple chips into a single computer, we can do the same thing in a datacenter.
+ [Mesos](http://mesos.apache.org/)
    + It’s a Data Center. But It Looks Like a Chip
    + Traditionally, the computer processor — the brain at the center of a machine — ran one task at a time. But a multi-core processor lets you run many tasks in parallel.
    + “What we found is that applications were smart about scheduling their computations across these computing resources, but they were also greedy. They would ignore other applications that might be running and just grab everything for themselves,” Hindman says. “So we built a system that would only give an application access to a certain number of cores, and give others to another application. And those allocations might change over time.”
    + Sixty-four cores or 128 cores on a single chip looks a lot like 64 machines or 128 machines in a data center.
    + We wanted people to be able to program for the data center just like they program for their laptop.
    + VMs are not good abstraction for application developers.
