最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 项目 makefile 脚本编写
简介：golang json omitempty 零值坑，omitempty 会忽略零值，区分业务是否需要输出零值字段。
 | 原文链接：http://wiki.gnzaeu.asia/arts/744788.Doc

原标题：项目目录结构规范化最佳实践
简介：SourceMap 生成线上报错定位，项目打包生成 SourceMap 文件，线上报错可以还原源码，快速定位报错位置。
 | 原文链接：http://wiki.gnzaeu.asia/arts/619581.Doc

原标题：部署实践：容器时区统一配置解决方案
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://wiki.gnzaeu.asia/arts/607100.Doc

原标题：架构复盘：数据库主从架构设计与延迟应对方案
简介：golang 参数校验业务接口处理，Go 接口入参参数校验，拦截非法入参，减少业务层参数判断代码。
 | 原文链接：http://wiki.gnzaeu.asia/arts/490909.Doc

原标题：新手向：开源项目依赖安装失败排查
简介：动态定时任务业务调度实现，实现可以动态增删启停定时任务，无需重启服务调整调度任务。
 | 原文链接：http://wiki.gnzaeu.asia/arts/603809.Doc

原标题：方案设计：接口版本管理架构向前兼容策略
简介：golang 工具函数库封装思路，Go 通用工具库封装思路，错误处理、类型转换，业务项目复用工具代码。
 | 原文链接：http://wiki.gnzaeu.asia/arts/220589.Doc

原标题：golang context 上下文传参讲解
简介：golang 容器信号转发处理问题修复，docker/k8s 正确转发 SIGTERM 信号，保证 go 程序收到信号优雅退出。
 | 原文链接：http://wiki.gnzaeu.asia/arts/925418.Doc

原标题：golang 系统设计容器镜像安全加固要点
简介：线程调度优化减少上下文切换，优化线程数量，减少线程频繁切换，降低 CPU 上下文切换开销。
 | 原文链接：http://wiki.gnzaeu.asia/arts/046910.Doc

原标题：golang 静态编译缩小镜像体积
简介：golang net/http/httptest 服务端模拟，httptest.NewRecorder 记录 handler 响应，校验返回状态码 body。
 | 原文链接：http://wiki.gnzaeu.asia/arts/377940.Doc

原标题：一次JWT令牌过期时间异常问题复盘
简介：golang go 单二进制文件静态编译交叉编译，交叉编译不同操作系统架构二进制文件，实现一次编译多平台运行。
 | 原文链接：http://wiki.gnzaeu.asia/arts/441980.Doc

原标题：Practice：实现跨机器文件同步脚本实践
简介：Docker 容器时区错误修复方案，修复 Docker 容器内部时区偏差，解决容器内时间不对引发业务逻辑异常。
 | 原文链接：http://wiki.gnzaeu.asia/arts/313870.Doc

原标题：实战：Nginx实现文件限速下载配置实践
简介：分页逻辑错误数据漏查修复，修复分页查询逻辑漏洞，解决分页漏数据、重复返回数据等业务问题。
 | 原文链接：http://wiki.gnzaeu.asia/arts/708323.Doc

原标题：golang 系统设计日志轮转切割防止磁盘占满
简介：golang http 中间件洋葱模型原理，理解 go http 中间件洋葱模型，请求响应流转顺序，编写自定义中间件。
 | 原文链接：http://wiki.gnzaeu.asia/arts/525086.Doc

原标题：Practice：实现多数据源动态切换组件实践
简介：全局本地依赖隔离冲突规避，区分全局依赖与项目本地依赖，隔离环境，防止全局包干扰项目运行。
 | 原文链接：http://wiki.gnzaeu.asia/arts/737254.Doc

原标题：开源实践：开源项目如何写好PullRequest
简介：golang go 程序版本号内置编译注入，编译时注入 git commit 版本号，程序运行输出版本便于排查。
 | 原文链接：http://wiki.gnzaeu.asia/arts/096406.Doc

原标题：项目实践：灰度发布简易方案落地实践
简介：全平台系统环境变量配置，汇总多操作系统环境变量配置方法，统一项目读取逻辑，适配不同运行平台。
 | 原文链接：http://wiki.gnzaeu.asia/arts/918210.Doc

原标题：开发记录：敏感数据加密存储解密业务实践
简介：日志切割配置防止日志丢失，配置日志切割轮转策略，日志按大小时间切割，防止日志文件丢失。
 | 原文链接：http://wiki.gnzaeu.asia/arts/568730.Doc

原标题：golang 系统设计 jwt 安全使用避坑要点
简介：golang 熔断降级简易组件开发，Go 简易熔断组件，下游故障触发熔断，保护上游服务不被拖垮。
 | 原文链接：http://wiki.gnzaeu.asia/arts/991043.Doc

