最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Hands‑on：简易短链接服务完整开发实践
简介：golang 定时任务任务持久化存储，定时任务持久化到数据库，服务重启任务不丢失，动态管理任务。
 | 原文链接：http://wiki.mljc3b.asia/arts/566514.Doc

原标题：golang 系统设计会话共享多实例部署
简介：golang 反向代理 http 服务开发，手写简易 http 反向代理，转发请求，修改请求头响应头。
 | 原文链接：http://wiki.mljc3b.asia/arts/596947.Doc

原标题：golang 系统设计 mq 消息丢失完整防护
简介：golang 大内存分配 GC 抖动规避，避免瞬时大量对象创建，分批处理，防止 GC 抖动业务抖动。
 | 原文链接：http://wiki.mljc3b.asia/arts/602210.Doc

原标题：DevOps：容器网络模式选型与坑点总结
简介：golang redis zset 实现延时任务队列，zset 存储任务到期时间，轮询到期任务执行，简易延迟队列。
 | 原文链接：http://wiki.mljc3b.asia/arts/721981.Doc

原标题：golang 系统设计数据库死锁分析规避
简介：golang rabbitmq 死信队列延迟消息，rabbitmq 实现死信、延迟消息，处理延时业务场景。
 | 原文链接：http://wiki.mljc3b.asia/arts/017210.Doc

原标题：Security：RPC调用身份认证安全加固
简介：golang 限流熔断放在代理层实践，代理层统一限流熔断，对后端服务做流量保护。
 | 原文链接：http://wiki.mljc3b.asia/arts/793492.Doc

原标题：全局异常处理器接口返回统一
简介：golang go‑zero rpc 微服务开发，go‑zero 定义 proto，生成 rpc 服务代码，实现微服务调用。
 | 原文链接：http://wiki.mljc3b.asia/arts/263033.Doc

原标题：踩坑记录：端口被占用导致服务启动失败
简介：死信队列处理消息阻塞业务，配置死信队列，处理消费失败消息，避免失败消息阻塞整个队列业务。
 | 原文链接：http://wiki.mljc3b.asia/arts/666741.Doc

原标题：开发复盘：统一错误码体系设计落地实践
简介：golang errors.Is errors.As 错误判断，判断是否为指定错误类型，提取自定义错误信息，错误处理进阶。
 | 原文链接：http://wiki.mljc3b.asia/arts/174479.Doc

原标题：golang k8s cronjob 定时任务配置
简介：golang go 服务日志输出 journald，systemd journald 接收程序 stdout 日志，统一管理服务日志。
 | 原文链接：http://wiki.mljc3b.asia/arts/240581.Doc

原标题：入门实践：简单重试逻辑封装实现
简介：golang 配置文件多环境加载，Go 多环境配置加载实现，读取配置文件环境变量，适配多套运行环境。
 | 原文链接：http://wiki.mljc3b.asia/arts/748512.Doc

原标题：坑点：gitcherry‑pick引入不兼容代码
简介：超大数据集分页性能优化方案，对比不同分页方案，针对海量数据集做分页性能优化，解决越翻越慢。
 | 原文链接：http://wiki.mljc3b.asia/arts/503418.Doc

原标题：Issue：定时任务并发执行未加锁重复执行业务
简介：golang redis pipeline 与 txpipeline 区别，区分普通管道与事务管道，根据业务场景选择合适批量执行方案。
 | 原文链接：http://wiki.mljc3b.asia/arts/758532.Doc

原标题：golang http 请求重试封装工具
简介：golang 配置文件多格式兼容加载，同时支持 yaml toml json 多种格式配置文件，灵活适配不同部署环境。
 | 原文链接：http://wiki.mljc3b.asia/arts/883655.Doc

原标题：复盘总结：微服务改造踩坑经验总结记录
简介：端口占用释放资源重启服务，查找占用端口进程，结束占用进程，释放端口，让服务能够正常启动监听。
 | 原文链接：http://wiki.mljc3b.asia/arts/191326.Doc

原标题：多套环境灵活切换配置方案
简介：nestjs 拦截器过滤器管道实战，实操 Nest 拦截器、异常过滤器、管道校验，处理请求与响应统一逻辑。
 | 原文链接：http://wiki.mljc3b.asia/arts/078957.Doc

原标题：实战项目：Nginx限速、限流、防爬虫配置实践
简介：包管理器依赖冲突解决方案，分析依赖冲突产生根源，提供版本调整、锁定依赖等手段，解决项目依赖报错问题。
 | 原文链接：http://wiki.mljc3b.asia/arts/674080.Doc

