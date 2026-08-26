最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang goroutine 池任务调度
简介：内存溢出问题现象识别排查，识别内存溢出现象，梳理排查方向，定位内存持续上涨引发服务崩溃问题。
 | 原文链接：http://wiki.huramu.asia/arts/396037.Doc

原标题：文件编码统一随机乱码修复
简介：golang go 种子初始化 rand 随机，rand 初始化种子，不初始化会固定序列，理解随机数种子行为。
 | 原文链接：http://wiki.huramu.asia/arts/722369.Doc

原标题：运维笔记：服务器日志轮转logrotate配置
简介：接口签名校验防篡改实现，实现请求签名验签逻辑，校验请求参数未被篡改，提升接口调用安全性。
 | 原文链接：http://wiki.huramu.asia/arts/801972.Doc

原标题：Architecture：事件溯源架构模式适用业务场景
简介：golang errgroup 协程组错误处理，errgroup 捕获协程错误，context 取消剩余协程，简化并发任务。
 | 原文链接：http://wiki.huramu.asia/arts/313453.Doc

原标题：排错：CI缓存策略错误，每次全量重新构建
简介：golang GC 调优 GOGC 参数调整，调整 GOGC 阈值，控制 GC 触发时机，权衡内存占用与 CPU 开销。
 | 原文链接：http://wiki.huramu.asia/arts/930712.Doc

原标题：Git 误删提交代码恢复找回
简介：手写简易 MQ 理解消息存储消费，手写极简消息队列 Demo，理解消息存储、投递、消费完整流程。
 | 原文链接：http://wiki.huramu.asia/arts/727014.Doc

原标题：坑点：软链接权限问题容器读取文件失败
简介：OOMKilled 容器被杀完整排查，排查容器被 OOM 终止完整流程，区分程序内存泄露和容器内存限制过小。
 | 原文链接：http://wiki.huramu.asia/arts/614414.Doc

原标题：Troubleshoot：磁盘打满导致服务全部不可用
简介：nodejs jwt 登录鉴权完整示例，Node 实现 JWT 登录鉴权，登录签发令牌，接口校验令牌身份。
 | 原文链接：http://wiki.huramu.asia/arts/444218.Doc

原标题：Architecture：鉴权授权系统架构设计思路
简介：golang 优雅处理 http 重定向逻辑，自定义控制 http 重定向跳转次数，防止无限重定向死循环。
 | 原文链接：http://wiki.huramu.asia/arts/751433.Doc

原标题：golang redis 缓存雪崩完整处理
简介：golang os 文件权限 mode，os.FileMode 文件权限，读写执行权限位，跨平台权限注意事项。
 | 原文链接：http://wiki.huramu.asia/arts/118484.Doc

原标题：GitHub Markdown 文档语法汇总
简介：golang html 模板渲染简单示例，Go HTML 模板渲染，服务端渲染页面，填充数据输出 HTML 页面。
 | 原文链接：http://wiki.huramu.asia/arts/421248.Doc

原标题：简易网关请求路由过滤模拟
简介：golang 开发环境快速搭建指南，快速完成 Golang 开发环境配置，工具链安装，环境变量设置，准备开发。
 | 原文链接：http://wiki.huramu.asia/arts/658100.Doc

原标题：golang docker 容器资源限制设置
简介：跨库查询性能优化处理，减少跨库关联查询，做数据冗余或者中间表，规避跨库查询性能低下。
 | 原文链接：http://wiki.huramu.asia/arts/830665.Doc

原标题：优化实践：业务定时任务错开高峰避免资源争抢
简介：灰度发布策略服务平滑升级，实现灰度发布逻辑，流量逐步切到新版本，出现问题快速回滚旧版本。
 | 原文链接：http://wiki.huramu.asia/arts/633181.Doc

原标题：nodejs redis 缓存业务实战
简介：golang gorm 原生 SQL 执行处理，复杂场景执行原生 SQL，处理返回结果集，兼顾性能与灵活性。
 | 原文链接：http://wiki.huramu.asia/arts/331384.Doc

原标题：包管理器依赖冲突解决方案
简介：golang context.WithCancel 手动取消上下文，WithCancel 生成可取消 ctx，手动调用 cancel 触发取消。
 | 原文链接：http://wiki.huramu.asia/arts/626797.Doc

原标题：Redis 热点 key 拆分降低集群压力
简介：golang 设置 net.Conn 读写超时，每次读写设置超时，防止连接永久阻塞挂起不返回。
 | 原文链接：http://wiki.huramu.asia/arts/818802.Doc

