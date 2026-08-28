最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计日志轮转切割防止磁盘占满
简介：golang 模板函数自定义拓展，自定义 template 模板函数，在 html 模板调用自定义逻辑处理数据。
 | 原文链接：http://book.ybhiwr.asia/blog/7376152.sHtMl

原标题：架构笔记：数据库读写分离架构数据不一致应对
简介：golang 大内存分配 GC 抖动规避，避免瞬时大量对象创建，分批处理，防止 GC 抖动业务抖动。
 | 原文链接：http://book.ybhiwr.asia/blog/8837276.sHtMl

原标题：架构复盘：限流系统架构防止恶意流量冲击
简介：golang 本地消息表实现最终一致性，本地消息表 + 定时任务轮询，可靠消息实现分布式事务。
 | 原文链接：http://book.ybhiwr.asia/blog/7826348.sHtMl

原标题：golang docker 部署 prometheus 整套
简介：包管理器依赖缓存清理，清理本地依赖缓存，解决缓存旧包引发问题，拉取最新版本依赖包。
 | 原文链接：http://book.ybhiwr.asia/blog/6928592.sHtMl

原标题：golang 分布式上下文传递方案
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://book.ybhiwr.asia/blog/0312661.sHtMl

原标题：golang 信号量控制并发数量
简介：时间同步修复令牌提前过期，服务器时间不同步导致 JWT 令牌提前过期，同步系统时间解决异常。
 | 原文链接：http://book.ybhiwr.asia/blog/9950850.sHtMl

原标题：实践：前后端分离项目登录状态保持完整方案
简介：程序预加载加快服务启动速度，把高频使用资源提前预加载，减少请求阶段初始化，加快服务启动。
 | 原文链接：http://book.ybhiwr.asia/blog/6976654.sHtMl

原标题：Troubleshooting：防火墙安全组拦截访问请求
简介：DNS 解析异常第三方调用故障，排查 DNS 解析故障，修复域名解析，恢复第三方接口网络调用。
 | 原文链接：http://book.ybhiwr.asia/blog/6149115.sHtMl

原标题：安全实践：API密钥管理轮换最佳实践
简介：golang 时间时区处理避坑指南，Go 时间时区常见坑，时区转换，时间比较，规避时间逻辑错误。
 | 原文链接：http://book.ybhiwr.asia/blog/9039740.sHtMl

原标题：内网 DNS 不稳定随机报错排查
简介：golang 灰度发布流量权重路由实现，根据权重切分流量，部分流量访问新版本服务，实现灰度发布。
 | 原文链接：http://book.ybhiwr.asia/blog/5823157.sHtMl

原标题：golang 令牌桶限流中间件 gin
简介：golang go 爬虫 html 解析 goquery，goquery 解析 html 文档，css 选择器提取网页内容，实现网页数据抓取。
 | 原文链接：http://book.ybhiwr.asia/blog/5833461.sHtMl

原标题：Security：限流防爬虫防恶意攻击防护体系
简介：Nginx 静态代理负载均衡全套配置，一套 Nginx 配置示例，覆盖静态资源、反向代理、负载均衡场景。
 | 原文链接：http://book.ybhiwr.asia/blog/6536064.sHtMl

原标题：golang 系统设计状态字段枚举约束设计思路
简介：golang 环境变量读取与类型转换，读取系统环境变量，做类型转换默认值处理，适配多环境部署。
 | 原文链接：http://book.ybhiwr.asia/blog/9824717.sHtMl

原标题：Security：限流防爬虫防恶意攻击防护体系
简介：文件读写与异常捕获代码示例，演示文件读取写入操作，增加异常捕获逻辑，规避文件不存在、权限不足导致崩溃。
 | 原文链接：http://book.ybhiwr.asia/blog/7155781.sHtMl

原标题：前端静态缓存更新生效处理
简介：多套环境灵活切换配置方案，实现配置动态切换，通过环境变量、配置文件，快速切换开发测试生产环境。
 | 原文链接：http://book.ybhiwr.asia/blog/5415343.sHtMl

原标题：实战：搭建本地对象存储兼容S3协议demo
简介：灰度发布策略服务平滑升级，实现灰度发布逻辑，流量逐步切到新版本，出现问题快速回滚旧版本。
 | 原文链接：http://book.ybhiwr.asia/blog/6600317.sHtMl

原标题：DevOps：环境配置管理区分开发测试生产
简介：golang go 爬虫代理池轮换使用，http 代理池轮换，请求自动切换代理 IP，突破访问限制。
 | 原文链接：http://book.ybhiwr.asia/blog/2271802.sHtMl

