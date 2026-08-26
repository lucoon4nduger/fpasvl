最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计主干开发 trunk‑based 讲解
简介：Fork 开源项目同步上游代码，Fork 开源仓库之后，配置上游源，同步官方最新代码，保持代码版本对齐。
 | 原文链接：http://wiki.nzrkf5.asia/arts/526265.Doc

原标题：golang 系统设计联合索引设计避坑要点
简介：golang go 爬虫请求速率控制，爬虫限频、代理轮换，设置 UA，防止爬虫被目标站点封禁 IP。
 | 原文链接：http://wiki.nzrkf5.asia/arts/641688.Doc

原标题：Security：业务操作审计日志安全留存
简介：限流窗口绕过漏洞修复方案，修复限流时间窗口漏洞，避免攻击者绕过限流规则，保障接口防护有效。
 | 原文链接：http://wiki.nzrkf5.asia/arts/086525.Doc

原标题：包管理器依赖冲突解决方案
简介：前端组件库按需加载性能优化，配置组件库按需引入，避免引入全部组件，减少打包产物体积。
 | 原文链接：http://wiki.nzrkf5.asia/arts/760473.Doc

原标题：缓存穿透击穿雪崩全套防护
简介：CI 构建缓存加速编译速度，开启 CI 流水线依赖缓存，复用上一次构建依赖包，缩短流水线构建耗时。
 | 原文链接：http://wiki.nzrkf5.asia/arts/253740.Doc

原标题：架构笔记：海量日志处理架构选型与实践
简介：golang hystrix 模式简易熔断实现，简易熔断组件，错误率达到阈值触发熔断，快速失败保护下游。
 | 原文链接：http://wiki.nzrkf5.asia/arts/316845.Doc

原标题：HelloTest：理解集成测试基础编写思路
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://wiki.nzrkf5.asia/arts/455232.Doc

原标题：Practice：实现接口签名、验签完整示例代码
简介：golang 日志按日期切割实现方案，实现日志文件按天切割，自动归档旧日志，防止单个日志文件过大。
 | 原文链接：http://wiki.nzrkf5.asia/arts/144101.Doc

原标题：golang 系统设计故障复盘模板 postmortem 参考
简介：任务执行锁防止并发重复调度，增加任务执行锁，多实例环境，防止同一个定时任务并发多次运行。
 | 原文链接：http://wiki.nzrkf5.asia/arts/003178.Doc

原标题：Hands‑on：简易熔断逻辑状态机原型实现
简介：golang kafka 消费者组重平衡避坑，规避消费者组频繁 rebalance，减少消费抖动，保障消息消费稳定性。
 | 原文链接：http://wiki.nzrkf5.asia/arts/226029.Doc

原标题：golang excel 简单读写操作示例
简介：golang cgroup 读取容器资源限制，go 程序读取 cgroup，获取容器 cpu 内存限额，适配容器环境。
 | 原文链接：http://wiki.nzrkf5.asia/arts/008723.Doc

原标题：序列化版本不一致解析失败
简介：golang 大文件 HTTP 流式上传接收，服务端流式接收上传文件，不全部加载内存，防止大文件 OOM 崩溃。
 | 原文链接：http://wiki.nzrkf5.asia/arts/347286.Doc

原标题：golang 工具函数库封装思路
简介：多版本开发环境共存配置，实现同一工具多版本并存，快速切换不同版本，适配不同项目对版本的差异化需求。
 | 原文链接：http://wiki.nzrkf5.asia/arts/090567.Doc

原标题：部署复盘：配置不要硬编码进镜像最佳实践
简介：缓存基础原理与简单代码实现，讲解缓存设计思路，编写简易缓存逻辑，减少重复计算与重复请求，提升程序响应速度。
 | 原文链接：http://wiki.nzrkf5.asia/arts/456435.Doc

原标题：golang 系统设计开源项目依赖版本升级维护
简介：golang grpc 负载均衡客户端实现，grpc 客户端负载均衡，轮询随机权重，分发请求到多个服务实例。
 | 原文链接：http://wiki.nzrkf5.asia/arts/441765.Doc

原标题：golang 限流熔断降级完整示例
简介：golang go json 序列化自定义字段，json 标签控制字段名称、忽略字段、omitempty 空值忽略。
 | 原文链接：http://wiki.nzrkf5.asia/arts/227611.Doc

原标题：新手向：配置项目eslint/prettier代码格式化
简介：golang cpu pprof 性能分析实操，使用 pprof 采集 CPU 性能数据，定位 CPU 高占用函数，做性能优化。
 | 原文链接：http://wiki.nzrkf5.asia/arts/263935.Doc

