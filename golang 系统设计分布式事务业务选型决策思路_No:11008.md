最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计分布式事务业务选型决策思路
简介：golang grpc 重试机制客户端配置，grpc 客户端配置重试策略，临时故障自动重试，提升调用稳定性。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/994394.sHtML

原标题：实践：前后端时间格式统一规范落地实践
简介：程序信号中断退出处理逻辑，捕获系统中断信号，执行资源释放、关闭连接，实现程序优雅退出。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/267628.sHtML

原标题：性能复盘：磁盘Swap大量使用系统卡顿优化
简介：golang os.Exit 退出程序注意 defer 不执行，os.Exit 会直接退出，不会执行 defer，优雅退出不要直接 os.Exit。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/182176.sHtML

原标题：记一次分布式锁失效引发的数据错乱问题
简介：golang 容器 OOM 被杀死排查区分，区分业务内存泄漏、容器限制过小，定位容器 OOMKilled 原因。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/519111.sHtML

原标题：golang 开发环境快速搭建指南
简介：golang mock 单元测试编写技巧，单元测试 mock 外部依赖，隔离数据库网络，只测试业务逻辑本身。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/881541.sHtML

原标题：nodejs 消息队列消费服务开发
简介：golang 日志脱敏敏感字段过滤，日志打印自动脱敏敏感字段，避免日志输出手机号身份证泄露隐私。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/681270.sHtML

原标题：开发记录：分布式ID生成器实现与压力测试
简介：内网 DNS 不稳定随机报错排查，定位内网 DNS 抖动问题，配置备选 DNS，解决偶现域名解析失败。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/417794.sHtML

原标题：golang 系统设计集成测试数据库回滚重置方案
简介：golang context.WithTimeout 超时上下文，WithTimeout 设置超时时间，超时自动 cancel 释放协程。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/048332.sHtML

原标题：Shell 运维脚本服务器效率提升
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/129547.sHtML

原标题：golang k8s 基础概念 pod deployment
简介：简易网关请求路由过滤模拟，模拟网关基础能力，实现请求路由转发、简单过滤，理解网关核心工作逻辑。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/239969.sHtML

原标题：开发记录：接口请求日志记录完整中间件实现
简介：golang slice 切片底层原理与坑点，切片扩容、截取、底层数组共享，规避切片修改互相影响数据。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/701965.sHtML

原标题：golang 系统设计网络 io 模型 epoll 原理讲解
简介：golang kafka 消费者位移管理，理解 kafka offset，手动提交位移，保证消息消费至少一次语义。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/774210.sHtML

原标题：golang docker 基础命令实操汇总
简介：golang docker 镜像构建最佳实践，Go 项目 Docker 镜像构建最佳实践，减小镜像体积，安全构建。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/591369.sHtML

原标题：开源实践：参与开源项目从Issue到PR完整流程
简介：golang go mod replace 本地模块替换，replace 替换模块为本地目录，修改第三方库本地调试。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/167996.sHtML

原标题：golang 系统设计蓝绿发布滚动发布对比
简介：hosts 配置本地回环访问修复，修改 hosts 配置，修复 127.0.0.1 解析异常，本地服务访问失败问题。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/379670.sHtML

原标题：零基础理解数据库事务基础ACID概念
简介：golang hertz 性能优化参数调优，hertz 连接池、缓冲区参数调优，最大化接口吞吐性能。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/611401.sHtML

原标题：WSL 内存上限限制防止资源耗尽
简介：golang 工具函数库封装思路，Go 通用工具库封装思路，错误处理、类型转换，业务项目复用工具代码。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/613390.sHtML

原标题：踩坑：对象未释放，长时间运行内存持续上涨
简介：程序日志分级输出规范实践，区分日志等级，规范日志打印内容，合理输出日志，方便线上问题排查定位。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/729866.sHtML

原标题：Hands‑on：代码生成器，一键生成CRUD模板
简介：golang 滑动窗口限流算法 go 实现，滑动窗口限流，解决固定窗口临界流量突增漏洞，限流更精准。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/506360.sHtML

原标题：golang 系统设计 websocket 协议原理梳理
简介：golang errors.Is errors.As 错误判断，判断是否为指定错误类型，提取自定义错误信息，错误处理进阶。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/973339.sHtML

