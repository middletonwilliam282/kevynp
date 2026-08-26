最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 优雅处理数据库事务
简介：golang 异步任务队列 worker 池开发，任务入数据库或 redis，worker 池消费执行，异步处理耗时业务。
 | 原文链接：http://book.9ysco2.asia/blog/655874.Doc

原标题：坑点：依赖缓存未更新，旧代码持续运行
简介：golang go 程序版本号内置编译注入，编译时注入 git commit 版本号，程序运行输出版本便于排查。
 | 原文链接：http://book.9ysco2.asia/blog/077528.Doc

原标题：安全笔记：依赖包漏洞检测供应链安全
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://book.9ysco2.asia/blog/931467.Doc

原标题：排错：前端打包chunk过大浏览器加载缓慢
简介：golang 静态编译缩小镜像体积，Go 程序静态编译，不依赖系统库，产出单二进制文件，缩小镜像。
 | 原文链接：http://book.9ysco2.asia/blog/855156.Doc

原标题：开源项目本地运行排错完整清单
简介：golang elasticsearch 客户端 golang 实操，es 客户端文档增删改查，条件搜索聚合统计对接搜索引擎。
 | 原文链接：http://book.9ysco2.asia/blog/753956.Doc

原标题：Debug：请求头过大Nginx拒绝连接报错
简介：nodejs 进程间通信 IPC 实操，演示 Node.js 主进程子进程 IPC 通信，进程之间传递消息数据。
 | 原文链接：http://book.9ysco2.asia/blog/050626.Doc

原标题：开发复盘：百万数据批量导入数据库优化方案
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://book.9ysco2.asia/blog/382401.Doc

原标题：前端权限路由动态生成实现
简介：Nginx 缓冲区调优大文件上传，调大 Nginx 请求缓冲区，支持客户端上传大体积文件，避免上传被截断。
 | 原文链接：http://book.9ysco2.asia/blog/041841.Doc

原标题：golang k8s ingress 路由域名转发
简介：golang cron 任务漂移问题处理，cron 任务执行超时导致任务漂移，通过分布式锁防止任务重叠执行。
 | 原文链接：http://book.9ysco2.asia/blog/600673.Doc

原标题：踩坑记录：浮点数作为Rediskey匹配异常
简介：golang redis pipeline 批量操作，使用 Redis Pipeline 批量执行多条命令，减少网络往返，提升批量操作性能。
 | 原文链接：http://book.9ysco2.asia/blog/923277.Doc

原标题：golang 日志脱敏敏感字段过滤
简介：golang 半关闭 tcp 连接 shutdown，tcp 连接 shutdown 半关闭，单向关闭读或者写，理解 tcp 关闭流程。
 | 原文链接：http://book.9ysco2.asia/blog/637469.Doc

原标题：WSL 内存上限限制防止资源耗尽
简介：golang json 自定义 MarshalJSON UnmarshalJSON，自定义 json 序列化反序列化逻辑，处理特殊格式字段。
 | 原文链接：http://book.9ysco2.asia/blog/005288.Doc

原标题：golang 系统设计大事务拆分实战思路
简介：golang grpc 拦截器开发鉴权日志，开发 grpc 服务端拦截器，统一做鉴权、日志打印、异常捕获处理。
 | 原文链接：http://book.9ysco2.asia/blog/423921.Doc

原标题：golang 系统设计压测工具 vegeta 使用示例
简介：golang go 包循环导入报错解决，A 导入 B B 导入 A，循环导入报错，重构代码拆分包消除循环依赖。
 | 原文链接：http://book.9ysco2.asia/blog/715004.Doc

原标题：golang k8s cronjob 定时任务配置
简介：golang go 逃逸分析实操查看，go build‑gcflags=-m 查看逃逸分析，减少堆分配优化程序性能。
 | 原文链接：http://book.9ysco2.asia/blog/847769.Doc

原标题：预编译 SQL 防注入实现
简介：golang go‑zero 分布式锁组件使用，go‑zero 内置 redis 分布式锁，业务直接调用实现并发控制。
 | 原文链接：http://book.9ysco2.asia/blog/821598.Doc

原标题：前端国际化多语言方案落地
简介：golang 钉钉企业微信告警消息推送，go 调用企业微信钉钉接口，推送告警通知、业务消息。
 | 原文链接：http://book.9ysco2.asia/blog/603321.Doc

原标题：CI 持续集成自动构建流程
简介：golang go 程序权限最小化运行，容器内使用普通用户运行程序，拒绝 root 运行提升安全等级。
 | 原文链接：http://book.9ysco2.asia/blog/578148.Doc