原标题：入门实践：搭建简单的热更新开发环境
简介：golang go 整洁架构代码组织实践，整洁架构依赖向内，解耦业务逻辑与外部基础设施。
 | 原文链接：http://wiki.huramu.asia/arts/195950.Doc

原标题：Troubleshooting：Redis大key引发集群卡顿
简介：GraphQL 接口查询优化实操，体验 GraphQL 查询方式，按需获取字段，减少冗余数据传输，优化接口请求效率。
 | 原文链接：http://wiki.huramu.asia/arts/410867.Doc

原标题：布隆过滤器误判问题修正
简介：golang go 爬虫异步并发抓取，协程池控制并发抓取网页，多协程采集，提升爬虫采集速度。
 | 原文链接：http://wiki.huramu.asia/arts/237516.Doc

原标题：golang redis hyperloglog 基数统计
简介：golang 接口限流中间件开发，Gin 开发限流中间件，接口层实现访问频率限制，防护接口流量。
 | 原文链接：http://wiki.huramu.asia/arts/233436.Doc

原标题：golang 系统设计 cpu 瓶颈定位优化方案
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://wiki.huramu.asia/arts/489402.Doc

原标题：golang redis 分布式计数器开发
简介：GitHub Markdown 文档语法汇总，整理 Markdown 常用语法，编写仓库 README、文档，提升开源项目文档排版质量。
 | 原文链接：http://wiki.huramu.asia/arts/421628.Doc

原标题：Issue：CI脚本超时，构建任务无故终止
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://wiki.huramu.asia/arts/371751.Doc

原标题：golang k8s 命名空间资源隔离方案
简介：golang 容器信号转发处理问题修复，docker/k8s 正确转发 SIGTERM 信号，保证 go 程序收到信号优雅退出。
 | 原文链接：http://wiki.huramu.asia/arts/663928.Doc

原标题：golang redis 批量 pipeline 实践
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://wiki.huramu.asia/arts/600395.Doc

原标题：架构复盘：消息队列在业务系统中边界与最佳实践
简介：本地运行正常线上报错排查，对比本地与线上环境差异，从配置、系统版本、文件权限定位线上独有的 bug。
 | 原文链接：http://wiki.huramu.asia/arts/357929.Doc

原标题：快速上手单元测试，写出第一个测试用例
简介：golang dns 自定义解析器实现，自定义 dns 解析，指定 dns 服务器，控制域名解析逻辑，适配内网环境。
 | 原文链接：http://wiki.huramu.asia/arts/598190.Doc

原标题：Debug：Websocket频繁断开重连根因分析
简介：golang go sum 校验失败处理方案，go sum 校验不匹配，排查网络代理，清理缓存解决校验报错。
 | 原文链接：http://wiki.huramu.asia/arts/782325.Doc

原标题：golang 系统设计密钥轮换安全实践思路
简介：极简方式搭建个人技术文档站点，使用轻量化工具快速部署文档站点，支持 markdown 编写，实现知识沉淀与对外分享。
 | 原文链接：http://wiki.huramu.asia/arts/912790.Doc

原标题：快速上手简单的限流逻辑模拟实现
简介：大事务拆分防止连接池耗尽，将执行时间很长的大事务拆分为小事务，减少事务占用连接时长。
 | 原文链接：http://wiki.huramu.asia/arts/333175.Doc

原标题：golang k8s 镜像拉取密钥配置
简介：golang 命令行交互 cobra 开发 cli，cobra 库开发功能完善命令行工具，子命令参数标志解析。
 | 原文链接：http://wiki.huramu.asia/arts/711161.Doc

原标题：Architecture：对象存储接入业务整体架构
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：http://wiki.huramu.asia/arts/858572.Doc

原标题：Troubleshooting：代理环境下证书校验失败HTTPS报错
简介：DNS TTL 配置域名切换生效，调整 DNS 解析 TTL，缩短缓存时间，域名变更后可以快速全网生效。
 | 原文链接：http://wiki.huramu.asia/arts/248774.Doc

原标题：实战：WebSocket断线重连完整业务处理实践
简介：golang excel 大文件读取流式解析，流式读取大 excel 文件，逐行解析数据，不加载全部内容进内存。
 | 原文链接：http://wiki.huramu.asia/arts/234403.Doc

原标题：限流组件计数器令牌桶模式实现
简介：webpack chunk 分包策略详解，讲解 webpack chunk 分包策略，拆分第三方包与业务代码，优化缓存复用。
 | 原文链接：http://wiki.huramu.asia/arts/966548.Doc

