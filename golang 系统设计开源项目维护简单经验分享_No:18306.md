最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计开源项目维护简单经验分享
简介：golang 内存持续上涨定位思路，区分内存泄漏、缓存占用、GC 参数不合理，分步定位内存持续走高。
 | 原文链接：http://wiki.y8fmju.asia/arts/180167.Doc

原标题：golang 系统设计压测指标确定与分析
简介：golang 开发环境快速搭建指南，快速完成 Golang 开发环境配置，工具链安装，环境变量设置，准备开发。
 | 原文链接：http://wiki.y8fmju.asia/arts/211725.Doc

原标题：golang 系统设计分布式锁不同场景选型对比
简介：golang 系统 IO 阻塞 goroutine 场景，理解系统调用阻塞 M，P 会调度其他 M，掌握 go 调度行为。
 | 原文链接：http://wiki.y8fmju.asia/arts/845575.Doc

原标题：实践：代码提交前自动格式化校验配置实践
简介：golang redis 事务 multi exec 使用，Redis 事务 multi exec 实现批量命令原子执行，理解 redis 事务隔离特性。
 | 原文链接：http://wiki.y8fmju.asia/arts/001749.Doc

原标题：CI 流水线超时时间延长配置
简介：golang kafka 消费者位移管理，理解 kafka offset，手动提交位移，保证消息消费至少一次语义。
 | 原文链接：http://wiki.y8fmju.asia/arts/527235.Doc

原标题：接口签名校验防篡改实现
简介：序列化版本不一致解析失败，保证序列化对象版本对齐，修复版本不匹配导致对象反序列化失败。
 | 原文链接：http://wiki.y8fmju.asia/arts/517445.Doc

原标题：golang 系统设计 protobuf oneof 类型业务场景
简介：golang net/http/httptest 服务端模拟，httptest.NewRecorder 记录 handler 响应，校验返回状态码 body。
 | 原文链接：http://wiki.y8fmju.asia/arts/784517.Doc

原标题：Issue：Nginxkeepalive参数不合理大量TIME_WAIT
简介：golang sync.RWMutex 读写锁使用场景，读多写少场景读写锁，读共享写互斥，提升并发性能。
 | 原文链接：http://wiki.y8fmju.asia/arts/256947.Doc

原标题：ICMP 放通网络丢包问题修复
简介：前端大文件分片上传完整方案，前端分片切割大文件，配合后端分片接口，实现稳定大文件上传。
 | 原文链接：http://wiki.y8fmju.asia/arts/023142.Doc

原标题：Debug：分布式会话时钟不同步令牌提前失效
简介：图片上传预览格式大小处理，实现图片上传接口，校验文件格式、大小，完成上传后预览处理。
 | 原文链接：http://wiki.y8fmju.asia/arts/337980.Doc

原标题：golang jwt 过期刷新 token 实现
简介：golang gin 中间件执行顺序讲解，理解 Gin 中间件注册顺序，区分前置后置逻辑，规避中间件顺序 bug。
 | 原文链接：http://wiki.y8fmju.asia/arts/043149.Doc

原标题：golang 系统设计网络超时故障排查思路
简介：定时任务周期调度 demo 开发，实现简单定时调度程序，按时间周期执行业务逻辑，理解定时任务运行机制。
 | 原文链接：http://wiki.y8fmju.asia/arts/301916.Doc

原标题：架构笔记：分布式事务方案对比与业务取舍
简介：golang context.WithCancel 手动取消上下文，WithCancel 生成可取消 ctx，手动调用 cancel 触发取消。
 | 原文链接：http://wiki.y8fmju.asia/arts/097864.Doc

原标题：DevOps：Docker镜像安全扫描集成CI流程
简介：golang 分布式锁防死锁实现要点，锁超时、续期、锁持有者校验，避免锁死锁，保障分布式锁可靠性。
 | 原文链接：http://wiki.y8fmju.asia/arts/203024.Doc

原标题：golang 系统设计链路追踪核心概念 trace span 讲解
简介：golang CPU 绑定亲和性设置 go 程序，设置进程 CPU 亲和绑定核心，减少 CPU 调度开销，提升计算性能。
 | 原文链接：http://wiki.y8fmju.asia/arts/745185.Doc

原标题：golang 系统设计开源项目自动化 ci 配置示例
简介：golang interface {} 类型断言类型转换，类型断言 ok 模式，避免断言失败触发 panic。
 | 原文链接：http://wiki.y8fmju.asia/arts/291847.Doc

原标题：Practice：从零实现轻量后端接口服务完整实践
简介：文件监控服务自动重启开发，监控项目文件变更，代码修改自动重启服务，提升本地开发调试效率。
 | 原文链接：http://wiki.y8fmju.asia/arts/864723.Doc

