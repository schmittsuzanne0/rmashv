最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计开源项目贡献指南 contributing
简介：golang 单例模式实现几种方式，Go 单例模式多种实现对比，sync.Once 等方式，实现全局唯一实例。
 | 原文链接：http://book.n23r2d.asia/blog/895363.Doc

原标题：golang es 映射 mapping 设计避坑
简介：限流规则误拦截正常请求修复，修正限流规则阈值，避免合法用户被限流拦截，兼顾防护与可用性。
 | 原文链接：http://book.n23r2d.asia/blog/351266.Doc

原标题：golang 系统设计内存复用 sync.pool 使用
简介：提交第一个开源 PR 完整流程，Fork 项目、修改代码、提交 Pull Request，讲解 PR 规范，提升合并通过率。
 | 原文链接：http://book.n23r2d.asia/blog/794323.Doc

原标题：golang 系统设计配置多环境隔离方案落地
简介：时间精度统一业务判断修复，统一业务使用时间戳精度，毫秒秒区分清楚，修复时间判断逻辑错误。
 | 原文链接：http://book.n23r2d.asia/blog/753266.Doc

原标题：坑点：Git仓库过大，clone速度极慢解决方案
简介：golang cgo 性能开销避坑指南，cgo 调用开销，减少频繁 cgo 调用，规避 cgo 带来内存泄漏风险。
 | 原文链接：http://book.n23r2d.asia/blog/672147.Doc

原标题：Nginx 请求头大小上限调整
简介：golang os.Signal 信号监听完整示例，signal.Notify 监听信号，缓冲 channel 防止信号丢失。
 | 原文链接：http://book.n23r2d.asia/blog/041609.Doc

原标题：记一次日志切割脚本错误直接清空业务日志
简介：golang nats 轻量消息队列 go 开发，nats 高性能轻量消息系统，发布订阅模式异步解耦业务。
 | 原文链接：http://book.n23r2d.asia/blog/626221.Doc

原标题：Architecture：灰度、蓝绿、金丝雀发布架构对比
简介：golang 信号捕获程序退出处理，Go 捕获操作系统信号，做资源回收，控制程序退出流程。
 | 原文链接：http://book.n23r2d.asia/blog/352412.Doc

原标题：零基础理解版本控制核心概念与工作流
简介：Docker 容器入门镜像实操教程，介绍 Docker 基础概念，演示镜像拉取、容器启停，帮助新手建立容器化开发认知。
 | 原文链接：http://book.n23r2d.asia/blog/429101.Doc

原标题：架构笔记：WebSocket大规模连接服务架构
简介：上传接口跨域配置特殊适配，针对文件上传接口，适配复杂请求，修复上传场景下跨域失效问题。
 | 原文链接：http://book.n23r2d.asia/blog/204991.Doc

原标题：golang 系统设计 cpu 瓶颈定位优化方案
简介：golang 大内存分配 GC 抖动规避，避免瞬时大量对象创建，分批处理，防止 GC 抖动业务抖动。
 | 原文链接：http://book.n23r2d.asia/blog/938440.Doc

原标题：部署复盘：金丝雀发布流量切分实操方案
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://book.n23r2d.asia/blog/908463.Doc

原标题：golang 系统设计配置多环境本地开发适配方案
简介：golang go mod tidy 依赖清理，go mod tidy 自动增删依赖，整理 go.mod go.sum 文件。
 | 原文链接：http://book.n23r2d.asia/blog/097233.Doc

原标题：特殊输入字符过滤解析防护
简介：并发数据覆盖加锁安全处理，多线程并发修改同一数据，增加锁机制，防止并发覆盖丢失更新数据。
 | 原文链接：http://book.n23r2d.asia/blog/019192.Doc

原标题：golang docker volume 数据持久化
简介：前端虚拟列表大数据渲染优化，实现虚拟滚动列表，只渲染可视区域 DOM，上万条数据页面流畅渲染。
 | 原文链接：http://book.n23r2d.asia/blog/450269.Doc

原标题：Performance：缓存策略优化，降低数据库压力
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://book.n23r2d.asia/blog/015541.Doc

原标题：Architecture：BFF后端聚合层架构适用场景
简介：动态定时任务业务调度实现，实现可以动态增删启停定时任务，无需重启服务调整调度任务。
 | 原文链接：http://book.n23r2d.asia/blog/567418.Doc

原标题：golang es 聚合统计查询实现
简介：本地运行正常线上报错排查，对比本地与线上环境差异，从配置、系统版本、文件权限定位线上独有的 bug。
 | 原文链接：http://book.n23r2d.asia/blog/297363.Doc

