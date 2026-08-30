最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang docker 部署 prometheus 整套
简介：golang grpc metadata 元数据透传，metadata 传递 traceId、鉴权信息，全链路透传上下文信息。
 | 原文链接：http://book.sodfth.asia/blog/1906799.sHtMl

原标题：设计思考：系统幂等性整体架构层面保障
简介：数据库主从延迟业务兼容处理，业务适配主从复制延迟，避免读取从库拿到还未同步完成旧数据。
 | 原文链接：http://book.sodfth.asia/blog/1295648.sHtMl

原标题：golang 系统设计缓存基准测试对比方案
简介：golang go select 多路等待 channel，select 等待多个 channel，default 非阻塞，超时等待 channel。
 | 原文链接：http://book.sodfth.asia/blog/4510636.sHtMl

原标题：golang 系统设计 websocket 协议原理梳理
简介：golang go 零停机升级实践要点，socket 继承，流量无损，旧连接处理完毕后旧进程退出。
 | 原文链接：http://book.sodfth.asia/blog/7806604.sHtMl

原标题：开源源码阅读拆解学习思路
简介：接口签名校验防篡改实现，实现请求签名验签逻辑，校验请求参数未被篡改，提升接口调用安全性。
 | 原文链接：http://book.sodfth.asia/blog/5000684.sHtMl

原标题：golang 系统设计索引设计通用方法论汇总
简介：golang bufio.Scanner 缓冲区调大，Scanner 默认缓冲区大小不够，读取超长行需要扩大缓冲区。
 | 原文链接：http://book.sodfth.asia/blog/1627706.sHtMl

原标题：Hands‑on：简易频率统计组件Redis实现
简介：全局本地依赖隔离冲突规避，区分全局依赖与项目本地依赖，隔离环境，防止全局包干扰项目运行。
 | 原文链接：http://book.sodfth.asia/blog/3885698.sHtMl

原标题：nodejs 中间件模式原理剖析
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://book.sodfth.asia/blog/3426541.sHtMl

原标题：golang redis 位图用户签到统计
简介：golang GC 调优 GOGC 参数调整，调整 GOGC 阈值，控制 GC 触发时机，权衡内存占用与 CPU 开销。
 | 原文链接：http://book.sodfth.asia/blog/7208318.sHtMl

原标题：golang 数据库批量更新性能优化
简介：golang 信号量控制并发数量，使用信号量控制并发，限制同时执行任务数量，保护下游资源。
 | 原文链接：http://book.sodfth.asia/blog/3529190.sHtMl

原标题：golang 分布式锁防死锁处理
简介：golang http 客户端连接泄漏排查，http client 未读取响应体导致连接无法复用，解决连接泄漏耗尽连接池。
 | 原文链接：http://book.sodfth.asia/blog/6173619.sHtMl

原标题：排错：多实例部署session共享失效登录失效
简介：golang go 爬虫 html 解析 goquery，goquery 解析 html 文档，css 选择器提取网页内容，实现网页数据抓取。
 | 原文链接：http://book.sodfth.asia/blog/8620641.sHtMl

原标题：Debug：时间回拨，定时任务调度逻辑错乱
简介：golang 熔断降级简易组件开发，Go 简易熔断组件，下游故障触发熔断，保护上游服务不被拖垮。
 | 原文链接：http://book.sodfth.asia/blog/9785311.sHtMl

原标题：Troubleshoot：异步异常未捕获，进程悄无声息退出
简介：CI 构建缓存加速编译速度，开启 CI 流水线依赖缓存，复用上一次构建依赖包，缩短流水线构建耗时。
 | 原文链接：http://book.sodfth.asia/blog/4322699.sHtMl

原标题：时间精度统一业务判断修复
简介：golang go regexp 正则预编译，regexp.MustCompile 预编译正则，不要循环内部编译正则，节省 CPU。
 | 原文链接：http://book.sodfth.asia/blog/7540591.sHtMl

原标题：线上异常：布隆过滤器误判造成业务逻辑异常
简介：golang trace 工具采集 go 程序执行轨迹，go trace 采集程序完整调度轨迹，分析协程调度阻塞问题。
 | 原文链接：http://book.sodfth.asia/blog/6064195.sHtMl

原标题：golang 系统设计分布式事务几种方案
简介：本地简易配置中心动态管理，搭建轻量本地配置中心，业务动态读取配置，修改配置不重启服务。
 | 原文链接：http://book.sodfth.asia/blog/8274354.sHtMl

原标题：Practice：实现多数据源动态切换组件实践
简介：golang base64 大文件流式编解码，大文件流式 base64 转换，不用一次性加载全部文件进入内存。
 | 原文链接：http://book.sodfth.asia/blog/1835506.sHtMl

