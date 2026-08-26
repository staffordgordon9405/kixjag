最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 接口请求日志记录中间件
简介：golang 读写分离 gorm 实现主从切换，gorm 配置主库写入从库查询，读写分离分担数据库查询压力。
 | 原文链接：http://wiki.mljc3b.asia/arts/933305.Doc

原标题：golang redis 过期策略内存淘汰
简介：后端分页查询逻辑代码实现，编写后端分页接口，处理页码、每页条数参数，优化大数据量查询返回结果。
 | 原文链接：http://wiki.mljc3b.asia/arts/303625.Doc

原标题：跨库查询性能优化处理
简介：golang 分布式追踪全链路日志打印，日志打印 traceId，各个服务日志可串联，排查跨服务调用问题。
 | 原文链接：http://wiki.mljc3b.asia/arts/977086.Doc

原标题：看懂报错日志快速定位问题
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://wiki.mljc3b.asia/arts/574529.Doc

原标题：Issue：Docker网络模式选择错误容器互通失败
简介：请求重试组件退避策略实现，封装重试组件，实现指数退避策略，避免大量请求同时重试压垮下游。
 | 原文链接：http://wiki.mljc3b.asia/arts/492184.Doc

原标题：开发记录：短信发送服务封装，失败重试策略
简介：nodejs 接口限流防刷代码实现，Node 层实现接口限流，限制 IP 访问频次，防护接口被恶意高频调用。
 | 原文链接：http://wiki.mljc3b.asia/arts/777607.Doc

原标题：macOS 脚本执行权限开启
简介：golang gif 图片帧处理操作，解析 gif 图片帧，压缩、拆分 gif 动图，处理动图业务。
 | 原文链接：http://wiki.mljc3b.asia/arts/670140.Doc

原标题：golang k8s 基础概念 pod deployment
简介：多实例部署 Session 共享方案，多服务实例部署场景，实现 Session 共享，保证用户登录状态跨实例生效。
 | 原文链接：http://wiki.mljc3b.asia/arts/059400.Doc

原标题：浏览器内存泄漏排查前端页面
简介：pnpm 包管理工具实战避坑指南，使用 pnpm 管理项目依赖，梳理常见坑点，充分利用 pnpm 优势。
 | 原文链接：http://wiki.mljc3b.asia/arts/155114.Doc

原标题：部署实践：服务器防火墙安全组配置实践
简介：前端权限路由动态生成实现，根据后端返回权限，动态生成前端路由菜单，实现页面权限控制。
 | 原文链接：http://wiki.mljc3b.asia/arts/387165.Doc

原标题：golang 系统设计数据库慢查询治理方案
简介：golang rate‑limiter 限流组件，封装通用 Go 限流组件，支持多算法，业务接口直接复用调用。
 | 原文链接：http://wiki.mljc3b.asia/arts/343111.Doc

原标题：golang 系统设计分布式锁可重入实现思路
简介：golang redis 过期时间处理技巧，设置 key 过期，监控过期事件，基于过期特性实现业务缓存逻辑。
 | 原文链接：http://wiki.mljc3b.asia/arts/544325.Doc

原标题：golang mongodb 索引优化查询速度
简介：配置与镜像分离防止信息泄露，业务配置不打包进镜像，外部挂载配置，避免密钥配置随镜像泄露。
 | 原文链接：http://wiki.mljc3b.asia/arts/481136.Doc

原标题：vite 插件开发自定义构建逻辑
简介：golang 大文件 HTTP 流式上传接收，服务端流式接收上传文件，不全部加载内存，防止大文件 OOM 崩溃。
 | 原文链接：http://wiki.mljc3b.asia/arts/535987.Doc

原标题：golang k8s job 一次性任务执行
简介：golang 容器健康检查接口开发，Go 开发 HTTP 健康接口，供容器编排工具探测实例存活状态。
 | 原文链接：http://wiki.mljc3b.asia/arts/823274.Doc

原标题：Practice：手写简易限流组件，计数器、令牌桶实现
简介：不必要字符转义关闭业务异常，关闭多余自动转义逻辑，防止业务数据被错误转义，破坏原始数据。
 | 原文链接：http://wiki.mljc3b.asia/arts/162658.Doc

原标题：golang 系统设计 rest 状态码合理使用指南
简介：golang 信号量控制并发数量，使用信号量控制并发，限制同时执行任务数量，保护下游资源。
 | 原文链接：http://wiki.mljc3b.asia/arts/526210.Doc

原标题：零基础学习简单正则表达式实战案例
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：http://wiki.mljc3b.asia/arts/001799.Doc

