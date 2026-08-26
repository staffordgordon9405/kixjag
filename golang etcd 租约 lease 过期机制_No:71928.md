最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang etcd 租约 lease 过期机制
简介：golang 配置热更新不重启服务，实现配置热加载，监听配置变更，更新内存配置，无需重启服务实例。
 | 原文链接：http://wiki.e6ia2g.asia/arts/384052.Doc

原标题：golang 链路 traceId 透传中间件
简介：golang ioutil 已废弃替换方案，ioutil 废弃之后替换为 os io 包函数，更新旧项目代码。
 | 原文链接：http://wiki.e6ia2g.asia/arts/074885.Doc

原标题：部署复盘：数据库主从备份恢复演练实践
简介：golang benchmark 减少测试干扰，benchmark 执行循环 b.N，避免循环内部做非被测逻辑干扰结果。
 | 原文链接：http://wiki.e6ia2g.asia/arts/563212.Doc

原标题：Security：反序列化漏洞风险识别与规避
简介：golang gorm 子查询嵌套查询写法，Gorm 实现子查询、嵌套查询，复杂条件查询简化代码编写。
 | 原文链接：http://wiki.e6ia2g.asia/arts/230063.Doc

原标题：实战项目：多实例部署会话一致性验证实践
简介：跨库查询性能优化处理，减少跨库关联查询，做数据冗余或者中间表，规避跨库查询性能低下。
 | 原文链接：http://wiki.e6ia2g.asia/arts/575773.Doc

原标题：CDN 缓存刷新获取最新静态资源
简介：golang 分布式锁防死锁实现要点，锁超时、续期、锁持有者校验，避免锁死锁，保障分布式锁可靠性。
 | 原文链接：http://wiki.e6ia2g.asia/arts/344982.Doc

原标题：golang 系统设计 grpc http2 多路复用讲解
简介：golang go 值传递引用传递理解，go 全部为值传递，指针本质拷贝指针值，理清参数传递行为。
 | 原文链接：http://wiki.e6ia2g.asia/arts/724698.Doc

原标题：golang kafka 死信队列业务落地
简介：golang 分布式事务 seata go 客户端，seata‑go 实现分布式事务，保证跨库业务数据最终一致性。
 | 原文链接：http://wiki.e6ia2g.asia/arts/373862.Doc

原标题：部署实践：Nginx反向代理传递真实客户端IP
简介：内存溢出问题现象识别排查，识别内存溢出现象，梳理排查方向，定位内存持续上涨引发服务崩溃问题。
 | 原文链接：http://wiki.e6ia2g.asia/arts/048368.Doc

原标题：效率笔记：Git高级命令日常开发高频使用汇总
简介：防火墙 IP 白名单回调接口放行，配置防火墙白名单，放行第三方回调服务器 IP，接收回调请求正常。
 | 原文链接：http://wiki.e6ia2g.asia/arts/237289.Doc

原标题：golang 系统设计字段命名类型选择最佳实践
简介：CI 流水线构建失败日志排查，阅读 CI 流水线输出日志，定位构建脚本、依赖、环境导致流水线失败问题。
 | 原文链接：http://wiki.e6ia2g.asia/arts/827997.Doc

原标题：Troubleshooting：数据库索引失效，查询性能暴跌
简介：golang gorm 批量插入性能调优，GORM 批量插入优化，调整批次大小，提升大量数据插入数据库速度。
 | 原文链接：http://wiki.e6ia2g.asia/arts/715828.Doc

原标题：golang 系统设计 pre‑commit 钩子本地代码校验
简介：缓存过期策略优化防业务故障，合理设置缓存过期策略，规避集中过期，减少缓存失效带来业务抖动。
 | 原文链接：http://wiki.e6ia2g.asia/arts/614553.Doc

原标题：架构笔记：多数据源架构设计事务处理难点
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：http://wiki.e6ia2g.asia/arts/124691.Doc

原标题：golang 系统设计本地缓存更新失效方案实现
简介：golang 雪花算法 workId 自动获取，自动获取机器 workId，不用手动配置，简化分布式 id 部署。
 | 原文链接：http://wiki.e6ia2g.asia/arts/944675.Doc

原标题：游标分页大数据查询性能提升
简介：RPC 接口字段增减兼容处理，RPC 接口新增删除字段做好向前兼容，老版本服务不会解析报错崩溃。
 | 原文链接：http://wiki.e6ia2g.asia/arts/130613.Doc

