最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计开源项目 issue pr 模板编写
简介：golang go1.18 + 泛型基础实操，go 泛型基础语法，泛型函数泛型类型，实现通用工具函数。
 | 原文链接：http://wiki.nmnc76.asia/arts/341417.Doc

原标题：快速入门WebSocket，实现简易双向通信demo
简介：golang grpc 错误状态码标准化，grpc 标准化错误返回，定义业务错误码，客户端解析处理业务异常。
 | 原文链接：http://wiki.nmnc76.asia/arts/346210.Doc

原标题：开源项目本地运行排错完整清单
简介：服务器时钟同步任务错乱修复，配置服务器 NTP 时间同步，保证集群所有机器时间保持一致。
 | 原文链接：http://wiki.nmnc76.asia/arts/080353.Doc

原标题：依赖版本冲突兼容修复方案
简介：服务启动依赖顺序配置正确，配置服务启动依赖关系，保证依赖服务就绪之后再启动当前业务服务。
 | 原文链接：http://wiki.nmnc76.asia/arts/774983.Doc

原标题：线上故障：Redis内存淘汰策略错误数据丢失
简介：消息队列生产消费模型入门，讲解消息队列生产、存储、消费流程，理解异步解耦、削峰，掌握消息队列基础概念。
 | 原文链接：http://wiki.nmnc76.asia/arts/012392.Doc

原标题：排错：对象存储跨域配置不生效前端上传失败
简介：超大数据集分页性能优化方案，对比不同分页方案，针对海量数据集做分页性能优化，解决越翻越慢。
 | 原文链接：http://wiki.nmnc76.asia/arts/374384.Doc

原标题：快速启动：本地运行开源项目排障清单
简介：golang docker 镜像构建最佳实践，Go 项目 Docker 镜像构建最佳实践，减小镜像体积，安全构建。
 | 原文链接：http://wiki.nmnc76.asia/arts/266879.Doc

原标题：golang 系统设计开源 pr 评审合并流程实操
简介：调试工具断点调试变量查看技巧，演示断点设置、变量监视、调用栈查看，借助调试工具高效排查业务逻辑错误。
 | 原文链接：http://wiki.nmnc76.asia/arts/953021.Doc

原标题：安全笔记：Git仓库密钥硬编码泄露处理方案
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://wiki.nmnc76.asia/arts/047344.Doc

原标题：golang redis 五种数据结构实战
简介：golang context 取消传播机制，父 ctx 取消，所有派生子 context 全部被取消，理解上下文传播。
 | 原文链接：http://wiki.nmnc76.asia/arts/600758.Doc

原标题：架构笔记：数据库读写分离架构数据不一致应对
简介：golang html 模板渲染简单示例，Go HTML 模板渲染，服务端渲染页面，填充数据输出 HTML 页面。
 | 原文链接：http://wiki.nmnc76.asia/arts/506093.Doc

原标题：部署实践：HTTPS证书自动续期配置实践
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://wiki.nmnc76.asia/arts/376088.Doc

原标题：避坑：CookieSecure属性造成测试环境登录失败
简介：golang recover 捕获 panic 使用边界，recover 只在 defer 内部生效，协程内部必须捕获本协程 panic。
 | 原文链接：http://wiki.nmnc76.asia/arts/482547.Doc

原标题：开发记录：文件锁实现多进程互斥实践
简介：golang go 输入数据校验防御，所有外部入参严格校验长度格式，防止恶意输入造成业务异常。
 | 原文链接：http://wiki.nmnc76.asia/arts/108804.Doc

原标题：实战：Nginx实现文件限速下载配置实践
简介：golang redis stream 消息队列实战，redis stream 实现可靠消息队列，消费组、ack 确认，消息不丢失。
 | 原文链接：http://wiki.nmnc76.asia/arts/771326.Doc

原标题：HelloCI：理解持续集成基础工作流程
简介：nestjs 框架模块化项目搭建，从零搭建 NestJS 项目，模块化拆分业务，搭建规范后端项目骨架。
 | 原文链接：http://wiki.nmnc76.asia/arts/077666.Doc

原标题：部署复盘：金丝雀发布流量切分实操方案
简介：vite 插件开发自定义构建逻辑，开发自定义 vite 插件，介入构建生命周期，实现项目个性化构建逻辑。
 | 原文链接：http://wiki.nmnc76.asia/arts/260285.Doc

原标题：实战：Redis管道批量操作性能优化实践
简介：golang prometheus http 接口暴露指标，暴露 prometheus metrics 接口，输出业务运行指标，接入监控告警系统。
 | 原文链接：http://wiki.nmnc76.asia/arts/078741.Doc