原标题：DevOps：私有镜像仓库搭建与权限管控
简介：站内邮件消息通知功能开发，实现站内消息、邮件通知推送，业务事件触发通知，提醒用户业务状态变更。
 | 原文链接：http://wiki.mljc3b.asia/arts/383794.Doc

原标题：调优方案：服务实例扩容，水平扩展性能
简介：golang map 并发读写 panic 解决方案，map 非并发安全，讲解加锁、sync.map 方案解决并发读写崩溃。
 | 原文链接：http://wiki.mljc3b.asia/arts/212188.Doc

原标题：排错：macOS权限保护导致脚本执行被拦截
简介：golang sync.Mutex 互斥锁正确模式，互斥锁 defer Unlock，锁粒度控制，避免锁范围过大。
 | 原文链接：http://wiki.mljc3b.asia/arts/015893.Doc

原标题：golang 系统设计线上问题复现思路简单讲解
简介：nodejs 项目 pm2 部署运维指南，使用 PM2 管理 Node 服务，进程守护、日志、重启，线上部署运维实操。
 | 原文链接：http://wiki.mljc3b.asia/arts/209360.Doc

原标题：golang 系统设计时间字段选型 datetime timestamp
简介：nodejs 脚手架工具开发完整教程，从零开发 Node 命令行脚手架，实现项目模板生成，理解 CLI 开发。
 | 原文链接：http://wiki.mljc3b.asia/arts/136674.Doc

原标题：坑点：依赖缓存未更新，旧代码持续运行
简介：Dockerfile 编写容器打包实战，讲解 Dockerfile 指令含义，编写镜像构建脚本，将本地项目打包成可分发容器镜像。
 | 原文链接：http://wiki.mljc3b.asia/arts/772925.Doc

原标题：从零搭建简单Mock接口服务
简介：golang go 程序容器资源 requests limits，设置容器 cpu 内存配额，防止实例抢占集群资源，稳定调度。
 | 原文链接：http://wiki.mljc3b.asia/arts/358585.Doc

原标题：Hands‑on：简易的事件订阅发布组件开发实践
简介：golang net/http/httptest 服务端模拟，httptest.NewRecorder 记录 handler 响应，校验返回状态码 body。
 | 原文链接：http://wiki.mljc3b.asia/arts/831073.Doc

原标题：golang redis 缓存雪崩完整处理
简介：golang mongodb 索引优化慢查询处理，mongodb 创建索引，分析慢查询，优化聚合查询执行性能。
 | 原文链接：http://wiki.mljc3b.asia/arts/495816.Doc

原标题：HelloMarkdown：GitHubMarkdown完整语法速查
简介：golang go 模块迁移从 GOPATH 到 GoMod，老项目从 GOPATH 迁移 go mod，解决依赖管理混乱问题。
 | 原文链接：http://wiki.mljc3b.asia/arts/455795.Doc

原标题：golang 系统设计敏感数据加密存储方案
简介：golang go 变量逃逸场景汇总，切片、指针、返回局部变量引发逃逸，变量分配到堆影响 GC。
 | 原文链接：http://wiki.mljc3b.asia/arts/492180.Doc

原标题：golang redis 缓存穿透解决方案
简介：golang sql 注入风险规避要点，参数化查询杜绝 sql 注入，禁止字符串拼接 SQL 语句执行。
 | 原文链接：http://wiki.mljc3b.asia/arts/287448.Doc

原标题：golang 系统设计消息 partition 数量设置思路
简介：golang proto 默认值坑点梳理，梳理 Protobuf 默认值坑，零值字段区分未赋值，避免业务逻辑错误。
 | 原文链接：http://wiki.mljc3b.asia/arts/323209.Doc

原标题：Security：密码存储哈希加盐最佳实践
简介：跨平台换行符统一异常修复，统一代码文件换行符，解决不同操作系统换行符不一致带来脚本执行异常。
 | 原文链接：http://wiki.mljc3b.asia/arts/140232.Doc

原标题：golang grafana 监控面板简单配置
简介：golang GC 调优 GOGC 参数调整，调整 GOGC 阈值，控制 GC 触发时机，权衡内存占用与 CPU 开销。
 | 原文链接：http://wiki.mljc3b.asia/arts/226862.Doc

原标题：部署实践：多实例服务部署无状态改造
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://wiki.mljc3b.asia/arts/906741.Doc

原标题：golang 系统设计内部服务链路 trace 传递实现
简介：golang go 爬虫 html 解析 goquery，goquery 解析 html 文档，css 选择器提取网页内容，实现网页数据抓取。
 | 原文链接：http://wiki.mljc3b.asia/arts/167977.Doc

