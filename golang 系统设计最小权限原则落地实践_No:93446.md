最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计最小权限原则落地实践
简介：限流规则误拦截正常请求修复，修正限流规则阈值，避免合法用户被限流拦截，兼顾防护与可用性。
 | 原文链接：www.blog.qm-i.cn/Article/details/6523270.shtml

原标题：golang mysql innodb 事务隔离级别
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：www.blog.qm-i.cn/Article/details/9051785.shtml

原标题：golang 系统设计内部服务熔断降级配置思路
简介：限流组件计数器令牌桶模式实现，实现计数器、令牌桶两种限流算法，封装可复用限流组件。
 | 原文链接：www.blog.qm-i.cn/Article/details/8308978.shtml

原标题：性能笔记：HTTP连接复用性能优化实践
简介：golang 定时任务任务持久化存储，定时任务持久化到数据库，服务重启任务不丢失，动态管理任务。
 | 原文链接：www.blog.qm-i.cn/Article/details/5235898.shtml

原标题：golang 系统设计 api 接口兼容性设计原则
简介：浏览器缓存强制刷新方案，设置 HTTP 缓存头，处理浏览器缓存旧静态资源，让用户加载更新后的页面。
 | 原文链接：www.blog.qm-i.cn/Article/details/6720575.shtml

原标题：Performance：避免循环查询N+1问题完整优化
简介：消息队列消费堆积扩容处理，消息大量堆积时，扩容消费实例，优化消费逻辑，加快消息处理速度。
 | 原文链接：www.blog.qm-i.cn/Article/details/8265304.shtml

原标题：空指针异常判空容错处理
简介：golang ssh 客户端远程命令执行，golang ssh 连接远程服务器，执行 shell 命令，获取命令输出结果。
 | 原文链接：www.blog.qm-i.cn/Article/details/9315276.shtml

原标题：线上异常：布隆过滤器误判造成业务逻辑异常
简介：Cookie Session 会话状态管理，讲解 Cookie 与 Session 原理，理解登录状态保存，实现服务端会话管理逻辑。
 | 原文链接：www.blog.qm-i.cn/Article/details/5824177.shtml

原标题：OpenSource：开源项目README高质量编写指南
简介：golang redis 事务 multi exec 使用，Redis 事务 multi exec 实现批量命令原子执行，理解 redis 事务隔离特性。
 | 原文链接：www.blog.qm-i.cn/Article/details/2459604.shtml

原标题：golang 系统设计 http1.1 http2 核心差异讲解
简介：前端水印防信息泄露实现，实现网页水印功能，页面叠加用户信息水印，防止页面截图信息外泄。
 | 原文链接：www.blog.qm-i.cn/Article/details/9436832.shtml

原标题：项目实践：搭建个人API网关最小实现版本
简介：golang 布隆过滤器实现去重，Go 实现布隆过滤器，海量数据去重，节省内存开销，提升判断效率。
 | 原文链接：www.blog.qm-i.cn/Article/details/8983046.shtml

原标题：调优方案：CDN优化静态资源访问延迟
简介：多操作系统开发兼容处理，解决不同系统路径、换行符、权限差异，保证项目跨平台正常运行。
 | 原文链接：www.blog.qm-i.cn/Article/details/5270384.shtml