原标题：记一次本地运行正常，线上环境报错诡异问题
简介：golang go 项目 CI github actions 配置，github actions 实现 go 项目 ci，自动测试、代码检查、编译打包镜像。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/912686.sHtML

原标题：webpack chunk 分包策略详解
简介：限流规则误拦截正常请求修复，修正限流规则阈值，避免合法用户被限流拦截，兼顾防护与可用性。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/305879.sHtML

原标题：图片上传预览格式大小处理
简介：golang 消息死信处理业务逻辑，Go 实现死信队列逻辑，消费失败消息转入死信，不阻塞正常消息队列。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/123481.sHtML

原标题：DevOps：环境配置管理区分开发测试生产
简介：golang 协程 panic 捕获防止崩溃，协程内部捕获 panic，防止单个协程恐慌造成整个 Go 进程崩溃。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/798430.sHtML

原标题：安全笔记：Cookie安全属性SecureHttpOnly
简介：golang 日志输出 stdout 标准输出规范，容器环境日志输出到 stdout，由容器平台统一采集日志文件。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/255942.sHtML

原标题：golang 系统设计防重复提交实现
简介：golang 限流熔断放在代理层实践，代理层统一限流熔断，对后端服务做流量保护。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/182869.sHtML

原标题：入门实践：简单图片上传预览本地demo
简介：golang http client 连接池调优，调优 Go HTTP Client 连接池参数，复用 TCP 连接，减少连接创建开销。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/556663.sHtML

原标题：golang 系统设计本地缓存 redis 缓存多级组合
简介：不必要字符转义关闭业务异常，关闭多余自动转义逻辑，防止业务数据被错误转义，破坏原始数据。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/245533.sHtML

原标题：golang 系统设计分表跨表 join 业务处理方案
简介：项目构建脚本编译打包解析，解读项目构建脚本，理清编译、压缩、资源复制流程，理解打包后产物如何生成。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/608022.sHtML

原标题：开发复盘：实现定时任务调度服务支持动态任务
简介：golang http body 必须关闭的重要性，无论成功失败必须关闭 request.Body，否则连接无法复用泄漏。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/018798.sHtML

原标题：golang prometheus counter gauge 使用
简介：DNS TTL 配置域名切换生效，调整 DNS 解析 TTL，缩短缓存时间，域名变更后可以快速全网生效。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/248170.sHtML

原标题：安全笔记：依赖包漏洞检测供应链安全
简介：golang channel 作为函数参数方向，声明 channel 入参方向，只读 channel 只写 channel 提升代码约束。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/893387.sHtML

原标题：项目实践：搭建个人API网关最小实现版本
简介：golang 数据库连接池泄露检测逻辑，监控连接池状态，检测连接长时间未归还，告警连接泄漏问题。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/566900.sHtML

原标题：项目实践：多环境配置管理组件设计与实现
简介：golang gorm 软删除实现逻辑，Gorm 开启软删除，删除数据仅标记，数据保留可恢复，满足业务数据留存。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/495722.sHtML

原标题：文件句柄上限调整上传随机失败
简介：文件读写与异常捕获代码示例，演示文件读取写入操作，增加异常捕获逻辑，规避文件不存在、权限不足导致崩溃。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/153645.sHtML

原标题：实战项目：本地搭建Prometheus监控完整demo
简介：golang sync.Mutex 互斥锁正确模式，互斥锁 defer Unlock，锁粒度控制，避免锁范围过大。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/586501.sHtML

原标题：golang rsa 非对称加密签名验签
简介：golang prometheus http 接口暴露指标，暴露 prometheus metrics 接口，输出业务运行指标，接入监控告警系统。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/411418.sHtML

原标题：零基础理解前后端简单交互流程
简介：golang go select 多路等待 channel，select 等待多个 channel，default 非阻塞，超时等待 channel。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/734170.sHtML

原标题：快速上手单元测试，写出第一个测试用例
简介：golang lru 缓存淘汰算法编写，手写 LRU 缓存淘汰算法，实现本地缓存，淘汰最久未使用数据。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/120763.sHtML