原标题：避坑：Spring事务传播行为理解错误事务失效
简介：golang go‑zero 框架项目快速搭建，go‑zero 脚手架生成微服务项目，api rpc 服务快速开发。
 | 原文链接：http://wiki.nzrkf5.asia/arts/190728.Doc

原标题：排错：多实例部署session共享失效登录失效
简介：golang kafka 消费者组重平衡避坑，规避消费者组频繁 rebalance，减少消费抖动，保障消息消费稳定性。
 | 原文链接：http://wiki.nzrkf5.asia/arts/196669.Doc

原标题：golang k8s 资源请求限制配置
简介：golang 本地消息表实现最终一致性，本地消息表 + 定时任务轮询，可靠消息实现分布式事务。
 | 原文链接：http://wiki.nzrkf5.asia/arts/370214.Doc

原标题：react 状态管理方案选型对比
简介：golang go 服务蓝绿发布实践思路，蓝绿两套实例，流量一键切换，回滚快速降低发布风险。
 | 原文链接：http://wiki.nzrkf5.asia/arts/671425.Doc

原标题：进程线程并发基础概念讲解
简介：golang feishu 飞书机器人消息发送，调用飞书 webhook 机器人，发送文本卡片消息，实现业务告警通知。
 | 原文链接：http://wiki.nzrkf5.asia/arts/797726.Doc

原标题：Issue：CI脚本超时，构建任务无故终止
简介：golang 性能压测 wr 工具实操指南，wr 压测工具对 Go 接口压测，观察 QPS 延迟，定位接口性能瓶颈。
 | 原文链接：http://wiki.nzrkf5.asia/arts/477793.Doc

原标题：golang 系统设计链路追踪架构简单讲解
简介：日志输出规范防止磁盘爆满，控制日志输出量，配置日志切割轮转，避免日志文件无限增长占满磁盘。
 | 原文链接：http://wiki.nzrkf5.asia/arts/241551.Doc

原标题：优化实践：业务定时任务错开高峰避免资源争抢
简介：golang 分布式锁防死锁实现要点，锁超时、续期、锁持有者校验，避免锁死锁，保障分布式锁可靠性。
 | 原文链接：http://wiki.nzrkf5.asia/arts/151797.Doc

原标题：部署复盘：静态资源版本哈希缓存策略
简介：前端骨架屏提升页面体验，实现页面骨架屏，数据未加载完成展示占位，优化页面白屏感知体验。
 | 原文链接：http://wiki.nzrkf5.asia/arts/863512.Doc

原标题：Issue：WSL2内存持续暴涨不自动释放
简介：golang smtp 邮件发送完整示例，调用 smtp 服务发送文本与 html 格式邮件，实现邮件通知能力。
 | 原文链接：http://wiki.nzrkf5.asia/arts/694516.Doc

原标题：golang k8s hpa 水平 pod 自动扩缩容
简介：Git commit 钩子提交规范校验，配置 Git 提交钩子，提交代码自动校验提交信息格式，规范提交记录。
 | 原文链接：http://wiki.nzrkf5.asia/arts/215168.Doc

原标题：优化实践：Redis管道、批量命令减少网络往返
简介：golang 日志输出 stdout 标准输出规范，容器环境日志输出到 stdout，由容器平台统一采集日志文件。
 | 原文链接：http://wiki.nzrkf5.asia/arts/634583.Doc

原标题：项目目录结构规范化最佳实践
简介：golang http client 全局变量复用，http Client 不要每次请求新建，复用 Transport 提升性能。
 | 原文链接：http://wiki.nzrkf5.asia/arts/163691.Doc

原标题：Issue：文件编码混合GBKUTF‑8乱码随机出现
简介：全局本地依赖隔离冲突规避，区分全局依赖与项目本地依赖，隔离环境，防止全局包干扰项目运行。
 | 原文链接：http://wiki.nzrkf5.asia/arts/456257.Doc

原标题：Practice：模拟网络抖动验证服务容错能力
简介：golang bcrypt 密码哈希加密存储，bcrypt 做用户密码哈希，加盐存储密码，保障用户密码安全。
 | 原文链接：http://wiki.nzrkf5.asia/arts/615258.Doc

原标题：golang 系统设计错误码体系完整设计
简介：golang mongodb 索引优化慢查询处理，mongodb 创建索引，分析慢查询，优化聚合查询执行性能。
 | 原文链接：http://wiki.nzrkf5.asia/arts/998682.Doc

原标题：golang 系统设计多租户数据隔离方案
简介：golang http client 连接池调优，调优 Go HTTP Client 连接池参数，复用 TCP 连接，减少连接创建开销。
 | 原文链接：http://wiki.nzrkf5.asia/arts/417173.Doc