原标题：golang 系统设计数据库慢查询治理方案
简介：golang sync/atomic 原子操作使用注意，理解原子操作内存顺序，规避原子操作错误使用带来 bug。
 | 原文链接：http://wiki.y8fmju.asia/arts/252931.Doc

原标题：记一次日志切割脚本错误直接清空业务日志
简介：golang go 项目安全检查漏洞扫描，扫描 go 项目依赖漏洞，代码安全审计，规避安全风险。
 | 原文链接：http://wiki.y8fmju.asia/arts/373333.Doc

原标题：golang 系统设计 grpc proto 接口设计原则
简介：golang redis 客户端业务使用，Go Redis 客户端对接，实现缓存、计数器，适配各类 Redis 业务场景。
 | 原文链接：http://wiki.y8fmju.asia/arts/754255.Doc

原标题：快速入门ORM，实现简单数据库增删改查
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：http://wiki.y8fmju.asia/arts/509134.Doc

原标题：nodejs 定时任务生产环境避坑
简介：限流窗口绕过漏洞修复方案，修复限流时间窗口漏洞，避免攻击者绕过限流规则，保障接口防护有效。
 | 原文链接：http://wiki.y8fmju.asia/arts/485025.Doc

原标题：golang redis 地理位置 geo 使用
简介：异步异常捕获避免进程崩溃，捕获异步代码内部抛出异常，防止未捕获异常直接导致整个进程退出。
 | 原文链接：http://wiki.y8fmju.asia/arts/897455.Doc

原标题：优化实践：分页查询性能优化解决offset问题
简介：SDK 版本兼容线上崩溃修复，处理 SDK 版本升级之后线上崩溃，定位 API 变更，做版本兼容适配改造。
 | 原文链接：http://wiki.y8fmju.asia/arts/419289.Doc

原标题：TLS 版本兼容 HTTPS 握手失败
简介：golang proto 可选字段处理方案，protobuf 可选字段正确判断，区分未赋值与零值，业务逻辑不出现偏差。
 | 原文链接：http://wiki.y8fmju.asia/arts/036928.Doc

原标题：入门实践：搭建简单的热更新开发环境
简介：golang go http 服务器优雅关闭完整代码，http.Server Shutdown，等待现有请求处理完成关闭服务。
 | 原文链接：http://wiki.y8fmju.asia/arts/556524.Doc

原标题：eslint prettier 代码规范落地
简介：golang sync/atomic 原子操作使用注意，理解原子操作内存顺序，规避原子操作错误使用带来 bug。
 | 原文链接：http://wiki.y8fmju.asia/arts/483809.Doc

原标题：Practice：从零实现轻量后端接口服务完整实践
简介：golang 协程数量监控统计方案，统计运行中 goroutine 数量，监控协程泄露，协程数量异常及时告警。
 | 原文链接：http://wiki.y8fmju.asia/arts/922854.Doc

原标题：golang 系统设计数据库基准压测简单思路
简介：nodejs http 服务性能调优实战，调优 Node HTTP 服务内核参数，连接复用，提升接口并发处理能力。
 | 原文链接：http://wiki.y8fmju.asia/arts/785793.Doc

原标题：golang 系统设计配置敏感信息加密存储方案
简介：重复提交幂等防护再次讲解，梳理前端重复点击、网络重试场景，落地接口幂等，杜绝重复业务。
 | 原文链接：http://wiki.y8fmju.asia/arts/259524.Doc

原标题：优化实践：接口批量合并减少网络请求次数
简介：golang 单元测试 mock http 请求，mock HTTP 外部接口，单元测试不依赖外部网络，保证用例稳定运行。
 | 原文链接：http://wiki.y8fmju.asia/arts/374994.Doc

原标题：WSL 搭建 Windows Linux 开发环境
简介：前端权限路由动态生成实现，根据后端返回权限，动态生成前端路由菜单，实现页面权限控制。
 | 原文链接：http://wiki.y8fmju.asia/arts/593877.Doc

原标题：安全复盘：Redis命令注入风险防护手段
简介：golang atomic 原子操作整数，atomic 加减比较交换，无锁更新整型变量，简单计数器场景。
 | 原文链接：http://wiki.y8fmju.asia/arts/419994.Doc

原标题：Issue：本地可以访问，容器内部网络不通
简介：golang 优雅处理 http 超时设置，Go HTTP 请求设置各类超时，防止请求无限阻塞，保护协程与连接。
 | 原文链接：http://wiki.y8fmju.asia/arts/663369.Doc