原标题：golang mysql 联合索引最左匹配
简介：golang sync.Once 只执行一次，sync.Once 做单例初始化，保证代码只执行一次，并发安全。
 | 原文链接：http://wiki.mljc3b.asia/arts/782032.Doc

原标题：Practice：实现批量任务失败断点续跑实践
简介：golang dns 自定义解析器实现，自定义 dns 解析，指定 dns 服务器，控制域名解析逻辑，适配内网环境。
 | 原文链接：http://wiki.mljc3b.asia/arts/843922.Doc

原标题：golang 系统设计缓存故障降级处理方案
简介：golang 日志输出 stdout 标准输出规范，容器环境日志输出到 stdout，由容器平台统一采集日志文件。
 | 原文链接：http://wiki.mljc3b.asia/arts/898143.Doc

原标题：性能笔记：HTTP连接复用性能优化实践
简介：golang 服务注册 etcd 简单示例，etcd 实现服务注册发现，微服务实例注册元数据，客户端发现节点。
 | 原文链接：http://wiki.mljc3b.asia/arts/712221.Doc

原标题：golang k8s 本地 minikube 调试应用
简介：golang bcrypt 密码哈希加密存储，bcrypt 做用户密码哈希，加盐存储密码，保障用户密码安全。
 | 原文链接：http://wiki.mljc3b.asia/arts/500835.Doc


二、踩坑排错｜Troubleshooting
原标题：实战项目：WSL开发环境完整配置实操
简介：分布式事务最终一致性实现，基于可靠消息实现最终一致性，解决跨数据库跨服务业务数据一致性。
 | 原文链接：http://wiki.mljc3b.asia/arts/729559.Doc

原标题：golang 系统设计分库分表本地测试调试技巧
简介：golang trace 可视化分析协程阻塞，使用 trace 网页 UI，定位协程阻塞、系统调用阻塞、锁等待。
 | 原文链接：http://wiki.mljc3b.asia/arts/219297.Doc

原标题：日志输出规范防止磁盘爆满
简介：golang feishu 飞书机器人消息发送，调用飞书 webhook 机器人，发送文本卡片消息，实现业务告警通知。
 | 原文链接：http://wiki.mljc3b.asia/arts/018109.Doc

原标题：进程线程并发基础概念讲解
简介：MySQL 慢查询索引优化实战，抓取慢查询 SQL，分析执行计划，新增或者调整索引，提升 SQL 执行速度。
 | 原文链接：http://wiki.mljc3b.asia/arts/761867.Doc

原标题：快速上手调试工具定位简单代码错误
简介：Nginx 缓冲区调优大文件上传，调大 Nginx 请求缓冲区，支持客户端上传大体积文件，避免上传被截断。
 | 原文链接：http://wiki.mljc3b.asia/arts/028232.Doc

原标题：实践：大文件分片上传后端完整实现思路
简介：golang go 程序权限最小化运行，容器内使用普通用户运行程序，拒绝 root 运行提升安全等级。
 | 原文链接：http://wiki.mljc3b.asia/arts/892789.Doc

原标题：实战项目：本地搭建Prometheus监控完整demo
简介：golang 文件句柄耗尽排查处理，统计进程打开文件句柄，找到未关闭文件，修复句柄泄漏问题。
 | 原文链接：http://wiki.mljc3b.asia/arts/263216.Doc

原标题：golang 系统设计大文件上传架构
简介：golang httptest 模拟外部 http 服务，httptest.NewServer 模拟第三方 http 服务，单元测试 mock 外部接口。
 | 原文链接：http://wiki.mljc3b.asia/arts/485776.Doc

原标题：gitignore 文件编写过滤规则
简介：Redis 热点 key 拆分降低集群压力，拆分访问量极高的热点 Key，分散请求压力，避免 Redis 节点压力过高。
 | 原文链接：http://wiki.mljc3b.asia/arts/392184.Doc

原标题：效率笔记：GitWorkflow团队协作规范模板
简介：golang go test 单元测试命令参数详解，gotest 参数覆盖率，指定测试用例，跳过测试，单元测试命令实操。
 | 原文链接：http://wiki.mljc3b.asia/arts/936220.Doc

原标题：golang 系统设计 lru 缓存算法实现思路
简介：前端水印防信息泄露实现，实现网页水印功能，页面叠加用户信息水印，防止页面截图信息外泄。
 | 原文链接：http://wiki.mljc3b.asia/arts/910300.Doc

原标题：实战项目：数据导出Excel百万级大数据导出方案
简介：文件监控服务自动重启开发，监控项目文件变更，代码修改自动重启服务，提升本地开发调试效率。
 | 原文链接：http://wiki.mljc3b.asia/arts/601672.Doc

