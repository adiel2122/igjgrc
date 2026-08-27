最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计逻辑删除物理删除选型对比
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://book.welpfox.asia/blog/3408888.sHtMl

原标题：复盘总结：接口重构兼容旧版本改造复盘
简介：golang sort 稳定排序 Stable，稳定排序保留相等元素原有顺序，业务需要稳定排序场景。
 | 原文链接：http://book.welpfox.asia/blog/7679153.sHtMl

原标题：项目实践：搭建个人API网关最小实现版本
简介：golang go 模板缓存预编译模板，预编译 html 模板，程序启动加载，避免每次请求解析模板损耗性能。
 | 原文链接：http://book.welpfox.asia/blog/5598651.sHtMl

原标题：Troubleshooting：数据库索引失效，查询性能暴跌
简介：golang 结构体零值可用性原则，go 结构体尽量做到零值可用，不用初始化直接使用提升易用性。
 | 原文链接：http://book.welpfox.asia/blog/1697649.sHtMl

原标题：golang 系统设计监控告警体系搭建思路
简介：golang go 网络编程 net 包基础，net 包 tcp udp socket 编程，监听接收连接，读写数据。
 | 原文链接：http://book.welpfox.asia/blog/5679805.sHtMl

原标题：golang 系统设计 git 工作流本地开发提交流程
简介：golang http 服务优雅关闭完整示例，接收终止信号，停止接收新请求，等待现有请求处理完毕后退出服务。
 | 原文链接：http://book.welpfox.asia/blog/1141113.sHtMl

原标题：golang 系统设计文件存储选型对比
简介：nodejs 事件循环机制完整讲解，拆解 Node.js 事件循环各个阶段，理解异步回调执行顺序。
 | 原文链接：http://book.welpfox.asia/blog/2151862.sHtMl

原标题：实战项目：百万日志文件解析处理脚本实践
简介：时间同步修复令牌提前过期，服务器时间不同步导致 JWT 令牌提前过期，同步系统时间解决异常。
 | 原文链接：http://book.welpfox.asia/blog/8878890.sHtMl

原标题：golang 系统设计 protobuf json 性能对比
简介：golang goroutine 泄露检测告警实现，监控 goroutine 数量，突增触发告警，提早发现协程泄露。
 | 原文链接：http://book.welpfox.asia/blog/8486632.sHtMl

原标题：Security：业务操作审计日志安全留存
简介：golang arp 缓存读取操作，读取系统 arp 缓存表，获取 ip 对应的 mac 地址信息。
 | 原文链接：http://book.welpfox.asia/blog/7976775.sHtMl

原标题：golang 简易埋点日志上报实现
简介：极简方式搭建个人技术文档站点，使用轻量化工具快速部署文档站点，支持 markdown 编写，实现知识沉淀与对外分享。
 | 原文链接：http://book.welpfox.asia/blog/2451828.sHtMl

原标题：golang redis bitmap 位图统计实现
简介：nodejs 接口限流防刷代码实现，Node 层实现接口限流，限制 IP 访问频次，防护接口被恶意高频调用。
 | 原文链接：http://book.welpfox.asia/blog/7373083.sHtMl

原标题：GitHub Markdown 文档语法汇总
简介：编译打包产物依赖分析解读，分析打包之后产物组成，理清运行依赖文件，排查打包后缺失文件问题。
 | 原文链接：http://book.welpfox.asia/blog/8085940.sHtMl

原标题：架构笔记：业务系统反模式架构踩坑总结
简介：golang gin 获取客户端真实 IP，多层代理场景正确拿到用户真实访问 IP，避免拿到网关代理内网地址。
 | 原文链接：http://book.welpfox.asia/blog/9652379.sHtMl

原标题：踩坑记录：文件描述符不足，上传功能随机失败
简介：golang 协程泄露问题排查方法，识别 Go 协程泄露现象，分析泄露场景，给出排查定位协程泄露手段。
 | 原文链接：http://book.welpfox.asia/blog/3753525.sHtMl

原标题：静态资源 404 路径打包修复
简介：golang 云存储 s3 协议对象存储，go s3 客户端，兼容 minio 阿里云 oss，实现文件上传下载签名访问。
 | 原文链接：http://book.welpfox.asia/blog/9880500.sHtMl

原标题：Troubleshoot：异步异常未捕获，进程悄无声息退出
简介：业务错误码完整落地实践，落地完整业务错误码，枚举全部业务异常，统一返回，配套文档说明。
 | 原文链接：http://book.welpfox.asia/blog/1562464.sHtMl