原标题：golang 系统设计缓存大 key 拆分优化实操
简介：golang csv 百万级数据导入数据库，流式读取 csv 分批写入数据库，避免一次性加载全部数据。
 | 原文链接：http://wiki.huramu.asia/arts/569023.Doc

原标题：API 大版本不兼容平滑迁移
简介：golang 优雅处理 http 重定向逻辑，自定义控制 http 重定向跳转次数，防止无限重定向死循环。
 | 原文链接：http://wiki.huramu.asia/arts/714572.Doc

原标题：golang 系统设计 gob msgpack 序列化对比
简介：golang sync.Map 高并发 map 使用场景，sync.Map 适用场景，读写实操，对比普通 map 加锁性能差异。
 | 原文链接：http://wiki.huramu.asia/arts/268408.Doc

原标题：Issue：本地可以访问，容器内部网络不通
简介：hosts 配置本地回环访问修复，修改 hosts 配置，修复 127.0.0.1 解析异常，本地服务访问失败问题。
 | 原文链接：http://wiki.huramu.asia/arts/174158.Doc


二、踩坑排错｜Troubleshooting
原标题：golang 系统设计 rest http 方法使用原则
简介：文件句柄上限调整上传随机失败，调高系统文件句柄上限，解决高并发上传场景随机打开文件失败。
 | 原文链接：http://wiki.huramu.asia/arts/718942.Doc

原标题：调优方案：CDN优化静态资源访问延迟
简介：分布式 ID 全局唯一生成方案，讲解分布式 ID 生成思路，实现全局唯一 ID，满足分布式系统主键生成需求。
 | 原文链接：http://wiki.huramu.asia/arts/702734.Doc

原标题：项目实践：搭建监控大盘查看系统关键指标
简介：golang go 单二进制文件静态编译交叉编译，交叉编译不同操作系统架构二进制文件，实现一次编译多平台运行。
 | 原文链接：http://wiki.huramu.asia/arts/784687.Doc

原标题：项目实践：幂等表实现接口幂等业务实践
简介：golang 表格驱动测试完整示例，表格驱动多组输入输出，批量执行测试用例，减少重复代码。
 | 原文链接：http://wiki.huramu.asia/arts/067872.Doc

原标题：Cookie Session 会话状态管理
简介：golang nats 轻量消息队列 go 开发，nats 高性能轻量消息系统，发布订阅模式异步解耦业务。
 | 原文链接：http://wiki.huramu.asia/arts/304357.Doc

原标题：service‑worker 离线缓存实践
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://wiki.huramu.asia/arts/383141.Doc

原标题：golang goroutine 协程基础实操
简介：时间同步修复令牌提前过期，服务器时间不同步导致 JWT 令牌提前过期，同步系统时间解决异常。
 | 原文链接：http://wiki.huramu.asia/arts/558911.Doc

原标题：golang gorm 批量插入性能调优
简介：数据库分表路由写入分片修正，修复分表路由逻辑，保证数据写入正确分片，不会出现数据丢失错乱。
 | 原文链接：http://wiki.huramu.asia/arts/740358.Doc

原标题：线程池拒绝策略任务丢失防护
简介：单元测试用例编写入门实操，讲解测试用例设计思路，演示基础单元测试代码，提升代码健壮性，提前发现逻辑 bug。
 | 原文链接：http://wiki.huramu.asia/arts/340655.Doc

原标题：开发记录：数据库悲观锁乐观锁业务场景实践
简介：RPC 报文大小上限调优大请求，调大 RPC 框架报文最大限制，支持传输大体积请求报文不被截断。
 | 原文链接：http://wiki.huramu.asia/arts/759972.Doc

原标题：前端错误监控上报系统搭建
简介：CI 构建缓存加速编译速度，开启 CI 流水线依赖缓存，复用上一次构建依赖包，缩短流水线构建耗时。
 | 原文链接：http://wiki.huramu.asia/arts/566489.Doc

原标题：golang gin 中间件执行顺序讲解
简介：golang socket 文件描述符继承重启，父进程传递 listener fd 给子进程，实现 go 程序零停机热重启。
 | 原文链接：http://wiki.huramu.asia/arts/074466.Doc

原标题：Troubleshooting：K8sPodOOMKilled完整排查流程
简介：多环境配置中心灵活切换方案，简易配置中心实现，支持多套环境配置，动态下发无需重启服务。
 | 原文链接：http://wiki.huramu.asia/arts/010140.Doc