原标题：多实例部署 Session 共享方案
简介：golang excel 简单读写操作示例，Go 实现 Excel 简单读写，业务数据导出 Excel 报表。
 | 原文链接：http://book.sodfth.asia/blog/1683086.sHtMl

原标题：CI 构建缓存加速编译速度
简介：macOS 脚本执行权限开启，给 Shell 脚本添加可执行权限，解决 macOS 下脚本无法运行权限报错。
 | 原文链接：http://book.sodfth.asia/blog/1509409.sHtMl

原标题：进程线程并发基础概念讲解
简介：JWT 工具封装令牌刷新过期，封装 JWT 工具类，实现令牌生成、校验、过期刷新整套令牌管理逻辑。
 | 原文链接：http://book.sodfth.asia/blog/1256746.sHtMl

原标题：数据库分表路由写入分片修正
简介：消息消费重试次数限制防爆炸，限制消息最大重试次数，防止失败消息无限重试造成消息爆炸堆积。
 | 原文链接：http://book.sodfth.asia/blog/7115552.sHtMl

原标题：方案设计：统一ID生成服务架构对比雪花算法
简介：nodejs 跨域中间件配置细节，Express 跨域中间件配置细节，处理预检请求，修复偶现跨域失效。
 | 原文链接：http://book.sodfth.asia/blog/7860297.sHtMl

原标题：实践：OpenAPI自动生成接口文档完整实践
简介：golang staticcheck 静态代码分析，staticcheck 深度静态检查，发现代码错误、性能问题、风格问题。
 | 原文链接：http://book.sodfth.asia/blog/1262340.sHtMl

原标题：golang 系统设计内存瓶颈定位优化思路
简介：nodejs 单元测试 jest 实操教程，Jest 单元测试实操，编写测试用例，mock 依赖，验证业务逻辑正确性。
 | 原文链接：http://book.sodfth.asia/blog/7988868.sHtMl

原标题：golang 系统设计本地消息表可靠消息最终一致性
简介：Nginx 请求头大小上限调整，修改 Nginx 配置，调大请求头允许最大大小，避免大 Header 请求被拒绝。
 | 原文链接：http://book.sodfth.asia/blog/2868915.sHtMl

原标题：golang 系统设计链路追踪架构简单讲解
简介：golang cgo 性能开销避坑指南，cgo 调用开销，减少频繁 cgo 调用，规避 cgo 带来内存泄漏风险。
 | 原文链接：http://book.sodfth.asia/blog/2985349.sHtMl

原标题：快速入门YAML配置文件语法与示例
简介：Docker 多阶段构建镜像瘦身，使用 Docker 多阶段构建，剔除编译阶段依赖，产出体积更小运行镜像。
 | 原文链接：http://book.sodfth.asia/blog/0762895.sHtMl

原标题：安全实践：SQL注入产生场景与完整防御手段
简介：布隆过滤器数据高效去重实现，实现布隆过滤器组件，用于海量数据去重，节省大量内存空间。
 | 原文链接：http://book.sodfth.asia/blog/9629143.sHtMl

原标题：新手指南：如何读懂开源项目报错日志
简介：golang go 项目安全检查漏洞扫描，扫描 go 项目依赖漏洞，代码安全审计，规避安全风险。
 | 原文链接：http://book.sodfth.asia/blog/4947240.sHtMl

原标题：实战项目：Nginx限速、限流、防爬虫配置实践
简介：golang redis pipeline 与 txpipeline 区别，区分普通管道与事务管道，根据业务场景选择合适批量执行方案。
 | 原文链接：http://book.sodfth.asia/blog/3433539.sHtMl

原标题：golang 系统设计大事务拆分实战思路
简介：CI/CD 流水线自动构建部署落地，搭建完整 CI/CD 流水线，代码提交自动构建、测试、部署到目标环境。
 | 原文链接：http://book.sodfth.asia/blog/7111350.sHtMl

原标题：Performance：避免内存拷贝，大对象处理优化
简介：golang 大文件读取内存优化，Go 流式读取大文件，分块处理，避免大文件一次性加载全部到内存。
 | 原文链接：http://book.sodfth.asia/blog/4862778.sHtMl

原标题：golang 系统设计集成测试环境准备清理实操
简介：golang grpc 服务端流推送数据，服务端流式响应，服务端持续向客户端推送多条响应消息。
 | 原文链接：http://book.sodfth.asia/blog/9505510.sHtMl