原标题：ORM 框架数据库增删改查实操
简介：分布式任务调度集群原型开发，开发简易分布式调度原型，集群多节点运行，保证任务只执行一次。
 | 原文链接：http://wiki.y8fmju.asia/arts/585084.Doc

原标题：Dockerfile 编写容器打包实战
简介：golang goroutine 协程基础实操，Goroutine 基础实操案例，启动协程执行任务，理解轻量级协程特性。
 | 原文链接：http://wiki.y8fmju.asia/arts/807801.Doc

原标题：Practice：实现定时任务动态启停管理接口
简介：golang 结构体零值可用性原则，go 结构体尽量做到零值可用，不用初始化直接使用提升易用性。
 | 原文链接：http://wiki.y8fmju.asia/arts/856365.Doc

原标题：Issue：日志疯狂打日志快速占满磁盘空间
简介：多线程线程安全脏数据规避，梳理多线程共享变量，做好同步控制，避免并发修改产生脏数据。
 | 原文链接：http://wiki.y8fmju.asia/arts/382180.Doc

原标题：golang rsa 非对称加密签名验签
简介：golang excel 简单读写操作示例，Go 实现 Excel 简单读写，业务数据导出 Excel 报表。
 | 原文链接：http://wiki.y8fmju.asia/arts/230402.Doc

原标题：前端防抖节流高频事件处理
简介：golang redis lua 脚本原子操作，使用 Lua 脚本实现原子逻辑，减少网络往返，保障多命令原子执行。
 | 原文链接：http://wiki.y8fmju.asia/arts/829656.Doc


二、踩坑排错｜Troubleshooting
原标题：golang 系统设计 id 生成器选型对比
简介：前端组件库按需加载性能优化，配置组件库按需引入，避免引入全部组件，减少打包产物体积。
 | 原文链接：http://wiki.y8fmju.asia/arts/759817.Doc

原标题：CDN 缓存刷新获取最新静态资源
简介：golang time 定时器重置 Reset 正确用法，Timer Reset 调用前提，避免 Reset 带来逻辑错误。
 | 原文链接：http://wiki.y8fmju.asia/arts/485914.Doc

原标题：Debug：消息队列死信队列堆积无人处理业务阻塞
简介：golang go 项目 CI github actions 配置，github actions 实现 go 项目 ci，自动测试、代码检查、编译打包镜像。
 | 原文链接：http://wiki.y8fmju.asia/arts/831517.Doc

原标题：golang consul 健康检查服务注册
简介：前端错误监控上报系统搭建，搭建前端错误监控，捕获页面 JS 错误，上报后端，快速发现线上页面 bug。
 | 原文链接：http://wiki.y8fmju.asia/arts/374455.Doc

原标题：golang 系统设计压测数据构造方法实现
简介：接口签名验签完整安全方案，一套完整接口签名方案，包含签名生成、请求携带、服务端验签校验。
 | 原文链接：http://wiki.y8fmju.asia/arts/774402.Doc

原标题：nestjs 全局返回格式统一处理
简介：文件描述符优化进程卡死修复，及时关闭文件句柄，控制打开文件数量，解决文件句柄耗尽进程卡死。
 | 原文链接：http://wiki.y8fmju.asia/arts/823835.Doc

原标题：实践：API接口文档自动导出离线文档实践
简介：axios 二次封装请求拦截处理，对 axios 做二次封装，统一请求拦截响应拦截，处理错误、token 自动刷新。
 | 原文链接：http://wiki.y8fmju.asia/arts/371195.Doc

原标题：vite 插件开发自定义构建逻辑
简介：全平台系统环境变量配置，汇总多操作系统环境变量配置方法，统一项目读取逻辑，适配不同运行平台。
 | 原文链接：http://wiki.y8fmju.asia/arts/355431.Doc

原标题：golang 系统设计缓存预热脚本编写实操
简介：golang 优雅停机服务关闭实现，监听系统信号，关闭服务等待请求处理完毕，实现 Go 服务优雅停机。
 | 原文链接：http://wiki.y8fmju.asia/arts/017421.Doc

原标题：安全笔记：GitHubAction密钥安全管理
简介：Fork 开源项目同步上游代码，Fork 开源仓库之后，配置上游源，同步官方最新代码，保持代码版本对齐。
 | 原文链接：http://wiki.y8fmju.asia/arts/253642.Doc

原标题：开发记录：容器日志标准输出采集实践方案
简介：程序性能指标 CPU 内存监控，讲解基础性能指标含义，简单实现监控采集，初步定位程序运行性能瓶颈。
 | 原文链接：http://wiki.y8fmju.asia/arts/941431.Doc

