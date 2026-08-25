最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计线上问题复现思路简单讲解
简介：YAML 配置文件语法快速上手，讲解 YAML 基础语法、缩进规则，编写项目配置文件，规避语法错误引发程序异常。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/0811834.sHtML

原标题：CI 持续集成自动构建流程
简介：接口请求重试容错机制实现，封装请求重试逻辑，遇到临时网络故障自动重试，提升第三方调用稳定性。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/9392248.sHtML

原标题：调优方案：静态资源缓存头Cache‑Control优化
简介：服务器 Swap 关闭提升响应速度，关闭服务器 Swap 交换分区，避免内存交换磁盘拖慢程序响应性能。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/5656177.sHtML

原标题：性能复盘：热点key导致RedisCPU飙升优化
简介：golang 配置文件多环境加载，Go 多环境配置加载实现，读取配置文件环境变量，适配多套运行环境。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/0725426.sHtML

原标题：golang consul 健康检查服务注册
简介：golang 系统 IO 阻塞 goroutine 场景，理解系统调用阻塞 M，P 会调度其他 M，掌握 go 调度行为。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/0176898.sHtML

原标题：golang 内存 pprof 定位内存泄漏
简介：请求工具封装统一异常处理，对网络请求做二次封装，统一捕获各类请求异常，标准化接口返回格式。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/1983186.sHtML

原标题：服务器时钟同步任务错乱修复
简介：golang ctx 关闭之后资源释放，context 取消后，监听 Done ()，释放 goroutine 网络 IO 资源。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/3536701.sHtML

原标题：实战：Redis过期回调实现业务事件通知实践
简介：golang go mod vendor 本地依赖导出，导出 vendor 目录，离线环境编译项目，无需访问外网拉依赖。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/2723504.sHtML

原标题：架构笔记：WebSocket大规模连接服务架构
简介：golang go 二进制安全 strip 减小体积，strip 剥离二进制调试符号，缩小程序二进制文件体积。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/1201493.sHtML

原标题：golang 系统设计本地缓存过期淘汰策略选型
简介：Git 误删提交代码恢复找回，使用 Git reflog 工具找回被误删除提交记录，恢复误删除代码。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/4929613.sHtML

原标题：方案设计：多租户系统架构三种实现模式对比
简介：golang context 取消传播机制，父 ctx 取消，所有派生子 context 全部被取消，理解上下文传播。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/1250351.sHtML

原标题：踩坑记录：乐观锁版本号处理不当更新失败
简介：golang trace 链路追踪 opentelemetry，opentelemetry 实现链路追踪，生成 traceId spanId，完整记录调用链路。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/0520615.sHtML

原标题：Hands‑on：简易代理服务器开发实践
简介：golang gorm 事务手动回滚提交，手动控制事务流程，业务异常主动回滚，保障数据操作原子性。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/9910721.sHtML

原标题：开发记录：文件锁实现多进程互斥实践
简介：重复提交幂等防护再次讲解，梳理前端重复点击、网络重试场景，落地接口幂等，杜绝重复业务。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/8571479.sHtML

原标题：Docker 容器入门镜像实操教程
简介：golang jwt 令牌刷新逻辑实现，实现 JWT 双令牌机制，access 短期有效 refresh 刷新令牌，实现无感续期登录。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/2621492.sHtML

原标题：golang 系统设计索引设计通用方法论汇总
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/5620946.sHtML

原标题：批量异步处理系统业务落地
简介：缓存过期策略优化防业务故障，合理设置缓存过期策略，规避集中过期，减少缓存失效带来业务抖动。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/7112991.sHtML

原标题：golang 系统设计短信发送限流降级
简介：golang bufio.Scanner 按行读取大文件，Scanner 逐行读取文本文件，处理超大日志 csv。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/7570262.sHtML

原标题：css 动画性能优化 GPU 加速
简介：包管理器依赖缓存清理，清理本地依赖缓存，解决缓存旧包引发问题，拉取最新版本依赖包。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/5675701.sHtML

原标题：零基础理解会话、Cookie、Session基础
简介：浏览器缓存强制刷新方案，设置 HTTP 缓存头，处理浏览器缓存旧静态资源，让用户加载更新后的页面。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/4232498.sHtML

