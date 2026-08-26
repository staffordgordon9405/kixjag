最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计线上日志快速检索技巧
简介：golang sync.Once 只执行一次，sync.Once 做单例初始化，保证代码只执行一次，并发安全。
 | 原文链接：http://wiki.ea7a5m.asia/arts/644527.Doc

原标题：Architecture：CI/CD流水线架构完整设计思考
简介：golang 日志级别动态调整热更新，不用重启程序动态修改日志输出级别，线上调试排查问题十分方便。
 | 原文链接：http://wiki.ea7a5m.asia/arts/001828.Doc

原标题：新手向：开源项目本地构建失败通用排查步骤
简介：正则表达式文本处理实战案例，结合业务场景演示正则匹配、提取、替换，处理手机号、邮箱等各类文本校验需求。
 | 原文链接：http://wiki.ea7a5m.asia/arts/716344.Doc

原标题：业务幂等键设计防重复逻辑
简介：请求重试组件退避策略实现，封装重试组件，实现指数退避策略，避免大量请求同时重试压垮下游。
 | 原文链接：http://wiki.ea7a5m.asia/arts/288471.Doc

原标题：golang websocket 服务端开发
简介：HTTPS 证书过期更新操作，检测 HTTPS 证书到期，更新证书文件，恢复 HTTPS 服务正常访问。
 | 原文链接：http://wiki.ea7a5m.asia/arts/617292.Doc

原标题：开源实践：Fork上游项目，持续同步更新代码
简介：golang io.LimitReader 限制读取字节数，LimitReader 限制最大读取，防止读取超大数据。
 | 原文链接：http://wiki.ea7a5m.asia/arts/530920.Doc

原标题：项目实践：多租户数据隔离三种方案实操对比
简介：golang http cookie jar 会话处理，客户端 cookie jar 自动管理 cookie，处理登录态会话。
 | 原文链接：http://wiki.ea7a5m.asia/arts/496870.Doc

原标题：Troubleshoot：磁盘inode耗尽，无法新建文件
简介：golang go mod graph 可视化依赖图，可视化 go 依赖关系，直观看到包之间依赖，定位冲突。
 | 原文链接：http://wiki.ea7a5m.asia/arts/649889.Doc

原标题：限流组件计数器令牌桶模式实现
简介：全量回归测试提升代码质量，搭建全量回归测试集，版本发布执行回归测试，避免迭代引入旧 bug。
 | 原文链接：http://wiki.ea7a5m.asia/arts/719830.Doc

原标题：架构复盘：数据库索引架构设计原则与边界
简介：golang goroutine 泄露常见场景汇总，channel 阻塞、context 忘记取消，导致协程无法退出发生泄露。
 | 原文链接：http://wiki.ea7a5m.asia/arts/907009.Doc

原标题：踩坑记录：浮点精度错误造成业务计算错误
简介：golang gorm ORM 数据库操作，GORM 实操数据库 CRUD，模型定义，关联查询，简化 Go 数据库开发。
 | 原文链接：http://wiki.ea7a5m.asia/arts/527998.Doc

原标题：golang 系统设计单元测试表驱动测试 table‑driven
简介：容器资源限制防止宿主机过载，设置容器 CPU 内存资源上限，避免单个容器耗尽宿主机全部硬件资源。
 | 原文链接：http://wiki.ea7a5m.asia/arts/869121.Doc

原标题：Redis 内存淘汰策略数据防丢失
简介：开发生产环境资源路径统一，对齐开发环境与生产环境资源路径，防止本地正常上线后资源找不到。
 | 原文链接：http://wiki.ea7a5m.asia/arts/307626.Doc

原标题：Hands‑on：实现服务健康检查与自动报警demo
简介：本地数据库开发环境搭建指南，讲解数据库安装配置、账号权限设置、连接测试，快速搭建用于开发调试的数据库实例。
 | 原文链接：http://wiki.ea7a5m.asia/arts/016847.Doc

原标题：golang gin 路由分组权限管控
简介：golang http 客户端连接泄漏排查，http client 未读取响应体导致连接无法复用，解决连接泄漏耗尽连接池。
 | 原文链接：http://wiki.ea7a5m.asia/arts/567517.Doc

原标题：golang 系统设计令牌桶漏桶算法对比
简介：golang 字符编码转换 go 处理，iconv‑go 做编码转换 gbk utf8 互转，处理老旧系统 gbk 编码数据。
 | 原文链接：http://wiki.ea7a5m.asia/arts/019185.Doc

原标题：浮点计算精度错误处理方案
简介：golang os.Signal 信号监听完整示例，signal.Notify 监听信号，缓冲 channel 防止信号丢失。
 | 原文链接：http://wiki.ea7a5m.asia/arts/234984.Doc