原标题：实战：Redis集群本地搭建与功能验证
简介：OOMKilled 容器被杀完整排查，排查容器被 OOM 终止完整流程，区分程序内存泄露和容器内存限制过小。
 | 原文链接：http://wiki.y8fmju.asia/arts/266047.Doc

原标题：﻿【GettingStarted】从零搭建本地开发环境完整指南
简介：新手参与开源社区贡献指南，介绍开源社区基础规则，讲解阅读 issue、提交 PR 流程，指导开发者参与开源贡献。
 | 原文链接：http://wiki.y8fmju.asia/arts/694170.Doc

原标题：实践：大文件分片上传后端完整实现思路
简介：图片上传预览格式大小处理，实现图片上传接口，校验文件格式、大小，完成上传后预览处理。
 | 原文链接：http://wiki.y8fmju.asia/arts/644476.Doc

原标题：DevOps：制品仓库管理二进制产物版本
简介：golang go 错误包装 fmt.Errorf % w，使用 % w 包装错误，支持 errors.Is errors.As 判断错误类型。
 | 原文链接：http://wiki.y8fmju.asia/arts/800869.Doc

原标题：golang jwt 鉴权中间件完整示例
简介：OAuth2 第三方登录服务搭建，搭建 OAuth2 服务，支持第三方账号登录，实现授权登录能力。
 | 原文链接：http://wiki.y8fmju.asia/arts/806344.Doc

原标题：方案设计：接口版本管理架构向前兼容策略
简介：golang httptest 模拟外部 http 服务，httptest.NewServer 模拟第三方 http 服务，单元测试 mock 外部接口。
 | 原文链接：http://wiki.y8fmju.asia/arts/563718.Doc

原标题：golang kafka 消费者组原理讲解
简介：golang 工具函数库封装思路，Go 通用工具库封装思路，错误处理、类型转换，业务项目复用工具代码。
 | 原文链接：http://wiki.y8fmju.asia/arts/929133.Doc

原标题：死信队列处理消息阻塞业务
简介：golang tidb 数据库 go 项目适配，go 程序适配 tidb，兼容 mysql 协议，分布式数据库业务开发。
 | 原文链接：http://wiki.y8fmju.asia/arts/142469.Doc

原标题：golang k8s cronjob 定时任务配置
简介：golang go mod 私有 git 仓库配置，配置 go mod 拉取私有仓库代码，处理私有模块依赖拉取问题。
 | 原文链接：http://wiki.y8fmju.asia/arts/701899.Doc

原标题：性能复盘：锁粒度太大，拆分细粒度锁优化
简介：golang 结构体 json 序列化坑点，梳理 Go 结构体 JSON 序列化高频坑点，字段大小写、零值处理问题。
 | 原文链接：http://wiki.y8fmju.asia/arts/855287.Doc

原标题：golang 系统设计 json 解析性能优化实操
简介：手写简易 RPC 服务通信原型，手写极简 RPC 原型，理解服务注册、网络传输、方法调用底层逻辑。
 | 原文链接：http://wiki.y8fmju.asia/arts/233692.Doc

原标题：实践：消息队列死信处理业务落地实践
简介：操作系统内核版本适配服务，针对服务运行要求，适配操作系统内核版本，规避内核兼容 bug。
 | 原文链接：http://wiki.y8fmju.asia/arts/222957.Doc

原标题：大事务拆分回滚日志暴涨解决
简介：异步任务堆积消费能力优化，处理消息任务堆积问题，提升消费处理速度，恢复队列正常处理水位。
 | 原文链接：http://wiki.y8fmju.asia/arts/562628.Doc

原标题：golang 系统设计故障演练简单思路
简介：golang 性能压测 wr 工具实操指南，wr 压测工具对 Go 接口压测，观察 QPS 延迟，定位接口性能瓶颈。
 | 原文链接：http://wiki.y8fmju.asia/arts/679881.Doc

原标题：golang redis 布隆过滤器安装使用
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://wiki.y8fmju.asia/arts/422998.Doc

原标题：golang 系统设计缓存 key 淘汰雪崩防护思路
简介：golang gorm 批量插入性能调优，GORM 批量插入优化，调整批次大小，提升大量数据插入数据库速度。
 | 原文链接：http://wiki.y8fmju.asia/arts/182761.Doc

原标题：golang docker 部署 mongodb 开发环境
简介：日志敏感信息脱敏泄露防护，日志打印时自动脱敏手机号身份证，避免日志输出泄露用户隐私数据。
 | 原文链接：http://wiki.y8fmju.asia/arts/481632.Doc