原标题：golang docker 部署 es 本地开发
简介：本地运行正常线上报错排查，对比本地与线上环境差异，从配置、系统版本、文件权限定位线上独有的 bug。
 | 原文链接：http://wiki.mljc3b.asia/arts/135618.Doc

原标题：golang 系统设计 tcp 三次握手四次挥手梳理
简介：golang 接口限流中间件开发，Gin 开发限流中间件，接口层实现访问频率限制，防护接口流量。
 | 原文链接：http://wiki.mljc3b.asia/arts/136745.Doc

原标题：Hands‑on：编写自定义Git钩子实现代码提交校验
简介：前端组件库按需加载性能优化，配置组件库按需引入，避免引入全部组件，减少打包产物体积。
 | 原文链接：http://wiki.mljc3b.asia/arts/282797.Doc

原标题：业务接口幂等完整落地案例
简介：安全组端口开放网络访问，调整服务器安全组规则，开放业务需要端口，恢复外部网络访问服务。
 | 原文链接：http://wiki.mljc3b.asia/arts/429023.Doc

原标题：语义化版本依赖管理防错乱
简介：golang 数据库分表策略按时间分片，按时间维度分表，历史数据拆分，单表数据量控制保证查询性能。
 | 原文链接：http://wiki.mljc3b.asia/arts/613723.Doc

原标题：golang 灰度权重流量分发简单实现
简介：golang interface {} 类型断言类型转换，类型断言 ok 模式，避免断言失败触发 panic。
 | 原文链接：http://wiki.mljc3b.asia/arts/047731.Doc

原标题：golang 令牌桶限流中间件 gin
简介：golang sqlx 原生 SQL 代码简化，sqlx 简化原生 SQL 结果映射结构体，兼顾性能与开发效率。
 | 原文链接：http://wiki.mljc3b.asia/arts/662422.Doc

原标题：从零搭建本地数据库开发环境
简介：golang grpc 拦截器开发鉴权日志，开发 grpc 服务端拦截器，统一做鉴权、日志打印、异常捕获处理。
 | 原文链接：http://wiki.mljc3b.asia/arts/566259.Doc

原标题：DevOps：多环境镜像标签版本管理规范
简介：golang 分库分表简单路由实现，简易分表路由逻辑实现，根据分片 key 计算分片位置，数据路由写入。
 | 原文链接：http://wiki.mljc3b.asia/arts/085269.Doc

原标题：服务器时钟同步任务错乱修复
简介：golang redis list 队列简易消息队列，利用 Redis List 实现简易队列，完成任务入队消费基础能力。
 | 原文链接：http://wiki.mljc3b.asia/arts/647806.Doc

原标题：DevOps：Docker镜像安全扫描集成CI流程
简介：golang go 符号表与调试信息取舍，区分生产环境调试符号取舍，平衡镜像体积与故障排查能力。
 | 原文链接：http://wiki.mljc3b.asia/arts/415518.Doc

原标题：golang 系统设计磁盘满故障应急处理步骤
简介：数据库事务 ACID 原理讲解，拆解事务四大特性，理解事务隔离、原子性，明白事务如何保障数据安全。
 | 原文链接：http://wiki.mljc3b.asia/arts/592796.Doc

原标题：Security：SSRF服务端请求伪造漏洞防御
简介：简易日志收集集中管理方案，搭建轻量日志收集方案，把多服务日志汇总，集中检索查看日志信息。
 | 原文链接：http://wiki.mljc3b.asia/arts/668765.Doc

原标题：开发复盘：批量任务进度持久化实现方案
简介：golang excel 生成导出高性能方案，excelize 流式生成 excel，百万行数据导出，规避内存溢出。
 | 原文链接：http://wiki.mljc3b.asia/arts/782776.Doc

原标题：布隆过滤器数据高效去重实现
简介：golang grpc 客户端流上传数据，客户端流式请求，客户端分批上传数据到服务端，适合大文件传输。
 | 原文链接：http://wiki.mljc3b.asia/arts/973460.Doc

原标题：设计思考：业务系统中什么时候不要用微服务
简介：golang CPU 绑定亲和性设置 go 程序，设置进程 CPU 亲和绑定核心，减少 CPU 调度开销，提升计算性能。
 | 原文链接：http://wiki.mljc3b.asia/arts/396052.Doc

原标题：Troubleshooting：k8s镜像拉取失败镜像仓库网络问题
简介：golang interface 接口使用避坑，interface 判 nil 坑点，理解接口底层结构，避免判空逻辑失效。
 | 原文链接：http://wiki.mljc3b.asia/arts/564751.Doc