原标题：架构复盘：分表扩容架构平滑迁移思路
简介：golang 压缩 zip 文件生成解压，golang 实现 zip 压缩打包，解压 zip 归档文件，处理批量文件归档。
 | 原文链接：http://wiki.gnzaeu.asia/arts/337990.Doc

原标题：实践：Git工作流主干开发团队协作实践
简介：缓存穿透击穿雪崩全套防护，完整梳理缓存三大问题，落地全套防护策略，保障缓存层稳定运行。
 | 原文链接：http://wiki.gnzaeu.asia/arts/222844.Doc

原标题：Performance：避免内存拷贝，大对象处理优化
简介：项目脚手架模板生成工具，搭建项目模板脚手架，一键生成标准化项目骨架，减少重复初始化工作。
 | 原文链接：http://wiki.gnzaeu.asia/arts/338862.Doc

原标题：踩坑：环境变量未生效导致线上配置错乱
简介：golang ip2regionIP 地址解析实战，集成 ip2region 库，根据 IP 解析归属地城市，实现 IP 地域解析。
 | 原文链接：http://wiki.gnzaeu.asia/arts/316785.Doc

原标题：新手向：开源项目依赖安装失败排查
简介：后端登录鉴权模块完整开发，实现完整登录模块，包含账号校验、令牌发放、接口鉴权整套能力。
 | 原文链接：http://wiki.gnzaeu.asia/arts/959716.Doc

原标题：快速上手搭建简易内网测试服务
简介：golang validator 自定义校验规则，Gin Validator 自定义校验器，实现业务特殊参数校验逻辑。
 | 原文链接：http://wiki.gnzaeu.asia/arts/884091.Doc

原标题：无用对象回收抑制内存上涨
简介：golang ioutil 已废弃替换方案，ioutil 废弃之后替换为 os io 包函数，更新旧项目代码。
 | 原文链接：http://wiki.gnzaeu.asia/arts/949583.Doc

原标题：golang 链路追踪简易实现方案
简介：新手参与开源社区贡献指南，介绍开源社区基础规则，讲解阅读 issue、提交 PR 流程，指导开发者参与开源贡献。
 | 原文链接：http://wiki.gnzaeu.asia/arts/147588.Doc

原标题：golang elasticsearch 索引设计思路
简介：内存广播本地进程消息通知，实现进程内内存消息广播，进程内部模块之间事件通知解耦。
 | 原文链接：http://wiki.gnzaeu.asia/arts/651038.Doc

原标题：项目实践：数据库慢日志采集分析落地实践
简介：golang 日志 zap 结构化日志实践，接入 Zap 结构化日志库，打印结构化日志，方便日志检索解析。
 | 原文链接：http://wiki.gnzaeu.asia/arts/711675.Doc

原标题：eslint prettier 代码规范落地
简介：golang feishu 飞书机器人消息发送，调用飞书 webhook 机器人，发送文本卡片消息，实现业务告警通知。
 | 原文链接：http://wiki.gnzaeu.asia/arts/365354.Doc

原标题：golang 系统设计接口参数防篡改校验
简介：golang gzip 压缩 http 响应，服务端开启 gzip 压缩，减小接口响应体积，降低网络传输耗时。
 | 原文链接：http://wiki.gnzaeu.asia/arts/780096.Doc

原标题：golang 系统设计缓存预热脚本编写实操
简介：golang 换行符统一处理，文本文件读写统一换行符，规避不同系统换行符带来解析异常。
 | 原文链接：http://wiki.gnzaeu.asia/arts/747957.Doc

原标题：golang 系统设计 jwt 安全使用避坑要点
简介：golang validator 自定义校验规则，Gin Validator 自定义校验器，实现业务特殊参数校验逻辑。
 | 原文链接：http://wiki.gnzaeu.asia/arts/156676.Doc

原标题：零基础理解跨域问题产生原因与基础方案
简介：golang go proxy 私有代理配置，配置 go proxy 私有代理，加速依赖下载，内网环境构建项目。
 | 原文链接：http://wiki.gnzaeu.asia/arts/581431.Doc

原标题：快速上手简易网关转发逻辑模拟
简介：golang slice 切片底层原理与坑点，切片扩容、截取、底层数组共享，规避切片修改互相影响数据。
 | 原文链接：http://wiki.gnzaeu.asia/arts/724211.Doc

原标题：Architecture：大文件上传下载系统架构设计
简介：极简 API 网关路由转发实现，开发极简网关服务，完成请求路由转发，理解网关基础实现原理。
 | 原文链接：http://wiki.gnzaeu.asia/arts/390805.Doc

