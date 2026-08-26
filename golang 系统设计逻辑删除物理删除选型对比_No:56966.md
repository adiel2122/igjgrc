最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计逻辑删除物理删除选型对比
简介：分布式 ID 全局唯一生成方案，讲解分布式 ID 生成思路，实现全局唯一 ID，满足分布式系统主键生成需求。
 | 原文链接：http://wiki.083dms.asia/arts/010411.Doc

原标题：缓存过期打散防止缓存雪崩
简介：网关超时时间调优后端等待，调大网关向后端转发请求超时时间，给后端业务充足处理时间。
 | 原文链接：http://wiki.083dms.asia/arts/571953.Doc

原标题：golang 系统设计 ide 配置 go 开发效率提升技巧
简介：TCP 长连接参数优化 TIME_WAIT，调整 TCP 内核参数，优化长连接，减少大量 TIME_WAIT 连接占用资源。
 | 原文链接：http://wiki.083dms.asia/arts/673758.Doc

原标题：架构复盘：服务优雅停机架构设计资源释放
简介：golang grpc 重试机制客户端配置，grpc 客户端配置重试策略，临时故障自动重试，提升调用稳定性。
 | 原文链接：http://wiki.083dms.asia/arts/418125.Doc

原标题：golang k8s cronjob 定时任务配置
简介：代理 HTTPS 证书访问异常处理，配置代理根证书，解决代理环境 HTTPS 证书校验失败无法访问外网。
 | 原文链接：http://wiki.083dms.asia/arts/699888.Doc

原标题：golang 系统设计日志级别业务使用原则梳理
简介：golang go select 多路等待 channel，select 等待多个 channel，default 非阻塞，超时等待 channel。
 | 原文链接：http://wiki.083dms.asia/arts/983111.Doc

原标题：架构复盘：多级缓存架构，本地缓存+分布式缓存
简介：CI 流水线超时时间延长配置，调大 CI 任务超时阈值，解决构建任务耗时较长被流水线强制终止。
 | 原文链接：http://wiki.083dms.asia/arts/672660.Doc

原标题：golang docker 基础命令实操汇总
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://wiki.083dms.asia/arts/896822.Doc

原标题：记一次内存Swap被大量使用系统响应缓慢
简介：golang 日志输出 stdout 标准输出规范，容器环境日志输出到 stdout，由容器平台统一采集日志文件。
 | 原文链接：http://wiki.083dms.asia/arts/149480.Doc

原标题：架构复盘：分表扩容架构平滑迁移思路
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://wiki.083dms.asia/arts/839090.Doc

原标题：golang docker compose 依赖启动顺序
简介：golang 分布式事务 seata go 客户端，seata‑go 实现分布式事务，保证跨库业务数据最终一致性。
 | 原文链接：http://wiki.083dms.asia/arts/339594.Doc

原标题：设计实践：如何设计可扩展业务数据库表结构
简介：接口压测定位系统性能瓶颈，使用压测工具对接口施压，观察指标，定位系统性能瓶颈点。
 | 原文链接：http://wiki.083dms.asia/arts/100074.Doc

原标题：golang 系统设计缓存与数据库一致性权衡
简介：golang 日志级别动态调整热更新，不用重启程序动态修改日志输出级别，线上调试排查问题十分方便。
 | 原文链接：http://wiki.083dms.asia/arts/984309.Doc

原标题：部署实践：内网开发环境代理配置实践
简介：Git 分支切换合并删除完整操作，实操分支全生命周期操作，包含切换、合并、删除，熟悉日常开发分支处理流程。
 | 原文链接：http://wiki.083dms.asia/arts/343178.Doc

原标题：Practice：实现请求大小限制中间件防护大报文
简介：全平台系统环境变量配置，汇总多操作系统环境变量配置方法，统一项目读取逻辑，适配不同运行平台。
 | 原文链接：http://wiki.083dms.asia/arts/019060.Doc

原标题：文件批量导入导出功能实现
简介：多套环境灵活切换配置方案，实现配置动态切换，通过环境变量、配置文件，快速切换开发测试生产环境。
 | 原文链接：http://wiki.083dms.asia/arts/153940.Doc

原标题：踩坑：批量MQ消费失败直接无限重试消息爆炸
简介：HTTP 状态码请求头完整梳理，汇总常用 HTTP 状态码与请求头含义，帮助快速看懂网络请求，排查接口通信问题。
 | 原文链接：http://wiki.083dms.asia/arts/113900.Doc