原标题：golang 系统设计故障定位排查通用步骤方法论
简介：Git 子模块更新代码不全修复，正确更新 Git 子模块，拉取子模块完整代码，解决子模块目录为空问题。
 | 原文链接：http://book.9ysco2.asia/blog/348197.Doc

原标题：实战项目：GitSubmodule管理多仓库实践
简介：任务执行锁防止并发重复调度，增加任务执行锁，多实例环境，防止同一个定时任务并发多次运行。
 | 原文链接：http://book.9ysco2.asia/blog/608436.Doc

原标题：新手向：开源项目本地构建失败通用排查步骤
简介：golang lru 缓存淘汰算法编写，手写 LRU 缓存淘汰算法，实现本地缓存，淘汰最久未使用数据。
 | 原文链接：http://book.9ysco2.asia/blog/412833.Doc

原标题：数值类型溢出错乱问题修复
简介：golang cgo 调用 C 语言代码示例，cgo 调用 C 函数，go 与 C 互相调用，对接 C 语言库能力。
 | 原文链接：http://book.9ysco2.asia/blog/303252.Doc

原标题：golang 系统设计 rest 资源命名规范汇总
简介：包管理器依赖冲突解决方案，分析依赖冲突产生根源，提供版本调整、锁定依赖等手段，解决项目依赖报错问题。
 | 原文链接：http://book.9ysco2.asia/blog/726725.Doc

原标题：零基础理解依赖管理与包管理器
简介：golang tcp_NODELAY 关闭延迟发送，设置 tcp_NODELAY，关闭 Nagle 算法，降低小包请求延迟。
 | 原文链接：http://book.9ysco2.asia/blog/150294.Doc

原标题：Hands‑on：简易ID生成雪花算法完整实现
简介：文件句柄上限调整上传随机失败，调高系统文件句柄上限，解决高并发上传场景随机打开文件失败。
 | 原文链接：http://book.9ysco2.asia/blog/604398.Doc

原标题：部署复盘：数据库主从备份恢复演练实践
简介：golang 错误栈捕获打印方案，捕获错误完整调用堆栈，线上日志输出堆栈，快速定位错误发生代码位置。
 | 原文链接：http://book.9ysco2.asia/blog/234044.Doc

原标题：性能复盘：网络IO优化减少接口等待时间
简介：golang go 调用动态链接库 so 文件，go 加载 so 动态库调用函数，复用编译好的 C 动态库。
 | 原文链接：http://book.9ysco2.asia/blog/743548.Doc

原标题：golang defer panic 异常处理
简介：golang 优雅处理 http 重定向逻辑，自定义控制 http 重定向跳转次数，防止无限重定向死循环。
 | 原文链接：http://book.9ysco2.asia/blog/527335.Doc

原标题：golang 内存 pprof 定位内存泄漏
简介：前端虚拟列表大数据渲染优化，实现虚拟滚动列表，只渲染可视区域 DOM，上万条数据页面流畅渲染。
 | 原文链接：http://book.9ysco2.asia/blog/318377.Doc

原标题：复盘总结：缓存改造业务落地踩坑复盘
简介：内网 DNS 不稳定随机报错排查，定位内网 DNS 抖动问题，配置备选 DNS，解决偶现域名解析失败。
 | 原文链接：http://book.9ysco2.asia/blog/526881.Doc

原标题：实战项目：容器健康探针配置完整实践示例
简介：golang net.Conn 包装自定义连接，包装 net.Conn，统计读写字节，日志打印，超时控制。
 | 原文链接：http://book.9ysco2.asia/blog/260819.Doc

原标题：golang mysql 避免 select * 查询
简介：Nginx 反向代理路由配置实战，配置 Nginx 反向代理，实现请求转发、路由分发，掌握 Nginx 基础配置能力。
 | 原文链接：http://book.9ysco2.asia/blog/837251.Doc

原标题：Hands‑on：简易连接池原型实现理解原理
简介：golang 自定义 http round tripper，封装 http 客户端拦截，实现请求日志、签名、重试统一处理逻辑。
 | 原文链接：http://book.9ysco2.asia/blog/638332.Doc

原标题：服务器 Swap 关闭提升响应速度
简介：接口压测定位系统性能瓶颈，使用压测工具对接口施压，观察指标，定位系统性能瓶颈点。
 | 原文链接：http://book.9ysco2.asia/blog/969160.Doc

原标题：golang k8s 持久化 pv pvc 使用实操
简介：golang strings 常用函数业务实战，字符串分割替换包含判断前缀后缀，掌握 strings 包高频函数。
 | 原文链接：http://book.9ysco2.asia/blog/864356.Doc