原标题：实战项目：容器资源限制配置压力测试实践
简介：进程线程并发基础概念讲解，区分进程与线程，讲解调度逻辑，理解并发执行原理，为高并发业务开发打基础。
 | 原文链接：http://wiki.gnzaeu.asia/arts/941900.Doc

原标题：安全组端口开放网络访问
简介：golang http 服务并发连接数限制，自定义 listener 统计连接数量，限制最大并发连接数保护服务。
 | 原文链接：http://wiki.gnzaeu.asia/arts/067304.Doc

原标题：JWT 令牌过期异常处理
简介：手写简易 RPC 服务通信原型，手写极简 RPC 原型，理解服务注册、网络传输、方法调用底层逻辑。
 | 原文链接：http://wiki.gnzaeu.asia/arts/669427.Doc

原标题：golang 系统设计契约测试接口兼容性保障思路
简介：golang os/exec 安全执行外部命令，规避命令注入漏洞，参数分离，禁止拼接命令字符串执行。
 | 原文链接：http://wiki.gnzaeu.asia/arts/012729.Doc

原标题：golang mysql 避免 select * 查询
简介：golang rate‑limiter 限流组件，封装通用 Go 限流组件，支持多算法，业务接口直接复用调用。
 | 原文链接：http://wiki.gnzaeu.asia/arts/712896.Doc


二、踩坑排错｜Troubleshooting
原标题：排错：多实例部署session共享失效登录失效
简介：golang httptest 模拟 http 请求单元测试，httptest 模拟 http 请求，测试 http handler 逻辑不用启动服务。
 | 原文链接：http://wiki.gnzaeu.asia/arts/523543.Doc

原标题：设计思考：业务系统中什么时候不要用微服务
简介：环境变量不生效问题修复，排查环境变量加载顺序、作用域问题，修复环境变量读取不到的异常。
 | 原文链接：http://wiki.gnzaeu.asia/arts/196292.Doc

原标题：部署实践：服务器防火墙安全组配置实践
简介：CPU 亲和性配置负载均衡调度，配置进程 CPU 亲和，均衡利用多核 CPU，优化程序调度性能。
 | 原文链接：http://wiki.gnzaeu.asia/arts/480021.Doc

原标题：golang k8s rbac 权限控制配置示例
简介：golang 消息队列中间件选型对比，kafka redis‑stream rabbitmq，对比吞吐量可靠性选型参考。
 | 原文链接：http://wiki.gnzaeu.asia/arts/189186.Doc

原标题：部署实践：HTTPS证书自动续期配置实践
简介：图片上传预览格式大小处理，实现图片上传接口，校验文件格式、大小，完成上传后预览处理。
 | 原文链接：http://wiki.gnzaeu.asia/arts/296490.Doc

原标题：Issue：本地数据库与线上数据库排序规则差异
简介：golang snowflake 时钟回拨解决方案，雪花算法处理时钟回拨，防止生成重复 ID，保证 ID 全局唯一。
 | 原文链接：http://wiki.gnzaeu.asia/arts/448733.Doc

原标题：golang 系统设计 rest api 接口设计最佳实践
简介：golang http body 必须关闭的重要性，无论成功失败必须关闭 request.Body，否则连接无法复用泄漏。
 | 原文链接：http://wiki.gnzaeu.asia/arts/090042.Doc

原标题：golang minio 分片上传断点续传
简介：golang net/url 路径拼接处理，url.ParseRequestURI 处理请求 url，正确拼接 url 路径避免拼接错误。
 | 原文链接：http://wiki.gnzaeu.asia/arts/956017.Doc

原标题：容器内存扩容 OOM 被杀死修复
简介：线程调度优化减少上下文切换，优化线程数量，减少线程频繁切换，降低 CPU 上下文切换开销。
 | 原文链接：http://wiki.gnzaeu.asia/arts/760558.Doc

原标题：零基础理解会话、Cookie、Session基础
简介：跨平台 uniapp 多端开发实操，uniapp 开发一套代码，编译多端，梳理多端差异处理与适配技巧。
 | 原文链接：http://wiki.gnzaeu.asia/arts/961887.Doc

原标题：HelloCI：理解持续集成基础工作流程
简介：Redis 内存淘汰策略数据防丢失，合理配置 Redis 内存淘汰策略，防止内存满后误删除业务重要数据。
 | 原文链接：http://wiki.gnzaeu.asia/arts/473761.Doc

原标题：快速入门YAML配置文件语法与示例
简介：数据库连接池参数调优，调整连接池最大最小连接数，空闲超时，避免连接耗尽或者资源浪费。
 | 原文链接：http://wiki.gnzaeu.asia/arts/245333.Doc

