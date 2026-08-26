最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang defer panic 异常处理
简介：golang 容器时区设置镜像构建处理，镜像内部设置正确时区，解决容器时间与宿主机不一致。
 | 原文链接：http://wiki.87s1od.asia/arts/745258.Doc

原标题：方案设计：多租户系统架构三种实现模式对比
简介：golang strconv 字符串类型转换，字符串转数字布尔，处理转换失败 error，避免 panic。
 | 原文链接：http://wiki.87s1od.asia/arts/862685.Doc

原标题：golang git 提交信息规范校验
简介：超大数据集分页性能优化方案，对比不同分页方案，针对海量数据集做分页性能优化，解决越翻越慢。
 | 原文链接：http://wiki.87s1od.asia/arts/004250.Doc

原标题：数据库主从延迟业务兼容处理
简介：OOMKilled 容器被杀完整排查，排查容器被 OOM 终止完整流程，区分程序内存泄露和容器内存限制过小。
 | 原文链接：http://wiki.87s1od.asia/arts/124640.Doc

原标题：程序日志分级输出规范实践
简介：golang 链路追踪简易实现方案，简易链路追踪实现，传递 traceId，记录调用链路，方便排查慢调用。
 | 原文链接：http://wiki.87s1od.asia/arts/037115.Doc

原标题：安全笔记：文件下载接口路径校验安全
简介：包管理器依赖缓存清理，清理本地依赖缓存，解决缓存旧包引发问题，拉取最新版本依赖包。
 | 原文链接：http://wiki.87s1od.asia/arts/822784.Doc

原标题：优化实践：序列化框架性能对比选型实践
简介：golang go url url.Values 参数编码，url.Values 构建 url 查询参数，自动处理参数 url 编码。
 | 原文链接：http://wiki.87s1od.asia/arts/940232.Doc

原标题：端口占用访问失败排查方案
简介：golang hertz 性能优化参数调优，hertz 连接池、缓冲区参数调优，最大化接口吞吐性能。
 | 原文链接：http://wiki.87s1od.asia/arts/271877.Doc

原标题：TCP 长连接参数优化 TIME_WAIT
简介：golang net.Listener 包装自定义监听器，包装 Listener 做连接计数、连接拦截，扩展网络能力。
 | 原文链接：http://wiki.87s1od.asia/arts/609449.Doc

原标题：前端国际化多语言方案落地
简介：文件句柄上限调整上传随机失败，调高系统文件句柄上限，解决高并发上传场景随机打开文件失败。
 | 原文链接：http://wiki.87s1od.asia/arts/531954.Doc

原标题：Hands‑on：简易邮件发送服务封装实践
简介：golang 字符串处理常用技巧汇总，字符串拼接、分割、替换、类型转换实操，规避字符串高频错误。
 | 原文链接：http://wiki.87s1od.asia/arts/206581.Doc

原标题：golang 系统设计错误码体系完整设计
简介：文件分片上传断点续传功能，实现文件分片上传，记录上传进度，支持断点续传大文件上传。
 | 原文链接：http://wiki.87s1od.asia/arts/158657.Doc

原标题：复盘总结：数据库迁移升级风险评估清单
简介：golang go 程序 CPU 占用高定位步骤，pprof 定位热点函数，分析 CPU 高占用，优化耗时代码逻辑。
 | 原文链接：http://wiki.87s1od.asia/arts/044958.Doc

原标题：Hands‑on：shell脚本批量自动化运维小工具
简介：移动端适配 rem vw 方案对比，对比 rem 与 vw 移动端适配方案，分析优缺点，给出选型建议。
 | 原文链接：http://wiki.87s1od.asia/arts/770633.Doc

原标题：golang 系统设计用户签到统计方案
简介：golang go http 服务器优雅关闭完整代码，http.Server Shutdown，等待现有请求处理完成关闭服务。
 | 原文链接：http://wiki.87s1od.asia/arts/720633.Doc

原标题：golang base64 编码解码实操
简介：golang grpc keepalive 保活配置，grpc keepalive 参数调优，检测断开僵死连接，释放无效连接资源。
 | 原文链接：http://wiki.87s1od.asia/arts/159060.Doc

原标题：日志输出规范防止磁盘爆满
简介：golang rate‑limiter 限流组件，封装通用 Go 限流组件，支持多算法，业务接口直接复用调用。
 | 原文链接：http://wiki.87s1od.asia/arts/883162.Doc

原标题：golang 系统设计数据库表设计通用规范模板
简介：golang go yaml 解析自定义类型，yaml 自定义序列化，时间、特殊类型自定义解析逻辑。
 | 原文链接：http://wiki.87s1od.asia/arts/232817.Doc