原标题：性能笔记：RPC超时参数优化防止级联阻塞
简介：nestjs 权限守卫鉴权实现方案，使用 Nest 守卫实现接口鉴权，角色权限控制，拦截未授权接口访问。
 | 原文链接：http://wiki.ea7a5m.asia/arts/341510.Doc

原标题：golang 系统设计日志级别业务使用原则梳理
简介：系统字符集统一乱码修复，统一数据库、程序、操作系统字符集，解决中文乱码显示异常问题。
 | 原文链接：http://wiki.ea7a5m.asia/arts/815074.Doc

原标题：开发记录：跨域中间件完整配置与边界处理
简介：数据库分表路由写入分片修正，修复分表路由逻辑，保证数据写入正确分片，不会出现数据丢失错乱。
 | 原文链接：http://wiki.ea7a5m.asia/arts/678185.Doc

原标题：项目实践：搭建个人API网关最小实现版本
简介：golang 错误栈捕获打印方案，捕获错误完整调用堆栈，线上日志输出堆栈，快速定位错误发生代码位置。
 | 原文链接：http://wiki.ea7a5m.asia/arts/456155.Doc

原标题：golang 系统设计会话共享多实例部署
简介：golang excel 简单读写操作示例，Go 实现 Excel 简单读写，业务数据导出 Excel 报表。
 | 原文链接：http://wiki.ea7a5m.asia/arts/748430.Doc

原标题：性能笔记：磁盘IO过高业务优化手段
简介：golang 系统资源限制读取 cpu 内存，读取系统容器 cpu 内存限制，程序适配容器资源配额做业务调优。
 | 原文链接：http://wiki.ea7a5m.asia/arts/442035.Doc

原标题：golang 系统设计 rest http 方法使用原则
简介：golang mime 类型检测文件，mime 识别文件 mime 类型，设置 http 响应 Content‑Type。
 | 原文链接：http://wiki.ea7a5m.asia/arts/578737.Doc

原标题：golang 系统设计 cpu 瓶颈定位优化方案
简介：golang os.Exit 退出程序注意 defer 不执行，os.Exit 会直接退出，不会执行 defer，优雅退出不要直接 os.Exit。
 | 原文链接：http://wiki.ea7a5m.asia/arts/717952.Doc

原标题：设计思考：容器化业务应用架构改造要点
简介：vite 插件开发自定义构建逻辑，开发自定义 vite 插件，介入构建生命周期，实现项目个性化构建逻辑。
 | 原文链接：http://wiki.ea7a5m.asia/arts/796740.Doc

原标题：线上异常：接口偶发超时，完整定位过程记录
简介：安全组端口开放网络访问，调整服务器安全组规则，开放业务需要端口，恢复外部网络访问服务。
 | 原文链接：http://wiki.ea7a5m.asia/arts/555733.Doc

原标题：Practice：实现业务操作日志记录中间件实践
简介：nodejs redis 缓存业务实战，Node 对接 Redis 实现业务缓存，缓存热点查询结果，减轻数据库压力。
 | 原文链接：http://wiki.ea7a5m.asia/arts/968777.Doc

原标题：golang 系统设计分布式会话方案对比
简介：业务错误码完整落地实践，落地完整业务错误码，枚举全部业务异常，统一返回，配套文档说明。
 | 原文链接：http://wiki.ea7a5m.asia/arts/721306.Doc

原标题：部署实践：多实例服务部署无状态改造
简介：golang 系统资源限制读取 cpu 内存，读取系统容器 cpu 内存限制，程序适配容器资源配额做业务调优。
 | 原文链接：http://wiki.ea7a5m.asia/arts/048669.Doc

原标题：Security：Docker镜像安全扫描漏洞修复
简介：golang lru 缓存淘汰算法编写，手写 LRU 缓存淘汰算法，实现本地缓存，淘汰最久未使用数据。
 | 原文链接：http://wiki.ea7a5m.asia/arts/911047.Doc

原标题：golang 系统设计集成测试环境准备清理实操
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://wiki.ea7a5m.asia/arts/422403.Doc

原标题：golang jwt 鉴权中间件完整示例
简介：golang go 模块迁移从 GOPATH 到 GoMod，老项目从 GOPATH 迁移 go mod，解决依赖管理混乱问题。
 | 原文链接：http://wiki.ea7a5m.asia/arts/089102.Doc

原标题：踩坑记录：时间戳精度不一致引发判断错误
简介：OpenAPI 自动接口文档生成，集成 OpenAPI 工具，自动扫描代码生成接口文档，减少文档维护成本。
 | 原文链接：http://wiki.ea7a5m.asia/arts/501622.Doc

