最新前沿技术资讯

一、入门教程｜Getting Started
原标题：项目实践：OpenTelemetry链路追踪本地部署实践
简介：GET POST 接口请求参数处理，讲解两种请求方式参数传递区别，演示参数接收、解析、校验，适配不同接口调用场景。
 | 原文链接：http://wiki.y3mtsi.asia/arts/28391880.html

原标题：实战：Redis集群本地搭建与功能验证
简介：golang hystrix 模式简易熔断实现，简易熔断组件，错误率达到阈值触发熔断，快速失败保护下游。
 | 原文链接：http://wiki.y3mtsi.asia/arts/04451204.html

原标题：踩坑：数据库连接未关闭，连接池泄露
简介：golang k8s secret 敏感配置加载，加载 k8s secret 存储密钥密码，敏感信息不存放配置文件。
 | 原文链接：http://wiki.y3mtsi.asia/arts/52777878.html

原标题：架构复盘：消息队列在业务系统中边界与最佳实践
简介：WebSocket 断线重连稳定优化，增加 WebSocket 断线自动重连逻辑，处理网络抖动，维持长连接稳定。
 | 原文链接：http://wiki.y3mtsi.asia/arts/74631123.html

原标题：golang 分库分表简单路由实现
简介：静态资源 404 路径打包修复，修复打包后静态资源访问 404，调整资源输出路径，保证资源正常加载。
 | 原文链接：http://wiki.y3mtsi.asia/arts/82851257.html

原标题：踩坑记录：时间戳精度不一致引发判断错误
简介：RPC 接口字段增减兼容处理，RPC 接口新增删除字段做好向前兼容，老版本服务不会解析报错崩溃。
 | 原文链接：http://wiki.y3mtsi.asia/arts/71935925.html

原标题：零基础理解内存溢出基础现象与表现
简介：golang sync.Pool 对象池复用对象，sync.Pool 复用临时对象，减少内存分配，降低 GC 频率提升性能。
 | 原文链接：http://wiki.y3mtsi.asia/arts/52858991.html

原标题：golang 系统设计接口超时设计原则梳理
简介：golang oss 签名 URL 临时访问，生成 oss 临时签名 url，限时访问私有文件，保障文件访问安全可控。
 | 原文链接：http://wiki.y3mtsi.asia/arts/40969901.html

原标题：CI 持续集成自动构建流程
简介：golang 分布式唯一 id 多种方案对比，雪花、redis、uuid 对比各方案优缺点，指导业务选型使用。
 | 原文链接：http://wiki.y3mtsi.asia/arts/56780746.html

原标题：HelloEnv：多操作系统环境变量配置汇总
简介：golang base64 编码解码实操，Go Base64 编码解码示例，处理业务场景 Base64 格式数据转换。
 | 原文链接：http://wiki.y3mtsi.asia/arts/45300316.html

原标题：golang 系统设计网络超时故障排查思路
简介：任务执行锁防止并发重复调度，增加任务执行锁，多实例环境，防止同一个定时任务并发多次运行。
 | 原文链接：http://wiki.y3mtsi.asia/arts/41926221.html

原标题：golang 系统设计分库分表中间件思路
简介：golang 容器健康检查接口开发，Go 开发 HTTP 健康接口，供容器编排工具探测实例存活状态。
 | 原文链接：http://wiki.y3mtsi.asia/arts/15754016.html

原标题：Issue：WSL2内存持续暴涨不自动释放
简介：golang 信号捕获程序退出处理，Go 捕获操作系统信号，做资源回收，控制程序退出流程。
 | 原文链接：http://wiki.y3mtsi.asia/arts/42314531.html

原标题：golang 系统设计消息队列解耦削峰
简介：golang 制品镜像版本号规范管理，镜像版本号结合 git commit，明确每个镜像对应代码版本便于追溯。
 | 原文链接：http://wiki.y3mtsi.asia/arts/31673754.html

原标题：Architecture：对象存储接入业务整体架构
简介：golang grpc 负载均衡客户端实现，grpc 客户端负载均衡，轮询随机权重，分发请求到多个服务实例。
 | 原文链接：http://wiki.y3mtsi.asia/arts/81418824.html

原标题：避坑：Nginx配置错误导致请求丢失Header
简介：golang kafka 同步异步消费对比，对比 Kafka 同步消费异步消费，分析优缺点，业务选型参考。
 | 原文链接：http://wiki.y3mtsi.asia/arts/48340089.html

原标题：DevOps：Docker镜像优化，减小镜像体积实践
简介：golang http MaxHeaderBytes 限制请求头，设置 http 最大请求头大小，防止超大 header 攻击。
 | 原文链接：http://wiki.y3mtsi.asia/arts/11909557.html

原标题：golang prometheus 指标暴露实现
简介：限流规则误拦截正常请求修复，修正限流规则阈值，避免合法用户被限流拦截，兼顾防护与可用性。
 | 原文链接：http://wiki.y3mtsi.asia/arts/33521927.html

原标题：golang 系统设计 protobuf 枚举类型规范写法
简介：golang 跨域处理中间件编写，Gin 跨域中间件开发，处理预检 OPTIONS 请求，解决浏览器跨域报错。
 | 原文链接：http://wiki.y3mtsi.asia/arts/04534890.html

原标题：日志切割配置防止日志丢失
简介：TCP 长连接参数优化 TIME_WAIT，调整 TCP 内核参数，优化长连接，减少大量 TIME_WAIT 连接占用资源。
 | 原文链接：http://wiki.y3mtsi.asia/arts/44707883.html

原标题：golang k8s liveness readiness 探针
简介：golang go 第三方库选型评估要点，评估库活跃度维护情况、性能、依赖数量，选择合适开源库。
 | 原文链接：http://wiki.y3mtsi.asia/arts/78340856.html

原标题：性能笔记：DNS缓存优化减少域名解析开销
简介：nodejs 定时任务生产环境避坑，Node 定时任务线上踩坑汇总，集群重复执行、任务阻塞等问题解决方案。
 | 原文链接：http://wiki.y3mtsi.asia/arts/36141493.html

原标题：架构复盘：容器资源隔离架构CPU内存限制设计
简介：golang 响应 body 流式返回大数据，http 流式输出数据，边生成边返回，无需在内存组装完整返回结果。
 | 原文链接：http://wiki.y3mtsi.asia/arts/41222231.html

原标题：实战项目：WebSocket消息广播房间分组实践
简介：golang testify mock 模拟接口，mock 接口生成 mock 对象，单元测试模拟外部依赖行为。
 | 原文链接：http://wiki.y3mtsi.asia/arts/03844740.html

原标题：golang 系统设计 go netpoll 多路复用简单理解
简介：golang sql 注入风险规避要点，参数化查询杜绝 sql 注入，禁止字符串拼接 SQL 语句执行。
 | 原文链接：http://wiki.y3mtsi.asia/arts/36158123.html

原标题：golang 系统设计数据库查询优化完整流程
简介：golang kitex 超时重试熔断配置，kitex 配置调用超时、重试、熔断策略，保障微服务调用稳定性。
 | 原文链接：http://wiki.y3mtsi.asia/arts/67211257.html

原标题：快速上手单元测试，写出第一个测试用例
简介：OpenAPI 自动接口文档生成，集成 OpenAPI 工具，自动扫描代码生成接口文档，减少文档维护成本。
 | 原文链接：http://wiki.y3mtsi.asia/arts/09875636.html