原标题：golang 静态文件服务搭建教程
简介：golang go regexp 正则预编译，regexp.MustCompile 预编译正则，不要循环内部编译正则，节省 CPU。
 | 原文链接：http://wiki.e6ia2g.asia/arts/969625.Doc

原标题：Troubleshooting：代理环境下证书校验失败HTTPS报错
简介：golang context.WithTimeout 超时上下文，WithTimeout 设置超时时间，超时自动 cancel 释放协程。
 | 原文链接：http://wiki.e6ia2g.asia/arts/374439.Doc

原标题：服务器时钟同步任务错乱修复
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://wiki.e6ia2g.asia/arts/481635.Doc

原标题：Nginx 静态代理负载均衡全套配置
简介：容器内存扩容 OOM 被杀死修复，调高容器内存限制，优化程序内存占用，避免程序被 OOM 终止。
 | 原文链接：http://wiki.e6ia2g.asia/arts/955856.Doc

原标题：OpenSource：开源项目风险评估依赖安全检查
简介：golang 单例模式实现几种方式，Go 单例模式多种实现对比，sync.Once 等方式，实现全局唯一实例。
 | 原文链接：http://wiki.e6ia2g.asia/arts/152845.Doc

原标题：安全实践：生产环境禁止开启debug调试模式
简介：golang io.Reader io.Writer 接口理解，io 读写接口，各类数据源统一抽象，适配 io 复制函数。
 | 原文链接：http://wiki.e6ia2g.asia/arts/720778.Doc

原标题：排坑：Git提交历史混乱，如何清理错误提交
简介：异步编程 Promise 执行流程解析，拆解异步执行顺序，理解回调与 Promise 差异，理清异步场景下代码执行逻辑。
 | 原文链接：http://wiki.e6ia2g.asia/arts/026632.Doc

原标题：golang 系统设计指标聚合计算存储选型对比
简介：前端图片懒加载性能优化，实现图片懒加载，页面可视区域才加载图片，减少页面初始网络请求。
 | 原文链接：http://wiki.e6ia2g.asia/arts/967919.Doc

原标题：程序日志分级输出规范实践
简介：golang 雪花 id 重复问题排查，排查雪花算法 ID 重复问题，时钟回拨、机器 ID 冲突，给出修复方案。
 | 原文链接：http://wiki.e6ia2g.asia/arts/712740.Doc

原标题：开源实践：参与开源项目从Issue到PR完整流程
简介：程序预加载加快服务启动速度，把高频使用资源提前预加载，减少请求阶段初始化，加快服务启动。
 | 原文链接：http://wiki.e6ia2g.asia/arts/278991.Doc

原标题：CI 流水线构建失败日志排查
简介：前端大文件分片上传完整方案，前端分片切割大文件，配合后端分片接口，实现稳定大文件上传。
 | 原文链接：http://wiki.e6ia2g.asia/arts/315697.Doc

原标题：Security：反序列化漏洞风险识别与规避
简介：定时任务重复执行分布式锁，使用分布式锁控制定时任务，保证集群环境定时任务只会执行一次。
 | 原文链接：http://wiki.e6ia2g.asia/arts/612856.Doc

原标题：调优方案：容器CPU内存参数压测后调优
简介：golang 雪花算法 workId 自动获取，自动获取机器 workId，不用手动配置，简化分布式 id 部署。
 | 原文链接：http://wiki.e6ia2g.asia/arts/631235.Doc

原标题：批量异步处理系统业务落地
简介：golang 漏桶算法实现接口限流，漏桶算法控制请求流出速率，平滑突发流量，削平流量峰值。
 | 原文链接：http://wiki.e6ia2g.asia/arts/853561.Doc

原标题：Debug：表单提交特殊字符造成接口解析失败
简介：golang jwt jwk 公钥验证令牌，使用 jwk 公钥校验 jwt，非对称方式签发校验令牌，提升安全性。
 | 原文链接：http://wiki.e6ia2g.asia/arts/329805.Doc

原标题：nodejs 中间件模式原理剖析
简介：nodejs 中间件模式原理剖析，拆解 Node 中间件设计模式，理解请求逐层处理流转的底层原理。
 | 原文链接：http://wiki.e6ia2g.asia/arts/828490.Doc

原标题：golang 表单文件大小限制配置
简介：golang tcp 四次挥手 go 程序行为，理解 tcp 四次挥手，处理连接关闭、重置、RST 包异常场景。
 | 原文链接：http://wiki.e6ia2g.asia/arts/681334.Doc

