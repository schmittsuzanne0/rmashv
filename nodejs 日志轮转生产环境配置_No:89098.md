最新前沿技术资讯

一、入门教程｜Getting Started
原标题：nodejs 日志轮转生产环境配置
简介：配置与镜像分离防止信息泄露，业务配置不打包进镜像，外部挂载配置，避免密钥配置随镜像泄露。
 | 原文链接：http://wiki.5mcbj6.asia/arts/529218.Doc

原标题：操作系统内核版本适配服务
简介：开发生产环境资源路径统一，对齐开发环境与生产环境资源路径，防止本地正常上线后资源找不到。
 | 原文链接：http://wiki.5mcbj6.asia/arts/701685.Doc

原标题：GitHub Markdown 文档语法汇总
简介：服务熔断防止故障级联传播，实现服务熔断逻辑，下游故障时快速失败，阻止故障向上游链式扩散。
 | 原文链接：http://wiki.5mcbj6.asia/arts/455555.Doc

原标题：防火墙 IP 白名单回调接口放行
简介：golang 熔断降级简易组件开发，Go 简易熔断组件，下游故障触发熔断，保护上游服务不被拖垮。
 | 原文链接：http://wiki.5mcbj6.asia/arts/826518.Doc

原标题：静态博客部署 GitHub Pages 教程
简介：MySQL 慢查询索引优化实战，抓取慢查询 SQL，分析执行计划，新增或者调整索引，提升 SQL 执行速度。
 | 原文链接：http://wiki.5mcbj6.asia/arts/481352.Doc

原标题：golang 系统设计代码评审关注点 checklist 清单
简介：golang go time 时区数据库内置，go 内置时区数据库，不用系统时区文件，容器时区不依赖系统。
 | 原文链接：http://wiki.5mcbj6.asia/arts/319778.Doc

原标题：golang 配置文件多环境加载
简介：golang 时间戳秒毫秒纳秒转换，Unix UnixMilli UnixNano 互相转换，区分单位避免时间逻辑 bug。
 | 原文链接：http://wiki.5mcbj6.asia/arts/536087.Doc

原标题：nodejs 中间件模式原理剖析
简介：golang context.WithCancel 手动取消上下文，WithCancel 生成可取消 ctx，手动调用 cancel 触发取消。
 | 原文链接：http://wiki.5mcbj6.asia/arts/023406.Doc

原标题：Practice：实现防爬虫简单拦截中间件实践
简介：golang go mod graph 查看依赖关系，go mod graph 打印依赖树，定位间接依赖来源，解决版本冲突。
 | 原文链接：http://wiki.5mcbj6.asia/arts/715436.Doc

原标题：架构复盘：热点数据防护架构防止节点过载
简介：golang os.Exit 退出程序注意 defer 不执行，os.Exit 会直接退出，不会执行 defer，优雅退出不要直接 os.Exit。
 | 原文链接：http://wiki.5mcbj6.asia/arts/237743.Doc

原标题：部署实践：内网开发环境代理配置实践
简介：golang 数据库慢查询监控实现，Go 封装 SQL 执行监控，记录慢 SQL，上报日志，发现数据库性能问题。
 | 原文链接：http://wiki.5mcbj6.asia/arts/590958.Doc

原标题：部署实践：容器时区统一配置解决方案
简介：golang go 防止路径穿越攻击，文件操作校验路径，拒绝../ 路径穿越，禁止访问系统任意文件。
 | 原文链接：http://wiki.5mcbj6.asia/arts/075803.Doc

原标题：Git 子模块更新代码不全修复
简介：golang panic 崩溃日志完整收集，捕获所有 panic，打印堆栈，记录日志，方便定位崩溃根源。
 | 原文链接：http://wiki.5mcbj6.asia/arts/116458.Doc

原标题：nodejs 内存溢出问题排查修复
简介：golang 定时任务 cron 使用指南，Go 使用 Cron 库实现定时任务，配置 corn 表达式调度业务任务。
 | 原文链接：http://wiki.5mcbj6.asia/arts/440525.Doc

原标题：golang 系统设计缓存更新策略 cache aside 讲解
简介：golang 程序崩溃 core dump 生成调试，开启 core dump，程序崩溃生成转储文件，事后分析崩溃原因。
 | 原文链接：http://wiki.5mcbj6.asia/arts/678539.Doc

原标题：golang 系统设计令牌桶漏桶算法对比
简介：nodejs 消息队列消费服务开发，Node 开发消息队列消费端，监听队列消息执行业务逻辑，异步解耦业务。
 | 原文链接：http://wiki.5mcbj6.asia/arts/941398.Doc