原标题：Practice：手写简易限流组件，计数器、令牌桶实现
简介：Nginx 缓冲区调优大文件上传，调大 Nginx 请求缓冲区，支持客户端上传大体积文件，避免上传被截断。
 | 原文链接：http://wiki.083dms.asia/arts/676752.Doc

原标题：部署复盘：服务启动顺序依赖处理方案
简介：日志驱动异常日志不输出修复，排查日志驱动配置，修复日志写入配置，恢复程序正常日志输出。
 | 原文链接：http://wiki.083dms.asia/arts/771903.Doc

原标题：项目语义化版本号规范管理
简介：线程池拒绝策略任务丢失防护，合理设置线程池拒绝策略，处理任务队列满场景，避免业务任务直接丢失。
 | 原文链接：http://wiki.083dms.asia/arts/333369.Doc

原标题：HTTPS 证书过期更新操作
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://wiki.083dms.asia/arts/366990.Doc

原标题：golang jwt 鉴权中间件完整示例
简介：nodejs 全局异常捕获进程防护，捕获未捕获异常与 Promise 拒绝，尽量保护进程不因为异常直接退出。
 | 原文链接：http://wiki.083dms.asia/arts/383522.Doc

原标题：golang 系统设计数据库连接池调优实践
简介：golang redis pipeline 与 txpipeline 区别，区分普通管道与事务管道，根据业务场景选择合适批量执行方案。
 | 原文链接：http://wiki.083dms.asia/arts/592511.Doc

原标题：架构笔记：海量消息堆积架构处理能力设计
简介：灰度发布策略服务平滑升级，实现灰度发布逻辑，流量逐步切到新版本，出现问题快速回滚旧版本。
 | 原文链接：http://wiki.083dms.asia/arts/316408.Doc

原标题：Git 代码冲突正确处理方式
简介：限流窗口绕过漏洞修复方案，修复限流时间窗口漏洞，避免攻击者绕过限流规则，保障接口防护有效。
 | 原文链接：http://wiki.083dms.asia/arts/179698.Doc

原标题：实战：Nginx配置静态站点、反向代理、负载均衡
简介：golang 数据库分表策略按时间分片，按时间维度分表，历史数据拆分，单表数据量控制保证查询性能。
 | 原文链接：http://wiki.083dms.asia/arts/691969.Doc

原标题：golang 系统设计密码存储哈希加盐实现
简介：golang trace 工具采集 go 程序执行轨迹，go trace 采集程序完整调度轨迹，分析协程调度阻塞问题。
 | 原文链接：http://wiki.083dms.asia/arts/802993.Doc

原标题：开发记录：搭建CI/CD流水线自动构建部署项目
简介：golang go 调度器 GMP 模型通俗讲解，拆解 GMP 模型，理解 goroutine M P 调度原理，看懂调度状态。
 | 原文链接：http://wiki.083dms.asia/arts/781479.Doc

原标题：部署复盘：蓝绿发布实现零停机业务更新
简介：golang redis 过期键监听回调，监听 key 过期事件，过期触发业务逻辑，实现过期自动处理业务场景。
 | 原文链接：http://wiki.083dms.asia/arts/023463.Doc

原标题：golang 系统设计缓存与数据库一致性权衡
简介：golang hertz http 框架快速上手，hertz 高性能 http 框架，路由中间件参数校验快速开发接口服务。
 | 原文链接：http://wiki.083dms.asia/arts/826733.Doc

原标题：golang 系统设计 protobuf json 性能对比
简介：golang uuid 生成多种版本实现，生成 uuid v1 v4，生成唯一标识，业务用于单据编号场景。
 | 原文链接：http://wiki.083dms.asia/arts/269969.Doc

原标题：排错：静态资源404，打包路径配置错误
简介：代理 HTTPS 证书访问异常处理，配置代理根证书，解决代理环境 HTTPS 证书校验失败无法访问外网。
 | 原文链接：http://wiki.083dms.asia/arts/491140.Doc

原标题：实战：Redis集群本地搭建与功能验证
简介：golang 环境变量读取与类型转换，读取系统环境变量，做类型转换默认值处理，适配多环境部署。
 | 原文链接：http://wiki.083dms.asia/arts/673981.Doc

原标题：golang gorm ORM 数据库操作
简介：golang 任务失败重试与死信队列，异步任务失败自动重试，超过重试次数进入死信队列人工处理。
 | 原文链接：http://wiki.083dms.asia/arts/557036.Doc

原标题：Debug：Websocket频繁断开重连根因分析
简介：golang http 重定向策略自定义，CheckRedirect 自定义重定向逻辑，限制重定向次数，防止死循环。
 | 原文链接：http://wiki.083dms.asia/arts/345003.Doc