原标题：实战：数据库索引设计，复合索引最佳实践
简介：golang 信号量控制并发数量，使用信号量控制并发，限制同时执行任务数量，保护下游资源。
 | 原文链接：http://wiki.gnzaeu.asia/arts/183478.Doc

原标题：实战：基于DockerCompose搭建本地开发栈
简介：golang cgo 性能开销避坑指南，cgo 调用开销，减少频繁 cgo 调用，规避 cgo 带来内存泄漏风险。
 | 原文链接：http://wiki.gnzaeu.asia/arts/017218.Doc

原标题：动态定时任务业务调度实现
简介：golang gorm 事务手动回滚提交，手动控制事务流程，业务异常主动回滚，保障数据操作原子性。
 | 原文链接：http://wiki.gnzaeu.asia/arts/036326.Doc

原标题：项目目录结构规范化最佳实践
简介：前端打包产物体积压缩优化，多手段压缩前端打包产物，移除无用代码，压缩资源，提升页面加载速度。
 | 原文链接：http://wiki.gnzaeu.asia/arts/384523.Doc

原标题：端口占用访问失败排查方案
简介：磁盘占满服务不可用清理方案，定位磁盘占用大文件，清理日志、缓存文件，恢复磁盘可用空间。
 | 原文链接：http://wiki.gnzaeu.asia/arts/319629.Doc

原标题：Architecture：API网关核心能力与组件拆分
简介：批量数据处理脚本编写技巧，编写脚本批量处理大量业务数据，循环处理、分批执行，提升数据处理效率。
 | 原文链接：http://wiki.gnzaeu.asia/arts/653995.Doc

原标题：golang cpu pprof 性能分析实操
简介：golang go 网络编程 net 包基础，net 包 tcp udp socket 编程，监听接收连接，读写数据。
 | 原文链接：http://wiki.gnzaeu.asia/arts/808766.Doc

原标题：golang 系统设计接口返回格式统一规范
简介：简易日志收集集中管理方案，搭建轻量日志收集方案，把多服务日志汇总，集中检索查看日志信息。
 | 原文链接：http://wiki.gnzaeu.asia/arts/724736.Doc

原标题：golang 系统设计网关错误重试超时处理策略
简介：monorepo 项目多包管理最佳实践，monorepo 仓库管理多子包，统一版本管理，处理包之间互相依赖。
 | 原文链接：http://wiki.gnzaeu.asia/arts/064718.Doc

原标题：golang nginx 反向代理 go 服务配置
简介：golang 布隆过滤器实现去重，Go 实现布隆过滤器，海量数据去重，节省内存开销，提升判断效率。
 | 原文链接：http://wiki.gnzaeu.asia/arts/059781.Doc

原标题：golang kafka 死信队列业务落地
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://wiki.gnzaeu.asia/arts/288094.Doc

原标题：golang 多协程任务池并发控制
简介：程序信号中断退出处理逻辑，捕获系统中断信号，执行资源释放、关闭连接，实现程序优雅退出。
 | 原文链接：http://wiki.gnzaeu.asia/arts/344244.Doc

原标题：golang grpc protobuf 开发实操
简介：golang go 项目 CI github actions 配置，github actions 实现 go 项目 ci，自动测试、代码检查、编译打包镜像。
 | 原文链接：http://wiki.gnzaeu.asia/arts/558735.Doc

原标题：nodejs http 服务性能调优实战
简介：golang 信号量控制并发数量，使用信号量控制并发，限制同时执行任务数量，保护下游资源。
 | 原文链接：http://wiki.gnzaeu.asia/arts/129472.Doc

原标题：Debug：DNS缓存TTL设置不当服务切换无法生效
简介：golang makefile 多平台编译脚本，makefile 一键交叉编译多平台二进制，打包镜像，执行测试。
 | 原文链接：http://wiki.gnzaeu.asia/arts/309110.Doc

原标题：git stash 代码暂存切换分支
简介：版本升级服务启动失败处理，版本更新之后服务无法启动，对比新旧版本配置、依赖差异，完成故障修复。
 | 原文链接：http://wiki.gnzaeu.asia/arts/007963.Doc

原标题：OpenSource：大型仓库Git历史清理瘦身实操
简介：golang arp 缓存读取操作，读取系统 arp 缓存表，获取 ip 对应的 mac 地址信息。
 | 原文链接：http://wiki.gnzaeu.asia/arts/198393.Doc