原标题：Performance：避免循环查询N+1问题完整优化
简介：golang wasm 性能优化与内存管理，wasm 内存分配释放，减少内存拷贝，优化浏览器端性能。
 | 原文链接：http://wiki.mljc3b.asia/arts/255929.Doc

原标题：Docker 容器入门镜像实操教程
简介：golang 分库分表简单路由实现，简易分表路由逻辑实现，根据分片 key 计算分片位置，数据路由写入。
 | 原文链接：http://wiki.mljc3b.asia/arts/851819.Doc

原标题：快速入门WebSocket，实现简易双向通信demo
简介：分布式 ID 全局唯一生成方案，讲解分布式 ID 生成思路，实现全局唯一 ID，满足分布式系统主键生成需求。
 | 原文链接：http://wiki.mljc3b.asia/arts/208625.Doc

原标题：nodejs 数据库连接池配置调优
简介：golang go 依赖漏洞检测 govulncheck，govulncheck 扫描依赖安全漏洞，发现项目供应链风险。
 | 原文链接：http://wiki.mljc3b.asia/arts/237466.Doc

原标题：方案设计：高可用Redis集群架构选型对比
简介：golang go 包循环导入报错解决，A 导入 B B 导入 A，循环导入报错，重构代码拆分包消除循环依赖。
 | 原文链接：http://wiki.mljc3b.asia/arts/603497.Doc

原标题：golang 内存缓存简单实现方案
简介：golang go 版本管理 go install 安装工具，go install 安装指定版本 go 工具，管理本地 go 工具版本。
 | 原文链接：http://wiki.mljc3b.asia/arts/166028.Doc

原标题：架构思考：单体应用向微服务拆分演进路径
简介：开发测试生产多环境配置区分，讲解三套环境配置分离思路，配置文件隔离，防止开发配置泄露到生产环境。
 | 原文链接：http://wiki.mljc3b.asia/arts/839265.Doc

原标题：部署复盘：配置热更新不用重启服务方案
简介：MySQL 慢查询索引优化实战，抓取慢查询 SQL，分析执行计划，新增或者调整索引，提升 SQL 执行速度。
 | 原文链接：http://wiki.mljc3b.asia/arts/888543.Doc

原标题：Architecture：API网关核心能力与组件拆分
简介：开源源码阅读拆解学习思路，分享阅读大型开源项目方法，从入口文件逐层拆解模块，降低源码学习门槛。
 | 原文链接：http://wiki.mljc3b.asia/arts/976472.Doc

原标题：golang redis lua 脚本原子操作
简介：分布式 ID 生成器高并发实现，实现高性能分布式 ID 生成器，适配高并发业务，生成全局唯一 ID。
 | 原文链接：http://wiki.mljc3b.asia/arts/084243.Doc

原标题：内网 DNS 不稳定随机报错排查
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://wiki.mljc3b.asia/arts/850834.Doc

原标题：golang redis bitmap 位图统计实现
简介：hosts 配置本地回环访问修复，修改 hosts 配置，修复 127.0.0.1 解析异常，本地服务访问失败问题。
 | 原文链接：http://wiki.mljc3b.asia/arts/644817.Doc

原标题：内存泄漏定位分析完整流程
简介：golang go 服务日志输出 journald，systemd journald 接收程序 stdout 日志，统一管理服务日志。
 | 原文链接：http://wiki.mljc3b.asia/arts/617620.Doc

原标题：HTTP 状态码请求头完整梳理
简介：golang go 泛型实现通用数据结构，泛型实现通用栈队列，复用逻辑支持多种数据类型。
 | 原文链接：http://wiki.mljc3b.asia/arts/718706.Doc

原标题：消息队列重复消费业务处理
简介：golang 接口返回统一封装工具，封装 Go 接口统一返回工具，标准化成功失败返回结构体。
 | 原文链接：http://wiki.mljc3b.asia/arts/743283.Doc

原标题：设计思考：缓存分层架构设计与失效处理策略
简介：golang 分布式 ID 雪花算法实现，Go 实现雪花算法，生成分布式全局唯一 ID，适配分库分表主键。
 | 原文链接：http://wiki.mljc3b.asia/arts/636067.Doc

原标题：从零搭建简单的健康检查接口示例
简介：分布式任务调度集群原型开发，开发简易分布式调度原型，集群多节点运行，保证任务只执行一次。
 | 原文链接：http://wiki.mljc3b.asia/arts/195320.Doc