原标题：主干开发团队代码合并策略
简介：css 动画性能优化 GPU 加速，优化 CSS 动画，使用 GPU 加速属性，避免动画过程页面卡顿掉帧。
 | 原文链接：http://book.9ysco2.asia/blog/255188.Doc

原标题：开发复盘：内存缓存LRU淘汰策略实现实践
简介：CLI 工具进度条交互效果开发，在命令行工具增加进度条展示，直观反馈任务执行进度，优化命令行体验。
 | 原文链接：http://book.9ysco2.asia/blog/141048.Doc

原标题：golang jaeger 链路追踪 go 接入
简介：容器软链接文件权限修复，修复容器内软链接文件权限，让程序能够正常读取软链接指向的文件。
 | 原文链接：http://book.9ysco2.asia/blog/181600.Doc

原标题：Redis 分布式锁高并发安全实现
简介：golang fasthttp 高性能 http 库使用，fasthttp 高性能 http 实现，适合超高 QPS 场景，对比 net/http 差异。
 | 原文链接：http://book.9ysco2.asia/blog/298031.Doc

原标题：Debug：请求头过大Nginx拒绝连接报错
简介：golang go‑zero rpc 微服务开发，go‑zero 定义 proto，生成 rpc 服务代码，实现微服务调用。
 | 原文链接：http://book.9ysco2.asia/blog/504722.Doc


二、踩坑排错｜Troubleshooting
原标题：golang 系统设计分布式锁看门狗续期原理理解
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://book.9ysco2.asia/blog/319481.Doc

原标题：性能笔记：数据库表字段设计影响查询性能
简介：nodejs 集群模式多核利用实现，使用 cluster 集群模式，充分利用服务器多核 CPU，提升服务处理能力。
 | 原文链接：http://book.9ysco2.asia/blog/092274.Doc

原标题：实战：单元测试+集成测试完整项目落地实践
简介：golang kafka 消费者位移管理，理解 kafka offset，手动提交位移，保证消息消费至少一次语义。
 | 原文链接：http://book.9ysco2.asia/blog/593133.Doc

原标题：游标分页大数据查询性能提升
简介：golang gorm group by 分组统计，GORM 分组聚合统计，实现 count sum 等统计查询，快速完成统计业务。
 | 原文链接：http://book.9ysco2.asia/blog/943706.Doc

原标题：数据库排序规则统一结果一致
简介：golang go 二进制安全 strip 减小体积，strip 剥离二进制调试符号，缩小程序二进制文件体积。
 | 原文链接：http://book.9ysco2.asia/blog/192416.Doc

原标题：大事务拆分防止连接池耗尽
简介：golang 反向代理 http 服务开发，手写简易 http 反向代理，转发请求，修改请求头响应头。
 | 原文链接：http://book.9ysco2.asia/blog/518702.Doc

原标题：环境变量不生效问题修复
简介：SSH 密钥配置 GitHub 免密登录，分步生成配置 SSH 密钥，实现 GitHub 免密推送拉取，免去重复输入账号密码的麻烦。
 | 原文链接：http://book.9ysco2.asia/blog/719117.Doc

原标题：实战：基于内存实现简单消息广播组件
简介：golang regexp 正则捕获分组提取数据，正则捕获分组提取子匹配内容，拿到需要业务字段。
 | 原文链接：http://book.9ysco2.asia/blog/647035.Doc

原标题：内网 DNS 不稳定随机报错排查
简介：golang os 环境变量读取设置，os.Getenv os.Setenv os.Unsetenv 读写环境变量，环境变量多值处理。
 | 原文链接：http://book.9ysco2.asia/blog/564399.Doc

原标题：上传接口跨域配置特殊适配
简介：golang go proxy 私有代理配置，配置 go proxy 私有代理，加速依赖下载，内网环境构建项目。
 | 原文链接：http://book.9ysco2.asia/blog/936550.Doc

原标题：性能复盘：锁等待严重业务逻辑优化记录
简介：RPC 接口字段增减兼容处理，RPC 接口新增删除字段做好向前兼容，老版本服务不会解析报错崩溃。
 | 原文链接：http://book.9ysco2.asia/blog/318027.Doc

原标题：golang goroutine 协程基础实操
简介：macOS 脚本执行权限开启，给 Shell 脚本添加可执行权限，解决 macOS 下脚本无法运行权限报错。
 | 原文链接：http://book.9ysco2.asia/blog/351527.Doc