原标题：开源实践：开源项目本地调试构建排坑经验
简介：空指针异常判空容错处理，讲解空指针产生场景，规范判空逻辑，增加容错，避免空指针直接造成程序崩溃。
 | 原文链接：http://wiki.ea7a5m.asia/arts/617341.Doc

原标题：golang 优雅处理数据库事务
简介：ORM 框架数据库增删改查实操，使用 ORM 框架完成数据库基础操作，减少手写 SQL，简化业务层数据库交互代码。
 | 原文链接：http://wiki.ea7a5m.asia/arts/526925.Doc

原标题：Practice：数据库分表简单实现方案与代码示例
简介：golang grpc 负载均衡客户端实现，grpc 客户端负载均衡，轮询随机权重，分发请求到多个服务实例。
 | 原文链接：http://wiki.ea7a5m.asia/arts/781639.Doc

原标题：GET POST 接口请求参数处理
简介：接口签名验签完整安全方案，一套完整接口签名方案，包含签名生成、请求携带、服务端验签校验。
 | 原文链接：http://wiki.ea7a5m.asia/arts/393556.Doc

原标题：golang 系统设计会话共享多实例部署
简介：任务执行锁防止并发重复调度，增加任务执行锁，多实例环境，防止同一个定时任务并发多次运行。
 | 原文链接：http://wiki.ea7a5m.asia/arts/523324.Doc

原标题：golang kafka 重试机制配置实操
简介：golang go 项目 CI github actions 配置，github actions 实现 go 项目 ci，自动测试、代码检查、编译打包镜像。
 | 原文链接：http://wiki.ea7a5m.asia/arts/211689.Doc


二、踩坑排错｜Troubleshooting
原标题：Debug：表单自动转义特殊字符业务逻辑出错
简介：集成测试业务流程编写示例，编写业务流程集成测试，覆盖完整业务链路，验证模块之间协同工作是否正常。
 | 原文链接：http://wiki.ea7a5m.asia/arts/863646.Doc

原标题：golang mysql 分表自增 id 方案
简介：golang 内存缓存简单实现方案，Go 实现进程内简易内存缓存，本地缓存热点数据，减少远程调用。
 | 原文链接：http://wiki.ea7a5m.asia/arts/893189.Doc

原标题：Practice：实现防爬虫简单拦截中间件实践
简介：golang cgo 性能开销避坑指南，cgo 调用开销，减少频繁 cgo 调用，规避 cgo 带来内存泄漏风险。
 | 原文链接：http://wiki.ea7a5m.asia/arts/230816.Doc

原标题：golang etcd 分布式锁实现原理
简介：golang json number 数字不转 float64，使用 json.Number 保留原始数字字符串，防止大数字精度丢失。
 | 原文链接：http://wiki.ea7a5m.asia/arts/663902.Doc

原标题：golang 系统设计开源版本发布 changelog 维护
简介：序列化版本不一致解析失败，保证序列化对象版本对齐，修复版本不匹配导致对象反序列化失败。
 | 原文链接：http://wiki.ea7a5m.asia/arts/923198.Doc

原标题：golang 系统设计读写分离架构示例
简介：golang hystrix 模式简易熔断实现，简易熔断组件，错误率达到阈值触发熔断，快速失败保护下游。
 | 原文链接：http://wiki.ea7a5m.asia/arts/903049.Doc

原标题：golang gin 静态资源访问配置
简介：golang gin 框架接口开发实战，Gin 框架搭建 HTTP 服务，开发增删改查接口，快速完成后端接口开发。
 | 原文链接：http://wiki.ea7a5m.asia/arts/567524.Doc

原标题：golang 系统设计配置回滚版本历史记录实现
简介：多操作系统开发兼容处理，解决不同系统路径、换行符、权限差异，保证项目跨平台正常运行。
 | 原文链接：http://wiki.ea7a5m.asia/arts/269516.Doc

原标题：安全笔记：CORS跨域配置错误安全风险
简介：网关集成鉴权限流日志一体化，在网关层整合鉴权、限流、请求日志，统一对入口请求做管控处理。
 | 原文链接：http://wiki.ea7a5m.asia/arts/025587.Doc

原标题：记一次第三方SDK版本兼容引发线上故障
简介：golang aes 对称加密解密示例，AES 对称加密解密实现，业务敏感数据加密存储传输。
 | 原文链接：http://wiki.ea7a5m.asia/arts/203183.Doc

原标题：golang k8s ingress 路由域名转发
简介：golang go 项目依赖冲突解决完整思路，定位冲突包，replace、exclude、升级降级解决版本冲突。
 | 原文链接：http://wiki.ea7a5m.asia/arts/830250.Doc