原标题：golang docker 镜像体积优化技巧
简介：golang http MaxHeaderBytes 限制请求头，设置 http 最大请求头大小，防止超大 header 攻击。
 | 原文链接：http://book.ybhiwr.asia/blog/7015071.sHtMl

原标题：golang 系统设计一致性哈希原理讲解
简介：golang 命令行彩色输出终端，终端彩色文字输出，进度条交互，优化命令行工具用户体验。
 | 原文链接：http://book.ybhiwr.asia/blog/4149209.sHtMl

原标题：golang 系统设计缓存更新策略 cache aside 讲解
简介：golang json omitempty 零值坑，omitempty 会忽略零值，区分业务是否需要输出零值字段。
 | 原文链接：http://book.ybhiwr.asia/blog/6218643.sHtMl

原标题：调优方案：消息批量消费提升MQ处理吞吐量
简介：monorepo 项目多包管理最佳实践，monorepo 仓库管理多子包，统一版本管理，处理包之间互相依赖。
 | 原文链接：http://book.ybhiwr.asia/blog/8772631.sHtMl

原标题：golang grafana 监控面板简单配置
简介：灰度发布策略服务平滑升级，实现灰度发布逻辑，流量逐步切到新版本，出现问题快速回滚旧版本。
 | 原文链接：http://book.ybhiwr.asia/blog/4716114.sHtMl

原标题：golang 系统设计时间字段选型 datetime timestamp
简介：前后端交互跨域问题完整处理，讲解跨域产生原理，列举多种解决方案，适配开发、生产不同环境的跨域处理。
 | 原文链接：http://book.ybhiwr.asia/blog/6851848.sHtMl

原标题：golang redis 分布式锁 redisson 思路
简介：网关超时时间调优后端等待，调大网关向后端转发请求超时时间，给后端业务充足处理时间。
 | 原文链接：http://book.ybhiwr.asia/blog/4392304.sHtMl

原标题：效率笔记：批量处理文本命令行工具实战案例
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://book.ybhiwr.asia/blog/6494668.sHtMl

原标题：golang 系统设计 json 解析性能优化实操
简介：golang 协程数量监控统计方案，统计运行中 goroutine 数量，监控协程泄露，协程数量异常及时告警。
 | 原文链接：http://book.ybhiwr.asia/blog/4856671.sHtMl

原标题：Architecture：文件处理服务架构大文件内存规避
简介：golang go‑zero 监控指标埋点，go‑zero 内置 metrics 监控，上报业务指标对接监控平台。
 | 原文链接：http://book.ybhiwr.asia/blog/1432336.sHtMl

原标题：浏览器缓存强制刷新方案
简介：WebSocket 断线重连稳定优化，增加 WebSocket 断线自动重连逻辑，处理网络抖动，维持长连接稳定。
 | 原文链接：http://book.ybhiwr.asia/blog/4065595.sHtMl

原标题：新手教程：本地项目初始化gitignore配置
简介：hosts 配置本地回环访问修复，修改 hosts 配置，修复 127.0.0.1 解析异常，本地服务访问失败问题。
 | 原文链接：http://book.ybhiwr.asia/blog/5186936.sHtMl

原标题：快速入门WebSocket，实现简易双向通信demo
简介：golang cgroup 读取容器资源限制，go 程序读取 cgroup，获取容器 cpu 内存限额，适配容器环境。
 | 原文链接：http://book.ybhiwr.asia/blog/4005253.sHtMl

原标题：golang mysql 时间类型选型避坑
简介：golang go‑pg postgres 客户端实操，go‑pg 操作 PostgreSQL 数据库，CRUD 关联查询业务开发。
 | 原文链接：http://book.ybhiwr.asia/blog/3689443.sHtMl

原标题：golang k8s hpa 水平 pod 自动扩缩容
简介：golang go select 多路等待 channel，select 等待多个 channel，default 非阻塞，超时等待 channel。
 | 原文链接：http://book.ybhiwr.asia/blog/6545079.sHtMl

原标题：优化实践：LRU本地缓存优化热点访问性能
简介：golang map 并发读写 panic 解决方案，map 非并发安全，讲解加锁、sync.map 方案解决并发读写崩溃。
 | 原文链接：http://book.ybhiwr.asia/blog/3383782.sHtMl

原标题：Hands‑on：简易图片压缩处理服务demo
简介：golang 跨域处理中间件编写，Gin 跨域中间件开发，处理预检 OPTIONS 请求，解决浏览器跨域报错。
 | 原文链接：http://book.ybhiwr.asia/blog/3715439.sHtMl