原标题：灰度发布策略服务平滑升级
简介：golang go 接口定义原则小接口，go 小接口设计原则，接口尽量小，只定义必要方法，提升代码灵活性。
 | 原文链接：http://wiki.e6ia2g.asia/arts/303238.Doc

原标题：Troubleshoot：跨域偶现失败难以复现问题
简介：golang grpc 拦截器开发鉴权日志，开发 grpc 服务端拦截器，统一做鉴权、日志打印、异常捕获处理。
 | 原文链接：http://wiki.e6ia2g.asia/arts/725429.Doc

原标题：Hands‑on：简易速率限制中间件完整实现
简介：GET POST 接口请求参数处理，讲解两种请求方式参数传递区别，演示参数接收、解析、校验，适配不同接口调用场景。
 | 原文链接：http://wiki.e6ia2g.asia/arts/541887.Doc

原标题：Architecture：事件溯源架构模式适用业务场景
简介：golang go‑zero 缓存自动击穿防护，go‑zero 缓存组件自带缓存击穿防护，减少缓存层故障。
 | 原文链接：http://wiki.e6ia2g.asia/arts/676876.Doc

原标题：架构复盘：系统扩容缩容架构无状态优先原则
简介：定时任务重复执行分布式锁，使用分布式锁控制定时任务，保证集群环境定时任务只会执行一次。
 | 原文链接：http://wiki.e6ia2g.asia/arts/167254.Doc

原标题：golang 布隆过滤器实现去重
简介：提交第一个开源 PR 完整流程，Fork 项目、修改代码、提交 Pull Request，讲解 PR 规范，提升合并通过率。
 | 原文链接：http://wiki.e6ia2g.asia/arts/162051.Doc

原标题：运维笔记：服务器磁盘内存监控告警配置
简介：golang testify testify 断言库使用，testify assert require 断言，简化单元测试断言代码。
 | 原文链接：http://wiki.e6ia2g.asia/arts/561041.Doc


二、踩坑排错｜Troubleshooting
原标题：golang 优雅停机服务关闭实现
简介：golang go‑pg postgres 客户端实操，go‑pg 操作 PostgreSQL 数据库，CRUD 关联查询业务开发。
 | 原文链接：http://wiki.e6ia2g.asia/arts/593214.Doc

原标题：数据库连接池参数调优
简介：golang go mod graph 查看依赖关系，go mod graph 打印依赖树，定位间接依赖来源，解决版本冲突。
 | 原文链接：http://wiki.e6ia2g.asia/arts/870910.Doc

原标题：golang redis pipeline 原子性说明
简介：开源源码阅读拆解学习思路，分享阅读大型开源项目方法，从入口文件逐层拆解模块，降低源码学习门槛。
 | 原文链接：http://wiki.e6ia2g.asia/arts/711393.Doc

原标题：大事务拆分防止连接池耗尽
简介：golang init 函数合理使用边界，少用 init，优先显式调用初始化，便于控制初始化时机。
 | 原文链接：http://wiki.e6ia2g.asia/arts/127699.Doc

原标题：方案设计：高可用Redis集群架构选型对比
简介：golang gorm group by 分组统计，GORM 分组聚合统计，实现 count sum 等统计查询，快速完成统计业务。
 | 原文链接：http://wiki.e6ia2g.asia/arts/048627.Doc

原标题：实践：API接口文档自动导出离线文档实践
简介：golang 信号量控制并发数量，使用信号量控制并发，限制同时执行任务数量，保护下游资源。
 | 原文链接：http://wiki.e6ia2g.asia/arts/548364.Doc

原标题：从零搭建简单的身份登录模拟示例
简介：golang go 爬虫请求速率控制，爬虫限频、代理轮换，设置 UA，防止爬虫被目标站点封禁 IP。
 | 原文链接：http://wiki.e6ia2g.asia/arts/537887.Doc

原标题：Hands‑on：简易配置中心本地原型实现
简介：golang jwt 鉴权中间件完整示例，Gin JWT 鉴权中间件，令牌校验，解析用户信息，接口鉴权拦截。
 | 原文链接：http://wiki.e6ia2g.asia/arts/190521.Doc

原标题：golang 系统设计滑动窗口限流代码示例
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://wiki.e6ia2g.asia/arts/365534.Doc

原标题：方案对比：单体、微服务、模块化单体取舍
简介：golang 日志按日期切割实现方案，实现日志文件按天切割，自动归档旧日志，防止单个日志文件过大。
 | 原文链接：http://wiki.e6ia2g.asia/arts/098096.Doc