原标题：golang 单元测试 mock http 请求
简介：golang os.Exit 退出程序注意 defer 不执行，os.Exit 会直接退出，不会执行 defer，优雅退出不要直接 os.Exit。
 | 原文链接：http://wiki.mljc3b.asia/arts/983042.Doc

原标题：vite 项目配置与构建提速技巧
简介：跨平台换行符统一异常修复，统一代码文件换行符，解决不同操作系统换行符不一致带来脚本执行异常。
 | 原文链接：http://wiki.mljc3b.asia/arts/688677.Doc

原标题：API 接口调试与异常处理实战
简介：异步任务堆积消费能力优化，处理消息任务堆积问题，提升消费处理速度，恢复队列正常处理水位。
 | 原文链接：http://wiki.mljc3b.asia/arts/533628.Doc

原标题：新手指南：本地防火墙端口访问失败排查
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://wiki.mljc3b.asia/arts/934544.Doc

原标题：全局本地依赖隔离冲突规避
简介：前端打包分包加载提速方案，前端打包做代码分包，拆分大 bundle，页面按需加载，提升首屏加载速度。
 | 原文链接：http://wiki.mljc3b.asia/arts/084585.Doc

原标题：架构复盘：消息队列在业务系统中边界与最佳实践
简介：DNS 解析异常第三方调用故障，排查 DNS 解析故障，修复域名解析，恢复第三方接口网络调用。
 | 原文链接：http://wiki.mljc3b.asia/arts/558351.Doc


二、踩坑排错｜Troubleshooting
原标题：Cookie 跨环境登录配置调整
简介：golang 读写分离 gorm 实现主从切换，gorm 配置主库写入从库查询，读写分离分担数据库查询压力。
 | 原文链接：http://wiki.mljc3b.asia/arts/011946.Doc

原标题：缓存过期策略优化防业务故障
简介：golang go 爬虫请求速率控制，爬虫限频、代理轮换，设置 UA，防止爬虫被目标站点封禁 IP。
 | 原文链接：http://wiki.mljc3b.asia/arts/422625.Doc

原标题：golang 表单文件大小限制配置
简介：golang nats jetstream 持久消息队列，nats jetstream 持久化消息，保证消息不丢失，实现可靠消费。
 | 原文链接：http://wiki.mljc3b.asia/arts/527940.Doc

原标题：golang 系统设计开源项目贡献指南 contributing
简介：Shell 运维脚本服务器效率提升，编写常用运维 Shell 脚本，自动化服务器运维操作，减少手工重复工作。
 | 原文链接：http://wiki.mljc3b.asia/arts/058245.Doc

原标题：golang 系统设计结构化日志字段规范约定
简介：数据库分表路由写入分片修正，修复分表路由逻辑，保证数据写入正确分片，不会出现数据丢失错乱。
 | 原文链接：http://wiki.mljc3b.asia/arts/443214.Doc

原标题：实践：多配置文件合并加载组件实现
简介：配置与镜像分离防止信息泄露，业务配置不打包进镜像，外部挂载配置，避免密钥配置随镜像泄露。
 | 原文链接：http://wiki.mljc3b.asia/arts/297877.Doc

原标题：OOMKilled 容器被杀完整排查
简介：golang kitex 超时重试熔断配置，kitex 配置调用超时、重试、熔断策略，保障微服务调用稳定性。
 | 原文链接：http://wiki.mljc3b.asia/arts/121507.Doc

原标题：记一次分库分表路由计算错误数据写入错误分片
简介：golang 制品镜像版本号规范管理，镜像版本号结合 git commit，明确每个镜像对应代码版本便于追溯。
 | 原文链接：http://wiki.mljc3b.asia/arts/656743.Doc

原标题：golang 系统设计用户签到统计方案
简介：死信队列处理消息阻塞业务，配置死信队列，处理消费失败消息，避免失败消息阻塞整个队列业务。
 | 原文链接：http://wiki.mljc3b.asia/arts/075760.Doc

原标题：项目实践：本地模拟缓存失效风暴验证防护
简介：golang 接口返回统一封装工具，封装 Go 接口统一返回工具，标准化成功失败返回结构体。
 | 原文链接：http://wiki.mljc3b.asia/arts/445655.Doc

原标题：后端大文件分片上传接口开发
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://wiki.mljc3b.asia/arts/728069.Doc

原标题：golang 系统设计主键 id 选型雪花自增对比
简介：golang sync.Cond 条件变量使用，Cond 条件变量协程等待唤醒，复杂并发同步场景。
 | 原文链接：http://wiki.mljc3b.asia/arts/584122.Doc