原标题：数值 key 浮点匹配异常规避
简介：golang os 主机名内核版本读取，os 读取主机名，内核信息，操作系统版本，获取运行环境信息。
 | 原文链接：http://book.n23r2d.asia/blog/184992.Doc

原标题：方案对比：单体、微服务、模块化单体取舍
简介：golang gin 框架接口开发实战，Gin 框架搭建 HTTP 服务，开发增删改查接口，快速完成后端接口开发。
 | 原文链接：http://book.n23r2d.asia/blog/590684.Doc

原标题：golang 系统设计第三方调用超时重试熔断
简介：Redis 内存淘汰策略数据防丢失，合理配置 Redis 内存淘汰策略，防止内存满后误删除业务重要数据。
 | 原文链接：http://book.n23r2d.asia/blog/944708.Doc

原标题：golang 系统设计缓存一致性方案对比
简介：golang http MaxHeaderBytes 限制请求头，设置 http 最大请求头大小，防止超大 header 攻击。
 | 原文链接：http://book.n23r2d.asia/blog/016680.Doc

原标题：线上异常：时间时区问题，定时任务执行偏移
简介：golang 读写分离 gorm 实现主从切换，gorm 配置主库写入从库查询，读写分离分担数据库查询压力。
 | 原文链接：http://book.n23r2d.asia/blog/757981.Doc

原标题：架构复盘：系统扩容缩容架构无状态优先原则
简介：OpenAPI 自动接口文档生成，集成 OpenAPI 工具，自动扫描代码生成接口文档，减少文档维护成本。
 | 原文链接：http://book.n23r2d.asia/blog/426744.Doc

原标题：vite 项目配置与构建提速技巧
简介：golang fuzz corpus 语料库使用，fuzz 语料存储历史输入，回归测试，持续复现曾经触发 bug 输入。
 | 原文链接：http://book.n23r2d.asia/blog/971228.Doc

原标题：Git LFS 大文件推送失败解决
简介：golang kafka 消费者组重平衡避坑，规避消费者组频繁 rebalance，减少消费抖动，保障消息消费稳定性。
 | 原文链接：http://book.n23r2d.asia/blog/453817.Doc

原标题：golang 系统设计缓存 key 命名规范最佳实践
简介：golang 子进程执行命令标准流处理，exec.Command 执行外部命令，处理 stdout stderr，防止缓冲区阻塞卡死。
 | 原文链接：http://book.n23r2d.asia/blog/593599.Doc

原标题：nodejs 定时任务生产环境避坑
简介：golang nilnil interface 陷阱复现，interface 包含类型不为 nil 值为 nil，判 ==nil 返回 false 经典坑。
 | 原文链接：http://book.n23r2d.asia/blog/904030.Doc

原标题：实践：接口参数自动校验业务落地实践
简介：golang go 二进制安全 strip 减小体积，strip 剥离二进制调试符号，缩小程序二进制文件体积。
 | 原文链接：http://book.n23r2d.asia/blog/160963.Doc

原标题：JWT 令牌过期异常处理
简介：前后端交互跨域问题完整处理，讲解跨域产生原理，列举多种解决方案，适配开发、生产不同环境的跨域处理。
 | 原文链接：http://book.n23r2d.asia/blog/178511.Doc

原标题：golang 大文件读取内存优化
简介：静态站点自动部署发布方案，配置流水线，代码更新自动构建静态站点并且部署上线，简化发布。
 | 原文链接：http://book.n23r2d.asia/blog/083822.Doc

原标题：golang 系统设计配置回滚版本历史记录实现
简介：golang 跨域处理中间件编写，Gin 跨域中间件开发，处理预检 OPTIONS 请求，解决浏览器跨域报错。
 | 原文链接：http://book.n23r2d.asia/blog/003477.Doc

原标题：Troubleshooting：数据库索引失效，查询性能暴跌
简介：批量异步处理系统业务落地，构建批量异步处理系统，把耗时业务异步化，提升接口响应速度。
 | 原文链接：http://book.n23r2d.asia/blog/007568.Doc

原标题：用户敏感数据脱敏代码实现
简介：golang aes 对称加密解密示例，AES 对称加密解密实现，业务敏感数据加密存储传输。
 | 原文链接：http://book.n23r2d.asia/blog/689851.Doc

原标题：DevOps：多阶段构建Dockerfile最佳实践
简介：golang mysql 事务回滚异常处理，Go MySQL 事务异常捕获，正确回滚事务，保证异常场景数据回滚。
 | 原文链接：http://book.n23r2d.asia/blog/758330.Doc