原标题：实战项目：本地搭建Prometheus监控完整demo
简介：golang os 文件权限 mode，os.FileMode 文件权限，读写执行权限位，跨平台权限注意事项。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/1155036.sHtML

原标题：踩坑：分布式事务状态不一致数据两边不一致
简介：Git commit 钩子提交规范校验，配置 Git 提交钩子，提交代码自动校验提交信息格式，规范提交记录。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/9037878.sHtML

原标题：坑点：gitreset误删本地代码恢复方案
简介：golang go proxy 私有代理配置，配置 go proxy 私有代理，加速依赖下载，内网环境构建项目。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/7369640.sHtML

原标题：服务健康检查告警监控体系
简介：程序日志分级输出规范实践，区分日志等级，规范日志打印内容，合理输出日志，方便线上问题排查定位。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/6171797.sHtML

原标题：入门实践：项目配置文件多环境管理方案
简介：项目目录结构规范化最佳实践，梳理源码、配置、静态资源目录划分，规范项目布局，提升代码可读性和可维护性。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/3831277.sHtML

原标题：开发记录：JWT过期刷新滑动过期实现实践
简介：开源项目构建失败排查步骤，梳理构建报错排查流程，从依赖、网络、权限、脚本多角度定位项目构建失败原因。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/8641279.sHtML

原标题：浏览器缓存强制刷新方案
简介：golang gin 获取客户端真实 IP，多层代理场景正确拿到用户真实访问 IP，避免拿到网关代理内网地址。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/6608435.sHtML

原标题：Practice：模拟缓存雪崩缓存击穿验证防护策略
简介：golang 压缩 zip 文件生成解压，golang 实现 zip 压缩打包，解压 zip 归档文件，处理批量文件归档。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/0403155.sHtML

原标题：Hands‑on：简易消息推送服务开发实践
简介：golang k8s secret 敏感配置加载，加载 k8s secret 存储密钥密码，敏感信息不存放配置文件。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/3038563.sHtML

原标题：nodejs 多进程任务分发处理
简介：golang CPU 绑定亲和性设置 go 程序，设置进程 CPU 亲和绑定核心，减少 CPU 调度开销，提升计算性能。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/9798656.sHtML

原标题：多环境配置中心灵活切换方案
简介：golang 制品镜像版本号规范管理，镜像版本号结合 git commit，明确每个镜像对应代码版本便于追溯。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/7197303.sHtML

原标题：API 接口调试与异常处理实战
简介：安全组端口开放网络访问，调整服务器安全组规则，开放业务需要端口，恢复外部网络访问服务。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/3829094.sHtML

原标题：布隆过滤器数据高效去重实现
简介：程序信号中断退出处理逻辑，捕获系统中断信号，执行资源释放、关闭连接，实现程序优雅退出。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/6792205.sHtML

原标题：数值 key 浮点匹配异常规避
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/5457161.sHtML

原标题：架构笔记：分库分表中间件选型业务约束
简介：前端权限路由动态生成实现，根据后端返回权限，动态生成前端路由菜单，实现页面权限控制。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/5027530.sHtML

原标题：网关超时时间调优后端等待
简介：golang nacos go 客户端配置服务发现，nacos‑go 对接 nacos，配置管理、微服务注册发现。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/4118301.sHtML

原标题：golang mysql 悲观锁乐观锁实现
简介：主干开发团队代码合并策略，讲解主干开发模式，团队代码合并流程，适合高频迭代的团队协作模式。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/2145969.sHtML

原标题：零基础理解模块化与组件化基础思想
简介：golang http 服务优雅关闭完整示例，接收终止信号，停止接收新请求，等待现有请求处理完毕后退出服务。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/4350245.sHtML

原标题：golang 系统设计故障演练简单落地思路方法论
简介：golang proto 可选字段处理方案，protobuf 可选字段正确判断，区分未赋值与零值，业务逻辑不出现偏差。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/5089418.sHtML

原标题：golang yaml 解析配置加载实操
简介：golang base64 编码解码实操，Go Base64 编码解码示例，处理业务场景 Base64 格式数据转换。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/5084508.sHtML