原标题：Security：密码存储哈希加盐最佳实践
简介：golang 日志输出 stdout 标准输出规范，容器环境日志输出到 stdout，由容器平台统一采集日志文件。
 | 原文链接：http://wiki.nmnc76.asia/arts/741447.Doc

原标题：CI 流水线超时时间延长配置
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：http://wiki.nmnc76.asia/arts/118106.Doc

原标题：golang 系统设计线上日志快速检索技巧
简介：开源源码阅读拆解学习思路，分享阅读大型开源项目方法，从入口文件逐层拆解模块，降低源码学习门槛。
 | 原文链接：http://wiki.nmnc76.asia/arts/970802.Doc

原标题：记一次GC频繁，服务CPU持续高负载排查
简介：golang csv 读写批量数据处理，Go 读写 CSV 文件，批量导入导出业务数据，处理 CSV 格式解析。
 | 原文链接：http://wiki.nmnc76.asia/arts/312524.Doc

原标题：包管理器依赖缓存清理
简介：golang bufio.Scanner 按行读取大文件，Scanner 逐行读取文本文件，处理超大日志 csv。
 | 原文链接：http://wiki.nmnc76.asia/arts/372271.Doc

原标题：golang 优雅处理 http 超时设置
简介：golang go1.18 + 泛型基础实操，go 泛型基础语法，泛型函数泛型类型，实现通用工具函数。
 | 原文链接：http://wiki.nmnc76.asia/arts/926540.Doc

原标题：Debug：时间回拨，定时任务调度逻辑错乱
简介：golang go 逃逸分析实操查看，go build‑gcflags=-m 查看逃逸分析，减少堆分配优化程序性能。
 | 原文链接：http://wiki.nmnc76.asia/arts/964989.Doc

原标题：新手教程：本地环境变量配置全流程
简介：线程池拒绝策略任务丢失防护，合理设置线程池拒绝策略，处理任务队列满场景，避免业务任务直接丢失。
 | 原文链接：http://wiki.nmnc76.asia/arts/344963.Doc

原标题：Troubleshoot：磁盘inode耗尽，无法新建文件
简介：nodejs 集群模式多核利用实现，使用 cluster 集群模式，充分利用服务器多核 CPU，提升服务处理能力。
 | 原文链接：http://wiki.nmnc76.asia/arts/532942.Doc

原标题：golang 系统设计故障止损降级回滚执行原则
简介：golang goroutine 协程基础实操，Goroutine 基础实操案例，启动协程执行任务，理解轻量级协程特性。
 | 原文链接：http://wiki.nmnc76.asia/arts/563323.Doc

原标题：golang es 查询语句 DSL 实操
简介：golang 协程 panic 捕获防止崩溃，协程内部捕获 panic，防止单个协程恐慌造成整个 Go 进程崩溃。
 | 原文链接：http://wiki.nmnc76.asia/arts/154672.Doc

原标题：架构笔记：海量日志处理架构选型与实践
简介：golang strconv 字符串类型转换，字符串转数字布尔，处理转换失败 error，避免 panic。
 | 原文链接：http://wiki.nmnc76.asia/arts/601520.Doc

原标题：任务执行锁防止并发重复调度
简介：golang go‑fuzz 模糊测试开发，go fuzz 模糊测试，自动构造异常输入，发现代码隐藏 bug。
 | 原文链接：http://wiki.nmnc76.asia/arts/723691.Doc

原标题：安全复盘：OAuth2授权流程安全坑点汇总
简介：全量回归测试提升代码质量，搭建全量回归测试集，版本发布执行回归测试，避免迭代引入旧 bug。
 | 原文链接：http://wiki.nmnc76.asia/arts/072979.Doc

原标题：golang 系统设计日志检索排查线上问题实操技巧
简介：golang 图片处理 go 图片裁剪压缩，golang 图像处理库，图片缩放裁剪水印，服务端图片处理。
 | 原文链接：http://wiki.nmnc76.asia/arts/684427.Doc

原标题：性能复盘：磁盘Swap大量使用系统卡顿优化
简介：分页逻辑错误数据漏查修复，修复分页查询逻辑漏洞，解决分页漏数据、重复返回数据等业务问题。
 | 原文链接：http://wiki.nmnc76.asia/arts/012195.Doc

原标题：golang 系统设计密码存储哈希加盐实现
简介：golang alertmanager 告警配置实践，alertmanager 配置告警路由，告警发送邮件钉钉，异常及时通知运维。
 | 原文链接：http://wiki.nmnc76.asia/arts/692808.Doc