原标题：架构笔记：分布式系统常见一致性模型梳理
简介：磁盘 inode 耗尽文件创建失败，排查磁盘 inode 占用，清理大量小文件，恢复文件创建能力。
 | 原文链接：http://wiki.y3mtsi.asia/arts/60669079.html

原标题：nodejs 信号处理优雅关闭服务
简介：nodejs 单元测试 jest 实操教程，Jest 单元测试实操，编写测试用例，mock 依赖，验证业务逻辑正确性。
 | 原文链接：http://wiki.y3mtsi.asia/arts/70987455.html

原标题：实战项目：搭建本地Mock服务快速开发联调
简介：golang 服务限流熔断降级监控完整实践，微服务防护体系，限流熔断降级指标监控告警整套落地。
 | 原文链接：http://wiki.y3mtsi.asia/arts/82443527.html

原标题：文件编码统一随机乱码修复
简介：WebSocket 聊天室实时通讯开发，基于 WebSocket 搭建简易聊天室，实现多人消息广播实时聊天效果。
 | 原文链接：http://wiki.y3mtsi.asia/arts/18033382.html

原标题：避坑：文件锁处理不当多进程竞争死锁
简介：golang redis 过期时间处理技巧，设置 key 过期，监控过期事件，基于过期特性实现业务缓存逻辑。
 | 原文链接：http://wiki.y3mtsi.asia/arts/73262221.html

原标题：golang 系统设计日志规范结构化日志落地
简介：golang go 程序运行时动态修改配置，运行时热加载配置结构体，原子更新保证并发读取安全。
 | 原文链接：http://wiki.y3mtsi.asia/arts/60209001.html

原标题：Issue：日志疯狂打日志快速占满磁盘空间
简介：golang 内存碎片问题识别与规避，大量小对象频繁分配产生内存碎片，通过对象池减少碎片。
 | 原文链接：http://wiki.y3mtsi.asia/arts/11747861.html

原标题：开发记录：表单参数校验统一中间件实现
简介：golang 系统 IO 阻塞 goroutine 场景，理解系统调用阻塞 M，P 会调度其他 M，掌握 go 调度行为。
 | 原文链接：http://wiki.y3mtsi.asia/arts/74555305.html

原标题：golang prometheus metrics 埋点开发
简介：golang go math 大数高精度计算，math/big 处理超大整数、高精度浮点数，金额大数运算。
 | 原文链接：http://wiki.y3mtsi.asia/arts/11909605.html

原标题：Hands‑on：编写shell健康检查自动重启脚本
简介：golang errgroup 协程组错误处理，errgroup 捕获协程错误，context 取消剩余协程，简化并发任务。
 | 原文链接：http://wiki.y3mtsi.asia/arts/92340816.html

原标题：Hands‑on：简易的事件订阅发布组件开发实践
简介：golang 优雅关闭 grpc 服务示例，gRPC 服务优雅关闭，等待现有请求处理完成再停止服务。
 | 原文链接：http://wiki.y3mtsi.asia/arts/43521205.html

原标题：性能笔记：锁优化减少竞争提升并发吞吐
简介：golang icmp ping 程序实现，go 实现 ping 工具发送 icmp 报文，检测网络连通性。
 | 原文链接：http://wiki.y3mtsi.asia/arts/63552938.html

原标题：安全笔记：CSP内容安全策略配置实践
简介：容器资源限制防止宿主机过载，设置容器 CPU 内存资源上限，避免单个容器耗尽宿主机全部硬件资源。
 | 原文链接：http://wiki.y3mtsi.asia/arts/85444847.html


二、踩坑排错｜Troubleshooting
原标题：WSL 搭建 Windows Linux 开发环境
简介：golang go list 双向链表使用，container/list 双向链表，频繁增删节点业务场景使用。
 | 原文链接：http://wiki.y3mtsi.asia/arts/11374554.html

原标题：golang 系统设计分布式锁可重入实现思路
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://wiki.y3mtsi.asia/arts/88044457.html

原标题：实战：多版本SDK兼容业务改造实践
简介：golang redis lua 脚本原子操作，使用 Lua 脚本实现原子逻辑，减少网络往返，保障多命令原子执行。
 | 原文链接：http://wiki.y3mtsi.asia/arts/39187853.html

原标题：Hands‑on：简易连接池原型实现理解原理
简介：golang go‑zero 中间件鉴权限流，go‑zero 自定义中间件，实现鉴权、限流、日志打印通用能力。
 | 原文链接：http://wiki.y3mtsi.asia/arts/29854850.html

原标题：golang 系统设计接口幂等架构设计
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://wiki.y3mtsi.asia/arts/52155258.html

原标题：golang redis 持久化 RDB AOF 对比
简介：golang 数据库连接池泄露检测逻辑，监控连接池状态，检测连接长时间未归还，告警连接泄漏问题。
 | 原文链接：http://wiki.y3mtsi.asia/arts/92158635.html

原标题：安全组端口开放网络访问
简介：golang hertz http 框架快速上手，hertz 高性能 http 框架，路由中间件参数校验快速开发接口服务。
 | 原文链接：http://wiki.y3mtsi.asia/arts/63883345.html

原标题：多规则数据脱敏组件开发
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://wiki.y3mtsi.asia/arts/40939348.html

原标题：golang etcd 分布式锁实现原理
简介：golang 分布式锁防死锁实现要点，锁超时、续期、锁持有者校验，避免锁死锁，保障分布式锁可靠性。
 | 原文链接：http://wiki.y3mtsi.asia/arts/29432776.html

原标题：golang proto 默认值坑点梳理
简介：异步异常捕获避免进程崩溃，捕获异步代码内部抛出异常，防止未捕获异常直接导致整个进程退出。
 | 原文链接：http://wiki.y3mtsi.asia/arts/67211934.html

原标题：golang 系统设计缓存优化落地实操指南
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：http://wiki.y3mtsi.asia/arts/94467240.html

原标题：从零搭建简单的健康检查接口示例
简介：接口压测定位系统性能瓶颈，使用压测工具对接口施压，观察指标，定位系统性能瓶颈点。
 | 原文链接：http://wiki.y3mtsi.asia/arts/95336786.html

原标题：golang 系统设计链路查询定位慢请求实操技巧
简介：接口请求重试容错机制实现，封装请求重试逻辑，遇到临时网络故障自动重试，提升第三方调用稳定性。
 | 原文链接：http://wiki.y3mtsi.asia/arts/58071423.html

原标题：JSON XML 数据解析处理示例
简介：golang fuzz corpus 语料库使用，fuzz 语料存储历史输入，回归测试，持续复现曾经触发 bug 输入。
 | 原文链接：http://wiki.y3mtsi.asia/arts/37230416.html

原标题：线上故障：消息队列重复消费业务处理异常
简介：不必要字符转义关闭业务异常，关闭多余自动转义逻辑，防止业务数据被错误转义，破坏原始数据。
 | 原文链接：http://wiki.y3mtsi.asia/arts/26537312.html

原标题：文件批量导入导出功能实现
简介：golang grpc 客户端流上传数据，客户端流式请求，客户端分批上传数据到服务端，适合大文件传输。
 | 原文链接：http://wiki.y3mtsi.asia/arts/29058046.html