原标题：golang 系统设计分库分表扩容平滑迁移
简介：golang 接口限流中间件开发，Gin 开发限流中间件，接口层实现访问频率限制，防护接口流量。
 | 原文链接：http://book.sodfth.asia/blog/9670455.sHtMl

原标题：golang 系统设计分布式锁选型对比
简介：golang select 随机分支执行特性，多个 channel 就绪 select 随机选择，理解 select 行为特性。
 | 原文链接：http://book.sodfth.asia/blog/2685661.sHtMl

原标题：Troubleshooting：k8s镜像拉取失败镜像仓库网络问题
简介：Fork 开源项目同步上游代码，Fork 开源仓库之后，配置上游源，同步官方最新代码，保持代码版本对齐。
 | 原文链接：http://book.sodfth.asia/blog/8530370.sHtMl

原标题：Performance：数据库大表优化，冷热数据分离
简介：内网测试服务搭建团队调试，配置本地服务内网可访问，团队成员能够访问调试，方便前后端联调与内部演示。
 | 原文链接：http://book.sodfth.asia/blog/7178795.sHtMl

原标题：快速上手简单性能监控指标查看
简介：golang go 并发模式 fan‑out fan‑in，fanout 分发任务 fanin 汇总结果，多协程并发处理任务。
 | 原文链接：http://book.sodfth.asia/blog/5933410.sHtMl

原标题：golang 系统设计主干开发 trunk‑based 讲解
简介：golang 模板函数自定义拓展，自定义 template 模板函数，在 html 模板调用自定义逻辑处理数据。
 | 原文链接：http://book.sodfth.asia/blog/2786465.sHtMl


二、踩坑排错｜Troubleshooting
原标题：部署实践：容器优雅停机配置处理信号
简介：nodejs 全局异常捕获进程防护，捕获未捕获异常与 Promise 拒绝，尽量保护进程不因为异常直接退出。
 | 原文链接：http://book.sodfth.asia/blog/6649153.sHtMl

原标题：业务幂等键设计防重复逻辑
简介：golang go 锁竞争导致 CPU 飙升，识别锁竞争场景，减少锁粒度，优化并发逻辑降低 CPU 开销。
 | 原文链接：http://book.sodfth.asia/blog/3224303.sHtMl

原标题：golang mysql 悲观锁乐观锁实现
简介：golang go 并发模式 errgroup 使用，errgroup 结合 context，协程组，任意协程出错整体取消任务。
 | 原文链接：http://book.sodfth.asia/blog/9680211.sHtMl

原标题：Debug：Websocket频繁断开重连根因分析
简介：golang os 打开文件 O_APPEND O_CREATE 标志，OpenFile 标志位，控制文件创建追加截断行为。
 | 原文链接：http://book.sodfth.asia/blog/9532770.sHtMl

原标题：调优方案：Docker容器内核参数性能调优
简介：golang smtp 邮件发送完整示例，调用 smtp 服务发送文本与 html 格式邮件，实现邮件通知能力。
 | 原文链接：http://book.sodfth.asia/blog/8567041.sHtMl

原标题：golang kafka 死信队列业务落地
简介：golang 文件句柄耗尽排查处理，统计进程打开文件句柄，找到未关闭文件，修复句柄泄漏问题。
 | 原文链接：http://book.sodfth.asia/blog/2653541.sHtMl

原标题：K8s 镜像拉取网络故障修复
简介：golang go 运行时获取编译信息，程序内部读取编译时间 git 版本，接口输出程序版本信息。
 | 原文链接：http://book.sodfth.asia/blog/1248179.sHtMl

原标题：Debug：并发场景下数据覆盖丢失问题定位
简介：缓存过期策略优化防业务故障，合理设置缓存过期策略，规避集中过期，减少缓存失效带来业务抖动。
 | 原文链接：http://book.sodfth.asia/blog/4888711.sHtMl

原标题：golang 系统设计 webhook 回调接口设计要点
简介：golang grpc 重试机制客户端配置，grpc 客户端配置重试策略，临时故障自动重试，提升调用稳定性。
 | 原文链接：http://book.sodfth.asia/blog/7122207.sHtMl

原标题：版本升级服务启动失败处理
简介：golang go1.18 + 泛型基础实操，go 泛型基础语法，泛型函数泛型类型，实现通用工具函数。
 | 原文链接：http://book.sodfth.asia/blog/7865824.sHtMl

原标题：新手向：项目目录结构规范与含义解析
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：http://book.sodfth.asia/blog/6177472.sHtMl

原标题：golang gitlab runner 部署与注册实操
简介：HTTP 状态码请求头完整梳理，汇总常用 HTTP 状态码与请求头含义，帮助快速看懂网络请求，排查接口通信问题。
 | 原文链接：http://book.sodfth.asia/blog/1515278.sHtMl