原标题：Issue：连接池参数不合理，大量连接被耗尽
简介：golang go 服务日志输出 journald，systemd journald 接收程序 stdout 日志，统一管理服务日志。
 | 原文链接：http://wiki.y8fmju.asia/arts/675957.Doc

原标题：避坑：正则回溯引发CPU占满DoS风险
简介：express 请求参数校验处理，接入参数校验库，校验入参，拦截非法参数，提前拦截错误请求。
 | 原文链接：http://wiki.y8fmju.asia/arts/456866.Doc

原标题：Hands‑on：简易频率统计组件Redis实现
简介：golang mysql 事务回滚异常处理，Go MySQL 事务异常捕获，正确回滚事务，保证异常场景数据回滚。
 | 原文链接：http://wiki.y8fmju.asia/arts/250100.Doc

原标题：golang 系统设计链路数据存储选型对比讲解
简介：特殊输入字符过滤解析防护，过滤用户输入特殊字符，防止解析报错，规避恶意字符带来业务异常。
 | 原文链接：http://wiki.y8fmju.asia/arts/888069.Doc

原标题：golang 系统设计分表 id 生成策略对比
简介：golang go 比较运算符可比较类型，哪些类型可以直接 == 比较，map slice 函数不可直接比较。
 | 原文链接：http://wiki.y8fmju.asia/arts/967005.Doc

原标题：排错：前端打包chunk过大浏览器加载缓慢
简介：golang 灰度发布流量权重路由实现，根据权重切分流量，部分流量访问新版本服务，实现灰度发布。
 | 原文链接：http://wiki.y8fmju.asia/arts/733373.Doc

原标题：性能笔记：RPC超时参数优化防止级联阻塞
简介：golang 分布式追踪全链路日志打印，日志打印 traceId，各个服务日志可串联，排查跨服务调用问题。
 | 原文链接：http://wiki.y8fmju.asia/arts/015705.Doc

原标题：项目实践：多环境配置管理组件设计与实现
简介：golang icmp ping 程序实现，go 实现 ping 工具发送 icmp 报文，检测网络连通性。
 | 原文链接：http://wiki.y8fmju.asia/arts/195559.Doc

原标题：golang 系统设计开源项目依赖版本升级维护
简介：golang json 解析未知动态 json 结构，解析到 map [string] any 处理未知 json，动态读取字段。
 | 原文链接：http://wiki.y8fmju.asia/arts/159329.Doc

原标题：Practice：模拟数据库故障验证降级逻辑实践
简介：golang defer 执行顺序与坑点，defer 后进先出，循环内部 defer 陷阱，资源释放正确写法。
 | 原文链接：http://wiki.y8fmju.asia/arts/896981.Doc

原标题：调优方案：MySQL缓冲池参数性能调优实践
简介：golang ip2regionIP 地址解析实战，集成 ip2region 库，根据 IP 解析归属地城市，实现 IP 地域解析。
 | 原文链接：http://wiki.y8fmju.asia/arts/013184.Doc

原标题：golang grafana 监控面板简单配置
简介：golang 图片处理 go 图片裁剪压缩，golang 图像处理库，图片缩放裁剪水印，服务端图片处理。
 | 原文链接：http://wiki.y8fmju.asia/arts/556988.Doc

三、实战开发｜Practice
原标题：Architecture：链路追踪架构核心组件与埋点
简介：golang 延迟队列实现方案对比，时间轮、redis zset 实现延迟队列，处理延时执行业务。
 | 原文链接：http://wiki.y8fmju.asia/arts/644749.Doc

原标题：golang 系统设计集成测试环境准备清理实操
简介：golang docker 多阶段构建 go 镜像，Go 项目 Docker 多阶段构建，编译与运行阶段分离，大幅度缩减最终镜像体积，提升镜像分发效率。
 | 原文链接：http://wiki.y8fmju.asia/arts/075889.Doc

原标题：golang docker 部署 kafka 本地调试
简介：golang systemd 配置 go 服务部署，编写 systemd unit 文件管理 go 服务，开机自启、崩溃自动重启。
 | 原文链接：http://wiki.y8fmju.asia/arts/417775.Doc

原标题：性能复盘：网络IO优化减少接口等待时间
简介：极简方式搭建个人技术文档站点，使用轻量化工具快速部署文档站点，支持 markdown 编写，实现知识沉淀与对外分享。
 | 原文链接：http://wiki.y8fmju.asia/arts/865148.Doc

原标题：设计思考：系统幂等性整体架构层面保障
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://wiki.y8fmju.asia/arts/820381.Doc

原标题：踩坑记录：文件描述符不足，上传功能随机失败
简介：golang context 上下文传参讲解，讲解 Context 使用场景，传递元数据、控制协程超时取消，规范协程控制。
 | 原文链接：http://wiki.y8fmju.asia/arts/219248.Doc