原标题：优化实践：批量操作性能优化，减少数据库IO
简介：开发代理服务网络限制解决，搭建本地代理服务，解决开发环境网络访问受限，实现外部接口正常调用。
 | 原文链接：http://book.9ysco2.asia/blog/978751.Doc

原标题：方案对比：轮询长轮询WebSocket推送架构选型
简介：golang 配置文件多格式兼容加载，同时支持 yaml toml json 多种格式配置文件，灵活适配不同部署环境。
 | 原文链接：http://book.9ysco2.asia/blog/139413.Doc

原标题：从零搭建简单CLI命令行工具
简介：文件读写与异常捕获代码示例，演示文件读取写入操作，增加异常捕获逻辑，规避文件不存在、权限不足导致崩溃。
 | 原文链接：http://book.9ysco2.asia/blog/345731.Doc

原标题：golang 系统设计自动化测试 ci 流水线集成实操
简介：golang go 测试 t.Run 子测试分组，t.Run 实现子测试，分组执行用例，输出分组测试结果。
 | 原文链接：http://book.9ysco2.asia/blog/610923.Doc

原标题：空指针异常判空容错处理
简介：golang context.Background 与 TODO 区别，Background 主流程根上下文，TODO 不确定用哪个上下文时使用。
 | 原文链接：http://book.9ysco2.asia/blog/304725.Doc

原标题：golang 系统设计分布式配置中心思路
简介：macOS 脚本执行权限开启，给 Shell 脚本添加可执行权限，解决 macOS 下脚本无法运行权限报错。
 | 原文链接：http://book.9ysco2.asia/blog/605778.Doc

原标题：Hands‑on：简易短链接服务完整开发实践
简介：golang gorm 事务手动回滚提交，手动控制事务流程，业务异常主动回滚，保障数据操作原子性。
 | 原文链接：http://book.9ysco2.asia/blog/590910.Doc

原标题：开源实践：开源Issue沟通技巧如何有效提Bug
简介：CORS 跨域问题多种解决方案，对比 CORS、代理等不同跨域方案优缺点，根据业务场景选择合适的跨域处理方式。
 | 原文链接：http://book.9ysco2.asia/blog/075481.Doc

原标题：浏览器缓存强制刷新方案
简介：golang go 种子初始化 rand 随机，rand 初始化种子，不初始化会固定序列，理解随机数种子行为。
 | 原文链接：http://book.9ysco2.asia/blog/359147.Doc

原标题：Practice：实现请求大小限制中间件防护大报文
简介：golang 容器 OOM 被杀死排查区分，区分业务内存泄漏、容器限制过小，定位容器 OOMKilled 原因。
 | 原文链接：http://book.9ysco2.asia/blog/821436.Doc

原标题：踩坑：数据库连接未关闭，连接池泄露
简介：nodejs 项目 pm2 部署运维指南，使用 PM2 管理 Node 服务，进程守护、日志、重启，线上部署运维实操。
 | 原文链接：http://book.9ysco2.asia/blog/712830.Doc

原标题：从零搭建简单Mock接口服务
简介：本地运行正常线上报错排查，对比本地与线上环境差异，从配置、系统版本、文件权限定位线上独有的 bug。
 | 原文链接：http://book.9ysco2.asia/blog/896594.Doc

原标题：API 接口调试与异常处理实战
简介：golang go 程序 CPU 占用高定位步骤，pprof 定位热点函数，分析 CPU 高占用，优化耗时代码逻辑。
 | 原文链接：http://book.9ysco2.asia/blog/896222.Doc

原标题：golang mysql 联合索引最左匹配
简介：数据库读写分离性能优化，讲解读写分离原理，主库写入从库查询，分担数据库查询压力，提升查询性能。
 | 原文链接：http://book.9ysco2.asia/blog/671711.Doc

原标题：踩坑：批量MQ消费失败直接无限重试消息爆炸
简介：golang 日志脱敏敏感字段过滤，日志打印自动脱敏敏感字段，避免日志输出手机号身份证泄露隐私。
 | 原文链接：http://book.9ysco2.asia/blog/754226.Doc

原标题：golang 系统设计覆盖索引减少回表查询实现
简介：线程调度优化减少上下文切换，优化线程数量，减少线程频繁切换，降低 CPU 上下文切换开销。
 | 原文链接：http://book.9ysco2.asia/blog/683000.Doc

原标题：golang 系统设计 e2e 端到端测试简单落地思路
简介：golang http3 quic 客户端服务端示例，go 实现 http3 quic 服务端客户端，体验 quic 协议低延迟特性。
 | 原文链接：http://book.9ysco2.asia/blog/118208.Doc