原标题：Issue复现：内存泄漏定位完整复盘记录
简介：golang 微服务网关简易实现，http 反向代理、路由匹配、鉴权限流，理解网关核心原理。
 | 原文链接：http://wiki.mljc3b.asia/arts/285887.Doc

原标题：Architecture：灰度、蓝绿、金丝雀发布架构对比
简介：golang go select 多路等待 channel，select 等待多个 channel，default 非阻塞，超时等待 channel。
 | 原文链接：http://wiki.mljc3b.asia/arts/506555.Doc

原标题：golang 系统设计集成测试数据库回滚重置方案
简介：Docker 容器网络不通排查，排查容器网络模式、端口映射、防火墙，解决容器之间、容器外部网络不通。
 | 原文链接：http://wiki.mljc3b.asia/arts/666151.Doc

原标题：线上异常：时间时区问题，定时任务执行偏移
简介：文件编码统一随机乱码修复，统一项目全部文件读写编码，消除随机中文乱码，保证文本处理稳定。
 | 原文链接：http://wiki.mljc3b.asia/arts/263363.Doc

原标题：Debug：HTTPS握手失败TLS版本兼容问题
简介：golang redis bloom 布隆过滤器 go‑redis，go‑redis 布隆过滤器，海量数据判断是否存在，减少数据库查询。
 | 原文链接：http://wiki.mljc3b.asia/arts/700211.Doc

原标题：Practice：实现业务id生成不连续有序ID方案
简介：golang go mod exclude 排除依赖版本，exclude 排除有问题依赖版本，规避有 bug 的第三方包。
 | 原文链接：http://wiki.mljc3b.asia/arts/477330.Doc

原标题：开发记录：服务优雅关闭释放资源完整实现
简介：开源源码阅读拆解学习思路，分享阅读大型开源项目方法，从入口文件逐层拆解模块，降低源码学习门槛。
 | 原文链接：http://wiki.mljc3b.asia/arts/991111.Doc

原标题：移动端适配 rem vw 方案对比
简介：Nginx 缓冲区调优大文件上传，调大 Nginx 请求缓冲区，支持客户端上传大体积文件，避免上传被截断。
 | 原文链接：http://wiki.mljc3b.asia/arts/373200.Doc

原标题：golang 系统设计 monorepo 仓库管理方案
简介：Cookie 跨环境登录配置调整，调整 Cookie 域、Secure 属性，适配开发测试生产环境，修复登录失效。
 | 原文链接：http://wiki.mljc3b.asia/arts/751929.Doc

原标题：实践：数据库备份脚本自动化编写实践
简介：golang interface {} 类型断言类型转换，类型断言 ok 模式，避免断言失败触发 panic。
 | 原文链接：http://wiki.mljc3b.asia/arts/118529.Doc

原标题：安全笔记：请求头伪造IP漏洞防护
简介：golang mqtt 客户端 go 开发物联网，paho.mqtt.golang 实现 mqtt 客户端，物联网设备消息收发。
 | 原文链接：http://wiki.mljc3b.asia/arts/010241.Doc

三、实战开发｜Practice
原标题：优化实践：Redis管道、批量命令减少网络往返
简介：golang 数据库分表策略按时间分片，按时间维度分表，历史数据拆分，单表数据量控制保证查询性能。
 | 原文链接：http://wiki.mljc3b.asia/arts/747296.Doc

原标题：浏览器内存泄漏排查前端页面
简介：golang 信号捕获程序退出处理，Go 捕获操作系统信号，做资源回收，控制程序退出流程。
 | 原文链接：http://wiki.mljc3b.asia/arts/896367.Doc

原标题：Practice：实现异步任务结果查询回调实践
简介：golang 大内存分配 GC 抖动规避，避免瞬时大量对象创建，分批处理，防止 GC 抖动业务抖动。
 | 原文链接：http://wiki.mljc3b.asia/arts/161922.Doc

原标题：golang ip 限流黑名单实现方案
简介：golang go1.18 + 泛型基础实操，go 泛型基础语法，泛型函数泛型类型，实现通用工具函数。
 | 原文链接：http://wiki.mljc3b.asia/arts/751658.Doc

原标题：Fork 开源项目同步上游代码
简介：golang html 模板防 xss 自动转义，理解 go html/template 自动转义，防止 XSS 攻击，处理不需要转义场景。
 | 原文链接：http://wiki.mljc3b.asia/arts/943664.Doc

原标题：Issue：防火墙拦截ICMP，MTU问题网络丢包
简介：golang 服务注册 etcd 简单示例，etcd 实现服务注册发现，微服务实例注册元数据，客户端发现节点。
 | 原文链接：http://wiki.mljc3b.asia/arts/748701.Doc