原标题：golang 系统设计混沌测试故障注入简单示例
简介：golang socket 文件描述符继承重启，父进程传递 listener fd 给子进程，实现 go 程序零停机热重启。
 | 原文链接：http://wiki.mljc3b.asia/arts/232833.Doc

原标题：golang 系统设计令牌桶漏桶算法对比
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://wiki.mljc3b.asia/arts/863892.Doc

原标题：Issue：开源项目升级大版本后API不兼容踩坑
简介：golang channel 通道并发处理，讲解 Channel 用法，协程之间通过通道传递数据，做并发同步控制。
 | 原文链接：http://wiki.mljc3b.asia/arts/822450.Doc

原标题：性能笔记：布隆过滤器减少无效数据库查询
简介：跨库查询性能优化处理，减少跨库关联查询，做数据冗余或者中间表，规避跨库查询性能低下。
 | 原文链接：http://wiki.mljc3b.asia/arts/718866.Doc

原标题：webpack chunk 分包策略详解
简介：Mock 接口服务快速搭建实操，搭建模拟后端接口，自定义返回数据、延迟响应，前端开发阶段无需依赖真实后端服务。
 | 原文链接：http://wiki.mljc3b.asia/arts/860493.Doc

原标题：多实例部署 Session 共享方案
简介：golang go 爬虫 robots 协议遵守，解析 robots.txt 规则，控制爬虫抓取范围，合规采集网页数据。
 | 原文链接：http://wiki.mljc3b.asia/arts/515614.Doc

原标题：线上异常：接口偶发超时，完整定位过程记录
简介：前端静态缓存更新生效处理，修改静态资源版本标识，处理浏览器强缓存，让更新资源生效。
 | 原文链接：http://wiki.mljc3b.asia/arts/233355.Doc

原标题：golang mongodb 事务多文档使用
简介：文件批量导入导出功能实现，开发批量导入导出接口，处理大量文件数据，完成业务数据批量迁移与导出。
 | 原文链接：http://wiki.mljc3b.asia/arts/330173.Doc

原标题：坑点：依赖包内部携带恶意代码供应链风险
简介：golang 漏桶算法实现接口限流，漏桶算法控制请求流出速率，平滑突发流量，削平流量峰值。
 | 原文链接：http://wiki.mljc3b.asia/arts/631696.Doc

原标题：前端打包分包加载提速方案
简介：golang go 接口定义原则小接口，go 小接口设计原则，接口尽量小，只定义必要方法，提升代码灵活性。
 | 原文链接：http://wiki.mljc3b.asia/arts/433025.Doc

原标题：ICMP 放通网络丢包问题修复
简介：golang hertz 反向代理与负载均衡，hertz 实现反向代理，内置负载均衡，快速搭建网关类服务。
 | 原文链接：http://wiki.mljc3b.asia/arts/184407.Doc

原标题：接口签名验签完整安全方案
简介：golang httptest 模拟 http 请求单元测试，httptest 模拟 http 请求，测试 http handler 逻辑不用启动服务。
 | 原文链接：http://wiki.mljc3b.asia/arts/670011.Doc

原标题：golang 项目 docker compose 本地调试
简介：批量异步处理系统业务落地，构建批量异步处理系统，把耗时业务异步化，提升接口响应速度。
 | 原文链接：http://wiki.mljc3b.asia/arts/280475.Doc

原标题：新手教程：如何给开源项目提交第一个PR
简介：新手参与开源社区贡献指南，介绍开源社区基础规则，讲解阅读 issue、提交 PR 流程，指导开发者参与开源贡献。
 | 原文链接：http://wiki.mljc3b.asia/arts/854670.Doc

原标题：前端权限路由动态生成实现
简介：golang go 锁竞争导致 CPU 飙升，识别锁竞争场景，减少锁粒度，优化并发逻辑降低 CPU 开销。
 | 原文链接：http://wiki.mljc3b.asia/arts/014466.Doc

原标题：OOMKilled 容器被杀完整排查
简介：golang gorm group by 分组统计，GORM 分组聚合统计，实现 count sum 等统计查询，快速完成统计业务。
 | 原文链接：http://wiki.mljc3b.asia/arts/411190.Doc

原标题：项目实践：本地模拟多节点分布式系统实践
简介：TLS 版本兼容 HTTPS 握手失败，兼容老旧 TLS 协议版本，修复部分客户端 HTTPS 握手失败无法访问。
 | 原文链接：http://wiki.mljc3b.asia/arts/781100.Doc

原标题：Performance：数据库分表解决单表过大性能衰减
简介：golang net.Conn 包装自定义连接，包装 net.Conn，统计读写字节，日志打印，超时控制。
 | 原文链接：http://wiki.mljc3b.asia/arts/047763.Doc