原标题：golang docker compose 本地开发最佳实践
简介：axios 二次封装请求拦截处理，对 axios 做二次封装，统一请求拦截响应拦截，处理错误、token 自动刷新。
 | 原文链接：http://book.sodfth.asia/blog/5218994.sHtMl

原标题：golang 系统设计 rest 资源命名规范汇总
简介：空指针异常判空容错处理，讲解空指针产生场景，规范判空逻辑，增加容错，避免空指针直接造成程序崩溃。
 | 原文链接：http://book.sodfth.asia/blog/3714009.sHtMl

原标题：golang jwt 鉴权中间件完整示例
简介：DNS TTL 配置域名切换生效，调整 DNS 解析 TTL，缩短缓存时间，域名变更后可以快速全网生效。
 | 原文链接：http://book.sodfth.asia/blog/5943520.sHtMl

原标题：golang 系统设计请求签名校验完整方案
简介：golang gorm select 指定查询字段，指定查询字段，避免查询全部字段，减少数据传输，提升查询性能。
 | 原文链接：http://book.sodfth.asia/blog/4551312.sHtMl

原标题：文件批量导入导出功能实现
简介：golang 时间轮算法实现延时调度，手写简易时间轮，高并发大量延时任务，降低轮询 CPU 消耗。
 | 原文链接：http://book.sodfth.asia/blog/2274943.sHtMl

原标题：并发数据覆盖加锁安全处理
简介：golang go mod replace 本地模块替换，replace 替换模块为本地目录，修改第三方库本地调试。
 | 原文链接：http://book.sodfth.asia/blog/6726089.sHtMl

原标题：Architecture：静态配置与动态配置架构分离
简介：golang go 锁竞争导致 CPU 飙升，识别锁竞争场景，减少锁粒度，优化并发逻辑降低 CPU 开销。
 | 原文链接：http://book.sodfth.asia/blog/9655059.sHtMl

原标题：Practice：模拟第三方接口超时服务降级验证
简介：前端组件库按需加载性能优化，配置组件库按需引入，避免引入全部组件，减少打包产物体积。
 | 原文链接：http://book.sodfth.asia/blog/3083033.sHtMl

原标题：golang docker compose 部署 minio
简介：golang 开发环境快速搭建指南，快速完成 Golang 开发环境配置，工具链安装，环境变量设置，准备开发。
 | 原文链接：http://book.sodfth.asia/blog/7283054.sHtMl

原标题：性能复盘：锁粒度太大，拆分细粒度锁优化
简介：golang context 取消传播机制，父 ctx 取消，所有派生子 context 全部被取消，理解上下文传播。
 | 原文链接：http://book.sodfth.asia/blog/9655990.sHtMl

原标题：服务健康检查告警监控体系
简介：golang go time 时区数据库内置，go 内置时区数据库，不用系统时区文件，容器时区不依赖系统。
 | 原文链接：http://book.sodfth.asia/blog/0586389.sHtMl

原标题：golang 系统设计压测指标 qps rt 错误率讲解
简介：CLI 批量处理工具文件操作开发，开发命令行批量工具，实现批量文件处理，提升重复文件处理效率。
 | 原文链接：http://book.sodfth.asia/blog/1110676.sHtMl

原标题：golang etcd watch 监听配置变更
简介：nodejs 读取大文件 csv 处理方案，Node 流式读取超大 CSV 文件，逐行解析，避免一次性加载全部文件。
 | 原文链接：http://book.sodfth.asia/blog/2511765.sHtMl

原标题：实战：单元测试+集成测试完整项目落地实践
简介：golang embed 目录读取文件列表，embed 嵌入整个目录，读取目录下全部文件，做静态资源服务。
 | 原文链接：http://book.sodfth.asia/blog/6406985.sHtMl

原标题：Hands‑on：实现WebSocket聊天室完整前后端demo
简介：分布式任务调度集群原型开发，开发简易分布式调度原型，集群多节点运行，保证任务只执行一次。
 | 原文链接：http://book.sodfth.asia/blog/7280502.sHtMl

原标题：golang 分布式 ID 雪花算法实现
简介：数据库连接及时关闭连接泄漏，确保数据库连接使用完毕释放归还连接池，杜绝连接泄漏耗尽连接。
 | 原文链接：http://book.sodfth.asia/blog/7027436.sHtMl

原标题：Practice：JWT工具封装，刷新令牌完整逻辑
简介：golang go 自定义错误类型实现，自定义 error 结构体，携带错误码、堆栈信息，统一业务错误。
 | 原文链接：http://book.sodfth.asia/blog/3169893.sHtMl