原标题：多实例部署 Session 共享方案
简介：分布式任务调度集群原型开发，开发简易分布式调度原型，集群多节点运行，保证任务只执行一次。
 | 原文链接：http://wiki.y3mtsi.asia/arts/68116163.html

原标题：优化实践：Redis性能调优，避免大key热key
简介：golang http client 连接池调优，调优 Go HTTP Client 连接池参数，复用 TCP 连接，减少连接创建开销。
 | 原文链接：http://wiki.y3mtsi.asia/arts/97463207.html

原标题：批量异步处理系统业务落地
简介：进程线程并发基础概念讲解，区分进程与线程，讲解调度逻辑，理解并发执行原理，为高并发业务开发打基础。
 | 原文链接：http://wiki.y3mtsi.asia/arts/93185625.html

原标题：golang 系统设计一致性哈希原理讲解
简介：业务错误码完整落地实践，落地完整业务错误码，枚举全部业务异常，统一返回，配套文档说明。
 | 原文链接：http://wiki.y3mtsi.asia/arts/82841520.html

原标题：golang 系统设计日志级别业务使用原则梳理
简介：golang 文件句柄耗尽排查处理，统计进程打开文件句柄，找到未关闭文件，修复句柄泄漏问题。
 | 原文链接：http://wiki.y3mtsi.asia/arts/63888568.html

原标题：安全复盘：业务登录暴力破解防护完整方案
简介：golang 接口限流中间件开发，Gin 开发限流中间件，接口层实现访问频率限制，防护接口流量。
 | 原文链接：http://wiki.y3mtsi.asia/arts/85603186.html

原标题：内存泄漏定位分析完整流程
简介：golang go 多版本管理 gvm 使用，gvm 管理多个 go sdk 版本，快速切换不同 go 版本做项目开发。
 | 原文链接：http://wiki.y3mtsi.asia/arts/19647110.html

原标题：CORS 跨域问题多种解决方案
简介：消息队列重复消费业务处理，实现消息消费幂等，处理重复投递消息，保证多次消费业务结果一致。
 | 原文链接：http://wiki.y3mtsi.asia/arts/09689778.html

原标题：golang 系统设计日志系统架构思路
简介：DNS TTL 配置域名切换生效，调整 DNS 解析 TTL，缩短缓存时间，域名变更后可以快速全网生效。
 | 原文链接：http://wiki.y3mtsi.asia/arts/95002159.html

原标题：golang 系统设计本地缓存过期淘汰策略选型
简介：golang http 服务优雅关闭完整示例，接收终止信号，停止接收新请求，等待现有请求处理完毕后退出服务。
 | 原文链接：http://wiki.y3mtsi.asia/arts/90948866.html

原标题：开发记录：短信发送服务封装，失败重试策略
简介：golang 模糊测试 go fuzz 基础编写，Fuzz 测试函数，自动生成随机输入，发现代码崩溃 panic。
 | 原文链接：http://wiki.y3mtsi.asia/arts/24388543.html

原标题：Debug：静态资源缓存策略错误，用户看不到更新
简介：前后端会话登录状态持久化，实现登录状态持久存储，重启服务登录状态不丢失，保障会话稳定性。
 | 原文链接：http://wiki.y3mtsi.asia/arts/06114453.html

原标题：开源实践：开源Issue沟通技巧如何有效提Bug
简介：golang redis 过期时间处理技巧，设置 key 过期，监控过期事件，基于过期特性实现业务缓存逻辑。
 | 原文链接：http://wiki.y3mtsi.asia/arts/45711227.html

原标题：缓存基础原理与简单代码实现
简介：极简 API 网关路由转发实现，开发极简网关服务，完成请求路由转发，理解网关基础实现原理。
 | 原文链接：http://wiki.y3mtsi.asia/arts/15070183.html

原标题：WebSocket 聊天室实时通讯开发
简介：前端错误监控上报系统搭建，搭建前端错误监控，捕获页面 JS 错误，上报后端，快速发现线上页面 bug。
 | 原文链接：http://wiki.y3mtsi.asia/arts/92370812.html

原标题：空指针异常判空容错处理
简介：JWT 工具封装令牌刷新过期，封装 JWT 工具类，实现令牌生成、校验、过期刷新整套令牌管理逻辑。
 | 原文链接：http://wiki.y3mtsi.asia/arts/23368404.html

原标题：golang 空接口 interface 使用技巧
简介：golang grpc 客户端流上传数据，客户端流式请求，客户端分批上传数据到服务端，适合大文件传输。
 | 原文链接：http://wiki.y3mtsi.asia/arts/91512985.html

原标题：Hands‑on：简易链路追踪原型开发实践
简介：golang go 程序版本号内置编译注入，编译时注入 git commit 版本号，程序运行输出版本便于排查。
 | 原文链接：http://wiki.y3mtsi.asia/arts/52235609.html

原标题：快速上手简单性能监控指标查看
简介：版本升级服务启动失败处理，版本更新之后服务无法启动，对比新旧版本配置、依赖差异，完成故障修复。
 | 原文链接：http://wiki.y3mtsi.asia/arts/55392201.html

原标题：golang gorm 批量插入性能调优
简介：golang grpc metadata 元数据透传，metadata 传递 traceId、鉴权信息，全链路透传上下文信息。
 | 原文链接：http://wiki.y3mtsi.asia/arts/28033673.html

原标题：golang 系统信号信号量处理
简介：golang redis 事务 multi exec 使用，Redis 事务 multi exec 实现批量命令原子执行，理解 redis 事务隔离特性。
 | 原文链接：http://wiki.y3mtsi.asia/arts/42370149.html

原标题：Practice：实现接口幂等性多种方案对比实践
简介：ORM 隐式慢查询问题规避，识别 ORM 框架隐式查询，避免循环查询数据库，减少不必要慢 SQL 产生。
 | 原文链接：http://wiki.y3mtsi.asia/arts/22425857.html

原标题：golang redis 过期策略内存淘汰
简介：golang 协程泄露问题排查方法，识别 Go 协程泄露现象，分析泄露场景，给出排查定位协程泄露手段。
 | 原文链接：http://wiki.y3mtsi.asia/arts/00563712.html

原标题：golang 系统设计日志脱敏防止信息泄露
简介：手写简易 MQ 理解消息存储消费，手写极简消息队列 Demo，理解消息存储、投递、消费完整流程。
 | 原文链接：http://wiki.y3mtsi.asia/arts/67528590.html

三、实战开发｜Practice
原标题：网络读取超时设置连接挂起防护
简介：golang strings.Builder 字符串高效拼接，strings.Builder 做字符串拼接，比 += 性能更高，减少内存拷贝。
 | 原文链接：http://wiki.y3mtsi.asia/arts/62127162.html

原标题：golang 系统设计联合索引设计避坑要点
简介：nodejs 多进程任务分发处理，多进程拆分处理 CPU 密集任务，主进程分发任务，利用多核提升处理速度。
 | 原文链接：http://wiki.y3mtsi.asia/arts/93054897.html

原标题：golang 系统设计蓝绿发布滚动发布对比
简介：golang grpc 双向流双向通信开发，grpc 双向流，服务端客户端持续互发消息，长连接流式业务场景。
 | 原文链接：http://wiki.y3mtsi.asia/arts/00962049.html