原标题：设计思考：系统限流熔断降级完整防护体系
简介：nodejs 单元测试 jest 实操教程，Jest 单元测试实操，编写测试用例，mock 依赖，验证业务逻辑正确性。
 | 原文链接：http://wiki.5mcbj6.asia/arts/208653.Doc

原标题：golang 数据库批量更新性能优化
简介：本地运行正常线上报错排查，对比本地与线上环境差异，从配置、系统版本、文件权限定位线上独有的 bug。
 | 原文链接：http://wiki.5mcbj6.asia/arts/683560.Doc

原标题：项目实践：本地模拟缓存失效风暴验证防护
简介：线程池拒绝策略任务丢失防护，合理设置线程池拒绝策略，处理任务队列满场景，避免业务任务直接丢失。
 | 原文链接：http://wiki.5mcbj6.asia/arts/456981.Doc

原标题：nodejs 项目 pm2 部署运维指南
简介：提交第一个开源 PR 完整流程，Fork 项目、修改代码、提交 Pull Request，讲解 PR 规范，提升合并通过率。
 | 原文链接：http://wiki.5mcbj6.asia/arts/975111.Doc

原标题：golang redis 缓存雪崩完整处理
简介：golang yaml 解析配置加载实操，Go 解析 YAML 配置文件，读取配置参数，驱动业务运行。
 | 原文链接：http://wiki.5mcbj6.asia/arts/776089.Doc

原标题：golang 系统设计开源 pr 评审合并流程实操
简介：内网 DNS 不稳定随机报错排查，定位内网 DNS 抖动问题，配置备选 DNS，解决偶现域名解析失败。
 | 原文链接：http://wiki.5mcbj6.asia/arts/031241.Doc

原标题：数据库读写分离性能优化
简介：全局异常处理器接口返回统一，接入全局异常捕获，拦截业务全部异常，对外输出统一格式返回值。
 | 原文链接：http://wiki.5mcbj6.asia/arts/709829.Doc

原标题：入门实践：简单数据脱敏处理示例
简介：golang go‑zero 监控指标埋点，go‑zero 内置 metrics 监控，上报业务指标对接监控平台。
 | 原文链接：http://wiki.5mcbj6.asia/arts/477180.Doc

原标题：golang mongodb 聚合管道实操案例
简介：golang sql 注入风险规避要点，参数化查询杜绝 sql 注入，禁止字符串拼接 SQL 语句执行。
 | 原文链接：http://wiki.5mcbj6.asia/arts/785399.Doc

原标题：踩坑：幂等键生成逻辑错误造成重复业务
简介：golang 接口返回统一封装工具，封装 Go 接口统一返回工具，标准化成功失败返回结构体。
 | 原文链接：http://wiki.5mcbj6.asia/arts/637321.Doc

原标题：Hands‑on：手写简单RPC框架基础通信版本
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://wiki.5mcbj6.asia/arts/063286.Doc

原标题：golang redis 布隆过滤器安装使用
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://wiki.5mcbj6.asia/arts/269713.Doc

原标题：实战项目：搭建私有Docker镜像仓库本地实践
简介：golang 僵尸进程处理 go 程序，正确等待子进程退出，避免产生僵尸进程，占用系统进程表。
 | 原文链接：http://wiki.5mcbj6.asia/arts/821453.Doc

原标题：开发记录：JWT过期刷新滑动过期实现实践
简介：golang go 时间 time.Timer time.Ticker，定时器与周期定时器，Stop Reset 正确使用，防止资源泄漏。
 | 原文链接：http://wiki.5mcbj6.asia/arts/956650.Doc

原标题：优化实践：LRU本地缓存优化热点访问性能
简介：golang nil channel 阻塞特性，nil channel 读写永久阻塞，理解 nil channel 行为做逻辑控制。
 | 原文链接：http://wiki.5mcbj6.asia/arts/991829.Doc

原标题：安全笔记：依赖包漏洞检测供应链安全
简介：golang benchmark 减少测试干扰，benchmark 执行循环 b.N，避免循环内部做非被测逻辑干扰结果。
 | 原文链接：http://wiki.5mcbj6.asia/arts/547156.Doc

原标题：golang es bool 查询条件组合技巧
简介：golang 数据库连接耗尽排查思路，监控连接池状态，定位连接未归还，解决连接耗尽报错。
 | 原文链接：http://wiki.5mcbj6.asia/arts/074541.Doc

原标题：golang 简单爬虫请求防封禁
简介：灰度发布策略服务平滑升级，实现灰度发布逻辑，流量逐步切到新版本，出现问题快速回滚旧版本。
 | 原文链接：http://wiki.5mcbj6.asia/arts/753684.Doc

