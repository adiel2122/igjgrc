最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 优雅停机服务关闭实现
简介：程序信号中断退出处理逻辑，捕获系统中断信号，执行资源释放、关闭连接，实现程序优雅退出。
 | 原文链接：http://blog.xhldejj.cn/Article/details/100369.sHtML

原标题：Architecture：链路追踪架构核心组件与埋点
简介：RPC 报文大小上限调优大请求，调大 RPC 框架报文最大限制，支持传输大体积请求报文不被截断。
 | 原文链接：http://blog.xhldejj.cn/Article/details/482805.sHtML

原标题：项目实践：MySQL读写分离本地模拟实践
简介：容器内存扩容 OOM 被杀死修复，调高容器内存限制，优化程序内存占用，避免程序被 OOM 终止。
 | 原文链接：http://blog.xhldejj.cn/Article/details/233379.sHtML

原标题：坑点：环境配置写死代码，上线忘记修改
简介：golang 进程信号捕获 SIGUSR 自定义信号，捕获用户自定义信号，实现线上不重启触发调试、日志切换。
 | 原文链接：http://blog.xhldejj.cn/Article/details/679938.sHtML

原标题：死信队列处理消息阻塞业务
简介：golang go json 序列化自定义字段，json 标签控制字段名称、忽略字段、omitempty 空值忽略。
 | 原文链接：http://blog.xhldejj.cn/Article/details/949432.sHtML

原标题：开发记录：表单参数校验统一中间件实现
简介：接口幂等性防重复请求实现，实现接口幂等逻辑，避免重复提交请求产生多条脏数据，保障业务数据安全。
 | 原文链接：http://blog.xhldejj.cn/Article/details/317797.sHtML

原标题：golang 接口请求日志记录中间件
简介：Nginx 丢失请求头配置修正，修复 Nginx 代理转发丢失请求头配置，保证上游服务拿到完整请求头信息。
 | 原文链接：http://blog.xhldejj.cn/Article/details/973576.sHtML

原标题：分布式锁失效问题排查修复
简介：线程调度优化减少上下文切换，优化线程数量，减少线程频繁切换，降低 CPU 上下文切换开销。
 | 原文链接：http://blog.xhldejj.cn/Article/details/066183.sHtML

原标题：设计思考：缓存分层架构设计与失效处理策略
简介：前端大文件分片上传完整方案，前端分片切割大文件，配合后端分片接口，实现稳定大文件上传。
 | 原文链接：http://blog.xhldejj.cn/Article/details/926119.sHtML

原标题：踩坑：大事务引发数据库连接池耗尽
简介：golang go 包循环导入报错解决，A 导入 B B 导入 A，循环导入报错，重构代码拆分包消除循环依赖。
 | 原文链接：http://blog.xhldejj.cn/Article/details/375487.sHtML

原标题：部署实践：服务器SSH安全加固配置实践
简介：语义化版本依赖管理防错乱，项目依赖遵循语义版本约束，规避依赖自动升级引入不兼容变更。
 | 原文链接：http://blog.xhldejj.cn/Article/details/823575.sHtML

原标题：避坑：文件锁处理不当多进程竞争死锁
简介：golang go test 单元测试命令参数详解，gotest 参数覆盖率，指定测试用例，跳过测试，单元测试命令实操。
 | 原文链接：http://blog.xhldejj.cn/Article/details/024681.sHtML

原标题：Practice：实现业务id生成不连续有序ID方案
简介：golang channel 作为函数参数方向，声明 channel 入参方向，只读 channel 只写 channel 提升代码约束。
 | 原文链接：http://blog.xhldejj.cn/Article/details/023317.sHtML

原标题：golang 系统设计埋点数据上报方案
简介：golang 静态文件服务搭建教程，Go 搭建静态文件服务，托管静态资源，实现文件直接对外访问。
 | 原文链接：http://blog.xhldejj.cn/Article/details/186629.sHtML

原标题：实战：搭建本地对象存储兼容S3协议demo
简介：ORM 隐式慢查询问题规避，识别 ORM 框架隐式查询，避免循环查询数据库，减少不必要慢 SQL 产生。
 | 原文链接：http://blog.xhldejj.cn/Article/details/609589.sHtML

原标题：Debug：分页偏移量过大数据库查询性能暴跌
简介：golang k8s 客户端 client‑go 简单示例，client‑go 操作 k8s 资源，增删改查 pod deployment 等资源对象。
 | 原文链接：http://blog.xhldejj.cn/Article/details/155249.sHtML

原标题：Troubleshoot：CPU调度频繁上下文切换性能下降
简介：时间精度统一业务判断修复，统一业务使用时间戳精度，毫秒秒区分清楚，修复时间判断逻辑错误。
 | 原文链接：http://blog.xhldejj.cn/Article/details/195107.sHtML