原标题：入门实践：简单数据脱敏处理示例
简介：golang 静态文件服务搭建教程，Go 搭建静态文件服务，托管静态资源，实现文件直接对外访问。
 | 原文链接：http://wiki.nzrkf5.asia/arts/352964.Doc

原标题：排错：内网域名解析不稳定导致服务随机报错
简介：开源项目构建失败排查步骤，梳理构建报错排查流程，从依赖、网络、权限、脚本多角度定位项目构建失败原因。
 | 原文链接：http://wiki.nzrkf5.asia/arts/960072.Doc

原标题：前端大文件分片上传完整方案
简介：golang 雪花算法 workId 自动获取，自动获取机器 workId，不用手动配置，简化分布式 id 部署。
 | 原文链接：http://wiki.nzrkf5.asia/arts/166271.Doc

原标题：运维笔记：备份策略数据库定时备份脚本
简介：golang go regexp 正则预编译，regexp.MustCompile 预编译正则，不要循环内部编译正则，节省 CPU。
 | 原文链接：http://wiki.nzrkf5.asia/arts/605278.Doc

原标题：golang 静态文件服务搭建教程
简介：golang goroutine 协程基础实操，Goroutine 基础实操案例，启动协程执行任务，理解轻量级协程特性。
 | 原文链接：http://wiki.nzrkf5.asia/arts/378051.Doc

原标题：golang 日志 zap 结构化日志实践
简介：golang io.Copy 流式拷贝数据，io.Copy 拷贝 reader 到 writer，不用加载全部数据到内存。
 | 原文链接：http://wiki.nzrkf5.asia/arts/015692.Doc


二、踩坑排错｜Troubleshooting
原标题：实践：前后端分离项目登录状态保持完整方案
简介：golang 配置文件多格式兼容加载，同时支持 yaml toml json 多种格式配置文件，灵活适配不同部署环境。
 | 原文链接：http://wiki.nzrkf5.asia/arts/782707.Doc

原标题：安全实践：防止重放攻击接口签名方案
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://wiki.nzrkf5.asia/arts/599292.Doc

原标题：坑点：软链接权限问题容器读取文件失败
简介：golang go 排序 sort 包自定义排序，sort 包实现自定义排序逻辑，对切片按业务规则排序。
 | 原文链接：http://wiki.nzrkf5.asia/arts/796303.Doc

原标题：Docker 容器网络不通排查
简介：express 中间件开发业务实践，开发 Express 自定义中间件，拦截请求，实现鉴权、日志记录等通用逻辑。
 | 原文链接：http://wiki.nzrkf5.asia/arts/165687.Doc

原标题：Debug：表单提交特殊字符造成接口解析失败
简介：golang 漏桶算法实现接口限流，漏桶算法控制请求流出速率，平滑突发流量，削平流量峰值。
 | 原文链接：http://wiki.nzrkf5.asia/arts/011183.Doc

原标题：项目实践：实现统一接口返回封装与全局异常处理
简介：golang go math 大数高精度计算，math/big 处理超大整数、高精度浮点数，金额大数运算。
 | 原文链接：http://wiki.nzrkf5.asia/arts/381187.Doc

原标题：新手教程：Gittag版本标签打标签实操
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://wiki.nzrkf5.asia/arts/644091.Doc

原标题：golang 系统设计接口超时设计原则梳理
简介：RPC 报文大小上限调优大请求，调大 RPC 框架报文最大限制，支持传输大体积请求报文不被截断。
 | 原文链接：http://wiki.nzrkf5.asia/arts/166651.Doc

原标题：性能复盘：热点key导致RedisCPU飙升优化
简介：golang 命令行彩色输出终端，终端彩色文字输出，进度条交互，优化命令行工具用户体验。
 | 原文链接：http://wiki.nzrkf5.asia/arts/764767.Doc

原标题：图片上传预览格式大小处理
简介：文件监控服务自动重启开发，监控项目文件变更，代码修改自动重启服务，提升本地开发调试效率。
 | 原文链接：http://wiki.nzrkf5.asia/arts/767381.Doc

原标题：开发复盘：内存缓存LRU淘汰策略实现实践
简介：pnpm 包管理工具实战避坑指南，使用 pnpm 管理项目依赖，梳理常见坑点，充分利用 pnpm 优势。
 | 原文链接：http://wiki.nzrkf5.asia/arts/652100.Doc

原标题：golang 系统设计 changelog 变更日志维护
简介：golang go 程序守护进程实现思路，go 程序不做 daemon 化，依靠 systemd pm2 k8s 实现进程守护。
 | 原文链接：http://wiki.nzrkf5.asia/arts/249993.Doc