原标题：Practice：实现请求大小限制中间件防护大报文
简介：nodejs 全局异常捕获进程防护，捕获未捕获异常与 Promise 拒绝，尽量保护进程不因为异常直接退出。
 | 原文链接：http://book.welpfox.asia/blog/2924960.sHtMl

原标题：golang 系统设计防重复提交实现
简介：CI 构建缓存加速编译速度，开启 CI 流水线依赖缓存，复用上一次构建依赖包，缩短流水线构建耗时。
 | 原文链接：http://book.welpfox.asia/blog/0007903.sHtMl

原标题：golang 系统设计 rest api 接口设计最佳实践
简介：日志输出规范防止磁盘爆满，控制日志输出量，配置日志切割轮转，避免日志文件无限增长占满磁盘。
 | 原文链接：http://book.welpfox.asia/blog/0013777.sHtMl

原标题：部署复盘：容器OOM问题完整排查流程
简介：golang kitex 超时重试熔断配置，kitex 配置调用超时、重试、熔断策略，保障微服务调用稳定性。
 | 原文链接：http://book.welpfox.asia/blog/3319823.sHtMl

原标题：限流组件计数器令牌桶模式实现
简介：golang redis 锁超时业务处理，Redis 分布式锁超时问题处理，锁续期逻辑，防止业务未完成锁提前释放。
 | 原文链接：http://book.welpfox.asia/blog/0997685.sHtMl

原标题：Issue：日志输出包含敏感信息造成泄露风险
简介：golang 本地消息表实现最终一致性，本地消息表 + 定时任务轮询，可靠消息实现分布式事务。
 | 原文链接：http://book.welpfox.asia/blog/6559070.sHtMl

原标题：golang mongodb 事务多文档使用
简介：数值类型溢出错乱问题修复，选择合适数值存储类型，处理数值溢出，避免数据存储错乱结果异常。
 | 原文链接：http://book.welpfox.asia/blog/1152550.sHtMl

原标题：golang 系统设计 protobuf json 性能对比
简介：极简方式搭建个人技术文档站点，使用轻量化工具快速部署文档站点，支持 markdown 编写，实现知识沉淀与对外分享。
 | 原文链接：http://book.welpfox.asia/blog/9987320.sHtMl

原标题：golang 错误包装 errors.wrap 用法
简介：react hooks 常见陷阱避坑指南，梳理 React Hooks 高频踩坑点，依赖数组、闭包陷阱，写出稳定组件。
 | 原文链接：http://book.welpfox.asia/blog/8413505.sHtMl

原标题：Security：业务操作审计日志安全留存
简介：golang 响应 body 流式返回大数据，http 流式输出数据，边生成边返回，无需在内存组装完整返回结果。
 | 原文链接：http://book.welpfox.asia/blog/3809978.sHtMl

原标题：golang 系统设计短信发送限流降级
简介：golang go 多版本管理 gvm 使用，gvm 管理多个 go sdk 版本，快速切换不同 go 版本做项目开发。
 | 原文链接：http://book.welpfox.asia/blog/3520588.sHtMl

原标题：实战项目：本地模拟磁盘IO高负载观察服务行为
简介：golang sort 搜索查找切片元素，sort.Search 二分查找有序切片，快速定位元素索引位置。
 | 原文链接：http://book.welpfox.asia/blog/9650740.sHtMl

原标题：golang 系统设计开发环境本地调试最佳实践
简介：接口限流逻辑简单模拟实现，编写简易限流逻辑，限制接口访问频次，保护服务，避免短时间大量请求压垮系统。
 | 原文链接：http://book.welpfox.asia/blog/4016045.sHtMl

原标题：golang 系统设计消息幂等消费去重实现方案
简介：nodejs 定时任务生产环境避坑，Node 定时任务线上踩坑汇总，集群重复执行、任务阻塞等问题解决方案。
 | 原文链接：http://book.welpfox.asia/blog/1531386.sHtMl

原标题：简易网关请求路由过滤模拟
简介：golang 互斥锁读写锁并发安全，互斥锁读写锁实操，保护共享变量，解决多协程并发读写数据竞争。
 | 原文链接：http://book.welpfox.asia/blog/9905483.sHtMl

原标题：Issue：Docker网络模式选择错误容器互通失败
简介：golang sftp 文件上传下载操作，sftp 协议远程文件上传下载，实现服务器之间文件传输功能。
 | 原文链接：http://book.welpfox.asia/blog/9519177.sHtMl

原标题：golang defer panic 异常处理
简介：golang go select 多路等待 channel，select 等待多个 channel，default 非阻塞，超时等待 channel。
 | 原文链接：http://book.welpfox.asia/blog/6488938.sHtMl