原标题：golang grafana 面板变量模板制作
简介：百万数据 Excel 导出内存优化，优化大 Excel 导出逻辑，流式输出，避免一次性加载全部数据造成 OOM。
 | 原文链接：http://wiki.87s1od.asia/arts/742526.Doc

原标题：css 动画性能优化 GPU 加速
简介：golang https 客户端跳过证书校验，开发测试环境跳过 tls 证书校验，仅用于内网测试禁止生产使用。
 | 原文链接：http://wiki.87s1od.asia/arts/715829.Doc

原标题：golang redis 客户端业务使用
简介：golang multipart 表单文件上传解析，服务端解析 multipart 表单，获取上传文件与表单字段。
 | 原文链接：http://wiki.87s1od.asia/arts/984940.Doc

原标题：OpenSource：如何高效阅读大型开源项目源码
简介：golang go 程序守护进程实现思路，go 程序不做 daemon 化，依靠 systemd pm2 k8s 实现进程守护。
 | 原文链接：http://wiki.87s1od.asia/arts/108267.Doc

原标题：golang 系统设计开源项目协作流程梳理
简介：golang go 泛型使用避坑注意点，泛型与 interface 区别，泛型性能，什么时候适合使用泛型。
 | 原文链接：http://wiki.87s1od.asia/arts/317222.Doc

原标题：golang 容器健康检查接口开发
简介：golang jwt 鉴权中间件完整示例，Gin JWT 鉴权中间件，令牌校验，解析用户信息，接口鉴权拦截。
 | 原文链接：http://wiki.87s1od.asia/arts/564525.Doc

原标题：golang 系统设计分布式锁超时业务防死锁处理
简介：前端虚拟列表大数据渲染优化，实现虚拟滚动列表，只渲染可视区域 DOM，上万条数据页面流畅渲染。
 | 原文链接：http://wiki.87s1od.asia/arts/123193.Doc

原标题：golang 系统设计 git 工作流本地开发提交流程
简介：golang go‑zero rpc 微服务开发，go‑zero 定义 proto，生成 rpc 服务代码，实现微服务调用。
 | 原文链接：http://wiki.87s1od.asia/arts/187700.Doc

原标题：Practice：模拟第三方接口超时服务降级验证
简介：golang 集成测试测试数据库回滚，集成测试结束自动回滚数据库，不污染测试环境数据。
 | 原文链接：http://wiki.87s1od.asia/arts/473500.Doc

原标题：golang 系统设计开源项目维护简单经验分享
简介：golang go mod 私有 git 仓库配置，配置 go mod 拉取私有仓库代码，处理私有模块依赖拉取问题。
 | 原文链接：http://wiki.87s1od.asia/arts/162480.Doc

原标题：Nginx 反向代理路由配置实战
简介：Git 标签版本标记发布管理，使用 Git 标签标记项目版本，打标签推送远程，用于版本发布、版本回溯。
 | 原文链接：http://wiki.87s1od.asia/arts/859177.Doc

原标题：文件读写与异常捕获代码示例
简介：golang go math 大数高精度计算，math/big 处理超大整数、高精度浮点数，金额大数运算。
 | 原文链接：http://wiki.87s1od.asia/arts/018207.Doc

原标题：golang k8s devops 流水线简单思路
简介：golang 漏桶算法实现接口限流，漏桶算法控制请求流出速率，平滑突发流量，削平流量峰值。
 | 原文链接：http://wiki.87s1od.asia/arts/345306.Doc

原标题：golang 系统设计 ide 配置 go 开发效率提升技巧
简介：golang 命令行交互 cobra 开发 cli，cobra 库开发功能完善命令行工具，子命令参数标志解析。
 | 原文链接：http://wiki.87s1od.asia/arts/047259.Doc

原标题：开发复盘：百万数据批量导入数据库优化方案
简介：WSL 搭建 Windows Linux 开发环境，配置 WSL 环境，在 Windows 系统使用 Linux 工具链，适配 Linux 开发项目。
 | 原文链接：http://wiki.87s1od.asia/arts/185379.Doc

原标题：nodejs 内存溢出问题排查修复
简介：golang embed 目录读取文件列表，embed 嵌入整个目录，读取目录下全部文件，做静态资源服务。
 | 原文链接：http://wiki.87s1od.asia/arts/030400.Doc

原标题：排错：静态资源404，打包路径配置错误
简介：golang go 并发模式 fan‑out fan‑in，fanout 分发任务 fanin 汇总结果，多协程并发处理任务。
 | 原文链接：http://wiki.87s1od.asia/arts/112035.Doc