原标题：开源实践：维护开源项目Issue管理经验总结
简介：golang 分布式追踪全链路日志打印，日志打印 traceId，各个服务日志可串联，排查跨服务调用问题。
 | 原文链接：http://wiki.huramu.asia/arts/191498.Doc

原标题：记一次第三方回调IP变动未更新防火墙拦截
简介：golang go 值传递引用传递理解，go 全部为值传递，指针本质拷贝指针值，理清参数传递行为。
 | 原文链接：http://wiki.huramu.asia/arts/337245.Doc

原标题：golang 系统设计开源项目贡献指南 contributing
简介：golang gorm 索引设置与优化技巧，定义数据库索引，理解索引生效条件，避免索引失效慢查询。
 | 原文链接：http://wiki.huramu.asia/arts/070635.Doc

原标题：nodejs 单元测试 jest 实操教程
简介：golang 容器时区设置镜像构建处理，镜像内部设置正确时区，解决容器时间与宿主机不一致。
 | 原文链接：http://wiki.huramu.asia/arts/628702.Doc

原标题：实战：接口压力测试实操，定位系统瓶颈
简介：golang go 程序抢占调度理解，理解 go 抢占式调度原理，长循环阻塞调度，造成协程调度延迟。
 | 原文链接：http://wiki.huramu.asia/arts/614812.Doc

原标题：记一次日志切割脚本错误直接清空业务日志
简介：多操作系统开发兼容处理，解决不同系统路径、换行符、权限差异，保证项目跨平台正常运行。
 | 原文链接：http://wiki.huramu.asia/arts/759097.Doc

原标题：golang k8s rbac 权限控制配置示例
简介：DNS TTL 配置域名切换生效，调整 DNS 解析 TTL，缩短缓存时间，域名变更后可以快速全网生效。
 | 原文链接：http://wiki.huramu.asia/arts/184038.Doc

原标题：运维笔记：服务器磁盘内存监控告警配置
简介：golang 消息队列 kafka 消费开发，Go 开发 Kafka 消费程序，消费消息执行业务，理解 Kafka 消费逻辑。
 | 原文链接：http://wiki.huramu.asia/arts/530042.Doc

原标题：Architecture：静态资源分发CDN整体架构思路
简介：WSL 文件权限访问异常修复，处理 WSL 环境文件权限错乱，调整权限配置，实现文件正常读写访问。
 | 原文链接：http://wiki.huramu.asia/arts/744807.Doc

原标题：坑点：限流计数器重置时机错误，绕过限流规则
简介：Redis 分布式锁高并发安全实现，基于 Redis 实现分布式锁，处理锁过期、续期，保障集群并发安全。
 | 原文链接：http://wiki.huramu.asia/arts/899336.Doc

原标题：线上故障：热点Key打满RedisCPU节点过载
简介：golang grpc 双向流双向通信开发，grpc 双向流，服务端客户端持续互发消息，长连接流式业务场景。
 | 原文链接：http://wiki.huramu.asia/arts/122656.Doc

原标题：SDK 版本兼容线上崩溃修复
简介：golang gorm 原生 SQL 执行处理，复杂场景执行原生 SQL，处理返回结果集，兼顾性能与灵活性。
 | 原文链接：http://wiki.huramu.asia/arts/780368.Doc

原标题：Git LFS 大文件推送失败解决
简介：磁盘 inode 耗尽文件创建失败，排查磁盘 inode 占用，清理大量小文件，恢复文件创建能力。
 | 原文链接：http://wiki.huramu.asia/arts/260667.Doc

原标题：Performance：数据库join优化，大表join规避
简介：golang go 测试文件命名规范，_test.go 测试文件，TestXxx 单元测试函数命名规范。
 | 原文链接：http://wiki.huramu.asia/arts/536262.Doc

原标题：架构笔记：事件驱动架构适用场景与坑点
简介：批量异步处理系统业务落地，构建批量异步处理系统，把耗时业务异步化，提升接口响应速度。
 | 原文链接：http://wiki.huramu.asia/arts/313095.Doc

原标题：Hands‑on：编写shell健康检查自动重启脚本
简介：golang go 死锁检测工具，静态检查、运行检测，发现 channel 锁导致死锁问题。
 | 原文链接：http://wiki.huramu.asia/arts/576468.Doc

原标题：项目实践：消息队列消息堆积模拟处理实践
简介：golang go mod 私有 git 仓库配置，配置 go mod 拉取私有仓库代码，处理私有模块依赖拉取问题。
 | 原文链接：http://wiki.huramu.asia/arts/036429.Doc

