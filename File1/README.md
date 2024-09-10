面试基本信息
面试岗位：运维工程师(容器与ES方向)、运维开发工程师、SRE工程师
工作经验：5年
薪资范围：年薪45万左右，base北京
面试时间：7月初-8月中旬
主要公司：

互联网公司：字节、京东、百度、网易、蚂蚁金服、小米、滴滴、去哪儿、猎豹移动、商汤、旷视、智谱华章、马蜂窝、竞技世界
国企子公司：电信、联通、建行、中石化
面试题汇总
其中☆表示多次出现过的高频面试题，已经按分类整理。

Linux
grep sed awk cut组合使用☆
http错误码和原因
长连接、短连接、WebSocket区别和使用场景
nginx性能优化有哪些方式☆
lvs、nginx、haproxy区别和使用场景☆
僵尸进程是什么
进程、线程、协程区别☆
什么是nginx的异步非阻塞
linux网络丢包怎么排查☆
常用的性能分析诊断命令☆
什么是进程中断
什么是软中断、硬中断
什么是不可中断进程
什么是栈内存和堆内存
top 命令里面可以看到进程哪些状态☆
Linux 系统中/proc是做什么的
load和cpu使用率区别
MAC地址IP地址如何转换
常见的raid有哪些，使用场景是什么
lvm怎么划分
jvm内存如何查看
如何管理和优化内核参数
什么是进程最大数、最大线程数、进程打开的文件数，怎么调整☆
du和df统计不一致原因☆
buffers与cached的区别☆
lsof命令使用场景
Linux中的进程间通信的方式及其使用场景
Linux中的进程优先级与设置方法
什么是内存分页和分段
如何创建和管理自定义systemd服务
Linux内核模块的加载与卸载过程
ansible roles使用场景，现在有多台机器需要批量加入k8s集群，怎么实现☆



Kubernetes
谈谈你对k8s的理解☆
k8s集群架构是什么☆
简述Pod创建过程☆
简述删除一个Pod流程
不同node上的Pod之间的通信过程☆
pod创建Pending状态的原因☆
deployment和statefulset区别☆
kube-proxy有什么作用☆
kube-proxy怎么修改ipvs规则
ipvs为什么比iptables效率高
pod之间访问不通怎么排查☆
k8s中Network Policy的实现原理
探针有哪些？探测方法有哪些？
pod健康检查失败可能的原因和排查思路
k8s的Service是什么☆
metrics-server采集指标数据链路
k8s服务发现有哪些方式？
pod几种常用状态
Pod 生命周期的钩子函数
Calico和flannel区别☆
calico网络原理、组网方式
Network Policy使用场景
kubectl exec 实现的原理
cgroup中限制CPU的方式有哪些
kubeconfig存放内容
pod DNS解析流程☆
traefik对比nginx ingress优点
Harbor有哪些组件
Harbor高可用怎么实现
ETCD调优
假设k8s集群规模上千，需要注意的问题有哪些？
节点NotReady可能的原因？会导致哪些问题？☆
service和endpoints是如何关联的？
ReplicaSet、Deployment功能是怎么实现的？
scheduler调度流程
HPA怎么实现的☆
request limit底层是怎么限制的☆
helm工作原理是什么？
helm chart rollback实现过程是什么？
velero备份与恢复流程是什么
docker网络模式
docker和container区别☆
如何减⼩dockerfile⽣成镜像体积？
k8s日志采集方案
Pause容器的用途☆
k8s证书过期怎么更新
K8S QoS等级☆
k8s节点维护注意事项
Headless Service和ClusterIP区别☆
Linux容器技术的基础原理
Kubernetes Pod的常见调度方式
kubernetes Ingress原理☆
Kubernetes各模块如何与API Server通信
kubelet监控worker节点如何实现
容器时区不一致如何解决？


Prometheus
Prometheus的工作流程
Metric的几种类型？分别是什么？☆
Prometheus有哪几种服务发现☆
Prometheus常用函数
thanos架构☆
thanos与VictoriaMetrics对比
thanos sidecar和receive区别☆
thanos rule组件和prometheus区别
Prometheus告警从触发到收到通知延迟在哪
告警抑制怎么做☆
告警架构高可用怎么做☆
Pod指标WSS和RSS区别☆
监控四个黄金指标
在大规模环境下，如何优化Prometheus性能
如何实现告警的自动化响应☆
Prometheus数据压缩和持久化实现原理
kubectl top输出与Linux free命令不一致原因☆
用到了哪些exporter，功能是什么
是否自己开发过exporter☆
target down的情况如何进行故障排除？
Exporter 停止工作，如何监控？
Prometheus的拉取模式与zabbix推送模式有何区别？各有什么优缺点？
Prometheus operator怎么添加targets和告警规则
k8s集群外exporter怎么使用Prometheus监控