原标题：golang github actions 多平台构建
简介：浏览器内存泄漏排查前端页面，梳理前端页面内存泄漏场景，讲解排查手段，修复页面内存持续上涨。
 | 原文链接：http://wiki.5mcbj6.asia/arts/340957.Doc

原标题：架构笔记：分布式事务方案对比与业务取舍
简介：golang http 重定向策略自定义，CheckRedirect 自定义重定向逻辑，限制重定向次数，防止死循环。
 | 原文链接：http://wiki.5mcbj6.asia/arts/210990.Doc

原标题：nestjs 权限守卫鉴权实现方案
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：http://wiki.5mcbj6.asia/arts/455750.Doc

原标题：数据库分表存储大表优化方案
简介：golang viper 多源配置管理实操，viper 读取配置文件环境变量命令行参数，多源配置优先级管理。
 | 原文链接：http://wiki.5mcbj6.asia/arts/412001.Doc

原标题：优化实践：内存池思想减少频繁分配释放
简介：TLS 版本兼容 HTTPS 握手失败，兼容老旧 TLS 协议版本，修复部分客户端 HTTPS 握手失败无法访问。
 | 原文链接：http://wiki.5mcbj6.asia/arts/587942.Doc

原标题：编译打包产物依赖分析解读
简介：极简方式搭建个人技术文档站点，使用轻量化工具快速部署文档站点，支持 markdown 编写，实现知识沉淀与对外分享。
 | 原文链接：http://wiki.5mcbj6.asia/arts/670886.Doc


二、踩坑排错｜Troubleshooting
原标题：golang 系统设计定时任务动态启停配置方案
简介：golang 协程数量监控统计方案，统计运行中 goroutine 数量，监控协程泄露，协程数量异常及时告警。
 | 原文链接：http://wiki.5mcbj6.asia/arts/281404.Doc

原标题：性能复盘：系统上下文切换过高性能下降调优
简介：golang 响应 body 流式返回大数据，http 流式输出数据，边生成边返回，无需在内存组装完整返回结果。
 | 原文链接：http://wiki.5mcbj6.asia/arts/649618.Doc

原标题：Docker 容器入门镜像实操教程
简介：vite 项目配置与构建提速技巧，讲解 vite 配置优化手段，提升开发热更新速度与生产构建打包效率。
 | 原文链接：http://wiki.5mcbj6.asia/arts/993074.Doc

原标题：正则表达式文本处理实战案例
简介：golang redis pipeline 批量操作，使用 Redis Pipeline 批量执行多条命令，减少网络往返，提升批量操作性能。
 | 原文链接：http://wiki.5mcbj6.asia/arts/069197.Doc

原标题：项目实践：搭建监控大盘查看系统关键指标
简介：golang bcrypt 密码哈希加密存储，bcrypt 做用户密码哈希，加盐存储密码，保障用户密码安全。
 | 原文链接：http://wiki.5mcbj6.asia/arts/892606.Doc

原标题：方案对比：同步调用vs异步消息业务选型
简介：浏览器缓存强制刷新方案，设置 HTTP 缓存头，处理浏览器缓存旧静态资源，让用户加载更新后的页面。
 | 原文链接：http://wiki.5mcbj6.asia/arts/579562.Doc

原标题：实战项目：本地搭建Prometheus监控完整demo
简介：golang net.Conn 包装自定义连接，包装 net.Conn，统计读写字节，日志打印，超时控制。
 | 原文链接：http://wiki.5mcbj6.asia/arts/121781.Doc

原标题：golang viper 配置热更新实操
简介：golang 项目 go mod 依赖管理，Go Mod 管理项目依赖，下载、升级、清理依赖，解决依赖版本管理。
 | 原文链接：http://wiki.5mcbj6.asia/arts/769031.Doc

原标题：开源实践：开源项目本地调试构建排坑经验
简介：golang 微服务网关简易实现，http 反向代理、路由匹配、鉴权限流，理解网关核心原理。
 | 原文链接：http://wiki.5mcbj6.asia/arts/295697.Doc

原标题：golang 系统设计单元测试表驱动测试 table‑driven
简介：golang cgo 调用 C 语言代码示例，cgo 调用 C 函数，go 与 C 互相调用，对接 C 语言库能力。
 | 原文链接：http://wiki.5mcbj6.asia/arts/270951.Doc

原标题：调优方案：Nginx性能参数调优高并发配置
简介：echarts 大数据渲染性能调优，大数据量 ECharts 图表调优，数据采样、分片渲染，解决图表卡顿。
 | 原文链接：http://wiki.5mcbj6.asia/arts/342096.Doc