原标题：golang 系统设计时间字段选型 datetime timestamp
简介：golang go‑zero 缓存自动击穿防护，go‑zero 缓存组件自带缓存击穿防护，减少缓存层故障。
 | 原文链接：http://wiki.87s1od.asia/arts/748326.Doc

原标题：轻量 API 后端接口服务快速开发
简介：程序性能指标 CPU 内存监控，讲解基础性能指标含义，简单实现监控采集，初步定位程序运行性能瓶颈。
 | 原文链接：http://wiki.87s1od.asia/arts/587326.Doc

原标题：golang 系统设计分表扩容数据平滑迁移思路
简介：golang go mod exclude 排除依赖版本，exclude 排除有问题依赖版本，规避有 bug 的第三方包。
 | 原文链接：http://wiki.87s1od.asia/arts/523410.Doc

原标题：golang 系统设计压测指标 qps rt 错误率讲解
简介：Redis 内存淘汰策略数据防丢失，合理配置 Redis 内存淘汰策略，防止内存满后误删除业务重要数据。
 | 原文链接：http://wiki.87s1od.asia/arts/021618.Doc

原标题：golang 系统设计接口向前兼容改造实操
简介：golang 进程信号捕获 SIGUSR 自定义信号，捕获用户自定义信号，实现线上不重启触发调试、日志切换。
 | 原文链接：http://wiki.87s1od.asia/arts/237141.Doc


二、踩坑排错｜Troubleshooting
原标题：Practice：实现接口幂等性多种方案对比实践
简介：文件分片上传断点续传功能，实现文件分片上传，记录上传进度，支持断点续传大文件上传。
 | 原文链接：http://wiki.87s1od.asia/arts/425265.Doc

原标题：golang 系统设计消息队列降级业务开关实现
简介：golang grpc 服务端流推送数据，服务端流式响应，服务端持续向客户端推送多条响应消息。
 | 原文链接：http://wiki.87s1od.asia/arts/915065.Doc

原标题：浏览器内存泄漏排查前端页面
简介：golang sync/atomic 原子操作使用注意，理解原子操作内存顺序，规避原子操作错误使用带来 bug。
 | 原文链接：http://wiki.87s1od.asia/arts/906299.Doc

原标题：安全笔记：CSP内容安全策略配置实践
简介：golang 跨域处理中间件编写，Gin 跨域中间件开发，处理预检 OPTIONS 请求，解决浏览器跨域报错。
 | 原文链接：http://wiki.87s1od.asia/arts/529466.Doc

原标题：Practice：实现业务id生成不连续有序ID方案
简介：golang go 程序抢占调度理解，理解 go 抢占式调度原理，长循环阻塞调度，造成协程调度延迟。
 | 原文链接：http://wiki.87s1od.asia/arts/881139.Doc

原标题：Troubleshooting：依赖安装失败完整排查清单
简介：golang defer 闭包变量捕获坑，defer 捕获循环变量引用，变量被复写，理解闭包变量捕获规则。
 | 原文链接：http://wiki.87s1od.asia/arts/634146.Doc

原标题：DevOps：多阶段构建Dockerfile最佳实践
简介：golang go toml 配置注释保留，toml 解析保留注释，修改配置后写回保留原有注释。
 | 原文链接：http://wiki.87s1od.asia/arts/212250.Doc

原标题：Practice：模拟热点key，验证缓存防护策略
简介：ServiceWorker 缓存页面更新清理，处理 ServiceWorker 缓存，实现页面新版本更新，用户可以加载最新页面。
 | 原文链接：http://wiki.87s1od.asia/arts/794627.Doc

原标题：Issue：浏览器缓存ServiceWorker导致旧页面常驻
简介：golang prometheus 指标埋点开发，业务埋点计数器、仪表盘、直方图，对接 prometheus 采集监控指标。
 | 原文链接：http://wiki.87s1od.asia/arts/563414.Doc

原标题：安全复盘：环境变量密钥泄露风险与防护
简介：代码格式化工具团队统一风格，接入格式化工具，统一全团队代码书写风格，减少格式类 git 冲突。
 | 原文链接：http://wiki.87s1od.asia/arts/493401.Doc

原标题：golang 系统设计热点数据缓存处理
简介：跨平台换行符统一异常修复，统一代码文件换行符，解决不同操作系统换行符不一致带来脚本执行异常。
 | 原文链接：http://wiki.87s1od.asia/arts/142724.Doc