原标题：设计思考：系统降级开关架构设计快速切流量
简介：静态博客部署 GitHub Pages 教程，将静态博客项目部署至 GitHub Pages，完成线上访问，快速搭建个人技术博客站点。
 | 原文链接：http://book.n23r2d.asia/blog/820265.Doc

原标题：简易网关请求路由过滤模拟
简介：golang http 服务优雅关闭完整示例，接收终止信号，停止接收新请求，等待现有请求处理完毕后退出服务。
 | 原文链接：http://book.n23r2d.asia/blog/561285.Doc

原标题：磁盘 inode 耗尽文件创建失败
简介：golang go 容器 heap 堆实现优先队列，实现 heap 接口，构建优先队列，任务优先级调度。
 | 原文链接：http://book.n23r2d.asia/blog/112544.Doc

原标题：调优方案：MySQL缓冲池参数性能调优实践
简介：golang interface {} 类型断言类型转换，类型断言 ok 模式，避免断言失败触发 panic。
 | 原文链接：http://book.n23r2d.asia/blog/415066.Doc

原标题：golang 系统设计滑动窗口限流代码示例
简介：golang gin 静态资源访问配置，Gin 配置静态资源目录，直接对外提供静态文件访问服务。
 | 原文链接：http://book.n23r2d.asia/blog/990772.Doc


二、踩坑排错｜Troubleshooting
原标题：golang 系统设计本地缓存更新失效方案实现
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://book.n23r2d.asia/blog/590515.Doc

原标题：开发记录：长连接连接管理自动清理僵死连接
简介：全局本地依赖隔离冲突规避，区分全局依赖与项目本地依赖，隔离环境，防止全局包干扰项目运行。
 | 原文链接：http://book.n23r2d.asia/blog/059444.Doc

原标题：golang 系统设计主键 id 选型雪花自增对比
简介：golang 分布式追踪全链路日志打印，日志打印 traceId，各个服务日志可串联，排查跨服务调用问题。
 | 原文链接：http://book.n23r2d.asia/blog/163217.Doc

原标题：无用对象回收抑制内存上涨
简介：网关超时时间调优后端等待，调大网关向后端转发请求超时时间，给后端业务充足处理时间。
 | 原文链接：http://book.n23r2d.asia/blog/017571.Doc

原标题：golang dockerfile 多阶段构建详解
简介：golang 半关闭 tcp 连接 shutdown，tcp 连接 shutdown 半关闭，单向关闭读或者写，理解 tcp 关闭流程。
 | 原文链接：http://book.n23r2d.asia/blog/758366.Doc

原标题：数值类型溢出错乱问题修复
简介：hosts 配置本地回环访问修复，修改 hosts 配置，修复 127.0.0.1 解析异常，本地服务访问失败问题。
 | 原文链接：http://book.n23r2d.asia/blog/820360.Doc

原标题：golang 优雅处理系统信号 SIGINT
简介：golang go 爬虫代理池轮换使用，http 代理池轮换，请求自动切换代理 IP，突破访问限制。
 | 原文链接：http://book.n23r2d.asia/blog/452699.Doc

原标题：前端权限路由动态生成实现
简介：golang grpc 客户端流上传数据，客户端流式请求，客户端分批上传数据到服务端，适合大文件传输。
 | 原文链接：http://book.n23r2d.asia/blog/969935.Doc

原标题：golang ci 流水线自动部署 k8s 示例
简介：golang net.Conn 包装自定义连接，包装 net.Conn，统计读写字节，日志打印，超时控制。
 | 原文链接：http://book.n23r2d.asia/blog/530247.Doc

原标题：程序信号中断退出处理逻辑
简介：golang trace 工具采集 go 程序执行轨迹，go trace 采集程序完整调度轨迹，分析协程调度阻塞问题。
 | 原文链接：http://book.n23r2d.asia/blog/604770.Doc

原标题：Issue：浏览器缓存ServiceWorker导致旧页面常驻
简介：golang 处理连接被重置 reset 错误，识别 connection reset by peer，对端关闭连接异常处理逻辑。
 | 原文链接：http://book.n23r2d.asia/blog/126223.Doc

原标题：golang 系统设计缓存 key 淘汰雪崩防护思路
简介：css 动画性能优化 GPU 加速，优化 CSS 动画，使用 GPU 加速属性，避免动画过程页面卡顿掉帧。
 | 原文链接：http://book.n23r2d.asia/blog/885939.Doc

原标题：golang csv 读写批量数据处理
简介：前端下载导出文件功能实现，前端实现文件流下载导出，处理异常，适配浏览器不同下载行为。
 | 原文链接：http://book.n23r2d.asia/blog/311356.Doc