原标题：golang github actions 发布 release 包
简介：golang go‑zero 分布式锁组件使用，go‑zero 内置 redis 分布式锁，业务直接调用实现并发控制。
 | 原文链接：http://wiki.ea7a5m.asia/arts/685478.Doc

原标题：实践：API错误统一捕获与告警通知实践
简介：数据库分表路由写入分片修正，修复分表路由逻辑，保证数据写入正确分片，不会出现数据丢失错乱。
 | 原文链接：http://wiki.ea7a5m.asia/arts/180991.Doc

原标题：正则表达式优化 CPU 占满问题
简介：golang kafka 批量消费性能优化，开启批量拉取消息，调整批量大小，提升 kafka 消息消费吞吐量。
 | 原文链接：http://wiki.ea7a5m.asia/arts/887602.Doc

原标题：golang etcd 租约 lease 过期机制
简介：MySQL 慢查询索引优化实战，抓取慢查询 SQL，分析执行计划，新增或者调整索引，提升 SQL 执行速度。
 | 原文链接：http://wiki.ea7a5m.asia/arts/232790.Doc

原标题：nodejs redis 缓存业务实战
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://wiki.ea7a5m.asia/arts/948664.Doc

原标题：golang 系统设计消息队列解耦削峰
简介：golang go ring 环形容器循环队列，ring 环形链表实现循环队列，环形缓冲区业务场景。
 | 原文链接：http://wiki.ea7a5m.asia/arts/233472.Doc

原标题：golang 系统设计布隆过滤器拦截不存在 key
简介：提交第一个开源 PR 完整流程，Fork 项目、修改代码、提交 Pull Request，讲解 PR 规范，提升合并通过率。
 | 原文链接：http://wiki.ea7a5m.asia/arts/297580.Doc

原标题：线上异常：线程池队列拒绝策略配置错误丢任务
简介：golang 时间轮算法实现延时调度，手写简易时间轮，高并发大量延时任务，降低轮询 CPU 消耗。
 | 原文链接：http://wiki.ea7a5m.asia/arts/363857.Doc

原标题：避坑：正则回溯引发CPU占满DoS风险
简介：Dockerfile 编写容器打包实战，讲解 Dockerfile 指令含义，编写镜像构建脚本，将本地项目打包成可分发容器镜像。
 | 原文链接：http://wiki.ea7a5m.asia/arts/982483.Doc

原标题：依赖安装失败全方位排错
简介：express 请求参数校验处理，接入参数校验库，校验入参，拦截非法参数，提前拦截错误请求。
 | 原文链接：http://wiki.ea7a5m.asia/arts/918253.Doc

原标题：golang 系统设计埋点数据上报方案
简介：golang rabbitmq 死信队列延迟消息，rabbitmq 实现死信、延迟消息，处理延时业务场景。
 | 原文链接：http://wiki.ea7a5m.asia/arts/837285.Doc

原标题：坑点：环境配置写死代码，上线忘记修改
简介：golang go1.18 + 泛型基础实操，go 泛型基础语法，泛型函数泛型类型，实现通用工具函数。
 | 原文链接：http://wiki.ea7a5m.asia/arts/044894.Doc

原标题：golang ci 流水线环境变量管理方案
简介：golang go 程序容器资源 requests limits，设置容器 cpu 内存配额，防止实例抢占集群资源，稳定调度。
 | 原文链接：http://wiki.ea7a5m.asia/arts/759140.Doc

原标题：Nginx 缓冲区调优大文件上传
简介：前端大文件分片上传完整方案，前端分片切割大文件，配合后端分片接口，实现稳定大文件上传。
 | 原文链接：http://wiki.ea7a5m.asia/arts/803436.Doc

原标题：golang 系统设计分表 id 生成策略对比
简介：内网 DNS 不稳定随机报错排查，定位内网 DNS 抖动问题，配置备选 DNS，解决偶现域名解析失败。
 | 原文链接：http://wiki.ea7a5m.asia/arts/013667.Doc

原标题：golang 系统设计逻辑删除物理删除选型对比
简介：nodejs jwt 登录鉴权完整示例，Node 实现 JWT 登录鉴权，登录签发令牌，接口校验令牌身份。
 | 原文链接：http://wiki.ea7a5m.asia/arts/482896.Doc

原标题：golang 系统设计网关灰度流量切分简单方案
简介：golang 数据库 ORM 框架选型对比，gorm xorm sqlx 对比各 ORM 优缺点，根据业务场景选型。
 | 原文链接：http://wiki.ea7a5m.asia/arts/617786.Doc

原标题：SDK 版本兼容线上崩溃修复
简介：golang 配置文件多环境加载，Go 多环境配置加载实现，读取配置文件环境变量，适配多套运行环境。
 | 原文链接：http://wiki.ea7a5m.asia/arts/867150.Doc