原标题：Troubleshooting：Nginx缓冲区过小大文件上传失败
简介：nestjs 权限守卫鉴权实现方案，使用 Nest 守卫实现接口鉴权，角色权限控制，拦截未授权接口访问。
 | 原文链接：http://wiki.gnzaeu.asia/arts/976844.Doc

原标题：架构复盘：网关层、应用层、数据库层层限流架构
简介：golang loki 日志收集 go 服务集成，日志输出适配 loki，标签携带 traceId，日志集中检索排查问题。
 | 原文链接：http://wiki.gnzaeu.asia/arts/304224.Doc

原标题：nodejs 流处理大文件不占内存
简介：vue3 组合式 API 业务开发实战，Vue3 组合式 API 业务实战示例，拆分业务逻辑组合复用，提升代码组织。
 | 原文链接：http://wiki.gnzaeu.asia/arts/663620.Doc

原标题：golang 单例模式实现几种方式
简介：golang validator 自定义校验规则，Gin Validator 自定义校验器，实现业务特殊参数校验逻辑。
 | 原文链接：http://wiki.gnzaeu.asia/arts/770145.Doc

原标题：文件锁正确使用避免死锁
简介：跨库查询性能优化处理，减少跨库关联查询，做数据冗余或者中间表，规避跨库查询性能低下。
 | 原文链接：http://wiki.gnzaeu.asia/arts/562148.Doc

原标题：定时任务重复执行分布式锁
简介：golang go 单二进制文件静态编译交叉编译，交叉编译不同操作系统架构二进制文件，实现一次编译多平台运行。
 | 原文链接：http://wiki.gnzaeu.asia/arts/990805.Doc

原标题：性能笔记：HTTP连接复用性能优化实践
简介：数据库排序规则统一结果一致，统一数据库表排序规则，解决不同环境查询排序结果不一致问题。
 | 原文链接：http://wiki.gnzaeu.asia/arts/880108.Doc

原标题：Debug：长连接未设置心跳，连接僵死不回收
简介：golang aes 对称加密解密示例，AES 对称加密解密实现，业务敏感数据加密存储传输。
 | 原文链接：http://wiki.gnzaeu.asia/arts/596441.Doc

原标题：golang 系统设计监控告警体系搭建思路
简介：golang io.MultiReader MultiWriter 拼接流，多个 reader 拼接，多 writer 同时写入一份数据。
 | 原文链接：http://wiki.gnzaeu.asia/arts/015093.Doc

原标题：AI实践：大模型生成代码后审查与重构实践
简介：golang go 项目安全检查漏洞扫描，扫描 go 项目依赖漏洞，代码安全审计，规避安全风险。
 | 原文链接：http://wiki.gnzaeu.asia/arts/015147.Doc

原标题：golang 系统设计 traceId 全链路透传完整方案
简介：golang go‑zero 缓存自动击穿防护，go‑zero 缓存组件自带缓存击穿防护，减少缓存层故障。
 | 原文链接：http://wiki.gnzaeu.asia/arts/292143.Doc

三、实战开发｜Practice
原标题：项目语义化版本号规范管理
简介：golang bytes.Buffer 字节缓冲区使用，bytes.Buffer 字节内存缓冲区，拼接字节，避免频繁内存分配。
 | 原文链接：http://wiki.gnzaeu.asia/arts/428954.Doc

原标题：golang 系统设计数据库迁移工具 go‑migrate 实操
简介：golang gorm 索引设置与优化技巧，定义数据库索引，理解索引生效条件，避免索引失效慢查询。
 | 原文链接：http://wiki.gnzaeu.asia/arts/275335.Doc

原标题：调优方案：数据库索引不要过度建立，权衡写性能
简介：golang go mod 私有 git 仓库配置，配置 go mod 拉取私有仓库代码，处理私有模块依赖拉取问题。
 | 原文链接：http://wiki.gnzaeu.asia/arts/237653.Doc

原标题：实践：实现Redis分布式锁完整可运行代码
简介：异步异常捕获避免进程崩溃，捕获异步代码内部抛出异常，防止未捕获异常直接导致整个进程退出。
 | 原文链接：http://wiki.gnzaeu.asia/arts/953245.Doc

原标题：Performance：后端接口性能优化完整分析流程
简介：golang go 时间 time.Timer time.Ticker，定时器与周期定时器，Stop Reset 正确使用，防止资源泄漏。
 | 原文链接：http://wiki.gnzaeu.asia/arts/141543.Doc

原标题：排错：HTTPS证书过期导致接口调用失败
简介：golang 单元测试 mock http 请求，mock HTTP 外部接口，单元测试不依赖外部网络，保证用例稳定运行。
 | 原文链接：http://wiki.gnzaeu.asia/arts/114943.Doc