二、踩坑排错｜Troubleshooting
原标题：配置外部化线上部署防错误
简介：nodejs 集成测试业务流程编写，编写 Node 集成测试，调用真实接口，验证完整业务链路执行结果。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/6661945.sHtML

原标题：golang 系统设计容器健康检查设计思路
简介：golang strings.Builder 字符串高效拼接，strings.Builder 做字符串拼接，比 += 性能更高，减少内存拷贝。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/5847474.sHtML

原标题：golang 系统设计 protobuf 命名规范最佳实践
简介：golang go 并发模式 fan‑out fan‑in，fanout 分发任务 fanin 汇总结果，多协程并发处理任务。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/4241892.sHtML

原标题：部署复盘：GitHubActions完整自动化配置
简介：golang systemd 信号与优雅退出配合，systemd 停止服务发送 SIGTERM，go 程序捕获信号优雅关闭。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/3477151.sHtML

原标题：效率笔记：Makefile项目构建脚本编写实践
简介：Git 误提交撤销回退实操教程，演示多种撤销提交方式，区分已经推送远程和本地未提交场景，处理误提交代码。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/2068928.sHtML

原标题：系统时间同步定时任务偏移
简介：K8s 镜像拉取网络故障修复，排查 K8s 集群镜像拉取网络问题，配置镜像源，恢复镜像正常拉取。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/3846762.sHtML

原标题：容器资源限制防止宿主机过载
简介：golang 高并发下锁优化减少竞争，减小锁粒度，读写锁替换互斥锁，无锁编程降低锁竞争开销。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/6276139.sHtML

原标题：极简方式搭建个人技术文档站点
简介：golang sqlx 原生 SQL 代码简化，sqlx 简化原生 SQL 结果映射结构体，兼顾性能与开发效率。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/6477931.sHtML

原标题：快速上手阅读开源项目源码的入门思路
简介：CDN 缓存刷新获取最新静态资源，调用 CDN 刷新接口，清除节点旧缓存，用户访问到更新后的静态文件。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/0439189.sHtML

原标题：golang 系统设计大表结构变更不停机方案
简介：golang 响应 body 流式返回大数据，http 流式输出数据，边生成边返回，无需在内存组装完整返回结果。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/2932308.sHtML

原标题：5分钟快速搭建个人技术文档站点
简介：golang sync.RWMutex 读写锁使用场景，读多写少场景读写锁，读共享写互斥，提升并发性能。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/8377706.sHtML

原标题：避坑：正则回溯引发CPU占满DoS风险
简介：nodejs 中间件模式原理剖析，拆解 Node 中间件设计模式，理解请求逐层处理流转的底层原理。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/4987085.sHtML

原标题：部署实践：服务器防火墙安全组配置实践
简介：golang 制品镜像版本号规范管理，镜像版本号结合 git commit，明确每个镜像对应代码版本便于追溯。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/0284541.sHtML

原标题：golang ci 流水线漏洞扫描依赖检查
简介：手写简易 ORM 理解对象映射，手写极简 ORM 示例，理解对象与数据库表字段映射底层原理。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/0121235.sHtML

原标题：golang k8s ingress‑nginx 配置 ssl 证书
简介：golang sql 注入风险规避要点，参数化查询杜绝 sql 注入，禁止字符串拼接 SQL 语句执行。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/5630356.sHtML

原标题：架构复盘：消息队列在业务系统中边界与最佳实践
简介：golang 模糊测试 go fuzz 基础编写，Fuzz 测试函数，自动生成随机输入，发现代码崩溃 panic。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/9240424.sHtML

原标题：开发生产环境资源路径统一
简介：异步编程 Promise 执行流程解析，拆解异步执行顺序，理解回调与 Promise 差异，理清异步场景下代码执行逻辑。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/7812682.sHtML

原标题：零基础理解缓存基础原理与简单使用
简介：本地简易配置中心动态管理，搭建轻量本地配置中心，业务动态读取配置，修改配置不重启服务。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/3723184.sHtML

原标题：golang 系统设计分布式任务调度
简介：golang context 取消传播机制，父 ctx 取消，所有派生子 context 全部被取消，理解上下文传播。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/7524977.sHtML