原标题：操作系统内核版本适配服务
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/926510.sHtML


二、踩坑排错｜Troubleshooting
原标题：新手向：项目目录结构规范与含义解析
简介：golang 日志 zap 结构化日志实践，接入 Zap 结构化日志库，打印结构化日志，方便日志检索解析。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/766940.sHtML

原标题：文件句柄上限调整上传随机失败
简介：golang nilnil interface 陷阱复现，interface 包含类型不为 nil 值为 nil，判 ==nil 返回 false 经典坑。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/201069.sHtML

原标题：大事务拆分防止连接池耗尽
简介：golang go 信号处理优雅重启实现，USR2 触发程序重启，不关闭监听 socket 实现零停机升级。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/726944.sHtML

原标题：Issue：操作系统最大打开文件数限制导致报错
简介：golang redis 锁超时业务处理，Redis 分布式锁超时问题处理，锁续期逻辑，防止业务未完成锁提前释放。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/892249.sHtML

原标题：项目实践：MySQL读写分离本地模拟实践
简介：golang hertz 反向代理与负载均衡，hertz 实现反向代理，内置负载均衡，快速搭建网关类服务。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/223520.sHtML

原标题：开发环境变量配置全平台教程
简介：ICMP 放通网络丢包问题修复，放开 ICMP 协议，解决 MTU 问题导致网络丢包，修复网络不稳定现象。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/720746.sHtML

原标题：golang 系统设计故障预案编写模板参考示例
简介：golang kitex 中间件与元数据传递，kitex 自定义中间件，透传 traceId 鉴权元数据，统一处理请求。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/453077.sHtML

原标题：golang 系统设计技术文档维护更新最佳实践
简介：定时任务周期调度 demo 开发，实现简单定时调度程序，按时间周期执行业务逻辑，理解定时任务运行机制。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/163373.sHtML

原标题：Security：SSRF服务端请求伪造漏洞防御
简介：golang grafana 面板 go 业务指标可视化，prometheus 指标对接 grafana，配置监控面板可视化业务状态。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/380400.sHtML

原标题：新手向：开源项目fork与同步上游代码
简介：golang redis lua 脚本原子操作，使用 Lua 脚本实现原子逻辑，减少网络往返，保障多命令原子执行。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/015106.sHtML

原标题：golang 系统设计线上问题复现思路简单讲解
简介：golang 正则表达式 Go 实操案例，正则匹配提取替换，处理手机号邮箱校验，规避正则回溯 CPU 暴涨。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/718202.sHtML

原标题：golang 系统设计批量处理优化业务性能
简介：golang tcp keepalive 参数程序配置，go 程序设置 tcp keepalive，操作系统 tcp 保活参数，清理僵死连接。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/462843.sHtML

原标题：TLS 版本兼容 HTTPS 握手失败
简介：golang staticcheck 静态代码分析，staticcheck 深度静态检查，发现代码错误、性能问题、风格问题。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/078050.sHtML

原标题：Practice：实现简单信号处理优雅停机实践
简介：golang 项目 go mod 依赖管理，Go Mod 管理项目依赖，下载、升级、清理依赖，解决依赖版本管理。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/919655.sHtML

原标题：Architecture：事件溯源架构模式适用业务场景
简介：本地数据库开发环境搭建指南，讲解数据库安装配置、账号权限设置、连接测试，快速搭建用于开发调试的数据库实例。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/400928.sHtML

原标题：pnpm 包管理工具实战避坑指南
简介：golang udp 服务端客户端开发示例，golang 实现 UDP 服务收发数据包，实现 udp 协议通信程序。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/939706.sHtML

原标题：golang 系统设计分布式任务调度
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/616960.sHtML

原标题：OpenAPI 自动接口文档生成
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/302304.sHtML

原标题：golang 系统设计 tcp 粘包拆包处理方案实现
简介：防火墙 IP 白名单回调接口放行，配置防火墙白名单，放行第三方回调服务器 IP，接收回调请求正常。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/237464.sHtML

原标题：golang dockerfile 多阶段构建详解
简介：golang 数据库 ORM 框架选型对比，gorm xorm sqlx 对比各 ORM 优缺点，根据业务场景选型。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/233889.sHtML