原标题：新手向：开源项目fork与同步上游代码
简介：前端 pdf 预览渲染方案对比，对比前端 PDF 预览库，分析性能、兼容性，给出业务选型参考。
 | 原文链接：http://wiki.mljc3b.asia/arts/085592.Doc

原标题：OpenSource：大型仓库Git历史清理瘦身实操
简介：vite 插件开发自定义构建逻辑，开发自定义 vite 插件，介入构建生命周期，实现项目个性化构建逻辑。
 | 原文链接：http://wiki.mljc3b.asia/arts/137844.Doc

原标题：踩坑记录：端口被占用导致服务启动失败
简介：消息队列重复消费业务处理，实现消息消费幂等，处理重复投递消息，保证多次消费业务结果一致。
 | 原文链接：http://wiki.mljc3b.asia/arts/396592.Doc

原标题：性能笔记：线程池参数调优任务队列策略
简介：react 状态管理方案选型对比，对比 Redux、Zustand 等 React 状态管理库，分析适用业务场景辅助选型。
 | 原文链接：http://wiki.mljc3b.asia/arts/545441.Doc

原标题：依赖安装失败全方位排错
简介：golang 结构体 json 序列化坑点，梳理 Go 结构体 JSON 序列化高频坑点，字段大小写、零值处理问题。
 | 原文链接：http://wiki.mljc3b.asia/arts/259541.Doc

原标题：golang lru 缓存淘汰算法编写
简介：golang 优雅关闭 grpc 服务示例，gRPC 服务优雅关闭，等待现有请求处理完成再停止服务。
 | 原文链接：http://wiki.mljc3b.asia/arts/998076.Doc

原标题：调优方案：MySQL缓冲池参数性能调优实践
简介：新手参与开源社区贡献指南，介绍开源社区基础规则，讲解阅读 issue、提交 PR 流程，指导开发者参与开源贡献。
 | 原文链接：http://wiki.mljc3b.asia/arts/946299.Doc

原标题：golang redis pipeline 原子性说明
简介：golang gorm 子查询嵌套查询写法，Gorm 实现子查询、嵌套查询，复杂条件查询简化代码编写。
 | 原文链接：http://wiki.mljc3b.asia/arts/641403.Doc

原标题：golang 系统设计敏感数据加密存储方案
简介：开发环境变量配置全平台教程，区分 Windows、macOS、Linux 系统，讲解环境变量配置、加载优先级与常见失效原因。
 | 原文链接：http://wiki.mljc3b.asia/arts/722174.Doc

原标题：DevOps：制品仓库管理二进制产物版本
简介：golang go 程序 CPU 占用高定位步骤，pprof 定位热点函数，分析 CPU 高占用，优化耗时代码逻辑。
 | 原文链接：http://wiki.mljc3b.asia/arts/159569.Doc

原标题：线上故障：Redis内存淘汰策略错误数据丢失
简介：golang net/http/httptest 服务端模拟，httptest.NewRecorder 记录 handler 响应，校验返回状态码 body。
 | 原文链接：http://wiki.mljc3b.asia/arts/488396.Doc

原标题：效率笔记：GitWorkflow团队协作规范模板
简介：golang ip 限流黑名单实现方案，基于 IP 做限流与黑名单，拦截恶意 IP 访问，保护接口服务。
 | 原文链接：http://wiki.mljc3b.asia/arts/910382.Doc

原标题：golang docker 镜像构建最佳实践
简介：文件锁正确使用避免死锁，合理使用文件锁，控制多进程访问同一个文件，规避文件锁死锁现象。
 | 原文链接：http://wiki.mljc3b.asia/arts/544034.Doc

原标题：部署实践：服务器时间同步chrony配置
简介：golang excel 大文件读取流式解析，流式读取大 excel 文件，逐行解析数据，不加载全部内容进内存。
 | 原文链接：http://wiki.mljc3b.asia/arts/122417.Doc

原标题：排错：容器OOM被杀死，日志看不到任何输出
简介：nestjs 框架模块化项目搭建，从零搭建 NestJS 项目，模块化拆分业务，搭建规范后端项目骨架。
 | 原文链接：http://wiki.mljc3b.asia/arts/120510.Doc

原标题：踩坑：消息队列消息堆积，消费者处理能力不足
简介：集成测试业务流程编写示例，编写业务流程集成测试，覆盖完整业务链路，验证模块之间协同工作是否正常。
 | 原文链接：http://wiki.mljc3b.asia/arts/772731.Doc

原标题：golang docker 私有仓库搭建使用
简介：golang grpc 服务端流推送数据，服务端流式响应，服务端持续向客户端推送多条响应消息。
 | 原文链接：http://wiki.mljc3b.asia/arts/385623.Doc