原标题：开发复盘：长轮询接口实现服务端消息推送
简介：golang csv 百万级数据导入数据库，流式读取 csv 分批写入数据库，避免一次性加载全部数据。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/7671407.sHtML

原标题：调优方案：消息批量消费提升MQ处理吞吐量
简介：前端打包分包加载提速方案，前端打包做代码分包，拆分大 bundle，页面按需加载，提升首屏加载速度。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/5938681.sHtML

原标题：golang 系统设计契约测试接口兼容性保障思路
简介：golang go math 大数高精度计算，math/big 处理超大整数、高精度浮点数，金额大数运算。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/3795525.sHtML

原标题：golang prometheus counter gauge 使用
简介：golang gif 图片帧处理操作，解析 gif 图片帧，压缩、拆分 gif 动图，处理动图业务。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/6772329.sHtML

原标题：nodejs 进程间通信 IPC 实操
简介：移动端适配 rem vw 方案对比，对比 rem 与 vw 移动端适配方案，分析优缺点，给出选型建议。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/3444713.sHtML

原标题：golang grafana 监控面板简单配置
简介：服务器 Swap 关闭提升响应速度，关闭服务器 Swap 交换分区，避免内存交换磁盘拖慢程序响应性能。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/7316525.sHtML

原标题：架构笔记：WebSocket大规模连接服务架构
简介：golang channel 关闭规则与坑点，关闭已经关闭 channel 会 panic，判断 channel 是否关闭正确写法。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/6189726.sHtML

原标题：golang 系统设计监控告警体系搭建思路
简介：golang 多协程任务池并发控制，实现协程任务池，控制并发协程数量，防止无限制创建 goroutine。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/6572673.sHtML

原标题：golang 系统设计缓存 key 淘汰雪崩防护思路
简介：golang viper 多源配置管理实操，viper 读取配置文件环境变量命令行参数，多源配置优先级管理。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/0157726.sHtML

原标题：实战：接口压力测试实操，定位系统瓶颈
简介：golang go 优雅处理信号丢失场景，处理信号丢失、信号被忽略，保障程序可以正常接收终止信号。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/8257030.sHtML

原标题：golang 系统设计时间字段选型 datetime timestamp
简介：golang go http 文件服务器自定义，http.FileServer 自定义 FileSystem，拦截访问，增加鉴权逻辑。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/4577300.sHtML

原标题：安全笔记：CSP内容安全策略配置实践
简介：golang go 错误包装 fmt.Errorf % w，使用 % w 包装错误，支持 errors.Is errors.As 判断错误类型。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/1872728.sHtML

原标题：运维笔记：服务器Swap分区调优生产实践
简介：CORS 跨域问题多种解决方案，对比 CORS、代理等不同跨域方案优缺点，根据业务场景选择合适的跨域处理方式。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/2601737.sHtML

原标题：项目实践：Docker镜像安全扫描本地实操
简介：vite 项目配置与构建提速技巧，讲解 vite 配置优化手段，提升开发热更新速度与生产构建打包效率。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/9589495.sHtML

原标题：golang mysql 事务回滚异常处理
简介：golang 雪花算法 workId 自动获取，自动获取机器 workId，不用手动配置，简化分布式 id 部署。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/8232799.sHtML

原标题：CI 流水线构建失败日志排查
简介：golang go 容器 heap 堆实现优先队列，实现 heap 接口，构建优先队列，任务优先级调度。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/7843359.sHtML

原标题：Hands‑on：简易反向代理中间件实现
简介：eslint prettier 代码规范落地，配置 eslint 与 prettier，做代码检查格式化，统一前端团队代码风格。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/0441156.sHtML

原标题：实践：前后端时间格式统一规范落地实践
简介：Docker 容器网络不通排查，排查容器网络模式、端口映射、防火墙，解决容器之间、容器外部网络不通。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/5427360.sHtML

原标题：数据库分表存储大表优化方案
简介：golang 信号触发配置重载实践，收到 SIGUSR1 信号重新加载配置，线上无需重启刷新配置。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/8647396.sHtML

原标题：运维笔记：备份策略数据库定时备份脚本
简介：nestjs 拦截器过滤器管道实战，实操 Nest 拦截器、异常过滤器、管道校验，处理请求与响应统一逻辑。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/3470509.sHtML