原标题：Hands‑on：简易代理服务器开发实践
简介：golang redis lua 脚本原子操作，使用 Lua 脚本实现原子逻辑，减少网络往返，保障多命令原子执行。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/649591.sHtML

原标题：效率笔记：GitWorkflow团队协作规范模板
简介：内存溢出问题现象识别排查，识别内存溢出现象，梳理排查方向，定位内存持续上涨引发服务崩溃问题。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/400608.sHtML

原标题：golang mysql 分表 id 路由逻辑
简介：golang math 包常用数学函数，绝对值取整平方根三角函数，业务数学计算工具。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/378000.sHtML

原标题：Practice：模拟数据库故障验证降级逻辑实践
简介：Nginx 缓冲区调优大文件上传，调大 Nginx 请求缓冲区，支持客户端上传大体积文件，避免上传被截断。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/795302.sHtML

原标题：golang 表单文件大小限制配置
简介：golang k8s secret 敏感配置加载，加载 k8s secret 存储密钥密码，敏感信息不存放配置文件。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/673073.sHtML

原标题：DevOps：GitLabCI完整流水线配置示例
简介：golang go 种子初始化 rand 随机，rand 初始化种子，不初始化会固定序列，理解随机数种子行为。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/458093.sHtML

原标题：golang 系统设计故障复盘模板 postmortem 参考
简介：数据库索引重建提升查询速度，针对碎片化索引，重建数据库索引，恢复 SQL 查询执行性能。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/932118.sHtML

原标题：Security：文件上传漏洞攻击面完整防护方案
简介：Fork 开源项目同步上游代码，Fork 开源仓库之后，配置上游源，同步官方最新代码，保持代码版本对齐。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/991651.sHtML

原标题：golang 系统设计最小权限原则落地实践
简介：macOS 脚本执行权限开启，给 Shell 脚本添加可执行权限，解决 macOS 下脚本无法运行权限报错。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/369523.sHtML

原标题：golang 系统设计 git 工作流本地开发提交流程
简介：golang math 包常用数学函数，绝对值取整平方根三角函数，业务数学计算工具。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/671632.sHtML

原标题：golang 开发环境快速搭建指南
简介：golang 服务注册 etcd 简单示例，etcd 实现服务注册发现，微服务实例注册元数据，客户端发现节点。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/169824.sHtML

原标题：开发测试生产多环境配置区分
简介：golang http 服务性能优化调参，调优 Go HTTP 服务参数，调整连接池，提升服务并发吞吐能力。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/370525.sHtML

原标题：Git LFS 大文件推送失败解决
简介：Cookie Session 会话状态管理，讲解 Cookie 与 Session 原理，理解登录状态保存，实现服务端会话管理逻辑。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/894328.sHtML

原标题：golang mysql 慢查询日志开启分析
简介：golang 任务失败重试与死信队列，异步任务失败自动重试，超过重试次数进入死信队列人工处理。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/574660.sHtML

原标题：golang 系统设计 http1.1 http2 核心差异讲解
简介：golang go 网络编程 net 包基础，net 包 tcp udp socket 编程，监听接收连接，读写数据。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/902808.sHtML

原标题：golang k8s service 服务暴露几种类型
简介：golang goroutine 泄露检测告警实现，监控 goroutine 数量，突增触发告警，提早发现协程泄露。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/159552.sHtML

原标题：分布式锁失效问题排查修复
简介：golang jwt 令牌刷新逻辑实现，实现 JWT 双令牌机制，access 短期有效 refresh 刷新令牌，实现无感续期登录。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/885791.sHtML

原标题：分布式锁失效问题排查修复
简介：golang go mod vendor 本地依赖导出，导出 vendor 目录，离线环境编译项目，无需访问外网拉依赖。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/310114.sHtML

原标题：golang 大文件读取内存优化
简介：golang redis 过期时间处理技巧，设置 key 过期，监控过期事件，基于过期特性实现业务缓存逻辑。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/318096.sHtML

原标题：零基础理解会话、Cookie、Session基础
简介：golang make new 关键字使用区别，分清 new 与 make 适用类型，正确初始化切片 map 通道，杜绝 nil 引发 panic。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/900399.sHtML