原标题：项目实践：OpenTelemetry链路追踪本地部署实践
简介：golang go 并发模式 fan‑out fan‑in，fanout 分发任务 fanin 汇总结果，多协程并发处理任务。
 | 原文链接：http://wiki.5mcbj6.asia/arts/372357.Doc

原标题：OpenSource：大型仓库Git历史清理瘦身实操
简介：前端工程化 webpack 打包优化，针对 webpack 项目做打包调优，分包、压缩、Tree‑Shaking，缩减包体积。
 | 原文链接：http://wiki.5mcbj6.asia/arts/129142.Doc

原标题：golang 数据库慢查询监控实现
简介：golang udp 服务端客户端开发示例，golang 实现 UDP 服务收发数据包，实现 udp 协议通信程序。
 | 原文链接：http://wiki.5mcbj6.asia/arts/742052.Doc

原标题：手写简易 MQ 理解消息存储消费
简介：golang make new 关键字使用区别，分清 new 与 make 适用类型，正确初始化切片 map 通道，杜绝 nil 引发 panic。
 | 原文链接：http://wiki.5mcbj6.asia/arts/060926.Doc

原标题：实践：API版本控制多种策略落地对比实践
简介：golang lru 缓存淘汰算法编写，手写 LRU 缓存淘汰算法，实现本地缓存，淘汰最久未使用数据。
 | 原文链接：http://wiki.5mcbj6.asia/arts/417690.Doc

原标题：golang 消息死信处理业务逻辑
简介：golang nil channel 阻塞特性，nil channel 读写永久阻塞，理解 nil channel 行为做逻辑控制。
 | 原文链接：http://wiki.5mcbj6.asia/arts/387240.Doc

原标题：实战：多版本SDK兼容业务改造实践
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://wiki.5mcbj6.asia/arts/509387.Doc

原标题：golang 系统设计依赖漏洞扫描修复流程
简介：golang go 程序 CPU 占用高定位步骤，pprof 定位热点函数，分析 CPU 高占用，优化耗时代码逻辑。
 | 原文链接：http://wiki.5mcbj6.asia/arts/187695.Doc

原标题：express 中间件开发业务实践
简介：golang excel 生成导出高性能方案，excelize 流式生成 excel，百万行数据导出，规避内存溢出。
 | 原文链接：http://wiki.5mcbj6.asia/arts/134073.Doc

原标题：golang 日志与链路 ID 关联打印
简介：golang 图片处理 go 图片裁剪压缩，golang 图像处理库，图片缩放裁剪水印，服务端图片处理。
 | 原文链接：http://wiki.5mcbj6.asia/arts/748555.Doc

原标题：golang k8s 命名空间资源隔离方案
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://wiki.5mcbj6.asia/arts/653861.Doc

原标题：部署实践：多实例服务部署无状态改造
简介：RPC 报文大小上限调优大请求，调大 RPC 框架报文最大限制，支持传输大体积请求报文不被截断。
 | 原文链接：http://wiki.5mcbj6.asia/arts/148653.Doc

原标题：新手指南：本地多版本环境共存配置
简介：golang go1.18 + 泛型基础实操，go 泛型基础语法，泛型函数泛型类型，实现通用工具函数。
 | 原文链接：http://wiki.5mcbj6.asia/arts/354425.Doc

原标题：eslint prettier 代码规范落地
简介：golang grpc keepalive 保活配置，grpc keepalive 参数调优，检测断开僵死连接，释放无效连接资源。
 | 原文链接：http://wiki.5mcbj6.asia/arts/734314.Doc

原标题：golang 分布式上下文传递方案
简介：golang base64 编码解码实操，Go Base64 编码解码示例，处理业务场景 Base64 格式数据转换。
 | 原文链接：http://wiki.5mcbj6.asia/arts/855040.Doc

原标题：Troubleshoot：跨域偶现失败难以复现问题
简介：golang sync.Mutex 互斥锁正确模式，互斥锁 defer Unlock，锁粒度控制，避免锁范围过大。
 | 原文链接：http://wiki.5mcbj6.asia/arts/339667.Doc

原标题：golang 系统设计缓存 key 淘汰雪崩防护思路
简介：系统时间同步定时任务偏移，同步服务器系统时间，防止时间偏移，避免定时任务执行时间错乱。
 | 原文链接：http://wiki.5mcbj6.asia/arts/234622.Doc

原标题：项目语义化版本号规范管理
简介：golang wasm webassembly go 编译，go 编译为 wasm，浏览器执行 go 代码，拓展 go 运行场景。
 | 原文链接：http://wiki.5mcbj6.asia/arts/496101.Doc