原标题：开发测试生产多环境配置区分
简介：golang time 时间格式化参考时间牢记，2006‑01‑02T15:04:05Z07:00，掌握 go 时间格式化关键点。
 | 原文链接：http://wiki.083dms.asia/arts/279756.Doc

原标题：HelloShell：入门常用shell脚本编写
简介：项目依赖安全扫描漏洞防范，扫描项目第三方依赖包，修复存在安全漏洞依赖，防范供应链攻击。
 | 原文链接：http://wiki.083dms.asia/arts/835987.Doc

原标题：golang 数据库批量更新性能优化
简介：TCP 心跳检测清理僵死连接，开启 TCP 心跳机制，自动清理僵死无效连接，释放连接资源。
 | 原文链接：http://wiki.083dms.asia/arts/636948.Doc

原标题：golang 系统设计缓存过期时间设置原则梳理
简介：开发测试生产多环境配置区分，讲解三套环境配置分离思路，配置文件隔离，防止开发配置泄露到生产环境。
 | 原文链接：http://wiki.083dms.asia/arts/265203.Doc

原标题：服务器 Swap 关闭提升响应速度
简介：golang gif 图片帧处理操作，解析 gif 图片帧，压缩、拆分 gif 动图，处理动图业务。
 | 原文链接：http://wiki.083dms.asia/arts/135500.Doc


二、踩坑排错｜Troubleshooting
原标题：Security：反序列化漏洞风险识别与规避
简介：线程调度优化减少上下文切换，优化线程数量，减少线程频繁切换，降低 CPU 上下文切换开销。
 | 原文链接：http://wiki.083dms.asia/arts/381911.Doc

原标题：golang 系统设计 webhook 回调处理架构
简介：golang 分布式锁 redis 实现，基于 Redis 实现 Go 分布式锁，解决多实例并发竞争资源问题。
 | 原文链接：http://wiki.083dms.asia/arts/553529.Doc

原标题：golang 系统设计数据库慢请求排查流程
简介：golang http body 必须关闭的重要性，无论成功失败必须关闭 request.Body，否则连接无法复用泄漏。
 | 原文链接：http://wiki.083dms.asia/arts/225835.Doc

原标题：多环境配置中心灵活切换方案
简介：golang go 程序容器资源 requests limits，设置容器 cpu 内存配额，防止实例抢占集群资源，稳定调度。
 | 原文链接：http://wiki.083dms.asia/arts/280814.Doc

原标题：性能复盘：GC停顿过长业务卡顿优化记录
简介：开发环境变量配置全平台教程，区分 Windows、macOS、Linux 系统，讲解环境变量配置、加载优先级与常见失效原因。
 | 原文链接：http://wiki.083dms.asia/arts/670417.Doc

原标题：架构复盘：多级缓存架构，本地缓存+分布式缓存
简介：golang 日志脱敏敏感字段过滤，日志打印自动脱敏敏感字段，避免日志输出手机号身份证泄露隐私。
 | 原文链接：http://wiki.083dms.asia/arts/002473.Doc

原标题：浏览器内存泄漏排查前端页面
简介：golang channel 缓冲无缓冲区别，缓冲 channel 与无缓冲 channel，底层行为差异业务选型参考。
 | 原文链接：http://wiki.083dms.asia/arts/510142.Doc

原标题：macOS 脚本执行权限开启
简介：golang delve 远程调试 go 线上程序，delve 远程调试，线上环境附加进程调试排查线上 bug。
 | 原文链接：http://wiki.083dms.asia/arts/449594.Doc

原标题：Security：RPC调用身份认证安全加固
简介：golang fasthttp 服务开发完整示例，fasthttp 搭建 http 服务，路由、参数读取、响应返回完整业务。
 | 原文链接：http://wiki.083dms.asia/arts/963752.Doc

原标题：系统文件描述符上限调大
简介：数据库排序规则统一结果一致，统一数据库表排序规则，解决不同环境查询排序结果不一致问题。
 | 原文链接：http://wiki.083dms.asia/arts/638282.Doc

原标题：golang 系统设计故障止损降级回滚执行原则
简介：golang 系统资源限制读取 cpu 内存，读取系统容器 cpu 内存限制，程序适配容器资源配额做业务调优。
 | 原文链接：http://wiki.083dms.asia/arts/679552.Doc

原标题：线上异常：布隆过滤器误判造成业务逻辑异常
简介：golang 自定义 pprof 扩展业务指标，扩展 pprof，输出业务自定义指标，结合性能数据分析业务状态。
 | 原文链接：http://wiki.083dms.asia/arts/895241.Doc