原标题：Hands‑on：代码生成器，一键生成CRUD模板
简介：日志切割配置防止日志丢失，配置日志切割轮转策略，日志按大小时间切割，防止日志文件丢失。
 | 原文链接：http://wiki.e6ia2g.asia/arts/142668.Doc

原标题：热更新开发环境配置教程
简介：golang go‑zero 配置中心热更新，go‑zero 对接 etcd 配置中心，配置热更新无需重启服务。
 | 原文链接：http://wiki.e6ia2g.asia/arts/083983.Doc

原标题：JSON XML 数据解析处理示例
简介：对象存储上传下载权限实操，演示对象存储文件上传、下载、访问权限设置，适配业务文件存储场景。
 | 原文链接：http://wiki.e6ia2g.asia/arts/126339.Doc

原标题：golang 系统设计日志脱敏防止信息泄露
简介：golang go regexp 正则预编译，regexp.MustCompile 预编译正则，不要循环内部编译正则，节省 CPU。
 | 原文链接：http://wiki.e6ia2g.asia/arts/640309.Doc

原标题：大事务拆分防止连接池耗尽
简介：MySQL 慢查询索引优化实战，抓取慢查询 SQL，分析执行计划，新增或者调整索引，提升 SQL 执行速度。
 | 原文链接：http://wiki.e6ia2g.asia/arts/003244.Doc

原标题：golang 项目环境变量加载方案
简介：golang 分布式唯一 id 多种方案对比，雪花、redis、uuid 对比各方案优缺点，指导业务选型使用。
 | 原文链接：http://wiki.e6ia2g.asia/arts/195352.Doc

原标题：实战项目：容器资源限制配置压力测试实践
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://wiki.e6ia2g.asia/arts/459086.Doc

原标题：跨域偶现失败配置修复
简介：布隆过滤器数据高效去重实现，实现布隆过滤器组件，用于海量数据去重，节省大量内存空间。
 | 原文链接：http://wiki.e6ia2g.asia/arts/831541.Doc

原标题：HelloShell：入门常用shell脚本编写
简介：Docker 网络模式容器互通设置，选择合适 Docker 网络模式，实现容器之间网络互相访问通信。
 | 原文链接：http://wiki.e6ia2g.asia/arts/831871.Doc

原标题：复盘总结：缓存改造业务落地踩坑复盘
简介：golang validator 自定义校验规则，Gin Validator 自定义校验器，实现业务特殊参数校验逻辑。
 | 原文链接：http://wiki.e6ia2g.asia/arts/018729.Doc

原标题：架构笔记：分布式系统常见一致性模型梳理
简介：golang 空接口 interface {} 类型处理，interface {} 存储任意类型，类型转换，处理泛型之前通用数据。
 | 原文链接：http://wiki.e6ia2g.asia/arts/711907.Doc

原标题：macOS 脚本执行权限开启
简介：业务错误码完整落地实践，落地完整业务错误码，枚举全部业务异常，统一返回，配套文档说明。
 | 原文链接：http://wiki.e6ia2g.asia/arts/894064.Doc

原标题：实战项目：实现分布式任务调度最小原型
简介：golang grpc 双向流双向通信开发，grpc 双向流，服务端客户端持续互发消息，长连接流式业务场景。
 | 原文链接：http://wiki.e6ia2g.asia/arts/640326.Doc

原标题：Security：开源项目安全审计简易检查清单
简介：golang go 程序守护进程实现思路，go 程序不做 daemon 化，依靠 systemd pm2 k8s 实现进程守护。
 | 原文链接：http://wiki.e6ia2g.asia/arts/902662.Doc

原标题：golang 系统设计第三方接口 mock 单元测试
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：http://wiki.e6ia2g.asia/arts/959211.Doc

原标题：OpenSource：开源项目贡献者协作流程规范
简介：golang 信号量 semaphore 并发限制，基于 semaphore 实现并发数量控制，保护数据库、第三方接口不被打满。
 | 原文链接：http://wiki.e6ia2g.asia/arts/205177.Doc

原标题：优化实践：序列化框架性能对比选型实践
简介：golang 字符编码转换 go 处理，iconv‑go 做编码转换 gbk utf8 互转，处理老旧系统 gbk 编码数据。
 | 原文链接：http://wiki.e6ia2g.asia/arts/357816.Doc

原标题：golang k8s helm chart 简单编写
简介：golang 配置文件多环境加载，Go 多环境配置加载实现，读取配置文件环境变量，适配多套运行环境。
 | 原文链接：http://wiki.e6ia2g.asia/arts/120295.Doc