原标题：安全实践：请求输入校验防御恶意参数
简介：golang prometheus 指标埋点开发，业务埋点计数器、仪表盘、直方图，对接 prometheus 采集监控指标。
 | 原文链接：http://wiki.5mcbj6.asia/arts/041223.Doc

原标题：请求重试组件退避策略实现
简介：golang go 信号处理优雅重启实现，USR2 触发程序重启，不关闭监听 socket 实现零停机升级。
 | 原文链接：http://wiki.5mcbj6.asia/arts/484294.Doc

原标题：部署实践：数据库迁移脚本版本管理实践
简介：接口幂等性防重复请求实现，实现接口幂等逻辑，避免重复提交请求产生多条脏数据，保障业务数据安全。
 | 原文链接：http://wiki.5mcbj6.asia/arts/525923.Doc

原标题：入门实践：简单批量处理脚本编写
简介：文件描述符优化进程卡死修复，及时关闭文件句柄，控制打开文件数量，解决文件句柄耗尽进程卡死。
 | 原文链接：http://wiki.5mcbj6.asia/arts/411181.Doc

原标题：部署实践：DockerCompose管理多服务环境
简介：golang context.Background 与 TODO 区别，Background 主流程根上下文，TODO 不确定用哪个上下文时使用。
 | 原文链接：http://wiki.5mcbj6.asia/arts/493066.Doc

原标题：部署实践：Nginx反向代理传递真实客户端IP
简介：Git 混乱提交历史清理方法，针对杂乱的提交记录，使用 Git 工具整理，清理无效提交，还原整洁版本历史。
 | 原文链接：http://wiki.5mcbj6.asia/arts/035331.Doc

原标题：golang 系统设计日志采样降低存储开销方案
简介：Redis 分布式锁高并发安全实现，基于 Redis 实现分布式锁，处理锁过期、续期，保障集群并发安全。
 | 原文链接：http://wiki.5mcbj6.asia/arts/165409.Doc

原标题：本地运行正常线上报错排查
简介：golang 信号捕获程序退出处理，Go 捕获操作系统信号，做资源回收，控制程序退出流程。
 | 原文链接：http://wiki.5mcbj6.asia/arts/120692.Doc

原标题：架构复盘：RPC框架架构超时重试设计要点
简介：nodejs jwt 登录鉴权完整示例，Node 实现 JWT 登录鉴权，登录签发令牌，接口校验令牌身份。
 | 原文链接：http://wiki.5mcbj6.asia/arts/738658.Doc

原标题：golang 系统设计数据库基准压测简单思路
简介：golang go 泛型约束与类型集合，泛型 type set 约束，限制泛型支持类型，写出安全泛型代码。
 | 原文链接：http://wiki.5mcbj6.asia/arts/483818.Doc

原标题：golang cpu pprof 性能分析实操
简介：golang toml 配置文件解析教程，Go 解析 Toml 格式配置，适用于项目配置管理场景。
 | 原文链接：http://wiki.5mcbj6.asia/arts/458022.Doc

三、实战开发｜Practice
原标题：golang websocket 消息广播实现
简介：golang channel 作为函数参数方向，声明 channel 入参方向，只读 channel 只写 channel 提升代码约束。
 | 原文链接：http://wiki.5mcbj6.asia/arts/234359.Doc

原标题：开发记录：业务错误告警邮件通知组件实践
简介：golang base64 大文件流式编解码，大文件流式 base64 转换，不用一次性加载全部文件进入内存。
 | 原文链接：http://wiki.5mcbj6.asia/arts/916657.Doc

原标题：golang 系统设计本地缓存与分布式缓存
简介：golang go 泛型使用避坑注意点，泛型与 interface 区别，泛型性能，什么时候适合使用泛型。
 | 原文链接：http://wiki.5mcbj6.asia/arts/169232.Doc

原标题：golang 链路 traceId 透传中间件
简介：golang 集成测试测试数据库回滚，集成测试结束自动回滚数据库，不污染测试环境数据。
 | 原文链接：http://wiki.5mcbj6.asia/arts/567713.Doc

原标题：Architecture：对象存储接入业务整体架构
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://wiki.5mcbj6.asia/arts/315086.Doc

原标题：Architecture：BFF后端聚合层架构适用场景
简介：golang 重试退避机制代码实现，Go 实现请求重试与指数退避，处理临时故障，提升调用稳定性。
 | 原文链接：http://wiki.5mcbj6.asia/arts/920731.Doc

原标题：golang 系统设计短链接服务实现思路
简介：图片上传预览格式大小处理，实现图片上传接口，校验文件格式、大小，完成上传后预览处理。
 | 原文链接：http://wiki.5mcbj6.asia/arts/151753.Doc