原标题：配置外部化线上部署防错误
简介：前端 pdf 预览渲染方案对比，对比前端 PDF 预览库，分析性能、兼容性，给出业务选型参考。
 | 原文链接：http://wiki.mljc3b.asia/arts/940740.Doc

原标题：前端下载导出文件功能实现
简介：Nginx 反向代理路由配置实战，配置 Nginx 反向代理，实现请求转发、路由分发，掌握 Nginx 基础配置能力。
 | 原文链接：http://wiki.mljc3b.asia/arts/564470.Doc

原标题：踩坑记录：乐观锁版本号处理不当更新失败
简介：浏览器本地存储安全使用技巧，讲解 localStorage、sessionStorage 使用边界，规避 XSS 泄露存储数据。
 | 原文链接：http://wiki.mljc3b.asia/arts/546723.Doc

原标题：golang 系统设计雪花算法 id 原理剖析
简介：golang socket 文件描述符继承重启，父进程传递 listener fd 给子进程，实现 go 程序零停机热重启。
 | 原文链接：http://wiki.mljc3b.asia/arts/933238.Doc

原标题：Security：密码存储哈希加盐最佳实践
简介：golang httptest 模拟 http 请求单元测试，httptest 模拟 http 请求，测试 http handler 逻辑不用启动服务。
 | 原文链接：http://wiki.mljc3b.asia/arts/238075.Doc

原标题：golang docker 部署 redis 配置要点
简介：golang select 随机分支执行特性，多个 channel 就绪 select 随机选择，理解 select 行为特性。
 | 原文链接：http://wiki.mljc3b.asia/arts/270980.Doc

原标题：安全笔记：文件下载接口路径校验安全
简介：nodejs 信号处理优雅关闭服务，监听系统信号，执行资源清理，实现 Node 服务优雅停机，拒绝粗暴杀死进程。
 | 原文链接：http://wiki.mljc3b.asia/arts/386568.Doc

原标题：golang 系统设计开源项目 release 发布流程
简介：golang time duration 解析时间字符串，time.ParseDuration 解析 1h30m 时间间隔字符串。
 | 原文链接：http://wiki.mljc3b.asia/arts/378093.Doc

原标题：依赖安装失败全方位排错
简介：文件监控服务自动重启开发，监控项目文件变更，代码修改自动重启服务，提升本地开发调试效率。
 | 原文链接：http://wiki.mljc3b.asia/arts/324419.Doc

原标题：开发复盘：避免大报文导致服务OOM优化实践
简介：nodejs 脚手架工具开发完整教程，从零开发 Node 命令行脚手架，实现项目模板生成，理解 CLI 开发。
 | 原文链接：http://wiki.mljc3b.asia/arts/671948.Doc

三、实战开发｜Practice
原标题：零基础理解模块化与组件化基础思想
简介：golang tcp 四次挥手 go 程序行为，理解 tcp 四次挥手，处理连接关闭、重置、RST 包异常场景。
 | 原文链接：http://wiki.mljc3b.asia/arts/567532.Doc

原标题：特殊输入字符过滤解析防护
简介：golang go proxy 私有代理配置，配置 go proxy 私有代理，加速依赖下载，内网环境构建项目。
 | 原文链接：http://wiki.mljc3b.asia/arts/859352.Doc

原标题：限流规则误拦截正常请求修复
简介：express 中间件开发业务实践，开发 Express 自定义中间件，拦截请求，实现鉴权、日志记录等通用逻辑。
 | 原文链接：http://wiki.mljc3b.asia/arts/334019.Doc

原标题：golang 系统设计架构图绘图工具选型对比
简介：golang trace 链路追踪 opentelemetry，opentelemetry 实现链路追踪，生成 traceId spanId，完整记录调用链路。
 | 原文链接：http://wiki.mljc3b.asia/arts/309465.Doc

原标题：项目实践：定时任务防重复执行落地实践
简介：接口请求重试容错机制实现，封装请求重试逻辑，遇到临时网络故障自动重试，提升第三方调用稳定性。
 | 原文链接：http://wiki.mljc3b.asia/arts/677717.Doc

原标题：golang 系统设计接口超时设计原则梳理
简介：WebSocket 双向通信 demo 开发，搭建简易 WebSocket 服务，实现客户端服务端双向消息推送，理解实时通信原理。
 | 原文链接：http://wiki.mljc3b.asia/arts/829548.Doc