原标题：golang mysql 悲观锁乐观锁实现
简介：vue3 组合式 API 业务开发实战，Vue3 组合式 API 业务实战示例，拆分业务逻辑组合复用，提升代码组织。
 | 原文链接：http://wiki.nmnc76.asia/arts/559431.Doc

原标题：零基础理解模块化与组件化基础思想
简介：golang go 终端 pty 伪终端操作，pty 启动子进程，模拟终端交互，实现交互式命令调用。
 | 原文链接：http://wiki.nmnc76.asia/arts/483871.Doc

原标题：排错：多实例部署session共享失效登录失效
简介：golang 处理连接被重置 reset 错误，识别 connection reset by peer，对端关闭连接异常处理逻辑。
 | 原文链接：http://wiki.nmnc76.asia/arts/631872.Doc

原标题：Practice：从零实现轻量后端接口服务完整实践
简介：golang go 终端 pty 伪终端操作，pty 启动子进程，模拟终端交互，实现交互式命令调用。
 | 原文链接：http://wiki.nmnc76.asia/arts/371381.Doc

原标题：一次JWT令牌过期时间异常问题复盘
简介：golang go 并发模式 fan‑out fan‑in，fanout 分发任务 fanin 汇总结果，多协程并发处理任务。
 | 原文链接：http://wiki.nmnc76.asia/arts/891610.Doc


二、踩坑排错｜Troubleshooting
原标题：nestjs 拦截器过滤器管道实战
简介：DNS 解析异常第三方调用故障，排查 DNS 解析故障，修复域名解析，恢复第三方接口网络调用。
 | 原文链接：http://wiki.nmnc76.asia/arts/116054.Doc

原标题：golang 系统设计数据库索引设计方法论
简介：JSON XML 数据解析处理示例，演示两种格式数据解析与序列化，增加异常捕获，处理格式错乱导致解析失败。
 | 原文链接：http://wiki.nmnc76.asia/arts/017095.Doc

原标题：golang 系统设计文件存储选型对比
简介：Git 分支切换合并删除完整操作，实操分支全生命周期操作，包含切换、合并、删除，熟悉日常开发分支处理流程。
 | 原文链接：http://wiki.nmnc76.asia/arts/344337.Doc

原标题：DNS TTL 配置域名切换生效
简介：无用对象回收抑制内存上涨，优化对象生命周期，及时释放不再使用对象，抑制内存持续不断增长。
 | 原文链接：http://wiki.nmnc76.asia/arts/968570.Doc

原标题：golang 系统设计接口向前兼容改造实操
简介：DNS 解析异常第三方调用故障，排查 DNS 解析故障，修复域名解析，恢复第三方接口网络调用。
 | 原文链接：http://wiki.nmnc76.asia/arts/451873.Doc

原标题：Hands‑on：简易反向代理中间件实现
简介：请求重试组件退避策略实现，封装重试组件，实现指数退避策略，避免大量请求同时重试压垮下游。
 | 原文链接：http://wiki.nmnc76.asia/arts/596815.Doc

原标题：部署复盘：容器OOM问题完整排查流程
简介：golang accept 错误循环崩溃处理，accept 返回系统错误，处理临时错误，避免死循环占满 CPU。
 | 原文链接：http://wiki.nmnc76.asia/arts/674436.Doc

原标题：golang 系统设计无锁编程思路简单示例
简介：golang crypto 密码学最佳实践，go crypto 包加密签名，规避不安全算法，使用安全密码套件。
 | 原文链接：http://wiki.nmnc76.asia/arts/234344.Doc

原标题：Fork 开源项目同步上游代码
简介：golang go 初始化顺序包变量 init 函数，包级变量初始化，init 执行顺序，理解包加载执行流程。
 | 原文链接：http://wiki.nmnc76.asia/arts/000802.Doc

原标题：nestjs 框架模块化项目搭建
简介：数据库主从延迟业务兼容处理，业务适配主从复制延迟，避免读取从库拿到还未同步完成旧数据。
 | 原文链接：http://wiki.nmnc76.asia/arts/406247.Doc

原标题：golang kafka 生产者参数调优
简介：文件句柄上限调整上传随机失败，调高系统文件句柄上限，解决高并发上传场景随机打开文件失败。
 | 原文链接：http://wiki.nmnc76.asia/arts/471392.Doc

原标题：实践：API接口文档自动导出离线文档实践
简介：golang 换行符统一处理，文本文件读写统一换行符，规避不同系统换行符带来解析异常。
 | 原文链接：http://wiki.nmnc76.asia/arts/371694.Doc

原标题：golang docker 多阶段构建 go 镜像
简介：浏览器本地存储安全使用技巧，讲解 localStorage、sessionStorage 使用边界，规避 XSS 泄露存储数据。
 | 原文链接：http://wiki.nmnc76.asia/arts/200402.Doc