三、实战开发｜Practice
原标题：golang 系统设计 protobuf 枚举类型规范写法
简介：golang 项目 go mod 依赖管理，Go Mod 管理项目依赖，下载、升级、清理依赖，解决依赖版本管理。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/569211.sHtML

原标题：golang 系统设计业务指标系统指标定义思路
简介：开发生产环境资源路径统一，对齐开发环境与生产环境资源路径，防止本地正常上线后资源找不到。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/970636.sHtML

原标题：golang base64 编码解码实操
简介：服务熔断防止故障级联传播，实现服务熔断逻辑，下游故障时快速失败，阻止故障向上游链式扩散。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/721361.sHtML

原标题：Practice：实现接口签名、验签完整示例代码
简介：读懂开源项目 README 实用技巧，教你快速解析开源项目说明文档，提取安装、运行、配置关键信息，快速上手项目。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/722274.sHtML

原标题：golang 系统设计内存瓶颈定位优化思路
简介：golang errors.Is errors.As 错误判断，判断是否为指定错误类型，提取自定义错误信息，错误处理进阶。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/825651.sHtML

原标题：Hands‑on：代码生成器，一键生成CRUD模板
简介：Docker 多阶段构建镜像瘦身，使用 Docker 多阶段构建，剔除编译阶段依赖，产出体积更小运行镜像。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/507591.sHtML

原标题：Hands‑on：简易验证码生成校验后端实践
简介：golang raw socket 底层网络报文收发，raw socket 收发原始网络报文，做网络抓包数据包处理。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/737928.sHtML

原标题：golang 系统设计网关错误重试超时处理策略
简介：CPU 亲和性配置负载均衡调度，配置进程 CPU 亲和，均衡利用多核 CPU，优化程序调度性能。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/718284.sHtML

原标题：后端登录鉴权模块完整开发
简介：golang 程序崩溃 core dump 生成调试，开启 core dump，程序崩溃生成转储文件，事后分析崩溃原因。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/304352.sHtML

原标题：CORS 跨域问题多种解决方案
简介：golang gin 静态资源访问配置，Gin 配置静态资源目录，直接对外提供静态文件访问服务。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/441947.sHtML

原标题：方案对比：单体、微服务、模块化单体取舍
简介：CI 流水线构建失败日志排查，阅读 CI 流水线输出日志，定位构建脚本、依赖、环境导致流水线失败问题。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/335377.sHtML

原标题：golang 系统设计本地缓存更新失效方案实现
简介：JSON XML 数据解析处理示例，演示两种格式数据解析与序列化，增加异常捕获，处理格式错乱导致解析失败。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/758520.sHtML

原标题：安全实践：接口错误信息不要暴露内部细节
简介：golang go 服务日志输出 journald，systemd journald 接收程序 stdout 日志，统一管理服务日志。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/599654.sHtML

原标题：踩坑：Docker容器内时区不一致引发的时间BUG
简介：golang 后端节点健康检查机制实现，定时探测后端节点状态，自动剔除故障节点，保障转发可用。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/457516.sHtML

原标题：多实例部署 Session 共享方案
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/733117.sHtML

原标题：nodejs 读取大文件 csv 处理方案
简介：异步编程 Promise 执行流程解析，拆解异步执行顺序，理解回调与 Promise 差异，理清异步场景下代码执行逻辑。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/890184.sHtML

原标题：golang 系统设计日志检索排查线上问题实操技巧
简介：golang tcp 连接泄露排查定位，netstat 查看连接状态，找出未正常关闭连接，定位连接泄漏代码。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/619255.sHtML

原标题：golang 结构体深拷贝几种实现
简介：golang multipart 表单文件上传解析，服务端解析 multipart 表单，获取上传文件与表单字段。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/756352.sHtML

原标题：GC 垃圾回收优化降低 CPU 占用
简介：项目语义化版本号规范管理，遵循语义化版本规范管理项目版本，明确主次版本变更含义。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/774631.sHtML

原标题：golang gin 框架接口开发实战
简介：golang go 爬虫 robots 协议遵守，解析 robots.txt 规则，控制爬虫抓取范围，合规采集网页数据。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/647354.sHtML