原标题：golang mysql 避免 select * 查询
简介：golang go‑zero api 接口开发与路由，go‑zero 编写 api 定义文件，生成代码开发 http 接口。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/1121796.sHtML

三、实战开发｜Practice
原标题：nodejs 读取大文件 csv 处理方案
简介：golang go regexp 正则预编译，regexp.MustCompile 预编译正则，不要循环内部编译正则，节省 CPU。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/0541884.sHtML

原标题：安全复盘：业务数据脱敏防止泄露实践
简介：golang 限流器熔断降级组合使用，限流熔断降级组合架构，流量防护完整方案，保障服务稳定性。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/7790512.sHtML

原标题：DNS TTL 配置域名切换生效
简介：超大数据集分页性能优化方案，对比不同分页方案，针对海量数据集做分页性能优化，解决越翻越慢。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/4563724.sHtML

原标题：快速入门简单签名校验实现思路
简介：数据库死锁成因规避方案，讲解数据库死锁产生条件，给出业务层面规避手段，减少死锁事件发生。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/0208733.sHtML

原标题：golang 系统设计线上故障排查完整流程
简介：开源项目构建失败排查步骤，梳理构建报错排查流程，从依赖、网络、权限、脚本多角度定位项目构建失败原因。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/0487633.sHtML

原标题：架构笔记：冷热数据分离架构设计与迁移
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/6842254.sHtML

原标题：实战项目：GitHubAction自动测试构建实践
简介：golang grpc 客户端流上传数据，客户端流式请求，客户端分批上传数据到服务端，适合大文件传输。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/8893134.sHtML

原标题：实践：数据库回滚点业务调试实践
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/1342803.sHtML

原标题：架构复盘：服务优雅停机架构设计资源释放
简介：定时任务周期调度 demo 开发，实现简单定时调度程序，按时间周期执行业务逻辑，理解定时任务运行机制。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/5794919.sHtML

原标题：Architecture：事件溯源架构模式适用业务场景
简介：移动端适配 rem vw 方案对比，对比 rem 与 vw 移动端适配方案，分析优缺点，给出选型建议。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/0840379.sHtML

原标题：Redis 热点 key 拆分降低集群压力
简介：golang redis 事务 multi exec 使用，Redis 事务 multi exec 实现批量命令原子执行，理解 redis 事务隔离特性。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/5852305.sHtML

原标题：前端权限路由动态生成实现
简介：golang mock 单元测试编写技巧，单元测试 mock 外部依赖，隔离数据库网络，只测试业务逻辑本身。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/5317599.sHtML

原标题：实践：API版本控制多种策略落地对比实践
简介：golang 服务注册 etcd 简单示例，etcd 实现服务注册发现，微服务实例注册元数据，客户端发现节点。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/8624955.sHtML

原标题：调优方案：MySQL缓冲池参数性能调优实践
简介：gRPC 服务端客户端入门示例，搭建 gRPC 服务端与调用客户端，学习 protobuf 定义，掌握 RPC 基础开发流程。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/6178622.sHtML

原标题：golang redis pipeline 批量操作
简介：WSL 搭建 Windows Linux 开发环境，配置 WSL 环境，在 Windows 系统使用 Linux 工具链，适配 Linux 开发项目。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/0251389.sHtML

原标题：RPC 报文大小上限调优大请求
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/8064545.sHtML

原标题：接口幂等性防重复请求实现
简介：golang 内存 pprof 定位内存泄漏，pprof 分析内存快照，定位内存泄露对象，解决 Go 程序内存持续上涨。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/7516916.sHtML

原标题：Debug：长连接未设置心跳，连接僵死不回收
简介：开发生产环境资源路径统一，对齐开发环境与生产环境资源路径，防止本地正常上线后资源找不到。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/5121252.sHtML

原标题：vue3 组合式 API 业务开发实战
简介：正则表达式文本处理实战案例，结合业务场景演示正则匹配、提取、替换，处理手机号、邮箱等各类文本校验需求。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/2482092.sHtML