原标题：开发记录：短信发送服务封装，失败重试策略
简介：golang go xml 解析生成 xml 文档，encoding/xml 解析 xml，结构体标签映射 xml 节点属性。
 | 原文链接：http://wiki.huramu.asia/arts/017164.Doc

原标题：HelloDocker：编写你的第一个Dockerfile
简介：K8s 镜像拉取网络故障修复，排查 K8s 集群镜像拉取网络问题，配置镜像源，恢复镜像正常拉取。
 | 原文链接：http://wiki.huramu.asia/arts/934575.Doc

原标题：Practice：实现多级缓存本地缓存+Redis实践
简介：golang snowflake 时钟回拨解决方案，雪花算法处理时钟回拨，防止生成重复 ID，保证 ID 全局唯一。
 | 原文链接：http://wiki.huramu.asia/arts/007093.Doc

原标题：性能复盘：系统上下文切换过高性能下降调优
简介：Docker 容器入门镜像实操教程，介绍 Docker 基础概念，演示镜像拉取、容器启停，帮助新手建立容器化开发认知。
 | 原文链接：http://wiki.huramu.asia/arts/965998.Doc

原标题：从零搭建简单Mock接口服务
简介：ServiceWorker 缓存页面更新清理，处理 ServiceWorker 缓存，实现页面新版本更新，用户可以加载最新页面。
 | 原文链接：http://wiki.huramu.asia/arts/233581.Doc

原标题：golang 系统设计数据库扩容几种方式
简介：golang bufio.Scanner 按行读取大文件，Scanner 逐行读取文本文件，处理超大日志 csv。
 | 原文链接：http://wiki.huramu.asia/arts/865855.Doc

原标题：Architecture：灰度、蓝绿、金丝雀发布架构对比
简介：API 接口调试与异常处理实战，覆盖接口请求、参数组装、错误捕获，提供调试思路，高效定位接口返回异常问题。
 | 原文链接：http://wiki.huramu.asia/arts/956828.Doc

原标题：开发复盘：实现定时任务调度服务支持动态任务
简介：golang tcp 四次挥手 go 程序行为，理解 tcp 四次挥手，处理连接关闭、重置、RST 包异常场景。
 | 原文链接：http://wiki.huramu.asia/arts/380073.Doc

原标题：项目实践：消息队列消息确认机制业务实践
简介：项目目录结构规范化最佳实践，梳理源码、配置、静态资源目录划分，规范项目布局，提升代码可读性和可维护性。
 | 原文链接：http://wiki.huramu.asia/arts/559213.Doc

原标题：效率笔记：VSCode插件集合后端前端开发效率
简介：golang go1.18 + 泛型基础实操，go 泛型基础语法，泛型函数泛型类型，实现通用工具函数。
 | 原文链接：http://wiki.huramu.asia/arts/211137.Doc

三、实战开发｜Practice
原标题：移动端适配 rem vw 方案对比
简介：GraphQL 接口查询优化实操，体验 GraphQL 查询方式，按需获取字段，减少冗余数据传输，优化接口请求效率。
 | 原文链接：http://wiki.huramu.asia/arts/062286.Doc

原标题：浏览器本地存储安全使用技巧
简介：golang go 测试文件命名规范，_test.go 测试文件，TestXxx 单元测试函数命名规范。
 | 原文链接：http://wiki.huramu.asia/arts/204053.Doc

原标题：golang 系统设计性能瓶颈定位完整方法论
简介：golang makefile 多平台编译脚本，makefile 一键交叉编译多平台二进制，打包镜像，执行测试。
 | 原文链接：http://wiki.huramu.asia/arts/271568.Doc

原标题：golang 系统设计无锁编程思路简单示例
简介：golang map 并发读写 panic 解决方案，map 非并发安全，讲解加锁、sync.map 方案解决并发读写崩溃。
 | 原文链接：http://wiki.huramu.asia/arts/122647.Doc

原标题：Docker 多阶段构建镜像瘦身
简介：golang prometheus 指标埋点开发，业务埋点计数器、仪表盘、直方图，对接 prometheus 采集监控指标。
 | 原文链接：http://wiki.huramu.asia/arts/241518.Doc

原标题：入门实践：简易进度条CLI工具实现demo
简介：golang http 文件下载断点续传服务，服务端实现断点续传，支持大文件分段下载，提升大文件下载稳定性。
 | 原文链接：http://wiki.huramu.asia/arts/781013.Doc

原标题：快速上手简易网关转发逻辑模拟
简介：golang gin 静态资源访问配置，Gin 配置静态资源目录，直接对外提供静态文件访问服务。
 | 原文链接：http://wiki.huramu.asia/arts/869897.Doc