原标题：调优方案：静态资源缓存头Cache‑Control优化
简介：YAML 配置文件语法快速上手，讲解 YAML 基础语法、缩进规则，编写项目配置文件，规避语法错误引发程序异常。
 | 原文链接：http://wiki.87s1od.asia/arts/119407.Doc

原标题：golang 系统设计服务优雅停机完整流程
简介：golang net/url 路径拼接处理，url.ParseRequestURI 处理请求 url，正确拼接 url 路径避免拼接错误。
 | 原文链接：http://wiki.87s1od.asia/arts/477696.Doc

原标题：架构复盘：消息死信处理架构避免消息丢失
简介：golang go 泛型实现通用数据结构，泛型实现通用栈队列，复用逻辑支持多种数据类型。
 | 原文链接：http://wiki.87s1od.asia/arts/965729.Doc

原标题：架构笔记：分布式事务方案对比与业务取舍
简介：容器内存扩容 OOM 被杀死修复，调高容器内存限制，优化程序内存占用，避免程序被 OOM 终止。
 | 原文链接：http://wiki.87s1od.asia/arts/488493.Doc

原标题：缓存穿透击穿雪崩全套防护
简介：golang go select 多路等待 channel，select 等待多个 channel，default 非阻塞，超时等待 channel。
 | 原文链接：http://wiki.87s1od.asia/arts/412269.Doc

原标题：Git commit 钩子提交规范校验
简介：golang 字符串处理常用技巧汇总，字符串拼接、分割、替换、类型转换实操，规避字符串高频错误。
 | 原文链接：http://wiki.87s1od.asia/arts/533630.Doc

原标题：golang 系统设计大事务拆分实战思路
简介：CLI 工具进度条交互效果开发，在命令行工具增加进度条展示，直观反馈任务执行进度，优化命令行体验。
 | 原文链接：http://wiki.87s1od.asia/arts/907058.Doc

原标题：golang github actions 缓存依赖提速
简介：golang go 爬虫代理池轮换使用，http 代理池轮换，请求自动切换代理 IP，突破访问限制。
 | 原文链接：http://wiki.87s1od.asia/arts/370225.Doc

原标题：后端分页查询逻辑代码实现
简介：golang go race 竞态检测工具，‑race 检测数据竞争，编译运行检测并发读写数据竞争 bug。
 | 原文链接：http://wiki.87s1od.asia/arts/938469.Doc

原标题：golang 分布式锁 redis 实现
简介：JWT 令牌过期异常处理，捕获 JWT 过期、篡改异常，编写业务处理逻辑，引导用户重新获取令牌。
 | 原文链接：http://wiki.87s1od.asia/arts/493138.Doc

原标题：golang 大文件读取内存优化
简介：golang go 整洁架构代码组织实践，整洁架构依赖向内，解耦业务逻辑与外部基础设施。
 | 原文链接：http://wiki.87s1od.asia/arts/926359.Doc

原标题：新手向：配置项目eslint/prettier代码格式化
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://wiki.87s1od.asia/arts/966081.Doc

原标题：golang k8s 持久化 pv pvc 使用实操
简介：看懂报错日志快速定位问题，讲解日志阅读方法，解析堆栈信息含义，学会从报错信息中定位代码出错位置。
 | 原文链接：http://wiki.87s1od.asia/arts/460950.Doc

原标题：golang mongodb 索引优化查询速度
简介：golang prometheus http 接口暴露指标，暴露 prometheus metrics 接口，输出业务运行指标，接入监控告警系统。
 | 原文链接：http://wiki.87s1od.asia/arts/596022.Doc

原标题：部署复盘：容器资源限制CPU内存配置实践
简介：golang 单例模式实现几种方式，Go 单例模式多种实现对比，sync.Once 等方式，实现全局唯一实例。
 | 原文链接：http://wiki.87s1od.asia/arts/920654.Doc

原标题：golang 系统设计 rest 错误返回格式统一规范
简介：nodejs 内存溢出问题排查修复，Node.js 程序 OOM 排查流程，定位内存泄露，调整内存限制修复崩溃。
 | 原文链接：http://wiki.87s1od.asia/arts/837780.Doc

原标题：golang 系统设计缓存优化落地实操指南
简介：golang tls 证书加载配置 https 服务，加载证书密钥，搭建 golang https 服务，配置 tls 版本安全策略。
 | 原文链接：http://wiki.87s1od.asia/arts/072278.Doc

原标题：golang 系统设计 go benchmark 性能测试实操
简介：golang 灰度发布流量权重路由实现，根据权重切分流量，部分流量访问新版本服务，实现灰度发布。
 | 原文链接：http://wiki.87s1od.asia/arts/999205.Doc