原标题：golang 系统设计消息大小限制业务处理方案
简介：golang grpc 错误状态码标准化，grpc 标准化错误返回，定义业务错误码，客户端解析处理业务异常。
 | 原文链接：http://wiki.y3mtsi.asia/arts/48636812.html

原标题：安全实践：SQL注入产生场景与完整防御手段
简介：golang 工具函数库封装思路，Go 通用工具库封装思路，错误处理、类型转换，业务项目复用工具代码。
 | 原文链接：http://wiki.y3mtsi.asia/arts/85771524.html

原标题：快速入门ORM，实现简单数据库增删改查
简介：golang 数据库慢查询监控实现，Go 封装 SQL 执行监控，记录慢 SQL，上报日志，发现数据库性能问题。
 | 原文链接：http://wiki.y3mtsi.asia/arts/90222633.html

原标题：方案对比：本地缓存vs分布式缓存架构取舍
简介：golang gin 路由分组权限管控，Gin 路由分组，不同分组绑定鉴权中间件，实现接口权限分组管控。
 | 原文链接：http://wiki.y3mtsi.asia/arts/73534812.html

原标题：运维笔记：服务器Swap分区调优生产实践
简介：golang 结构体深浅拷贝区别实操，区分结构体浅拷贝深拷贝，规避指针引用带来数据意外篡改问题。
 | 原文链接：http://wiki.y3mtsi.asia/arts/84004590.html

原标题：golang 系统设计第三方调用超时重试熔断
简介：golang word 文档生成处理 go 方案，go 生成 word 文档报表，填充文本表格，输出 docx 文件。
 | 原文链接：http://wiki.y3mtsi.asia/arts/66518383.html

原标题：golang 接口限流中间件开发
简介：react hooks 常见陷阱避坑指南，梳理 React Hooks 高频踩坑点，依赖数组、闭包陷阱，写出稳定组件。
 | 原文链接：http://wiki.y3mtsi.asia/arts/31206635.html

原标题：前端图片懒加载性能优化
简介：Git 分支管理多人协作实战教程，详解分支创建、合并、冲突处理，适配团队开发场景，规范多人协同代码工作流。
 | 原文链接：http://wiki.y3mtsi.asia/arts/31632968.html

原标题：golang 分库分表简单路由实现
简介：golang redis stream 消息队列实战，redis stream 实现可靠消息队列，消费组、ack 确认，消息不丢失。
 | 原文链接：http://wiki.y3mtsi.asia/arts/63858689.html

原标题：golang 系统设计接口幂等架构设计
简介：golang consul 服务发现简单示例，对接 Consul 实现服务注册发现，微服务实例自动感知。
 | 原文链接：http://wiki.y3mtsi.asia/arts/69632934.html

原标题：golang channel 通道并发处理
简介：golang gorm 批量插入性能调优，GORM 批量插入优化，调整批次大小，提升大量数据插入数据库速度。
 | 原文链接：http://wiki.y3mtsi.asia/arts/03295909.html

原标题：Practice：实现业务id生成不连续有序ID方案
简介：pnpm 包管理工具实战避坑指南，使用 pnpm 管理项目依赖，梳理常见坑点，充分利用 pnpm 优势。
 | 原文链接：http://wiki.y3mtsi.asia/arts/26824215.html

原标题：golang 系统设计日志架构采集存储检索完整链路
简介：CI 流水线构建失败日志排查，阅读 CI 流水线输出日志，定位构建脚本、依赖、环境导致流水线失败问题。
 | 原文链接：http://wiki.y3mtsi.asia/arts/59135994.html

原标题：golang prometheus metrics 埋点开发
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://wiki.y3mtsi.asia/arts/36573750.html

原标题：部署实践：Nginx高可用配置方案实践
简介：golang 项目 makefile 脚本编写，编写 Makefile 脚本，封装编译、测试、构建命令，简化项目操作。
 | 原文链接：http://wiki.y3mtsi.asia/arts/92783016.html

原标题：OpenSource：大型仓库Git历史清理瘦身实操
简介：golang 字符编码转换 go 处理，iconv‑go 做编码转换 gbk utf8 互转，处理老旧系统 gbk 编码数据。
 | 原文链接：http://wiki.y3mtsi.asia/arts/35273048.html

原标题：Performance：避免全表扫描索引失效场景汇总
简介：前端国际化多语言方案落地，搭建前端多语言国际化方案，切换语言，页面文本自动切换对应语种。
 | 原文链接：http://wiki.y3mtsi.asia/arts/27869671.html

原标题：接口幂等性防重复请求实现
简介：golang wasm webassembly go 编译，go 编译为 wasm，浏览器执行 go 代码，拓展 go 运行场景。
 | 原文链接：http://wiki.y3mtsi.asia/arts/33885016.html

原标题：golang redis 缓存雪崩完整处理
简介：内存溢出问题现象识别排查，识别内存溢出现象，梳理排查方向，定位内存持续上涨引发服务崩溃问题。
 | 原文链接：http://wiki.y3mtsi.asia/arts/19495342.html

原标题：golang 系统设计开源项目自动化 ci 配置示例
简介：从零编写简易 CLI 命令行工具，通过实战案例实现基础命令交互，理解命令行程序执行逻辑，产出可运行小工具。
 | 原文链接：http://wiki.y3mtsi.asia/arts/35303746.html

原标题：golang gin 框架接口开发实战
简介：golang 异步任务队列 worker 池开发，任务入数据库或 redis，worker 池消费执行，异步处理耗时业务。
 | 原文链接：http://wiki.y3mtsi.asia/arts/96122961.html

原标题：golang 系统设计监控体系指标分类方法论梳理
简介：golang 结构体零值可用性原则，go 结构体尽量做到零值可用，不用初始化直接使用提升易用性。
 | 原文链接：http://wiki.y3mtsi.asia/arts/29411453.html

原标题：golang 系统设计 go benchmark 性能测试实操
简介：golang http 中间件洋葱模型原理，理解 go http 中间件洋葱模型，请求响应流转顺序，编写自定义中间件。
 | 原文链接：http://wiki.y3mtsi.asia/arts/14641527.html

原标题：golang 系统设计消息队列 topic 设计原则梳理
简介：nodejs 定时任务生产环境避坑，Node 定时任务线上踩坑汇总，集群重复执行、任务阻塞等问题解决方案。
 | 原文链接：http://wiki.y3mtsi.asia/arts/81379605.html

原标题：Practice：实现接口防重提交组件实践
简介：golang trace 链路追踪 opentelemetry，opentelemetry 实现链路追踪，生成 traceId spanId，完整记录调用链路。
 | 原文链接：http://wiki.y3mtsi.asia/arts/63581826.html

原标题：部署实践：容器优雅停机配置处理信号
简介：golang panic 崩溃日志完整收集，捕获所有 panic，打印堆栈，记录日志，方便定位崩溃根源。
 | 原文链接：http://wiki.y3mtsi.asia/arts/69744419.html

原标题：service‑worker 离线缓存实践
简介：golang grpc 服务端流推送数据，服务端流式响应，服务端持续向客户端推送多条响应消息。
 | 原文链接：http://wiki.y3mtsi.asia/arts/07595279.html