原标题：排错：前端打包chunk过大浏览器加载缓慢
简介：golang 参数校验业务接口处理，Go 接口入参参数校验，拦截非法入参，减少业务层参数判断代码。
 | 原文链接：http://wiki.mljc3b.asia/arts/604843.Doc

原标题：架构复盘：服务优雅停机架构设计资源释放
简介：golang trace 工具采集 go 程序执行轨迹，go trace 采集程序完整调度轨迹，分析协程调度阻塞问题。
 | 原文链接：http://wiki.mljc3b.asia/arts/660777.Doc

原标题：Fork 开源项目同步上游代码
简介：golang go‑zero 监控指标埋点，go‑zero 内置 metrics 监控，上报业务指标对接监控平台。
 | 原文链接：http://wiki.mljc3b.asia/arts/820988.Doc

原标题：文件锁正确使用避免死锁
简介：上传接口跨域配置特殊适配，针对文件上传接口，适配复杂请求，修复上传场景下跨域失效问题。
 | 原文链接：http://wiki.mljc3b.asia/arts/852503.Doc

原标题：golang docker 部署 kafka 本地调试
简介：golang 时间戳秒毫秒纳秒转换，Unix UnixMilli UnixNano 互相转换，区分单位避免时间逻辑 bug。
 | 原文链接：http://wiki.mljc3b.asia/arts/931662.Doc

原标题：Security：Web常见安全漏洞原理与修复清单
简介：golang go 爬虫请求速率控制，爬虫限频、代理轮换，设置 UA，防止爬虫被目标站点封禁 IP。
 | 原文链接：http://wiki.mljc3b.asia/arts/560914.Doc

原标题：部署复盘：GitHubActions完整自动化配置
简介：golang excel 生成导出高性能方案，excelize 流式生成 excel，百万行数据导出，规避内存溢出。
 | 原文链接：http://wiki.mljc3b.asia/arts/537600.Doc

原标题：Hands‑on：简易邮件发送服务封装实践
简介：golang net/url 路径拼接处理，url.ParseRequestURI 处理请求 url，正确拼接 url 路径避免拼接错误。
 | 原文链接：http://wiki.mljc3b.asia/arts/607070.Doc

原标题：golang zap 日志按日期切割方案
简介：golang gorm group by 分组统计，GORM 分组聚合统计，实现 count sum 等统计查询，快速完成统计业务。
 | 原文链接：http://wiki.mljc3b.asia/arts/485474.Doc

原标题：开发记录：批量接口请求并发控制实践
简介：Git 代码冲突正确处理方式，讲解冲突产生场景，演示冲突文件修改，正确合并代码，防止代码丢失。
 | 原文链接：http://wiki.mljc3b.asia/arts/418713.Doc

原标题：开发测试生产多环境配置区分
简介：Fork 开源项目同步上游代码，Fork 开源仓库之后，配置上游源，同步官方最新代码，保持代码版本对齐。
 | 原文链接：http://wiki.mljc3b.asia/arts/234031.Doc

原标题：golang 系统设计依赖漏洞扫描修复流程
简介：数据库读写分离性能优化，讲解读写分离原理，主库写入从库查询，分担数据库查询压力，提升查询性能。
 | 原文链接：http://wiki.mljc3b.asia/arts/204286.Doc

原标题：安全实践：SQL注入产生场景与完整防御手段
简介：golang go 基准测试 benchmark 编写，Benchmark 性能基准测试，测量函数执行耗时内存分配情况。
 | 原文链接：http://wiki.mljc3b.asia/arts/942832.Doc

原标题：Hands‑on：手写简单消息队列理解存储模型
简介：golang gin 路由分组权限管控，Gin 路由分组，不同分组绑定鉴权中间件，实现接口权限分组管控。
 | 原文链接：http://wiki.mljc3b.asia/arts/678074.Doc

原标题：Troubleshooting：WSL文件权限问题大量踩坑
简介：golang sql 注入风险规避要点，参数化查询杜绝 sql 注入，禁止字符串拼接 SQL 语句执行。
 | 原文链接：http://wiki.mljc3b.asia/arts/593031.Doc

原标题：golang 系统设计配置多环境本地开发适配方案
简介：代码格式化工具团队统一风格，接入格式化工具，统一全团队代码书写风格，减少格式类 git 冲突。
 | 原文链接：http://wiki.mljc3b.asia/arts/404591.Doc

原标题：Practice：模拟热点key，验证缓存防护策略
简介：golang redis zset 实现延时任务队列，zset 存储任务到期时间，轮询到期任务执行，简易延迟队列。
 | 原文链接：http://wiki.mljc3b.asia/arts/152976.Doc