原标题：服务器 Swap 关闭提升响应速度
简介：轻量 API 后端接口服务快速开发，快速搭建简易 API 服务，实现基础接口能力，快速支撑小型业务需求。
 | 原文链接：http://wiki.nzrkf5.asia/arts/681135.Doc

原标题：golang 系统设计网络 io 模型 epoll 原理讲解
简介：包管理器依赖冲突解决方案，分析依赖冲突产生根源，提供版本调整、锁定依赖等手段，解决项目依赖报错问题。
 | 原文链接：http://wiki.nzrkf5.asia/arts/520445.Doc

原标题：前端大文件分片上传完整方案
简介：环境变量不生效问题修复，排查环境变量加载顺序、作用域问题，修复环境变量读取不到的异常。
 | 原文链接：http://wiki.nzrkf5.asia/arts/973388.Doc

原标题：golang 重试退避机制代码实现
简介：golang docker 多阶段构建 go 镜像，Go 项目 Docker 多阶段构建，编译与运行阶段分离，大幅度缩减最终镜像体积，提升镜像分发效率。
 | 原文链接：http://wiki.nzrkf5.asia/arts/867350.Doc

原标题：实战：搭建本地对象存储兼容S3协议demo
简介：golang go 种子初始化 rand 随机，rand 初始化种子，不初始化会固定序列，理解随机数种子行为。
 | 原文链接：http://wiki.nzrkf5.asia/arts/793259.Doc

原标题：性能复盘：系统上下文切换过高性能下降调优
简介：golang gorm 索引设置与优化技巧，定义数据库索引，理解索引生效条件，避免索引失效慢查询。
 | 原文链接：http://wiki.nzrkf5.asia/arts/750770.Doc

原标题：Hands‑on：简易的事件订阅发布组件开发实践
简介：Nginx 静态代理负载均衡全套配置，一套 Nginx 配置示例，覆盖静态资源、反向代理、负载均衡场景。
 | 原文链接：http://wiki.nzrkf5.asia/arts/452704.Doc

原标题：golang redis pipeline 原子性说明
简介：日志敏感信息脱敏泄露防护，日志打印时自动脱敏手机号身份证，避免日志输出泄露用户隐私数据。
 | 原文链接：http://wiki.nzrkf5.asia/arts/693374.Doc

原标题：新手指南：读懂项目构建脚本作用
简介：golang hertz 性能优化参数调优，hertz 连接池、缓冲区参数调优，最大化接口吞吐性能。
 | 原文链接：http://wiki.nzrkf5.asia/arts/411485.Doc

原标题：Performance：数据库join优化，大表join规避
简介：短信服务封装失败自动重试，封装短信发送组件，处理发送失败自动重试，兼容多短信服务商。
 | 原文链接：http://wiki.nzrkf5.asia/arts/334317.Doc

原标题：部署实践：容器时区统一配置解决方案
简介：上传接口跨域配置特殊适配，针对文件上传接口，适配复杂请求，修复上传场景下跨域失效问题。
 | 原文链接：http://wiki.nzrkf5.asia/arts/341845.Doc

原标题：Debug：长连接未设置心跳，连接僵死不回收
简介：nodejs 集群模式多核利用实现，使用 cluster 集群模式，充分利用服务器多核 CPU，提升服务处理能力。
 | 原文链接：http://wiki.nzrkf5.asia/arts/788832.Doc

原标题：新手向：Mac/Windows开发环境差异踩坑
简介：golang prometheus 指标埋点开发，业务埋点计数器、仪表盘、直方图，对接 prometheus 采集监控指标。
 | 原文链接：http://wiki.nzrkf5.asia/arts/099246.Doc

原标题：golang docker 镜像安全扫描漏洞
简介：golang context.WithValue 传递元数据，WithValue 只传 traceId 鉴权元数据，不要传业务大对象。
 | 原文链接：http://wiki.nzrkf5.asia/arts/192547.Doc

原标题：golang 系统设计分布式事务几种方案
简介：golang delve 远程调试 go 线上程序，delve 远程调试，线上环境附加进程调试排查线上 bug。
 | 原文链接：http://wiki.nzrkf5.asia/arts/661021.Doc

原标题：golang 错误包装 errors.wrap 用法
简介：对象存储上传下载权限实操，演示对象存储文件上传、下载、访问权限设置，适配业务文件存储场景。
 | 原文链接：http://wiki.nzrkf5.asia/arts/498205.Doc