原标题：OpenSource：开源项目README高质量编写指南
简介：移动端适配 rem vw 方案对比，对比 rem 与 vw 移动端适配方案，分析优缺点，给出选型建议。
 | 原文链接：http://wiki.e6ia2g.asia/arts/128746.Doc

原标题：golang 系统设计字符串拼接性能优化技巧
简介：golang go xml 解析生成 xml 文档，encoding/xml 解析 xml，结构体标签映射 xml 节点属性。
 | 原文链接：http://wiki.e6ia2g.asia/arts/565481.Doc

原标题：Hands‑on：手写简易ORM框架理解底层原理
简介：WSL 文件权限访问异常修复，处理 WSL 环境文件权限错乱，调整权限配置，实现文件正常读写访问。
 | 原文链接：http://wiki.e6ia2g.asia/arts/790667.Doc

原标题：大事务拆分回滚日志暴涨解决
简介：golang mime 类型检测文件，mime 识别文件 mime 类型，设置 http 响应 Content‑Type。
 | 原文链接：http://wiki.e6ia2g.asia/arts/377141.Doc

原标题：nestjs 全局返回格式统一处理
简介：golang gorm 软删除实现逻辑，Gorm 开启软删除，删除数据仅标记，数据保留可恢复，满足业务数据留存。
 | 原文链接：http://wiki.e6ia2g.asia/arts/190433.Doc

原标题：数值 key 浮点匹配异常规避
简介：golang go 自定义错误类型实现，自定义 error 结构体，携带错误码、堆栈信息，统一业务错误。
 | 原文链接：http://wiki.e6ia2g.asia/arts/305928.Doc

原标题：golang mysql 时间类型选型避坑
简介：golang 结构体零值可用性原则，go 结构体尽量做到零值可用，不用初始化直接使用提升易用性。
 | 原文链接：http://wiki.e6ia2g.asia/arts/423302.Doc

原标题：入门实践：Git分支创建切换合并完整演示
简介：golang bufio 缓冲读写性能优化，bufio 带缓冲读写，减少系统调用，提升文件网络 IO 性能。
 | 原文链接：http://wiki.e6ia2g.asia/arts/808248.Doc

原标题：golang 日志与链路 ID 关联打印
简介：文件句柄上限调整上传随机失败，调高系统文件句柄上限，解决高并发上传场景随机打开文件失败。
 | 原文链接：http://wiki.e6ia2g.asia/arts/159807.Doc

原标题：golang 系统设计消息重试次数间隔策略设置
简介：内存溢出问题现象识别排查，识别内存溢出现象，梳理排查方向，定位内存持续上涨引发服务崩溃问题。
 | 原文链接：http://wiki.e6ia2g.asia/arts/704118.Doc

原标题：消息队列生产消费模型入门
简介：全量回归测试提升代码质量，搭建全量回归测试集，版本发布执行回归测试，避免迭代引入旧 bug。
 | 原文链接：http://wiki.e6ia2g.asia/arts/493155.Doc

原标题：golang mysql 避免 select * 查询
简介：golang os 文件目录操作大全，文件创建删除重命名，目录遍历，文件信息读取，完成各类文件系统操作。
 | 原文链接：http://wiki.e6ia2g.asia/arts/717035.Doc

三、实战开发｜Practice
原标题：golang 参数校验业务接口处理
简介：golang go 程序版本号内置编译注入，编译时注入 git commit 版本号，程序运行输出版本便于排查。
 | 原文链接：http://wiki.e6ia2g.asia/arts/594320.Doc

原标题：部署复盘：GitHubActions完整自动化配置
简介：静态站点自动部署发布方案，配置流水线，代码更新自动构建静态站点并且部署上线，简化发布。
 | 原文链接：http://wiki.e6ia2g.asia/arts/944283.Doc

原标题：性能笔记：压测如何定位真实系统瓶颈
简介：golang io.Reader io.Writer 接口理解，io 读写接口，各类数据源统一抽象，适配 io 复制函数。
 | 原文链接：http://wiki.e6ia2g.asia/arts/139494.Doc

原标题：golang grpc protobuf 开发实操
简介：golang 制品镜像版本号规范管理，镜像版本号结合 git commit，明确每个镜像对应代码版本便于追溯。
 | 原文链接：http://wiki.e6ia2g.asia/arts/655739.Doc

原标题：golang k8s 命名空间资源隔离方案
简介：golang defer 执行顺序与坑点，defer 后进先出，循环内部 defer 陷阱，资源释放正确写法。
 | 原文链接：http://wiki.e6ia2g.asia/arts/208079.Doc