原标题：缓存基础原理与简单代码实现
简介：预编译 SQL 防注入实现，使用预编译 SQL 方式，杜绝 SQL 注入风险，提升数据库访问层安全能力。
 | 原文链接：http://wiki.mljc3b.asia/arts/232430.Doc

原标题：golang 系统设计分布式配置中心思路
简介：golang go‑fuzz 模糊测试开发，go fuzz 模糊测试，自动构造异常输入，发现代码隐藏 bug。
 | 原文链接：http://wiki.mljc3b.asia/arts/725334.Doc

原标题：golang websocket 服务端开发
简介：golang 子进程超时杀死防止挂住，context 控制子进程超时，超时强制杀掉子进程，避免子进程僵尸。
 | 原文链接：http://wiki.mljc3b.asia/arts/784441.Doc

原标题：golang 系统设计数据库表设计通用规范模板
简介：golang context.WithValue 传递元数据，WithValue 只传 traceId 鉴权元数据，不要传业务大对象。
 | 原文链接：http://wiki.mljc3b.asia/arts/766299.Doc

原标题：Issue：系统fd快速上涨进程慢慢卡死
简介：golang gorm select 指定查询字段，指定查询字段，避免查询全部字段，减少数据传输，提升查询性能。
 | 原文链接：http://wiki.mljc3b.asia/arts/837263.Doc

原标题：Practice：实现异步回调处理通用组件封装
简介：前端工程化 webpack 打包优化，针对 webpack 项目做打包调优，分包、压缩、Tree‑Shaking，缩减包体积。
 | 原文链接：http://wiki.mljc3b.asia/arts/645000.Doc

原标题：多线程线程安全脏数据规避
简介：golang os 环境变量读取设置，os.Getenv os.Setenv os.Unsetenv 读写环境变量，环境变量多值处理。
 | 原文链接：http://wiki.mljc3b.asia/arts/662135.Doc

原标题：golang 系统设计本地缓存过期淘汰策略选型
简介：前端错误监控上报系统搭建，搭建前端错误监控，捕获页面 JS 错误，上报后端，快速发现线上页面 bug。
 | 原文链接：http://wiki.mljc3b.asia/arts/606071.Doc

原标题：数据库主从延迟业务兼容处理
简介：express 请求参数校验处理，接入参数校验库，校验入参，拦截非法参数，提前拦截错误请求。
 | 原文链接：http://wiki.mljc3b.asia/arts/752342.Doc

原标题：git cherry‑pick 规范操作防 bug
简介：Dockerfile 编写容器打包实战，讲解 Dockerfile 指令含义，编写镜像构建脚本，将本地项目打包成可分发容器镜像。
 | 原文链接：http://wiki.mljc3b.asia/arts/230952.Doc

原标题：快速入门gRPC基础概念与简单示例
简介：golang redis hyperloglog 基数统计，hyperloglog 统计 UV 基数，海量数据去重统计，极低内存开销。
 | 原文链接：http://wiki.mljc3b.asia/arts/936047.Doc

原标题：零基础理解会话、Cookie、Session基础
简介：业务错误码完整落地实践，落地完整业务错误码，枚举全部业务异常，统一返回，配套文档说明。
 | 原文链接：http://wiki.mljc3b.asia/arts/337992.Doc

原标题：Issue：容器日志驱动配置错误日志全部丢失
简介：golang 容器时区设置镜像构建处理，镜像内部设置正确时区，解决容器时间与宿主机不一致。
 | 原文链接：http://wiki.mljc3b.asia/arts/110363.Doc

原标题：性能笔记：DNS缓存优化减少域名解析开销
简介：静态博客部署 GitHub Pages 教程，将静态博客项目部署至 GitHub Pages，完成线上访问，快速搭建个人技术博客站点。
 | 原文链接：http://wiki.mljc3b.asia/arts/042818.Doc

原标题：内存溢出问题现象识别排查
简介：golang 分布式锁 redis 实现，基于 Redis 实现 Go 分布式锁，解决多实例并发竞争资源问题。
 | 原文链接：http://wiki.mljc3b.asia/arts/560163.Doc

原标题：预编译 SQL 防注入实现
简介：数据库分表存储大表优化方案，对超大数据表做分表，拆分数据，降低单表数据量提升查询性能。
 | 原文链接：http://wiki.mljc3b.asia/arts/595194.Doc

原标题：零基础学习简单正则表达式实战案例
简介：golang rsa 非对称加密签名验签，RSA 非对称加密与签名验签，实现非对称安全通信。
 | 原文链接：http://wiki.mljc3b.asia/arts/979181.Doc