原标题：项目实践：Docker多环境镜像构建策略实践
简介：Git 标签版本标记发布管理，使用 Git 标签标记项目版本，打标签推送远程，用于版本发布、版本回溯。
 | 原文链接：http://wiki.5mcbj6.asia/arts/787980.Doc

原标题：踩坑：重试逻辑未做幂等，重复生成业务数据
简介：golang hmac 签名生成校验示例，hmac 生成消息签名，做接口请求签名，校验数据不被篡改。
 | 原文链接：http://wiki.5mcbj6.asia/arts/728124.Doc

原标题：架构复盘：服务优雅停机架构设计资源释放
简介：golang rsa 公钥加密私钥解密，rsa 非对称加密，大文件分块加密，处理非对称加密长度限制。
 | 原文链接：http://wiki.5mcbj6.asia/arts/529814.Doc

原标题：极简方式搭建个人技术文档站点
简介：golang 本地消息表实现最终一致性，本地消息表 + 定时任务轮询，可靠消息实现分布式事务。
 | 原文链接：http://wiki.5mcbj6.asia/arts/197358.Doc

原标题：golang 系统设计故障演练简单落地思路方法论
简介：golang go 逃逸分析实操查看，go build‑gcflags=-m 查看逃逸分析，减少堆分配优化程序性能。
 | 原文链接：http://wiki.5mcbj6.asia/arts/409039.Doc

原标题：优化实践：Redis管道、批量命令减少网络往返
简介：单元测试用例编写入门实操，讲解测试用例设计思路，演示基础单元测试代码，提升代码健壮性，提前发现逻辑 bug。
 | 原文链接：http://wiki.5mcbj6.asia/arts/043635.Doc

原标题：优化实践：分页查询性能优化解决offset问题
简介：Git 分支切换合并删除完整操作，实操分支全生命周期操作，包含切换、合并、删除，熟悉日常开发分支处理流程。
 | 原文链接：http://wiki.5mcbj6.asia/arts/086869.Doc

原标题：消息队列消费堆积扩容处理
简介：服务器 Swap 关闭提升响应速度，关闭服务器 Swap 交换分区，避免内存交换磁盘拖慢程序响应性能。
 | 原文链接：http://wiki.5mcbj6.asia/arts/033226.Doc

原标题：Performance：后端接口性能优化完整分析流程
简介：Dockerfile 编写容器打包实战，讲解 Dockerfile 指令含义，编写镜像构建脚本，将本地项目打包成可分发容器镜像。
 | 原文链接：http://wiki.5mcbj6.asia/arts/154297.Doc

原标题：Hands‑on：编写自定义Git钩子实现代码提交校验
简介：网关集成鉴权限流日志一体化，在网关层整合鉴权、限流、请求日志，统一对入口请求做管控处理。
 | 原文链接：http://wiki.5mcbj6.asia/arts/168224.Doc

原标题：Shell 脚本自动化命令编写
简介：golang go select 多路等待 channel，select 等待多个 channel，default 非阻塞，超时等待 channel。
 | 原文链接：http://wiki.5mcbj6.asia/arts/786877.Doc

原标题：GitHub 项目提交推送完整流程讲解
简介：golang defer panic 异常处理，理解 defer 延迟执行，panic 恐慌捕获，实现函数资源释放异常保护。
 | 原文链接：http://wiki.5mcbj6.asia/arts/995170.Doc

原标题：Architecture：API网关核心能力与组件拆分
简介：golang bytes.Buffer 字节缓冲区使用，bytes.Buffer 字节内存缓冲区，拼接字节，避免频繁内存分配。
 | 原文链接：http://wiki.5mcbj6.asia/arts/123665.Doc

原标题：方案设计：统一ID生成服务架构对比雪花算法
简介：CLI 工具进度条交互效果开发，在命令行工具增加进度条展示，直观反馈任务执行进度，优化命令行体验。
 | 原文链接：http://wiki.5mcbj6.asia/arts/930991.Doc

原标题：架构复盘：分表扩容架构平滑迁移思路
简介：WebSocket 断线重连稳定优化，增加 WebSocket 断线自动重连逻辑，处理网络抖动，维持长连接稳定。
 | 原文链接：http://wiki.5mcbj6.asia/arts/678211.Doc

原标题：调优方案：gzip压缩开启降低网络传输体积
简介：golang 分布式锁 redis 实现，基于 Redis 实现 Go 分布式锁，解决多实例并发竞争资源问题。
 | 原文链接：http://wiki.5mcbj6.asia/arts/977624.Doc

原标题：安全复盘：OAuth2授权流程安全坑点汇总
简介：golang nilnil interface 陷阱复现，interface 包含类型不为 nil 值为 nil，判 ==nil 返回 false 经典坑。
 | 原文链接：http://wiki.5mcbj6.asia/arts/315353.Doc