原标题：Security：文件路径穿越漏洞完整防护
简介：golang go 排序 sort 包自定义排序，sort 包实现自定义排序逻辑，对切片按业务规则排序。
 | 原文链接：http://wiki.nmnc76.asia/arts/852585.Doc

原标题：golang 熔断降级简易组件开发
简介：读懂开源项目 README 实用技巧，教你快速解析开源项目说明文档，提取安装、运行、配置关键信息，快速上手项目。
 | 原文链接：http://wiki.nmnc76.asia/arts/227960.Doc

原标题：新手教程：gitstash暂存工作区变更实操
简介：golang go 自定义错误类型实现，自定义 error 结构体，携带错误码、堆栈信息，统一业务错误。
 | 原文链接：http://wiki.nmnc76.asia/arts/453517.Doc

原标题：golang 系统设计代码评审关注点 checklist 清单
简介：golang tar gz 压缩解压处理，tar.gz 归档压缩解压，服务端日志备份、文件打包场景使用。
 | 原文链接：http://wiki.nmnc76.asia/arts/878063.Doc

原标题：golang k8s 命名空间资源隔离方案
简介：golang go 自定义错误类型实现，自定义 error 结构体，携带错误码、堆栈信息，统一业务错误。
 | 原文链接：http://wiki.nmnc76.asia/arts/485983.Doc

原标题：Debug：静态资源缓存策略错误，用户看不到更新
简介：golang os.Signal 信号监听完整示例，signal.Notify 监听信号，缓冲 channel 防止信号丢失。
 | 原文链接：http://wiki.nmnc76.asia/arts/126805.Doc

原标题：Hands‑on：手写简单RPC框架基础通信版本
简介：端口占用释放资源重启服务，查找占用端口进程，结束占用进程，释放端口，让服务能够正常启动监听。
 | 原文链接：http://wiki.nmnc76.asia/arts/971684.Doc

原标题：开发记录：网关实现接口鉴权、限流、日志打印
简介：依赖安装失败全方位排错，从网络、镜像源、权限、版本多角度，定位依赖安装失败，给出对应修复手段。
 | 原文链接：http://wiki.nmnc76.asia/arts/925733.Doc

原标题：架构复盘：业务系统中如何合理使用分库分表
简介：Nginx 丢失请求头配置修正，修复 Nginx 代理转发丢失请求头配置，保证上游服务拿到完整请求头信息。
 | 原文链接：http://wiki.nmnc76.asia/arts/304648.Doc

原标题：golang redis 限流几种实现方案
简介：SDK 版本兼容线上崩溃修复，处理 SDK 版本升级之后线上崩溃，定位 API 变更，做版本兼容适配改造。
 | 原文链接：http://wiki.nmnc76.asia/arts/674325.Doc

原标题：golang 系统设计熔断降级架构讲解
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://wiki.nmnc76.asia/arts/966467.Doc

原标题：Troubleshoot：跨域偶现失败难以复现问题
简介：golang go 项目依赖冲突解决完整思路，定位冲突包，replace、exclude、升级降级解决版本冲突。
 | 原文链接：http://wiki.nmnc76.asia/arts/782239.Doc

原标题：快速上手阅读开源项目源码的入门思路
简介：容器内存扩容 OOM 被杀死修复，调高容器内存限制，优化程序内存占用，避免程序被 OOM 终止。
 | 原文链接：http://wiki.nmnc76.asia/arts/169231.Doc

原标题：golang mysql 分表自增 id 方案
简介：golang bufio.Scanner 按行读取大文件，Scanner 逐行读取文本文件，处理超大日志 csv。
 | 原文链接：http://wiki.nmnc76.asia/arts/481470.Doc

原标题：文件句柄上限调整上传随机失败
简介：golang prometheus 指标埋点开发，业务埋点计数器、仪表盘、直方图，对接 prometheus 采集监控指标。
 | 原文链接：http://wiki.nmnc76.asia/arts/714760.Doc

原标题：浏览器缓存强制刷新方案
简介：定时任务重复执行分布式锁，使用分布式锁控制定时任务，保证集群环境定时任务只会执行一次。
 | 原文链接：http://wiki.nmnc76.asia/arts/773479.Doc

原标题：方案对比：同步调用vs异步消息业务选型
简介：vue pinia 状态管理实战教程，Pinia 完整实战示例，实现状态定义修改，模块拆分替代 Vuex。
 | 原文链接：http://wiki.nmnc76.asia/arts/742342.Doc