ELK
ES写入索引原理
ES存储原理☆
搜索文档（单个文档）流程
ES全文搜索流程
ES写入性能优化☆
ES查询性能优化☆
ES JVM使用过高如何排查
ES的Fleet server架构☆
Fleet server架构和elk架构使用场景☆
ClickHouse、loki、ES的优劣对比
ES架构☆
业务类ES和日志类ES架构设计区别
ES Full Gc怎么排查处理
全文检索和精确搜索区别☆
集群变黄状态时，你会如何进行故障排除☆
如何在集群中添加或移除节点
ES Young GC和old GC有什么区别
怎么提高查询结果评分
ES的version是解决什么问题的
查询数据慢如何排查优化☆
是否对ES JVM做过调优
ES是否数据越多需要内存越大
ES集群数据备份如何实现☆
ES聚合有哪些方式
Filebeat如何保证连续发送日志
Logstash如何提升性能☆
如何提高Filebeat性能
Filebeat如何收集容器日志


Devops
gitlab runner做了哪些优化
怎么实现多集群逐个发布
蓝绿部署、灰度发布、金丝雀发布区别☆
什么是测试左移？（Shift-Left testing）
什么是GitOps
GitOps和DevOps区别☆
gitlab仓库代码如何备份
Jenkins 构建失败时，你如何排查问题☆
Jenkins用户权限管理怎么做的
Jenkins pipeline有几种模式，区别是什么？
如何配置 Jenkins 实现高可用性
Jenkins Master和Slave是如何协同工作的
如何设计和实现一个 Jenkins Pipeline，以支持多阶段构建、测试和部署流程
Argo Rollouts蓝绿部署和金丝雀发布原理☆
Argo CD中的 Application CRD是什么
Argo CD中自动同步（Auto-sync）和手动同步的区别与应用场景
Argo CD检测到应用状态异常，你会如何进行故障排除
Argo CD如何配置自定义的健康检查规则
Argo CD检测到配置与实际状态不一致时如何处理这些差异
CICD流程如何监控?
平时开发项目时git开发功能分支标准流程是什么?
git分支冲突怎么解决?


Python VUE
Python中的 GIL是什么？它如何影响多线程？☆
python装饰器☆
is 和 == 的区别☆
Python中的生成器和迭代器有什么区别
Python的垃圾回收机制是如何工作的
Python上下文管理器的概念及其用途。
dict的内部实现原理
python浅拷贝和深拷贝☆
lambda匿名函数使用场景举例
常见设计模式
python单例模式
面向对象中__new__和__init__区别☆
Python中的列表和字典是如何实现的？它们在时间复杂度上有何差异？
Python中的多线程模块的区别☆
asyncio编写异步代码
django请求的生命周期☆
JWT认证
什么是wsgi，uwsgi
Django安全防护
drf继承过哪些视图类，他们之间的区别☆
谈谈django flask fastapi各自的优劣和适用场景。
python定时任务解决方案☆
在 Celery 中，如何确保任务的可靠性和持久性
如何监控 Celery 任务的执行情况
当 Celery 任务出现阻塞或延迟时，你如何进行故障排除？
VUE双向数据绑定
VUE实例的生命周期钩子函数有哪些☆
v-if与v-show区别☆
cookie和seesion区别☆
VUE父子组件如何通信
nextTick 使用场景
ref和reactive区别
你有写过VUE自定义指令吗？
排序算法☆
查找算法☆
SSO单点登录实现原理☆


开放性问题
谈谈你对SRE理念的理解☆
什么是可观测性
你们当前的业务规模☆
运维过程中遇到的最大的故障是什么？怎么解决的？☆
有没有人为误操作导致故障，如何处理的？☆
平时怎么去学习新的技术☆
最近工作中做过最有意义的事☆
最近研究的技术方向是什么
运维上线流程规范
运维体系建设包含哪些方面☆
故障事件管控怎么设计
告警覆盖率和准确率怎么衡量☆
如何建设运维保障体系
运维给公司带来的价值是什么
运维和其他团队的职能边界和合作模式是什么
运维的发展方向是什么☆
运维的工作重点是什么
运维的工作效率如何提升
是否做过故障总结，包含哪些内容
如何看待自动化操作高效性和人工操作确认安全性的问题
如何看待运维维稳和开发求新的问题☆
如何看待追求更多的可靠性和成本的平衡问题
如何看待追求稳定性和新技术方案实践的问题
如何看待运维工作中的重复性、没有持续价值的工作☆
如何避免告警通知频繁导致成为告警噪声☆
是否关注过资源使用率，考虑降低成本☆
CMDB数据库怎么设计
SLO是多少，运维自动化率多少
与上级意见不一致怎么办
你的优点和缺点分别是什么？
与其他候选人相比，你的核心竞争力是什么？
部分用户访问服务首页白屏超时，分析服务请求过程和可能的原因
线上一个服务响应很慢，你如何排查，排查流程是什么?
你们的告警监控体系怎么设计的？