原标题：golang 系统设计性能优化通用思路方法论
简介：golang e2e 端到端测试 go 接口，编写 e2e 测试，完整模拟用户请求，校验整套业务链路正确性。
 | 原文链接：http://wiki.y3mtsi.asia/arts/31908154.html

原标题：golang 系统设计重试退避策略业务落地
简介：golang hystrix 模式简易熔断实现，简易熔断组件，错误率达到阈值触发熔断，快速失败保护下游。
 | 原文链接：http://wiki.y3mtsi.asia/arts/45644168.html

原标题：开发复盘：统一错误码体系设计落地实践
简介：golang go 值传递引用传递理解，go 全部为值传递，指针本质拷贝指针值，理清参数传递行为。
 | 原文链接：http://wiki.y3mtsi.asia/arts/25148142.html

原标题：架构笔记：多环境隔离架构开发测试生产隔离
简介：golang net/url 路径拼接处理，url.ParseRequestURI 处理请求 url，正确拼接 url 路径避免拼接错误。
 | 原文链接：http://wiki.y3mtsi.asia/arts/59070413.html

原标题：CORS 跨域问题多种解决方案
简介：golang context.WithCancel 手动取消上下文，WithCancel 生成可取消 ctx，手动调用 cancel 触发取消。
 | 原文链接：http://wiki.y3mtsi.asia/arts/64969779.html

原标题：HelloShell：入门常用shell脚本编写
简介：golang gin 静态资源访问配置，Gin 配置静态资源目录，直接对外提供静态文件访问服务。
 | 原文链接：http://wiki.y3mtsi.asia/arts/22007220.html

原标题：内网 DNS 不稳定随机报错排查
简介：缓存穿透击穿雪崩全套防护，完整梳理缓存三大问题，落地全套防护策略，保障缓存层稳定运行。
 | 原文链接：http://wiki.y3mtsi.asia/arts/89447727.html

原标题：golang 系统设计监控体系指标分类方法论梳理
简介：golang 进程信号捕获 SIGUSR 自定义信号，捕获用户自定义信号，实现线上不重启触发调试、日志切换。
 | 原文链接：http://wiki.y3mtsi.asia/arts/88355228.html

原标题：复盘总结：技术方案文档模板架构设计文档
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://wiki.y3mtsi.asia/arts/52380813.html

原标题：部署实践：Nginx高可用配置方案实践
简介：golang 响应 body 流式返回大数据，http 流式输出数据，边生成边返回，无需在内存组装完整返回结果。
 | 原文链接：http://wiki.y3mtsi.asia/arts/81366086.html

四、架构设计｜Architecture
原标题：golang 系统设计本地缓存 redis 缓存多级组合
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://wiki.y3mtsi.asia/arts/51698884.html

原标题：Practice：批量异步任务处理系统设计实现
简介：golang redis lua 脚本原子操作，使用 Lua 脚本实现原子逻辑，减少网络往返，保障多命令原子执行。
 | 原文链接：http://wiki.y3mtsi.asia/arts/36303550.html

原标题：踩坑：Docker容器内时区不一致引发的时间BUG
简介：文件监控服务自动重启开发，监控项目文件变更，代码修改自动重启服务，提升本地开发调试效率。
 | 原文链接：http://wiki.y3mtsi.asia/arts/15787150.html

原标题：golang 静态文件服务搭建教程
简介：golang http client Transport 参数调优，Transport 最大连接空闲连接，TLS 配置，http 客户端调优。
 | 原文链接：http://wiki.y3mtsi.asia/arts/66775239.html

原标题：golang 系统设计架构图绘制规范简单建议
简介：golang errgroup 协程组错误处理，errgroup 捕获协程错误，context 取消剩余协程，简化并发任务。
 | 原文链接：http://wiki.y3mtsi.asia/arts/84569410.html

原标题：实战：GraphQL服务搭建与CRUD实操
简介：异步异常捕获避免进程崩溃，捕获异步代码内部抛出异常，防止未捕获异常直接导致整个进程退出。
 | 原文链接：http://wiki.y3mtsi.asia/arts/52466379.html

原标题：Practice：实现文件监控自动重启开发服务工具
简介：golang elasticsearch 客户端 golang 实操，es 客户端文档增删改查，条件搜索聚合统计对接搜索引擎。
 | 原文链接：http://wiki.y3mtsi.asia/arts/82677046.html

原标题：golang 系统设计缓存大 key 拆分优化实操
简介：golang make new 关键字使用区别，分清 new 与 make 适用类型，正确初始化切片 map 通道，杜绝 nil 引发 panic。
 | 原文链接：http://wiki.y3mtsi.asia/arts/90990180.html

原标题：golang 系统设计缓存 key 命名规范最佳实践
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://wiki.y3mtsi.asia/arts/30888938.html

原标题：静态网页 HTML CSS 快速入门实战
简介：golang go 网络编程 net 包基础，net 包 tcp udp socket 编程，监听接收连接，读写数据。
 | 原文链接：http://wiki.y3mtsi.asia/arts/63599379.html

原标题：Hands‑on：简易短消息模板渲染组件实践
简介：golang go http 静态文件禁止目录遍历，http.FileServer 防止../ 路径穿越，了解底层安全实现。
 | 原文链接：http://wiki.y3mtsi.asia/arts/92373313.html

原标题：线上异常：接口偶发超时，完整定位过程记录
简介：golang go 值传递引用传递理解，go 全部为值传递，指针本质拷贝指针值，理清参数传递行为。
 | 原文链接：http://wiki.y3mtsi.asia/arts/62117450.html

原标题：golang k8s 滚动更新回滚策略
简介：前端权限路由动态生成实现，根据后端返回权限，动态生成前端路由菜单，实现页面权限控制。
 | 原文链接：http://wiki.y3mtsi.asia/arts/26189938.html

原标题：Security：SSRF服务端请求伪造漏洞防御
简介：golang 信号捕获程序退出处理，Go 捕获操作系统信号，做资源回收，控制程序退出流程。
 | 原文链接：http://wiki.y3mtsi.asia/arts/66158113.html

原标题：架构笔记：分库分表中间件选型业务约束
简介：golang grpc protobuf 开发实操，Go gRPC 开发，编写 Protobuf 定义，服务端客户端完整示例。
 | 原文链接：http://wiki.y3mtsi.asia/arts/01606440.html

原标题：磁盘占满服务不可用清理方案
简介：golang gorm 索引设置与优化技巧，定义数据库索引，理解索引生效条件，避免索引失效慢查询。
 | 原文链接：http://wiki.y3mtsi.asia/arts/55144753.html

原标题：快速上手简单性能监控指标查看
简介：golang http.Server 配置参数详解，ReadTimeout WriteTimeout IdleTimeout，全方位防护慢请求攻击。
 | 原文链接：http://wiki.y3mtsi.asia/arts/88039905.html

原标题：Practice：实现接口幂等性多种方案对比实践
简介：手写简易 ORM 理解对象映射，手写极简 ORM 示例，理解对象与数据库表字段映射底层原理。
 | 原文链接：http://wiki.y3mtsi.asia/arts/26018291.html

原标题：编译打包产物依赖分析解读
简介：golang 性能压测 wr 工具实操指南，wr 压测工具对 Go 接口压测，观察 QPS 延迟，定位接口性能瓶颈。
 | 原文链接：http://wiki.y3mtsi.asia/arts/77398538.html