原标题：部署复盘：配置不要硬编码进镜像最佳实践
简介：golang 制品镜像版本号规范管理，镜像版本号结合 git commit，明确每个镜像对应代码版本便于追溯。
 | 原文链接：http://book.welpfox.asia/blog/5457892.sHtMl

原标题：OpenSource：开源项目风险评估依赖安全检查
简介：异步任务堆积消费能力优化，处理消息任务堆积问题，提升消费处理速度，恢复队列正常处理水位。
 | 原文链接：http://book.welpfox.asia/blog/7082646.sHtMl

原标题：调优方案：Web服务内核socket参数调优
简介：golang go‑zero 配置中心热更新，go‑zero 对接 etcd 配置中心，配置热更新无需重启服务。
 | 原文链接：http://book.welpfox.asia/blog/7603635.sHtMl

原标题：golang 系统设计 ci 流水线安全管控思路
简介：批量异步处理系统业务落地，构建批量异步处理系统，把耗时业务异步化，提升接口响应速度。
 | 原文链接：http://book.welpfox.asia/blog/5528714.sHtMl

原标题：实战项目：WSL开发环境完整配置实操
简介：golang redis pipeline 批量操作，使用 Redis Pipeline 批量执行多条命令，减少网络往返，提升批量操作性能。
 | 原文链接：http://book.welpfox.asia/blog/4484483.sHtMl

原标题：避坑：预编译SQL失效，出现SQL注入风险
简介：golang http client 连接池调优，调优 Go HTTP Client 连接池参数，复用 TCP 连接，减少连接创建开销。
 | 原文链接：http://book.welpfox.asia/blog/0422070.sHtMl


二、踩坑排错｜Troubleshooting
原标题：golang 系统设计传输加密 tls 配置要点
简介：DNS TTL 配置域名切换生效，调整 DNS 解析 TTL，缩短缓存时间，域名变更后可以快速全网生效。
 | 原文链接：http://book.welpfox.asia/blog/4732110.sHtMl

原标题：ICMP 放通网络丢包问题修复
简介：golang go 程序容器资源 requests limits，设置容器 cpu 内存配额，防止实例抢占集群资源，稳定调度。
 | 原文链接：http://book.welpfox.asia/blog/8120598.sHtMl

原标题：golang 系统设计网关请求日志 traceId 透传实现
简介：消息队列重复消费业务处理，实现消息消费幂等，处理重复投递消息，保证多次消费业务结果一致。
 | 原文链接：http://book.welpfox.asia/blog/5494371.sHtMl

原标题：HTTPS 证书过期更新操作
简介：golang net/http/httptest 服务端模拟，httptest.NewRecorder 记录 handler 响应，校验返回状态码 body。
 | 原文链接：http://book.welpfox.asia/blog/8687976.sHtMl

原标题：golang 系统设计网关限流熔断降级配置思路
简介：golang go 程序守护进程实现思路，go 程序不做 daemon 化，依靠 systemd pm2 k8s 实现进程守护。
 | 原文链接：http://book.welpfox.asia/blog/6903138.sHtMl

原标题：SSH 密钥配置 GitHub 免密登录
简介：golang 集成测试测试数据库回滚，集成测试结束自动回滚数据库，不污染测试环境数据。
 | 原文链接：http://book.welpfox.asia/blog/7750313.sHtMl

原标题：前端权限路由动态生成实现
简介：数据库连接池参数调优，调整连接池最大最小连接数，空闲超时，避免连接耗尽或者资源浪费。
 | 原文链接：http://book.welpfox.asia/blog/7365238.sHtMl

原标题：Hands‑on：简易熔断逻辑状态机原型实现
简介：golang go 模板执行错误捕获，捕获模板执行错误，防止模板错误直接返回空白页面。
 | 原文链接：http://book.welpfox.asia/blog/7523451.sHtMl

原标题：本地简易配置中心动态管理
简介：hosts 配置本地回环访问修复，修改 hosts 配置，修复 127.0.0.1 解析异常，本地服务访问失败问题。
 | 原文链接：http://book.welpfox.asia/blog/8246119.sHtMl

原标题：踩坑记录：浮点数作为Rediskey匹配异常
简介：移动端适配 rem vw 方案对比，对比 rem 与 vw 移动端适配方案，分析优缺点，给出选型建议。
 | 原文链接：http://book.welpfox.asia/blog/1361102.sHtMl

原标题：golang minio 存储桶权限管控配置
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://book.welpfox.asia/blog/9894608.sHtMl