原标题：零基础学习简单正则表达式实战案例
简介：golang 结构体零值可用性原则，go 结构体尽量做到零值可用，不用初始化直接使用提升易用性。
 | 原文链接：http://wiki.87s1od.asia/arts/442916.Doc

原标题：入门实践：项目配置文件多环境管理方案
简介：golang arp 缓存读取操作，读取系统 arp 缓存表，获取 ip 对应的 mac 地址信息。
 | 原文链接：http://wiki.87s1od.asia/arts/570327.Doc

原标题：快速入门OpenAPI文档生成基础实践
简介：golang 系统资源限制读取 cpu 内存，读取系统容器 cpu 内存限制，程序适配容器资源配额做业务调优。
 | 原文链接：http://wiki.87s1od.asia/arts/111797.Doc

原标题：golang ci 流水线漏洞扫描依赖检查
简介：Git 误删提交代码恢复找回，使用 Git reflog 工具找回被误删除提交记录，恢复误删除代码。
 | 原文链接：http://wiki.87s1od.asia/arts/856242.Doc

原标题：架构复盘：RPC框架架构超时重试设计要点
简介：前端图片懒加载性能优化，实现图片懒加载，页面可视区域才加载图片，减少页面初始网络请求。
 | 原文链接：http://wiki.87s1od.asia/arts/223908.Doc

原标题：踩坑：对象未释放，长时间运行内存持续上涨
简介：golang 单元测试 mock http 请求，mock HTTP 外部接口，单元测试不依赖外部网络，保证用例稳定运行。
 | 原文链接：http://wiki.87s1od.asia/arts/839677.Doc

原标题：golang 系统设计分布式事务几种方案
简介：golang go race 竞态检测工具，‑race 检测数据竞争，编译运行检测并发读写数据竞争 bug。
 | 原文链接：http://wiki.87s1od.asia/arts/126057.Doc

原标题：golang pprof 线上采集性能数据
简介：golang html 模板渲染简单示例，Go HTML 模板渲染，服务端渲染页面，填充数据输出 HTML 页面。
 | 原文链接：http://wiki.87s1od.asia/arts/333205.Doc

原标题：从零学习基础的接口请求与参数处理
简介：golang 熔断降级简易组件开发，Go 简易熔断组件，下游故障触发熔断，保护上游服务不被拖垮。
 | 原文链接：http://wiki.87s1od.asia/arts/670740.Doc

原标题：golang 系统设计 mq 消息顺序性保证思路
简介：golang math 包常用数学函数，绝对值取整平方根三角函数，业务数学计算工具。
 | 原文链接：http://wiki.87s1od.asia/arts/967425.Doc

原标题：排错：对象存储跨域配置不生效前端上传失败
简介：前端权限路由动态生成实现，根据后端返回权限，动态生成前端路由菜单，实现页面权限控制。
 | 原文链接：http://wiki.87s1od.asia/arts/077014.Doc

三、实战开发｜Practice
原标题：坑点：版本号语义化理解错误依赖版本错乱
简介：golang CPU 绑定亲和性设置 go 程序，设置进程 CPU 亲和绑定核心，减少 CPU 调度开销，提升计算性能。
 | 原文链接：http://wiki.87s1od.asia/arts/207751.Doc

原标题：后端登录鉴权模块完整开发
简介：文件编码统一随机乱码修复，统一项目全部文件读写编码，消除随机中文乱码，保证文本处理稳定。
 | 原文链接：http://wiki.87s1od.asia/arts/672751.Doc

原标题：后端登录鉴权模块完整开发
简介：golang go 错误包装 fmt.Errorf % w，使用 % w 包装错误，支持 errors.Is errors.As 判断错误类型。
 | 原文链接：http://wiki.87s1od.asia/arts/529941.Doc

原标题：golang 系统设计全局异常处理器实现
简介：golang gin 路由分组权限管控，Gin 路由分组，不同分组绑定鉴权中间件，实现接口权限分组管控。
 | 原文链接：http://wiki.87s1od.asia/arts/646276.Doc

原标题：开发记录：网关实现接口鉴权、限流、日志打印
简介：golang 容器时区设置镜像构建处理，镜像内部设置正确时区，解决容器时间与宿主机不一致。
 | 原文链接：http://wiki.87s1od.asia/arts/263802.Doc

原标题：项目实践：Docker多环境镜像构建策略实践
简介：golang json number 数字不转 float64，使用 json.Number 保留原始数字字符串，防止大数字精度丢失。
 | 原文链接：http://wiki.87s1od.asia/arts/696371.Doc