原标题：golang minio 对象存储接口开发
简介：golang rsa 非对称加密签名验签，RSA 非对称加密与签名验签，实现非对称安全通信。
 | 原文链接：http://book.n23r2d.asia/blog/052733.Doc

原标题：入门实践：项目配置文件多环境管理方案
简介：golang 环境变量读取与类型转换，读取系统环境变量，做类型转换默认值处理，适配多环境部署。
 | 原文链接：http://book.n23r2d.asia/blog/267984.Doc

原标题：golang 系统设计定时任务调度时间校准要点
简介：golang redis 锁超时业务处理，Redis 分布式锁超时问题处理，锁续期逻辑，防止业务未完成锁提前释放。
 | 原文链接：http://book.n23r2d.asia/blog/075003.Doc

原标题：golang 系统设计缓存预热缓存降级实现
简介：golang make new 关键字使用区别，分清 new 与 make 适用类型，正确初始化切片 map 通道，杜绝 nil 引发 panic。
 | 原文链接：http://book.n23r2d.asia/blog/750989.Doc

原标题：开发复盘：消息队列消息顺序性业务落地实践
简介：golang 静态编译缩小镜像体积，Go 程序静态编译，不依赖系统库，产出单二进制文件，缩小镜像。
 | 原文链接：http://book.n23r2d.asia/blog/415002.Doc

原标题：踩坑：Docker容器内时区不一致引发的时间BUG
简介：nodejs 进程间通信 IPC 实操，演示 Node.js 主进程子进程 IPC 通信，进程之间传递消息数据。
 | 原文链接：http://book.n23r2d.asia/blog/279813.Doc

原标题：开源源码阅读拆解学习思路
简介：nodejs 定时任务生产环境避坑，Node 定时任务线上踩坑汇总，集群重复执行、任务阻塞等问题解决方案。
 | 原文链接：http://book.n23r2d.asia/blog/860926.Doc

原标题：Performance：避免内存拷贝，大对象处理优化
简介：golang atomic 原子操作整数，atomic 加减比较交换，无锁更新整型变量，简单计数器场景。
 | 原文链接：http://book.n23r2d.asia/blog/827914.Doc

原标题：golang 系统设计定时任务分布式锁防重复执行
简介：HTTP 状态码请求头完整梳理，汇总常用 HTTP 状态码与请求头含义，帮助快速看懂网络请求，排查接口通信问题。
 | 原文链接：http://book.n23r2d.asia/blog/430698.Doc

原标题：golang redis lua 脚本原子操作
简介：golang 容器 OOM 被杀死排查区分，区分业务内存泄漏、容器限制过小，定位容器 OOMKilled 原因。
 | 原文链接：http://book.n23r2d.asia/blog/566414.Doc

原标题：Troubleshoot：跨域偶现失败难以复现问题
简介：golang go 种子初始化 rand 随机，rand 初始化种子，不初始化会固定序列，理解随机数种子行为。
 | 原文链接：http://book.n23r2d.asia/blog/445362.Doc

原标题：踩坑：环境变量未生效导致线上配置错乱
简介：系统字符集统一乱码修复，统一数据库、程序、操作系统字符集，解决中文乱码显示异常问题。
 | 原文链接：http://book.n23r2d.asia/blog/497233.Doc

原标题：项目实践：本地模拟缓存失效风暴验证防护
简介：golang go 程序容器资源 requests limits，设置容器 cpu 内存配额，防止实例抢占集群资源，稳定调度。
 | 原文链接：http://book.n23r2d.asia/blog/742622.Doc

原标题：项目实践：接口压测，逐步加压观察系统表现
简介：golang 系统资源限制读取 cpu 内存，读取系统容器 cpu 内存限制，程序适配容器资源配额做业务调优。
 | 原文链接：http://book.n23r2d.asia/blog/860462.Doc

原标题：静态网页 HTML CSS 快速入门实战
简介：DNS TTL 配置域名切换生效，调整 DNS 解析 TTL，缩短缓存时间，域名变更后可以快速全网生效。
 | 原文链接：http://book.n23r2d.asia/blog/612112.Doc

原标题：golang 系统设计 ci 流水线安全管控思路
简介：golang 错误静默忽略风险规避，禁止空忽略错误，必须处理或者明确注释为什么忽略错误。
 | 原文链接：http://book.n23r2d.asia/blog/886521.Doc