原标题：调优方案：服务实例扩容，水平扩展性能
简介：golang rabbitmq go 客户端生产消费，streadway/amqp 实现 rabbitmq 生产者消费者，队列交换机绑定。
 | 原文链接：http://wiki.e6ia2g.asia/arts/945454.Doc

原标题：golang 空接口 interface 使用技巧
简介：nestjs 拦截器过滤器管道实战，实操 Nest 拦截器、异常过滤器、管道校验，处理请求与响应统一逻辑。
 | 原文链接：http://wiki.e6ia2g.asia/arts/202414.Doc

原标题：golang excel 简单读写操作示例
简介：golang netlink 系统信息获取，netlink 获取系统网络信息，网卡地址，内核网络状态读取。
 | 原文链接：http://wiki.e6ia2g.asia/arts/129404.Doc

原标题：golang mysql 行锁表锁场景区分
简介：灰度发布策略服务平滑升级，实现灰度发布逻辑，流量逐步切到新版本，出现问题快速回滚旧版本。
 | 原文链接：http://wiki.e6ia2g.asia/arts/789638.Doc

原标题：新手向：开源项目依赖安装失败排查
简介：golang 配置文件热加载监听变更，监听配置文件改动，自动重新加载配置，业务即时生效无需重启。
 | 原文链接：http://wiki.e6ia2g.asia/arts/785227.Doc

原标题：坑点：gitcherry‑pick引入不兼容代码
简介：前后端会话登录状态持久化，实现登录状态持久存储，重启服务登录状态不丢失，保障会话稳定性。
 | 原文链接：http://wiki.e6ia2g.asia/arts/306932.Doc

原标题：golang es 分页深分页性能优化
简介：磁盘 inode 耗尽文件创建失败，排查磁盘 inode 占用，清理大量小文件，恢复文件创建能力。
 | 原文链接：http://wiki.e6ia2g.asia/arts/788044.Doc

原标题：看懂报错日志快速定位问题
简介：golang go work 多模块本地开发，go work 多模块本地同时开发，本地模块互相引用，无需推送仓库。
 | 原文链接：http://wiki.e6ia2g.asia/arts/856417.Doc

原标题：golang redis lua 脚本原子操作
简介：golang 数据库分表策略按时间分片，按时间维度分表，历史数据拆分，单表数据量控制保证查询性能。
 | 原文链接：http://wiki.e6ia2g.asia/arts/996517.Doc

原标题：Hands‑on：简易短消息模板渲染组件实践
简介：golang gorm ORM 数据库操作，GORM 实操数据库 CRUD，模型定义，关联查询，简化 Go 数据库开发。
 | 原文链接：http://wiki.e6ia2g.asia/arts/780527.Doc

原标题：golang 系统设计蓝绿发布滚动发布对比
简介：golang 性能压测 wr 工具实操指南，wr 压测工具对 Go 接口压测，观察 QPS 延迟，定位接口性能瓶颈。
 | 原文链接：http://wiki.e6ia2g.asia/arts/533221.Doc

原标题：HelloDocker：编写你的第一个Dockerfile
简介：express 中间件开发业务实践，开发 Express 自定义中间件，拦截请求，实现鉴权、日志记录等通用逻辑。
 | 原文链接：http://wiki.e6ia2g.asia/arts/293690.Doc

原标题：数据库读写分离性能优化
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://wiki.e6ia2g.asia/arts/585835.Doc

原标题：部署复盘：静态站点部署CDN完整流程
简介：golang etcd key 监听变更 watch 机制，watch 监听 etcd 键变化，配置变更实时感知，实现配置热更新。
 | 原文链接：http://wiki.e6ia2g.asia/arts/101449.Doc

原标题：golang 系统设计消息体序列化选型对比
简介：golang go 领域驱动 DDD 项目分层，go 项目 DDD 分层架构，领域层应用层基础设施层划分业务代码。
 | 原文链接：http://wiki.e6ia2g.asia/arts/648913.Doc

原标题：golang 系统设计告警渠道钉钉邮件企业微信集成
简介：WSL 文件权限访问异常修复，处理 WSL 环境文件权限错乱，调整权限配置，实现文件正常读写访问。
 | 原文链接：http://wiki.e6ia2g.asia/arts/982091.Doc

原标题：golang 系统设计 http 接口基准测试实操示例
简介：golang go 种子初始化 rand 随机，rand 初始化种子，不初始化会固定序列，理解随机数种子行为。
 | 原文链接：http://wiki.e6ia2g.asia/arts/012711.Doc