原标题：项目依赖安全扫描漏洞防范
简介：golang 命令行交互 cobra 开发 cli，cobra 库开发功能完善命令行工具，子命令参数标志解析。
 | 原文链接：http://wiki.y8fmju.asia/arts/448443.Doc

原标题：线上故障：Redis内存淘汰策略错误数据丢失
简介：序列化版本不一致解析失败，保证序列化对象版本对齐，修复版本不匹配导致对象反序列化失败。
 | 原文链接：http://wiki.y8fmju.asia/arts/616231.Doc

原标题：多套环境灵活切换配置方案
简介：golang 接口返回统一封装工具，封装 Go 接口统一返回工具，标准化成功失败返回结构体。
 | 原文链接：http://wiki.y8fmju.asia/arts/872119.Doc

原标题：排错：静态资源CDN缓存未刷新旧资源持续返回
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://wiki.y8fmju.asia/arts/607862.Doc

原标题：Troubleshoot：RPC序列化对象字段增减兼容踩坑
简介：请求工具封装统一异常处理，对网络请求做二次封装，统一捕获各类请求异常，标准化接口返回格式。
 | 原文链接：http://wiki.y8fmju.asia/arts/837463.Doc

原标题：golang k8s service 服务暴露几种类型
简介：golang trace 可视化分析协程阻塞，使用 trace 网页 UI，定位协程阻塞、系统调用阻塞、锁等待。
 | 原文链接：http://wiki.y8fmju.asia/arts/511640.Doc

原标题：优化实践：批量操作性能优化，减少数据库IO
简介：golang 信号触发配置重载实践，收到 SIGUSR1 信号重新加载配置，线上无需重启刷新配置。
 | 原文链接：http://wiki.y8fmju.asia/arts/342836.Doc

原标题：golang es 查询语句 DSL 实操
简介：golang go 死锁检测工具，静态检查、运行检测，发现 channel 锁导致死锁问题。
 | 原文链接：http://wiki.y8fmju.asia/arts/903051.Doc

原标题：golang 系统设计日志架构采集存储检索完整链路
简介：代码格式化工具团队统一风格，接入格式化工具，统一全团队代码书写风格，减少格式类 git 冲突。
 | 原文链接：http://wiki.y8fmju.asia/arts/971520.Doc

原标题：实践：多配置文件合并加载组件实现
简介：时间精度统一业务判断修复，统一业务使用时间戳精度，毫秒秒区分清楚，修复时间判断逻辑错误。
 | 原文链接：http://wiki.y8fmju.asia/arts/661247.Doc

原标题：nodejs 单元测试 jest 实操教程
简介：golang 网卡 ip 读取网络信息获取，程序读取本机网卡 IP，多网卡环境筛选业务使用 IP 地址。
 | 原文链接：http://wiki.y8fmju.asia/arts/373903.Doc

原标题：golang 系统设计 commit 提交规范约定
简介：gitignore 文件编写过滤规则，讲解 gitignore 语法，编写过滤配置，忽略缓存、编译产物、密钥文件，保持仓库整洁。
 | 原文链接：http://wiki.y8fmju.asia/arts/599894.Doc

原标题：开源实践：开源项目本地调试构建排坑经验
简介：golang kafka 同步异步消费对比，对比 Kafka 同步消费异步消费，分析优缺点，业务选型参考。
 | 原文链接：http://wiki.y8fmju.asia/arts/393777.Doc

原标题：golang 系统设计日志架构采集存储检索完整链路
简介：golang go 泛型使用避坑注意点，泛型与 interface 区别，泛型性能，什么时候适合使用泛型。
 | 原文链接：http://wiki.y8fmju.asia/arts/306112.Doc

原标题：golang 数据库批量更新性能优化
简介：golang go mod why 查询依赖引入原因，go mod why 查询为什么引入某个包，理清依赖来源。
 | 原文链接：http://wiki.y8fmju.asia/arts/818447.Doc

原标题：坑点：gitcherry‑pick引入不兼容代码
简介：golang http 服务优雅关闭完整示例，接收终止信号，停止接收新请求，等待现有请求处理完毕后退出服务。
 | 原文链接：http://wiki.y8fmju.asia/arts/232844.Doc

原标题：golang 系统设计数据库版本迁移回滚方案
简介：golang 接口限流中间件开发，Gin 开发限流中间件，接口层实现访问频率限制，防护接口流量。
 | 原文链接：http://wiki.y8fmju.asia/arts/962221.Doc