原标题：Issue：日志疯狂打日志快速占满磁盘空间
简介：golang go1.18 + 泛型基础实操，go 泛型基础语法，泛型函数泛型类型，实现通用工具函数。
 | 原文链接：http://wiki.87s1od.asia/arts/781335.Doc

原标题：实战：Docker资源监控查看容器状态实操
简介：golang 终端交互式输入选择，命令行交互式问答选择输入，实现交互式脚本工具。
 | 原文链接：http://wiki.87s1od.asia/arts/820619.Doc

原标题：部署复盘：配置热更新不用重启服务方案
简介：Spring 事务传播机制配置生效，理解事务传播行为，正确配置，修复事务不生效、事务失效的业务 bug。
 | 原文链接：http://wiki.87s1od.asia/arts/234519.Doc

原标题：入门实践：简单图片上传预览本地demo
简介：golang 服务注册 etcd 简单示例，etcd 实现服务注册发现，微服务实例注册元数据，客户端发现节点。
 | 原文链接：http://wiki.87s1od.asia/arts/679970.Doc

原标题：部署复盘：配置热更新不用重启服务方案
简介：golang consul 服务发现简单示例，对接 Consul 实现服务注册发现，微服务实例自动感知。
 | 原文链接：http://wiki.87s1od.asia/arts/308192.Doc

原标题：Troubleshoot：CPU调度频繁上下文切换性能下降
简介：monorepo 项目多包管理最佳实践，monorepo 仓库管理多子包，统一版本管理，处理包之间互相依赖。
 | 原文链接：http://wiki.87s1od.asia/arts/618487.Doc

原标题：调优方案：Nginx性能参数调优高并发配置
简介：golang nats 轻量消息队列 go 开发，nats 高性能轻量消息系统，发布订阅模式异步解耦业务。
 | 原文链接：http://wiki.87s1od.asia/arts/196929.Doc

原标题：安全复盘：业务接口越权测试与修复实践
简介：golang 限制 multipart 内存大小，设置 MaxMemory，大文件写入磁盘临时文件防止内存暴涨。
 | 原文链接：http://wiki.87s1od.asia/arts/935849.Doc

原标题：golang 系统设计错误码体系完整设计
简介：golang prometheus http 接口暴露指标，暴露 prometheus metrics 接口，输出业务运行指标，接入监控告警系统。
 | 原文链接：http://wiki.87s1od.asia/arts/840319.Doc

原标题：踩坑：重试逻辑未做幂等，重复生成业务数据
简介：golang ip2regionIP 地址解析实战，集成 ip2region 库，根据 IP 解析归属地城市，实现 IP 地域解析。
 | 原文链接：http://wiki.87s1od.asia/arts/936089.Doc

原标题：入门实践：简易进度条CLI工具实现demo
简介：golang go race 竞态检测工具，‑race 检测数据竞争，编译运行检测并发读写数据竞争 bug。
 | 原文链接：http://wiki.87s1od.asia/arts/237205.Doc

原标题：golang 系统设计 rest 资源命名规范汇总
简介：分布式任务调度集群原型开发，开发简易分布式调度原型，集群多节点运行，保证任务只执行一次。
 | 原文链接：http://wiki.87s1od.asia/arts/528387.Doc

原标题：开发记录：JWT过期刷新滑动过期实现实践
简介：golang alertmanager 告警配置实践，alertmanager 配置告警路由，告警发送邮件钉钉，异常及时通知运维。
 | 原文链接：http://wiki.87s1od.asia/arts/411463.Doc

原标题：golang 系统设计 tcp 三次握手四次挥手梳理
简介：golang nacos go 客户端配置服务发现，nacos‑go 对接 nacos，配置管理、微服务注册发现。
 | 原文链接：http://wiki.87s1od.asia/arts/939285.Doc

原标题：记一次日志切割脚本错误直接清空业务日志
简介：golang go 并发模式 errgroup 使用，errgroup 结合 context，协程组，任意协程出错整体取消任务。
 | 原文链接：http://wiki.87s1od.asia/arts/936887.Doc

原标题：Troubleshooting：依赖安装失败完整排查清单
简介：TCP 心跳检测清理僵死连接，开启 TCP 心跳机制，自动清理僵死无效连接，释放连接资源。
 | 原文链接：http://wiki.87s1od.asia/arts/419249.Doc