原标题：Architecture：BFF后端聚合层架构适用场景
简介：golang base64 大文件流式编解码，大文件流式 base64 转换，不用一次性加载全部文件进入内存。
 | 原文链接：http://wiki.5mcbj6.asia/arts/688258.Doc

原标题：golang ip 限流黑名单实现方案
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://wiki.5mcbj6.asia/arts/537598.Doc

原标题：性能笔记：HTTP连接复用性能优化实践
简介：golang 参数校验业务接口处理，Go 接口入参参数校验，拦截非法入参，减少业务层参数判断代码。
 | 原文链接：http://wiki.5mcbj6.asia/arts/129443.Doc

原标题：CI 持续集成自动构建流程
简介：golang go 泛型实现通用数据结构，泛型实现通用栈队列，复用逻辑支持多种数据类型。
 | 原文链接：http://wiki.5mcbj6.asia/arts/092666.Doc

原标题：坑点：缓存过期策略不当引发业务异常
简介：Git 分支管理多人协作实战教程，详解分支创建、合并、冲突处理，适配团队开发场景，规范多人协同代码工作流。
 | 原文链接：http://wiki.5mcbj6.asia/arts/699797.Doc

原标题：golang 系统设计线上 ddl 变更安全执行思路
简介：golang go ring 环形容器循环队列，ring 环形链表实现循环队列，环形缓冲区业务场景。
 | 原文链接：http://wiki.5mcbj6.asia/arts/611694.Doc

原标题：vue pinia 状态管理实战教程
简介：前后端会话登录状态持久化，实现登录状态持久存储，重启服务登录状态不丢失，保障会话稳定性。
 | 原文链接：http://wiki.5mcbj6.asia/arts/635776.Doc

原标题：极简 API 网关路由转发实现
简介：开源项目构建失败排查步骤，梳理构建报错排查流程，从依赖、网络、权限、脚本多角度定位项目构建失败原因。
 | 原文链接：http://wiki.5mcbj6.asia/arts/156697.Doc

原标题：设计思考：系统幂等性整体架构层面保障
简介：OAuth2 第三方登录服务搭建，搭建 OAuth2 服务，支持第三方账号登录，实现授权登录能力。
 | 原文链接：http://wiki.5mcbj6.asia/arts/463171.Doc

原标题：golang kafka offset 提交策略
简介：用户敏感数据脱敏代码实现，编写数据脱敏工具，对手机号、身份证做脱敏处理，防止敏感信息直接泄露。
 | 原文链接：http://wiki.5mcbj6.asia/arts/162803.Doc

原标题：Practice：模拟网络抖动验证服务容错能力
简介：HTTPS 证书过期更新操作，检测 HTTPS 证书到期，更新证书文件，恢复 HTTPS 服务正常访问。
 | 原文链接：http://wiki.5mcbj6.asia/arts/884866.Doc

原标题：部署复盘：静态站点部署CDN完整流程
简介：网关超时时间调优后端等待，调大网关向后端转发请求超时时间，给后端业务充足处理时间。
 | 原文链接：http://wiki.5mcbj6.asia/arts/535777.Doc

原标题：开源实践：给开源项目写单元测试贡献代码
简介：静态博客部署 GitHub Pages 教程，将静态博客项目部署至 GitHub Pages，完成线上访问，快速搭建个人技术博客站点。
 | 原文链接：http://wiki.5mcbj6.asia/arts/578415.Doc

原标题：性能复盘：锁等待严重业务逻辑优化记录
简介：golang fasthttp 高性能 http 库使用，fasthttp 高性能 http 实现，适合超高 QPS 场景，对比 net/http 差异。
 | 原文链接：http://wiki.5mcbj6.asia/arts/949109.Doc

原标题：golang 系统设计接口返回格式统一规范
简介：golang http cookie jar 会话处理，客户端 cookie jar 自动管理 cookie，处理登录态会话。
 | 原文链接：http://wiki.5mcbj6.asia/arts/930881.Doc

原标题：golang 系统设计本地缓存与分布式缓存
简介：多版本开发环境共存配置，实现同一工具多版本并存，快速切换不同版本，适配不同项目对版本的差异化需求。
 | 原文链接：http://wiki.5mcbj6.asia/arts/463870.Doc

四、架构设计｜Architecture
原标题：Git 代码冲突正确处理方式
简介：golang cgo 性能开销避坑指南，cgo 调用开销，减少频繁 cgo 调用，规避 cgo 带来内存泄漏风险。
 | 原文链接：http://wiki.5mcbj6.asia/arts/986928.Doc