原标题：排错：打包后资源路径，开发生产行为不一致
简介：golang go 排序 sort 包自定义排序，sort 包实现自定义排序逻辑，对切片按业务规则排序。
 | 原文链接：http://wiki.nzrkf5.asia/arts/912471.Doc

原标题：设计思考：系统降级开关架构设计快速切流量
简介：golang 处理连接被重置 reset 错误，识别 connection reset by peer，对端关闭连接异常处理逻辑。
 | 原文链接：http://wiki.nzrkf5.asia/arts/202960.Doc

原标题：调优方案：消息批量消费提升MQ处理吞吐量
简介：golang atomic 原子操作整数，atomic 加减比较交换，无锁更新整型变量，简单计数器场景。
 | 原文链接：http://wiki.nzrkf5.asia/arts/739119.Doc

原标题：golang es 更新文档注意版本冲突
简介：golang go 整洁架构代码组织实践，整洁架构依赖向内，解耦业务逻辑与外部基础设施。
 | 原文链接：http://wiki.nzrkf5.asia/arts/889502.Doc

原标题：数据库事务 ACID 原理讲解
简介：golang 项目 go mod 依赖管理，Go Mod 管理项目依赖，下载、升级、清理依赖，解决依赖版本管理。
 | 原文链接：http://wiki.nzrkf5.asia/arts/128485.Doc

原标题：架构笔记：WebSocket大规模连接服务架构
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：http://wiki.nzrkf5.asia/arts/460280.Doc

原标题：golang 系统设计压力测试性能测试执行流程
简介：golang 限流器熔断降级组合使用，限流熔断降级组合架构，流量防护完整方案，保障服务稳定性。
 | 原文链接：http://wiki.nzrkf5.asia/arts/129257.Doc

原标题：实战：对象存储断点续传下载实践
简介：ORM 隐式慢查询问题规避，识别 ORM 框架隐式查询，避免循环查询数据库，减少不必要慢 SQL 产生。
 | 原文链接：http://wiki.nzrkf5.asia/arts/199708.Doc

原标题：golang 系统设计热点数据缓存处理
简介：golang 信号触发配置重载实践，收到 SIGUSR1 信号重新加载配置，线上无需重启刷新配置。
 | 原文链接：http://wiki.nzrkf5.asia/arts/713579.Doc

原标题：架构复盘：服务优雅停机架构设计资源释放
简介：golang go 线上故障排查完整流程，CPU 高、内存上涨、接口超时、goroutine 泄露一套排查处理流程。
 | 原文链接：http://wiki.nzrkf5.asia/arts/788877.Doc

原标题：golang 系统设计死信队列 dlq 业务落地完整流程
简介：golang json omitempty 零值坑，omitempty 会忽略零值，区分业务是否需要输出零值字段。
 | 原文链接：http://wiki.nzrkf5.asia/arts/873920.Doc

原标题：golang rate‑limiter 限流组件
简介：前端下载导出文件功能实现，前端实现文件流下载导出，处理异常，适配浏览器不同下载行为。
 | 原文链接：http://wiki.nzrkf5.asia/arts/714077.Doc

三、实战开发｜Practice
原标题：性能复盘：网络IO优化减少接口等待时间
简介：全局本地依赖隔离冲突规避，区分全局依赖与项目本地依赖，隔离环境，防止全局包干扰项目运行。
 | 原文链接：http://wiki.nzrkf5.asia/arts/292512.Doc

原标题：golang 系统设计 pre‑commit 钩子本地代码校验
简介：SDK 版本兼容线上崩溃修复，处理 SDK 版本升级之后线上崩溃，定位 API 变更，做版本兼容适配改造。
 | 原文链接：http://wiki.nzrkf5.asia/arts/318691.Doc

原标题：设计思考：大促系统架构压测改造整体思路
简介：golang grpc 拦截器开发鉴权日志，开发 grpc 服务端拦截器，统一做鉴权、日志打印、异常捕获处理。
 | 原文链接：http://wiki.nzrkf5.asia/arts/978275.Doc

原标题：golang 系统设计契约测试接口兼容性保障思路
简介：golang context.Background 与 TODO 区别，Background 主流程根上下文，TODO 不确定用哪个上下文时使用。
 | 原文链接：http://wiki.nzrkf5.asia/arts/249389.Doc

原标题：入门实践：简单错误码设计与使用规范
简介：golang 跨平台系统差异处理方案，处理 windows linux mac 路径、信号、文件权限差异，代码跨平台兼容。
 | 原文链接：http://wiki.nzrkf5.asia/arts/072833.Doc

原标题：部署复盘：GitHubActions完整自动化配置
简介：golang 子进程超时杀死防止挂住，context 控制子进程超时，超时强制杀掉子进程，避免子进程僵尸。
 | 原文链接：http://wiki.nzrkf5.asia/arts/703528.Doc