原标题：Redis 大 key 拆分集群卡顿解决
简介：golang gzip 压缩 http 响应，服务端开启 gzip 压缩，减小接口响应体积，降低网络传输耗时。
 | 原文链接：http://wiki.gnzaeu.asia/arts/521649.Doc

原标题：DevOps：GitLabCI完整流水线配置示例
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://wiki.gnzaeu.asia/arts/233546.Doc

原标题：golang mysql innodb 事务隔离级别
简介：golang go 程序版本号内置编译注入，编译时注入 git commit 版本号，程序运行输出版本便于排查。
 | 原文链接：http://wiki.gnzaeu.asia/arts/808368.Doc

原标题：golang 系统设计单元测试 mock 外部依赖技巧
简介：TCP 长连接参数优化 TIME_WAIT，调整 TCP 内核参数，优化长连接，减少大量 TIME_WAIT 连接占用资源。
 | 原文链接：http://wiki.gnzaeu.asia/arts/602699.Doc

原标题：Performance：大事务拆分，减少锁持有时间
简介：项目脚手架模板生成工具，搭建项目模板脚手架，一键生成标准化项目骨架，减少重复初始化工作。
 | 原文链接：http://wiki.gnzaeu.asia/arts/634289.Doc

原标题：开发复盘：分库分表本地模拟与数据路由实践
简介：golang http 服务并发连接数限制，自定义 listener 统计连接数量，限制最大并发连接数保护服务。
 | 原文链接：http://wiki.gnzaeu.asia/arts/913849.Doc

原标题：golang 系统设计文件存储选型对比
简介：golang strings.Builder 字符串高效拼接，strings.Builder 做字符串拼接，比 += 性能更高，减少内存拷贝。
 | 原文链接：http://wiki.gnzaeu.asia/arts/784981.Doc

原标题：AI实践：大模型生成测试用例实践与校验
简介：golang gin 路由动态注册实现方案，根据配置动态注册接口路由，无需硬编码路由，适配动态业务模块。
 | 原文链接：http://wiki.gnzaeu.asia/arts/903812.Doc

原标题：项目实践：实现数据脱敏组件支持多种脱敏规则
简介：golang go 程序容器资源 requests limits，设置容器 cpu 内存配额，防止实例抢占集群资源，稳定调度。
 | 原文链接：http://wiki.gnzaeu.asia/arts/862860.Doc

原标题：golang redis 地理位置 geo 使用
简介：golang go 服务日志输出 journald，systemd journald 接收程序 stdout 日志，统一管理服务日志。
 | 原文链接：http://wiki.gnzaeu.asia/arts/577361.Doc

原标题：快速入门Nginx基础配置，反向代理示例
简介：golang bcrypt 密码哈希加密存储，bcrypt 做用户密码哈希，加盐存储密码，保障用户密码安全。
 | 原文链接：http://wiki.gnzaeu.asia/arts/456558.Doc

原标题：Performance：数据库join优化，大表join规避
简介：golang go 逃逸分析实操查看，go build‑gcflags=-m 查看逃逸分析，减少堆分配优化程序性能。
 | 原文链接：http://wiki.gnzaeu.asia/arts/460954.Doc

原标题：Mock 接口服务快速搭建实操
简介：golang go 锁竞争导致 CPU 飙升，识别锁竞争场景，减少锁粒度，优化并发逻辑降低 CPU 开销。
 | 原文链接：http://wiki.gnzaeu.asia/arts/237228.Doc

原标题：架构复盘：分表扩容架构平滑迁移思路
简介：golang go 泛型约束与类型集合，泛型 type set 约束，限制泛型支持类型，写出安全泛型代码。
 | 原文链接：http://wiki.gnzaeu.asia/arts/081919.Doc

原标题：性能复盘：锁等待严重业务逻辑优化记录
简介：golang interface {} 类型断言类型转换，类型断言 ok 模式，避免断言失败触发 panic。
 | 原文链接：http://wiki.gnzaeu.asia/arts/373279.Doc

原标题：日志敏感信息脱敏泄露防护
简介：golang kafka 消费者组重平衡避坑，规避消费者组频繁 rebalance，减少消费抖动，保障消息消费稳定性。
 | 原文链接：http://wiki.gnzaeu.asia/arts/297614.Doc

原标题：安全笔记：HTTPSTLS配置安全加固实践
简介：热更新开发环境配置教程，配置代码热重载，修改代码无需重启服务立即生效，大幅提升本地开发调试效率。
 | 原文链接：http://wiki.gnzaeu.asia/arts/150973.Doc