四、架构设计｜Architecture
原标题：任务执行锁防止并发重复调度
简介：缓存穿透击穿雪崩全套防护，完整梳理缓存三大问题，落地全套防护策略，保障缓存层稳定运行。
 | 原文链接：http://wiki.mljc3b.asia/arts/243374.Doc

原标题：踩坑：对象未释放，长时间运行内存持续上涨
简介：golang goroutine 池任务调度，实现 goroutine 池，复用协程，频繁任务场景减少协程创建销毁开销。
 | 原文链接：http://wiki.mljc3b.asia/arts/358855.Doc

原标题：nestjs 拦截器过滤器管道实战
简介：golang cgroup 读取容器资源限制，go 程序读取 cgroup，获取容器 cpu 内存限额，适配容器环境。
 | 原文链接：http://wiki.mljc3b.asia/arts/044602.Doc

原标题：golang redis 锁超时业务处理
简介：golang go 依赖漏洞检测 govulncheck，govulncheck 扫描依赖安全漏洞，发现项目供应链风险。
 | 原文链接：http://wiki.mljc3b.asia/arts/493232.Doc

原标题：golang 系统设计内部服务契约测试简单思路
简介：golang go decimal 定点小数金额计算，decimal 库处理金额，规避 float64 精度丢失，财务计算。
 | 原文链接：http://wiki.mljc3b.asia/arts/184664.Doc

原标题：golang 系统设计逻辑删除物理删除选型对比
简介：golang GC 调优 GOGC 参数调整，调整 GOGC 阈值，控制 GC 触发时机，权衡内存占用与 CPU 开销。
 | 原文链接：http://wiki.mljc3b.asia/arts/125118.Doc

原标题：golang context 上下文传参讲解
简介：前端错误监控上报系统搭建，搭建前端错误监控，捕获页面 JS 错误，上报后端，快速发现线上页面 bug。
 | 原文链接：http://wiki.mljc3b.asia/arts/815117.Doc

原标题：golang redis 过期 key 监听业务
简介：Docker 容器网络不通排查，排查容器网络模式、端口映射、防火墙，解决容器之间、容器外部网络不通。
 | 原文链接：http://wiki.mljc3b.asia/arts/206140.Doc

原标题：架构笔记：分布式事务方案对比与业务取舍
简介：nodejs 消息队列消费服务开发，Node 开发消息队列消费端，监听队列消息执行业务逻辑，异步解耦业务。
 | 原文链接：http://wiki.mljc3b.asia/arts/711750.Doc

原标题：依赖版本冲突兼容修复方案
简介：golang rabbitmq 死信队列延迟消息，rabbitmq 实现死信、延迟消息，处理延时业务场景。
 | 原文链接：http://wiki.mljc3b.asia/arts/459421.Doc

原标题：消息队列重复消费业务处理
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://wiki.mljc3b.asia/arts/358746.Doc

原标题：golang url 参数编码处理方案
简介：golang go 终端 pty 伪终端操作，pty 启动子进程，模拟终端交互，实现交互式命令调用。
 | 原文链接：http://wiki.mljc3b.asia/arts/780845.Doc

原标题：踩坑：大事务引发数据库连接池耗尽
简介：golang base64 编码解码实操，Go Base64 编码解码示例，处理业务场景 Base64 格式数据转换。
 | 原文链接：http://wiki.mljc3b.asia/arts/101078.Doc

原标题：效率笔记：提升开发效率shell脚本小工具合集
简介：golang 优雅处理数据库事务，Go 数据库事务封装，正确处理事务提交回滚，保证业务数据一致性。
 | 原文链接：http://wiki.mljc3b.asia/arts/687528.Doc

原标题：安全笔记：GitHubAction密钥安全管理
简介：异步编程 Promise 执行流程解析，拆解异步执行顺序，理解回调与 Promise 差异，理清异步场景下代码执行逻辑。
 | 原文链接：http://wiki.mljc3b.asia/arts/748062.Doc

原标题：实战：数据库explain执行计划分析实操演练
简介：短信服务封装失败自动重试，封装短信发送组件，处理发送失败自动重试，兼容多短信服务商。
 | 原文链接：http://wiki.mljc3b.asia/arts/459098.Doc

原标题：容器资源限制防止宿主机过载
简介：golang http client 连接池调优，调优 Go HTTP Client 连接池参数，复用 TCP 连接，减少连接创建开销。
 | 原文链接：http://wiki.mljc3b.asia/arts/414449.Doc

原标题：WebSocket 断线重连稳定优化
简介：golang go 程序敏感信息禁止打印日志，密钥密码禁止输出日志，防止敏感信息日志泄露。
 | 原文链接：http://wiki.mljc3b.asia/arts/350551.Doc

?