原标题：Git 分支管理多人协作实战教程
简介：golang 限流熔断放在代理层实践，代理层统一限流熔断，对后端服务做流量保护。
 | 原文链接：http://book.welpfox.asia/blog/9692019.sHtMl

原标题：golang 系统设计用户签到统计方案
简介：程序日志分级输出规范实践，区分日志等级，规范日志打印内容，合理输出日志，方便线上问题排查定位。
 | 原文链接：http://book.welpfox.asia/blog/0739124.sHtMl

原标题：项目实践：Docker镜像安全扫描本地实操
简介：并发数据覆盖加锁安全处理，多线程并发修改同一数据，增加锁机制，防止并发覆盖丢失更新数据。
 | 原文链接：http://book.welpfox.asia/blog/7042616.sHtMl

原标题：程序日志分级输出规范实践
简介：golang go cover 覆盖率报告生成，go test‑cover 生成测试覆盖率，html 可视化查看未覆盖代码行。
 | 原文链接：http://book.welpfox.asia/blog/5625851.sHtMl

原标题：开发记录：数据库悲观锁乐观锁业务场景实践
简介：轻量 API 后端接口服务快速开发，快速搭建简易 API 服务，实现基础接口能力，快速支撑小型业务需求。
 | 原文链接：http://book.welpfox.asia/blog/5816576.sHtMl

原标题：golang 系统设计降级策略开关配置方案
简介：golang go‑zero 缓存自动击穿防护，go‑zero 缓存组件自带缓存击穿防护，减少缓存层故障。
 | 原文链接：http://book.welpfox.asia/blog/5518909.sHtMl

原标题：golang 接口返回统一封装工具
简介：golang clickhouse go 客户端数据写入，clickhouse‑go 客户端写入查询，海量时序数据分析业务。
 | 原文链接：http://book.welpfox.asia/blog/4110492.sHtMl

原标题：部署实践：数据库迁移脚本版本管理实践
简介：任务执行锁防止并发重复调度，增加任务执行锁，多实例环境，防止同一个定时任务并发多次运行。
 | 原文链接：http://book.welpfox.asia/blog/0112936.sHtMl

原标题：golang kafka 消息顺序性保证方案
简介：静态网页 HTML CSS 快速入门实战，通过简单页面案例讲解标签、样式布局，从零编写页面，理解网页基础渲染原理。
 | 原文链接：http://book.welpfox.asia/blog/8609931.sHtMl

原标题：golang http client 连接池调优
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://book.welpfox.asia/blog/9313654.sHtMl

原标题：golang 系统设计日志本地打印线上关闭调试信息
简介：Dockerfile 编写容器打包实战，讲解 Dockerfile 指令含义，编写镜像构建脚本，将本地项目打包成可分发容器镜像。
 | 原文链接：http://book.welpfox.asia/blog/2479633.sHtMl

原标题：golang 系统设计架构图绘制规范简单建议
简介：golang sync.Map 高并发 map 使用场景，sync.Map 适用场景，读写实操，对比普通 map 加锁性能差异。
 | 原文链接：http://book.welpfox.asia/blog/9802880.sHtMl

原标题：Practice：实现IP黑名单拦截中间件实践
简介：golang go cover 覆盖率报告生成，go test‑cover 生成测试覆盖率，html 可视化查看未覆盖代码行。
 | 原文链接：http://book.welpfox.asia/blog/5972349.sHtMl

原标题：golang 系统设计 jwt 安全使用避坑要点
简介：golang 表格驱动测试完整示例，表格驱动多组输入输出，批量执行测试用例，减少重复代码。
 | 原文链接：http://book.welpfox.asia/blog/4821858.sHtMl

原标题：请求重试组件退避策略实现
简介：nodejs 单元测试 jest 实操教程，Jest 单元测试实操，编写测试用例，mock 依赖，验证业务逻辑正确性。
 | 原文链接：http://book.welpfox.asia/blog/3933161.sHtMl

原标题：golang es bool 查询条件组合技巧
简介：慢查询分析索引调优数据库实战，抓取慢查询，分析执行计划，优化索引，解决数据库慢查询拖慢业务。
 | 原文链接：http://book.welpfox.asia/blog/2488025.sHtMl

原标题：golang docker compose 依赖启动顺序
简介：文件读写与异常捕获代码示例，演示文件读取写入操作，增加异常捕获逻辑，规避文件不存在、权限不足导致崩溃。
 | 原文链接：http://book.welpfox.asia/blog/7742080.sHtMl