原标题：文件读写与异常捕获代码示例
简介：异步编程 Promise 执行流程解析，拆解异步执行顺序，理解回调与 Promise 差异，理清异步场景下代码执行逻辑。
 | 原文链接：http://wiki.nmnc76.asia/arts/964455.Doc

原标题：Issue：本地可以访问，容器内部网络不通
简介：vite 插件开发自定义构建逻辑，开发自定义 vite 插件，介入构建生命周期，实现项目个性化构建逻辑。
 | 原文链接：http://wiki.nmnc76.asia/arts/442921.Doc

原标题：线上异常：布隆过滤器误判造成业务逻辑异常
简介：前端工程化 webpack 打包优化，针对 webpack 项目做打包调优，分包、压缩、Tree‑Shaking，缩减包体积。
 | 原文链接：http://wiki.nmnc76.asia/arts/420298.Doc

原标题：Redis 分布式锁高并发安全实现
简介：数值 key 浮点匹配异常规避，避免浮点数作为 Redis 等存储的 key，防止精度问题引发 key 匹配失败。
 | 原文链接：http://wiki.nmnc76.asia/arts/660967.Doc

原标题：入门实践：Git分支创建切换合并完整演示
简介：简易网关请求路由过滤模拟，模拟网关基础能力，实现请求路由转发、简单过滤，理解网关核心工作逻辑。
 | 原文链接：http://wiki.nmnc76.asia/arts/660703.Doc

原标题：golang 系统设计架构图绘制规范简单建议
简介：golang 分布式唯一 id 多种方案对比，雪花、redis、uuid 对比各方案优缺点，指导业务选型使用。
 | 原文链接：http://wiki.nmnc76.asia/arts/422435.Doc

原标题：方案对比：几种任务队列架构选型优缺点
简介：golang json 解析未知动态 json 结构，解析到 map [string] any 处理未知 json，动态读取字段。
 | 原文链接：http://wiki.nmnc76.asia/arts/149733.Doc

原标题：项目实践：本地模拟缓存失效风暴验证防护
简介：golang 消息死信处理业务逻辑，Go 实现死信队列逻辑，消费失败消息转入死信，不阻塞正常消息队列。
 | 原文链接：http://wiki.nmnc76.asia/arts/286036.Doc

原标题：golang 系统设计联合索引设计避坑要点
简介：nodejs 中间件模式原理剖析，拆解 Node 中间件设计模式，理解请求逐层处理流转的底层原理。
 | 原文链接：http://wiki.nmnc76.asia/arts/647296.Doc

原标题：express 请求参数校验处理
简介：ORM 框架数据库增删改查实操，使用 ORM 框架完成数据库基础操作，减少手写 SQL，简化业务层数据库交互代码。
 | 原文链接：http://wiki.nmnc76.asia/arts/197392.Doc

三、实战开发｜Practice
原标题：网关集成鉴权限流日志一体化
简介：git cherry‑pick 规范操作防 bug，规范 cherry‑pick 使用流程，处理冲突，避免错误引入不兼容代码。
 | 原文链接：http://wiki.nmnc76.asia/arts/187568.Doc

原标题：golang k8s configmap secret 配置
简介：OOMKilled 容器被杀完整排查，排查容器被 OOM 终止完整流程，区分程序内存泄露和容器内存限制过小。
 | 原文链接：http://wiki.nmnc76.asia/arts/336983.Doc

原标题：坑点：Git仓库过大，clone速度极慢解决方案
简介：golang icmp ping 程序实现，go 实现 ping 工具发送 icmp 报文，检测网络连通性。
 | 原文链接：http://wiki.nmnc76.asia/arts/743391.Doc

原标题：golang 系统设计依赖漏洞扫描修复流程
简介：golang redis bitmap 位图业务实战，bitmap 做签到统计、用户状态标记，节省大量内存空间。
 | 原文链接：http://wiki.nmnc76.asia/arts/198172.Doc

原标题：实战项目：Nginx限速、限流、防爬虫配置实践
简介：SDK 版本兼容线上崩溃修复，处理 SDK 版本升级之后线上崩溃，定位 API 变更，做版本兼容适配改造。
 | 原文链接：http://wiki.nmnc76.asia/arts/601778.Doc

原标题：golang csv 读写批量数据处理
简介：golang uuid 生成多种版本实现，生成 uuid v1 v4，生成唯一标识，业务用于单据编号场景。
 | 原文链接：http://wiki.nmnc76.asia/arts/170637.Doc

原标题：部署复盘：GitHubActions完整自动化配置
简介：golang 布隆过滤器实现去重，Go 实现布隆过滤器，海量数据去重，节省内存开销，提升判断效率。
 | 原文链接：http://wiki.nmnc76.asia/arts/006572.Doc