原标题：性能笔记：RPC超时参数优化防止级联阻塞
简介：golang 文件句柄耗尽排查处理，统计进程打开文件句柄，找到未关闭文件，修复句柄泄漏问题。
 | 原文链接：http://book.n23r2d.asia/blog/757348.Doc

原标题：Fork 开源项目同步上游代码
简介：系统字符集统一乱码修复，统一数据库、程序、操作系统字符集，解决中文乱码显示异常问题。
 | 原文链接：http://book.n23r2d.asia/blog/590241.Doc

原标题：golang 系统设计压测工具 vegeta 使用示例
简介：golang 熔断降级简易组件开发，Go 简易熔断组件，下游故障触发熔断，保护上游服务不被拖垮。
 | 原文链接：http://book.n23r2d.asia/blog/089779.Doc

原标题：HelloWorld：快速上手新项目最小可运行示例
简介：golang time.After 内存泄漏场景，for 循环使用 time.After 会创建大量 timer，造成内存泄漏。
 | 原文链接：http://book.n23r2d.asia/blog/167000.Doc

原标题：看懂报错日志快速定位问题
简介：golang mqtt 客户端 go 开发物联网，paho.mqtt.golang 实现 mqtt 客户端，物联网设备消息收发。
 | 原文链接：http://book.n23r2d.asia/blog/127609.Doc

原标题：golang ci 流水线制品仓库上传下载
简介：服务器 Swap 关闭提升响应速度，关闭服务器 Swap 交换分区，避免内存交换磁盘拖慢程序响应性能。
 | 原文链接：http://book.n23r2d.asia/blog/691000.Doc

原标题：开发复盘：百万数据批量导入数据库优化方案
简介：golang 任务失败重试与死信队列，异步任务失败自动重试，超过重试次数进入死信队列人工处理。
 | 原文链接：http://book.n23r2d.asia/blog/235074.Doc

原标题：实战项目：CLI批量文件处理工具开发全过程
简介：新手参与开源社区贡献指南，介绍开源社区基础规则，讲解阅读 issue、提交 PR 流程，指导开发者参与开源贡献。
 | 原文链接：http://book.n23r2d.asia/blog/729444.Doc

原标题：性能笔记：线程池参数调优任务队列策略
简介：golang rabbitmq go 客户端生产消费，streadway/amqp 实现 rabbitmq 生产者消费者，队列交换机绑定。
 | 原文链接：http://book.n23r2d.asia/blog/786951.Doc

原标题：性能复盘：慢查询日积月累拖垮数据库优化
简介：安全组端口开放网络访问，调整服务器安全组规则，开放业务需要端口，恢复外部网络访问服务。
 | 原文链接：http://book.n23r2d.asia/blog/712818.Doc

原标题：设计思考：容器化业务应用架构改造要点
简介：定时任务重复执行分布式锁，使用分布式锁控制定时任务，保证集群环境定时任务只会执行一次。
 | 原文链接：http://book.n23r2d.asia/blog/193438.Doc

三、实战开发｜Practice
原标题：golang docker compose 完整语法
简介：nodejs 信号处理优雅关闭服务，监听系统信号，执行资源清理，实现 Node 服务优雅停机，拒绝粗暴杀死进程。
 | 原文链接：http://book.n23r2d.asia/blog/347133.Doc

原标题：K8s 镜像拉取网络故障修复
简介：golang http 服务优雅关闭完整示例，接收终止信号，停止接收新请求，等待现有请求处理完毕后退出服务。
 | 原文链接：http://book.n23r2d.asia/blog/620929.Doc

原标题：入门实践：搭建简单的热更新开发环境
简介：golang mqtt 客户端 go 开发物联网，paho.mqtt.golang 实现 mqtt 客户端，物联网设备消息收发。
 | 原文链接：http://book.n23r2d.asia/blog/938548.Doc

原标题：DevOps：Docker镜像优化，减小镜像体积实践
简介：golang json omitempty 零值坑，omitempty 会忽略零值，区分业务是否需要输出零值字段。
 | 原文链接：http://book.n23r2d.asia/blog/586555.Doc

原标题：DevOps：Docker镜像安全扫描集成CI流程
简介：golang arp 缓存读取操作，读取系统 arp 缓存表，获取 ip 对应的 mac 地址信息。
 | 原文链接：http://book.n23r2d.asia/blog/419552.Doc

原标题：Hands‑on：简易压缩中间件gzip实现实践
简介：前端图片懒加载性能优化，实现图片懒加载，页面可视区域才加载图片，减少页面初始网络请求。
 | 原文链接：http://book.n23r2d.asia/blog/503159.Doc