原标题：服务器 Swap 关闭提升响应速度
简介：golang go 依赖漏洞检测 govulncheck，govulncheck 扫描依赖安全漏洞，发现项目供应链风险。
 | 原文链接：http://wiki.e6ia2g.asia/arts/963322.Doc

原标题：WSL 搭建 Windows Linux 开发环境
简介：golang 命令行参数解析开发，解析命令行入参，开发自定义 CLI 程序，读取启动参数配置服务。
 | 原文链接：http://wiki.e6ia2g.asia/arts/688140.Doc

原标题：Debug：表单提交特殊字符造成接口解析失败
简介：golang 字符串处理常用技巧汇总，字符串拼接、分割、替换、类型转换实操，规避字符串高频错误。
 | 原文链接：http://wiki.e6ia2g.asia/arts/574071.Doc

原标题：优化实践：序列化框架性能对比选型实践
简介：golang go 服务压测前后性能对比，压测记录 QPS 延迟，优化前后对比，验证优化效果。
 | 原文链接：http://wiki.e6ia2g.asia/arts/791777.Doc

原标题：踩坑记录：文件描述符不足，上传功能随机失败
简介：CDN 缓存刷新获取最新静态资源，调用 CDN 刷新接口，清除节点旧缓存，用户访问到更新后的静态文件。
 | 原文链接：http://wiki.e6ia2g.asia/arts/269558.Doc

原标题：复盘总结：缓存改造业务落地踩坑复盘
简介：golang go 服务压测前后性能对比，压测记录 QPS 延迟，优化前后对比，验证优化效果。
 | 原文链接：http://wiki.e6ia2g.asia/arts/591601.Doc

原标题：Git 误提交撤销回退实操教程
简介：golang testing.TB Helper 标记辅助函数，t.Helper 标记辅助函数，报错打印真实调用位置。
 | 原文链接：http://wiki.e6ia2g.asia/arts/508449.Doc

原标题：避坑：Spring事务传播行为理解错误事务失效
简介：模拟登录鉴权权限判断示例，实现简易登录流程，会话状态维护，完成接口权限校验，理解身份鉴权基础逻辑。
 | 原文链接：http://wiki.e6ia2g.asia/arts/731758.Doc

原标题：golang minio 存储桶权限管控配置
简介：golang 故障演练服务模拟超时报错，程序模拟接口超时、报错，做混沌测试验证熔断降级有效性。
 | 原文链接：http://wiki.e6ia2g.asia/arts/776383.Doc

原标题：实战：Nginx负载均衡多种策略配置实践
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://wiki.e6ia2g.asia/arts/237335.Doc

原标题：实战项目：本地模拟磁盘IO高负载观察服务行为
简介：nestjs 权限守卫鉴权实现方案，使用 Nest 守卫实现接口鉴权，角色权限控制，拦截未授权接口访问。
 | 原文链接：http://wiki.e6ia2g.asia/arts/965496.Doc

原标题：Practice：批量异步任务处理系统设计实现
简介：golang 正则表达式 Go 实操案例，正则匹配提取替换，处理手机号邮箱校验，规避正则回溯 CPU 暴涨。
 | 原文链接：http://wiki.e6ia2g.asia/arts/326865.Doc

原标题：端口占用访问失败排查方案
简介：数值 key 浮点匹配异常规避，避免浮点数作为 Redis 等存储的 key，防止精度问题引发 key 匹配失败。
 | 原文链接：http://wiki.e6ia2g.asia/arts/092479.Doc

原标题：实践：分布式事务本地模拟验证实践
简介：golang pdf 生成 go 服务端生成 pdf，服务端动态生成 pdf 报表文件，直接输出下载给到前端。
 | 原文链接：http://wiki.e6ia2g.asia/arts/863062.Doc

原标题：性能复盘：接口响应从800ms优化到50ms全过程
简介：CI 流水线构建失败日志排查，阅读 CI 流水线输出日志，定位构建脚本、依赖、环境导致流水线失败问题。
 | 原文链接：http://wiki.e6ia2g.asia/arts/586228.Doc

原标题：golang 系统设计分布式事务几种方案优缺点
简介：golang k8s informer 机制原理理解，informer 监听 k8s 资源变更，本地缓存，减少 apiserver 压力。
 | 原文链接：http://wiki.e6ia2g.asia/arts/780099.Doc

原标题：设计思考：业务系统如何做故障隔离架构
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://wiki.e6ia2g.asia/arts/988122.Doc