原标题：ORM 框架数据库增删改查实操
简介：nodejs 事件循环机制完整讲解，拆解 Node.js 事件循环各个阶段，理解异步回调执行顺序。
 | 原文链接：http://wiki.nmnc76.asia/arts/237846.Doc

原标题：快速入门GraphQL基础查询语法示例
简介：开源项目构建失败排查步骤，梳理构建报错排查流程，从依赖、网络、权限、脚本多角度定位项目构建失败原因。
 | 原文链接：http://wiki.nmnc76.asia/arts/485792.Doc

原标题：golang 系统设计全局异常处理器实现
简介：golang go 随机数安全与非安全，math/rand 伪随机与 crypto/rand 密码学安全随机，区分业务场景。
 | 原文链接：http://wiki.nmnc76.asia/arts/327990.Doc

原标题：项目脚手架模板生成工具
简介：磁盘 inode 耗尽文件创建失败，排查磁盘 inode 占用，清理大量小文件，恢复文件创建能力。
 | 原文链接：http://wiki.nmnc76.asia/arts/630221.Doc

原标题：golang redis 集群 hash 槽讲解
简介：nodejs 流处理大文件不占内存，使用 Node.js 流处理超大文件，边读边写，不需要全部加载进内存。
 | 原文链接：http://wiki.nmnc76.asia/arts/669708.Doc

原标题：坑点：Docker资源限制未设置导致宿主机卡死
简介：限流规则误拦截正常请求修复，修正限流规则阈值，避免合法用户被限流拦截，兼顾防护与可用性。
 | 原文链接：http://wiki.nmnc76.asia/arts/604632.Doc

原标题：golang 系统设计代码评审关注点 checklist 清单
简介：golang 错误处理最佳实践汇总，Go 错误处理规范，包装错误，堆栈携带，拒绝简单忽略错误。
 | 原文链接：http://wiki.nmnc76.asia/arts/660703.Doc

原标题：坑点：缓存穿透，大量无效请求打穿数据库
简介：golang 内存持续上涨定位思路，区分内存泄漏、缓存占用、GC 参数不合理，分步定位内存持续走高。
 | 原文链接：http://wiki.nmnc76.asia/arts/019871.Doc

原标题：实战：Nginx负载均衡多种策略配置实践
简介：vue pinia 状态管理实战教程，Pinia 完整实战示例，实现状态定义修改，模块拆分替代 Vuex。
 | 原文链接：http://wiki.nmnc76.asia/arts/634840.Doc

原标题：内网测试服务搭建团队调试
简介：golang grpc metadata 元数据透传，metadata 传递 traceId、鉴权信息，全链路透传上下文信息。
 | 原文链接：http://wiki.nmnc76.asia/arts/929829.Doc

原标题：部署复盘：容器资源限制CPU内存配置实践
简介：golang jaeger 链路追踪部署对接，jaeger 接收 opentelemetry 链路数据，可视化完整调用链路。
 | 原文链接：http://wiki.nmnc76.asia/arts/678764.Doc

原标题：golang mysql 读写分离简单实现
简介：WSL 搭建 Windows Linux 开发环境，配置 WSL 环境，在 Windows 系统使用 Linux 工具链，适配 Linux 开发项目。
 | 原文链接：http://wiki.nmnc76.asia/arts/426103.Doc

原标题：后端登录鉴权模块完整开发
简介：服务器 Swap 关闭提升响应速度，关闭服务器 Swap 交换分区，避免内存交换磁盘拖慢程序响应性能。
 | 原文链接：http://wiki.nmnc76.asia/arts/588273.Doc

原标题：Git 误删提交代码恢复找回
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://wiki.nmnc76.asia/arts/254150.Doc

原标题：golang 消息队列 kafka 消费开发
简介：vite 项目配置与构建提速技巧，讲解 vite 配置优化手段，提升开发热更新速度与生产构建打包效率。
 | 原文链接：http://wiki.nmnc76.asia/arts/355260.Doc

原标题：接口限流逻辑简单模拟实现
简介：程序日志分级输出规范实践，区分日志等级，规范日志打印内容，合理输出日志，方便线上问题排查定位。
 | 原文链接：http://wiki.nmnc76.asia/arts/994409.Doc

原标题：Practice：实现请求body重复读取中间件实践
简介：golang go 服务压测前后性能对比，压测记录 QPS 延迟，优化前后对比，验证优化效果。
 | 原文链接：http://wiki.nmnc76.asia/arts/605395.Doc