原标题：golang 令牌桶限流中间件 gin
简介：CDN 缓存刷新获取最新静态资源，调用 CDN 刷新接口，清除节点旧缓存，用户访问到更新后的静态文件。
 | 原文链接：http://wiki.083dms.asia/arts/254092.Doc

原标题：golang mysql 时间类型选型避坑
简介：golang 处理连接被重置 reset 错误，识别 connection reset by peer，对端关闭连接异常处理逻辑。
 | 原文链接：http://wiki.083dms.asia/arts/844770.Doc

原标题：容器软链接文件权限修复
简介：golang 协程 panic 捕获防止崩溃，协程内部捕获 panic，防止单个协程恐慌造成整个 Go 进程崩溃。
 | 原文链接：http://wiki.083dms.asia/arts/704099.Doc

原标题：开发记录：日志脱敏防止敏感信息输出实践
简介：OOMKilled 容器被杀完整排查，排查容器被 OOM 终止完整流程，区分程序内存泄露和容器内存限制过小。
 | 原文链接：http://wiki.083dms.asia/arts/272229.Doc

原标题：坑点：gitrebase操作失误，代码提交丢失
简介：异步任务堆积消费能力优化，处理消息任务堆积问题，提升消费处理速度，恢复队列正常处理水位。
 | 原文链接：http://wiki.083dms.asia/arts/443477.Doc

原标题：Issue：本地可以访问，容器内部网络不通
简介：golang go 排序 sort 包自定义排序，sort 包实现自定义排序逻辑，对切片按业务规则排序。
 | 原文链接：http://wiki.083dms.asia/arts/836523.Doc

原标题：nodejs redis 缓存业务实战
简介：golang excel 大文件读取流式解析，流式读取大 excel 文件，逐行解析数据，不加载全部内容进内存。
 | 原文链接：http://wiki.083dms.asia/arts/943885.Doc

原标题：实战项目：数据导出Excel百万级大数据导出方案
简介：golang grpc protobuf 开发实操，Go gRPC 开发，编写 Protobuf 定义，服务端客户端完整示例。
 | 原文链接：http://wiki.083dms.asia/arts/653512.Doc

原标题：Practice：实现接口幂等性多种方案对比实践
简介：golang defer 闭包变量捕获坑，defer 捕获循环变量引用，变量被复写，理解闭包变量捕获规则。
 | 原文链接：http://wiki.083dms.asia/arts/212966.Doc

原标题：坑点：gitrebase操作失误，代码提交丢失
简介：golang 容器信号转发处理问题修复，docker/k8s 正确转发 SIGTERM 信号，保证 go 程序收到信号优雅退出。
 | 原文链接：http://wiki.083dms.asia/arts/370556.Doc

原标题：设计思考：系统幂等性整体架构层面保障
简介：golang wasm webassembly go 编译，go 编译为 wasm，浏览器执行 go 代码，拓展 go 运行场景。
 | 原文链接：http://wiki.083dms.asia/arts/712334.Doc

原标题：golang k8s devops 流水线简单思路
简介：golang redis lua 脚本原子操作，使用 Lua 脚本实现原子逻辑，减少网络往返，保障多命令原子执行。
 | 原文链接：http://wiki.083dms.asia/arts/377002.Doc

原标题：golang 系统设计无锁编程思路简单示例
简介：golang 灰度发布流量权重路由实现，根据权重切分流量，部分流量访问新版本服务，实现灰度发布。
 | 原文链接：http://wiki.083dms.asia/arts/511457.Doc

原标题：Issue复现：内存泄漏定位完整复盘记录
简介：golang 分布式事务 seata go 客户端，seata‑go 实现分布式事务，保证跨库业务数据最终一致性。
 | 原文链接：http://wiki.083dms.asia/arts/057485.Doc

原标题：入门实践：使用Git完成第一次代码提交与推送
简介：接口幂等性防重复请求实现，实现接口幂等逻辑，避免重复提交请求产生多条脏数据，保障业务数据安全。
 | 原文链接：http://wiki.083dms.asia/arts/684163.Doc

原标题：golang 系统设计 id 生成器选型对比
简介：golang excel 简单读写操作示例，Go 实现 Excel 简单读写，业务数据导出 Excel 报表。
 | 原文链接：http://wiki.083dms.asia/arts/985701.Doc

原标题：开发记录：实现完整用户登录鉴权业务模块
简介：golang csv 读写批量数据处理，Go 读写 CSV 文件，批量导入导出业务数据，处理 CSV 格式解析。
 | 原文链接：http://wiki.083dms.asia/arts/684400.Doc