原标题：golang 系统设计 api 接口兼容性设计原则
简介：golang 分布式锁防死锁实现要点，锁超时、续期、锁持有者校验，避免锁死锁，保障分布式锁可靠性。
 | 原文链接：http://book.ybhiwr.asia/blog/6227633.sHtMl

原标题：golang redis 五种数据结构实战
简介：golang 时间时区处理避坑指南，Go 时间时区常见坑，时区转换，时间比较，规避时间逻辑错误。
 | 原文链接：http://book.ybhiwr.asia/blog/8405771.sHtMl

原标题：Practice：实现请求body重复读取中间件实践
简介：golang select 随机分支执行特性，多个 channel 就绪 select 随机选择，理解 select 行为特性。
 | 原文链接：http://book.ybhiwr.asia/blog/5127305.sHtMl

原标题：RPC 接口字段增减兼容处理
简介：golang 错误栈捕获打印方案，捕获错误完整调用堆栈，线上日志输出堆栈，快速定位错误发生代码位置。
 | 原文链接：http://book.ybhiwr.asia/blog/9202890.sHtMl

原标题：安全笔记：GitHubAction密钥安全管理
简介：超大数据集分页性能优化方案，对比不同分页方案，针对海量数据集做分页性能优化，解决越翻越慢。
 | 原文链接：http://book.ybhiwr.asia/blog/4000998.sHtMl

原标题：设计思考：业务埋点架构日志埋点设计原则
简介：线上接口超时故障排查思路，从网络、数据库、代码逻辑逐层排查接口超时，定位慢请求根因。
 | 原文链接：http://book.ybhiwr.asia/blog/5946757.sHtMl


二、踩坑排错｜Troubleshooting
原标题：vue3 组合式 API 业务开发实战
简介：golang 结构体零值可用性原则，go 结构体尽量做到零值可用，不用初始化直接使用提升易用性。
 | 原文链接：http://book.ybhiwr.asia/blog/3076589.sHtMl

原标题：零基础理解依赖管理与包管理器
简介：golang gorm select 指定查询字段，指定查询字段，避免查询全部字段，减少数据传输，提升查询性能。
 | 原文链接：http://book.ybhiwr.asia/blog/3208967.sHtMl

原标题：入门实践：简单重试逻辑封装实现
简介：容器资源限制防止宿主机过载，设置容器 CPU 内存资源上限，避免单个容器耗尽宿主机全部硬件资源。
 | 原文链接：http://book.ybhiwr.asia/blog/2481616.sHtMl

原标题：golang 系统设计熔断算法 hystrix 思路
简介：前后端会话登录状态持久化，实现登录状态持久存储，重启服务登录状态不丢失，保障会话稳定性。
 | 原文链接：http://book.ybhiwr.asia/blog/7939118.sHtMl

原标题：业务错误码完整落地实践
简介：golang cgo 调用 C 语言代码示例，cgo 调用 C 函数，go 与 C 互相调用，对接 C 语言库能力。
 | 原文链接：http://book.ybhiwr.asia/blog/6038813.sHtMl

原标题：Issue：文件句柄耗尽，服务缓慢卡死复盘
简介：golang uuid 生成多种版本实现，生成 uuid v1 v4，生成唯一标识，业务用于单据编号场景。
 | 原文链接：http://book.ybhiwr.asia/blog/3061228.sHtMl

原标题：golang prometheus 指标暴露实现
简介：前端国际化多语言方案落地，搭建前端多语言国际化方案，切换语言，页面文本自动切换对应语种。
 | 原文链接：http://book.ybhiwr.asia/blog/3096327.sHtMl

原标题：golang 系统设计字符串拼接性能优化技巧
简介：nodejs 中间件模式原理剖析，拆解 Node 中间件设计模式，理解请求逐层处理流转的底层原理。
 | 原文链接：http://book.ybhiwr.asia/blog/5509986.sHtMl

原标题：部署复盘：数据库主从备份恢复演练实践
简介：跨域偶现失败配置修复，解决跨域问题时而复现时而正常，定位配置漏配、请求头异常等隐性问题。
 | 原文链接：http://book.ybhiwr.asia/blog/4480487.sHtMl

原标题：记一次第三方SDK版本兼容引发线上故障
简介：nestjs 全局返回格式统一处理，Nest 全局拦截器统一包装接口返回数据，对外输出标准化响应格式。
 | 原文链接：http://book.ybhiwr.asia/blog/3271365.sHtMl

原标题：实战项目：本地模拟磁盘IO高负载观察服务行为
简介：数据库读写分离性能优化，讲解读写分离原理，主库写入从库查询，分担数据库查询压力，提升查询性能。
 | 原文链接：http://book.ybhiwr.asia/blog/6673755.sHtMl