原标题：golang 系统设计 protobuf 可选字段使用技巧
简介：golang go 项目 CI github actions 配置，github actions 实现 go 项目 ci，自动测试、代码检查、编译打包镜像。
 | 原文链接：http://book.sodfth.asia/blog/6898122.sHtMl

原标题：消息队列消费堆积扩容处理
简介：golang 故障演练服务模拟超时报错，程序模拟接口超时、报错，做混沌测试验证熔断降级有效性。
 | 原文链接：http://book.sodfth.asia/blog/1230139.sHtMl

原标题：项目依赖安全扫描漏洞防范
简介：分布式事务最终一致性实现，基于可靠消息实现最终一致性，解决跨数据库跨服务业务数据一致性。
 | 原文链接：http://book.sodfth.asia/blog/3283440.sHtMl

原标题：Issue：日志输出包含敏感信息造成泄露风险
简介：golang http client 连接池调优，调优 Go HTTP Client 连接池参数，复用 TCP 连接，减少连接创建开销。
 | 原文链接：http://book.sodfth.asia/blog/9353210.sHtMl

原标题：golang 优雅处理 http 超时设置
简介：golang ctx 传递规则不要存结构体，context 作为函数参数传递，禁止放入结构体字段存储。
 | 原文链接：http://book.sodfth.asia/blog/7673148.sHtMl

原标题：记一次内存Swap被大量使用系统响应缓慢
简介：golang 数据库连接池参数调优详解，最大连接空闲连接最大生命周期，结合业务合理配置避免资源浪费。
 | 原文链接：http://book.sodfth.asia/blog/7423300.sHtMl

原标题：跨平台换行符统一异常修复
简介：golang 结构体深浅拷贝区别实操，区分结构体浅拷贝深拷贝，规避指针引用带来数据意外篡改问题。
 | 原文链接：http://book.sodfth.asia/blog/9779590.sHtMl

原标题：方案对比：同步调用vs异步消息业务选型
简介：Git 代码冲突正确处理方式，讲解冲突产生场景，演示冲突文件修改，正确合并代码，防止代码丢失。
 | 原文链接：http://book.sodfth.asia/blog/2530948.sHtMl

原标题：新手指南：看懂开源项目的Issue与PR
简介：多版本开发环境共存配置，实现同一工具多版本并存，快速切换不同版本，适配不同项目对版本的差异化需求。
 | 原文链接：http://book.sodfth.asia/blog/6873762.sHtMl

原标题：记一次第三方回调IP变动未更新防火墙拦截
简介：service‑worker 离线缓存实践，使用 ServiceWorker 实现静态资源离线缓存，弱网环境页面依然可访问。
 | 原文链接：http://book.sodfth.asia/blog/1874053.sHtMl

原标题：Hands‑on：简易的事件订阅发布组件开发实践
简介：golang e2e 端到端测试 go 接口，编写 e2e 测试，完整模拟用户请求，校验整套业务链路正确性。
 | 原文链接：http://book.sodfth.asia/blog/1694875.sHtMl

三、实战开发｜Practice
原标题：操作系统内核版本适配服务
简介：golang sync.WaitGroup 协程等待控制，WaitGroup 控制一组协程等待全部执行完成，完成批量协程任务调度。
 | 原文链接：http://book.sodfth.asia/blog/1626570.sHtMl

原标题：golang 系统设计链路查询定位慢请求实操技巧
简介：nodejs 项目 pm2 部署运维指南，使用 PM2 管理 Node 服务，进程守护、日志、重启，线上部署运维实操。
 | 原文链接：http://book.sodfth.asia/blog/9477462.sHtMl

原标题：架构复盘：跨机房多活架构基础概念与代价
简介：JSON XML 数据解析处理示例，演示两种格式数据解析与序列化，增加异常捕获，处理格式错乱导致解析失败。
 | 原文链接：http://book.sodfth.asia/blog/2790139.sHtMl

原标题：入门实践：本地简单代理服务搭建
简介：golang rate 令牌桶限流器源码理解，拆解令牌桶限流核心逻辑，理解令牌生成消耗，掌握限流底层原理。
 | 原文链接：http://book.sodfth.asia/blog/4657180.sHtMl

原标题：Hands‑on：简易代理服务器开发实践
简介：golang mysql 长连接检测保活设置，配置 mysql 连接保活检测，剔除失效连接，避免拿到断开无效数据库连接。
 | 原文链接：http://book.sodfth.asia/blog/2629484.sHtMl