原标题：golang 系统设计监控大盘故障快速定位思路
简介：golang docker 多阶段构建 go 镜像，Go 项目 Docker 多阶段构建，编译与运行阶段分离，大幅度缩减最终镜像体积，提升镜像分发效率。
 | 原文链接：http://wiki.mljc3b.asia/arts/319611.Doc

原标题：RPC 报文大小上限调优大请求
简介：golang 表单文件大小限制配置，限制表单上传文件最大体积，拦截超大文件上传请求，保护服务。
 | 原文链接：http://wiki.mljc3b.asia/arts/315655.Doc

原标题：golang ci 流水线代码质量扫描集成
简介：golang 接口限流中间件开发，Gin 开发限流中间件，接口层实现访问频率限制，防护接口流量。
 | 原文链接：http://wiki.mljc3b.asia/arts/374771.Doc

原标题：Git LFS 大文件推送失败解决
简介：golang mysql 事务回滚异常处理，Go MySQL 事务异常捕获，正确回滚事务，保证异常场景数据回滚。
 | 原文链接：http://wiki.mljc3b.asia/arts/818737.Doc

原标题：golang 分布式上下文传递方案
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://wiki.mljc3b.asia/arts/342628.Doc

原标题：服务熔断防止故障级联传播
简介：golang go 防止路径穿越攻击，文件操作校验路径，拒绝../ 路径穿越，禁止访问系统任意文件。
 | 原文链接：http://wiki.mljc3b.asia/arts/997646.Doc

原标题：Hands‑on：简易压缩中间件gzip实现实践
简介：golang systemd 配置 go 服务部署，编写 systemd unit 文件管理 go 服务，开机自启、崩溃自动重启。
 | 原文链接：http://wiki.mljc3b.asia/arts/978333.Doc

原标题：内存泄漏定位分析完整流程
简介：golang 信号量 semaphore 并发限制，基于 semaphore 实现并发数量控制，保护数据库、第三方接口不被打满。
 | 原文链接：http://wiki.mljc3b.asia/arts/853366.Doc

原标题：golang 系统设计开源项目安全漏洞处理流程
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://wiki.mljc3b.asia/arts/618584.Doc

原标题：开发复盘：分库分表本地模拟与数据路由实践
简介：golang httptest 模拟 http 请求单元测试，httptest 模拟 http 请求，测试 http handler 逻辑不用启动服务。
 | 原文链接：http://wiki.mljc3b.asia/arts/202262.Doc

原标题：golang 系统设计读写分离架构示例
简介：golang 换行符统一处理，文本文件读写统一换行符，规避不同系统换行符带来解析异常。
 | 原文链接：http://wiki.mljc3b.asia/arts/153694.Doc

原标题：调优方案：消息队列消费速度优化处理堆积
简介：golang context.WithCancel 手动取消上下文，WithCancel 生成可取消 ctx，手动调用 cancel 触发取消。
 | 原文链接：http://wiki.mljc3b.asia/arts/702478.Doc

原标题：golang redis stream 消息队列实践
简介：接口签名校验防篡改实现，实现请求签名验签逻辑，校验请求参数未被篡改，提升接口调用安全性。
 | 原文链接：http://wiki.mljc3b.asia/arts/720374.Doc

原标题：golang github actions 发布 release 包
简介：golang strings.Builder 字符串高效拼接，strings.Builder 做字符串拼接，比 += 性能更高，减少内存拷贝。
 | 原文链接：http://wiki.mljc3b.asia/arts/190589.Doc

原标题：golang 日志脱敏敏感字段过滤
简介：全平台系统环境变量配置，汇总多操作系统环境变量配置方法，统一项目读取逻辑，适配不同运行平台。
 | 原文链接：http://wiki.mljc3b.asia/arts/754583.Doc

原标题：TLS 版本兼容 HTTPS 握手失败
简介：序列化版本不一致解析失败，保证序列化对象版本对齐，修复版本不匹配导致对象反序列化失败。
 | 原文链接：http://wiki.mljc3b.asia/arts/150901.Doc

原标题：系统文件描述符上限调大
简介：golang systemd 信号与优雅退出配合，systemd 停止服务发送 SIGTERM，go 程序捕获信号优雅关闭。
 | 原文链接：http://wiki.mljc3b.asia/arts/034103.Doc

四、架构设计｜Architecture
原标题：golang 系统设计基准测试 benchmark 编写
简介：golang 内存持续上涨定位思路，区分内存泄漏、缓存占用、GC 参数不合理，分步定位内存持续走高。
 | 原文链接：http://wiki.mljc3b.asia/arts/619328.Doc