原标题：golang redis bitmap 位图统计实现
简介：轻量 API 后端接口服务快速开发，快速搭建简易 API 服务，实现基础接口能力，快速支撑小型业务需求。
 | 原文链接：http://blog.xhldejj.cn/Article/details/344790.sHtML

原标题：踩坑记录：时间戳精度不一致引发判断错误
简介：本地运行正常线上报错排查，对比本地与线上环境差异，从配置、系统版本、文件权限定位线上独有的 bug。
 | 原文链接：http://blog.xhldejj.cn/Article/details/702853.sHtML

原标题：快速入门ORM，实现简单数据库增删改查
简介：前端错误监控上报系统搭建，搭建前端错误监控，捕获页面 JS 错误，上报后端，快速发现线上页面 bug。
 | 原文链接：http://blog.xhldejj.cn/Article/details/011405.sHtML

原标题：golang k8s 监控 prometheus 部署
简介：nodejs 中间件模式原理剖析，拆解 Node 中间件设计模式，理解请求逐层处理流转的底层原理。
 | 原文链接：http://blog.xhldejj.cn/Article/details/439638.sHtML

原标题：Practice：模拟主从延迟业务兼容方案实践
简介：golang go 应用内存使用优化手段，减少对象分配，复用对象，降低 GC 压力，减少 GC 停顿时间。
 | 原文链接：http://blog.xhldejj.cn/Article/details/883553.sHtML

原标题：Hands‑on：简易短消息模板渲染组件实践
简介：集成测试业务流程编写示例，编写业务流程集成测试，覆盖完整业务链路，验证模块之间协同工作是否正常。
 | 原文链接：http://blog.xhldejj.cn/Article/details/969808.sHtML

原标题：golang gin 框架接口开发实战
简介：golang go 网络编程 net 包基础，net 包 tcp udp socket 编程，监听接收连接，读写数据。
 | 原文链接：http://blog.xhldejj.cn/Article/details/491792.sHtML

原标题：效率笔记：提升开发效率shell脚本小工具合集
简介：golang os 文件目录操作大全，文件创建删除重命名，目录遍历，文件信息读取，完成各类文件系统操作。
 | 原文链接：http://blog.xhldejj.cn/Article/details/197815.sHtML

原标题：golang 系统设计开源项目贡献指南 contributing
简介：包管理器依赖缓存清理，清理本地依赖缓存，解决缓存旧包引发问题，拉取最新版本依赖包。
 | 原文链接：http://blog.xhldejj.cn/Article/details/908743.sHtML

原标题：Hands‑on：简易链路追踪原型开发实践
简介：OOMKilled 容器被杀完整排查，排查容器被 OOM 终止完整流程，区分程序内存泄露和容器内存限制过小。
 | 原文链接：http://blog.xhldejj.cn/Article/details/058166.sHtML

原标题：golang es 映射 mapping 设计避坑
简介：golang go 模板执行错误捕获，捕获模板执行错误，防止模板错误直接返回空白页面。
 | 原文链接：http://blog.xhldejj.cn/Article/details/474925.sHtML

原标题：golang k8s 日志收集 efk 简单架构
简介：golang mysql 长连接检测保活设置，配置 mysql 连接保活检测，剔除失效连接，避免拿到断开无效数据库连接。
 | 原文链接：http://blog.xhldejj.cn/Article/details/795222.sHtML

原标题：接口请求重试容错机制实现
简介：跨平台换行符统一异常修复，统一代码文件换行符，解决不同操作系统换行符不一致带来脚本执行异常。
 | 原文链接：http://blog.xhldejj.cn/Article/details/459693.sHtML

原标题：入门实践：简单的请求封装与异常捕获
简介：golang go 终端 pty 伪终端操作，pty 启动子进程，模拟终端交互，实现交互式命令调用。
 | 原文链接：http://blog.xhldejj.cn/Article/details/522633.sHtML

原标题：golang mysql 读写分离简单实现
简介：线上接口超时故障排查思路，从网络、数据库、代码逻辑逐层排查接口超时，定位慢请求根因。
 | 原文链接：http://blog.xhldejj.cn/Article/details/070581.sHtML

原标题：实战项目：WebSocket消息广播房间分组实践
简介：golang 协程 panic 捕获防止崩溃，协程内部捕获 panic，防止单个协程恐慌造成整个 Go 进程崩溃。
 | 原文链接：http://blog.xhldejj.cn/Article/details/984101.sHtML

原标题：坑点：gitrebase操作失误，代码提交丢失
简介：﻿从零搭建本地开发环境完整教程，手把手完成环境配置，梳理踩坑点，帮助开发者快速搭建可用的本地开发环境，降低上手成本。
 | 原文链接：http://blog.xhldejj.cn/Article/details/299664.sHtML