原标题：golang 系统设计开源 pr 评审合并流程实操
简介：golang 微服务网关简易实现，http 反向代理、路由匹配、鉴权限流，理解网关核心原理。
 | 原文链接：http://book.welpfox.asia/blog/3218087.sHtMl

原标题：避坑：定时任务重复执行带来业务脏数据
简介：golang docker 多阶段构建 go 镜像，Go 项目 Docker 多阶段构建，编译与运行阶段分离，大幅度缩减最终镜像体积，提升镜像分发效率。
 | 原文链接：http://book.welpfox.asia/blog/0605909.sHtMl

原标题：记一次第三方回调IP变动未更新防火墙拦截
简介：消息队列消费堆积扩容处理，消息大量堆积时，扩容消费实例，优化消费逻辑，加快消息处理速度。
 | 原文链接：http://book.welpfox.asia/blog/8334332.sHtMl

原标题：OpenSource：开源项目许可证License选型指南
简介：golang channel 通道并发处理，讲解 Channel 用法，协程之间通过通道传递数据，做并发同步控制。
 | 原文链接：http://book.welpfox.asia/blog/0186895.sHtMl

原标题：Architecture：中小型后端服务整体架构设计复盘
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://book.welpfox.asia/blog/3330349.sHtMl

原标题：golang mysql 死锁排查步骤讲解
简介：golang 日志输出 stdout 标准输出规范，容器环境日志输出到 stdout，由容器平台统一采集日志文件。
 | 原文链接：http://book.welpfox.asia/blog/6736436.sHtMl

原标题：一次数据库死锁现场分析与解决方案记录
简介：golang go url url.Values 参数编码，url.Values 构建 url 查询参数，自动处理参数 url 编码。
 | 原文链接：http://book.welpfox.asia/blog/3965195.sHtMl

原标题：golang redis 连接池参数最佳值
简介：golang go 比较运算符可比较类型，哪些类型可以直接 == 比较，map slice 函数不可直接比较。
 | 原文链接：http://book.welpfox.asia/blog/2632043.sHtMl

原标题：golang prometheus counter gauge 使用
简介：OpenAPI 自动接口文档生成，集成 OpenAPI 工具，自动扫描代码生成接口文档，减少文档维护成本。
 | 原文链接：http://book.welpfox.asia/blog/4156619.sHtMl

原标题：golang gorm 批量插入性能调优
简介：golang go 应用内存使用优化手段，减少对象分配，复用对象，降低 GC 压力，减少 GC 停顿时间。
 | 原文链接：http://book.welpfox.asia/blog/5376426.sHtMl

原标题：Practice：实现请求大小限制中间件防护大报文
简介：数据库索引重建提升查询速度，针对碎片化索引，重建数据库索引，恢复 SQL 查询执行性能。
 | 原文链接：http://book.welpfox.asia/blog/5524717.sHtMl

原标题：golang 优雅关闭 grpc 服务示例
简介：golang netlink 系统信息获取，netlink 获取系统网络信息，网卡地址，内核网络状态读取。
 | 原文链接：http://book.welpfox.asia/blog/1019081.sHtMl

三、实战开发｜Practice
原标题：golang 系统设计网关错误重试超时处理策略
简介：系统字符集统一乱码修复，统一数据库、程序、操作系统字符集，解决中文乱码显示异常问题。
 | 原文链接：http://book.welpfox.asia/blog/2222747.sHtMl

原标题：DevOps：多阶段构建Dockerfile最佳实践
简介：golang 进程信号捕获 SIGUSR 自定义信号，捕获用户自定义信号，实现线上不重启触发调试、日志切换。
 | 原文链接：http://book.welpfox.asia/blog/6743451.sHtMl

原标题：golang 系统设计 graphql 接口优缺点梳理
简介：golang 内存持续上涨定位思路，区分内存泄漏、缓存占用、GC 参数不合理，分步定位内存持续走高。
 | 原文链接：http://book.welpfox.asia/blog/9920315.sHtMl

原标题：踩坑记录：乐观锁版本号处理不当更新失败
简介：数据库读写分离性能优化，讲解读写分离原理，主库写入从库查询，分担数据库查询压力，提升查询性能。
 | 原文链接：http://book.welpfox.asia/blog/0016965.sHtMl

原标题：定时任务重复执行分布式锁
简介：Mock 接口服务快速搭建实操，搭建模拟后端接口，自定义返回数据、延迟响应，前端开发阶段无需依赖真实后端服务。
 | 原文链接：http://book.welpfox.asia/blog/9021373.sHtMl

原标题：nodejs 内存溢出问题排查修复
简介：golang elasticsearch 客户端 golang 实操，es 客户端文档增删改查，条件搜索聚合统计对接搜索引擎。
 | 原文链接：http://book.welpfox.asia/blog/5549925.sHtMl