原标题：零基础理解模块化与组件化基础思想
简介：文件批量导入导出功能实现，开发批量导入导出接口，处理大量文件数据，完成业务数据批量迁移与导出。
 | 原文链接：http://book.9ysco2.asia/blog/941588.Doc

原标题：日志敏感信息脱敏泄露防护
简介：服务健康检查告警监控体系，搭建健康检查加告警体系，服务异常及时推送告警通知运维人员。
 | 原文链接：http://book.9ysco2.asia/blog/023451.Doc

原标题：git cherry‑pick 规范操作防 bug
简介：golang fasthttp 客户端连接池调优，fasthttp 客户端连接池配置，复用连接提升请求性能。
 | 原文链接：http://book.9ysco2.asia/blog/647300.Doc

原标题：Hands‑on：本地模拟分布式锁失效场景测试
简介：nodejs 全局异常捕获进程防护，捕获未捕获异常与 Promise 拒绝，尽量保护进程不因为异常直接退出。
 | 原文链接：http://book.9ysco2.asia/blog/088104.Doc

原标题：TCP 长连接参数优化 TIME_WAIT
简介：静态网页 HTML CSS 快速入门实战，通过简单页面案例讲解标签、样式布局，从零编写页面，理解网页基础渲染原理。
 | 原文链接：http://book.9ysco2.asia/blog/241766.Doc

原标题：部署复盘：容器OOM问题完整排查流程
简介：分布式 ID 全局唯一生成方案，讲解分布式 ID 生成思路，实现全局唯一 ID，满足分布式系统主键生成需求。
 | 原文链接：http://book.9ysco2.asia/blog/995559.Doc

原标题：Security：业务操作审计日志安全留存
简介：golang testify testify 断言库使用，testify assert require 断言，简化单元测试断言代码。
 | 原文链接：http://book.9ysco2.asia/blog/881092.Doc

原标题：零基础理解数据库事务基础ACID概念
简介：golang systemd 配置 go 服务部署，编写 systemd unit 文件管理 go 服务，开机自启、崩溃自动重启。
 | 原文链接：http://book.9ysco2.asia/blog/482968.Doc

原标题：golang channel 通道并发处理
简介：golang json 解析未知动态 json 结构，解析到 map [string] any 处理未知 json，动态读取字段。
 | 原文链接：http://book.9ysco2.asia/blog/200588.Doc

原标题：线上异常：线程池队列拒绝策略配置错误丢任务
简介：golang 消息队列中间件选型对比，kafka redis‑stream rabbitmq，对比吞吐量可靠性选型参考。
 | 原文链接：http://book.9ysco2.asia/blog/375140.Doc

原标题：新手避坑：第一次提交GitHub项目完整流程
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://book.9ysco2.asia/blog/128070.Doc

三、实战开发｜Practice
原标题：nodejs 中间件模式原理剖析
简介：golang gorm select 指定查询字段，指定查询字段，避免查询全部字段，减少数据传输，提升查询性能。
 | 原文链接：http://book.9ysco2.asia/blog/935671.Doc

原标题：golang 系统设计网关 ssl 证书配置更新实操
简介：轻量 API 后端接口服务快速开发，快速搭建简易 API 服务，实现基础接口能力，快速支撑小型业务需求。
 | 原文链接：http://book.9ysco2.asia/blog/236953.Doc

原标题：golang 系统设计数据库索引设计方法论
简介：静态资源 404 路径打包修复，修复打包后静态资源访问 404，调整资源输出路径，保证资源正常加载。
 | 原文链接：http://book.9ysco2.asia/blog/901339.Doc

原标题：golang es 分词器选型业务适配
简介：golang testify testify 断言库使用，testify assert require 断言，简化单元测试断言代码。
 | 原文链接：http://book.9ysco2.asia/blog/036328.Doc

原标题：TCP 心跳检测清理僵死连接
简介：golang 分布式事务 seata go 客户端，seata‑go 实现分布式事务，保证跨库业务数据最终一致性。
 | 原文链接：http://book.9ysco2.asia/blog/710100.Doc

原标题：golang 系统设计熔断降级架构讲解
简介：golang go sum 校验失败处理方案，go sum 校验不匹配，排查网络代理，清理缓存解决校验报错。
 | 原文链接：http://book.9ysco2.asia/blog/919865.Doc

原标题：golang 系统设计大事务拆分实战思路
简介：golang 消息队列实现事务消息方案，基于 kafka 实现事务消息，业务执行成功才对外投递消息。
 | 原文链接：http://book.9ysco2.asia/blog/088020.Doc