原标题：golang 系统设计告警规则阈值设置方法论
简介：golang grpc 拦截器开发鉴权日志，开发 grpc 服务端拦截器，统一做鉴权、日志打印、异常捕获处理。
 | 原文链接：http://wiki.gnzaeu.asia/arts/415984.Doc

原标题：运维笔记：服务器故障排查常用命令清单
简介：服务熔断防止故障级联传播，实现服务熔断逻辑，下游故障时快速失败，阻止故障向上游链式扩散。
 | 原文链接：http://wiki.gnzaeu.asia/arts/118709.Doc

原标题：零基础理解前后端简单交互流程
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://wiki.gnzaeu.asia/arts/826180.Doc

原标题：RPC 接口字段增减兼容处理
简介：GitHub Markdown 文档语法汇总，整理 Markdown 常用语法，编写仓库 README、文档，提升开源项目文档排版质量。
 | 原文链接：http://wiki.gnzaeu.asia/arts/152668.Doc

原标题：端口占用访问失败排查方案
简介：golang go‑zero 配置中心热更新，go‑zero 对接 etcd 配置中心，配置热更新无需重启服务。
 | 原文链接：http://wiki.gnzaeu.asia/arts/233326.Doc

原标题：开发记录：短信发送服务封装，失败重试策略
简介：极简方式搭建个人技术文档站点，使用轻量化工具快速部署文档站点，支持 markdown 编写，实现知识沉淀与对外分享。
 | 原文链接：http://wiki.gnzaeu.asia/arts/631622.Doc

原标题：rebase 操作防止代码丢失
简介：golang json 解析未知动态 json 结构，解析到 map [string] any 处理未知 json，动态读取字段。
 | 原文链接：http://wiki.gnzaeu.asia/arts/697081.Doc

原标题：项目实践：幂等表实现接口幂等业务实践
简介：golang go 输入数据校验防御，所有外部入参严格校验长度格式，防止恶意输入造成业务异常。
 | 原文链接：http://wiki.gnzaeu.asia/arts/488481.Doc

原标题：开发复盘：长轮询接口实现服务端消息推送
简介：golang 内存 pprof 定位内存泄漏，pprof 分析内存快照，定位内存泄露对象，解决 Go 程序内存持续上涨。
 | 原文链接：http://wiki.gnzaeu.asia/arts/748004.Doc

原标题：安全实践：敏感信息加密存储传输完整方案
简介：golang go 网络编程 net 包基础，net 包 tcp udp socket 编程，监听接收连接，读写数据。
 | 原文链接：http://wiki.gnzaeu.asia/arts/072336.Doc

原标题：golang 优雅停机服务关闭实现
简介：golang proto 默认值坑点梳理，梳理 Protobuf 默认值坑，零值字段区分未赋值，避免业务逻辑错误。
 | 原文链接：http://wiki.gnzaeu.asia/arts/037412.Doc

原标题：golang 系统设计代码评审关注点 checklist 清单
简介：服务器 Swap 关闭提升响应速度，关闭服务器 Swap 交换分区，避免内存交换磁盘拖慢程序响应性能。
 | 原文链接：http://wiki.gnzaeu.asia/arts/857074.Doc

原标题：项目实践：搭建监控大盘查看系统关键指标
简介：golang html 模板防 xss 自动转义，理解 go html/template 自动转义，防止 XSS 攻击，处理不需要转义场景。
 | 原文链接：http://wiki.gnzaeu.asia/arts/692155.Doc

原标题：从零搭建本地开发环境完整教程
简介：golang docker 多阶段构建 go 镜像，Go 项目 Docker 多阶段构建，编译与运行阶段分离，大幅度缩减最终镜像体积，提升镜像分发效率。
 | 原文链接：http://wiki.gnzaeu.asia/arts/415857.Doc

原标题：golang redis 限流几种实现方案
简介：接口请求重试容错机制实现，封装请求重试逻辑，遇到临时网络故障自动重试，提升第三方调用稳定性。
 | 原文链接：http://wiki.gnzaeu.asia/arts/778811.Doc

原标题：避坑：文件锁处理不当多进程竞争死锁
简介：容器内存扩容 OOM 被杀死修复，调高容器内存限制，优化程序内存占用，避免程序被 OOM 终止。
 | 原文链接：http://wiki.gnzaeu.asia/arts/260329.Doc

原标题：架构复盘：供应链安全架构依赖包风险治理
简介：golang go cover 覆盖率报告生成，go test‑cover 生成测试覆盖率，html 可视化查看未覆盖代码行。
 | 原文链接：http://wiki.gnzaeu.asia/arts/596814.Doc