原标题：排错：本地[localhost](https://localhost)可以，127001访问失败
简介：服务启动依赖顺序配置正确，配置服务启动依赖关系，保证依赖服务就绪之后再启动当前业务服务。
 | 原文链接：www.blog.qm-i.cn/Article/details/6691884.shtml

原标题：HelloEnv：多操作系统环境变量配置汇总
简介：golang gin 获取客户端真实 IP，多层代理场景正确拿到用户真实访问 IP，避免拿到网关代理内网地址。
 | 原文链接：www.blog.qm-i.cn/Article/details/8715011.shtml

原标题：性能复盘：慢SQL定位、分析、改写完整案例
简介：golang go race 竞态检测工具，‑race 检测数据竞争，编译运行检测并发读写数据竞争 bug。
 | 原文链接：www.blog.qm-i.cn/Article/details/9053332.shtml

原标题：安全笔记：XSS跨站脚本攻击防御落地实践
简介：golang 系统调用跟踪 strace 排查 go 程序，strace 跟踪系统调用，定位文件网络 IO 慢的底层原因。
 | 原文链接：www.blog.qm-i.cn/Article/details/8600456.shtml

原标题：安全复盘：Redis命令注入风险防护手段
简介：Git commit 钩子提交规范校验，配置 Git 提交钩子，提交代码自动校验提交信息格式，规范提交记录。
 | 原文链接：www.blog.qm-i.cn/Article/details/1980864.shtml

原标题：golang 系统设计 http 接口基准测试实操示例
简介：golang os 环境变量读取设置，os.Getenv os.Setenv os.Unsetenv 读写环境变量，环境变量多值处理。
 | 原文链接：www.blog.qm-i.cn/Article/details/6418681.shtml

原标题：部署实践：容器优雅停机配置处理信号
简介：接口签名验签完整安全方案，一套完整接口签名方案，包含签名生成、请求携带、服务端验签校验。
 | 原文链接：www.blog.qm-i.cn/Article/details/4500187.shtml

原标题：Docker 容器时区错误修复方案
简介：golang fasthttp 高性能 http 库使用，fasthttp 高性能 http 实现，适合超高 QPS 场景，对比 net/http 差异。
 | 原文链接：www.blog.qm-i.cn/Article/details/6897606.shtml

原标题：golang mysql exists in 性能对比
简介：golang 图片处理 go 图片裁剪压缩，golang 图像处理库，图片缩放裁剪水印，服务端图片处理。
 | 原文链接：www.blog.qm-i.cn/Article/details/0495013.shtml

原标题：Git LFS 大文件推送失败解决
简介：golang go work 多模块本地开发，go work 多模块本地同时开发，本地模块互相引用，无需推送仓库。
 | 原文链接：www.blog.qm-i.cn/Article/details/8248896.shtml

原标题：安全实践：生产环境禁止开启debug调试模式
简介：golang go 程序版本号内置编译注入，编译时注入 git commit 版本号，程序运行输出版本便于排查。
 | 原文链接：www.blog.qm-i.cn/Article/details/8970384.shtml

原标题：golang 系统设计业务指标系统指标定义思路
简介：空指针异常判空容错处理，讲解空指针产生场景，规范判空逻辑，增加容错，避免空指针直接造成程序崩溃。
 | 原文链接：www.blog.qm-i.cn/Article/details/8235761.shtml

原标题：架构笔记：数据库连接池架构参数调优思路
简介：数据库死锁成因规避方案，讲解数据库死锁产生条件，给出业务层面规避手段，减少死锁事件发生。
 | 原文链接：www.blog.qm-i.cn/Article/details/4048214.shtml

原标题：golang 系统设计网关鉴权鉴权转发流程讲解
简介：golang nil channel 阻塞特性，nil channel 读写永久阻塞，理解 nil channel 行为做逻辑控制。
 | 原文链接：www.blog.qm-i.cn/Article/details/1768549.shtml

原标题：golang channel 通道并发处理
简介：golang 信号量控制并发数量，使用信号量控制并发，限制同时执行任务数量，保护下游资源。
 | 原文链接：www.blog.qm-i.cn/Article/details/2428239.shtml

原标题：golang 系统设计多租户数据隔离方案
简介：golang go 应用内存使用优化手段，减少对象分配，复用对象，降低 GC 压力，减少 GC 停顿时间。
 | 原文链接：www.blog.qm-i.cn/Article/details/6518939.shtml

原标题：golang redis lua 脚本原子操作
简介：golang mongodb go 驱动实操教程，mongo‑go‑driver 操作 mongodb，文档增删改查聚合查询。
 | 原文链接：www.blog.qm-i.cn/Article/details/2301173.shtml

原标题：golang k8s helm chart 简单编写
简介：跨库查询性能优化处理，减少跨库关联查询，做数据冗余或者中间表，规避跨库查询性能低下。
 | 原文链接：www.blog.qm-i.cn/Article/details/5463095.shtml

原标题：优化实践：预加载与懒加载业务场景取舍
简介：golang defer panic 异常处理，理解 defer 延迟执行，panic 恐慌捕获，实现函数资源释放异常保护。
 | 原文链接：www.blog.qm-i.cn/Article/details/2049233.shtml

原标题：调试工具断点调试变量查看技巧
简介：golang http 服务性能优化调参，调优 Go HTTP 服务参数，调整连接池，提升服务并发吞吐能力。
 | 原文链接：www.blog.qm-i.cn/Article/details/9638457.shtml

原标题：golang 系统设计 rest 错误返回格式统一规范
简介：调试工具断点调试变量查看技巧，演示断点设置、变量监视、调用栈查看，借助调试工具高效排查业务逻辑错误。
 | 原文链接：www.blog.qm-i.cn/Article/details/2131753.shtml

原标题：方案设计：分布式分页查询架构难点处理
简介：golang os 环境变量读取设置，os.Getenv os.Setenv os.Unsetenv 读写环境变量，环境变量多值处理。
 | 原文链接：www.blog.qm-i.cn/Article/details/4165869.shtml

原标题：Troubleshoot：批量导入数据，事务过大回滚日志暴涨
简介：golang 协程数量监控统计方案，统计运行中 goroutine 数量，监控协程泄露，协程数量异常及时告警。
 | 原文链接：www.blog.qm-i.cn/Article/details/5497770.shtml

原标题：HTTPS 证书过期更新操作
简介：golang context.Background 与 TODO 区别，Background 主流程根上下文，TODO 不确定用哪个上下文时使用。
 | 原文链接：www.blog.qm-i.cn/Article/details/5423284.shtml

原标题：Troubleshooting：Nginx缓冲区过小大文件上传失败
简介：service‑worker 离线缓存实践，使用 ServiceWorker 实现静态资源离线缓存，弱网环境页面依然可访问。
 | 原文链接：www.blog.qm-i.cn/Article/details/7980501.shtml

原标题：调优方案：gzip压缩开启降低网络传输体积
简介：ServiceWorker 缓存页面更新清理，处理 ServiceWorker 缓存，实现页面新版本更新，用户可以加载最新页面。
 | 原文链接：www.blog.qm-i.cn/Article/details/5450163.shtml

原标题：golang 系统设计技术文档编写最佳实践
简介：golang go 服务蓝绿发布实践思路，蓝绿两套实例，流量一键切换，回滚快速降低发布风险。
 | 原文链接：www.blog.qm-i.cn/Article/details/7532787.shtml

原标题：文件读写与异常捕获代码示例
简介：golang excel 生成导出高性能方案，excelize 流式生成 excel，百万行数据导出，规避内存溢出。
 | 原文链接：www.blog.qm-i.cn/Article/details/4843200.shtml


二、踩坑排错｜Troubleshooting
原标题：golang 系统设计缓存空值防止缓存穿透实现
简介：golang 网卡 ip 读取网络信息获取，程序读取本机网卡 IP，多网卡环境筛选业务使用 IP 地址。
 | 原文链接：www.blog.qm-i.cn/Article/details/3496041.shtml

原标题：golang 工具函数库封装思路
简介：golang tcp_NODELAY 关闭延迟发送，设置 tcp_NODELAY，关闭 Nagle 算法，降低小包请求延迟。
 | 原文链接：www.blog.qm-i.cn/Article/details/6191742.shtml

原标题：golang 系统设计缓存 key 淘汰雪崩防护思路
简介：golang 配置文件热加载监听变更，监听配置文件改动，自动重新加载配置，业务即时生效无需重启。
 | 原文链接：www.blog.qm-i.cn/Article/details/7178441.shtml

原标题：golang redis 布隆过滤器安装使用
简介：golang loki 日志收集 go 服务集成，日志输出适配 loki，标签携带 traceId，日志集中检索排查问题。
 | 原文链接：www.blog.qm-i.cn/Article/details/6454600.shtml

原标题：实战：gRPC服务编写客户端服务端完整demo
简介：手写简易 RPC 服务通信原型，手写极简 RPC 原型，理解服务注册、网络传输、方法调用底层逻辑。
 | 原文链接：www.blog.qm-i.cn/Article/details/0997058.shtml

原标题：golang gin 框架接口开发实战
简介：数据库分表路由写入分片修正，修复分表路由逻辑，保证数据写入正确分片，不会出现数据丢失错乱。
 | 原文链接：www.blog.qm-i.cn/Article/details/5799577.shtml

原标题：SSH 密钥配置 GitHub 免密登录
简介：golang 命令行交互 cobra 开发 cli，cobra 库开发功能完善命令行工具，子命令参数标志解析。
 | 原文链接：www.blog.qm-i.cn/Article/details/4571351.shtml

原标题：golang k8s configmap secret 配置
简介：golang raw socket 底层网络报文收发，raw socket 收发原始网络报文，做网络抓包数据包处理。
 | 原文链接：www.blog.qm-i.cn/Article/details/2645193.shtml

原标题：分布式事务最终一致性实现
简介：golang csv 百万级数据导入数据库，流式读取 csv 分批写入数据库，避免一次性加载全部数据。
 | 原文链接：www.blog.qm-i.cn/Article/details/2084077.shtml

原标题：从零学习基础的接口请求与参数处理
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：www.blog.qm-i.cn/Article/details/2495750.shtml

原标题：坑点：缓存过期策略不当引发业务异常
简介：开发环境变量配置全平台教程，区分 Windows、macOS、Linux 系统，讲解环境变量配置、加载优先级与常见失效原因。
 | 原文链接：www.blog.qm-i.cn/Article/details/5938042.shtml

原标题：golang gitlab runner 部署与注册实操
简介：nodejs 多进程任务分发处理，多进程拆分处理 CPU 密集任务，主进程分发任务，利用多核提升处理速度。
 | 原文链接：www.blog.qm-i.cn/Article/details/7429349.shtml

原标题：HelloWorld：快速上手新项目最小可运行示例
简介：golang minio 私有对象存储开发，minio s3 对象存储，bucket 管理，文件上传下载权限设置。
 | 原文链接：www.blog.qm-i.cn/Article/details/1213832.shtml

原标题：WSL 搭建 Windows Linux 开发环境
简介：系统字符集统一乱码修复，统一数据库、程序、操作系统字符集，解决中文乱码显示异常问题。
 | 原文链接：www.blog.qm-i.cn/Article/details/0197106.shtml

原标题：百万数据 Excel 导出内存优化
简介：golang go 泛型实现通用数据结构，泛型实现通用栈队列，复用逻辑支持多种数据类型。
 | 原文链接：www.blog.qm-i.cn/Article/details/6137270.shtml

原标题：开发记录：日志脱敏防止敏感信息输出实践
简介：数据库 utf8mb4 支持 emoji 存储，数据库字段设置 utf8mb4 字符集，完整支持 emoji 表情存储入库。
 | 原文链接：www.blog.qm-i.cn/Article/details/6127388.shtml

原标题：golang k8s 镜像拉取密钥配置
简介：golang 换行符统一处理，文本文件读写统一换行符，规避不同系统换行符带来解析异常。
 | 原文链接：www.blog.qm-i.cn/Article/details/9538353.shtml

原标题：实战：对象存储断点续传下载实践
简介：golang udp 服务端客户端开发示例，golang 实现 UDP 服务收发数据包，实现 udp 协议通信程序。
 | 原文链接：www.blog.qm-i.cn/Article/details/9150901.shtml

原标题：golang 接口请求日志记录中间件
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：www.blog.qm-i.cn/Article/details/8676193.shtml

原标题：golang 系统设计日志脱敏敏感字段过滤处理
简介：golang 优雅关闭 grpc 服务示例，gRPC 服务优雅关闭，等待现有请求处理完成再停止服务。
 | 原文链接：www.blog.qm-i.cn/Article/details/9112590.shtml

原标题：HelloGitWorkflow：理解简单主干开发流程
简介：MySQL 慢查询索引优化实战，抓取慢查询 SQL，分析执行计划，新增或者调整索引，提升 SQL 执行速度。
 | 原文链接：www.blog.qm-i.cn/Article/details/6824489.shtml

原标题：golang redis 客户端业务使用
简介：golang 单元测试 table‑driven，表格驱动单元测试写法，批量输入多组测试用例，简化单元测试代码。
 | 原文链接：www.blog.qm-i.cn/Article/details/2166494.shtml

原标题：Practice：实现业务操作日志记录中间件实践
简介：YAML 配置文件语法快速上手，讲解 YAML 基础语法、缩进规则，编写项目配置文件，规避语法错误引发程序异常。
 | 原文链接：www.blog.qm-i.cn/Article/details/7732622.shtml

原标题：golang 系统设计开源项目自动化 ci 配置示例
简介：大事务拆分防止连接池耗尽，将执行时间很长的大事务拆分为小事务，减少事务占用连接时长。
 | 原文链接：www.blog.qm-i.cn/Article/details/8961194.shtml

原标题：nodejs http 服务性能调优实战
简介：无用对象回收抑制内存上涨，优化对象生命周期，及时释放不再使用对象，抑制内存持续不断增长。
 | 原文链接：www.blog.qm-i.cn/Article/details/3893637.shtml

原标题：开发生产环境资源路径统一
简介：golang 表单文件大小限制配置，限制表单上传文件最大体积，拦截超大文件上传请求，保护服务。
 | 原文链接：www.blog.qm-i.cn/Article/details/7521317.shtml

原标题：排错：DockerCompose依赖顺序启动顺序坑
简介：golang benchmark 参数‑bench‑mem 统计内存分配，benchmark 开启内存统计，观察内存分配次数大小。
 | 原文链接：www.blog.qm-i.cn/Article/details/7863919.shtml

原标题：复盘总结：线上故障完整复盘报告模板示例
简介：开源项目本地运行排错完整清单，汇总开源项目拉取后运行失败各类问题，给出排查思路，快速解决本地启动异常。
 | 原文链接：www.blog.qm-i.cn/Article/details/1772322.shtml

原标题：nodejs 多进程任务分发处理
简介：golang json 自定义 MarshalJSON UnmarshalJSON，自定义 json 序列化反序列化逻辑，处理特殊格式字段。
 | 原文链接：www.blog.qm-i.cn/Article/details/6196747.shtml

原标题：实战：Nginx配置静态站点、反向代理、负载均衡
简介：nodejs 单元测试 jest 实操教程，Jest 单元测试实操，编写测试用例，mock 依赖，验证业务逻辑正确性。
 | 原文链接：www.blog.qm-i.cn/Article/details/0898991.shtml

原标题：golang 系统设计故障定位排查通用步骤方法论
简介：集成测试业务流程编写示例，编写业务流程集成测试，覆盖完整业务链路，验证模块之间协同工作是否正常。
 | 原文链接：www.blog.qm-i.cn/Article/details/6378467.shtml

原标题：golang k8s service 服务暴露几种类型
简介：接口签名验签完整安全方案，一套完整接口签名方案，包含签名生成、请求携带、服务端验签校验。
 | 原文链接：www.blog.qm-i.cn/Article/details/1257272.shtml

原标题：nodejs 定时任务生产环境避坑
简介：网关超时时间调优后端等待，调大网关向后端转发请求超时时间，给后端业务充足处理时间。
 | 原文链接：www.blog.qm-i.cn/Article/details/1040333.shtml

原标题：部署实践：HTTPS证书自动续期配置实践
简介：golang grpc 负载均衡客户端实现，grpc 客户端负载均衡，轮询随机权重，分发请求到多个服务实例。
 | 原文链接：www.blog.qm-i.cn/Article/details/0125401.shtml

原标题：入门实践：搭建简单的热更新开发环境
简介：超大数据集分页性能优化方案，对比不同分页方案，针对海量数据集做分页性能优化，解决越翻越慢。
 | 原文链接：www.blog.qm-i.cn/Article/details/0352262.shtml

原标题：golang k8s 基础概念 pod deployment
简介：golang 限制 multipart 内存大小，设置 MaxMemory，大文件写入磁盘临时文件防止内存暴涨。
 | 原文链接：www.blog.qm-i.cn/Article/details/7494458.shtml

原标题：实战项目：GitSubmodule管理多仓库实践
简介：golang 静态编译缩小镜像体积，Go 程序静态编译，不依赖系统库，产出单二进制文件，缩小镜像。
 | 原文链接：www.blog.qm-i.cn/Article/details/0252717.shtml

原标题：Hands‑on：简易频率统计组件Redis实现
简介：简易网关请求路由过滤模拟，模拟网关基础能力，实现请求路由转发、简单过滤，理解网关核心工作逻辑。
 | 原文链接：www.blog.qm-i.cn/Article/details/9478569.shtml

原标题：新手向：npm/pip/maven依赖版本冲突入门排查
简介：golang errgroup 协程组错误处理，errgroup 捕获协程错误，context 取消剩余协程，简化并发任务。
 | 原文链接：www.blog.qm-i.cn/Article/details/3852791.shtml

原标题：Performance：避免循环查询N+1问题完整优化
简介：golang atomic.Value 存储任意类型数据，atomic.Value 安全存储读取任意类型，配置热更新常用。
 | 原文链接：www.blog.qm-i.cn/Article/details/1538863.shtml

三、实战开发｜Practice
原标题：零基础理解版本控制核心概念与工作流
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：www.blog.qm-i.cn/Article/details/4268838.shtml

原标题：项目语义化版本号规范管理
简介：golang hystrix 模式简易熔断实现，简易熔断组件，错误率达到阈值触发熔断，快速失败保护下游。
 | 原文链接：www.blog.qm-i.cn/Article/details/4723386.shtml

原标题：运维笔记：服务器磁盘内存监控告警配置
简介：golang 程序崩溃 core dump 生成调试，开启 core dump，程序崩溃生成转储文件，事后分析崩溃原因。
 | 原文链接：www.blog.qm-i.cn/Article/details/9383221.shtml

原标题：golang 系统设计分布式会话方案对比
简介：Nginx 透传真实客户端 IP 配置，配置 Nginx 把真实客户端 IP 传递后端服务，后端拿到访问者真实 IP。
 | 原文链接：www.blog.qm-i.cn/Article/details/7858722.shtml

原标题：Redis 热点 key 拆分降低集群压力
简介：golang tar gz 压缩解压处理，tar.gz 归档压缩解压，服务端日志备份、文件打包场景使用。
 | 原文链接：www.blog.qm-i.cn/Article/details/9545192.shtml

原标题：golang redis zset 延时队列实现
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：www.blog.qm-i.cn/Article/details/2662936.shtml

原标题：golang 系统设计缓存降级开关快速切库实现
简介：golang prometheus 指标埋点开发，业务埋点计数器、仪表盘、直方图，对接 prometheus 采集监控指标。
 | 原文链接：www.blog.qm-i.cn/Article/details/2328804.shtml

原标题：golang 系统设计消息体序列化选型对比
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：www.blog.qm-i.cn/Article/details/5950835.shtml

原标题：调优方案：静态资源缓存头Cache‑Control优化
简介：Git 标签版本标记发布管理，使用 Git 标签标记项目版本，打标签推送远程，用于版本发布、版本回溯。
 | 原文链接：www.blog.qm-i.cn/Article/details/6574022.shtml

原标题：安全笔记：JWT安全风险，签名泄露过期控制
简介：golang raw socket 底层网络报文收发，raw socket 收发原始网络报文，做网络抓包数据包处理。
 | 原文链接：www.blog.qm-i.cn/Article/details/5250030.shtml

原标题：性能笔记：锁优化减少竞争提升并发吞吐
简介：本地数据库开发环境搭建指南，讲解数据库安装配置、账号权限设置、连接测试，快速搭建用于开发调试的数据库实例。
 | 原文链接：www.blog.qm-i.cn/Article/details/4927722.shtml

原标题：文件句柄上限调整上传随机失败
简介：golang go 程序守护进程实现思路，go 程序不做 daemon 化，依靠 systemd pm2 k8s 实现进程守护。
 | 原文链接：www.blog.qm-i.cn/Article/details/6148732.shtml

原标题：实战：Redis过期回调实现业务事件通知实践
简介：golang 分布式事务 seata go 客户端，seata‑go 实现分布式事务，保证跨库业务数据最终一致性。
 | 原文链接：www.blog.qm-i.cn/Article/details/7102502.shtml

原标题：golang gorm 预加载关联查询优化
简介：进程线程并发基础概念讲解，区分进程与线程，讲解调度逻辑，理解并发执行原理，为高并发业务开发打基础。
 | 原文链接：www.blog.qm-i.cn/Article/details/4964192.shtml

原标题：Performance：缓存策略优化，降低数据库压力
简介：golang redis hash 结构业务实战，使用 Redis Hash 存储对象数据，适合对象字段频繁更新业务场景。
 | 原文链接：www.blog.qm-i.cn/Article/details/5578752.shtml

原标题：golang 系统设计 json 解析性能优化实操
简介：提交第一个开源 PR 完整流程，Fork 项目、修改代码、提交 Pull Request，讲解 PR 规范，提升合并通过率。
 | 原文链接：www.blog.qm-i.cn/Article/details/1234256.shtml

原标题：golang 系统设计单元测试编写原则最佳实践
简介：nodejs 多进程任务分发处理，多进程拆分处理 CPU 密集任务，主进程分发任务，利用多核提升处理速度。
 | 原文链接：www.blog.qm-i.cn/Article/details/8257903.shtml

原标题：Security：RPC调用身份认证安全加固
简介：Docker 容器网络不通排查，排查容器网络模式、端口映射、防火墙，解决容器之间、容器外部网络不通。
 | 原文链接：www.blog.qm-i.cn/Article/details/6698159.shtml

原标题：5分钟快速搭建个人技术文档站点
简介：golang 配置文件热加载监听变更，监听配置文件改动，自动重新加载配置，业务即时生效无需重启。
 | 原文链接：www.blog.qm-i.cn/Article/details/5542480.shtml

原标题：golang 系统设计基准测试 benchmark 编写
简介：golang os 文件权限 mode，os.FileMode 文件权限，读写执行权限位，跨平台权限注意事项。
 | 原文链接：www.blog.qm-i.cn/Article/details/8502894.shtml

原标题：接口压测定位系统性能瓶颈
简介：golang net/http 超时全套配置，完整配置 Go HTTP 服务读写空闲超时，全方位防止请求挂住。
 | 原文链接：www.blog.qm-i.cn/Article/details/2638355.shtml

原标题：golang 系统设计告警规则阈值设置方法论
简介：golang 速率限制令牌桶实现，Go 实现令牌桶限流算法，可复用限流器，控制业务调用速率。
 | 原文链接：www.blog.qm-i.cn/Article/details/9689192.shtml

原标题：零基础理解JSON、XML数据格式处理
简介：golang 内存 dump 线上堆快照采集，线上生成内存 dump 文件，线下分析，定位内存泄漏问题。
 | 原文链接：www.blog.qm-i.cn/Article/details/6686554.shtml

原标题：golang 系统设计数据库连接池调优实践
简介：golang channel 通道并发处理，讲解 Channel 用法，协程之间通过通道传递数据，做并发同步控制。
 | 原文链接：www.blog.qm-i.cn/Article/details/4546469.shtml

原标题：golang excel 简单读写操作示例
简介：golang io.MultiReader MultiWriter 拼接流，多个 reader 拼接，多 writer 同时写入一份数据。
 | 原文链接：www.blog.qm-i.cn/Article/details/6325628.shtml

原标题：golang 系统设计 graphql 接口优缺点梳理
简介：新手参与开源社区贡献指南，介绍开源社区基础规则，讲解阅读 issue、提交 PR 流程，指导开发者参与开源贡献。
 | 原文链接：www.blog.qm-i.cn/Article/details/8028362.shtml

原标题：站内邮件消息通知功能开发
简介：项目构建脚本编译打包解析，解读项目构建脚本，理清编译、压缩、资源复制流程，理解打包后产物如何生成。
 | 原文链接：www.blog.qm-i.cn/Article/details/7838497.shtml

原标题：代理 HTTPS 证书访问异常处理
简介：golang md5 sha 加密工具实现，实现 MD5、SHA 哈希工具，做数据摘要，用于签名校验场景。
 | 原文链接：www.blog.qm-i.cn/Article/details/2984499.shtml

原标题：端口占用访问失败排查方案
简介：手写简易 RPC 服务通信原型，手写极简 RPC 原型，理解服务注册、网络传输、方法调用底层逻辑。
 | 原文链接：www.blog.qm-i.cn/Article/details/8001077.shtml

原标题：从零学习简单分布式ID生成思路
简介：golang go 锁竞争导致 CPU 飙升，识别锁竞争场景，减少锁粒度，优化并发逻辑降低 CPU 开销。
 | 原文链接：www.blog.qm-i.cn/Article/details/6120946.shtml

原标题：golang redis zset 延时队列实现
简介：golang grpc 负载均衡客户端实现，grpc 客户端负载均衡，轮询随机权重，分发请求到多个服务实例。
 | 原文链接：www.blog.qm-i.cn/Article/details/7126987.shtml

原标题：golang docker 私有仓库搭建使用
简介：golang docker 多阶段构建 go 镜像，Go 项目 Docker 多阶段构建，编译与运行阶段分离，大幅度缩减最终镜像体积，提升镜像分发效率。
 | 原文链接：www.blog.qm-i.cn/Article/details/8647907.shtml

原标题：golang 系统设计数据库索引设计方法论
简介：消息消费重试次数限制防爆炸，限制消息最大重试次数，防止失败消息无限重试造成消息爆炸堆积。
 | 原文链接：www.blog.qm-i.cn/Article/details/8934261.shtml

原标题：网关集成鉴权限流日志一体化
简介：golang os 环境变量读取设置，os.Getenv os.Setenv os.Unsetenv 读写环境变量，环境变量多值处理。
 | 原文链接：www.blog.qm-i.cn/Article/details/7532889.shtml

原标题：golang 系统设计内网外网服务隔离方案
简介：golang 单元测试 mock http 请求，mock HTTP 外部接口，单元测试不依赖外部网络，保证用例稳定运行。
 | 原文链接：www.blog.qm-i.cn/Article/details/8198739.shtml

原标题：git rebase 整理提交历史实操
简介：Git 分支管理多人协作实战教程，详解分支创建、合并、冲突处理，适配团队开发场景，规范多人协同代码工作流。
 | 原文链接：www.blog.qm-i.cn/Article/details/0852454.shtml

原标题：golang 链路追踪简易实现方案
简介：WebSocket 双向通信 demo 开发，搭建简易 WebSocket 服务，实现客户端服务端双向消息推送，理解实时通信原理。
 | 原文链接：www.blog.qm-i.cn/Article/details/0432901.shtml

原标题：Practice：实现数据库连接池简易模拟实现
简介：git stash 代码暂存切换分支，使用 stash 暂存未提交代码，切换其他分支处理紧急任务，再恢复原有工作进度。
 | 原文链接：www.blog.qm-i.cn/Article/details/4326890.shtml

原标题：golang 错误处理最佳实践汇总
简介：golang os 文件权限 mode，os.FileMode 文件权限，读写执行权限位，跨平台权限注意事项。
 | 原文链接：www.blog.qm-i.cn/Article/details/1499910.shtml

原标题：从零搭建简单的身份登录模拟示例
简介：任务执行锁防止并发重复调度，增加任务执行锁，多实例环境，防止同一个定时任务并发多次运行。
 | 原文链接：www.blog.qm-i.cn/Article/details/5318599.shtml

四、架构设计｜Architecture
原标题：系统文件描述符上限调大
简介：全局本地依赖隔离冲突规避，区分全局依赖与项目本地依赖，隔离环境，防止全局包干扰项目运行。
 | 原文链接：www.blog.qm-i.cn/Article/details/9321055.shtml

原标题：golang 系统设计缓存故障降级处理方案
简介：golang go 爬虫代理池轮换使用，http 代理池轮换，请求自动切换代理 IP，突破访问限制。
 | 原文链接：www.blog.qm-i.cn/Article/details/9058975.shtml

原标题：Hands‑on：简易请求转发代理中间件实现
简介：程序预加载加快服务启动速度，把高频使用资源提前预加载，减少请求阶段初始化，加快服务启动。
 | 原文链接：www.blog.qm-i.cn/Article/details/8912523.shtml

原标题：进程线程并发基础概念讲解
简介：golang go proxy 私有代理配置，配置 go proxy 私有代理，加速依赖下载，内网环境构建项目。
 | 原文链接：www.blog.qm-i.cn/Article/details/3246601.shtml

原标题：golang redis 缓存穿透解决方案
简介：golang go 服务压测前后性能对比，压测记录 QPS 延迟，优化前后对比，验证优化效果。
 | 原文链接：www.blog.qm-i.cn/Article/details/1735244.shtml

原标题：golang 系统设计消息重试次数间隔策略设置
简介：百万数据 Excel 导出内存优化，优化大 Excel 导出逻辑，流式输出，避免一次性加载全部数据造成 OOM。
 | 原文链接：www.blog.qm-i.cn/Article/details/4932248.shtml

原标题：Debug：表单自动转义特殊字符业务逻辑出错
简介：golang redis bloom 布隆过滤器 go‑redis，go‑redis 布隆过滤器，海量数据判断是否存在，减少数据库查询。
 | 原文链接：www.blog.qm-i.cn/Article/details/4716270.shtml

原标题：开发复盘：避免大报文导致服务OOM优化实践
简介：Git 代码冲突正确处理方式，讲解冲突产生场景，演示冲突文件修改，正确合并代码，防止代码丢失。
 | 原文链接：www.blog.qm-i.cn/Article/details/4174323.shtml

原标题：配置外部化线上部署防错误
简介：容器内存扩容 OOM 被杀死修复，调高容器内存限制，优化程序内存占用，避免程序被 OOM 终止。
 | 原文链接：www.blog.qm-i.cn/Article/details/8354593.shtml

原标题：golang 系统设计内部服务调用超时设置要点
简介：文件锁正确使用避免死锁，合理使用文件锁，控制多进程访问同一个文件，规避文件锁死锁现象。
 | 原文链接：www.blog.qm-i.cn/Article/details/7453687.shtml

原标题：golang docker 部署 prometheus 整套
简介：nodejs 日志轮转生产环境配置，配置 Node 日志轮转切割，防止日志文件无限变大，适配生产环境。
 | 原文链接：www.blog.qm-i.cn/Article/details/5147641.shtml

原标题：内网测试服务搭建团队调试
简介：golang 配置文件多格式兼容加载，同时支持 yaml toml json 多种格式配置文件，灵活适配不同部署环境。
 | 原文链接：www.blog.qm-i.cn/Article/details/1062794.shtml

原标题：golang 系统设计配置回滚版本历史记录实现
简介：限流规则误拦截正常请求修复，修正限流规则阈值，避免合法用户被限流拦截，兼顾防护与可用性。
 | 原文链接：www.blog.qm-i.cn/Article/details/7222760.shtml

原标题：实战项目：Nginx限速、限流、防爬虫配置实践
简介：golang json omitempty 零值坑，omitempty 会忽略零值，区分业务是否需要输出零值字段。
 | 原文链接：www.blog.qm-i.cn/Article/details/1887324.shtml

原标题：部署实践：HTTPS证书自动续期配置实践
简介：golang 静态编译缩小镜像体积，Go 程序静态编译，不依赖系统库，产出单二进制文件，缩小镜像。
 | 原文链接：www.blog.qm-i.cn/Article/details/0544191.shtml

原标题：golang 跨域处理中间件编写
简介：程序性能指标 CPU 内存监控，讲解基础性能指标含义，简单实现监控采集，初步定位程序运行性能瓶颈。
 | 原文链接：www.blog.qm-i.cn/Article/details/7446315.shtml

原标题：golang 系统设计契约测试接口兼容性保障思路
简介：golang grpc 服务端流推送数据，服务端流式响应，服务端持续向客户端推送多条响应消息。
 | 原文链接：www.blog.qm-i.cn/Article/details/0401796.shtml

原标题：Architecture：API设计RESTful最佳实践与反模式
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：www.blog.qm-i.cn/Article/details/3289134.shtml

?