原标题：golang 接口限流中间件开发
简介：nestjs 框架模块化项目搭建，从零搭建 NestJS 项目，模块化拆分业务，搭建规范后端项目骨架。
 | 原文链接：http://book.ybhiwr.asia/blog/8854937.sHtMl

原标题：方案设计：批量大数据导出系统架构拆解
简介：文件锁正确使用避免死锁，合理使用文件锁，控制多进程访问同一个文件，规避文件锁死锁现象。
 | 原文链接：http://book.ybhiwr.asia/blog/9930666.sHtMl

原标题：golang redis pipeline 原子性说明
简介：golang kitex 超时重试熔断配置，kitex 配置调用超时、重试、熔断策略，保障微服务调用稳定性。
 | 原文链接：http://book.ybhiwr.asia/blog/7120232.sHtMl

原标题：golang mysql 读写分离简单实现
简介：golang go 服务日志输出 journald，systemd journald 接收程序 stdout 日志，统一管理服务日志。
 | 原文链接：http://book.ybhiwr.asia/blog/4133521.sHtMl

原标题：实战项目：本地搭建Prometheus监控完整demo
简介：golang os/exec 安全执行外部命令，规避命令注入漏洞，参数分离，禁止拼接命令字符串执行。
 | 原文链接：http://book.ybhiwr.asia/blog/7231084.sHtMl

原标题：JWT 工具封装令牌刷新过期
简介：golang 跨域处理中间件编写，Gin 跨域中间件开发，处理预检 OPTIONS 请求，解决浏览器跨域报错。
 | 原文链接：http://book.ybhiwr.asia/blog/8722673.sHtMl

原标题：Performance：避免大报文，减少内存占用优化
简介：线上接口超时故障排查思路，从网络、数据库、代码逻辑逐层排查接口超时，定位慢请求根因。
 | 原文链接：http://book.ybhiwr.asia/blog/3075824.sHtMl

原标题：部署实践：多实例服务部署无状态改造
简介：浮点计算精度错误处理方案，讲解浮点数计算精度丢失问题，使用合适数据类型，规避金额计算出错。
 | 原文链接：http://book.ybhiwr.asia/blog/1051839.sHtMl

原标题：实战项目：GitSubmodule管理多仓库实践
简介：golang go 项目安全检查漏洞扫描，扫描 go 项目依赖漏洞，代码安全审计，规避安全风险。
 | 原文链接：http://book.ybhiwr.asia/blog/2980077.sHtMl

原标题：nodejs 读取大文件 csv 处理方案
简介：接口签名校验防篡改实现，实现请求签名验签逻辑，校验请求参数未被篡改，提升接口调用安全性。
 | 原文链接：http://book.ybhiwr.asia/blog/3010079.sHtMl

原标题：Issue：本地可以访问，容器内部网络不通
简介：业务错误码完整落地实践，落地完整业务错误码，枚举全部业务异常，统一返回，配套文档说明。
 | 原文链接：http://book.ybhiwr.asia/blog/8424451.sHtMl

原标题：golang github actions 缓存依赖提速
简介：golang testing.TB Helper 标记辅助函数，t.Helper 标记辅助函数，报错打印真实调用位置。
 | 原文链接：http://book.ybhiwr.asia/blog/6124014.sHtMl

原标题：golang 系统设计对象池复用减少内存分配
简介：浏览器缓存强制刷新方案，设置 HTTP 缓存头，处理浏览器缓存旧静态资源，让用户加载更新后的页面。
 | 原文链接：http://book.ybhiwr.asia/blog/2553566.sHtMl

原标题：Troubleshoot：MySQL字符集utf8非utf8mb4emoji报错
简介：golang 服务注册 etcd 简单示例，etcd 实现服务注册发现，微服务实例注册元数据，客户端发现节点。
 | 原文链接：http://book.ybhiwr.asia/blog/7300774.sHtMl

原标题：开发记录：文件锁实现多进程互斥实践
简介：golang gin 框架接口开发实战，Gin 框架搭建 HTTP 服务，开发增删改查接口，快速完成后端接口开发。
 | 原文链接：http://book.ybhiwr.asia/blog/6229899.sHtMl

原标题：安全笔记：文件下载接口路径校验安全
简介：golang go 零停机升级实践要点，socket 继承，流量无损，旧连接处理完毕后旧进程退出。
 | 原文链接：http://book.ybhiwr.asia/blog/4722005.sHtMl

原标题：golang docker compose 部署 minio
简介：golang influxdb 时序数据库读写操作，influxdb 存储时序指标，业务指标监控数据存取。
 | 原文链接：http://book.ybhiwr.asia/blog/2596598.sHtMl