原标题：百万数据 Excel 导出内存优化
简介：golang redis 事务 multi exec 使用，Redis 事务 multi exec 实现批量命令原子执行，理解 redis 事务隔离特性。
 | 原文链接：http://book.n23r2d.asia/blog/607637.Doc

原标题：优化实践：LRU本地缓存优化热点访问性能
简介：golang go time 时区数据库内置，go 内置时区数据库，不用系统时区文件，容器时区不依赖系统。
 | 原文链接：http://book.n23r2d.asia/blog/893992.Doc

原标题：开发记录：业务错误告警邮件通知组件实践
简介：golang proto 可选字段处理方案，protobuf 可选字段正确判断，区分未赋值与零值，业务逻辑不出现偏差。
 | 原文链接：http://book.n23r2d.asia/blog/875144.Doc

原标题：Issue：Nginxkeepalive参数不合理大量TIME_WAIT
简介：golang 分库分表简单路由实现，简易分表路由逻辑实现，根据分片 key 计算分片位置，数据路由写入。
 | 原文链接：http://book.n23r2d.asia/blog/412655.Doc

原标题：前后端会话登录状态持久化
简介：nodejs 读取大文件 csv 处理方案，Node 流式读取超大 CSV 文件，逐行解析，避免一次性加载全部文件。
 | 原文链接：http://book.n23r2d.asia/blog/853832.Doc

原标题：Hands‑on：编写shell健康检查自动重启脚本
简介：前端组件库按需加载性能优化，配置组件库按需引入，避免引入全部组件，减少打包产物体积。
 | 原文链接：http://book.n23r2d.asia/blog/338003.Doc

原标题：踩坑：对象未释放，长时间运行内存持续上涨
简介：golang go 服务日志输出 journald，systemd journald 接收程序 stdout 日志，统一管理服务日志。
 | 原文链接：http://book.n23r2d.asia/blog/015499.Doc

原标题：性能笔记：布隆过滤器减少无效数据库查询
简介：golang sync.Map 高并发 map 使用场景，sync.Map 适用场景，读写实操，对比普通 map 加锁性能差异。
 | 原文链接：http://book.n23r2d.asia/blog/378528.Doc

原标题：实战：GraphQL服务搭建与CRUD实操
简介：nestjs 权限守卫鉴权实现方案，使用 Nest 守卫实现接口鉴权，角色权限控制，拦截未授权接口访问。
 | 原文链接：http://book.n23r2d.asia/blog/013226.Doc

原标题：快速入门Nginx基础配置，反向代理示例
简介：数据库事务 ACID 原理讲解，拆解事务四大特性，理解事务隔离、原子性，明白事务如何保障数据安全。
 | 原文链接：http://book.n23r2d.asia/blog/978703.Doc

原标题：golang 大文件 http 下载服务
简介：golang context.Background 与 TODO 区别，Background 主流程根上下文，TODO 不确定用哪个上下文时使用。
 | 原文链接：http://book.n23r2d.asia/blog/381481.Doc

原标题：golang redis 缓存雪崩完整处理
简介：golang os 文件权限 mode，os.FileMode 文件权限，读写执行权限位，跨平台权限注意事项。
 | 原文链接：http://book.n23r2d.asia/blog/043636.Doc

原标题：golang 系统设计事务消息 rocketmq 简单原理
简介：golang channel 关闭规则与坑点，关闭已经关闭 channel 会 panic，判断 channel 是否关闭正确写法。
 | 原文链接：http://book.n23r2d.asia/blog/482890.Doc

原标题：golang 系统设计分表分页排序业务实现难点
简介：golang 定时任务 cron 使用指南，Go 使用 Cron 库实现定时任务，配置 corn 表达式调度业务任务。
 | 原文链接：http://book.n23r2d.asia/blog/074773.Doc

原标题：踩坑：重试逻辑未做幂等，重复生成业务数据
简介：golang 网卡 ip 读取网络信息获取，程序读取本机网卡 IP，多网卡环境筛选业务使用 IP 地址。
 | 原文链接：http://book.n23r2d.asia/blog/078066.Doc

原标题：golang k8s 资源请求限制配置
简介：golang go 程序守护进程实现思路，go 程序不做 daemon 化，依靠 systemd pm2 k8s 实现进程守护。
 | 原文链接：http://book.n23r2d.asia/blog/535147.Doc

原标题：golang 系统设计集成测试数据库回滚重置方案
简介：golang 大文件 HTTP 流式上传接收，服务端流式接收上传文件，不全部加载内存，防止大文件 OOM 崩溃。
 | 原文链接：http://book.n23r2d.asia/blog/791709.Doc