原标题：golang 系统设计技术文档维护更新最佳实践
简介：浏览器本地存储安全使用技巧，讲解 localStorage、sessionStorage 使用边界，规避 XSS 泄露存储数据。
 | 原文链接：http://wiki.083dms.asia/arts/444820.Doc

原标题：Hands‑on：手写简易ORM框架理解底层原理
简介：golang go‑zero 分布式锁组件使用，go‑zero 内置 redis 分布式锁，业务直接调用实现并发控制。
 | 原文链接：http://wiki.083dms.asia/arts/279130.Doc

原标题：端口占用访问失败排查方案
简介：HTTP 状态码请求头完整梳理，汇总常用 HTTP 状态码与请求头含义，帮助快速看懂网络请求，排查接口通信问题。
 | 原文链接：http://wiki.083dms.asia/arts/540558.Doc

原标题：golang 系统设计线上故障排查完整流程
简介：Fork 开源项目同步上游代码，Fork 开源仓库之后，配置上游源，同步官方最新代码，保持代码版本对齐。
 | 原文链接：http://wiki.083dms.asia/arts/426384.Doc

原标题：优化实践：接口返回字段裁剪减少报文大小
简介：golang atomic.Value 存储任意类型数据，atomic.Value 安全存储读取任意类型，配置热更新常用。
 | 原文链接：http://wiki.083dms.asia/arts/854460.Doc

原标题：golang 系统设计熔断降级架构讲解
简介：大事务拆分防止连接池耗尽，将执行时间很长的大事务拆分为小事务，减少事务占用连接时长。
 | 原文链接：http://wiki.083dms.asia/arts/349648.Doc

原标题：实战项目：前端资源打包体积优化完整实操
简介：nodejs 全局异常捕获进程防护，捕获未捕获异常与 Promise 拒绝，尽量保护进程不因为异常直接退出。
 | 原文链接：http://wiki.083dms.asia/arts/333125.Doc

原标题：golang redis 缓存击穿防护实现
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://wiki.083dms.asia/arts/900243.Doc

原标题：golang 系统设计 hot‑reload 热重载 go 开发工具
简介：Git 分支管理多人协作实战教程，详解分支创建、合并、冲突处理，适配团队开发场景，规范多人协同代码工作流。
 | 原文链接：http://wiki.083dms.asia/arts/973408.Doc

原标题：序列化版本不一致解析失败
简介：Nginx 静态代理负载均衡全套配置，一套 Nginx 配置示例，覆盖静态资源、反向代理、负载均衡场景。
 | 原文链接：http://wiki.083dms.asia/arts/635635.Doc

原标题：排错：静态资源404，打包路径配置错误
简介：调试工具断点调试变量查看技巧，演示断点设置、变量监视、调用栈查看，借助调试工具高效排查业务逻辑错误。
 | 原文链接：http://wiki.083dms.asia/arts/903406.Doc

三、实战开发｜Practice
原标题：安全实践：备份文件访问权限安全管控
简介：golang 表格驱动测试完整示例，表格驱动多组输入输出，批量执行测试用例，减少重复代码。
 | 原文链接：http://wiki.083dms.asia/arts/788521.Doc

原标题：运维笔记：服务器定时任务运维脚本编写
简介：golang 滑动窗口限流算法 go 实现，滑动窗口限流，解决固定窗口临界流量突增漏洞，限流更精准。
 | 原文链接：http://wiki.083dms.asia/arts/955497.Doc

原标题：快速入门环境区分：开发、测试、生产环境
简介：golang grpc 双向流双向通信开发，grpc 双向流，服务端客户端持续互发消息，长连接流式业务场景。
 | 原文链接：http://wiki.083dms.asia/arts/025114.Doc

原标题：网关集成鉴权限流日志一体化
简介：golang jaeger 链路追踪部署对接，jaeger 接收 opentelemetry 链路数据，可视化完整调用链路。
 | 原文链接：http://wiki.083dms.asia/arts/714015.Doc

原标题：golang 系统设计限流算法原理代码实现
简介：golang excel 大文件读取流式解析，流式读取大 excel 文件，逐行解析数据，不加载全部内容进内存。
 | 原文链接：http://wiki.083dms.asia/arts/443435.Doc

原标题：架构笔记：分布式事务方案对比与业务取舍
简介：golang go list 双向链表使用，container/list 双向链表，频繁增删节点业务场景使用。
 | 原文链接：http://wiki.083dms.asia/arts/787465.Doc