原标题：开发记录：文件锁实现多进程互斥实践
简介：golang kitex 字节微服务框架入门，kitex 开发 rpc 微服务，代码生成，服务注册发现完整流程。
 | 原文链接：http://wiki.nzrkf5.asia/arts/158188.Doc

原标题：golang 系统设计线程协程泄露定位方法
简介：golang cgroup 读取容器资源限制，go 程序读取 cgroup，获取容器 cpu 内存限额，适配容器环境。
 | 原文链接：http://wiki.nzrkf5.asia/arts/937984.Doc

原标题：golang 系统设计 graphql 接口优缺点梳理
简介：golang grpc protobuf 开发实操，Go gRPC 开发，编写 Protobuf 定义，服务端客户端完整示例。
 | 原文链接：http://wiki.nzrkf5.asia/arts/050268.Doc

原标题：golang k8s 资源请求限制配置
简介：nodejs 项目 pm2 部署运维指南，使用 PM2 管理 Node 服务，进程守护、日志、重启，线上部署运维实操。
 | 原文链接：http://wiki.nzrkf5.asia/arts/575142.Doc

原标题：Practice：实现限流之后友好业务返回处理
简介：golang 分布式事务 seata go 客户端，seata‑go 实现分布式事务，保证跨库业务数据最终一致性。
 | 原文链接：http://wiki.nzrkf5.asia/arts/439858.Doc

原标题：零基础理解模块化与组件化基础思想
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://wiki.nzrkf5.asia/arts/343360.Doc

原标题：golang 系统设计内存瓶颈定位优化思路
简介：golang testify testify 断言库使用，testify assert require 断言，简化单元测试断言代码。
 | 原文链接：http://wiki.nzrkf5.asia/arts/522716.Doc

原标题：记一次第三方回调IP变动未更新防火墙拦截
简介：新手快速上手 Git 版本控制实操指南，讲解 Git 基础概念与常用命令，结合实操案例，帮助零基础用户掌握版本控制核心能力。
 | 原文链接：http://wiki.nzrkf5.asia/arts/372368.Doc

原标题：踩坑：批量MQ消费失败直接无限重试消息爆炸
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://wiki.nzrkf5.asia/arts/824726.Doc

原标题：优化实践：Redis管道、批量命令减少网络往返
简介：golang atomic.Value 存储任意类型数据，atomic.Value 安全存储读取任意类型，配置热更新常用。
 | 原文链接：http://wiki.nzrkf5.asia/arts/823605.Doc

原标题：Debug：多线程共享可变变量产生脏数据
简介：MySQL 慢查询索引优化实战，抓取慢查询 SQL，分析执行计划，新增或者调整索引，提升 SQL 执行速度。
 | 原文链接：http://wiki.nzrkf5.asia/arts/201076.Doc

原标题：golang k8s job 一次性任务执行
简介：RPC 报文大小上限调优大请求，调大 RPC 框架报文最大限制，支持传输大体积请求报文不被截断。
 | 原文链接：http://wiki.nzrkf5.asia/arts/314280.Doc

原标题：golang jaeger 链路追踪 go 接入
简介：程序预加载加快服务启动速度，把高频使用资源提前预加载，减少请求阶段初始化，加快服务启动。
 | 原文链接：http://wiki.nzrkf5.asia/arts/425336.Doc

原标题：golang defer panic 异常处理
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://wiki.nzrkf5.asia/arts/705038.Doc

原标题：开发复盘：导出大文件避免内存溢出实现方案
简介：Git 混乱提交历史清理方法，针对杂乱的提交记录，使用 Git 工具整理，清理无效提交，还原整洁版本历史。
 | 原文链接：http://wiki.nzrkf5.asia/arts/990573.Doc

原标题：Docker 网络模式容器互通设置
简介：golang icmp ping 程序实现，go 实现 ping 工具发送 icmp 报文，检测网络连通性。
 | 原文链接：http://wiki.nzrkf5.asia/arts/272167.Doc

原标题：CI 构建缓存加速编译速度
简介：业务错误码完整落地实践，落地完整业务错误码，枚举全部业务异常，统一返回，配套文档说明。
 | 原文链接：http://wiki.nzrkf5.asia/arts/850998.Doc

原标题：golang 系统设计 webhook 回调处理架构
简介：Docker 多阶段构建镜像瘦身，使用 Docker 多阶段构建，剔除编译阶段依赖，产出体积更小运行镜像。
 | 原文链接：http://wiki.nzrkf5.asia/arts/195643.Doc