原标题：golang 系统设计配置敏感信息加密存储
简介：线程池拒绝策略任务丢失防护，合理设置线程池拒绝策略，处理任务队列满场景，避免业务任务直接丢失。
 | 原文链接：http://book.n23r2d.asia/blog/807929.Doc

原标题：golang 系统设计熔断算法 hystrix 思路
简介：golang 错误静默忽略风险规避，禁止空忽略错误，必须处理或者明确注释为什么忽略错误。
 | 原文链接：http://book.n23r2d.asia/blog/662441.Doc

原标题：golang 系统设计指标聚合计算存储选型对比
简介：golang k8s go 服务 yaml 资源编写，k8s 部署 go 应用 deployment service，健康检查资源限制配置。
 | 原文链接：http://book.n23r2d.asia/blog/620299.Doc

原标题：golang 系统设计锁优化减少竞争提升吞吐
简介：Shell 运维脚本服务器效率提升，编写常用运维 Shell 脚本，自动化服务器运维操作，减少手工重复工作。
 | 原文链接：http://book.n23r2d.asia/blog/568733.Doc

原标题：本地运行正常线上报错排查
简介：Docker 容器入门镜像实操教程，介绍 Docker 基础概念，演示镜像拉取、容器启停，帮助新手建立容器化开发认知。
 | 原文链接：http://book.n23r2d.asia/blog/997661.Doc

原标题：请求工具封装统一异常处理
简介：golang go http 安全头配置实践，设置 http 安全响应头，防范 XSS、点击劫持，提升 web 服务安全性。
 | 原文链接：http://book.n23r2d.asia/blog/489553.Doc

原标题：架构复盘：消息队列在业务系统中边界与最佳实践
简介：golang 微服务网关简易实现，http 反向代理、路由匹配、鉴权限流，理解网关核心原理。
 | 原文链接：http://book.n23r2d.asia/blog/126737.Doc

原标题：golang 系统设计数据脱敏架构实现
简介：golang rate 令牌桶限流器源码理解，拆解令牌桶限流核心逻辑，理解令牌生成消耗，掌握限流底层原理。
 | 原文链接：http://book.n23r2d.asia/blog/891288.Doc

原标题：数据库索引重建提升查询速度
简介：golang go‑zero 监控指标埋点，go‑zero 内置 metrics 监控，上报业务指标对接监控平台。
 | 原文链接：http://book.n23r2d.asia/blog/030040.Doc

原标题：golang 跨域处理中间件编写
简介：从零编写简易 CLI 命令行工具，通过实战案例实现基础命令交互，理解命令行程序执行逻辑，产出可运行小工具。
 | 原文链接：http://book.n23r2d.asia/blog/890044.Doc

原标题：记一次升级操作系统内核引发服务不稳定
简介：golang go 程序权限最小化运行，容器内使用普通用户运行程序，拒绝 root 运行提升安全等级。
 | 原文链接：http://book.n23r2d.asia/blog/723460.Doc

原标题：golang 系统设计 tcp keepalive 参数调优实践
简介：数值 key 浮点匹配异常规避，避免浮点数作为 Redis 等存储的 key，防止精度问题引发 key 匹配失败。
 | 原文链接：http://book.n23r2d.asia/blog/241860.Doc

原标题：golang 错误包装 errors.wrap 用法
简介：golang context.Background 与 TODO 区别，Background 主流程根上下文，TODO 不确定用哪个上下文时使用。
 | 原文链接：http://book.n23r2d.asia/blog/014292.Doc

原标题：golang jwt 过期刷新 token 实现
简介：序列化版本不一致解析失败，保证序列化对象版本对齐，修复版本不匹配导致对象反序列化失败。
 | 原文链接：http://book.n23r2d.asia/blog/122211.Doc

原标题：golang 协程泄露问题排查方法
简介：golang gorm 预加载关联查询优化，GORM 预加载关联数据，避免 N+1 查询问题，提升数据库查询性能。
 | 原文链接：http://book.n23r2d.asia/blog/556830.Doc

原标题：Practice：JWT工具封装，刷新令牌完整逻辑
简介：golang 开发环境快速搭建指南，快速完成 Golang 开发环境配置，工具链安装，环境变量设置，准备开发。
 | 原文链接：http://book.n23r2d.asia/blog/023026.Doc

原标题：开发复盘：统一错误码体系设计落地实践
简介：内存广播本地进程消息通知，实现进程内内存消息广播，进程内部模块之间事件通知解耦。
 | 原文链接：http://book.n23r2d.asia/blog/969287.Doc