原标题：实践：Git大仓库历史清理减小仓库体积实践
简介：golang 优雅关闭 grpc 服务示例，gRPC 服务优雅关闭，等待现有请求处理完成再停止服务。
 | 原文链接：http://wiki.nmnc76.asia/arts/259955.Doc

原标题：容器软链接文件权限修复
简介：golang ssh 客户端远程命令执行，golang ssh 连接远程服务器，执行 shell 命令，获取命令输出结果。
 | 原文链接：http://wiki.nmnc76.asia/arts/718861.Doc

原标题：运维笔记：服务器故障排查常用命令清单
简介：axios 二次封装请求拦截处理，对 axios 做二次封装，统一请求拦截响应拦截，处理错误、token 自动刷新。
 | 原文链接：http://wiki.nmnc76.asia/arts/115104.Doc

原标题：零基础理解JSON、XML数据格式处理
简介：Redis 内存淘汰策略数据防丢失，合理配置 Redis 内存淘汰策略，防止内存满后误删除业务重要数据。
 | 原文链接：http://wiki.nmnc76.asia/arts/445468.Doc

原标题：golang 系统设计 docker compose 本地开发环境搭建
简介：golang gorm 预加载关联查询优化，GORM 预加载关联数据，避免 N+1 查询问题，提升数据库查询性能。
 | 原文链接：http://wiki.nmnc76.asia/arts/864265.Doc

原标题：Troubleshooting：依赖安装失败完整排查清单
简介：Git 仓库瘦身加快克隆下载速度，清理 Git 仓库历史大文件，缩减仓库体积，提升克隆拉取仓库速度。
 | 原文链接：http://wiki.nmnc76.asia/arts/877382.Doc

原标题：部署实践：服务器时间同步chrony配置
简介：golang http 代理客户端配置，Go HTTP Client 配置代理，通过代理服务器发起网络请求。
 | 原文链接：http://wiki.nmnc76.asia/arts/078691.Doc

原标题：设计实践：如何设计可扩展业务数据库表结构
简介：Mock 接口服务快速搭建实操，搭建模拟后端接口，自定义返回数据、延迟响应，前端开发阶段无需依赖真实后端服务。
 | 原文链接：http://wiki.nmnc76.asia/arts/970054.Doc

原标题：golang 系统设计缓存更新策略 cache aside 讲解
简介：golang multipart 表单文件上传解析，服务端解析 multipart 表单，获取上传文件与表单字段。
 | 原文链接：http://wiki.nmnc76.asia/arts/085071.Doc

原标题：golang 系统设计缓存空值防止缓存穿透实现
简介：golang 半关闭 tcp 连接 shutdown，tcp 连接 shutdown 半关闭，单向关闭读或者写，理解 tcp 关闭流程。
 | 原文链接：http://wiki.nmnc76.asia/arts/929361.Doc

原标题：避坑：Nginx配置错误导致请求丢失Header
简介：pnpm 包管理工具实战避坑指南，使用 pnpm 管理项目依赖，梳理常见坑点，充分利用 pnpm 优势。
 | 原文链接：http://wiki.nmnc76.asia/arts/078782.Doc

原标题：接口签名校验防篡改实现
简介：数据库事务 ACID 原理讲解，拆解事务四大特性，理解事务隔离、原子性，明白事务如何保障数据安全。
 | 原文链接：http://wiki.nmnc76.asia/arts/899585.Doc

原标题：golang k8s configmap secret 配置
简介：golang 静态文件服务搭建教程，Go 搭建静态文件服务，托管静态资源，实现文件直接对外访问。
 | 原文链接：http://wiki.nmnc76.asia/arts/852873.Doc

原标题：golang 系统设计限流服务架构讲解
简介：golang grpc 服务端流推送数据，服务端流式响应，服务端持续向客户端推送多条响应消息。
 | 原文链接：http://wiki.nmnc76.asia/arts/628738.Doc

原标题：项目实践：灰度发布简易方案落地实践
简介：golang fuzz corpus 语料库使用，fuzz 语料存储历史输入，回归测试，持续复现曾经触发 bug 输入。
 | 原文链接：http://wiki.nmnc76.asia/arts/341235.Doc

原标题：Troubleshoot：跨域偶现失败难以复现问题
简介：golang 布隆过滤器实现去重，Go 实现布隆过滤器，海量数据去重，节省内存开销，提升判断效率。
 | 原文链接：http://wiki.nmnc76.asia/arts/681137.Doc

四、架构设计｜Architecture
原标题：golang 系统设计故障止损降级回滚执行原则
简介：golang tcp 四次挥手 go 程序行为，理解 tcp 四次挥手，处理连接关闭、重置、RST 包异常场景。
 | 原文链接：http://wiki.nmnc76.asia/arts/379535.Doc