原标题：golang 系统设计定时任务分布式锁
简介：golang 钉钉企业微信告警消息推送，go 调用企业微信钉钉接口，推送告警通知、业务消息。
 | 原文链接：http://wiki.huramu.asia/arts/121449.Doc

原标题：Practice：实现异步任务结果查询回调实践
简介：开源源码阅读拆解学习思路，分享阅读大型开源项目方法，从入口文件逐层拆解模块，降低源码学习门槛。
 | 原文链接：http://wiki.huramu.asia/arts/855511.Doc

原标题：golang 容器健康检查接口开发
简介：接口限流逻辑简单模拟实现，编写简易限流逻辑，限制接口访问频次，保护服务，避免短时间大量请求压垮系统。
 | 原文链接：http://wiki.huramu.asia/arts/030773.Doc

原标题：手写简易 RPC 服务通信原型
简介：golang 速率限制令牌桶实现，Go 实现令牌桶限流算法，可复用限流器，控制业务调用速率。
 | 原文链接：http://wiki.huramu.asia/arts/593694.Doc

原标题：部署实践：服务器时间同步chrony配置
简介：程序预加载加快服务启动速度，把高频使用资源提前预加载，减少请求阶段初始化，加快服务启动。
 | 原文链接：http://wiki.huramu.asia/arts/200959.Doc

原标题：安全实践：请求输入校验防御恶意参数
简介：RPC 报文大小上限调优大请求，调大 RPC 框架报文最大限制，支持传输大体积请求报文不被截断。
 | 原文链接：http://wiki.huramu.asia/arts/236238.Doc

原标题：Architecture：静态资源分发CDN整体架构思路
简介：golang defer 执行顺序与坑点，defer 后进先出，循环内部 defer 陷阱，资源释放正确写法。
 | 原文链接：http://wiki.huramu.asia/arts/209067.Doc

原标题：架构笔记：业务操作审计日志系统架构设计
简介：上传接口跨域配置特殊适配，针对文件上传接口，适配复杂请求，修复上传场景下跨域失效问题。
 | 原文链接：http://wiki.huramu.asia/arts/222024.Doc

原标题：接口签名验签完整安全方案
简介：golang go‑zero rpc 微服务开发，go‑zero 定义 proto，生成 rpc 服务代码，实现微服务调用。
 | 原文链接：http://wiki.huramu.asia/arts/914407.Doc

原标题：golang 系统设计监控大盘故障快速定位思路
简介：golang io.MultiReader MultiWriter 拼接流，多个 reader 拼接，多 writer 同时写入一份数据。
 | 原文链接：http://wiki.huramu.asia/arts/995911.Doc

原标题：架构复盘：业务系统中如何合理使用分库分表
简介：golang proto 可选字段处理方案，protobuf 可选字段正确判断，区分未赋值与零值，业务逻辑不出现偏差。
 | 原文链接：http://wiki.huramu.asia/arts/717361.Doc

原标题：golang 系统设计 sql 注入 xss 防护实践
简介：golang kitex 超时重试熔断配置，kitex 配置调用超时、重试、熔断策略，保障微服务调用稳定性。
 | 原文链接：http://wiki.huramu.asia/arts/418145.Doc

原标题：HelloDocker：编写你的第一个Dockerfile
简介：golang go 逃逸分析实操查看，go build‑gcflags=-m 查看逃逸分析，减少堆分配优化程序性能。
 | 原文链接：http://wiki.huramu.asia/arts/266684.Doc

原标题：golang redis 缓存更新策略讲解
简介：golang go http 服务器优雅关闭完整代码，http.Server Shutdown，等待现有请求处理完成关闭服务。
 | 原文链接：http://wiki.huramu.asia/arts/537320.Doc

原标题：安全复盘：定时任务权限过大风险管控
简介：环境变量不生效问题修复，排查环境变量加载顺序、作用域问题，修复环境变量读取不到的异常。
 | 原文链接：http://wiki.huramu.asia/arts/021248.Doc

原标题：内网 DNS 不稳定随机报错排查
简介：golang go‑fuzz 模糊测试开发，go fuzz 模糊测试，自动构造异常输入，发现代码隐藏 bug。
 | 原文链接：http://wiki.huramu.asia/arts/001287.Doc

原标题：Architecture：鉴权授权系统架构设计思路
简介：nestjs 框架模块化项目搭建，从零搭建 NestJS 项目，模块化拆分业务，搭建规范后端项目骨架。
 | 原文链接：http://wiki.huramu.asia/arts/310812.Doc