原标题：性能复盘：热点key导致RedisCPU飙升优化
简介：消息队列生产消费模型入门，讲解消息队列生产、存储、消费流程，理解异步解耦、削峰，掌握消息队列基础概念。
 | 原文链接：http://wiki.ea7a5m.asia/arts/371194.Doc

原标题：实践：接口参数自动校验业务落地实践
简介：golang 链路追踪简易实现方案，简易链路追踪实现，传递 traceId，记录调用链路，方便排查慢调用。
 | 原文链接：http://wiki.ea7a5m.asia/arts/767696.Doc

原标题：Issue：文件编码混合GBKUTF‑8乱码随机出现
简介：golang goroutine 泄露常见场景汇总，channel 阻塞、context 忘记取消，导致协程无法退出发生泄露。
 | 原文链接：http://wiki.ea7a5m.asia/arts/003997.Doc

原标题：golang 链路追踪简易实现方案
简介：容器资源限制防止宿主机过载，设置容器 CPU 内存资源上限，避免单个容器耗尽宿主机全部硬件资源。
 | 原文链接：http://wiki.ea7a5m.asia/arts/041302.Doc

原标题：golang redis 缓存预热实现思路
简介：golang go cover 覆盖率报告生成，go test‑cover 生成测试覆盖率，html 可视化查看未覆盖代码行。
 | 原文链接：http://wiki.ea7a5m.asia/arts/567265.Doc

原标题：golang 单元测试 mock http 请求
简介：代码模块化组件化拆分思路，讲解代码拆分原则，将大业务拆分为独立模块组件，提升代码复用与维护能力。
 | 原文链接：http://wiki.ea7a5m.asia/arts/956823.Doc

原标题：Practice：实现接口幂等性多种方案对比实践
简介：gitignore 文件编写过滤规则，讲解 gitignore 语法，编写过滤配置，忽略缓存、编译产物、密钥文件，保持仓库整洁。
 | 原文链接：http://wiki.ea7a5m.asia/arts/056891.Doc

原标题：golang 雪花 id 重复问题排查
简介：golang go http 静态文件禁止目录遍历，http.FileServer 防止../ 路径穿越，了解底层安全实现。
 | 原文链接：http://wiki.ea7a5m.asia/arts/180953.Doc

原标题：本地运行正常线上报错排查
简介：文件分片上传断点续传功能，实现文件分片上传，记录上传进度，支持断点续传大文件上传。
 | 原文链接：http://wiki.ea7a5m.asia/arts/311584.Doc

原标题：从零搭建本地开发环境完整教程
简介：golang go cover 覆盖率报告生成，go test‑cover 生成测试覆盖率，html 可视化查看未覆盖代码行。
 | 原文链接：http://wiki.ea7a5m.asia/arts/504103.Doc

原标题：架构复盘：RPC框架架构超时重试设计要点
简介：CLI 工具进度条交互效果开发，在命令行工具增加进度条展示，直观反馈任务执行进度，优化命令行体验。
 | 原文链接：http://wiki.ea7a5m.asia/arts/973651.Doc

三、实战开发｜Practice
原标题：golang 静态文件服务搭建教程
简介：golang grpc 客户端拦截器封装，grpc 客户端拦截器实现请求统一签名、重试、链路信息透传。
 | 原文链接：http://wiki.ea7a5m.asia/arts/804458.Doc

原标题：开发复盘：统一错误码体系设计落地实践
简介：golang goreleaser 自动版本发布打包，goreleaser 自动化打包发布，生成多平台二进制归档文件。
 | 原文链接：http://wiki.ea7a5m.asia/arts/896702.Doc

原标题：时间同步修复令牌提前过期
简介：golang 互斥锁读写锁并发安全，互斥锁读写锁实操，保护共享变量，解决多协程并发读写数据竞争。
 | 原文链接：http://wiki.ea7a5m.asia/arts/514327.Doc

原标题：前端打包分包加载提速方案
简介：golang go 项目安全检查漏洞扫描，扫描 go 项目依赖漏洞，代码安全审计，规避安全风险。
 | 原文链接：http://wiki.ea7a5m.asia/arts/486486.Doc

原标题：golang 系统设计唯一索引业务使用场景
简介：express 请求参数校验处理，接入参数校验库，校验入参，拦截非法参数，提前拦截错误请求。
 | 原文链接：http://wiki.ea7a5m.asia/arts/912068.Doc

原标题：golang 系统设计压力测试性能测试执行流程
简介：golang udp 服务端客户端开发示例，golang 实现 UDP 服务收发数据包，实现 udp 协议通信程序。
 | 原文链接：http://wiki.ea7a5m.asia/arts/599773.Doc