原标题：golang 系统设计 vscode go 插件调试配置实操
简介：golang 字符串处理常用技巧汇总，字符串拼接、分割、替换、类型转换实操，规避字符串高频错误。
 | 原文链接：http://blog.xhldejj.cn/Article/details/429227.sHtML

原标题：golang 系统设计并发控制协程池任务池实现
简介：golang redis stream 消息队列实战，redis stream 实现可靠消息队列，消费组、ack 确认，消息不丢失。
 | 原文链接：http://blog.xhldejj.cn/Article/details/701078.sHtML

原标题：开发记录：短信发送服务封装，失败重试策略
简介：缓存穿透防护保护数据库，实现缓存穿透防护手段，拦截不存在的数据查询，避免请求直接打穿数据库。
 | 原文链接：http://blog.xhldejj.cn/Article/details/992348.sHtML

原标题：数据库分表存储大表优化方案
简介：OpenAPI 自动接口文档生成，集成 OpenAPI 工具，自动扫描代码生成接口文档，减少文档维护成本。
 | 原文链接：http://blog.xhldejj.cn/Article/details/947600.sHtML

原标题：GitHub Markdown 文档语法汇总
简介：golang alertmanager 告警配置实践，alertmanager 配置告警路由，告警发送邮件钉钉，异常及时通知运维。
 | 原文链接：http://blog.xhldejj.cn/Article/details/040901.sHtML

原标题：golang 时间时区处理避坑指南
简介：golang redis stream 消息队列实战，redis stream 实现可靠消息队列，消费组、ack 确认，消息不丢失。
 | 原文链接：http://blog.xhldejj.cn/Article/details/315153.sHtML


二、踩坑排错｜Troubleshooting
原标题：进程线程并发基础概念讲解
简介：golang rate 令牌桶限流器源码理解，拆解令牌桶限流核心逻辑，理解令牌生成消耗，掌握限流底层原理。
 | 原文链接：http://blog.xhldejj.cn/Article/details/495668.sHtML

原标题：golang 系统设计无锁编程思路简单示例
简介：golang gin 参数绑定 query form json，掌握 Gin 多种参数绑定方式，适配不同请求格式参数读取。
 | 原文链接：http://blog.xhldejj.cn/Article/details/788110.sHtML

原标题：golang 项目 makefile 脚本编写
简介：接口签名校验防篡改实现，实现请求签名验签逻辑，校验请求参数未被篡改，提升接口调用安全性。
 | 原文链接：http://blog.xhldejj.cn/Article/details/608045.sHtML

原标题：golang 系统设计降级策略开关配置方案
简介：nodejs 信号处理优雅关闭服务，监听系统信号，执行资源清理，实现 Node 服务优雅停机，拒绝粗暴杀死进程。
 | 原文链接：http://blog.xhldejj.cn/Article/details/495096.sHtML

原标题：pnpm 包管理工具实战避坑指南
简介：数据库主从延迟业务兼容处理，业务适配主从复制延迟，避免读取从库拿到还未同步完成旧数据。
 | 原文链接：http://blog.xhldejj.cn/Article/details/128404.sHtML

原标题：Git 标签版本标记发布管理
简介：Git 混乱提交历史清理方法，针对杂乱的提交记录，使用 Git 工具整理，清理无效提交，还原整洁版本历史。
 | 原文链接：http://blog.xhldejj.cn/Article/details/482367.sHtML

原标题：golang 系统设计 p0 故障复盘方法论讲解
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://blog.xhldejj.cn/Article/details/304401.sHtML

原标题：Practice：实现请求大小限制中间件防护大报文
简介：golang 优雅处理 http 重定向逻辑，自定义控制 http 重定向跳转次数，防止无限重定向死循环。
 | 原文链接：http://blog.xhldejj.cn/Article/details/279904.sHtML

原标题：DevOps：多阶段构建Dockerfile最佳实践
简介：golang k8s 客户端 client‑go 简单示例，client‑go 操作 k8s 资源，增删改查 pod deployment 等资源对象。
 | 原文链接：http://blog.xhldejj.cn/Article/details/136607.sHtML

原标题：golang toml 配置文件解析教程
简介：Redis 热点 key 拆分降低集群压力，拆分访问量极高的热点 Key，分散请求压力，避免 Redis 节点压力过高。
 | 原文链接：http://blog.xhldejj.cn/Article/details/853378.sHtML

原标题：golang 系统设计并发控制协程池任务池实现
简介：golang grpc keepalive 保活配置，grpc keepalive 参数调优，检测断开僵死连接，释放无效连接资源。
 | 原文链接：http://blog.xhldejj.cn/Article/details/257848.sHtML