原标题：快速入门GraphQL基础查询语法示例
简介：nodejs 数据库连接池配置调优，调优 Node 数据库连接池参数，平衡性能与资源占用，避免连接耗尽。
 | 原文链接：http://wiki.y3mtsi.asia/arts/70007375.html

原标题：golang mysql json 字段查询使用
简介：开发环境变量配置全平台教程，区分 Windows、macOS、Linux 系统，讲解环境变量配置、加载优先级与常见失效原因。
 | 原文链接：http://wiki.y3mtsi.asia/arts/03613036.html

原标题：golang 系统设计单元测试 mock 外部依赖技巧
简介：golang 分布式锁 redis 实现，基于 Redis 实现 Go 分布式锁，解决多实例并发竞争资源问题。
 | 原文链接：http://wiki.y3mtsi.asia/arts/74884524.html

原标题：golang 系统设计配置中心核心能力梳理讲解
简介：golang fasthttp 客户端连接池调优，fasthttp 客户端连接池配置，复用连接提升请求性能。
 | 原文链接：http://wiki.y3mtsi.asia/arts/44551224.html

原标题：架构笔记：批量任务系统架构防重复、断点续跑
简介：golang go 无锁并发编程技巧，原子操作 sync/atomic，简单场景替换锁，提升并发性能。
 | 原文链接：http://wiki.y3mtsi.asia/arts/41252232.html

原标题：Practice：手写简易限流组件，计数器、令牌桶实现
简介：项目脚手架模板生成工具，搭建项目模板脚手架，一键生成标准化项目骨架，减少重复初始化工作。
 | 原文链接：http://wiki.y3mtsi.asia/arts/65018294.html

原标题：安全笔记：第三方SDK安全风险评估要点
简介：golang bufio.Scanner 按行读取大文件，Scanner 逐行读取文本文件，处理超大日志 csv。
 | 原文链接：http://wiki.y3mtsi.asia/arts/88044120.html

原标题：golang 系统设计定时任务执行超时中断防护
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://wiki.y3mtsi.asia/arts/01233155.html

原标题：前端骨架屏提升页面体验
简介：golang 数据库连接泄露排查，定位 Go 数据库连接泄露，连接没有归还池，导致连接耗尽报错。
 | 原文链接：http://wiki.y3mtsi.asia/arts/67727651.html

原标题：优化实践：读写分离分担主库查询压力
简介：golang go math 大数高精度计算，math/big 处理超大整数、高精度浮点数，金额大数运算。
 | 原文链接：http://wiki.y3mtsi.asia/arts/49644025.html

原标题：Practice：实现简单信号处理优雅停机实践
简介：移动端适配 rem vw 方案对比，对比 rem 与 vw 移动端适配方案，分析优缺点，给出选型建议。
 | 原文链接：http://wiki.y3mtsi.asia/arts/84558554.html

原标题：调优方案：前端静态资源打包性能体积优化
简介：前端错误监控上报系统搭建，搭建前端错误监控，捕获页面 JS 错误，上报后端，快速发现线上页面 bug。
 | 原文链接：http://wiki.y3mtsi.asia/arts/42525298.html

原标题：golang kafka 消费者偏移量管理
简介：nodejs 日志轮转生产环境配置，配置 Node 日志轮转切割，防止日志文件无限变大，适配生产环境。
 | 原文链接：http://wiki.y3mtsi.asia/arts/18305938.html

原标题：安全复盘：环境变量密钥泄露风险与防护
简介：golang sync.Once 只执行一次，sync.Once 做单例初始化，保证代码只执行一次，并发安全。
 | 原文链接：http://wiki.y3mtsi.asia/arts/25448416.html

原标题：排错：HTTPS证书过期导致接口调用失败
简介：golang redis 过期键监听回调，监听 key 过期事件，过期触发业务逻辑，实现过期自动处理业务场景。
 | 原文链接：http://wiki.y3mtsi.asia/arts/15313295.html

原标题：方案设计：接口版本管理架构向前兼容策略
简介：service‑worker 离线缓存实践，使用 ServiceWorker 实现静态资源离线缓存，弱网环境页面依然可访问。
 | 原文链接：http://wiki.y3mtsi.asia/arts/65907193.html

原标题：数据库分表存储大表优化方案
简介：浏览器缓存强制刷新方案，设置 HTTP 缓存头，处理浏览器缓存旧静态资源，让用户加载更新后的页面。
 | 原文链接：http://wiki.y3mtsi.asia/arts/47719551.html

原标题：运维笔记：线上服务健康检查脚本编写
简介：线程调度优化减少上下文切换，优化线程数量，减少线程频繁切换，降低 CPU 上下文切换开销。
 | 原文链接：http://wiki.y3mtsi.asia/arts/29757457.html

原标题：golang 大文件 http 下载服务
简介：golang feishu 飞书机器人消息发送，调用飞书 webhook 机器人，发送文本卡片消息，实现业务告警通知。
 | 原文链接：http://wiki.y3mtsi.asia/arts/31177240.html

原标题：golang docker volume 数据持久化
简介：golang md5 sha 加密工具实现，实现 MD5、SHA 哈希工具，做数据摘要，用于签名校验场景。
 | 原文链接：http://wiki.y3mtsi.asia/arts/85164922.html

原标题：线上异常：缓存雪崩带来数据库压力瞬间飙升
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://wiki.y3mtsi.asia/arts/62081824.html

五、文体娱乐
原标题：坑点：gitrebase操作失误，代码提交丢失
简介：golang nil channel 阻塞特性，nil channel 读写永久阻塞，理解 nil channel 行为做逻辑控制。
 | 原文链接：http://wiki.y3mtsi.asia/arts/22118826.html

原标题：golang 系统设计 id 生成器选型对比
简介：golang 子进程超时杀死防止挂住，context 控制子进程超时，超时强制杀掉子进程，避免子进程僵尸。
 | 原文链接：http://wiki.y3mtsi.asia/arts/44366719.html

原标题：SDK 版本兼容线上崩溃修复
简介：golang redis 过期时间处理技巧，设置 key 过期，监控过期事件，基于过期特性实现业务缓存逻辑。
 | 原文链接：http://wiki.y3mtsi.asia/arts/01643035.html

原标题：实战项目：百万日志文件解析处理脚本实践
简介：JWT 工具封装令牌刷新过期，封装 JWT 工具类，实现令牌生成、校验、过期刷新整套令牌管理逻辑。
 | 原文链接：http://wiki.y3mtsi.asia/arts/71222635.html

原标题：golang 系统设计接口幂等架构设计
简介：golang tcp 连接泄露排查定位，netstat 查看连接状态，找出未正常关闭连接，定位连接泄漏代码。
 | 原文链接：http://wiki.y3mtsi.asia/arts/41298889.html

原标题：开源项目构建失败排查步骤
简介：golang 内存碎片问题识别与规避，大量小对象频繁分配产生内存碎片，通过对象池减少碎片。
 | 原文链接：http://wiki.y3mtsi.asia/arts/42976378.html

原标题：HelloShell：入门常用shell脚本编写
简介：golang testify mock 模拟接口，mock 接口生成 mock 对象，单元测试模拟外部依赖行为。
 | 原文链接：http://wiki.y3mtsi.asia/arts/50217179.html