原标题：golang 系统设计 saga 事务补偿模式实现思路
简介：golang io.Reader io.Writer 接口理解，io 读写接口，各类数据源统一抽象，适配 io 复制函数。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/1474576.sHtML

原标题：golang 项目 makefile 脚本编写
简介：golang go 服务压测前后性能对比，压测记录 QPS 延迟，优化前后对比，验证优化效果。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/5061887.sHtML

原标题：Issue：日志输出包含敏感信息造成泄露风险
简介：golang alertmanager 告警配置实践，alertmanager 配置告警路由，告警发送邮件钉钉，异常及时通知运维。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/3171425.sHtML

原标题：CDN 缓存刷新获取最新静态资源
简介：golang 静态编译缩小镜像体积，Go 程序静态编译，不依赖系统库，产出单二进制文件，缩小镜像。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/0387679.sHtML

原标题：设计思考：系统限流熔断降级完整防护体系
简介：特殊输入字符过滤解析防护，过滤用户输入特殊字符，防止解析报错，规避恶意字符带来业务异常。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/5466266.sHtML

原标题：golang 日志脱敏敏感字段过滤
简介：golang kafka 消费者组重平衡避坑，规避消费者组频繁 rebalance，减少消费抖动，保障消息消费稳定性。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/1858962.sHtML

原标题：开发复盘：内存缓存LRU淘汰策略实现实践
简介：golang 时间时区处理避坑指南，Go 时间时区常见坑，时区转换，时间比较，规避时间逻辑错误。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/9702461.sHtML

原标题：架构思考：单体应用向微服务拆分演进路径
简介：golang rabbitmq 死信队列延迟消息，rabbitmq 实现死信、延迟消息，处理延时业务场景。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/4526856.sHtML

原标题：golang 系统设计配置敏感信息加密存储方案
简介：golang 灰度发布流量权重路由实现，根据权重切分流量，部分流量访问新版本服务，实现灰度发布。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/7672548.sHtML

原标题：golang ci 流水线代码质量扫描集成
简介：golang 配置文件多环境加载，Go 多环境配置加载实现，读取配置文件环境变量，适配多套运行环境。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/3615065.sHtML

原标题：golang 系统设计回调签名校验防伪造实现
简介：golang 云存储 s3 协议对象存储，go s3 客户端，兼容 minio 阿里云 oss，实现文件上传下载签名访问。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/3309086.sHtML

原标题：golang 系统设计开源项目依赖版本升级维护
简介：golang nacos go 客户端配置服务发现，nacos‑go 对接 nacos，配置管理、微服务注册发现。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/5810131.sHtML

原标题：Troubleshooting：依赖安装失败完整排查清单
简介：golang json number 数字不转 float64，使用 json.Number 保留原始数字字符串，防止大数字精度丢失。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/6537365.sHtML

原标题：golang 系统设计本地缓存与分布式缓存
简介：异步任务堆积消费能力优化，处理消息任务堆积问题，提升消费处理速度，恢复队列正常处理水位。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/9042775.sHtML

原标题：内网 DNS 不稳定随机报错排查
简介：网络读取超时设置连接挂起防护，设置网络读取超时时间，防止请求无限挂起不返回，占用连接资源。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/2848961.sHtML

原标题：实战项目：CLI批量文件处理工具开发全过程
简介：golang atomic 原子操作整数，atomic 加减比较交换，无锁更新整型变量，简单计数器场景。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/8092700.sHtML

原标题：golang 系统设计代码安全审计简单思路
简介：git stash 代码暂存切换分支，使用 stash 暂存未提交代码，切换其他分支处理紧急任务，再恢复原有工作进度。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/7033001.sHtML

原标题：golang 系统设计 cpu 高占用排查步骤
简介：golang grpc 重试机制客户端配置，grpc 客户端配置重试策略，临时故障自动重试，提升调用稳定性。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/7655257.sHtML

原标题：架构笔记：数据库连接池架构参数调优思路
简介：golang http body 必须关闭的重要性，无论成功失败必须关闭 request.Body，否则连接无法复用泄漏。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/6528234.sHtML

原标题：golang net/http 超时全套配置
简介：golang grpc 客户端流上传数据，客户端流式请求，客户端分批上传数据到服务端，适合大文件传输。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/3644959.sHtML