原标题：golang etcd 配置中心简单使用
简介：golang gorm 子查询嵌套查询写法，Gorm 实现子查询、嵌套查询，复杂条件查询简化代码编写。
 | 原文链接：http://book.ybhiwr.asia/blog/0881058.sHtMl

原标题：golang mock 单元测试编写技巧
简介：容器资源限制防止宿主机过载，设置容器 CPU 内存资源上限，避免单个容器耗尽宿主机全部硬件资源。
 | 原文链接：http://book.ybhiwr.asia/blog/2972941.sHtMl

原标题：快速上手简单的限流逻辑模拟实现
简介：golang 错误处理最佳实践汇总，Go 错误处理规范，包装错误，堆栈携带，拒绝简单忽略错误。
 | 原文链接：http://book.ybhiwr.asia/blog/3748774.sHtMl

原标题：缓存过期策略优化防业务故障
简介：灰度发布策略服务平滑升级，实现灰度发布逻辑，流量逐步切到新版本，出现问题快速回滚旧版本。
 | 原文链接：http://book.ybhiwr.asia/blog/6526117.sHtMl

原标题：文件句柄上限调整上传随机失败
简介：CLI 批量处理工具文件操作开发，开发命令行批量工具，实现批量文件处理，提升重复文件处理效率。
 | 原文链接：http://book.ybhiwr.asia/blog/7531515.sHtMl

原标题：golang 静态编译缩小镜像体积
简介：golang 僵尸进程处理 go 程序，正确等待子进程退出，避免产生僵尸进程，占用系统进程表。
 | 原文链接：http://book.ybhiwr.asia/blog/6207623.sHtMl

原标题：避坑：ORM框架隐式查询产生大量慢SQL
简介：golang context 上下文传参讲解，讲解 Context 使用场景，传递元数据、控制协程超时取消，规范协程控制。
 | 原文链接：http://book.ybhiwr.asia/blog/8135782.sHtMl

原标题：golang 时间时区处理避坑指南
简介：golang http 服务并发连接数限制，自定义 listener 统计连接数量，限制最大并发连接数保护服务。
 | 原文链接：http://book.ybhiwr.asia/blog/4741718.sHtMl

原标题：Debug：请求头过大Nginx拒绝连接报错
简介：golang os 文件目录操作大全，文件创建删除重命名，目录遍历，文件信息读取，完成各类文件系统操作。
 | 原文链接：http://book.ybhiwr.asia/blog/8166210.sHtMl

原标题：站内邮件消息通知功能开发
简介：nodejs redis 缓存业务实战，Node 对接 Redis 实现业务缓存，缓存热点查询结果，减轻数据库压力。
 | 原文链接：http://book.ybhiwr.asia/blog/0771732.sHtMl

原标题：Practice：实现接口幂等性多种方案对比实践
简介：本地数据库开发环境搭建指南，讲解数据库安装配置、账号权限设置、连接测试，快速搭建用于开发调试的数据库实例。
 | 原文链接：http://book.ybhiwr.asia/blog/4111534.sHtMl

原标题：golang kafka 消息丢失重复消费
简介：接口签名验签完整安全方案，一套完整接口签名方案，包含签名生成、请求携带、服务端验签校验。
 | 原文链接：http://book.ybhiwr.asia/blog/4508820.sHtMl

三、实战开发｜Practice
原标题：接口请求重试容错机制实现
简介：API 接口调试与异常处理实战，覆盖接口请求、参数组装、错误捕获，提供调试思路，高效定位接口返回异常问题。
 | 原文链接：http://book.ybhiwr.asia/blog/8892004.sHtMl

原标题：Architecture：API网关核心能力与组件拆分
简介：golang 定时任务任务持久化存储，定时任务持久化到数据库，服务重启任务不丢失，动态管理任务。
 | 原文链接：http://book.ybhiwr.asia/blog/5044475.sHtMl

原标题：开发复盘：分布式会话共享多种方案实践
简介：浏览器缓存强制刷新方案，设置 HTTP 缓存头，处理浏览器缓存旧静态资源，让用户加载更新后的页面。
 | 原文链接：http://book.ybhiwr.asia/blog/6933307.sHtMl

原标题：文件批量导入导出功能实现
简介：monorepo 项目多包管理最佳实践，monorepo 仓库管理多子包，统一版本管理，处理包之间互相依赖。
 | 原文链接：http://book.ybhiwr.asia/blog/6578410.sHtMl

原标题：golang 优雅关闭 grpc 服务示例
简介：golang go sum 校验失败处理方案，go sum 校验不匹配，排查网络代理，清理缓存解决校验报错。
 | 原文链接：http://book.ybhiwr.asia/blog/2589100.sHtMl