四、架构设计｜Architecture
原标题：安全笔记：文件下载接口路径校验安全
简介：golang go math 大数高精度计算，math/big 处理超大整数、高精度浮点数，金额大数运算。
 | 原文链接：http://book.n23r2d.asia/blog/788496.Doc

原标题：全局异常处理器接口返回统一
简介：WebSocket 聊天室实时通讯开发，基于 WebSocket 搭建简易聊天室，实现多人消息广播实时聊天效果。
 | 原文链接：http://book.n23r2d.asia/blog/756221.Doc

原标题：Debug：网关超时时间小于后端接口超时设置
简介：ORM 隐式慢查询问题规避，识别 ORM 框架隐式查询，避免循环查询数据库，减少不必要慢 SQL 产生。
 | 原文链接：http://book.n23r2d.asia/blog/984112.Doc

原标题：golang 系统设计延迟队列业务实现
简介：golang grpc 双向流双向通信开发，grpc 双向流，服务端客户端持续互发消息，长连接流式业务场景。
 | 原文链接：http://book.n23r2d.asia/blog/244466.Doc

原标题：超大数据集分页性能优化方案
简介：golang go‑zero 框架项目快速搭建，go‑zero 脚手架生成微服务项目，api rpc 服务快速开发。
 | 原文链接：http://book.n23r2d.asia/blog/892618.Doc

原标题：golang 配置文件多环境加载
简介：golang 服务注册 etcd 简单示例，etcd 实现服务注册发现，微服务实例注册元数据，客户端发现节点。
 | 原文链接：http://book.n23r2d.asia/blog/011790.Doc

原标题：空指针异常判空容错处理
简介：项目构建脚本编译打包解析，解读项目构建脚本，理清编译、压缩、资源复制流程，理解打包后产物如何生成。
 | 原文链接：http://book.n23r2d.asia/blog/907134.Doc

原标题：开发复盘：避免大报文导致服务OOM优化实践
简介：前端国际化多语言方案落地，搭建前端多语言国际化方案，切换语言，页面文本自动切换对应语种。
 | 原文链接：http://book.n23r2d.asia/blog/686098.Doc

原标题：方案对比：几种分布式限流算法架构适用性
简介：接口限流逻辑简单模拟实现，编写简易限流逻辑，限制接口访问频次，保护服务，避免短时间大量请求压垮系统。
 | 原文链接：http://book.n23r2d.asia/blog/387799.Doc

原标题：简易日志收集集中管理方案
简介：前端组件库按需加载性能优化，配置组件库按需引入，避免引入全部组件，减少打包产物体积。
 | 原文链接：http://book.n23r2d.asia/blog/377456.Doc

原标题：golang ci 流水线漏洞扫描依赖检查
简介：Redis 内存淘汰策略数据防丢失，合理配置 Redis 内存淘汰策略，防止内存满后误删除业务重要数据。
 | 原文链接：http://book.n23r2d.asia/blog/900643.Doc

原标题：简易网关请求路由过滤模拟
简介：golang regexp 正则捕获分组提取数据，正则捕获分组提取子匹配内容，拿到需要业务字段。
 | 原文链接：http://book.n23r2d.asia/blog/748160.Doc

原标题：避坑：请求未设置read超时无限挂起连接
简介：golang context 上下文传参讲解，讲解 Context 使用场景，传递元数据、控制协程超时取消，规范协程控制。
 | 原文链接：http://book.n23r2d.asia/blog/250632.Doc

原标题：TLS 版本兼容 HTTPS 握手失败
简介：golang go test 单元测试命令参数详解，gotest 参数覆盖率，指定测试用例，跳过测试，单元测试命令实操。
 | 原文链接：http://book.n23r2d.asia/blog/672826.Doc

原标题：消息队列生产消费模型入门
简介：golang 子进程执行命令标准流处理，exec.Command 执行外部命令，处理 stdout stderr，防止缓冲区阻塞卡死。
 | 原文链接：http://book.n23r2d.asia/blog/636819.Doc

原标题：开发复盘：海量日志轮转清理脚本实践
简介：RPC 报文大小上限调优大请求，调大 RPC 框架报文最大限制，支持传输大体积请求报文不被截断。
 | 原文链接：http://book.n23r2d.asia/blog/696531.Doc

原标题：新手指南：本地防火墙端口访问失败排查
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://book.n23r2d.asia/blog/297951.Doc

原标题：GitHub Markdown 文档语法汇总
简介：golang 配置文件热加载监听变更，监听配置文件改动，自动重新加载配置，业务即时生效无需重启。
 | 原文链接：http://book.n23r2d.asia/blog/441496.Doc

?