原标题：golang websocket 消息广播实现
简介：消息消费重试次数限制防爆炸，限制消息最大重试次数，防止失败消息无限重试造成消息爆炸堆积。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/7296216.sHtML

四、架构设计｜Architecture
原标题：排错：静态资源404，打包路径配置错误
简介：golang gorm 原生 SQL 执行处理，复杂场景执行原生 SQL，处理返回结果集，兼顾性能与灵活性。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/7238136.sHtML

原标题：从零搭建本地开发环境完整教程
简介：golang 数据库 ORM 框架选型对比，gorm xorm sqlx 对比各 ORM 优缺点，根据业务场景选型。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/4437707.sHtML

原标题：消息消费重试次数限制防爆炸
简介：vite 项目配置与构建提速技巧，讲解 vite 配置优化手段，提升开发热更新速度与生产构建打包效率。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/6628549.sHtML

原标题：零基础理解跨域问题产生原因与基础方案
简介：Redis 内存淘汰策略数据防丢失，合理配置 Redis 内存淘汰策略，防止内存满后误删除业务重要数据。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/7674557.sHtML

原标题：坑点：npm/pip全局版本与项目本地版本冲突
简介：golang go 符号表与调试信息取舍，区分生产环境调试符号取舍，平衡镜像体积与故障排查能力。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/4175291.sHtML

原标题：golang 系统设计创建更新时间自动维护方案
简介：golang go time 时区数据库内置，go 内置时区数据库，不用系统时区文件，容器时区不依赖系统。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/7421091.sHtML

原标题：Hands‑on：简易短消息模板渲染组件实践
简介：golang rsa 非对称加密签名验签，RSA 非对称加密与签名验签，实现非对称安全通信。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/4714725.sHtML

原标题：golang websocket 消息广播实现
简介：业务错误码完整落地实践，落地完整业务错误码，枚举全部业务异常，统一返回，配套文档说明。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/8630209.sHtML

原标题：Practice：从零实现轻量后端接口服务完整实践
简介：golang docker compose 开发环境 go 服务，docker compose 编排 go 服务与中间件，本地一键拉起整套开发环境。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/6780273.sHtML

原标题：golang 内存缓存简单实现方案
简介：vue pinia 状态管理实战教程，Pinia 完整实战示例，实现状态定义修改，模块拆分替代 Vuex。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/3537364.sHtML

原标题：golang 分布式 ID 雪花算法实现
简介：golang 压缩 zip 文件生成解压，golang 实现 zip 压缩打包，解压 zip 归档文件，处理批量文件归档。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/0089499.sHtML

原标题：服务熔断防止故障级联传播
简介：ORM 隐式慢查询问题规避，识别 ORM 框架隐式查询，避免循环查询数据库，减少不必要慢 SQL 产生。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/4930625.sHtML

原标题：nodejs 流处理大文件不占内存
简介：Docker 容器网络不通排查，排查容器网络模式、端口映射、防火墙，解决容器之间、容器外部网络不通。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/3903769.sHtML

原标题：接口幂等性防重复请求实现
简介：定时任务周期调度 demo 开发，实现简单定时调度程序，按时间周期执行业务逻辑，理解定时任务运行机制。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/2687925.sHtML

原标题：安全实践：生产环境禁止开启debug调试模式
简介：golang kitex 中间件与元数据传递，kitex 自定义中间件，透传 traceId 鉴权元数据，统一处理请求。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/6350617.sHtML

原标题：性能笔记：服务CPU高负载定位分析完整步骤
简介：不必要字符转义关闭业务异常，关闭多余自动转义逻辑，防止业务数据被错误转义，破坏原始数据。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/9817444.sHtML

原标题：golang es bool 查询条件组合技巧
简介：Git 代码冲突正确处理方式，讲解冲突产生场景，演示冲突文件修改，正确合并代码，防止代码丢失。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/0598360.sHtML

原标题：部署复盘：服务启动顺序依赖处理方案
简介：golang go http 静态文件禁止目录遍历，http.FileServer 防止../ 路径穿越，了解底层安全实现。
 | 原文链接：http://zhishi.4ix9yz.asia/blog/1426987.sHtML

?