原标题：Hands‑on：简易ID生成雪花算法完整实现
简介：golang go mod tidy 依赖清理，go mod tidy 自动增删依赖，整理 go.mod go.sum 文件。
 | 原文链接：http://wiki.083dms.asia/arts/181764.Doc

原标题：JSON XML 数据解析处理示例
简介：golang prometheus 指标埋点开发，业务埋点计数器、仪表盘、直方图，对接 prometheus 采集监控指标。
 | 原文链接：http://wiki.083dms.asia/arts/775754.Doc

原标题：golang kafka 同步异步消费对比
简介：golang httptest 模拟 http 请求单元测试，httptest 模拟 http 请求，测试 http handler 逻辑不用启动服务。
 | 原文链接：http://wiki.083dms.asia/arts/185778.Doc

原标题：新手向：开源项目fork与同步上游代码
简介：对象存储上传下载权限实操，演示对象存储文件上传、下载、访问权限设置，适配业务文件存储场景。
 | 原文链接：http://wiki.083dms.asia/arts/184876.Doc

原标题：坑点：缓存穿透，大量无效请求打穿数据库
简介：CI 构建缓存加速编译速度，开启 CI 流水线依赖缓存，复用上一次构建依赖包，缩短流水线构建耗时。
 | 原文链接：http://wiki.083dms.asia/arts/275201.Doc

原标题：调优方案：Nginx性能参数调优高并发配置
简介：静态资源 404 路径打包修复，修复打包后静态资源访问 404，调整资源输出路径，保证资源正常加载。
 | 原文链接：http://wiki.083dms.asia/arts/981207.Doc

原标题：golang 系统设计 json 解析性能优化实操
简介：golang 集成测试测试数据库回滚，集成测试结束自动回滚数据库，不污染测试环境数据。
 | 原文链接：http://wiki.083dms.asia/arts/612372.Doc

原标题：DNS 解析异常第三方调用故障
简介：golang 接口返回统一封装工具，封装 Go 接口统一返回工具，标准化成功失败返回结构体。
 | 原文链接：http://wiki.083dms.asia/arts/963210.Doc

原标题：golang 系统设计定时任务调度时间校准要点
简介：golang recover 捕获 panic 使用边界，recover 只在 defer 内部生效，协程内部必须捕获本协程 panic。
 | 原文链接：http://wiki.083dms.asia/arts/695848.Doc

原标题：golang gitlab ci 配置自动构建镜像
简介：简易日志收集集中管理方案，搭建轻量日志收集方案，把多服务日志汇总，集中检索查看日志信息。
 | 原文链接：http://wiki.083dms.asia/arts/073544.Doc

原标题：架构复盘：限流系统架构防止恶意流量冲击
简介：golang go 优雅处理信号丢失场景，处理信号丢失、信号被忽略，保障程序可以正常接收终止信号。
 | 原文链接：http://wiki.083dms.asia/arts/803287.Doc

原标题：WebSocket 聊天室实时通讯开发
简介：集成测试业务流程编写示例，编写业务流程集成测试，覆盖完整业务链路，验证模块之间协同工作是否正常。
 | 原文链接：http://wiki.083dms.asia/arts/207026.Doc

原标题：Hands‑on：手写简单RPC框架基础通信版本
简介：golang udp 服务端客户端开发示例，golang 实现 UDP 服务收发数据包，实现 udp 协议通信程序。
 | 原文链接：http://wiki.083dms.asia/arts/807102.Doc

原标题：nodejs 数据库连接池配置调优
简介：golang go 泛型使用避坑注意点，泛型与 interface 区别，泛型性能，什么时候适合使用泛型。
 | 原文链接：http://wiki.083dms.asia/arts/308050.Doc

原标题：golang 系统设计单元测试边界条件覆盖思路
简介：golang gin 框架接口开发实战，Gin 框架搭建 HTTP 服务，开发增删改查接口，快速完成后端接口开发。
 | 原文链接：http://wiki.083dms.asia/arts/878820.Doc

原标题：nestjs 全局返回格式统一处理
简介：文件读写与异常捕获代码示例，演示文件读取写入操作，增加异常捕获逻辑，规避文件不存在、权限不足导致崩溃。
 | 原文链接：http://wiki.083dms.asia/arts/940385.Doc

原标题：Debug：Websocket频繁断开重连根因分析
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：http://wiki.083dms.asia/arts/302373.Doc

原标题：多版本开发环境共存配置
简介：golang 故障演练服务模拟超时报错，程序模拟接口超时、报错，做混沌测试验证熔断降级有效性。
 | 原文链接：http://wiki.083dms.asia/arts/822484.Doc