原标题：坑点：限流计数器重置时机错误，绕过限流规则
简介：golang go 种子初始化 rand 随机，rand 初始化种子，不初始化会固定序列，理解随机数种子行为。
 | 原文链接：http://wiki.nzrkf5.asia/arts/347775.Doc

原标题：golang 系统设计熔断降级架构讲解
简介：golang udp 服务端客户端开发示例，golang 实现 UDP 服务收发数据包，实现 udp 协议通信程序。
 | 原文链接：http://wiki.nzrkf5.asia/arts/296140.Doc

原标题：golang 系统设计消息可靠性投递实现
简介：慢查询分析索引调优数据库实战，抓取慢查询，分析执行计划，优化索引，解决数据库慢查询拖慢业务。
 | 原文链接：http://wiki.nzrkf5.asia/arts/185414.Doc

原标题：golang 系统设计错误码体系完整设计
简介：golang go race 竞态检测工具，‑race 检测数据竞争，编译运行检测并发读写数据竞争 bug。
 | 原文链接：http://wiki.nzrkf5.asia/arts/228138.Doc

原标题：项目实践：Docker多环境镜像构建策略实践
简介：macOS 脚本执行权限开启，给 Shell 脚本添加可执行权限，解决 macOS 下脚本无法运行权限报错。
 | 原文链接：http://wiki.nzrkf5.asia/arts/096838.Doc

原标题：开发复盘：超时参数统一治理线上服务实践
简介：golang go 爬虫代理池轮换使用，http 代理池轮换，请求自动切换代理 IP，突破访问限制。
 | 原文链接：http://wiki.nzrkf5.asia/arts/078902.Doc

原标题：golang 系统设计 canary 金丝雀部署实操
简介：缓存过期策略优化防业务故障，合理设置缓存过期策略，规避集中过期，减少缓存失效带来业务抖动。
 | 原文链接：http://wiki.nzrkf5.asia/arts/920932.Doc

原标题：架构思考：单体应用向微服务拆分演进路径
简介：golang context 取消传播机制，父 ctx 取消，所有派生子 context 全部被取消，理解上下文传播。
 | 原文链接：http://wiki.nzrkf5.asia/arts/744696.Doc

原标题：项目实践：灰度发布简易方案落地实践
简介：golang net.Conn 包装自定义连接，包装 net.Conn，统计读写字节，日志打印，超时控制。
 | 原文链接：http://wiki.nzrkf5.asia/arts/297376.Doc

原标题：从零学习基础的接口请求与参数处理
简介：请求重试组件退避策略实现，封装重试组件，实现指数退避策略，避免大量请求同时重试压垮下游。
 | 原文链接：http://wiki.nzrkf5.asia/arts/932083.Doc

原标题：nodejs 项目 pm2 部署运维指南
简介：服务熔断防止故障级联传播，实现服务熔断逻辑，下游故障时快速失败，阻止故障向上游链式扩散。
 | 原文链接：http://wiki.nzrkf5.asia/arts/930689.Doc

原标题：golang 系统设计线上日志快速检索技巧
简介：内存广播本地进程消息通知，实现进程内内存消息广播，进程内部模块之间事件通知解耦。
 | 原文链接：http://wiki.nzrkf5.asia/arts/608216.Doc

原标题：golang 系统设计全局异常处理器实现
简介：golang docker 镜像构建最佳实践，Go 项目 Docker 镜像构建最佳实践，减小镜像体积，安全构建。
 | 原文链接：http://wiki.nzrkf5.asia/arts/765476.Doc

原标题：游标分页大数据查询性能提升
简介：golang ssh 客户端远程命令执行，golang ssh 连接远程服务器，执行 shell 命令，获取命令输出结果。
 | 原文链接：http://wiki.nzrkf5.asia/arts/660310.Doc

原标题：安全笔记：请求头伪造IP漏洞防护
简介：golang go 整洁架构代码组织实践，整洁架构依赖向内，解耦业务逻辑与外部基础设施。
 | 原文链接：http://wiki.nzrkf5.asia/arts/183353.Doc

原标题：Redis 热点 key 拆分降低集群压力
简介：操作系统内核版本适配服务，针对服务运行要求，适配操作系统内核版本，规避内核兼容 bug。
 | 原文链接：http://wiki.nzrkf5.asia/arts/907668.Doc

四、架构设计｜Architecture
原标题：项目实践：灰度发布简易方案落地实践
简介：golang go 时间 time.Timer time.Ticker，定时器与周期定时器，Stop Reset 正确使用，防止资源泄漏。
 | 原文链接：http://wiki.nzrkf5.asia/arts/527576.Doc