原标题：golang validator 自定义校验规则
简介：API 接口调试与异常处理实战，覆盖接口请求、参数组装、错误捕获，提供调试思路，高效定位接口返回异常问题。
 | 原文链接：http://book.welpfox.asia/blog/8588932.sHtMl

原标题：性能笔记：RPC超时参数优化防止级联阻塞
简介：程序预加载加快服务启动速度，把高频使用资源提前预加载，减少请求阶段初始化，加快服务启动。
 | 原文链接：http://book.welpfox.asia/blog/0158754.sHtMl

原标题：操作系统内核版本适配服务
简介：前端骨架屏提升页面体验，实现页面骨架屏，数据未加载完成展示占位，优化页面白屏感知体验。
 | 原文链接：http://book.welpfox.asia/blog/8163709.sHtMl

原标题：部署实践：数据库迁移脚本版本管理实践
简介：nodejs 集成测试业务流程编写，编写 Node 集成测试，调用真实接口，验证完整业务链路执行结果。
 | 原文链接：http://book.welpfox.asia/blog/5866564.sHtMl

原标题：部署复盘：金丝雀发布流量切分实操方案
简介：golang sqlx 原生 SQL 代码简化，sqlx 简化原生 SQL 结果映射结构体，兼顾性能与开发效率。
 | 原文链接：http://book.welpfox.asia/blog/8441078.sHtMl

原标题：从零学习简单分页逻辑实现思路
简介：后端大文件分片上传接口开发，开发后端分片上传接口，接收分片，合并分片完成大文件存储。
 | 原文链接：http://book.welpfox.asia/blog/0307995.sHtMl

原标题：坑点：环境配置被打包进镜像引发安全泄露
简介：golang hertz 反向代理与负载均衡，hertz 实现反向代理，内置负载均衡，快速搭建网关类服务。
 | 原文链接：http://book.welpfox.asia/blog/2084305.sHtMl

原标题：Practice：实现接口mock动态返回不同响应
简介：golang 内存 dump 线上堆快照采集，线上生成内存 dump 文件，线下分析，定位内存泄漏问题。
 | 原文链接：http://book.welpfox.asia/blog/4817157.sHtMl

原标题：实践：Git大仓库历史清理减小仓库体积实践
简介：站内邮件消息通知功能开发，实现站内消息、邮件通知推送，业务事件触发通知，提醒用户业务状态变更。
 | 原文链接：http://book.welpfox.asia/blog/9780095.sHtMl

原标题：golang toml 配置文件解析教程
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://book.welpfox.asia/blog/9857115.sHtMl

原标题：Practice：实现请求body重复读取中间件实践
简介：golang grpc 客户端拦截器封装，grpc 客户端拦截器实现请求统一签名、重试、链路信息透传。
 | 原文链接：http://book.welpfox.asia/blog/8750942.sHtMl

原标题：限流组件计数器令牌桶模式实现
简介：golang json 解析未知动态 json 结构，解析到 map [string] any 处理未知 json，动态读取字段。
 | 原文链接：http://book.welpfox.asia/blog/3461552.sHtMl

原标题：优化实践：批量操作性能优化，减少数据库IO
简介：前端大文件分片上传完整方案，前端分片切割大文件，配合后端分片接口，实现稳定大文件上传。
 | 原文链接：http://book.welpfox.asia/blog/4347703.sHtMl

原标题：HelloMarkdown：GitHubMarkdown完整语法速查
简介：golang 数据库连接耗尽排查思路，监控连接池状态，定位连接未归还，解决连接耗尽报错。
 | 原文链接：http://book.welpfox.asia/blog/4381928.sHtMl

原标题：hosts 配置本地回环访问修复
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：http://book.welpfox.asia/blog/1804636.sHtMl

原标题：Spring 事务传播机制配置生效
简介：golang dns 自定义解析器实现，自定义 dns 解析，指定 dns 服务器，控制域名解析逻辑，适配内网环境。
 | 原文链接：http://book.welpfox.asia/blog/9215838.sHtMl

原标题：实践：消息队列死信处理业务落地实践
简介：Nginx 丢失请求头配置修正，修复 Nginx 代理转发丢失请求头配置，保证上游服务拿到完整请求头信息。
 | 原文链接：http://book.welpfox.asia/blog/8496952.sHtMl

原标题：部署复盘：容器OOM问题完整排查流程
简介：golang http 代理客户端配置，Go HTTP Client 配置代理，通过代理服务器发起网络请求。
 | 原文链接：http://book.welpfox.asia/blog/0483078.sHtMl