原标题：golang kafka 消息顺序性保证方案
简介：版本升级服务启动失败处理，版本更新之后服务无法启动，对比新旧版本配置、依赖差异，完成故障修复。
 | 原文链接：http://wiki.5mcbj6.asia/arts/690506.Doc

原标题：golang redis 布隆过滤器安装使用
简介：golang go json 序列化自定义字段，json 标签控制字段名称、忽略字段、omitempty 空值忽略。
 | 原文链接：http://wiki.5mcbj6.asia/arts/534011.Doc

原标题：Docker 多阶段构建镜像瘦身
简介：文件批量导入导出功能实现，开发批量导入导出接口，处理大量文件数据，完成业务数据批量迁移与导出。
 | 原文链接：http://wiki.5mcbj6.asia/arts/047272.Doc

原标题：golang docker 多阶段构建 go 镜像
简介：golang go 零停机升级实践要点，socket 继承，流量无损，旧连接处理完毕后旧进程退出。
 | 原文链接：http://wiki.5mcbj6.asia/arts/571350.Doc

原标题：golang 系统设计大文件上传架构
简介：服务启动依赖顺序配置正确，配置服务启动依赖关系，保证依赖服务就绪之后再启动当前业务服务。
 | 原文链接：http://wiki.5mcbj6.asia/arts/348763.Doc

原标题：安全实践：输入输出双向过滤安全最佳实践
简介：文件批量导入导出功能实现，开发批量导入导出接口，处理大量文件数据，完成业务数据批量迁移与导出。
 | 原文链接：http://wiki.5mcbj6.asia/arts/723595.Doc

原标题：语义化版本依赖管理防错乱
简介：golang go 变量逃逸场景汇总，切片、指针、返回局部变量引发逃逸，变量分配到堆影响 GC。
 | 原文链接：http://wiki.5mcbj6.asia/arts/129109.Doc

原标题：新手向：npm/pip/maven依赖版本冲突入门排查
简介：golang 配置文件多格式兼容加载，同时支持 yaml toml json 多种格式配置文件，灵活适配不同部署环境。
 | 原文链接：http://wiki.5mcbj6.asia/arts/148812.Doc

原标题：golang gin 框架接口开发实战
简介：静态站点自动部署发布方案，配置流水线，代码更新自动构建静态站点并且部署上线，简化发布。
 | 原文链接：http://wiki.5mcbj6.asia/arts/673860.Doc

原标题：文件分片上传断点续传功能
简介：GET POST 接口请求参数处理，讲解两种请求方式参数传递区别，演示参数接收、解析、校验，适配不同接口调用场景。
 | 原文链接：http://wiki.5mcbj6.asia/arts/325141.Doc

原标题：golang 文件上传下载接口开发
简介：前端虚拟列表大数据渲染优化，实现虚拟滚动列表，只渲染可视区域 DOM，上万条数据页面流畅渲染。
 | 原文链接：http://wiki.5mcbj6.asia/arts/963635.Doc

原标题：实战：多版本SDK兼容业务改造实践
简介：golang nil channel 阻塞特性，nil channel 读写永久阻塞，理解 nil channel 行为做逻辑控制。
 | 原文链接：http://wiki.5mcbj6.asia/arts/195868.Doc

原标题：DevOps：WSL2生产环境使用风险提示
简介：分布式锁失效问题排查修复，分析分布式锁失效场景，修复锁超时、续期问题，保证锁逻辑可靠。
 | 原文链接：http://wiki.5mcbj6.asia/arts/122096.Doc

原标题：golang 系统设计开源 pr 评审合并流程实操
简介：golang prometheus http 接口暴露指标，暴露 prometheus metrics 接口，输出业务运行指标，接入监控告警系统。
 | 原文链接：http://wiki.5mcbj6.asia/arts/303511.Doc

原标题：后端登录鉴权模块完整开发
简介：golang 消息队列实现事务消息方案，基于 kafka 实现事务消息，业务执行成功才对外投递消息。
 | 原文链接：http://wiki.5mcbj6.asia/arts/130426.Doc

原标题：实战：Nginx负载均衡多种策略配置实践
简介：golang 时间戳秒毫秒纳秒转换，Unix UnixMilli UnixNano 互相转换，区分单位避免时间逻辑 bug。
 | 原文链接：http://wiki.5mcbj6.asia/arts/522969.Doc

原标题：golang minio 对象存储接口开发
简介：消息消费重试次数限制防爆炸，限制消息最大重试次数，防止失败消息无限重试造成消息爆炸堆积。
 | 原文链接：http://wiki.5mcbj6.asia/arts/269210.Doc

?