原标题：golang 系统设计令牌桶漏桶算法对比
简介：golang 反向代理 http 服务开发，手写简易 http 反向代理，转发请求，修改请求头响应头。
 | 原文链接：http://wiki.mljc3b.asia/arts/277305.Doc

原标题：golang 令牌桶限流中间件 gin
简介：跨平台 uniapp 多端开发实操，uniapp 开发一套代码，编译多端，梳理多端差异处理与适配技巧。
 | 原文链接：http://wiki.mljc3b.asia/arts/941692.Doc

原标题：golang aes 对称加密解密示例
简介：golang grpc 服务端流推送数据，服务端流式响应，服务端持续向客户端推送多条响应消息。
 | 原文链接：http://wiki.mljc3b.asia/arts/033841.Doc

原标题：实战项目：编写Dockerfile多阶段构建减小镜像体积
简介：golang csv 读写批量数据处理，Go 读写 CSV 文件，批量导入导出业务数据，处理 CSV 格式解析。
 | 原文链接：http://wiki.mljc3b.asia/arts/622447.Doc

原标题：golang kafka 核心概念分区副本
简介：golang io.MultiReader MultiWriter 拼接流，多个 reader 拼接，多 writer 同时写入一份数据。
 | 原文链接：http://wiki.mljc3b.asia/arts/745951.Doc

原标题：Cookie 跨环境登录配置调整
简介：文件锁正确使用避免死锁，合理使用文件锁，控制多进程访问同一个文件，规避文件锁死锁现象。
 | 原文链接：http://wiki.mljc3b.asia/arts/266317.Doc

原标题：线程池拒绝策略任务丢失防护
简介：golang go mod exclude 排除依赖版本，exclude 排除有问题依赖版本，规避有 bug 的第三方包。
 | 原文链接：http://wiki.mljc3b.asia/arts/894852.Doc

原标题：Performance：数据库索引优化常见错误案例
简介：golang nats 轻量消息队列 go 开发，nats 高性能轻量消息系统，发布订阅模式异步解耦业务。
 | 原文链接：http://wiki.mljc3b.asia/arts/123330.Doc

原标题：golang 系统设计灰度发布实现思路
简介：nodejs 信号处理优雅关闭服务，监听系统信号，执行资源清理，实现 Node 服务优雅停机，拒绝粗暴杀死进程。
 | 原文链接：http://wiki.mljc3b.asia/arts/188244.Doc

原标题：方案设计：短链接系统完整架构方案拆解
简介：golang go 网络编程 net 包基础，net 包 tcp udp socket 编程，监听接收连接，读写数据。
 | 原文链接：http://wiki.mljc3b.asia/arts/993797.Doc

原标题：架构笔记：事件驱动架构适用场景与坑点
简介：Redis 分布式锁高并发安全实现，基于 Redis 实现分布式锁，处理锁过期、续期，保障集群并发安全。
 | 原文链接：http://wiki.mljc3b.asia/arts/314928.Doc

原标题：Practice：实现定时任务动态启停管理接口
简介：gitignore 文件编写过滤规则，讲解 gitignore 语法，编写过滤配置，忽略缓存、编译产物、密钥文件，保持仓库整洁。
 | 原文链接：http://wiki.mljc3b.asia/arts/822031.Doc

原标题：新手教程：本地环境变量配置全流程
简介：前端组件库按需加载性能优化，配置组件库按需引入，避免引入全部组件，减少打包产物体积。
 | 原文链接：http://wiki.mljc3b.asia/arts/089806.Doc

原标题：golang 内存缓存简单实现方案
简介：主干开发团队代码合并策略，讲解主干开发模式，团队代码合并流程，适合高频迭代的团队协作模式。
 | 原文链接：http://wiki.mljc3b.asia/arts/899281.Doc

原标题：性能调优：MySQL查询性能优化实战清单
简介：golang go xml 解析生成 xml 文档，encoding/xml 解析 xml，结构体标签映射 xml 节点属性。
 | 原文链接：http://wiki.mljc3b.asia/arts/637661.Doc

原标题：新手教程：本地环境变量配置全流程
简介：golang go json 序列化自定义字段，json 标签控制字段名称、忽略字段、omitempty 空值忽略。
 | 原文链接：http://wiki.mljc3b.asia/arts/488356.Doc

原标题：开发复盘：大事务拆分优化业务性能实践
简介：WebSocket 断线重连稳定优化，增加 WebSocket 断线自动重连逻辑，处理网络抖动，维持长连接稳定。
 | 原文链接：http://wiki.mljc3b.asia/arts/963222.Doc

?