原标题：运维笔记：磁盘inode耗尽故障排查处理
简介：golang go 单二进制文件静态编译交叉编译，交叉编译不同操作系统架构二进制文件，实现一次编译多平台运行。
 | 原文链接：http://book.sodfth.asia/blog/7330672.sHtMl

原标题：一次JWT令牌过期时间异常问题复盘
简介：Git 分支管理多人协作实战教程，详解分支创建、合并、冲突处理，适配团队开发场景，规范多人协同代码工作流。
 | 原文链接：http://book.sodfth.asia/blog/3870597.sHtMl

原标题：踩坑：批量MQ消费失败直接无限重试消息爆炸
简介：项目脚手架模板生成工具，搭建项目模板脚手架，一键生成标准化项目骨架，减少重复初始化工作。
 | 原文链接：http://book.sodfth.asia/blog/0990943.sHtMl

原标题：Debug：长连接未设置心跳，连接僵死不回收
简介：golang slice 切片底层原理与坑点，切片扩容、截取、底层数组共享，规避切片修改互相影响数据。
 | 原文链接：http://book.sodfth.asia/blog/6723097.sHtMl

原标题：架构复盘：限流系统架构防止恶意流量冲击
简介：golang panic 崩溃日志完整收集，捕获所有 panic，打印堆栈，记录日志，方便定位崩溃根源。
 | 原文链接：http://book.sodfth.asia/blog/5317867.sHtMl

原标题：踩坑记录：CPU亲和配置不合理多核心负载不均
简介：golang tcp 连接泄露排查定位，netstat 查看连接状态，找出未正常关闭连接，定位连接泄漏代码。
 | 原文链接：http://book.sodfth.asia/blog/9461348.sHtMl

原标题：golang 系统设计测试覆盖率目标合理设定思路
简介：程序性能指标 CPU 内存监控，讲解基础性能指标含义，简单实现监控采集，初步定位程序运行性能瓶颈。
 | 原文链接：http://book.sodfth.asia/blog/5110441.sHtMl

原标题：设计思考：业务埋点架构日志埋点设计原则
简介：golang csv 百万级数据导入数据库，流式读取 csv 分批写入数据库，避免一次性加载全部数据。
 | 原文链接：http://book.sodfth.asia/blog/8246658.sHtMl

原标题：效率笔记：终端开发工具提升日常调试效率
简介：golang 任务失败重试与死信队列，异步任务失败自动重试，超过重试次数进入死信队列人工处理。
 | 原文链接：http://book.sodfth.asia/blog/5337052.sHtMl

原标题：monorepo 项目多包管理最佳实践
简介：golang 分布式 ID 雪花算法实现，Go 实现雪花算法，生成分布式全局唯一 ID，适配分库分表主键。
 | 原文链接：http://book.sodfth.asia/blog/2157208.sHtMl

原标题：开发环境变量配置全平台教程
简介：golang goroutine 泄露检测告警实现，监控 goroutine 数量，突增触发告警，提早发现协程泄露。
 | 原文链接：http://book.sodfth.asia/blog/4974694.sHtMl

原标题：大文件导出内存溢出防护
简介：Nginx 静态代理负载均衡全套配置，一套 Nginx 配置示例，覆盖静态资源、反向代理、负载均衡场景。
 | 原文链接：http://book.sodfth.asia/blog/2034317.sHtMl

原标题：日志敏感信息脱敏泄露防护
简介：Redis 热点 key 拆分降低集群压力，拆分访问量极高的热点 Key，分散请求压力，避免 Redis 节点压力过高。
 | 原文链接：http://book.sodfth.asia/blog/2332049.sHtMl

原标题：避坑：版本升级之后项目直接无法启动
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://book.sodfth.asia/blog/3168348.sHtMl

原标题：golang 系统设计 jwt 安全使用避坑要点
简介：数据库事务 ACID 原理讲解，拆解事务四大特性，理解事务隔离、原子性，明白事务如何保障数据安全。
 | 原文链接：http://book.sodfth.asia/blog/7351661.sHtMl

原标题：Hands‑on：简易图片压缩处理服务demo
简介：golang redis stream 消息队列实战，redis stream 实现可靠消息队列，消费组、ack 确认，消息不丢失。
 | 原文链接：http://book.sodfth.asia/blog/9024313.sHtMl

原标题：数值类型溢出错乱问题修复
简介：golang clickhouse go 客户端数据写入，clickhouse‑go 客户端写入查询，海量时序数据分析业务。
 | 原文链接：http://book.sodfth.asia/blog/6099373.sHtMl

原标题：golang 系统设计指标聚合计算存储选型对比
简介：前端静态缓存更新生效处理，修改静态资源版本标识，处理浏览器强缓存，让更新资源生效。
 | 原文链接：http://book.sodfth.asia/blog/0517200.sHtMl