四、架构设计｜Architecture
原标题：移动端适配 rem vw 方案对比
简介：golang dns 自定义解析器实现，自定义 dns 解析，指定 dns 服务器，控制域名解析逻辑，适配内网环境。
 | 原文链接：http://wiki.gnzaeu.asia/arts/296885.Doc

原标题：golang 系统设计批量处理优化业务性能
简介：golang 开发环境快速搭建指南，快速完成 Golang 开发环境配置，工具链安装，环境变量设置，准备开发。
 | 原文链接：http://wiki.gnzaeu.asia/arts/331320.Doc

原标题：nodejs 跨域中间件配置细节
简介：golang 集成测试测试数据库回滚，集成测试结束自动回滚数据库，不污染测试环境数据。
 | 原文链接：http://wiki.gnzaeu.asia/arts/160742.Doc

原标题：开发复盘：大列表内存分批读取避免OOM实践
简介：Git 混乱提交历史清理方法，针对杂乱的提交记录，使用 Git 工具整理，清理无效提交，还原整洁版本历史。
 | 原文链接：http://wiki.gnzaeu.asia/arts/337226.Doc

原标题：日志输出规范防止磁盘爆满
简介：golang go 自定义错误类型实现，自定义 error 结构体，携带错误码、堆栈信息，统一业务错误。
 | 原文链接：http://wiki.gnzaeu.asia/arts/862461.Doc

原标题：线上异常：布隆过滤器误判造成业务逻辑异常
简介：Docker 容器入门镜像实操教程，介绍 Docker 基础概念，演示镜像拉取、容器启停，帮助新手建立容器化开发认知。
 | 原文链接：http://wiki.gnzaeu.asia/arts/944995.Doc

原标题：rebase 操作防止代码丢失
简介：golang net/http 超时全套配置，完整配置 Go HTTP 服务读写空闲超时，全方位防止请求挂住。
 | 原文链接：http://wiki.gnzaeu.asia/arts/469741.Doc

原标题：golang k8s ingress‑nginx 配置 ssl 证书
简介：golang benchmark 减少测试干扰，benchmark 执行循环 b.N，避免循环内部做非被测逻辑干扰结果。
 | 原文链接：http://wiki.gnzaeu.asia/arts/433248.Doc

原标题：GET POST 接口请求参数处理
简介：golang go 泛型使用避坑注意点，泛型与 interface 区别，泛型性能，什么时候适合使用泛型。
 | 原文链接：http://wiki.gnzaeu.asia/arts/981776.Doc

原标题：Hands‑on：简易事件驱动架构原型开发
简介：文件读写与异常捕获代码示例，演示文件读取写入操作，增加异常捕获逻辑，规避文件不存在、权限不足导致崩溃。
 | 原文链接：http://wiki.gnzaeu.asia/arts/071096.Doc

原标题：静态站点自动部署发布方案
简介：WSL 文件权限访问异常修复，处理 WSL 环境文件权限错乱，调整权限配置，实现文件正常读写访问。
 | 原文链接：http://wiki.gnzaeu.asia/arts/270623.Doc

原标题：实战项目：GitHubAction自动测试构建实践
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：http://wiki.gnzaeu.asia/arts/370580.Doc

原标题：调优方案：静态资源缓存头Cache‑Control优化
简介：跨平台 uniapp 多端开发实操，uniapp 开发一套代码，编译多端，梳理多端差异处理与适配技巧。
 | 原文链接：http://wiki.gnzaeu.asia/arts/381286.Doc

原标题：新手指南：本地防火墙端口访问失败排查
简介：不必要字符转义关闭业务异常，关闭多余自动转义逻辑，防止业务数据被错误转义，破坏原始数据。
 | 原文链接：http://wiki.gnzaeu.asia/arts/899512.Doc

原标题：复盘总结：接口重构兼容旧版本改造复盘
简介：golang go 爬虫请求速率控制，爬虫限频、代理轮换，设置 UA，防止爬虫被目标站点封禁 IP。
 | 原文链接：http://wiki.gnzaeu.asia/arts/315487.Doc

原标题：Hands‑on：shell脚本批量自动化运维小工具
简介：golang 限制 multipart 内存大小，设置 MaxMemory，大文件写入磁盘临时文件防止内存暴涨。
 | 原文链接：http://wiki.gnzaeu.asia/arts/567673.Doc

原标题：日志驱动异常日志不输出修复
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://wiki.gnzaeu.asia/arts/267761.Doc

原标题：RPC 接口字段增减兼容处理
简介：golang go test 单元测试命令参数详解，gotest 参数覆盖率，指定测试用例，跳过测试，单元测试命令实操。
 | 原文链接：http://wiki.gnzaeu.asia/arts/677709.Doc

?