原标题：golang redis 网络超时参数调优
简介：全局异常处理器接口返回统一，接入全局异常捕获，拦截业务全部异常，对外输出统一格式返回值。
 | 原文链接：http://wiki.083dms.asia/arts/383024.Doc

原标题：react hooks 常见陷阱避坑指南
简介：golang go 时间 time.Timer time.Ticker，定时器与周期定时器，Stop Reset 正确使用，防止资源泄漏。
 | 原文链接：http://wiki.083dms.asia/arts/198979.Doc

原标题：golang 系统设计网关鉴权鉴权转发流程讲解
简介：golang 日志 zap 结构化日志实践，接入 Zap 结构化日志库，打印结构化日志，方便日志检索解析。
 | 原文链接：http://wiki.083dms.asia/arts/534492.Doc

原标题：golang k8s secret 加密敏感信息
简介：日志敏感信息脱敏泄露防护，日志打印时自动脱敏手机号身份证，避免日志输出泄露用户隐私数据。
 | 原文链接：http://wiki.083dms.asia/arts/269103.Doc

原标题：零基础理解数据库事务基础ACID概念
简介：CI/CD 流水线自动构建部署落地，搭建完整 CI/CD 流水线，代码提交自动构建、测试、部署到目标环境。
 | 原文链接：http://wiki.083dms.asia/arts/030124.Doc

原标题：golang 优雅停机服务关闭实现
简介：golang 静态文件服务搭建教程，Go 搭建静态文件服务，托管静态资源，实现文件直接对外访问。
 | 原文链接：http://wiki.083dms.asia/arts/332800.Doc

原标题：快速入门gRPC基础概念与简单示例
简介：前端权限路由动态生成实现，根据后端返回权限，动态生成前端路由菜单，实现页面权限控制。
 | 原文链接：http://wiki.083dms.asia/arts/761227.Doc

原标题：Practice：批量异步任务处理系统设计实现
简介：golang redis hyperloglog 基数统计，hyperloglog 统计 UV 基数，海量数据去重统计，极低内存开销。
 | 原文链接：http://wiki.083dms.asia/arts/295349.Doc

原标题：golang 系统设计短信发送限流降级
简介：Git 子模块更新代码不全修复，正确更新 Git 子模块，拉取子模块完整代码，解决子模块目录为空问题。
 | 原文链接：http://wiki.083dms.asia/arts/803574.Doc

原标题：坑点：Git工作区换行符CRLF/LF跨平台坑
简介：golang mqtt 客户端 go 开发物联网，paho.mqtt.golang 实现 mqtt 客户端，物联网设备消息收发。
 | 原文链接：http://wiki.083dms.asia/arts/386087.Doc

原标题：golang 系统设计缓存 key 命名规范最佳实践
简介：golang go 泛型约束与类型集合，泛型 type set 约束，限制泛型支持类型，写出安全泛型代码。
 | 原文链接：http://wiki.083dms.asia/arts/232893.Doc

原标题：安全笔记：第三方SDK安全风险评估要点
简介：golang cron 任务漂移问题处理，cron 任务执行超时导致任务漂移，通过分布式锁防止任务重叠执行。
 | 原文链接：http://wiki.083dms.asia/arts/644733.Doc

原标题：Git 误提交撤销回退实操教程
简介：golang rsa 非对称加密签名验签，RSA 非对称加密与签名验签，实现非对称安全通信。
 | 原文链接：http://wiki.083dms.asia/arts/599644.Doc

原标题：golang 系统设计数据库基准压测简单思路
简介：golang go embed 嵌入静态资源文件，使用 go embed 把静态文件编译进二进制，单文件部署携带静态资源。
 | 原文链接：http://wiki.083dms.asia/arts/908351.Doc

原标题：性能笔记：线程池参数调优任务队列策略
简介：业务错误码完整落地实践，落地完整业务错误码，枚举全部业务异常，统一返回，配套文档说明。
 | 原文链接：http://wiki.083dms.asia/arts/102688.Doc

原标题：Practice：模拟网络抖动验证服务容错能力
简介：上传接口跨域配置特殊适配，针对文件上传接口，适配复杂请求，修复上传场景下跨域失效问题。
 | 原文链接：http://wiki.083dms.asia/arts/532703.Doc

四、架构设计｜Architecture
原标题：本地数据库开发环境搭建指南
简介：golang sync.Cond 条件变量使用，Cond 条件变量协程等待唤醒，复杂并发同步场景。
 | 原文链接：http://wiki.083dms.asia/arts/969122.Doc