原标题：踩坑：环境变量未生效导致线上配置错乱
简介：golang cgroup 读取容器资源限制，go 程序读取 cgroup，获取容器 cpu 内存限额，适配容器环境。
 | 原文链接：http://wiki.nmnc76.asia/arts/173356.Doc

原标题：golang 优雅处理系统信号 SIGINT
简介：golang go 零停机升级实践要点，socket 继承，流量无损，旧连接处理完毕后旧进程退出。
 | 原文链接：http://wiki.nmnc76.asia/arts/748537.Doc

原标题：golang 多协程任务池并发控制
简介：macOS 脚本执行权限开启，给 Shell 脚本添加可执行权限，解决 macOS 下脚本无法运行权限报错。
 | 原文链接：http://wiki.nmnc76.asia/arts/178134.Doc

原标题：Docker 多阶段构建镜像瘦身
简介：echarts 大数据渲染性能调优，大数据量 ECharts 图表调优，数据采样、分片渲染，解决图表卡顿。
 | 原文链接：http://wiki.nmnc76.asia/arts/853389.Doc

原标题：项目实践：MySQL读写分离本地模拟实践
简介：跨库查询性能优化处理，减少跨库关联查询，做数据冗余或者中间表，规避跨库查询性能低下。
 | 原文链接：http://wiki.nmnc76.asia/arts/967736.Doc

原标题：golang 系统设计内部 rpc 接口设计原则梳理
简介：环境变量不生效问题修复，排查环境变量加载顺序、作用域问题，修复环境变量读取不到的异常。
 | 原文链接：http://wiki.nmnc76.asia/arts/899743.Doc

原标题：golang 系统设计死信队列 dlq 业务落地完整流程
简介：跨平台 uniapp 多端开发实操，uniapp 开发一套代码，编译多端，梳理多端差异处理与适配技巧。
 | 原文链接：http://wiki.nmnc76.asia/arts/699184.Doc

原标题：HTTP 状态码请求头完整梳理
简介：服务健康检查监控接口开发，开发健康检查接口，反馈服务运行状态，供编排工具监控服务存活状态。
 | 原文链接：http://wiki.nmnc76.asia/arts/589105.Doc

原标题：运维笔记：系统文件句柄数调整生产配置
简介：nodejs 数据库连接池配置调优，调优 Node 数据库连接池参数，平衡性能与资源占用，避免连接耗尽。
 | 原文链接：http://wiki.nmnc76.asia/arts/881603.Doc

原标题：golang 接口请求日志记录中间件
简介：golang grpc 重试机制客户端配置，grpc 客户端配置重试策略，临时故障自动重试，提升调用稳定性。
 | 原文链接：http://wiki.nmnc76.asia/arts/376414.Doc

原标题：golang 系统设计分表字段选择路由规则设计
简介：golang 静态编译缩小镜像体积，Go 程序静态编译，不依赖系统库，产出单二进制文件，缩小镜像。
 | 原文链接：http://wiki.nmnc76.asia/arts/382025.Doc

原标题：Hands‑on：简易网关路由转发组件开发
简介：前端图片懒加载性能优化，实现图片懒加载，页面可视区域才加载图片，减少页面初始网络请求。
 | 原文链接：http://wiki.nmnc76.asia/arts/041904.Doc

原标题：实践：API版本控制多种策略落地对比实践
简介：golang go json 序列化自定义字段，json 标签控制字段名称、忽略字段、omitempty 空值忽略。
 | 原文链接：http://wiki.nmnc76.asia/arts/148635.Doc

原标题：TLS 版本兼容 HTTPS 握手失败
简介：集成测试业务流程编写示例，编写业务流程集成测试，覆盖完整业务链路，验证模块之间协同工作是否正常。
 | 原文链接：http://wiki.nmnc76.asia/arts/330582.Doc

原标题：golang 系统设计 protobuf 默认值坑点梳理
简介：内存泄漏定位分析完整流程，分享内存泄漏排查步骤，定位没有释放的对象，解决内存持续上涨问题。
 | 原文链接：http://wiki.nmnc76.asia/arts/133579.Doc

原标题：实战项目：容器健康探针配置完整实践示例
简介：golang 配置文件多环境加载，Go 多环境配置加载实现，读取配置文件环境变量，适配多套运行环境。
 | 原文链接：http://wiki.nmnc76.asia/arts/239585.Doc

原标题：golang 系统设计分布式事务几种方案
简介：nodejs jwt 登录鉴权完整示例，Node 实现 JWT 登录鉴权，登录签发令牌，接口校验令牌身份。
 | 原文链接：http://wiki.nmnc76.asia/arts/748705.Doc

?