原标题：Performance：避免大报文，减少内存占用优化
简介：HTTP 状态码请求头完整梳理，汇总常用 HTTP 状态码与请求头含义，帮助快速看懂网络请求，排查接口通信问题。
 | 原文链接：http://wiki.huramu.asia/arts/798618.Doc

原标题：记一次GC频繁，服务CPU持续高负载排查
简介：golang go 程序运行时动态修改配置，运行时热加载配置结构体，原子更新保证并发读取安全。
 | 原文链接：http://wiki.huramu.asia/arts/078573.Doc

原标题：golang 系统设计无锁编程思路简单示例
简介：前端虚拟列表大数据渲染优化，实现虚拟滚动列表，只渲染可视区域 DOM，上万条数据页面流畅渲染。
 | 原文链接：http://wiki.huramu.asia/arts/382911.Doc

原标题：golang redis 持久化 RDB AOF 对比
简介：golang net/http/httptest 服务端模拟，httptest.NewRecorder 记录 handler 响应，校验返回状态码 body。
 | 原文链接：http://wiki.huramu.asia/arts/557206.Doc

原标题：Security：文件路径穿越漏洞完整防护
简介：golang redis bloom 布隆过滤器 go‑redis，go‑redis 布隆过滤器，海量数据判断是否存在，减少数据库查询。
 | 原文链接：http://wiki.huramu.asia/arts/081988.Doc

原标题：golang k8s hpa 水平 pod 自动扩缩容
简介：golang redis lua 脚本原子操作，使用 Lua 脚本实现原子逻辑，减少网络往返，保障多命令原子执行。
 | 原文链接：http://wiki.huramu.asia/arts/285104.Doc

原标题：踩坑：大事务引发数据库连接池耗尽
简介：golang 接口返回统一封装工具，封装 Go 接口统一返回工具，标准化成功失败返回结构体。
 | 原文链接：http://wiki.huramu.asia/arts/879322.Doc

原标题：Hands‑on：简易的事件订阅发布组件开发实践
简介：golang delve 远程调试 go 线上程序，delve 远程调试，线上环境附加进程调试排查线上 bug。
 | 原文链接：http://wiki.huramu.asia/arts/752945.Doc

原标题：开发记录：分布式ID生成器实现与压力测试
简介：程序预加载加快服务启动速度，把高频使用资源提前预加载，减少请求阶段初始化，加快服务启动。
 | 原文链接：http://wiki.huramu.asia/arts/115818.Doc

原标题：线程调度优化减少上下文切换
简介：golang goroutine 协程基础实操，Goroutine 基础实操案例，启动协程执行任务，理解轻量级协程特性。
 | 原文链接：http://wiki.huramu.asia/arts/637438.Doc

原标题：线上故障：消息队列重复消费业务处理异常
简介：golang mysql 长连接检测保活设置，配置 mysql 连接保活检测，剔除失效连接，避免拿到断开无效数据库连接。
 | 原文链接：http://wiki.huramu.asia/arts/377437.Doc

原标题：方案设计：多租户系统架构三种实现模式对比
简介：OOMKilled 容器被杀完整排查，排查容器被 OOM 终止完整流程，区分程序内存泄露和容器内存限制过小。
 | 原文链接：http://wiki.huramu.asia/arts/224852.Doc

原标题：项目实践：Docker镜像安全扫描本地实操
简介：golang 命令行彩色输出终端，终端彩色文字输出，进度条交互，优化命令行工具用户体验。
 | 原文链接：http://wiki.huramu.asia/arts/784497.Doc

原标题：设计思考：大促系统架构压测改造整体思路
简介：日志敏感信息脱敏泄露防护，日志打印时自动脱敏手机号身份证，避免日志输出泄露用户隐私数据。
 | 原文链接：http://wiki.huramu.asia/arts/089087.Doc

原标题：golang mongodb 分页性能优化技巧
简介：数据库主从延迟业务兼容处理，业务适配主从复制延迟，避免读取从库拿到还未同步完成旧数据。
 | 原文链接：http://wiki.huramu.asia/arts/707462.Doc

原标题：安全笔记：请求头伪造IP漏洞防护
简介：磁盘占满服务不可用清理方案，定位磁盘占用大文件，清理日志、缓存文件，恢复磁盘可用空间。
 | 原文链接：http://wiki.huramu.asia/arts/947765.Doc

四、架构设计｜Architecture
原标题：golang 系统设计 rest 分页排序过滤参数规范
简介：golang go 二进制安全 strip 减小体积，strip 剥离二进制调试符号，缩小程序二进制文件体积。
 | 原文链接：http://wiki.huramu.asia/arts/500497.Doc