原标题：设计思考：业务系统中什么时候不要用微服务
简介：golang 静态编译缩小镜像体积，Go 程序静态编译，不依赖系统库，产出单二进制文件，缩小镜像。
 | 原文链接：http://wiki.y3mtsi.asia/arts/96492319.html

原标题：开发复盘：消息队列消息顺序性业务落地实践
简介：多套环境灵活切换配置方案，实现配置动态切换，通过环境变量、配置文件，快速切换开发测试生产环境。
 | 原文链接：http://wiki.y3mtsi.asia/arts/89007786.html

原标题：大事务拆分回滚日志暴涨解决
简介：golang 内存持续上涨定位思路，区分内存泄漏、缓存占用、GC 参数不合理，分步定位内存持续走高。
 | 原文链接：http://wiki.y3mtsi.asia/arts/51040015.html

原标题：golang es 索引生命周期管理思路
简介：golang gorm 事务手动回滚提交，手动控制事务流程，业务异常主动回滚，保障数据操作原子性。
 | 原文链接：http://wiki.y3mtsi.asia/arts/84902679.html

原标题：Docker 容器网络不通排查
简介：golang csv 读写批量数据处理，Go 读写 CSV 文件，批量导入导出业务数据，处理 CSV 格式解析。
 | 原文链接：http://wiki.y3mtsi.asia/arts/56784580.html

原标题：记一次本地运行正常，线上环境报错诡异问题
简介：golang multipart 表单文件上传解析，服务端解析 multipart 表单，获取上传文件与表单字段。
 | 原文链接：http://wiki.y3mtsi.asia/arts/81222978.html

原标题：golang 系统设计告警风暴抑制方案实现
简介：golang time 时间格式化避坑，Go 时间格式化参考时间牢记，处理时间解析格式化，解决时间输出错乱。
 | 原文链接：http://wiki.y3mtsi.asia/arts/71395678.html

原标题：golang 系统设计内网外网服务隔离方案
简介：golang k8s 客户端 client‑go 简单示例，client‑go 操作 k8s 资源，增删改查 pod deployment 等资源对象。
 | 原文链接：http://wiki.y3mtsi.asia/arts/52781528.html

原标题：避坑：定时任务重复执行带来业务脏数据
简介：golang 大内存分配 GC 抖动规避，避免瞬时大量对象创建，分批处理，防止 GC 抖动业务抖动。
 | 原文链接：http://wiki.y3mtsi.asia/arts/25188291.html

原标题：避坑：Nginx配置错误导致请求丢失Header
简介：golang fasthttp 客户端连接池调优，fasthttp 客户端连接池配置，复用连接提升请求性能。
 | 原文链接：http://wiki.y3mtsi.asia/arts/60966746.html

原标题：坑点：Git仓库过大，clone速度极慢解决方案
简介：golang interface 接口使用避坑，interface 判 nil 坑点，理解接口底层结构，避免判空逻辑失效。
 | 原文链接：http://wiki.y3mtsi.asia/arts/23411884.html

原标题：Performance：数据库索引优化常见错误案例
简介：golang prometheus client 业务埋点实操，prometheus client‑go 业务埋点，计数器、仪表盘、直方图指标开发。
 | 原文链接：http://wiki.y3mtsi.asia/arts/92747783.html

原标题：golang docker compose 完整语法
简介：golang tar gz 压缩解压处理，tar.gz 归档压缩解压，服务端日志备份、文件打包场景使用。
 | 原文链接：http://wiki.y3mtsi.asia/arts/23599647.html

原标题：Debug：时间回拨，定时任务调度逻辑错乱
简介：golang context.WithTimeout 超时上下文，WithTimeout 设置超时时间，超时自动 cancel 释放协程。
 | 原文链接：http://wiki.y3mtsi.asia/arts/86711251.html

原标题：Git 仓库瘦身加快克隆下载速度
简介：golang 消息队列实现事务消息方案，基于 kafka 实现事务消息，业务执行成功才对外投递消息。
 | 原文链接：http://wiki.y3mtsi.asia/arts/36587880.html

原标题：golang 系统设计大表结构变更不停机方案
简介：golang 处理连接被重置 reset 错误，识别 connection reset by peer，对端关闭连接异常处理逻辑。
 | 原文链接：http://wiki.y3mtsi.asia/arts/85371113.html

原标题：新手指南：读懂项目构建脚本作用
简介：golang grpc 拦截器开发鉴权日志，开发 grpc 服务端拦截器，统一做鉴权、日志打印、异常捕获处理。
 | 原文链接：http://wiki.y3mtsi.asia/arts/07235607.html

原标题：坑点：缓存穿透，大量无效请求打穿数据库
简介：golang mysql 长连接检测保活设置，配置 mysql 连接保活检测，剔除失效连接，避免拿到断开无效数据库连接。
 | 原文链接：http://wiki.y3mtsi.asia/arts/26660042.html

原标题：golang 大文件读取内存优化
简介：文件监控服务自动重启开发，监控项目文件变更，代码修改自动重启服务，提升本地开发调试效率。
 | 原文链接：http://wiki.y3mtsi.asia/arts/30269278.html

原标题：实战项目：WebSocket消息广播房间分组实践
简介：golang go 项目依赖冲突解决完整思路，定位冲突包，replace、exclude、升级降级解决版本冲突。
 | 原文链接：http://wiki.y3mtsi.asia/arts/52757187.html

原标题：多环境配置中心灵活切换方案
简介：容器软链接文件权限修复，修复容器内软链接文件权限，让程序能够正常读取软链接指向的文件。
 | 原文链接：http://wiki.y3mtsi.asia/arts/15111126.html

原标题：Troubleshooting：防火墙安全组拦截访问请求
简介：WSL 文件权限访问异常修复，处理 WSL 环境文件权限错乱，调整权限配置，实现文件正常读写访问。
 | 原文链接：http://wiki.y3mtsi.asia/arts/64552635.html

原标题：golang 系统设计指标聚合计算存储选型对比
简介：golang wasm webassembly go 编译，go 编译为 wasm，浏览器执行 go 代码，拓展 go 运行场景。
 | 原文链接：http://wiki.y3mtsi.asia/arts/25418526.html

原标题：零基础理解读写分离基础思想
简介：系统文件描述符上限调大，调高操作系统文件描述符上限，解决高并发场景打开文件报错。
 | 原文链接：http://wiki.y3mtsi.asia/arts/42041297.html

原标题：golang 系统设计数据库慢请求排查流程
简介：图片上传预览格式大小处理，实现图片上传接口，校验文件格式、大小，完成上传后预览处理。
 | 原文链接：http://wiki.y3mtsi.asia/arts/51444457.html

原标题：vite 项目配置与构建提速技巧
简介：golang prometheus http 接口暴露指标，暴露 prometheus metrics 接口，输出业务运行指标，接入监控告警系统。
 | 原文链接：http://wiki.y3mtsi.asia/arts/56758479.html

原标题：新手教程：本地环境变量配置全流程
简介：golang redis list 队列简易消息队列，利用 Redis List 实现简易队列，完成任务入队消费基础能力。
 | 原文链接：http://wiki.y3mtsi.asia/arts/99188213.html

原标题：golang mongodb 文档结构设计原则
简介：前端静态缓存更新生效处理，修改静态资源版本标识，处理浏览器强缓存，让更新资源生效。
 | 原文链接：http://wiki.y3mtsi.asia/arts/96536816.html