原标题：开发复盘：数据库批量更新优化性能实践
简介：静态资源 404 路径打包修复，修复打包后静态资源访问 404，调整资源输出路径，保证资源正常加载。
 | 原文链接：http://book.ybhiwr.asia/blog/8570828.sHtMl

原标题：Architecture：对象存储接入业务整体架构
简介：golang math 包常用数学函数，绝对值取整平方根三角函数，业务数学计算工具。
 | 原文链接：http://book.ybhiwr.asia/blog/3012990.sHtMl

原标题：Troubleshooting：K8sPodOOMKilled完整排查流程
简介：golang grpc 拦截器开发鉴权日志，开发 grpc 服务端拦截器，统一做鉴权、日志打印、异常捕获处理。
 | 原文链接：http://book.ybhiwr.asia/blog/6229785.sHtMl

原标题：日志驱动异常日志不输出修复
简介：定时任务周期调度 demo 开发，实现简单定时调度程序，按时间周期执行业务逻辑，理解定时任务运行机制。
 | 原文链接：http://book.ybhiwr.asia/blog/0747648.sHtMl

原标题：实战：容器内执行调试排错完整实操流程
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://book.ybhiwr.asia/blog/4356445.sHtMl

原标题：Performance：数据库分表解决单表过大性能衰减
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：http://book.ybhiwr.asia/blog/4489075.sHtMl

原标题：Practice：实现跨机器文件同步脚本实践
简介：分布式 ID 生成器高并发实现，实现高性能分布式 ID 生成器，适配高并发业务，生成全局唯一 ID。
 | 原文链接：http://book.ybhiwr.asia/blog/6512717.sHtMl

原标题：零基础学习简单正则表达式实战案例
简介：golang 协程泄露问题排查方法，识别 Go 协程泄露现象，分析泄露场景，给出排查定位协程泄露手段。
 | 原文链接：http://book.ybhiwr.asia/blog/0550698.sHtMl

原标题：Troubleshooting：数据库主从延迟带来查询数据不一致
简介：数据库索引重建提升查询速度，针对碎片化索引，重建数据库索引，恢复 SQL 查询执行性能。
 | 原文链接：http://book.ybhiwr.asia/blog/0001347.sHtMl

原标题：排错：静态资源CDN缓存未刷新旧资源持续返回
简介：Docker Compose 一键搭建本地栈，使用 Compose 编排多个容器，一键拉起全套开发依赖服务。
 | 原文链接：http://book.ybhiwr.asia/blog/8223908.sHtMl

原标题：文件编码统一随机乱码修复
简介：前端权限路由动态生成实现，根据后端返回权限，动态生成前端路由菜单，实现页面权限控制。
 | 原文链接：http://book.ybhiwr.asia/blog/9557378.sHtMl

原标题：项目实践：本地模拟多节点分布式系统实践
简介：Git LFS 大文件推送失败解决，配置 Git LFS，处理仓库大文件，解决大文件推送报错推送失败。
 | 原文链接：http://book.ybhiwr.asia/blog/1894251.sHtMl

原标题：golang docker compose 环境变量
简介：golang 命令行交互 cobra 开发 cli，cobra 库开发功能完善命令行工具，子命令参数标志解析。
 | 原文链接：http://book.ybhiwr.asia/blog/2451124.sHtMl

原标题：调优方案：数据库索引不要过度建立，权衡写性能
简介：容器资源限制防止宿主机过载，设置容器 CPU 内存资源上限，避免单个容器耗尽宿主机全部硬件资源。
 | 原文链接：http://book.ybhiwr.asia/blog/2859348.sHtMl

原标题：Hands‑on：简易配置中心本地原型实现
简介：缓存穿透防护保护数据库，实现缓存穿透防护手段，拦截不存在的数据查询，避免请求直接打穿数据库。
 | 原文链接：http://book.ybhiwr.asia/blog/8199427.sHtMl

原标题：golang 互斥锁读写锁并发安全
简介：golang pprof 线上采集性能数据，线上环境采集 pprof 性能样本，不用停机，分析线上性能问题。
 | 原文链接：http://book.ybhiwr.asia/blog/8174389.sHtMl

原标题：golang redis set 集合去重业务
简介：golang 文件句柄耗尽排查处理，统计进程打开文件句柄，找到未关闭文件，修复句柄泄漏问题。
 | 原文链接：http://book.ybhiwr.asia/blog/1075004.sHtMl

原标题：golang 系统设计 tcc 事务简单原理业务示例
简介：golang go 值传递引用传递理解，go 全部为值传递，指针本质拷贝指针值，理清参数传递行为。
 | 原文链接：http://book.ybhiwr.asia/blog/4112186.sHtMl