原标题：TCP 心跳检测清理僵死连接
简介：golang 静态编译缩小镜像体积，Go 程序静态编译，不依赖系统库，产出单二进制文件，缩小镜像。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/458705.sHtML

原标题：golang 消息死信处理业务逻辑
简介：golang make new 关键字使用区别，分清 new 与 make 适用类型，正确初始化切片 map 通道，杜绝 nil 引发 panic。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/608989.sHtML

原标题：接口请求重试容错机制实现
简介：golang 服务注册 etcd 简单示例，etcd 实现服务注册发现，微服务实例注册元数据，客户端发现节点。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/618417.sHtML

原标题：golang 系统设计 gob msgpack 序列化对比
简介：依赖版本冲突兼容修复方案，定位依赖版本冲突根源，通过版本约束、替换包，解决版本不兼容运行报错。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/287323.sHtML

原标题：零基础理解读写分离基础思想
简介：golang 时间戳秒毫秒纳秒转换，Unix UnixMilli UnixNano 互相转换，区分单位避免时间逻辑 bug。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/499661.sHtML

原标题：开发复盘：分布式会话共享多种方案实践
简介：golang pprof 线上采集性能数据，线上环境采集 pprof 性能样本，不用停机，分析线上性能问题。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/641458.sHtML

原标题：CLI 工具进度条交互效果开发
简介：golang go‑zero 配置中心热更新，go‑zero 对接 etcd 配置中心，配置热更新无需重启服务。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/821561.sHtML

原标题：golang 系统设计定时任务动态启停配置方案
简介：从零编写简易 CLI 命令行工具，通过实战案例实现基础命令交互，理解命令行程序执行逻辑，产出可运行小工具。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/808733.sHtML

原标题：golang 系统设计线上问题复现思路简单讲解
简介：golang 内存 dump 线上堆快照采集，线上生成内存 dump 文件，线下分析，定位内存泄漏问题。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/387700.sHtML

原标题：golang 系统设计单元测试表驱动测试 table‑driven
简介：golang mysql 慢查询日志程序采集解析，程序读取解析 mysql 慢查询日志，统计慢 SQL 做监控告警。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/738452.sHtML

原标题：看懂报错日志快速定位问题
简介：golang io.MultiReader MultiWriter 拼接流，多个 reader 拼接，多 writer 同时写入一份数据。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/389674.sHtML

原标题：golang k8s pod 优雅关闭流程讲解
简介：正则表达式文本处理实战案例，结合业务场景演示正则匹配、提取、替换，处理手机号、邮箱等各类文本校验需求。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/159804.sHtML

原标题：golang 告警推送钉钉机器人实现
简介：golang fasthttp 客户端连接池调优，fasthttp 客户端连接池配置，复用连接提升请求性能。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/074622.sHtML

原标题：安全笔记：CSP内容安全策略配置实践
简介：golang math 包常用数学函数，绝对值取整平方根三角函数，业务数学计算工具。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/468549.sHtML

原标题：golang 限流熔断降级完整示例
简介：主干开发团队代码合并策略，讲解主干开发模式，团队代码合并流程，适合高频迭代的团队协作模式。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/491344.sHtML

原标题：复盘总结：技术选型对比文档模板实践
简介：WSL 搭建 Windows Linux 开发环境，配置 WSL 环境，在 Windows 系统使用 Linux 工具链，适配 Linux 开发项目。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/161098.sHtML

原标题：前端骨架屏提升页面体验
简介：数据库索引重建提升查询速度，针对碎片化索引，重建数据库索引，恢复 SQL 查询执行性能。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/304300.sHtML

原标题：golang 系统设计链路追踪核心概念 trace span 讲解
简介：golang go‑zero 监控指标埋点，go‑zero 内置 metrics 监控，上报业务指标对接监控平台。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/745439.sHtML

原标题：站内邮件消息通知功能开发
简介：项目脚手架模板生成工具，搭建项目模板脚手架，一键生成标准化项目骨架，减少重复初始化工作。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/919873.sHtML

原标题：优化实践：异步改造同步接口提升吞吐能力
简介：golang go 程序权限最小化运行，容器内使用普通用户运行程序，拒绝 root 运行提升安全等级。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/042117.sHtML