原标题：Issue：WSL2内存持续暴涨不自动释放
简介：Docker 容器时区错误修复方案，修复 Docker 容器内部时区偏差，解决容器内时间不对引发业务逻辑异常。
 | 原文链接：http://blog.xhldejj.cn/Article/details/685879.sHtML

原标题：排错：HTTPS证书过期导致接口调用失败
简介：golang go 爬虫 html 解析 goquery，goquery 解析 html 文档，css 选择器提取网页内容，实现网页数据抓取。
 | 原文链接：http://blog.xhldejj.cn/Article/details/721430.sHtML

原标题：golang 系统设计 protobuf 枚举类型规范写法
简介：golang 分布式锁 redis 实现，基于 Redis 实现 Go 分布式锁，解决多实例并发竞争资源问题。
 | 原文链接：http://blog.xhldejj.cn/Article/details/487488.sHtML

原标题：实战：多版本SDK兼容业务改造实践
简介：golang go 爬虫 robots 协议遵守，解析 robots.txt 规则，控制爬虫抓取范围，合规采集网页数据。
 | 原文链接：http://blog.xhldejj.cn/Article/details/644002.sHtML

原标题：前端权限路由动态生成实现
简介：提交第一个开源 PR 完整流程，Fork 项目、修改代码、提交 Pull Request，讲解 PR 规范，提升合并通过率。
 | 原文链接：http://blog.xhldejj.cn/Article/details/684585.sHtML

原标题：Hands‑on：简易配置中心本地原型实现
简介：服务健康检查告警监控体系，搭建健康检查加告警体系，服务异常及时推送告警通知运维人员。
 | 原文链接：http://blog.xhldejj.cn/Article/details/714794.sHtML

原标题：Troubleshoot：批量导入数据，事务过大回滚日志暴涨
简介：业务错误码体系设计方案，设计项目统一错误码，区分不同业务异常，标准化错误返回，便于前端识别处理。
 | 原文链接：http://blog.xhldejj.cn/Article/details/576989.sHtML

原标题：内存广播本地进程消息通知
简介：golang raw socket 底层网络报文收发，raw socket 收发原始网络报文，做网络抓包数据包处理。
 | 原文链接：http://blog.xhldejj.cn/Article/details/638013.sHtML

原标题：TLS 版本兼容 HTTPS 握手失败
简介：gRPC 服务端客户端入门示例，搭建 gRPC 服务端与调用客户端，学习 protobuf 定义，掌握 RPC 基础开发流程。
 | 原文链接：http://blog.xhldejj.cn/Article/details/296637.sHtML

原标题：业务接口幂等完整落地案例
简介：磁盘占满服务不可用清理方案，定位磁盘占用大文件，清理日志、缓存文件，恢复磁盘可用空间。
 | 原文链接：http://blog.xhldejj.cn/Article/details/298892.sHtML

原标题：golang 系统设计日志规范结构化日志落地
简介：golang yaml 解析配置加载实操，Go 解析 YAML 配置文件，读取配置参数，驱动业务运行。
 | 原文链接：http://blog.xhldejj.cn/Article/details/084792.sHtML

原标题：大文件导出内存溢出防护
简介：golang os 进程 pid 获取父进程 pid，os.Getpid 获取进程 id，获取父进程 pid，进程间识别。
 | 原文链接：http://blog.xhldejj.cn/Article/details/026184.sHtML

原标题：Troubleshooting：K8sPodOOMKilled完整排查流程
简介：业务错误码体系设计方案，设计项目统一错误码，区分不同业务异常，标准化错误返回，便于前端识别处理。
 | 原文链接：http://blog.xhldejj.cn/Article/details/885552.sHtML

原标题：Hands‑on：模拟RPC超时重试业务异常场景
简介：golang go 接口定义原则小接口，go 小接口设计原则，接口尽量小，只定义必要方法，提升代码灵活性。
 | 原文链接：http://blog.xhldejj.cn/Article/details/536302.sHtML

原标题：golang 表单文件大小限制配置
简介：全局异常处理器接口返回统一，接入全局异常捕获，拦截业务全部异常，对外输出统一格式返回值。
 | 原文链接：http://blog.xhldejj.cn/Article/details/160495.sHtML

原标题：golang k8s pod 优雅关闭流程讲解
简介：golang channel 通道并发处理，讲解 Channel 用法，协程之间通过通道传递数据，做并发同步控制。
 | 原文链接：http://blog.xhldejj.cn/Article/details/236596.sHtML

原标题：golang 系统信号信号量处理
简介：网关超时时间调优后端等待，调大网关向后端转发请求超时时间，给后端业务充足处理时间。
 | 原文链接：http://blog.xhldejj.cn/Article/details/244378.sHtML