原标题：golang 系统设计 vscode go 插件调试配置实操
简介：大事务拆分防止连接池耗尽，将执行时间很长的大事务拆分为小事务，减少事务占用连接时长。
 | 原文链接：http://book.ybhiwr.asia/blog/3349703.sHtMl

原标题：部署实践：服务器时间同步chrony配置
简介：golang pprof 线上采集性能数据，线上环境采集 pprof 性能样本，不用停机，分析线上性能问题。
 | 原文链接：http://book.ybhiwr.asia/blog/3045424.sHtMl

原标题：golang 系统设计基准测试 benchmark 编写
简介：golang go 模板缓存预编译模板，预编译 html 模板，程序启动加载，避免每次请求解析模板损耗性能。
 | 原文链接：http://book.ybhiwr.asia/blog/2344777.sHtMl

原标题：文件句柄耗尽资源泄露处理
简介：网络读取超时设置连接挂起防护，设置网络读取超时时间，防止请求无限挂起不返回，占用连接资源。
 | 原文链接：http://book.ybhiwr.asia/blog/5657632.sHtMl

原标题：开发复盘：分库分表本地模拟与数据路由实践
简介：golang go 锁竞争导致 CPU 飙升，识别锁竞争场景，减少锁粒度，优化并发逻辑降低 CPU 开销。
 | 原文链接：http://book.ybhiwr.asia/blog/3962936.sHtMl

原标题：实战：Redis过期回调实现业务事件通知实践
简介：正则表达式文本处理实战案例，结合业务场景演示正则匹配、提取、替换，处理手机号、邮箱等各类文本校验需求。
 | 原文链接：http://book.ybhiwr.asia/blog/6965781.sHtMl

原标题：golang redis zset 排行榜业务实现
简介：静态站点自动部署发布方案，配置流水线，代码更新自动构建静态站点并且部署上线，简化发布。
 | 原文链接：http://book.ybhiwr.asia/blog/9947183.sHtMl

原标题：踩坑：大报文传输，RPC消息超过大小限制
简介：golang embed 目录读取文件列表，embed 嵌入整个目录，读取目录下全部文件，做静态资源服务。
 | 原文链接：http://book.ybhiwr.asia/blog/3382443.sHtMl

原标题：golang 工具函数库封装思路
简介：monorepo 项目多包管理最佳实践，monorepo 仓库管理多子包，统一版本管理，处理包之间互相依赖。
 | 原文链接：http://book.ybhiwr.asia/blog/5972852.sHtMl

原标题：开源实践：开源项目如何写好PullRequest
简介：golang go work 多模块本地开发，go work 多模块本地同时开发，本地模块互相引用，无需推送仓库。
 | 原文链接：http://book.ybhiwr.asia/blog/8013034.sHtMl

原标题：golang 系统设计大流量削峰处理方案
简介：golang 字符编码转换 go 处理，iconv‑go 做编码转换 gbk utf8 互转，处理老旧系统 gbk 编码数据。
 | 原文链接：http://book.ybhiwr.asia/blog/0794824.sHtMl

原标题：golang websocket 服务端开发
简介：golang 多协程任务池并发控制，实现协程任务池，控制并发协程数量，防止无限制创建 goroutine。
 | 原文链接：http://book.ybhiwr.asia/blog/7486823.sHtMl

原标题：golang 数据库慢查询监控实现
简介：接口限流逻辑简单模拟实现，编写简易限流逻辑，限制接口访问频次，保护服务，避免短时间大量请求压垮系统。
 | 原文链接：http://book.ybhiwr.asia/blog/6618159.sHtMl

原标题：浮点计算精度错误处理方案
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://book.ybhiwr.asia/blog/6953582.sHtMl

原标题：golang 系统设计线程协程泄露定位方法
简介：前端水印防信息泄露实现，实现网页水印功能，页面叠加用户信息水印，防止页面截图信息外泄。
 | 原文链接：http://book.ybhiwr.asia/blog/4194938.sHtMl

原标题：golang 系统设计配置多环境隔离方案落地
简介：golang time 时间格式化参考时间牢记，2006‑01‑02T15:04:05Z07:00，掌握 go 时间格式化关键点。
 | 原文链接：http://book.ybhiwr.asia/blog/8619062.sHtMl

原标题：重复提交幂等防护再次讲解
简介：golang redis 客户端业务使用，Go Redis 客户端对接，实现缓存、计数器，适配各类 Redis 业务场景。
 | 原文链接：http://book.ybhiwr.asia/blog/0040258.sHtMl