原标题：Troubleshoot：DNS解析异常导致第三方调用失败
简介：golang 限流熔断放在代理层实践，代理层统一限流熔断，对后端服务做流量保护。
 | 原文链接：http://wiki.y3mtsi.asia/arts/63233443.html

原标题：前端静态缓存更新生效处理
简介：项目依赖安全扫描漏洞防范，扫描项目第三方依赖包，修复存在安全漏洞依赖，防范供应链攻击。
 | 原文链接：http://wiki.y3mtsi.asia/arts/90114675.html

原标题：项目实践：消息队列消息确认机制业务实践
简介：接口请求重试容错机制实现，封装请求重试逻辑，遇到临时网络故障自动重试，提升第三方调用稳定性。
 | 原文链接：http://wiki.y3mtsi.asia/arts/80460838.html

原标题：golang 系统设计监控告警体系搭建思路
简介：golang redis list 队列简易消息队列，利用 Redis List 实现简易队列，完成任务入队消费基础能力。
 | 原文链接：http://wiki.y3mtsi.asia/arts/57898092.html

原标题：复盘总结：线上故障完整复盘报告模板示例
简介：golang rate‑limiter 限流组件，封装通用 Go 限流组件，支持多算法，业务接口直接复用调用。
 | 原文链接：http://wiki.y3mtsi.asia/arts/09230829.html

五、性能优化｜Performance
仓库链接：
https://github.com/halescott79/kjbxzv/commit/61b6d6e1c7bfbdac28b9d6caaa83ef46346cc3c3

https://github.com/franklinvalerie417/ghnktp/commit/5b1843c0f28b6f9895d259dd24abad11c086a29b

https://github.com/reyesvicki427/tfxinp/commit/556d293cd39a0782e3c88dec49c79360677779ce

https://github.com/huntdavid698/pcqczo/commit/f2288cc00e08fc5b5c871cf580250dfb546096b7

https://github.com/woodnatalie531/wsunre/commit/dfe2d4b096aa46742b2ce958bf3e5bc248acc849

https://github.com/kelleymichele2/busbxm/commit/46963fe14c8370aed0a7afd882403a83176aad22

https://github.com/campbellgwendolyn04/rcbwlz/commit/f792f4e6973698b03640bbf425b4503d80c65445

https://github.com/gutierrezcindy3/vamoqy/commit/1095fe928f71dcce244863b75d3fdac6d75fc00f

https://github.com/shannontracy562/dusahi/commit/79d68f598ef93cadfabf0e07f582b36701ae0b59

https://github.com/lewisrobert902/dfpzmg/commit/cea9b5da9236fa5fc2ff9c43fc34634aeb87242f

https://github.com/garrettjoy2/soaxuk/commit/25220431ec24e534352eed33ac019dec16f62584

https://github.com/haynesbrittany91/atftev/commit/3171d995edc0cc6b8876f34861c6d598ba69a160

https://github.com/hernandezmicheal9930/kvpqqa/commit/a0e5d0ffa8cc5faec14643773b691c46eee310e6

https://github.com/humphreykyle58/rspshh/commit/19f0a41c308b3b126e6d8bcf58e74fd1173fb701


六、安全｜Security
代码仓库：
https://github.com/nixonscott3145/mooyvl/commit/25243b788d19a3e34fddc9969b46df9e15154a94

https://github.com/williamslynn4829/scpzcl/commit/1579a183787539525e7a5baf85bee6488e78e4f7

https://github.com/frederickcynthia322/sluyfj/commit/6c51a7004929052641f50431470bdcac3a8e895e

https://github.com/browntonya78/nackic/commit/8989e5ea0fce0bc0bc535dbbf1abb3e11a794dcc

https://github.com/griffineric92/dokwsr/commit/74a3c942f669c007bf5bb38604f1f5ba80e41ca6

https://github.com/vargasgary779/xgzyue/commit/7dd4278525a4d33124b26274cf55f1c8d097221e

https://github.com/piercekevin7/xvuwgj/commit/1c0b8605cf88fb4d140dbbddab324be929c05667

https://github.com/lopezmatthew5/gnmqar/commit/0d2ab875a75a70e99a264aeca86504f0fd45a422

https://github.com/allencassandra0463/cvnbsx/commit/7da0de47aa8689b27916e15bbc38a681f8461eb1

https://github.com/carrbrian51/fsxudt/commit/45c3215a968000373335985be6da0d77dc75f777

https://github.com/dyerwendy576/yrwibx/commit/2cee964688dc5e3645b89958190277f592ca7196

https://github.com/wardgregory26/talhxt/commit/26cd2a1cd33a80f9a3f85d793f962c1c2bba8f28

https://github.com/rodriguezmatthew5/vtzhkz/commit/fb4aa2ef18d7add23e3d1ff2e52b151dff303b96

https://github.com/stonejonathan67/pmzikz/commit/e8cba1d74ce396ca980599121af6102259f3052d


七、DevOps｜运维部署
参考资料[1]：https://github.com/garciacindy6770/fidydu/commit/f19bb47a25e785de4f8e03c003eea0efd0a1e7c7

参考资料[2]：https://github.com/robinsonsherry31/nkiokc/commit/15c030d545e00398ad79f58aa5819efe075a65a2

参考资料[3]：https://github.com/smithmichael8495/jmnjgj/commit/5997abe3ebb7c0f1ee89a1fd7c7aa8cb9c37d29b

参考资料[4]：https://github.com/mckinneyhannah5539/vpbrak/commit/19cbbcfcc2c5f885b783167272e4193457a8420c

参考资料[5]：https://github.com/thomaseileen4/tfblzb/commit/6b69f7651aa22938c18e074c7d2e0c57f3abc9c5


八、开源、效率、AI、总结复盘
开源资料：https://github.com/ballardbarbara3001/bhmqof/commit/fff5335301aa971455e3447e4d3e2e0f21676a5f

开源资料：https://github.com/hamptontiffany427/azlwfb/commit/8cef62b0b958d902cd9016bd76c38074cf21be2d

开源资料：https://github.com/brewerchristopher8044/utrvqg/commit/59605ffb068589b4a922514fb3bfe335785f75d5

开源资料：https://github.com/popekimberly6070/gcndud/commit/5e892bea01a79f0aba52aa9aa1db7d66b3d2ab9a

开源资料：https://github.com/adamsgregory05/wlqkoi/commit/190761257c13103c27963a39fa8d24eca6e8bbea

开源资料：https://github.com/woodsdennis5/ixfsfx/commit/e98b02245b052e9292f32c8d7aebf7ccf16e5061

开源资料：https://github.com/halescott79/kjbxzv/commit/ffc7e7471c584fb60a9e54458a41606750e98421

开源资料：https://github.com/browntheodore81/scjnsj/commit/d470a5f059e74ba27a15fff78efd08ff5c814827

开源资料：https://github.com/franklinvalerie417/ghnktp/commit/fc4ac0844b15e76ab598f05d9ff7580500d968a3


*数据更新时间：2026年08月23日05时11分52秒(UTC+8)*
*数据采集自，GitHub README、Issues、Blog、技术文档、项目 Wiki，包含：教程、踩坑、实战、架构、性能、部署、排错、最佳实践、复盘、迁移、重构、安全、运维、前端、后端、云原生、AI、效率工具。*