原标题：golang 系统设计 gob msgpack 序列化对比
简介：golang http client 连接池调优，调优 Go HTTP Client 连接池参数，复用 TCP 连接，减少连接创建开销。
 | 原文链接：http://wiki.ea7a5m.asia/arts/567301.Doc

原标题：消息队列重复消费业务处理
简介：golang 数据库连接泄露排查，定位 Go 数据库连接泄露，连接没有归还池，导致连接耗尽报错。
 | 原文链接：http://wiki.ea7a5m.asia/arts/371730.Doc

原标题：设计思考：系统降级开关架构设计快速切流量
简介：golang go 包循环导入报错解决，A 导入 B B 导入 A，循环导入报错，重构代码拆分包消除循环依赖。
 | 原文链接：http://wiki.ea7a5m.asia/arts/323999.Doc

原标题：golang 系统设计 e2e 端到端测试简单落地思路
简介：golang race 检测器性能开销，race 检测器有性能损耗，只用于测试环境，禁止生产开启 race。
 | 原文链接：http://wiki.ea7a5m.asia/arts/970580.Doc

原标题：开发记录：JWT过期刷新滑动过期实现实践
简介：golang url 参数编码处理方案，Go URL 参数编码解码，处理特殊字符，避免 URL 参数错乱。
 | 原文链接：http://wiki.ea7a5m.asia/arts/118844.Doc

原标题：部署实践：数据库迁移脚本版本管理实践
简介：golang tcp_NODELAY 关闭延迟发送，设置 tcp_NODELAY，关闭 Nagle 算法，降低小包请求延迟。
 | 原文链接：http://wiki.ea7a5m.asia/arts/604628.Doc

原标题：HelloDocker：编写你的第一个Dockerfile
简介：golang base64 大文件流式编解码，大文件流式 base64 转换，不用一次性加载全部文件进入内存。
 | 原文链接：http://wiki.ea7a5m.asia/arts/943443.Doc

原标题：避坑：Spring事务传播行为理解错误事务失效
简介：浮点计算精度错误处理方案，讲解浮点数计算精度丢失问题，使用合适数据类型，规避金额计算出错。
 | 原文链接：http://wiki.ea7a5m.asia/arts/510003.Doc

原标题：坑点：依赖缓存未更新，旧代码持续运行
简介：开源项目构建失败排查步骤，梳理构建报错排查流程，从依赖、网络、权限、脚本多角度定位项目构建失败原因。
 | 原文链接：http://wiki.ea7a5m.asia/arts/517710.Doc

原标题：安全笔记：依赖包漏洞检测供应链安全
简介：golang jwt 令牌刷新逻辑实现，实现 JWT 双令牌机制，access 短期有效 refresh 刷新令牌，实现无感续期登录。
 | 原文链接：http://wiki.ea7a5m.asia/arts/019638.Doc

原标题：golang kafka 生产者参数调优
简介：GitHub Markdown 文档语法汇总，整理 Markdown 常用语法，编写仓库 README、文档，提升开源项目文档排版质量。
 | 原文链接：http://wiki.ea7a5m.asia/arts/600521.Doc

原标题：Architecture：限流计数器架构时间窗口选型对比
简介：网关超时时间调优后端等待，调大网关向后端转发请求超时时间，给后端业务充足处理时间。
 | 原文链接：http://wiki.ea7a5m.asia/arts/075022.Doc

原标题：golang 系统设计分布式任务调度
简介：磁盘占满服务不可用清理方案，定位磁盘占用大文件，清理日志、缓存文件，恢复磁盘可用空间。
 | 原文链接：http://wiki.ea7a5m.asia/arts/641128.Doc

原标题：调优方案：容器CPU内存参数压测后调优
简介：golang netlink 系统信息获取，netlink 获取系统网络信息，网卡地址，内核网络状态读取。
 | 原文链接：http://wiki.ea7a5m.asia/arts/176472.Doc

原标题：WSL 文件权限访问异常修复
简介：golang grpc 双向流双向通信开发，grpc 双向流，服务端客户端持续互发消息，长连接流式业务场景。
 | 原文链接：http://wiki.ea7a5m.asia/arts/329679.Doc

原标题：安全复盘：业务接口越权测试与修复实践
简介：golang 微服务网关简易实现，http 反向代理、路由匹配、鉴权限流，理解网关核心原理。
 | 原文链接：http://wiki.ea7a5m.asia/arts/007593.Doc

原标题：Architecture：限流计数器架构时间窗口选型对比
简介：浏览器缓存强制刷新方案，设置 HTTP 缓存头，处理浏览器缓存旧静态资源，让用户加载更新后的页面。
 | 原文链接：http://wiki.ea7a5m.asia/arts/487259.Doc