原标题：golang k8s 日志收集 efk 简单架构
简介：正则表达式文本处理实战案例，结合业务场景演示正则匹配、提取、替换，处理手机号、邮箱等各类文本校验需求。
 | 原文链接：http://book.9ysco2.asia/blog/908746.Doc

原标题：golang es 映射 mapping 设计避坑
简介：缓存基础原理与简单代码实现，讲解缓存设计思路，编写简易缓存逻辑，减少重复计算与重复请求，提升程序响应速度。
 | 原文链接：http://book.9ysco2.asia/blog/523020.Doc

原标题：设计思考：防雪崩，系统过载保护架构设计
简介：golang systemd 信号与优雅退出配合，systemd 停止服务发送 SIGTERM，go 程序捕获信号优雅关闭。
 | 原文链接：http://book.9ysco2.asia/blog/074224.Doc

原标题：后端登录鉴权模块完整开发
简介：golang os.Signal 信号监听完整示例，signal.Notify 监听信号，缓冲 channel 防止信号丢失。
 | 原文链接：http://book.9ysco2.asia/blog/897921.Doc

原标题：实战项目：CLI批量文件处理工具开发全过程
简介：golang systemd 信号与优雅退出配合，systemd 停止服务发送 SIGTERM，go 程序捕获信号优雅关闭。
 | 原文链接：http://book.9ysco2.asia/blog/856339.Doc

原标题：golang excel 简单读写操作示例
简介：JSON XML 数据解析处理示例，演示两种格式数据解析与序列化，增加异常捕获，处理格式错乱导致解析失败。
 | 原文链接：http://book.9ysco2.asia/blog/641006.Doc

原标题：Practice：手写简易限流组件，计数器、令牌桶实现
简介：golang go 包循环导入报错解决，A 导入 B B 导入 A，循环导入报错，重构代码拆分包消除循环依赖。
 | 原文链接：http://book.9ysco2.asia/blog/051975.Doc

原标题：Hands‑on：编写自定义Git钩子实现代码提交校验
简介：Git 分支管理多人协作实战教程，详解分支创建、合并、冲突处理，适配团队开发场景，规范多人协同代码工作流。
 | 原文链接：http://book.9ysco2.asia/blog/064659.Doc

原标题：golang 系统设计接口向前兼容改造实操
简介：golang http MaxHeaderBytes 限制请求头，设置 http 最大请求头大小，防止超大 header 攻击。
 | 原文链接：http://book.9ysco2.asia/blog/013492.Doc

原标题：新手指南：本地多版本环境共存配置
简介：服务健康检查告警监控体系，搭建健康检查加告警体系，服务异常及时推送告警通知运维人员。
 | 原文链接：http://book.9ysco2.asia/blog/718347.Doc

原标题：Hands‑on：简易的事件订阅发布组件开发实践
简介：时间同步修复令牌提前过期，服务器时间不同步导致 JWT 令牌提前过期，同步系统时间解决异常。
 | 原文链接：http://book.9ysco2.asia/blog/747699.Doc

原标题：golang 系统设计大盘看板设计最佳实践汇总
简介：正则表达式文本处理实战案例，结合业务场景演示正则匹配、提取、替换，处理手机号、邮箱等各类文本校验需求。
 | 原文链接：http://book.9ysco2.asia/blog/642114.Doc

原标题：数值 key 浮点匹配异常规避
简介：golang pdf 生成 go 服务端生成 pdf，服务端动态生成 pdf 报表文件，直接输出下载给到前端。
 | 原文链接：http://book.9ysco2.asia/blog/507485.Doc

原标题：golang 系统设计性能瓶颈定位完整方法论
简介：极简 API 网关路由转发实现，开发极简网关服务，完成请求路由转发，理解网关基础实现原理。
 | 原文链接：http://book.9ysco2.asia/blog/615779.Doc

原标题：Architecture：API设计RESTful最佳实践与反模式
简介：golang 后端节点健康检查机制实现，定时探测后端节点状态，自动剔除故障节点，保障转发可用。
 | 原文链接：http://book.9ysco2.asia/blog/059579.Doc

原标题：golang kafka offset 提交策略
简介：golang sync.Mutex 互斥锁正确模式，互斥锁 defer Unlock，锁粒度控制，避免锁范围过大。
 | 原文链接：http://book.9ysco2.asia/blog/801961.Doc

原标题：golang 协程 panic 捕获防止崩溃
简介：golang lru 缓存淘汰算法编写，手写 LRU 缓存淘汰算法，实现本地缓存，淘汰最久未使用数据。
 | 原文链接：http://book.9ysco2.asia/blog/375037.Doc