原标题：踩坑记录：端口被占用导致服务启动失败
简介：git cherry‑pick 规范操作防 bug，规范 cherry‑pick 使用流程，处理冲突，避免错误引入不兼容代码。
 | 原文链接：http://blog.xhldejj.cn/Article/details/806507.sHtML

原标题：架构笔记：海量消息堆积架构处理能力设计
简介：golang icmp ping 程序实现，go 实现 ping 工具发送 icmp 报文，检测网络连通性。
 | 原文链接：http://blog.xhldejj.cn/Article/details/498690.sHtML

原标题：方案设计：批量大数据导出系统架构拆解
简介：前端工程化 webpack 打包优化，针对 webpack 项目做打包调优，分包、压缩、Tree‑Shaking，缩减包体积。
 | 原文链接：http://blog.xhldejj.cn/Article/details/170585.sHtML

原标题：golang 错误包装 errors.wrap 用法
简介：golang 表单文件大小限制配置，限制表单上传文件最大体积，拦截超大文件上传请求，保护服务。
 | 原文链接：http://blog.xhldejj.cn/Article/details/072855.sHtML

原标题：开发记录：表单文件类型校验后端安全校验实践
简介：golang go select 多路等待 channel，select 等待多个 channel，default 非阻塞，超时等待 channel。
 | 原文链接：http://blog.xhldejj.cn/Article/details/526936.sHtML

原标题：GET POST 接口请求参数处理
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://blog.xhldejj.cn/Article/details/876437.sHtML

原标题：多版本开发环境共存配置
简介：golang 错误处理最佳实践汇总，Go 错误处理规范，包装错误，堆栈携带，拒绝简单忽略错误。
 | 原文链接：http://blog.xhldejj.cn/Article/details/350033.sHtML

原标题：开发复盘：分布式会话共享多种方案实践
简介：golang 时间轮算法实现延时调度，手写简易时间轮，高并发大量延时任务，降低轮询 CPU 消耗。
 | 原文链接：http://blog.xhldejj.cn/Article/details/644398.sHtML

原标题：新手向：开源项目本地构建失败通用排查步骤
简介：golang go 泛型实现通用数据结构，泛型实现通用栈队列，复用逻辑支持多种数据类型。
 | 原文链接：http://blog.xhldejj.cn/Article/details/201218.sHtML

原标题：golang 系统设计字符串拼接性能优化技巧
简介：golang 分页查询封装通用工具，封装 Go 通用分页工具，统一处理分页参数，简化业务分页接口开发。
 | 原文链接：http://blog.xhldejj.cn/Article/details/131451.sHtML

原标题：golang 系统设计数据库查询优化完整流程
简介：golang embed 目录读取文件列表，embed 嵌入整个目录，读取目录下全部文件，做静态资源服务。
 | 原文链接：http://blog.xhldejj.cn/Article/details/569197.sHtML

原标题：golang 系统设计 protobuf 可选字段使用技巧
简介：golang os.Signal 信号监听完整示例，signal.Notify 监听信号，缓冲 channel 防止信号丢失。
 | 原文链接：http://blog.xhldejj.cn/Article/details/673225.sHtML

三、实战开发｜Practice
原标题：golang k8s 网络策略网络隔离设置
简介：golang go get 升级降级依赖版本，go get 指定版本升级降级依赖包，管理第三方库版本。
 | 原文链接：http://blog.xhldejj.cn/Article/details/343699.sHtML

原标题：安全笔记：文件下载接口路径校验安全
简介：nodejs 内存溢出问题排查修复，Node.js 程序 OOM 排查流程，定位内存泄露，调整内存限制修复崩溃。
 | 原文链接：http://blog.xhldejj.cn/Article/details/659594.sHtML

原标题：Git 误删提交代码恢复找回
简介：前端 pdf 预览渲染方案对比，对比前端 PDF 预览库，分析性能、兼容性，给出业务选型参考。
 | 原文链接：http://blog.xhldejj.cn/Article/details/536617.sHtML

原标题：运维笔记：系统内核参数调优生产服务器
简介：golang 工具函数库封装思路，Go 通用工具库封装思路，错误处理、类型转换，业务项目复用工具代码。
 | 原文链接：http://blog.xhldejj.cn/Article/details/595664.sHtML