四、架构设计｜Architecture
原标题：特殊输入字符过滤解析防护
简介：全量回归测试提升代码质量，搭建全量回归测试集，版本发布执行回归测试，避免迭代引入旧 bug。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/606872.sHtML

原标题：记一次GC频繁，服务CPU持续高负载排查
简介：golang trace 可视化分析协程阻塞，使用 trace 网页 UI，定位协程阻塞、系统调用阻塞、锁等待。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/858437.sHtML

原标题：golang 优雅关闭 grpc 服务示例
简介：Redis 内存淘汰策略数据防丢失，合理配置 Redis 内存淘汰策略，防止内存满后误删除业务重要数据。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/975157.sHtML

原标题：golang k8s cronjob 定时任务配置
简介：依赖版本冲突兼容修复方案，定位依赖版本冲突根源，通过版本约束、替换包，解决版本不兼容运行报错。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/715716.sHtML

原标题：Hands‑on：编写自定义Git钩子实现代码提交校验
简介：golang nilnil interface 陷阱复现，interface 包含类型不为 nil 值为 nil，判 ==nil 返回 false 经典坑。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/640073.sHtML

原标题：运维笔记：服务器日志轮转logrotate配置
简介：接口幂等性防重复请求实现，实现接口幂等逻辑，避免重复提交请求产生多条脏数据，保障业务数据安全。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/903519.sHtML

原标题：golang mysql 悲观锁乐观锁实现
简介：golang 服务限流熔断降级监控完整实践，微服务防护体系，限流熔断降级指标监控告警整套落地。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/999411.sHtML

原标题：golang 系统设计日志与 traceId 关联打印实现
简介：极简 API 网关路由转发实现，开发极简网关服务，完成请求路由转发，理解网关基础实现原理。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/464227.sHtML

原标题：实践：大文件分片上传后端完整实现思路
简介：golang go 初始化顺序包变量 init 函数，包级变量初始化，init 执行顺序，理解包加载执行流程。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/575473.sHtML

原标题：AI实践：大模型生成测试用例实践与校验
简介：容器软链接文件权限修复，修复容器内软链接文件权限，让程序能够正常读取软链接指向的文件。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/274337.sHtML

原标题：前端工程化 webpack 打包优化
简介：golang trace 可视化分析协程阻塞，使用 trace 网页 UI，定位协程阻塞、系统调用阻塞、锁等待。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/564156.sHtML

原标题：Troubleshooting：WSL文件权限问题大量踩坑
简介：nodejs 信号处理优雅关闭服务，监听系统信号，执行资源清理，实现 Node 服务优雅停机，拒绝粗暴杀死进程。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/432026.sHtML

原标题：排错：HTTPS证书过期导致接口调用失败
简介：后端大文件分片上传接口开发，开发后端分片上传接口，接收分片，合并分片完成大文件存储。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/805653.sHtML

原标题：golang 系统设计 k8s 集群安全配置梳理
简介：vite 插件开发自定义构建逻辑，开发自定义 vite 插件，介入构建生命周期，实现项目个性化构建逻辑。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/260064.sHtML

原标题：踩坑记录：乐观锁版本号处理不当更新失败
简介：golang ssh 客户端远程命令执行，golang ssh 连接远程服务器，执行 shell 命令，获取命令输出结果。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/995113.sHtML

原标题：避坑：预编译SQL失效，出现SQL注入风险
简介：vite 插件开发自定义构建逻辑，开发自定义 vite 插件，介入构建生命周期，实现项目个性化构建逻辑。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/573961.sHtML

原标题：踩坑：批量MQ消费失败直接无限重试消息爆炸
简介：代理 HTTPS 证书访问异常处理，配置代理根证书，解决代理环境 HTTPS 证书校验失败无法访问外网。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/597669.sHtML

原标题：golang 系统设计 ci 流水线安全管控思路
简介：golang 内存碎片问题识别与规避，大量小对象频繁分配产生内存碎片，通过对象池减少碎片。
 | 原文链接：http://blog.yuanyustar.cn/Article/details/596338.sHtML

?