四、架构设计｜Architecture
原标题：Debug：表单自动转义特殊字符业务逻辑出错
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：http://book.ybhiwr.asia/blog/0333190.sHtMl

原标题：异步编程 Promise 执行流程解析
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://book.ybhiwr.asia/blog/1883528.sHtMl

原标题：文件监控服务自动重启开发
简介：限流窗口绕过漏洞修复方案，修复限流时间窗口漏洞，避免攻击者绕过限流规则，保障接口防护有效。
 | 原文链接：http://book.ybhiwr.asia/blog/7345250.sHtMl

原标题：排错：多实例部署session共享失效登录失效
简介：ORM 框架数据库增删改查实操，使用 ORM 框架完成数据库基础操作，减少手写 SQL，简化业务层数据库交互代码。
 | 原文链接：http://book.ybhiwr.asia/blog/4783922.sHtMl

原标题：后端登录鉴权模块完整开发
简介：golang gorm 软删除实现逻辑，Gorm 开启软删除，删除数据仅标记，数据保留可恢复，满足业务数据留存。
 | 原文链接：http://book.ybhiwr.asia/blog/9875226.sHtMl

原标题：部署实践：容器优雅停机配置处理信号
简介：golang io.LimitReader 限制读取字节数，LimitReader 限制最大读取，防止读取超大数据。
 | 原文链接：http://book.ybhiwr.asia/blog/2340227.sHtMl

原标题：golang 系统设计代码仓库权限管理方案
简介：Mock 接口服务快速搭建实操，搭建模拟后端接口，自定义返回数据、延迟响应，前端开发阶段无需依赖真实后端服务。
 | 原文链接：http://book.ybhiwr.asia/blog/1564491.sHtMl

原标题：nodejs jwt 登录鉴权完整示例
简介：golang prometheus client 业务埋点实操，prometheus client‑go 业务埋点，计数器、仪表盘、直方图指标开发。
 | 原文链接：http://book.ybhiwr.asia/blog/8854957.sHtMl

原标题：golang 系统设计容器 OOM 故障完整排查
简介：Git 标签版本标记发布管理，使用 Git 标签标记项目版本，打标签推送远程，用于版本发布、版本回溯。
 | 原文链接：http://book.ybhiwr.asia/blog/1201405.sHtMl

原标题：git cherry‑pick 规范操作防 bug
简介：环境变量不生效问题修复，排查环境变量加载顺序、作用域问题，修复环境变量读取不到的异常。
 | 原文链接：http://book.ybhiwr.asia/blog/2897393.sHtMl

原标题：设计思考：API网关和BFF职责边界划分
简介：golang 集成测试测试数据库回滚，集成测试结束自动回滚数据库，不污染测试环境数据。
 | 原文链接：http://book.ybhiwr.asia/blog/4734308.sHtMl

原标题：架构笔记：数据脱敏架构接入层与存储层方案
简介：golang ctx 传递规则不要存结构体，context 作为函数参数传递，禁止放入结构体字段存储。
 | 原文链接：http://book.ybhiwr.asia/blog/4019796.sHtMl

原标题：OpenAPI 自动接口文档生成
简介：golang go 种子初始化 rand 随机，rand 初始化种子，不初始化会固定序列，理解随机数种子行为。
 | 原文链接：http://book.ybhiwr.asia/blog/2590817.sHtMl

原标题：golang 静态文件服务搭建教程
简介：golang go 爬虫请求速率控制，爬虫限频、代理轮换，设置 UA，防止爬虫被目标站点封禁 IP。
 | 原文链接：http://book.ybhiwr.asia/blog/9254590.sHtMl

原标题：零基础理解幂等性基础概念与场景
简介：接口压测定位系统性能瓶颈，使用压测工具对接口施压，观察指标，定位系统性能瓶颈点。
 | 原文链接：http://book.ybhiwr.asia/blog/9213296.sHtMl

原标题：浏览器缓存强制刷新方案
简介：golang grpc protobuf 开发实操，Go gRPC 开发，编写 Protobuf 定义，服务端客户端完整示例。
 | 原文链接：http://book.ybhiwr.asia/blog/6674372.sHtMl

原标题：部署实践：服务器防火墙安全组配置实践
简介：golang systemd 信号与优雅退出配合，systemd 停止服务发送 SIGTERM，go 程序捕获信号优雅关闭。
 | 原文链接：http://book.ybhiwr.asia/blog/4371531.sHtMl

原标题：golang 系统设计单元测试 mock 外部依赖技巧
简介：golang 消息队列实现事务消息方案，基于 kafka 实现事务消息，业务执行成功才对外投递消息。
 | 原文链接：http://book.ybhiwr.asia/blog/0316507.sHtMl

?