原标题：golang 系统设计代码安全审计简单思路
简介：golang loki 日志收集 go 服务集成，日志输出适配 loki，标签携带 traceId，日志集中检索排查问题。
 | 原文链接：http://book.9ysco2.asia/blog/137552.Doc

原标题：CI 持续集成自动构建流程
简介：Fork 开源项目同步上游代码，Fork 开源仓库之后，配置上游源，同步官方最新代码，保持代码版本对齐。
 | 原文链接：http://book.9ysco2.asia/blog/266549.Doc

原标题：golang 内存缓存简单实现方案
简介：golang go 程序运行时动态修改配置，运行时热加载配置结构体，原子更新保证并发读取安全。
 | 原文链接：http://book.9ysco2.asia/blog/121379.Doc

原标题：安全笔记：CORS跨域配置错误安全风险
简介：golang go test 单元测试命令参数详解，gotest 参数覆盖率，指定测试用例，跳过测试，单元测试命令实操。
 | 原文链接：http://book.9ysco2.asia/blog/103202.Doc

原标题：golang redis 缓存更新策略讲解
简介：golang goroutine 泄露常见场景汇总，channel 阻塞、context 忘记取消，导致协程无法退出发生泄露。
 | 原文链接：http://book.9ysco2.asia/blog/636582.Doc

原标题：golang redis lua 脚本开发调试
简介：Redis 热点 key 拆分降低集群压力，拆分访问量极高的热点 Key，分散请求压力，避免 Redis 节点压力过高。
 | 原文链接：http://book.9ysco2.asia/blog/509124.Doc

原标题：消息队列消费堆积扩容处理
简介：golang kafka 消费者组重平衡避坑，规避消费者组频繁 rebalance，减少消费抖动，保障消息消费稳定性。
 | 原文链接：http://book.9ysco2.asia/blog/440668.Doc

原标题：golang 系统设计缓存更新策略 cache aside 讲解
简介：nodejs 多进程任务分发处理，多进程拆分处理 CPU 密集任务，主进程分发任务，利用多核提升处理速度。
 | 原文链接：http://book.9ysco2.asia/blog/145521.Doc

原标题：SSH 密钥配置 GitHub 免密登录
简介：golang go math 大数高精度计算，math/big 处理超大整数、高精度浮点数，金额大数运算。
 | 原文链接：http://book.9ysco2.asia/blog/507601.Doc

原标题：排错：多实例部署session共享失效登录失效
简介：nodejs 集群模式多核利用实现，使用 cluster 集群模式，充分利用服务器多核 CPU，提升服务处理能力。
 | 原文链接：http://book.9ysco2.asia/blog/903012.Doc

原标题：golang 系统设计数据库查询优化完整流程
简介：浏览器内存泄漏排查前端页面，梳理前端页面内存泄漏场景，讲解排查手段，修复页面内存持续上涨。
 | 原文链接：http://book.9ysco2.asia/blog/600997.Doc

原标题：全量回归测试提升代码质量
简介：golang go cover 覆盖率报告生成，go test‑cover 生成测试覆盖率，html 可视化查看未覆盖代码行。
 | 原文链接：http://book.9ysco2.asia/blog/619551.Doc

原标题：前端打包产物体积压缩优化
简介：DNS TTL 配置域名切换生效，调整 DNS 解析 TTL，缩短缓存时间，域名变更后可以快速全网生效。
 | 原文链接：http://book.9ysco2.asia/blog/838442.Doc

原标题：golang redis 计数器防超卖示例
简介：golang 静态编译缩小镜像体积，Go 程序静态编译，不依赖系统库，产出单二进制文件，缩小镜像。
 | 原文链接：http://book.9ysco2.asia/blog/085849.Doc

原标题：golang 系统设计故障定位排查通用步骤方法论
简介：灰度发布策略服务平滑升级，实现灰度发布逻辑，流量逐步切到新版本，出现问题快速回滚旧版本。
 | 原文链接：http://book.9ysco2.asia/blog/427664.Doc

原标题：golang prometheus counter gauge 使用
简介：golang go cover 覆盖率报告生成，go test‑cover 生成测试覆盖率，html 可视化查看未覆盖代码行。
 | 原文链接：http://book.9ysco2.asia/blog/592886.Doc

四、架构设计｜Architecture
原标题：调优方案：CDN优化静态资源访问延迟
简介：golang 半关闭 tcp 连接 shutdown，tcp 连接 shutdown 半关闭，单向关闭读或者写，理解 tcp 关闭流程。
 | 原文链接：http://book.9ysco2.asia/blog/915076.Doc