原标题：开发复盘：实现定时任务调度服务支持动态任务
简介：golang time 时间格式化避坑，Go 时间格式化参考时间牢记，处理时间解析格式化，解决时间输出错乱。
 | 原文链接：http://wiki.87s1od.asia/arts/990158.Doc

原标题：踩坑：环境变量未生效导致线上配置错乱
简介：golang 异步任务队列 worker 池开发，任务入数据库或 redis，worker 池消费执行，异步处理耗时业务。
 | 原文链接：http://wiki.87s1od.asia/arts/007292.Doc

原标题：golang mongodb 事务多文档使用
简介：golang go 并发模式 errgroup 使用，errgroup 结合 context，协程组，任意协程出错整体取消任务。
 | 原文链接：http://wiki.87s1od.asia/arts/596836.Doc

原标题：排错：静态资源404，打包路径配置错误
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://wiki.87s1od.asia/arts/355697.Doc

原标题：项目实践：消息队列消息堆积模拟处理实践
简介：日志切割配置防止日志丢失，配置日志切割轮转策略，日志按大小时间切割，防止日志文件丢失。
 | 原文链接：http://wiki.87s1od.asia/arts/791331.Doc

原标题：跨平台换行符统一异常修复
简介：golang go 爬虫代理池轮换使用，http 代理池轮换，请求自动切换代理 IP，突破访问限制。
 | 原文链接：http://wiki.87s1od.asia/arts/015317.Doc

原标题：Troubleshoot：DNS解析异常导致第三方调用失败
简介：golang 数据库连接泄露排查，定位 Go 数据库连接泄露，连接没有归还池，导致连接耗尽报错。
 | 原文链接：http://wiki.87s1od.asia/arts/044632.Doc

原标题：golang 单元测试 mock http 请求
简介：golang sync.Map 高并发 map 使用场景，sync.Map 适用场景，读写实操，对比普通 map 加锁性能差异。
 | 原文链接：http://wiki.87s1od.asia/arts/639213.Doc

原标题：golang kafka 死信队列业务落地
简介：前端打包产物体积压缩优化，多手段压缩前端打包产物，移除无用代码，压缩资源，提升页面加载速度。
 | 原文链接：http://wiki.87s1od.asia/arts/991306.Doc

原标题：读懂开源项目 README 实用技巧
简介：异步编程 Promise 执行流程解析，拆解异步执行顺序，理解回调与 Promise 差异，理清异步场景下代码执行逻辑。
 | 原文链接：http://wiki.87s1od.asia/arts/299112.Doc

原标题：Git LFS 大文件推送失败解决
简介：nodejs jwt 登录鉴权完整示例，Node 实现 JWT 登录鉴权，登录签发令牌，接口校验令牌身份。
 | 原文链接：http://wiki.87s1od.asia/arts/116236.Doc

原标题：依赖版本冲突兼容修复方案
简介：Nginx 透传真实客户端 IP 配置，配置 Nginx 把真实客户端 IP 传递后端服务，后端拿到访问者真实 IP。
 | 原文链接：http://wiki.87s1od.asia/arts/821669.Doc

原标题：部署实践：DockerCompose管理多服务环境
简介：golang raw socket 底层网络报文收发，raw socket 收发原始网络报文，做网络抓包数据包处理。
 | 原文链接：http://wiki.87s1od.asia/arts/595065.Doc

原标题：前端下载导出文件功能实现
简介：nestjs 全局返回格式统一处理，Nest 全局拦截器统一包装接口返回数据，对外输出标准化响应格式。
 | 原文链接：http://wiki.87s1od.asia/arts/334469.Doc

原标题：服务启动依赖顺序配置正确
简介：golang bufio 缓冲读写性能优化，bufio 带缓冲读写，减少系统调用，提升文件网络 IO 性能。
 | 原文链接：http://wiki.87s1od.asia/arts/982569.Doc

原标题：golang mysql 存储过程简单使用
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://wiki.87s1od.asia/arts/230302.Doc

原标题：性能笔记：数据库表字段设计影响查询性能
简介：golang rate 令牌桶限流器源码理解，拆解令牌桶限流核心逻辑，理解令牌生成消耗，掌握限流底层原理。
 | 原文链接：http://wiki.87s1od.asia/arts/458339.Doc

原标题：JWT 工具封装令牌刷新过期
简介：nodejs 数据库连接池配置调优，调优 Node 数据库连接池参数，平衡性能与资源占用，避免连接耗尽。
 | 原文链接：http://wiki.87s1od.asia/arts/537760.Doc

四、架构设计｜Architecture
原标题：TLS 版本兼容 HTTPS 握手失败
简介：golang redis bitmap 位图业务实战，bitmap 做签到统计、用户状态标记，节省大量内存空间。
 | 原文链接：http://wiki.87s1od.asia/arts/425190.Doc