原标题：golang 系统设计锁优化减少竞争提升吞吐
简介：golang go 死锁检测工具，静态检查、运行检测，发现 channel 锁导致死锁问题。
 | 原文链接：http://wiki.083dms.asia/arts/150761.Doc

原标题：Hands‑on：模拟RPC超时重试业务异常场景
简介：依赖安装失败全方位排错，从网络、镜像源、权限、版本多角度，定位依赖安装失败，给出对应修复手段。
 | 原文链接：http://wiki.083dms.asia/arts/167821.Doc

原标题：Hands‑on：简易跨进程通信demo开发实践
简介：golang 消息死信处理业务逻辑，Go 实现死信队列逻辑，消费失败消息转入死信，不阻塞正常消息队列。
 | 原文链接：http://wiki.083dms.asia/arts/484429.Doc

原标题：Troubleshooting：k8s镜像拉取失败镜像仓库网络问题
简介：时间同步修复令牌提前过期，服务器时间不同步导致 JWT 令牌提前过期，同步系统时间解决异常。
 | 原文链接：http://wiki.083dms.asia/arts/020063.Doc

原标题：安全笔记：XSS跨站脚本攻击防御落地实践
简介：golang kafka 同步异步消费对比，对比 Kafka 同步消费异步消费，分析优缺点，业务选型参考。
 | 原文链接：http://wiki.083dms.asia/arts/317428.Doc

原标题：性能复盘：数据库回滚日志过大性能影响优化
简介：线程调度优化减少上下文切换，优化线程数量，减少线程频繁切换，降低 CPU 上下文切换开销。
 | 原文链接：http://wiki.083dms.asia/arts/458215.Doc

原标题：golang 系统设计逻辑删除物理删除选型对比
简介：golang clickhouse go 客户端数据写入，clickhouse‑go 客户端写入查询，海量时序数据分析业务。
 | 原文链接：http://wiki.083dms.asia/arts/406733.Doc

原标题：golang 分布式上下文传递方案
简介：golang 半关闭 tcp 连接 shutdown，tcp 连接 shutdown 半关闭，单向关闭读或者写，理解 tcp 关闭流程。
 | 原文链接：http://wiki.083dms.asia/arts/681569.Doc

原标题：Hands‑on：简易的事件订阅发布组件开发实践
简介：golang 协程数量监控统计方案，统计运行中 goroutine 数量，监控协程泄露，协程数量异常及时告警。
 | 原文链接：http://wiki.083dms.asia/arts/648238.Doc

原标题：golang 接口限流中间件开发
简介：golang sync.Pool 对象池复用对象，sync.Pool 复用临时对象，减少内存分配，降低 GC 频率提升性能。
 | 原文链接：http://wiki.083dms.asia/arts/085630.Doc

原标题：Performance：大事务拆分，减少锁持有时间
简介：golang sort 稳定排序 Stable，稳定排序保留相等元素原有顺序，业务需要稳定排序场景。
 | 原文链接：http://wiki.083dms.asia/arts/568717.Doc

原标题：golang 系统设计告警风暴抑制合并降噪方案
简介：包管理器依赖冲突解决方案，分析依赖冲突产生根源，提供版本调整、锁定依赖等手段，解决项目依赖报错问题。
 | 原文链接：http://wiki.083dms.asia/arts/788365.Doc

原标题：golang mysql 主从同步延迟兼容
简介：golang go 服务压测前后性能对比，压测记录 QPS 延迟，优化前后对比，验证优化效果。
 | 原文链接：http://wiki.083dms.asia/arts/500144.Doc

原标题：任务执行锁防止并发重复调度
简介：golang go mod exclude 排除依赖版本，exclude 排除有问题依赖版本，规避有 bug 的第三方包。
 | 原文链接：http://wiki.083dms.asia/arts/728983.Doc

原标题：golang 系统设计内部服务熔断降级配置思路
简介：线上接口超时故障排查思路，从网络、数据库、代码逻辑逐层排查接口超时，定位慢请求根因。
 | 原文链接：http://wiki.083dms.asia/arts/847077.Doc

原标题：配置外部化线上部署防错误
简介：golang go 爬虫 robots 协议遵守，解析 robots.txt 规则，控制爬虫抓取范围，合规采集网页数据。
 | 原文链接：http://wiki.083dms.asia/arts/345258.Doc

原标题：golang k8s 滚动更新回滚策略
简介：golang 自定义 pprof 扩展业务指标，扩展 pprof，输出业务自定义指标，结合性能数据分析业务状态。
 | 原文链接：http://wiki.083dms.asia/arts/811884.Doc

?