原标题：golang cron 定时任务防并发执行
简介：golang go 符号表与调试信息取舍，区分生产环境调试符号取舍，平衡镜像体积与故障排查能力。
 | 原文链接：http://wiki.nzrkf5.asia/arts/611771.Doc

原标题：golang mysql 主从同步延迟兼容
简介：文件锁正确使用避免死锁，合理使用文件锁，控制多进程访问同一个文件，规避文件锁死锁现象。
 | 原文链接：http://wiki.nzrkf5.asia/arts/284554.Doc

原标题：快速入门环境区分：开发、测试、生产环境
简介：golang http.Server 配置参数详解，ReadTimeout WriteTimeout IdleTimeout，全方位防护慢请求攻击。
 | 原文链接：http://wiki.nzrkf5.asia/arts/686599.Doc

原标题：vite 插件开发自定义构建逻辑
简介：golang 自定义 http round tripper，封装 http 客户端拦截，实现请求日志、签名、重试统一处理逻辑。
 | 原文链接：http://wiki.nzrkf5.asia/arts/649959.Doc

原标题：项目目录结构规范化最佳实践
简介：golang mysql 慢查询日志程序采集解析，程序读取解析 mysql 慢查询日志，统计慢 SQL 做监控告警。
 | 原文链接：http://wiki.nzrkf5.asia/arts/641130.Doc

原标题：golang redis 过期 key 监听业务
简介：golang md5 sha 加密工具实现，实现 MD5、SHA 哈希工具，做数据摘要，用于签名校验场景。
 | 原文链接：http://wiki.nzrkf5.asia/arts/652738.Doc

原标题：Spring 事务传播机制配置生效
简介：数值 key 浮点匹配异常规避，避免浮点数作为 Redis 等存储的 key，防止精度问题引发 key 匹配失败。
 | 原文链接：http://wiki.nzrkf5.asia/arts/555319.Doc

原标题：限流窗口绕过漏洞修复方案
简介：golang 换行符统一处理，文本文件读写统一换行符，规避不同系统换行符带来解析异常。
 | 原文链接：http://wiki.nzrkf5.asia/arts/686284.Doc

原标题：线上异常：接口偶发超时，完整定位过程记录
简介：golang go xml 解析生成 xml 文档，encoding/xml 解析 xml，结构体标签映射 xml 节点属性。
 | 原文链接：http://wiki.nzrkf5.asia/arts/717716.Doc

原标题：golang 系统设计无锁编程思路简单示例
简介：请求重试组件退避策略实现，封装重试组件，实现指数退避策略，避免大量请求同时重试压垮下游。
 | 原文链接：http://wiki.nzrkf5.asia/arts/901504.Doc

原标题：golang 系统设计短链接服务实现思路
简介：golang go 模块迁移从 GOPATH 到 GoMod，老项目从 GOPATH 迁移 go mod，解决依赖管理混乱问题。
 | 原文链接：http://wiki.nzrkf5.asia/arts/726287.Doc

原标题：快速上手简单的限流逻辑模拟实现
简介：axios 二次封装请求拦截处理，对 axios 做二次封装，统一请求拦截响应拦截，处理错误、token 自动刷新。
 | 原文链接：http://wiki.nzrkf5.asia/arts/074189.Doc

原标题：开发复盘：导出大文件避免内存溢出实现方案
简介：golang 内存 dump 线上堆快照采集，线上生成内存 dump 文件，线下分析，定位内存泄漏问题。
 | 原文链接：http://wiki.nzrkf5.asia/arts/054082.Doc

原标题：golang 系统设计排行榜几种实现
简介：golang 文件句柄耗尽排查处理，统计进程打开文件句柄，找到未关闭文件，修复句柄泄漏问题。
 | 原文链接：http://wiki.nzrkf5.asia/arts/737133.Doc

原标题：项目实践：数据库慢日志采集分析落地实践
简介：golang fasthttp 服务开发完整示例，fasthttp 搭建 http 服务，路由、参数读取、响应返回完整业务。
 | 原文链接：http://wiki.nzrkf5.asia/arts/964751.Doc

原标题：设计思考：分布式ID系统架构选型对比
简介：golang jwt 令牌刷新逻辑实现，实现 JWT 双令牌机制，access 短期有效 refresh 刷新令牌，实现无感续期登录。
 | 原文链接：http://wiki.nzrkf5.asia/arts/677012.Doc

原标题：react hooks 常见陷阱避坑指南
简介：限流窗口绕过漏洞修复方案，修复限流时间窗口漏洞，避免攻击者绕过限流规则，保障接口防护有效。
 | 原文链接：http://wiki.nzrkf5.asia/arts/008030.Doc

?