原标题：golang 系统设计字段命名类型选择最佳实践
简介：golang 表格驱动测试完整示例，表格驱动多组输入输出，批量执行测试用例，减少重复代码。
 | 原文链接：http://book.9ysco2.asia/blog/457694.Doc

原标题：MySQL 慢查询索引优化实战
简介：golang testify testify 断言库使用，testify assert require 断言，简化单元测试断言代码。
 | 原文链接：http://book.9ysco2.asia/blog/443872.Doc

原标题：react 状态管理方案选型对比
简介：从零编写简易 CLI 命令行工具，通过实战案例实现基础命令交互，理解命令行程序执行逻辑，产出可运行小工具。
 | 原文链接：http://book.9ysco2.asia/blog/203961.Doc

原标题：Shell 脚本自动化命令编写
简介：golang 灰度发布流量权重路由实现，根据权重切分流量，部分流量访问新版本服务，实现灰度发布。
 | 原文链接：http://book.9ysco2.asia/blog/458624.Doc

原标题：架构笔记：分布式系统常见一致性模型梳理
简介：golang makefile 多平台编译脚本，makefile 一键交叉编译多平台二进制，打包镜像，执行测试。
 | 原文链接：http://book.9ysco2.asia/blog/011649.Doc

原标题：golang github actions 发布 release 包
简介：golang fasthttp 服务开发完整示例，fasthttp 搭建 http 服务，路由、参数读取、响应返回完整业务。
 | 原文链接：http://book.9ysco2.asia/blog/567038.Doc

原标题：TLS 版本兼容 HTTPS 握手失败
简介：依赖版本冲突兼容修复方案，定位依赖版本冲突根源，通过版本约束、替换包，解决版本不兼容运行报错。
 | 原文链接：http://book.9ysco2.asia/blog/807225.Doc

原标题：golang 链路追踪简易实现方案
简介：golang 项目 makefile 脚本编写，编写 Makefile 脚本，封装编译、测试、构建命令，简化项目操作。
 | 原文链接：http://book.9ysco2.asia/blog/273981.Doc

原标题：运维笔记：服务器磁盘内存监控告警配置
简介：业务接口幂等完整落地案例，完整业务场景幂等落地示例，覆盖表单提交、回调、重试各类场景。
 | 原文链接：http://book.9ysco2.asia/blog/273116.Doc

原标题：JSON XML 数据解析处理示例
简介：golang http 服务并发连接数限制，自定义 listener 统计连接数量，限制最大并发连接数保护服务。
 | 原文链接：http://book.9ysco2.asia/blog/164469.Doc

原标题：golang 系统设计 io 瓶颈磁盘网络优化实践
简介：nodejs redis 缓存业务实战，Node 对接 Redis 实现业务缓存，缓存热点查询结果，减轻数据库压力。
 | 原文链接：http://book.9ysco2.asia/blog/387925.Doc

原标题：golang gin 框架接口开发实战
简介：golang context.WithCancel 手动取消上下文，WithCancel 生成可取消 ctx，手动调用 cancel 触发取消。
 | 原文链接：http://book.9ysco2.asia/blog/292075.Doc

原标题：项目脚手架模板生成工具
简介：golang 子进程超时杀死防止挂住，context 控制子进程超时，超时强制杀掉子进程，避免子进程僵尸。
 | 原文链接：http://book.9ysco2.asia/blog/465076.Doc

原标题：实战项目：前端资源打包体积优化完整实操
简介：游标分页大数据查询性能提升，使用游标分页替代偏移分页，解决大数据 offset 分页性能越来越差问题。
 | 原文链接：http://book.9ysco2.asia/blog/848064.Doc

原标题：golang 系统设计配置本地缓存降级策略方案
简介：golang gorm 批量插入性能调优，GORM 批量插入优化，调整批次大小，提升大量数据插入数据库速度。
 | 原文链接：http://book.9ysco2.asia/blog/593257.Doc

原标题：Shell 脚本自动化命令编写
简介：golang mysql 事务回滚异常处理，Go MySQL 事务异常捕获，正确回滚事务，保证异常场景数据回滚。
 | 原文链接：http://book.9ysco2.asia/blog/669810.Doc

原标题：调优方案：CDN优化静态资源访问延迟
简介：数值类型溢出错乱问题修复，选择合适数值存储类型，处理数值溢出，避免数据存储错乱结果异常。
 | 原文链接：http://book.9ysco2.asia/blog/393027.Doc

?