原标题：golang 系统设计缓存热点 key 问题业务规避
简介：golang 项目 go mod 依赖管理，Go Mod 管理项目依赖，下载、升级、清理依赖，解决依赖版本管理。
 | 原文链接：http://wiki.y8fmju.asia/arts/201237.Doc

原标题：部署复盘：回滚策略，线上故障快速回退
简介：golang accept 错误循环崩溃处理，accept 返回系统错误，处理临时错误，避免死循环占满 CPU。
 | 原文链接：http://wiki.y8fmju.asia/arts/829730.Doc

原标题：开发环境变量配置全平台教程
简介：golang net/url 路径拼接处理，url.ParseRequestURI 处理请求 url，正确拼接 url 路径避免拼接错误。
 | 原文链接：http://wiki.y8fmju.asia/arts/699500.Doc

原标题：方案设计：分布式锁失效风险架构层面规避
简介：golang hystrix 模式简易熔断实现，简易熔断组件，错误率达到阈值触发熔断，快速失败保护下游。
 | 原文链接：http://wiki.y8fmju.asia/arts/374605.Doc

原标题：golang mysql 避免 select * 查询
简介：golang kitex 中间件与元数据传递，kitex 自定义中间件，透传 traceId 鉴权元数据，统一处理请求。
 | 原文链接：http://wiki.y8fmju.asia/arts/830173.Doc

原标题：Practice：实现接口签名、验签完整示例代码
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://wiki.y8fmju.asia/arts/342446.Doc

原标题：Nginx 静态代理负载均衡全套配置
简介：golang sql 注入风险规避要点，参数化查询杜绝 sql 注入，禁止字符串拼接 SQL 语句执行。
 | 原文链接：http://wiki.y8fmju.asia/arts/558335.Doc

原标题：golang kafka 重试机制配置实操
简介：golang 负载均衡轮询加权轮询实现，手写负载均衡算法，轮询、加权轮询分发请求到后端节点。
 | 原文链接：http://wiki.y8fmju.asia/arts/315551.Doc

原标题：安全实践：API密钥管理轮换最佳实践
简介：项目依赖安全扫描漏洞防范，扫描项目第三方依赖包，修复存在安全漏洞依赖，防范供应链攻击。
 | 原文链接：http://wiki.y8fmju.asia/arts/454711.Doc

原标题：记一次第三方SDK版本兼容引发线上故障
简介：golang slice 切片底层原理与坑点，切片扩容、截取、底层数组共享，规避切片修改互相影响数据。
 | 原文链接：http://wiki.y8fmju.asia/arts/765744.Doc

原标题：文件描述符优化进程卡死修复
简介：golang redis 锁超时业务处理，Redis 分布式锁超时问题处理，锁续期逻辑，防止业务未完成锁提前释放。
 | 原文链接：http://wiki.y8fmju.asia/arts/339513.Doc

原标题：Nginx 透传真实客户端 IP 配置
简介：开源源码阅读拆解学习思路，分享阅读大型开源项目方法，从入口文件逐层拆解模块，降低源码学习门槛。
 | 原文链接：http://wiki.y8fmju.asia/arts/880566.Doc

原标题：全量回归测试提升代码质量
简介：golang grpc 客户端拦截器封装，grpc 客户端拦截器实现请求统一签名、重试、链路信息透传。
 | 原文链接：http://wiki.y8fmju.asia/arts/847116.Doc

原标题：日志输出规范防止磁盘爆满
简介：nodejs 集群模式多核利用实现，使用 cluster 集群模式，充分利用服务器多核 CPU，提升服务处理能力。
 | 原文链接：http://wiki.y8fmju.asia/arts/112881.Doc

原标题：方案设计：异步解耦业务架构边界识别
简介：golang go 二进制安全 strip 减小体积，strip 剥离二进制调试符号，缩小程序二进制文件体积。
 | 原文链接：http://wiki.y8fmju.asia/arts/108076.Doc

原标题：golang 系统设计缓存优化落地实操指南
简介：golang proto 可选字段处理方案，protobuf 可选字段正确判断，区分未赋值与零值，业务逻辑不出现偏差。
 | 原文链接：http://wiki.y8fmju.asia/arts/741184.Doc

原标题：效率笔记：提升开发效率shell脚本小工具合集
简介：golang atomic 原子操作整数，atomic 加减比较交换，无锁更新整型变量，简单计数器场景。
 | 原文链接：http://wiki.y8fmju.asia/arts/231181.Doc

四、架构设计｜Architecture
原标题：Hands‑on：实现服务健康检查与自动报警demo
简介：golang nats 轻量消息队列 go 开发，nats 高性能轻量消息系统，发布订阅模式异步解耦业务。
 | 原文链接：http://wiki.y8fmju.asia/arts/799100.Doc