原标题：排错：本地[localhost](https://localhost)可以，127001访问失败
简介：golang go 爬虫异步并发抓取，协程池控制并发抓取网页，多协程采集，提升爬虫采集速度。
 | 原文链接：http://blog.xhldejj.cn/Article/details/997113.sHtML

原标题：golang 系统设计 csrf 接口防护实现
简介：内存广播本地进程消息通知，实现进程内内存消息广播，进程内部模块之间事件通知解耦。
 | 原文链接：http://blog.xhldejj.cn/Article/details/233762.sHtML

原标题：golang 系统设计防重复提交实现
简介：golang dns 自定义解析器实现，自定义 dns 解析，指定 dns 服务器，控制域名解析逻辑，适配内网环境。
 | 原文链接：http://blog.xhldejj.cn/Article/details/581743.sHtML

原标题：新手指南：如何读懂开源项目报错日志
简介：前端水印防信息泄露实现，实现网页水印功能，页面叠加用户信息水印，防止页面截图信息外泄。
 | 原文链接：http://blog.xhldejj.cn/Article/details/389219.sHtML

原标题：开发记录：业务错误告警邮件通知组件实践
简介：golang go http 静态文件禁止目录遍历，http.FileServer 防止../ 路径穿越，了解底层安全实现。
 | 原文链接：http://blog.xhldejj.cn/Article/details/357314.sHtML

原标题：golang 系统设计单元测试边界条件覆盖思路
简介：接口限流逻辑简单模拟实现，编写简易限流逻辑，限制接口访问频次，保护服务，避免短时间大量请求压垮系统。
 | 原文链接：http://blog.xhldejj.cn/Article/details/987054.sHtML

原标题：Redis 热点 key 拆分降低集群压力
简介：golang go 测试文件命名规范，_test.go 测试文件，TestXxx 单元测试函数命名规范。
 | 原文链接：http://blog.xhldejj.cn/Article/details/115823.sHtML

原标题：性能复盘：消息队列大量小消息性能问题优化
简介：golang k8s go 服务 yaml 资源编写，k8s 部署 go 应用 deployment service，健康检查资源限制配置。
 | 原文链接：http://blog.xhldejj.cn/Article/details/501449.sHtML

原标题：Hands‑on：简易配置热更新组件开发实践
简介：golang gzip 压缩 http 响应，服务端开启 gzip 压缩，减小接口响应体积，降低网络传输耗时。
 | 原文链接：http://blog.xhldejj.cn/Article/details/351087.sHtML

原标题：golang net/http 超时全套配置
简介：golang go mod graph 查看依赖关系，go mod graph 打印依赖树，定位间接依赖来源，解决版本冲突。
 | 原文链接：http://blog.xhldejj.cn/Article/details/943910.sHtML

原标题：golang k8s pod 优雅关闭流程讲解
简介：CI 构建缓存加速编译速度，开启 CI 流水线依赖缓存，复用上一次构建依赖包，缩短流水线构建耗时。
 | 原文链接：http://blog.xhldejj.cn/Article/details/569461.sHtML

原标题：业务错误码体系设计方案
简介：eslint prettier 代码规范落地，配置 eslint 与 prettier，做代码检查格式化，统一前端团队代码风格。
 | 原文链接：http://blog.xhldejj.cn/Article/details/695564.sHtML

原标题：Architecture：大文件上传下载系统架构设计
简介：静态博客部署 GitHub Pages 教程，将静态博客项目部署至 GitHub Pages，完成线上访问，快速搭建个人技术博客站点。
 | 原文链接：http://blog.xhldejj.cn/Article/details/903253.sHtML

原标题：golang ip 限流黑名单实现方案
简介：golang sync/atomic 原子操作使用注意，理解原子操作内存顺序，规避原子操作错误使用带来 bug。
 | 原文链接：http://blog.xhldejj.cn/Article/details/552830.sHtML

原标题：golang 系统设计网关鉴权鉴权转发流程讲解
简介：golang go 信号处理优雅重启实现，USR2 触发程序重启，不关闭监听 socket 实现零停机升级。
 | 原文链接：http://blog.xhldejj.cn/Article/details/089117.sHtML

原标题：性能笔记：HTTP连接复用性能优化实践
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://blog.xhldejj.cn/Article/details/423522.sHtML

原标题：开发记录：长连接连接管理自动清理僵死连接
简介：golang accept 错误循环崩溃处理，accept 返回系统错误，处理临时错误，避免死循环占满 CPU。
 | 原文链接：http://blog.xhldejj.cn/Article/details/491416.sHtML

原标题：CDN 缓存刷新获取最新静态资源
简介：TCP 长连接参数优化 TIME_WAIT，调整 TCP 内核参数，优化长连接，减少大量 TIME_WAIT 连接占用资源。
 | 原文链接：http://blog.xhldejj.cn/Article/details/186263.sHtML

原标题：golang 系统设计开源 pr 评审合并流程实操
简介：nestjs 全局返回格式统一处理，Nest 全局拦截器统一包装接口返回数据，对外输出标准化响应格式。
 | 原文链接：http://blog.xhldejj.cn/Article/details/365250.sHtML

原标题：运维笔记：服务器磁盘内存监控告警配置
简介：golang trace 可视化分析协程阻塞，使用 trace 网页 UI，定位协程阻塞、系统调用阻塞、锁等待。
 | 原文链接：http://blog.xhldejj.cn/Article/details/598440.sHtML

原标题：TCP 长连接参数优化 TIME_WAIT
简介：golang bufio.Scanner 按行读取大文件，Scanner 逐行读取文本文件，处理超大日志 csv。
 | 原文链接：http://blog.xhldejj.cn/Article/details/337470.sHtML

原标题：架构复盘：数据库主从架构设计与延迟应对方案
简介：react hooks 常见陷阱避坑指南，梳理 React Hooks 高频踩坑点，依赖数组、闭包陷阱，写出稳定组件。
 | 原文链接：http://blog.xhldejj.cn/Article/details/995659.sHtML

原标题：golang 系统设计数据库版本迁移回滚方案
简介：golang 速率限制令牌桶实现，Go 实现令牌桶限流算法，可复用限流器，控制业务调用速率。
 | 原文链接：http://blog.xhldejj.cn/Article/details/630944.sHtML

原标题：Issue复现：内存泄漏定位完整复盘记录
简介：文件读写与异常捕获代码示例，演示文件读取写入操作，增加异常捕获逻辑，规避文件不存在、权限不足导致崩溃。
 | 原文链接：http://blog.xhldejj.cn/Article/details/154455.sHtML

原标题：Practice：实现接口mock动态返回不同响应
简介：golang benchmark 减少测试干扰，benchmark 执行循环 b.N，避免循环内部做非被测逻辑干扰结果。
 | 原文链接：http://blog.xhldejj.cn/Article/details/482037.sHtML

原标题：入门实践：简单错误码设计与使用规范
简介：golang sync.RWMutex 读写锁使用场景，读多写少场景读写锁，读共享写互斥，提升并发性能。
 | 原文链接：http://blog.xhldejj.cn/Article/details/143711.sHtML

原标题：架构复盘：数据库主从架构设计与延迟应对方案
简介：golang interface 接口使用避坑，interface 判 nil 坑点，理解接口底层结构，避免判空逻辑失效。
 | 原文链接：http://blog.xhldejj.cn/Article/details/969929.sHtML

原标题：快速上手简单的限流逻辑模拟实现
简介：golang 模糊测试 go fuzz 基础编写，Fuzz 测试函数，自动生成随机输入，发现代码崩溃 panic。
 | 原文链接：http://blog.xhldejj.cn/Article/details/246995.sHtML

原标题：golang 系统设计数据库扩容几种方式
简介：开源源码阅读拆解学习思路，分享阅读大型开源项目方法，从入口文件逐层拆解模块，降低源码学习门槛。
 | 原文链接：http://blog.xhldejj.cn/Article/details/459725.sHtML

原标题：架构复盘：网关层、应用层、数据库层层限流架构
简介：golang tls 证书加载配置 https 服务，加载证书密钥，搭建 golang https 服务，配置 tls 版本安全策略。
 | 原文链接：http://blog.xhldejj.cn/Article/details/185170.sHtML

原标题：Hands‑on：简易连接池原型实现理解原理
简介：异步异常捕获避免进程崩溃，捕获异步代码内部抛出异常，防止未捕获异常直接导致整个进程退出。
 | 原文链接：http://blog.xhldejj.cn/Article/details/414095.sHtML

原标题：线上故障：慢查询拖垮整个数据库服务
简介：JWT 工具封装令牌刷新过期，封装 JWT 工具类，实现令牌生成、校验、过期刷新整套令牌管理逻辑。
 | 原文链接：http://blog.xhldejj.cn/Article/details/423367.sHtML

原标题：golang 系统设计代码仓库权限管理方案
简介：golang recover 捕获 panic 使用边界，recover 只在 defer 内部生效，协程内部必须捕获本协程 panic。
 | 原文链接：http://blog.xhldejj.cn/Article/details/938158.sHtML

原标题：nestjs 框架模块化项目搭建
简介：golang go time 时区数据库内置，go 内置时区数据库，不用系统时区文件，容器时区不依赖系统。
 | 原文链接：http://blog.xhldejj.cn/Article/details/248598.sHtML

原标题：golang 系统设计分布式锁选型对比
简介：golang os 进程 pid 获取父进程 pid，os.Getpid 获取进程 id，获取父进程 pid，进程间识别。
 | 原文链接：http://blog.xhldejj.cn/Article/details/977639.sHtML

原标题：坑点：缓存过期策略不当引发业务异常
简介：日志切割配置防止日志丢失，配置日志切割轮转策略，日志按大小时间切割，防止日志文件丢失。
 | 原文链接：http://blog.xhldejj.cn/Article/details/607302.sHtML

四、架构设计｜Architecture
原标题：缓存过期打散防止缓存雪崩
简介：golang gitlab ci go 项目流水线编写，gitlab ci 流水线执行单元测试、静态检查、构建推送镜像。
 | 原文链接：http://blog.xhldejj.cn/Article/details/074479.sHtML

原标题：golang 系统设计熔断降级架构讲解
简介：golang 半关闭 tcp 连接 shutdown，tcp 连接 shutdown 半关闭，单向关闭读或者写，理解 tcp 关闭流程。
 | 原文链接：http://blog.xhldejj.cn/Article/details/498574.sHtML

原标题：nodejs 定时任务生产环境避坑
简介：golang smtp 邮件发送完整示例，调用 smtp 服务发送文本与 html 格式邮件，实现邮件通知能力。
 | 原文链接：http://blog.xhldejj.cn/Article/details/222688.sHtML

原标题：实战：搭建本地对象存储兼容S3协议demo
简介：golang redis list 队列简易消息队列，利用 Redis List 实现简易队列，完成任务入队消费基础能力。
 | 原文链接：http://blog.xhldejj.cn/Article/details/225090.sHtML

原标题：golang go test 覆盖率统计实操
简介：golang go sum 校验失败处理方案，go sum 校验不匹配，排查网络代理，清理缓存解决校验报错。
 | 原文链接：http://blog.xhldejj.cn/Article/details/087794.sHtML

原标题：golang redis set 集合去重业务
简介：golang 时间戳秒毫秒纳秒转换，Unix UnixMilli UnixNano 互相转换，区分单位避免时间逻辑 bug。
 | 原文链接：http://blog.xhldejj.cn/Article/details/455377.sHtML

原标题：Security：开源项目安全审计简易检查清单
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：http://blog.xhldejj.cn/Article/details/427309.sHtML

原标题：golang es 分页深分页性能优化
简介：golang tcp 四次挥手 go 程序行为，理解 tcp 四次挥手，处理连接关闭、重置、RST 包异常场景。
 | 原文链接：http://blog.xhldejj.cn/Article/details/792586.sHtML

原标题：golang jwt 鉴权中间件完整示例
简介：golang strconv 字符串类型转换，字符串转数字布尔，处理转换失败 error，避免 panic。
 | 原文链接：http://blog.xhldejj.cn/Article/details/544583.sHtML

原标题：OOMKilled 容器被杀完整排查
简介：后端分页查询逻辑代码实现，编写后端分页接口，处理页码、每页条数参数，优化大数据量查询返回结果。
 | 原文链接：http://blog.xhldejj.cn/Article/details/206360.sHtML

原标题：排错：macOS权限保护导致脚本执行被拦截
简介：对象存储上传下载权限实操，演示对象存储文件上传、下载、访问权限设置，适配业务文件存储场景。
 | 原文链接：http://blog.xhldejj.cn/Article/details/123184.sHtML

原标题：golang k8s ingress‑nginx 配置 ssl 证书
简介：golang defer 闭包变量捕获坑，defer 捕获循环变量引用，变量被复写，理解闭包变量捕获规则。
 | 原文链接：http://blog.xhldejj.cn/Article/details/428214.sHtML

原标题：golang 系统设计定时任务分片执行分布式思路
简介：项目语义化版本号规范管理，遵循语义化版本规范管理项目版本，明确主次版本变更含义。
 | 原文链接：http://blog.xhldejj.cn/Article/details/159287.sHtML

原标题：部署实践：数据库迁移脚本版本管理实践
简介：golang select 随机分支执行特性，多个 channel 就绪 select 随机选择，理解 select 行为特性。
 | 原文链接：http://blog.xhldejj.cn/Article/details/658515.sHtML

原标题：本地运行正常线上报错排查
简介：线上接口超时故障排查思路，从网络、数据库、代码逻辑逐层排查接口超时，定位慢请求根因。
 | 原文链接：http://blog.xhldejj.cn/Article/details/305038.sHtML

原标题：golang 重试退避机制代码实现
简介：golang 灰度发布流量权重路由实现，根据权重切分流量，部分流量访问新版本服务，实现灰度发布。
 | 原文链接：http://blog.xhldejj.cn/Article/details/729995.sHtML

原标题：坑点：版本号语义化理解错误依赖版本错乱
简介：golang 接口限流中间件开发，Gin 开发限流中间件，接口层实现访问频率限制，防护接口流量。
 | 原文链接：http://blog.xhldejj.cn/Article/details/057257.sHtML

原标题：踩坑：幂等键生成逻辑错误造成重复业务
简介：golang 数据库分表策略按时间分片，按时间维度分表，历史数据拆分，单表数据量控制保证查询性能。
 | 原文链接：http://blog.xhldejj.cn/Article/details/658373.sHtML

?