原标题：安全实践：容器最小化镜像减少攻击面
简介：golang 任务失败重试与死信队列，异步任务失败自动重试，超过重试次数进入死信队列人工处理。
 | 原文链接：http://wiki.huramu.asia/arts/264947.Doc

原标题：golang grafana 监控面板简单配置
简介：golang grpc 客户端流上传数据，客户端流式请求，客户端分批上传数据到服务端，适合大文件传输。
 | 原文链接：http://wiki.huramu.asia/arts/872413.Doc

原标题：入门实践：简单错误码设计与使用规范
简介：golang http 服务优雅关闭完整示例，接收终止信号，停止接收新请求，等待现有请求处理完毕后退出服务。
 | 原文链接：http://wiki.huramu.asia/arts/084686.Doc

原标题：踩坑记录：时间戳精度不一致引发判断错误
简介：golang 错误静默忽略风险规避，禁止空忽略错误，必须处理或者明确注释为什么忽略错误。
 | 原文链接：http://wiki.huramu.asia/arts/932605.Doc

原标题：坑点：软链接权限问题容器读取文件失败
简介：golang 单元测试 mock http 请求，mock HTTP 外部接口，单元测试不依赖外部网络，保证用例稳定运行。
 | 原文链接：http://wiki.huramu.asia/arts/006577.Doc

原标题：golang 系统设计缓存降级开关快速切库实现
简介：系统字符集统一乱码修复，统一数据库、程序、操作系统字符集，解决中文乱码显示异常问题。
 | 原文链接：http://wiki.huramu.asia/arts/666817.Doc

原标题：新手向：开源项目依赖安装失败排查
简介：golang gin 中间件执行顺序讲解，理解 Gin 中间件注册顺序，区分前置后置逻辑，规避中间件顺序 bug。
 | 原文链接：http://wiki.huramu.asia/arts/914552.Doc

原标题：设计思考：业务系统如何做故障隔离架构
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://wiki.huramu.asia/arts/992771.Doc

原标题：golang 系统设计 api 接口兼容性设计原则
简介：golang hystrix 模式简易熔断实现，简易熔断组件，错误率达到阈值触发熔断，快速失败保护下游。
 | 原文链接：http://wiki.huramu.asia/arts/846822.Doc

原标题：开发记录：接口请求日志记录完整中间件实现
简介：golang go‑zero 框架项目快速搭建，go‑zero 脚手架生成微服务项目，api rpc 服务快速开发。
 | 原文链接：http://wiki.huramu.asia/arts/985255.Doc

原标题：golang docker compose 环境变量
简介：golang pdf 生成 go 服务端生成 pdf，服务端动态生成 pdf 报表文件，直接输出下载给到前端。
 | 原文链接：http://wiki.huramu.asia/arts/488240.Doc

原标题：golang 系统设计降级策略开关配置方案
简介：golang interface {} 类型断言类型转换，类型断言 ok 模式，避免断言失败触发 panic。
 | 原文链接：http://wiki.huramu.asia/arts/743159.Doc

原标题：开发记录：业务错误告警邮件通知组件实践
简介：golang channel 关闭规则与坑点，关闭已经关闭 channel 会 panic，判断 channel 是否关闭正确写法。
 | 原文链接：http://wiki.huramu.asia/arts/740781.Doc

原标题：OpenSource：开源项目版本发布CHANGELOG编写
简介：进程线程并发基础概念讲解，区分进程与线程，讲解调度逻辑，理解并发执行原理，为高并发业务开发打基础。
 | 原文链接：http://wiki.huramu.asia/arts/667451.Doc

原标题：Troubleshoot：CPU调度频繁上下文切换性能下降
简介：golang docker compose 开发环境 go 服务，docker compose 编排 go 服务与中间件，本地一键拉起整套开发环境。
 | 原文链接：http://wiki.huramu.asia/arts/862299.Doc

原标题：DevOps：私有镜像仓库搭建与权限管控
简介：项目依赖安全扫描漏洞防范，扫描项目第三方依赖包，修复存在安全漏洞依赖，防范供应链攻击。
 | 原文链接：http://wiki.huramu.asia/arts/047180.Doc

原标题：react 状态管理方案选型对比
简介：golang k8s informer 机制原理理解，informer 监听 k8s 资源变更，本地缓存，减少 apiserver 压力。
 | 原文链接：http://wiki.huramu.asia/arts/807127.Doc

?