原标题：开发复盘：避免大报文导致服务OOM优化实践
简介：语义化版本依赖管理防错乱，项目依赖遵循语义版本约束，规避依赖自动升级引入不兼容变更。
 | 原文链接：http://wiki.87s1od.asia/arts/307213.Doc

原标题：golang 系统设计埋点数据上报方案
简介：golang e2e 端到端测试 go 接口，编写 e2e 测试，完整模拟用户请求，校验整套业务链路正确性。
 | 原文链接：http://wiki.87s1od.asia/arts/181455.Doc

原标题：架构笔记：OAuth2授权服务架构模式拆解
简介：golang gorm ORM 数据库操作，GORM 实操数据库 CRUD，模型定义，关联查询，简化 Go 数据库开发。
 | 原文链接：http://wiki.87s1od.asia/arts/609467.Doc

原标题：golang 系统设计令牌桶漏桶算法对比
简介：golang init 函数合理使用边界，少用 init，优先显式调用初始化，便于控制初始化时机。
 | 原文链接：http://wiki.87s1od.asia/arts/788939.Doc

原标题：架构复盘：跨机房多活架构基础概念与代价
简介：golang 正则表达式 Go 实操案例，正则匹配提取替换，处理手机号邮箱校验，规避正则回溯 CPU 暴涨。
 | 原文链接：http://wiki.87s1od.asia/arts/539994.Doc

原标题：从零学习简单分布式ID生成思路
简介：golang go 死锁检测工具，静态检查、运行检测，发现 channel 锁导致死锁问题。
 | 原文链接：http://wiki.87s1od.asia/arts/263134.Doc

原标题：安全实践：接口速率限制防止暴力破解
简介：项目语义化版本号规范管理，遵循语义化版本规范管理项目版本，明确主次版本变更含义。
 | 原文链接：http://wiki.87s1od.asia/arts/311317.Doc

原标题：golang minio 存储桶权限管控配置
简介：golang go‑zero 框架项目快速搭建，go‑zero 脚手架生成微服务项目，api rpc 服务快速开发。
 | 原文链接：http://wiki.87s1od.asia/arts/975755.Doc

原标题：坑点：环境配置被打包进镜像引发安全泄露
简介：网络读取超时设置连接挂起防护，设置网络读取超时时间，防止请求无限挂起不返回，占用连接资源。
 | 原文链接：http://wiki.87s1od.asia/arts/998777.Doc

原标题：golang docker compose 部署 minio
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://wiki.87s1od.asia/arts/922935.Doc

原标题：从零搭建简单CLI命令行工具
简介：golang go 逃逸分析实操查看，go build‑gcflags=-m 查看逃逸分析，减少堆分配优化程序性能。
 | 原文链接：http://wiki.87s1od.asia/arts/611139.Doc

原标题：Hands‑on：简易配置中心本地原型实现
简介：golang smtp 邮件发送完整示例，调用 smtp 服务发送文本与 html 格式邮件，实现邮件通知能力。
 | 原文链接：http://wiki.87s1od.asia/arts/859476.Doc

原标题：安全笔记：Cookie安全属性SecureHttpOnly
简介：极简方式搭建个人技术文档站点，使用轻量化工具快速部署文档站点，支持 markdown 编写，实现知识沉淀与对外分享。
 | 原文链接：http://wiki.87s1od.asia/arts/569317.Doc

原标题：Hands‑on：简易配置热更新组件开发实践
简介：golang jwt 鉴权中间件完整示例，Gin JWT 鉴权中间件，令牌校验，解析用户信息，接口鉴权拦截。
 | 原文链接：http://wiki.87s1od.asia/arts/407296.Doc

原标题：效率笔记：gitlog高效查询历史提交技巧
简介：golang go 模板执行错误捕获，捕获模板执行错误，防止模板错误直接返回空白页面。
 | 原文链接：http://wiki.87s1od.asia/arts/595177.Doc

原标题：golang 系统信号信号量处理
简介：golang 设置 net.Conn 读写超时，每次读写设置超时，防止连接永久阻塞挂起不返回。
 | 原文链接：http://wiki.87s1od.asia/arts/510011.Doc

原标题：踩坑记录：时间戳精度不一致引发判断错误
简介：WebSocket 聊天室实时通讯开发，基于 WebSocket 搭建简易聊天室，实现多人消息广播实时聊天效果。
 | 原文链接：http://wiki.87s1od.asia/arts/537728.Doc

?