原标题：零基础理解模块化与组件化基础思想
简介：golang goroutine 泄露常见场景汇总，channel 阻塞、context 忘记取消，导致协程无法退出发生泄露。
 | 原文链接：http://wiki.y8fmju.asia/arts/511287.Doc

原标题：复盘总结：分布式系统常见坑点汇总清单
简介：nodejs 内存溢出问题排查修复，Node.js 程序 OOM 排查流程，定位内存泄露，调整内存限制修复崩溃。
 | 原文链接：http://wiki.y8fmju.asia/arts/295762.Doc

原标题：golang 系统设计 rest 资源命名规范汇总
简介：golang prometheus 指标埋点开发，业务埋点计数器、仪表盘、直方图，对接 prometheus 采集监控指标。
 | 原文链接：http://wiki.y8fmju.asia/arts/204927.Doc

原标题：golang k8s 滚动更新回滚策略
简介：golang go 自定义错误类型实现，自定义 error 结构体，携带错误码、堆栈信息，统一业务错误。
 | 原文链接：http://wiki.y8fmju.asia/arts/916848.Doc

原标题：golang 日志 zap 结构化日志实践
简介：golang 自定义 http round tripper，封装 http 客户端拦截，实现请求日志、签名、重试统一处理逻辑。
 | 原文链接：http://wiki.y8fmju.asia/arts/498085.Doc

原标题：业务错误码体系设计方案
简介：死信队列处理消息阻塞业务，配置死信队列，处理消费失败消息，避免失败消息阻塞整个队列业务。
 | 原文链接：http://wiki.y8fmju.asia/arts/165019.Doc

原标题：数据库读写分离性能优化
简介：多操作系统开发兼容处理，解决不同系统路径、换行符、权限差异，保证项目跨平台正常运行。
 | 原文链接：http://wiki.y8fmju.asia/arts/539061.Doc

原标题：golang 系统设计 webhook 回调处理架构
简介：golang 钉钉企业微信告警消息推送，go 调用企业微信钉钉接口，推送告警通知、业务消息。
 | 原文链接：http://wiki.y8fmju.asia/arts/555193.Doc

原标题：Architecture：API设计RESTful最佳实践与反模式
简介：热更新开发环境配置教程，配置代码热重载，修改代码无需重启服务立即生效，大幅提升本地开发调试效率。
 | 原文链接：http://wiki.y8fmju.asia/arts/994943.Doc

原标题：golang 系统设计 vscode go 插件调试配置实操
简介：业务接口幂等完整落地案例，完整业务场景幂等落地示例，覆盖表单提交、回调、重试各类场景。
 | 原文链接：http://wiki.y8fmju.asia/arts/769512.Doc

原标题：golang 系统设计 rest 状态码合理使用指南
简介：CI 流水线超时时间延长配置，调大 CI 任务超时阈值，解决构建任务耗时较长被流水线强制终止。
 | 原文链接：http://wiki.y8fmju.asia/arts/908950.Doc

原标题：排坑：Git提交历史混乱，如何清理错误提交
简介：golang atomic 原子操作整数，atomic 加减比较交换，无锁更新整型变量，简单计数器场景。
 | 原文链接：http://wiki.y8fmju.asia/arts/088838.Doc

原标题：golang 系统设计回调签名校验防伪造实现
简介：前端组件库按需加载性能优化，配置组件库按需引入，避免引入全部组件，减少打包产物体积。
 | 原文链接：http://wiki.y8fmju.asia/arts/561357.Doc

原标题：新手指南：虚拟机WSL开发环境入门配置
简介：golang go 错误包装 fmt.Errorf % w，使用 % w 包装错误，支持 errors.Is errors.As 判断错误类型。
 | 原文链接：http://wiki.y8fmju.asia/arts/394052.Doc

原标题：golang 互斥锁读写锁并发安全
简介：前后端会话登录状态持久化，实现登录状态持久存储，重启服务登录状态不丢失，保障会话稳定性。
 | 原文链接：http://wiki.y8fmju.asia/arts/330680.Doc

原标题：部署复盘：容器OOM问题完整排查流程
简介：前端下载导出文件功能实现，前端实现文件流下载导出，处理异常，适配浏览器不同下载行为。
 | 原文链接：http://wiki.y8fmju.asia/arts/017084.Doc

原标题：HTTP 状态码请求头完整梳理
简介：开源项目本地运行排错完整清单，汇总开源项目拉取后运行失败各类问题，给出排查思路，快速解决本地启动异常。
 | 原文链接：http://wiki.y8fmju.asia/arts/314408.Doc

?