原标题：全局时间标准统一逻辑错乱修复
简介：文件描述符优化进程卡死修复，及时关闭文件句柄，控制打开文件数量，解决文件句柄耗尽进程卡死。
 | 原文链接：http://wiki.ea7a5m.asia/arts/491387.Doc

原标题：服务器 Swap 关闭提升响应速度
简介：跨库查询性能优化处理，减少跨库关联查询，做数据冗余或者中间表，规避跨库查询性能低下。
 | 原文链接：http://wiki.ea7a5m.asia/arts/869583.Doc

原标题：golang 系统设计 protobuf json 性能对比
简介：golang cgo 性能开销避坑指南，cgo 调用开销，减少频繁 cgo 调用，规避 cgo 带来内存泄漏风险。
 | 原文链接：http://wiki.ea7a5m.asia/arts/528803.Doc

原标题：优化实践：异步改造同步接口提升吞吐能力
简介：Git 分支管理多人协作实战教程，详解分支创建、合并、冲突处理，适配团队开发场景，规范多人协同代码工作流。
 | 原文链接：http://wiki.ea7a5m.asia/arts/532442.Doc

原标题：golang 系统设计结构化日志字段规范约定
简介：golang redis hyperloglog 基数统计，hyperloglog 统计 UV 基数，海量数据去重统计，极低内存开销。
 | 原文链接：http://wiki.ea7a5m.asia/arts/455609.Doc

原标题：golang http client 连接池调优
简介：golang jwt 令牌刷新逻辑实现，实现 JWT 双令牌机制，access 短期有效 refresh 刷新令牌，实现无感续期登录。
 | 原文链接：http://wiki.ea7a5m.asia/arts/963623.Doc

原标题：效率笔记：Git高级命令日常开发高频使用汇总
简介：golang testify mock 模拟接口，mock 接口生成 mock 对象，单元测试模拟外部依赖行为。
 | 原文链接：http://wiki.ea7a5m.asia/arts/252528.Doc

原标题：安全复盘：Nginx配置不当带来的安全风险
简介：DNS TTL 配置域名切换生效，调整 DNS 解析 TTL，缩短缓存时间，域名变更后可以快速全网生效。
 | 原文链接：http://wiki.ea7a5m.asia/arts/458613.Doc

原标题：Architecture：API设计RESTful最佳实践与反模式
简介：golang ssh 客户端远程命令执行，golang ssh 连接远程服务器，执行 shell 命令，获取命令输出结果。
 | 原文链接：http://wiki.ea7a5m.asia/arts/532368.Doc

原标题：文件批量导入导出功能实现
简介：golang kafka 消费者组重平衡避坑，规避消费者组频繁 rebalance，减少消费抖动，保障消息消费稳定性。
 | 原文链接：http://wiki.ea7a5m.asia/arts/907148.Doc

原标题：golang 系统设计 canary 金丝雀部署实操
简介：新手参与开源社区贡献指南，介绍开源社区基础规则，讲解阅读 issue、提交 PR 流程，指导开发者参与开源贡献。
 | 原文链接：http://wiki.ea7a5m.asia/arts/978148.Doc

原标题：golang minio 预签名 url 临时访问
简介：golang http 客户端连接泄漏排查，http client 未读取响应体导致连接无法复用，解决连接泄漏耗尽连接池。
 | 原文链接：http://wiki.ea7a5m.asia/arts/278373.Doc

原标题：排错：CI流水线构建失败，日志无明确报错
简介：golang 内存缓存简单实现方案，Go 实现进程内简易内存缓存，本地缓存热点数据，减少远程调用。
 | 原文链接：http://wiki.ea7a5m.asia/arts/720879.Doc

原标题：golang docker 容器资源限制设置
简介：golang go http 文件服务器自定义，http.FileServer 自定义 FileSystem，拦截访问，增加鉴权逻辑。
 | 原文链接：http://wiki.ea7a5m.asia/arts/801602.Doc

原标题：项目目录结构规范化最佳实践
简介：版本升级服务启动失败处理，版本更新之后服务无法启动，对比新旧版本配置、依赖差异，完成故障修复。
 | 原文链接：http://wiki.ea7a5m.asia/arts/067406.Doc

原标题：golang ci 流水线自动部署 k8s 示例
简介：本地简易配置中心动态管理，搭建轻量本地配置中心，业务动态读取配置，修改配置不重启服务。
 | 原文链接：http://wiki.ea7a5m.asia/arts/541583.Doc

原标题：静态资源 404 路径打包修复
简介：golang 静态文件服务搭建教程，Go 搭建静态文件服务，托管静态资源，实现文件直接对外访问。
 | 原文链接：http://wiki.ea7a5m.asia/arts/449452.Doc