原标题：golang 系统设计监控告警体系搭建思路
简介：golang go 项目 CI github actions 配置，github actions 实现 go 项目 ci，自动测试、代码检查、编译打包镜像。
 | 原文链接：http://wiki.e6ia2g.asia/arts/781403.Doc

四、架构设计｜Architecture
原标题：Practice：模拟磁盘满，验证服务降级表现
简介：golang redis pipeline 与 txpipeline 区别，区分普通管道与事务管道，根据业务场景选择合适批量执行方案。
 | 原文链接：http://wiki.e6ia2g.asia/arts/749818.Doc

原标题：入门实践：使用模板快速生成项目脚手架
简介：前端打包分包加载提速方案，前端打包做代码分包，拆分大 bundle，页面按需加载，提升首屏加载速度。
 | 原文链接：http://wiki.e6ia2g.asia/arts/607697.Doc

原标题：入门实战：搭建简易静态网页项目
简介：数据库分表路由写入分片修正，修复分表路由逻辑，保证数据写入正确分片，不会出现数据丢失错乱。
 | 原文链接：http://wiki.e6ia2g.asia/arts/229818.Doc

原标题：Troubleshooting：数据库索引失效，查询性能暴跌
简介：golang http 中间件洋葱模型原理，理解 go http 中间件洋葱模型，请求响应流转顺序，编写自定义中间件。
 | 原文链接：http://wiki.e6ia2g.asia/arts/345412.Doc

原标题：前端工程化 webpack 打包优化
简介：golang go url url.Values 参数编码，url.Values 构建 url 查询参数，自动处理参数 url 编码。
 | 原文链接：http://wiki.e6ia2g.asia/arts/950806.Doc

原标题：快速入门Nginx基础配置，反向代理示例
简介：HTTPS 证书过期更新操作，检测 HTTPS 证书到期，更新证书文件，恢复 HTTPS 服务正常访问。
 | 原文链接：http://wiki.e6ia2g.asia/arts/601993.Doc

原标题：全局时间标准统一逻辑错乱修复
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：http://wiki.e6ia2g.asia/arts/164900.Doc

原标题：golang 项目 go mod 依赖管理
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://wiki.e6ia2g.asia/arts/949889.Doc

原标题：golang 系统设计网络超时故障排查思路
简介：golang rsa 公钥加密私钥解密，rsa 非对称加密，大文件分块加密，处理非对称加密长度限制。
 | 原文链接：http://wiki.e6ia2g.asia/arts/163330.Doc

原标题：golang mysql limit 大分页优化
简介：内网测试服务搭建团队调试，配置本地服务内网可访问，团队成员能够访问调试，方便前后端联调与内部演示。
 | 原文链接：http://wiki.e6ia2g.asia/arts/789264.Doc

原标题：实战项目：GitSubmodule管理多仓库实践
简介：golang grpc 错误状态码标准化，grpc 标准化错误返回，定义业务错误码，客户端解析处理业务异常。
 | 原文链接：http://wiki.e6ia2g.asia/arts/557877.Doc

原标题：golang 系统设计大盘看板设计最佳实践汇总
简介：golang sync.Once 只执行一次，sync.Once 做单例初始化，保证代码只执行一次，并发安全。
 | 原文链接：http://wiki.e6ia2g.asia/arts/418465.Doc

原标题：golang 接口请求日志记录中间件
简介：golang go 程序 CPU 占用高定位步骤，pprof 定位热点函数，分析 CPU 高占用，优化耗时代码逻辑。
 | 原文链接：http://wiki.e6ia2g.asia/arts/864171.Doc

原标题：Architecture：服务注册发现架构原理与选型
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：http://wiki.e6ia2g.asia/arts/159914.Doc

原标题：golang 系统设计压测指标确定与分析
简介：Nginx 静态代理负载均衡全套配置，一套 Nginx 配置示例，覆盖静态资源、反向代理、负载均衡场景。
 | 原文链接：http://wiki.e6ia2g.asia/arts/921365.Doc

原标题：CLI 工具进度条交互效果开发
简介：后端大文件分片上传接口开发，开发后端分片上传接口，接收分片，合并分片完成大文件存储。
 | 原文链接：http://wiki.e6ia2g.asia/arts/965581.Doc

原标题：golang jwt 鉴权中间件完整示例
简介：git stash 代码暂存切换分支，使用 stash 暂存未提交代码，切换其他分支处理紧急任务，再恢复原有工作进度。
 | 原文链接：http://wiki.e6ia2g.asia/arts/842240.Doc

原标题：项目目录结构规范化最佳实践
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://wiki.e6ia2g.asia/arts/144839.Doc

?