原标题：本地简易配置中心动态管理
简介：golang 程序崩溃 core dump 生成调试，开启 core dump，程序崩溃生成转储文件，事后分析崩溃原因。
 | 原文链接：http://book.welpfox.asia/blog/2871335.sHtMl

原标题：golang 系统设计数据库表设计通用规范模板
简介：Nginx 缓冲区调优大文件上传，调大 Nginx 请求缓冲区，支持客户端上传大体积文件，避免上传被截断。
 | 原文链接：http://book.welpfox.asia/blog/5818978.sHtMl

原标题：方案设计：统一ID生成服务架构对比雪花算法
简介：golang 协程泄露问题排查方法，识别 Go 协程泄露现象，分析泄露场景，给出排查定位协程泄露手段。
 | 原文链接：http://book.welpfox.asia/blog/5882538.sHtMl

原标题：坑点：gitsubmodule子模块更新失败踩坑
简介：对象存储上传下载权限实操，演示对象存储文件上传、下载、访问权限设置，适配业务文件存储场景。
 | 原文链接：http://book.welpfox.asia/blog/2903236.sHtMl

原标题：golang 系统设计集成测试环境准备清理实操
简介：golang http 代理客户端配置，Go HTTP Client 配置代理，通过代理服务器发起网络请求。
 | 原文链接：http://book.welpfox.asia/blog/0337549.sHtMl

原标题：全量回归测试提升代码质量
简介：golang base64 编码解码实操，Go Base64 编码解码示例，处理业务场景 Base64 格式数据转换。
 | 原文链接：http://book.welpfox.asia/blog/5936524.sHtMl

原标题：GraphQL 接口查询优化实操
简介：包管理器依赖缓存清理，清理本地依赖缓存，解决缓存旧包引发问题，拉取最新版本依赖包。
 | 原文链接：http://book.welpfox.asia/blog/6560127.sHtMl

原标题：golang etcd 租约 lease 过期机制
简介：golang http 文件下载断点续传服务，服务端实现断点续传，支持大文件分段下载，提升大文件下载稳定性。
 | 原文链接：http://book.welpfox.asia/blog/4585640.sHtMl

原标题：golang 接口请求日志记录中间件
简介：golang 消息队列实现事务消息方案，基于 kafka 实现事务消息，业务执行成功才对外投递消息。
 | 原文链接：http://book.welpfox.asia/blog/8408840.sHtMl

原标题：golang toml 配置文件解析教程
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://book.welpfox.asia/blog/2271564.sHtMl

原标题：部署复盘：蓝绿发布实现零停机业务更新
简介：SDK 版本兼容线上崩溃修复，处理 SDK 版本升级之后线上崩溃，定位 API 变更，做版本兼容适配改造。
 | 原文链接：http://book.welpfox.asia/blog/6037559.sHtMl

原标题：golang 系统设计分布式锁不同场景选型对比
简介：golang 配置热更新不重启服务，实现配置热加载，监听配置变更，更新内存配置，无需重启服务实例。
 | 原文链接：http://book.welpfox.asia/blog/0780417.sHtMl

原标题：golang 系统设计 rest 分页排序过滤参数规范
简介：golang go 程序守护进程实现思路，go 程序不做 daemon 化，依靠 systemd pm2 k8s 实现进程守护。
 | 原文链接：http://book.welpfox.asia/blog/8500997.sHtMl

原标题：排错：CI流水线构建失败，日志无明确报错
简介：nodejs redis 缓存业务实战，Node 对接 Redis 实现业务缓存，缓存热点查询结果，减轻数据库压力。
 | 原文链接：http://book.welpfox.asia/blog/7114568.sHtMl

原标题：axios 二次封装请求拦截处理
简介：系统时间同步定时任务偏移，同步服务器系统时间，防止时间偏移，避免定时任务执行时间错乱。
 | 原文链接：http://book.welpfox.asia/blog/2528551.sHtMl

原标题：RPC 报文大小上限调优大请求
简介：golang 分页查询封装通用工具，封装 Go 通用分页工具，统一处理分页参数，简化业务分页接口开发。
 | 原文链接：http://book.welpfox.asia/blog/3033181.sHtMl

四、架构设计｜Architecture
原标题：golang 系统设计日志级别业务使用原则梳理
简介：golang init 函数合理使用边界，少用 init，优先显式调用初始化，便于控制初始化时机。
 | 原文链接：http://book.welpfox.asia/blog/5138589.sHtMl