原标题：golang redis 大 key 识别处理方案
简介：golang go decimal 定点小数金额计算，decimal 库处理金额，规避 float64 精度丢失，财务计算。
 | 原文链接：http://book.sodfth.asia/blog/1506145.sHtMl

原标题：golang prometheus counter gauge 使用
简介：golang 数据库连接池参数调优详解，最大连接空闲连接最大生命周期，结合业务合理配置避免资源浪费。
 | 原文链接：http://book.sodfth.asia/blog/3795141.sHtMl

原标题：golang redis zset 延时队列实现
简介：golang redis 客户端业务使用，Go Redis 客户端对接，实现缓存、计数器，适配各类 Redis 业务场景。
 | 原文链接：http://book.sodfth.asia/blog/6163662.sHtMl

原标题：golang 系统设计防爬虫简单策略
简介：golang 大文件读取内存优化，Go 流式读取大文件，分块处理，避免大文件一次性加载全部到内存。
 | 原文链接：http://book.sodfth.asia/blog/8642838.sHtMl

原标题：golang 系统设计多级缓存架构落地
简介：golang 负载均衡轮询加权轮询实现，手写负载均衡算法，轮询、加权轮询分发请求到后端节点。
 | 原文链接：http://book.sodfth.asia/blog/7859164.sHtMl

原标题：golang kafka offset 提交策略
简介：集成测试业务流程编写示例，编写业务流程集成测试，覆盖完整业务链路，验证模块之间协同工作是否正常。
 | 原文链接：http://book.sodfth.asia/blog/8546122.sHtMl

原标题：golang 优雅处理 http 超时设置
简介：线上接口超时故障排查思路，从网络、数据库、代码逻辑逐层排查接口超时，定位慢请求根因。
 | 原文链接：http://book.sodfth.asia/blog/2166732.sHtMl

原标题：踩坑：大报文传输，RPC消息超过大小限制
简介：golang 文件上传下载接口开发，Go 开发文件上传下载接口，校验文件，处理文件读写存储逻辑。
 | 原文链接：http://book.sodfth.asia/blog/3159886.sHtMl

原标题：Issue：浏览器缓存ServiceWorker导致旧页面常驻
简介：接口压测定位系统性能瓶颈，使用压测工具对接口施压，观察指标，定位系统性能瓶颈点。
 | 原文链接：http://book.sodfth.asia/blog/1341536.sHtMl

原标题：性能笔记：DNS缓存优化减少域名解析开销
简介：golang 环境变量读取与类型转换，读取系统环境变量，做类型转换默认值处理，适配多环境部署。
 | 原文链接：http://book.sodfth.asia/blog/4027432.sHtMl

原标题：业务接口幂等完整落地案例
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：http://book.sodfth.asia/blog/4982315.sHtMl

原标题：项目实践：接口压测，逐步加压观察系统表现
简介：golang net.Listener 包装自定义监听器，包装 Listener 做连接计数、连接拦截，扩展网络能力。
 | 原文链接：http://book.sodfth.asia/blog/6775380.sHtMl

原标题：性能笔记：TCP参数内核调优服务高并发场景
简介：golang uuid 生成多种版本实现，生成 uuid v1 v4，生成唯一标识，业务用于单据编号场景。
 | 原文链接：http://book.sodfth.asia/blog/4320243.sHtMl

原标题：部署复盘：静态站点部署CDN完整流程
简介：前端水印防信息泄露实现，实现网页水印功能，页面叠加用户信息水印，防止页面截图信息外泄。
 | 原文链接：http://book.sodfth.asia/blog/0868163.sHtMl

原标题：Issue：Docker网络模式选择错误容器互通失败
简介：golang defer 执行顺序与坑点，defer 后进先出，循环内部 defer 陷阱，资源释放正确写法。
 | 原文链接：http://book.sodfth.asia/blog/2928094.sHtMl

原标题：Shell 运维脚本服务器效率提升
简介：golang gin 框架接口开发实战，Gin 框架搭建 HTTP 服务，开发增删改查接口，快速完成后端接口开发。
 | 原文链接：http://book.sodfth.asia/blog/9463052.sHtMl

原标题：nestjs 框架模块化项目搭建
简介：golang 响应 body 流式返回大数据，http 流式输出数据，边生成边返回，无需在内存组装完整返回结果。
 | 原文链接：http://book.sodfth.asia/blog/7242533.sHtMl

四、架构设计｜Architecture
原标题：Git 标签版本标记发布管理
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://book.sodfth.asia/blog/4931909.sHtMl