四、架构设计｜Architecture
原标题：安全实践：最小权限原则数据库账号管控
简介：游标分页大数据查询性能提升，使用游标分页替代偏移分页，解决大数据 offset 分页性能越来越差问题。
 | 原文链接：http://wiki.ea7a5m.asia/arts/315208.Doc

原标题：golang 系统设计故障预案编写模板参考示例
简介：Nginx 缓冲区调优大文件上传，调大 Nginx 请求缓冲区，支持客户端上传大体积文件，避免上传被截断。
 | 原文链接：http://wiki.ea7a5m.asia/arts/541022.Doc

原标题：WSL 文件权限访问异常修复
简介：golang 雪花算法 workId 自动获取，自动获取机器 workId，不用手动配置，简化分布式 id 部署。
 | 原文链接：http://wiki.ea7a5m.asia/arts/207923.Doc

原标题：golang 系统设计配置敏感信息加密存储方案
简介：golang grpc 服务端流推送数据，服务端流式响应，服务端持续向客户端推送多条响应消息。
 | 原文链接：http://wiki.ea7a5m.asia/arts/944302.Doc

原标题：性能复盘：慢查询日积月累拖垮数据库优化
简介：布隆过滤器数据高效去重实现，实现布隆过滤器组件，用于海量数据去重，节省大量内存空间。
 | 原文链接：http://wiki.ea7a5m.asia/arts/718072.Doc

原标题：Debug：异步任务堆积，服务响应越来越慢
简介：golang 结构体零值可用性原则，go 结构体尽量做到零值可用，不用初始化直接使用提升易用性。
 | 原文链接：http://wiki.ea7a5m.asia/arts/518443.Doc

原标题：坑点：环境配置被打包进镜像引发安全泄露
简介：axios 二次封装请求拦截处理，对 axios 做二次封装，统一请求拦截响应拦截，处理错误、token 自动刷新。
 | 原文链接：http://wiki.ea7a5m.asia/arts/533290.Doc

原标题：安全复盘：Redis命令注入风险防护手段
简介：golang 漏桶算法实现接口限流，漏桶算法控制请求流出速率，平滑突发流量，削平流量峰值。
 | 原文链接：http://wiki.ea7a5m.asia/arts/696978.Doc

原标题：Practice：实现防爬虫简单拦截中间件实践
简介：网络读取超时设置连接挂起防护，设置网络读取超时时间，防止请求无限挂起不返回，占用连接资源。
 | 原文链接：http://wiki.ea7a5m.asia/arts/239420.Doc

原标题：坑点：Git仓库过大，clone速度极慢解决方案
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://wiki.ea7a5m.asia/arts/975246.Doc

原标题：排错：容器OOM被杀死，日志看不到任何输出
简介：Shell 运维脚本服务器效率提升，编写常用运维 Shell 脚本，自动化服务器运维操作，减少手工重复工作。
 | 原文链接：http://wiki.ea7a5m.asia/arts/234880.Doc

原标题：Git 分支管理多人协作实战教程
简介：golang k8s 客户端 client‑go 简单示例，client‑go 操作 k8s 资源，增删改查 pod deployment 等资源对象。
 | 原文链接：http://wiki.ea7a5m.asia/arts/447103.Doc

原标题：nodejs 项目 pm2 部署运维指南
简介：程序日志分级输出规范实践，区分日志等级，规范日志打印内容，合理输出日志，方便线上问题排查定位。
 | 原文链接：http://wiki.ea7a5m.asia/arts/889754.Doc

原标题：ORM 隐式慢查询问题规避
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://wiki.ea7a5m.asia/arts/229442.Doc

原标题：Performance：长连接管理优化减少连接重建开销
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://wiki.ea7a5m.asia/arts/574063.Doc

原标题：CPU 亲和性配置负载均衡调度
简介：golang redis hash 结构业务实战，使用 Redis Hash 存储对象数据，适合对象字段频繁更新业务场景。
 | 原文链接：http://wiki.ea7a5m.asia/arts/371005.Doc

原标题：WebSocket 双向通信 demo 开发
简介：golang http 服务优雅关闭完整示例，接收终止信号，停止接收新请求，等待现有请求处理完毕后退出服务。
 | 原文链接：http://wiki.ea7a5m.asia/arts/781097.Doc

原标题：golang 系统设计批量处理优化业务性能
简介：css 动画性能优化 GPU 加速，优化 CSS 动画，使用 GPU 加速属性，避免动画过程页面卡顿掉帧。
 | 原文链接：http://wiki.ea7a5m.asia/arts/908980.Doc

?