原标题：优化实践：LRU本地缓存优化热点访问性能
简介：golang 项目 go mod 依赖管理，Go Mod 管理项目依赖，下载、升级、清理依赖，解决依赖版本管理。
 | 原文链接：http://book.welpfox.asia/blog/9681373.sHtMl

原标题：入门实践：简单重试逻辑封装实现
简介：游标分页大数据查询性能提升，使用游标分页替代偏移分页，解决大数据 offset 分页性能越来越差问题。
 | 原文链接：http://book.welpfox.asia/blog/0434412.sHtMl

原标题：方案对比：单体、微服务、模块化单体取舍
简介：分布式 ID 生成器高并发实现，实现高性能分布式 ID 生成器，适配高并发业务，生成全局唯一 ID。
 | 原文链接：http://book.welpfox.asia/blog/7409718.sHtMl

原标题：CI/CD 流水线自动构建部署落地
简介：读懂开源项目 README 实用技巧，教你快速解析开源项目说明文档，提取安装、运行、配置关键信息，快速上手项目。
 | 原文链接：http://book.welpfox.asia/blog/8159421.sHtMl

原标题：新手教程：如何给开源项目提交第一个PR
简介：Redis 热点 key 拆分降低集群压力，拆分访问量极高的热点 Key，分散请求压力，避免 Redis 节点压力过高。
 | 原文链接：http://book.welpfox.asia/blog/0004013.sHtMl

原标题：golang kafka 生产者参数调优
简介：golang grpc 客户端流上传数据，客户端流式请求，客户端分批上传数据到服务端，适合大文件传输。
 | 原文链接：http://book.welpfox.asia/blog/5171301.sHtMl

原标题：golang mongodb 分页性能优化技巧
简介：golang kafka 消费者位移管理，理解 kafka offset，手动提交位移，保证消息消费至少一次语义。
 | 原文链接：http://book.welpfox.asia/blog/6346347.sHtMl

原标题：TCP 长连接参数优化 TIME_WAIT
简介：golang trace 可视化分析协程阻塞，使用 trace 网页 UI，定位协程阻塞、系统调用阻塞、锁等待。
 | 原文链接：http://book.welpfox.asia/blog/5835546.sHtMl

原标题：记一次升级操作系统内核引发服务不稳定
简介：限流组件计数器令牌桶模式实现，实现计数器、令牌桶两种限流算法，封装可复用限流组件。
 | 原文链接：http://book.welpfox.asia/blog/6731072.sHtMl

原标题：golang 系统设计蓝绿发布滚动发布对比
简介：数据库分表路由写入分片修正，修复分表路由逻辑，保证数据写入正确分片，不会出现数据丢失错乱。
 | 原文链接：http://book.welpfox.asia/blog/9150748.sHtMl

原标题：运维笔记：服务器定时任务运维脚本编写
简介：golang docker compose 开发环境 go 服务，docker compose 编排 go 服务与中间件，本地一键拉起整套开发环境。
 | 原文链接：http://book.welpfox.asia/blog/6153020.sHtMl

原标题：nodejs 中间件模式原理剖析
简介：消息队列生产消费模型入门，讲解消息队列生产、存储、消费流程，理解异步解耦、削峰，掌握消息队列基础概念。
 | 原文链接：http://book.welpfox.asia/blog/3651730.sHtMl

原标题：入门实践：使用模板快速生成项目脚手架
简介：golang grafana 面板 go 业务指标可视化，prometheus 指标对接 grafana，配置监控面板可视化业务状态。
 | 原文链接：http://book.welpfox.asia/blog/8790337.sHtMl

原标题：Architecture：文件处理服务架构大文件内存规避
简介：golang json omitempty 零值坑，omitempty 会忽略零值，区分业务是否需要输出零值字段。
 | 原文链接：http://book.welpfox.asia/blog/4437057.sHtMl

原标题：golang 优雅处理数据库事务
简介：golang jwt jwk 公钥验证令牌，使用 jwk 公钥校验 jwt，非对称方式签发校验令牌，提升安全性。
 | 原文链接：http://book.welpfox.asia/blog/8812559.sHtMl

原标题：golang cron 定时任务防并发执行
简介：express 请求参数校验处理，接入参数校验库，校验入参，拦截非法参数，提前拦截错误请求。
 | 原文链接：http://book.welpfox.asia/blog/5417073.sHtMl

原标题：开发复盘：统一错误码体系设计落地实践
简介：golang go 项目 CI github actions 配置，github actions 实现 go 项目 ci，自动测试、代码检查、编译打包镜像。
 | 原文链接：http://book.welpfox.asia/blog/8991930.sHtMl

?