原标题：部署复盘：服务启动顺序依赖处理方案
简介：日志驱动异常日志不输出修复，排查日志驱动配置，修复日志写入配置，恢复程序正常日志输出。
 | 原文链接：http://book.sodfth.asia/blog/2387132.sHtMl

原标题：提交第一个开源 PR 完整流程
简介：golang goroutine 协程基础实操，Goroutine 基础实操案例，启动协程执行任务，理解轻量级协程特性。
 | 原文链接：http://book.sodfth.asia/blog/7161722.sHtMl

原标题：数据库排序规则统一结果一致
简介：golang go http 服务器优雅关闭完整代码，http.Server Shutdown，等待现有请求处理完成关闭服务。
 | 原文链接：http://book.sodfth.asia/blog/1406674.sHtMl

原标题：golang 系统设计数据库扩容几种方式
简介：golang rsa 签名验签 pem 证书加载，加载 pem 格式密钥证书，rsa 签名与验签完整业务实现。
 | 原文链接：http://book.sodfth.asia/blog/0533157.sHtMl

原标题：开源实践：Fork上游项目，持续同步更新代码
简介：时间精度统一业务判断修复，统一业务使用时间戳精度，毫秒秒区分清楚，修复时间判断逻辑错误。
 | 原文链接：http://book.sodfth.asia/blog/8219960.sHtMl

原标题：实战项目：搭建本地Mock服务快速开发联调
简介：golang mongodb 索引优化慢查询处理，mongodb 创建索引，分析慢查询，优化聚合查询执行性能。
 | 原文链接：http://book.sodfth.asia/blog/7814788.sHtMl

原标题：OpenAPI 自动接口文档生成
简介：golang 数据库连接池泄露检测逻辑，监控连接池状态，检测连接长时间未归还，告警连接泄漏问题。
 | 原文链接：http://book.sodfth.asia/blog/5378625.sHtMl

原标题：Git 误提交撤销回退实操教程
简介：线程池拒绝策略任务丢失防护，合理设置线程池拒绝策略，处理任务队列满场景，避免业务任务直接丢失。
 | 原文链接：http://book.sodfth.asia/blog/1216484.sHtMl

原标题：nestjs 框架模块化项目搭建
简介：服务器时钟同步任务错乱修复，配置服务器 NTP 时间同步，保证集群所有机器时间保持一致。
 | 原文链接：http://book.sodfth.asia/blog/0060403.sHtMl

原标题：golang 系统设计缓存一致性方案对比
简介：golang go 运行时获取编译信息，程序内部读取编译时间 git 版本，接口输出程序版本信息。
 | 原文链接：http://book.sodfth.asia/blog/3874959.sHtMl

原标题：方案对比：几种任务队列架构选型优缺点
简介：日志切割配置防止日志丢失，配置日志切割轮转策略，日志按大小时间切割，防止日志文件丢失。
 | 原文链接：http://book.sodfth.asia/blog/0711020.sHtMl

原标题：golang 系统设计日志本地打印线上关闭调试信息
简介：golang interface 接口使用避坑，interface 判 nil 坑点，理解接口底层结构，避免判空逻辑失效。
 | 原文链接：http://book.sodfth.asia/blog/5916247.sHtMl

原标题：nodejs 全局异常捕获进程防护
简介：golang context 取消传播机制，父 ctx 取消，所有派生子 context 全部被取消，理解上下文传播。
 | 原文链接：http://book.sodfth.asia/blog/0802735.sHtMl

原标题：golang k8s hpa 水平 pod 自动扩缩容
简介：nodejs 内存溢出问题排查修复，Node.js 程序 OOM 排查流程，定位内存泄露，调整内存限制修复崩溃。
 | 原文链接：http://book.sodfth.asia/blog/9214247.sHtMl

原标题：golang docker 部署 redis 配置要点
简介：golang tcp_NODELAY 关闭延迟发送，设置 tcp_NODELAY，关闭 Nagle 算法，降低小包请求延迟。
 | 原文链接：http://book.sodfth.asia/blog/5561425.sHtMl

原标题：开源项目构建失败排查步骤
简介：调试工具断点调试变量查看技巧，演示断点设置、变量监视、调用栈查看，借助调试工具高效排查业务逻辑错误。
 | 原文链接：http://book.sodfth.asia/blog/5742211.sHtMl

原标题：方案对比：同步调用vs异步消息业务选型
简介：golang 本地消息表实现最终一致性，本地消息表 + 定时任务轮询，可靠消息实现分布式事务。
 | 原文链接：http://book.sodfth.asia/blog/5178615.sHtMl

?
