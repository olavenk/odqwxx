最新前沿技术资讯

一、入门教程｜Getting Started
原标题：方案对比：RPC、HTTP、gRPC场景选型分析
简介：golang go 并发模式 or‑channel 信号合并，合并多个 done 信号，任意一个完成触发退出逻辑。
 | 原文链接：http://book.amd1dg.asia/blog/006066.Doc

原标题：golang kafka 消息顺序性保证方案
简介：数据库连接池参数调优，调整连接池最大最小连接数，空闲超时，避免连接耗尽或者资源浪费。
 | 原文链接：http://book.amd1dg.asia/blog/747366.Doc

原标题：golang 系统设计分布式配置中心思路
简介：golang 多协程任务池并发控制，实现协程任务池，控制并发协程数量，防止无限制创建 goroutine。
 | 原文链接：http://book.amd1dg.asia/blog/158795.Doc

原标题：项目实践：多租户数据隔离三种方案实操对比
简介：golang 子进程超时杀死防止挂住，context 控制子进程超时，超时强制杀掉子进程，避免子进程僵尸。
 | 原文链接：http://book.amd1dg.asia/blog/887255.Doc

原标题：golang docker 部署 mysql 注意事项
简介：不必要字符转义关闭业务异常，关闭多余自动转义逻辑，防止业务数据被错误转义，破坏原始数据。
 | 原文链接：http://book.amd1dg.asia/blog/936223.Doc

原标题：方案设计：分布式锁失效风险架构层面规避
简介：golang ctx 传递规则不要存结构体，context 作为函数参数传递，禁止放入结构体字段存储。
 | 原文链接：http://book.amd1dg.asia/blog/683910.Doc

原标题：golang 系统设计分布式锁超时业务防死锁处理
简介：golang os 文件权限 mode，os.FileMode 文件权限，读写执行权限位，跨平台权限注意事项。
 | 原文链接：http://book.amd1dg.asia/blog/908258.Doc

原标题：记一次第三方SDK版本兼容引发线上故障
简介：移动端适配 rem vw 方案对比，对比 rem 与 vw 移动端适配方案，分析优缺点，给出选型建议。
 | 原文链接：http://book.amd1dg.asia/blog/869486.Doc

原标题：golang 系统设计测试覆盖率目标合理设定思路
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://book.amd1dg.asia/blog/267004.Doc

原标题：坑点：环境配置写死代码，上线忘记修改
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://book.amd1dg.asia/blog/938843.Doc

原标题：Debug：静态资源缓存策略错误，用户看不到更新
简介：代码格式化工具团队统一风格，接入格式化工具，统一全团队代码书写风格，减少格式类 git 冲突。
 | 原文链接：http://book.amd1dg.asia/blog/387198.Doc

原标题：架构复盘：网关层、应用层、数据库层层限流架构
简介：golang go 项目依赖冲突解决完整思路，定位冲突包，replace、exclude、升级降级解决版本冲突。
 | 原文链接：http://book.amd1dg.asia/blog/893628.Doc

原标题：手写简易 ORM 理解对象映射
简介：golang 终端交互式输入选择，命令行交互式问答选择输入，实现交互式脚本工具。
 | 原文链接：http://book.amd1dg.asia/blog/641843.Doc

原标题：Hands‑on：简易短链接服务完整开发实践
简介：golang redis hyperloglog 基数统计，hyperloglog 统计 UV 基数，海量数据去重统计，极低内存开销。
 | 原文链接：http://book.amd1dg.asia/blog/544432.Doc

原标题：golang 大文件 http 下载服务
简介：前端错误监控上报系统搭建，搭建前端错误监控，捕获页面 JS 错误，上报后端，快速发现线上页面 bug。
 | 原文链接：http://book.amd1dg.asia/blog/036065.Doc

原标题：golang 系统设计分表分页排序业务实现难点
简介：OpenAPI 自动接口文档生成，集成 OpenAPI 工具，自动扫描代码生成接口文档，减少文档维护成本。
 | 原文链接：http://book.amd1dg.asia/blog/134312.Doc

原标题：实战项目：HTTPS本地自签名证书配置实践
简介：golang systemd 配置 go 服务部署，编写 systemd unit 文件管理 go 服务，开机自启、崩溃自动重启。
 | 原文链接：http://book.amd1dg.asia/blog/610954.Doc

原标题：golang 系统设计 rest 版本管理几种方案对比
简介：并发数据覆盖加锁安全处理，多线程并发修改同一数据，增加锁机制，防止并发覆盖丢失更新数据。
 | 原文链接：http://book.amd1dg.asia/blog/868884.Doc

原标题：golang 系统设计定时任务动态启停配置方案
简介：golang io.LimitReader 限制读取字节数，LimitReader 限制最大读取，防止读取超大数据。
 | 原文链接：http://book.amd1dg.asia/blog/013120.Doc

原标题：nodejs 多进程任务分发处理
简介：SourceMap 生成线上报错定位，项目打包生成 SourceMap 文件，线上报错可以还原源码，快速定位报错位置。
 | 原文链接：http://book.amd1dg.asia/blog/500302.Doc

原标题：golang redis 持久化 RDB AOF 对比
简介：前后端会话登录状态持久化，实现登录状态持久存储，重启服务登录状态不丢失，保障会话稳定性。
 | 原文链接：http://book.amd1dg.asia/blog/934210.Doc

原标题：golang 系统设计缓存 key 淘汰雪崩防护思路
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：http://book.amd1dg.asia/blog/565574.Doc

原标题：golang redis lua 脚本原子操作
简介：vue pinia 状态管理实战教程，Pinia 完整实战示例，实现状态定义修改，模块拆分替代 Vuex。
 | 原文链接：http://book.amd1dg.asia/blog/130713.Doc

原标题：静态网页 HTML CSS 快速入门实战
简介：golang 自定义 pprof 扩展业务指标，扩展 pprof，输出业务自定义指标，结合性能数据分析业务状态。
 | 原文链接：http://book.amd1dg.asia/blog/203441.Doc

原标题：性能复盘：慢查询日积月累拖垮数据库优化
简介：golang redis pipeline 批量操作，使用 Redis Pipeline 批量执行多条命令，减少网络往返，提升批量操作性能。
 | 原文链接：http://book.amd1dg.asia/blog/908599.Doc

原标题：golang mysql innodb 事务隔离级别
简介：golang trace 链路追踪 opentelemetry，opentelemetry 实现链路追踪，生成 traceId spanId，完整记录调用链路。
 | 原文链接：http://book.amd1dg.asia/blog/934434.Doc

原标题：golang 系统设计雪花算法 id 原理剖析
简介：golang goroutine 池任务调度，实现 goroutine 池，复用协程，频繁任务场景减少协程创建销毁开销。
 | 原文链接：http://book.amd1dg.asia/blog/509236.Doc

原标题：nodejs jwt 登录鉴权完整示例
简介：golang contract 契约测试微服务，微服务契约测试，保证接口变更不破坏调用方，提前发现兼容性问题。
 | 原文链接：http://book.amd1dg.asia/blog/113307.Doc

原标题：golang redis 过期 key 监听业务
简介：golang go 错误包装 fmt.Errorf % w，使用 % w 包装错误，支持 errors.Is errors.As 判断错误类型。
 | 原文链接：http://book.amd1dg.asia/blog/452170.Doc

原标题：避坑：批量操作未分批次，一次性内存打爆
简介：golang go 容器 heap 堆实现优先队列，实现 heap 接口，构建优先队列，任务优先级调度。
 | 原文链接：http://book.amd1dg.asia/blog/684106.Doc

原标题：vite 项目配置与构建提速技巧
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://book.amd1dg.asia/blog/423288.Doc

原标题：eslint prettier 代码规范落地
简介：golang 配置文件多格式兼容加载，同时支持 yaml toml json 多种格式配置文件，灵活适配不同部署环境。
 | 原文链接：http://book.amd1dg.asia/blog/136882.Doc

原标题：golang 分布式上下文传递方案
简介：golang 日志 zap 结构化日志实践，接入 Zap 结构化日志库，打印结构化日志，方便日志检索解析。
 | 原文链接：http://book.amd1dg.asia/blog/843925.Doc

原标题：记一次本地运行正常，线上环境报错诡异问题
简介：golang context.WithValue 传递元数据，WithValue 只传 traceId 鉴权元数据，不要传业务大对象。
 | 原文链接：http://book.amd1dg.asia/blog/467043.Doc

原标题：Practice：实现跨机器文件同步脚本实践
简介：golang 速率限制令牌桶实现，Go 实现令牌桶限流算法，可复用限流器，控制业务调用速率。
 | 原文链接：http://book.amd1dg.asia/blog/537552.Doc

原标题：Architecture：静态配置与动态配置架构分离
简介：手写简易 MQ 理解消息存储消费，手写极简消息队列 Demo，理解消息存储、投递、消费完整流程。
 | 原文链接：http://book.amd1dg.asia/blog/976951.Doc

原标题：实战项目：前端资源打包体积优化完整实操
简介：Git commit 钩子提交规范校验，配置 Git 提交钩子，提交代码自动校验提交信息格式，规范提交记录。
 | 原文链接：http://book.amd1dg.asia/blog/670251.Doc

原标题：golang 系统设计开源项目协作流程梳理
简介：安全组端口开放网络访问，调整服务器安全组规则，开放业务需要端口，恢复外部网络访问服务。
 | 原文链接：http://book.amd1dg.asia/blog/531981.Doc

原标题：golang 工具函数库封装思路
简介：golang go 无锁并发编程技巧，原子操作 sync/atomic，简单场景替换锁，提升并发性能。
 | 原文链接：http://book.amd1dg.asia/blog/918066.Doc

原标题：golang redis 限流几种实现方案
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://book.amd1dg.asia/blog/038003.Doc


二、踩坑排错｜Troubleshooting
原标题：包管理器依赖缓存清理
简介：golang redis pipeline 与 txpipeline 区别，区分普通管道与事务管道，根据业务场景选择合适批量执行方案。
 | 原文链接：http://book.amd1dg.asia/blog/797000.Doc

原标题：Practice：实现接口mock动态返回不同响应
简介：golang bytes.Buffer 字节缓冲区使用，bytes.Buffer 字节内存缓冲区，拼接字节，避免频繁内存分配。
 | 原文链接：http://book.amd1dg.asia/blog/208455.Doc

原标题：golang validator 自定义校验规则
简介：react hooks 常见陷阱避坑指南，梳理 React Hooks 高频踩坑点，依赖数组、闭包陷阱，写出稳定组件。
 | 原文链接：http://book.amd1dg.asia/blog/720680.Doc

原标题：线上故障：慢查询拖垮整个数据库服务
简介：golang go 爬虫 html 解析 goquery，goquery 解析 html 文档，css 选择器提取网页内容，实现网页数据抓取。
 | 原文链接：http://book.amd1dg.asia/blog/545877.Doc

原标题：安全实践：容器最小化镜像减少攻击面
简介：golang benchmark 参数‑bench‑mem 统计内存分配，benchmark 开启内存统计，观察内存分配次数大小。
 | 原文链接：http://book.amd1dg.asia/blog/085515.Doc

原标题：极简 API 网关路由转发实现
简介：golang 多协程任务池并发控制，实现协程任务池，控制并发协程数量，防止无限制创建 goroutine。
 | 原文链接：http://book.amd1dg.asia/blog/912913.Doc

原标题：百万数据 Excel 导出内存优化
简介：golang k8s informer 机制原理理解，informer 监听 k8s 资源变更，本地缓存，减少 apiserver 压力。
 | 原文链接：http://book.amd1dg.asia/blog/047994.Doc

原标题：golang go test 覆盖率统计实操
简介：定时任务重复执行分布式锁，使用分布式锁控制定时任务，保证集群环境定时任务只会执行一次。
 | 原文链接：http://book.amd1dg.asia/blog/712806.Doc

原标题：调优方案：消息批量消费提升MQ处理吞吐量
简介：golang 接口限流中间件开发，Gin 开发限流中间件，接口层实现访问频率限制，防护接口流量。
 | 原文链接：http://book.amd1dg.asia/blog/948809.Doc

原标题：Debug：分页偏移量过大数据库查询性能暴跌
简介：前端下载导出文件功能实现，前端实现文件流下载导出，处理异常，适配浏览器不同下载行为。
 | 原文链接：http://book.amd1dg.asia/blog/862577.Doc

原标题：golang 系统设计限流服务架构讲解
简介：golang gorm 预加载关联查询优化，GORM 预加载关联数据，避免 N+1 查询问题，提升数据库查询性能。
 | 原文链接：http://book.amd1dg.asia/blog/018046.Doc

原标题：部署实践：服务器防火墙安全组配置实践
简介：golang rate‑limiter 限流组件，封装通用 Go 限流组件，支持多算法，业务接口直接复用调用。
 | 原文链接：http://book.amd1dg.asia/blog/160146.Doc

原标题：DevOps：多环境镜像标签版本管理规范
简介：golang 容器 OOM 被杀死排查区分，区分业务内存泄漏、容器限制过小，定位容器 OOMKilled 原因。
 | 原文链接：http://book.amd1dg.asia/blog/379033.Doc

原标题：运维笔记：服务器磁盘内存监控告警配置
简介：golang benchmark 减少测试干扰，benchmark 执行循环 b.N，避免循环内部做非被测逻辑干扰结果。
 | 原文链接：http://book.amd1dg.asia/blog/080293.Doc

原标题：golang es 批量 bulk 操作性能调优
简介：golang 链路追踪简易实现方案，简易链路追踪实现，传递 traceId，记录调用链路，方便排查慢调用。
 | 原文链接：http://book.amd1dg.asia/blog/322986.Doc

原标题：Practice：数据库分表简单实现方案与代码示例
简介：golang 设置 net.Conn 读写超时，每次读写设置超时，防止连接永久阻塞挂起不返回。
 | 原文链接：http://book.amd1dg.asia/blog/899662.Doc

原标题：Debug：异步任务堆积，服务响应越来越慢
简介：golang redis hash 结构业务实战，使用 Redis Hash 存储对象数据，适合对象字段频繁更新业务场景。
 | 原文链接：http://book.amd1dg.asia/blog/457050.Doc

原标题：vue pinia 状态管理实战教程
简介：golang go ring 环形容器循环队列，ring 环形链表实现循环队列，环形缓冲区业务场景。
 | 原文链接：http://book.amd1dg.asia/blog/138924.Doc

原标题：Practice：实现多数据源动态切换组件实践
简介：Git 分支管理多人协作实战教程，详解分支创建、合并、冲突处理，适配团队开发场景，规范多人协同代码工作流。
 | 原文链接：http://book.amd1dg.asia/blog/204413.Doc

原标题：golang 系统设计第三方接口调用封装思路
简介：消息队列消费堆积扩容处理，消息大量堆积时，扩容消费实例，优化消费逻辑，加快消息处理速度。
 | 原文链接：http://book.amd1dg.asia/blog/507648.Doc

原标题：golang 系统设计字段命名类型选择最佳实践
简介：webpack chunk 分包策略详解，讲解 webpack chunk 分包策略，拆分第三方包与业务代码，优化缓存复用。
 | 原文链接：http://book.amd1dg.asia/blog/658456.Doc

原标题：开源实践：维护开源项目Issue管理经验总结
简介：golang os 进程 pid 获取父进程 pid，os.Getpid 获取进程 id，获取父进程 pid，进程间识别。
 | 原文链接：http://book.amd1dg.asia/blog/401774.Doc

原标题：开发复盘：大数据量分页避免offset性能问题
简介：数据库事务 ACID 原理讲解，拆解事务四大特性，理解事务隔离、原子性，明白事务如何保障数据安全。
 | 原文链接：http://book.amd1dg.asia/blog/149351.Doc

原标题：golang 系统设计容量评估简单方法论
简介：golang init 函数合理使用边界，少用 init，优先显式调用初始化，便于控制初始化时机。
 | 原文链接：http://book.amd1dg.asia/blog/881408.Doc

原标题：动态定时任务业务调度实现
简介：golang 数据库分表策略按时间分片，按时间维度分表，历史数据拆分，单表数据量控制保证查询性能。
 | 原文链接：http://book.amd1dg.asia/blog/085800.Doc

原标题：golang zap 日志按日期切割方案
简介：序列化版本不一致解析失败，保证序列化对象版本对齐，修复版本不匹配导致对象反序列化失败。
 | 原文链接：http://book.amd1dg.asia/blog/812147.Doc

原标题：golang 系统设计链路追踪核心概念 trace span 讲解
简介：golang 文件句柄耗尽排查处理，统计进程打开文件句柄，找到未关闭文件，修复句柄泄漏问题。
 | 原文链接：http://book.amd1dg.asia/blog/315840.Doc

原标题：Git 混乱提交历史清理方法
简介：消息消费重试次数限制防爆炸，限制消息最大重试次数，防止失败消息无限重试造成消息爆炸堆积。
 | 原文链接：http://book.amd1dg.asia/blog/920670.Doc

原标题：golang 系统设计 mq 消息顺序性保证思路
简介：golang https 客户端跳过证书校验，开发测试环境跳过 tls 证书校验，仅用于内网测试禁止生产使用。
 | 原文链接：http://book.amd1dg.asia/blog/522929.Doc

原标题：Practice：实现熔断降级组件简单原型代码
简介：golang go 项目工程目录布局标准，不同规模 go 项目目录结构，小型项目中型项目大型微服务项目布局。
 | 原文链接：http://book.amd1dg.asia/blog/423718.Doc

原标题：开发记录：批量接口请求并发控制实践
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://book.amd1dg.asia/blog/775604.Doc

原标题：Troubleshooting：K8sPodOOMKilled完整排查流程
简介：golang go 泛型约束与类型集合，泛型 type set 约束，限制泛型支持类型，写出安全泛型代码。
 | 原文链接：http://book.amd1dg.asia/blog/864356.Doc

原标题：golang 系统设计内部服务链路 trace 传递实现
简介：容器资源限制防止宿主机过载，设置容器 CPU 内存资源上限，避免单个容器耗尽宿主机全部硬件资源。
 | 原文链接：http://book.amd1dg.asia/blog/790494.Doc

原标题：坑点：依赖缓存未更新，旧代码持续运行
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://book.amd1dg.asia/blog/535563.Doc

原标题：HelloMarkdown：GitHubMarkdown完整语法速查
简介：golang 内存 pprof 定位内存泄漏，pprof 分析内存快照，定位内存泄露对象，解决 Go 程序内存持续上涨。
 | 原文链接：http://book.amd1dg.asia/blog/775815.Doc

原标题：golang 协程泄露问题排查方法
简介：react 状态管理方案选型对比，对比 Redux、Zustand 等 React 状态管理库，分析适用业务场景辅助选型。
 | 原文链接：http://book.amd1dg.asia/blog/459322.Doc

原标题：Fork 开源项目同步上游代码
简介：前后端交互跨域问题完整处理，讲解跨域产生原理，列举多种解决方案，适配开发、生产不同环境的跨域处理。
 | 原文链接：http://book.amd1dg.asia/blog/047482.Doc

原标题：golang 系统设计 tcp keepalive 参数调优实践
简介：golang 多协程任务池并发控制，实现协程任务池，控制并发协程数量，防止无限制创建 goroutine。
 | 原文链接：http://book.amd1dg.asia/blog/160526.Doc

原标题：Troubleshoot：MySQL字符集utf8非utf8mb4emoji报错
简介：golang time 时间格式化参考时间牢记，2006‑01‑02T15:04:05Z07:00，掌握 go 时间格式化关键点。
 | 原文链接：http://book.amd1dg.asia/blog/756693.Doc

原标题：golang 系统设计参数校验统一处理方案
简介：golang 空接口 interface {} 类型处理，interface {} 存储任意类型，类型转换，处理泛型之前通用数据。
 | 原文链接：http://book.amd1dg.asia/blog/452282.Doc

三、实战开发｜Practice
原标题：golang 系统设计内部服务调用超时设置要点
简介：golang go yaml 解析自定义类型，yaml 自定义序列化，时间、特殊类型自定义解析逻辑。
 | 原文链接：http://book.amd1dg.asia/blog/055811.Doc

原标题：HelloDocker：编写你的第一个Dockerfile
简介：golang go‑zero 框架项目快速搭建，go‑zero 脚手架生成微服务项目，api rpc 服务快速开发。
 | 原文链接：http://book.amd1dg.asia/blog/337515.Doc

原标题：AI实践：大模型生成代码后审查与重构实践
简介：golang gorm ORM 数据库操作，GORM 实操数据库 CRUD，模型定义，关联查询，简化 Go 数据库开发。
 | 原文链接：http://book.amd1dg.asia/blog/866623.Doc

原标题：安全笔记：XSS跨站脚本攻击防御落地实践
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://book.amd1dg.asia/blog/612818.Doc

原标题：进程线程并发基础概念讲解
简介：golang channel 通道并发处理，讲解 Channel 用法，协程之间通过通道传递数据，做并发同步控制。
 | 原文链接：http://book.amd1dg.asia/blog/192186.Doc

原标题：前端权限路由动态生成实现
简介：monorepo 项目多包管理最佳实践，monorepo 仓库管理多子包，统一版本管理，处理包之间互相依赖。
 | 原文链接：http://book.amd1dg.asia/blog/420690.Doc

原标题：Hands‑on：静态资源CDN缓存控制头配置实践
简介：跨库查询性能优化处理，减少跨库关联查询，做数据冗余或者中间表，规避跨库查询性能低下。
 | 原文链接：http://book.amd1dg.asia/blog/549844.Doc

原标题：优化实践：异步改造同步接口提升吞吐能力
简介：多版本开发环境共存配置，实现同一工具多版本并存，快速切换不同版本，适配不同项目对版本的差异化需求。
 | 原文链接：http://book.amd1dg.asia/blog/541171.Doc

原标题：踩坑：消息队列消息堆积，消费者处理能力不足
简介：golang rate‑limiter 限流组件，封装通用 Go 限流组件，支持多算法，业务接口直接复用调用。
 | 原文链接：http://book.amd1dg.asia/blog/126281.Doc

原标题：安全实践：输入输出双向过滤安全最佳实践
简介：golang redis hyperloglog 基数统计，hyperloglog 统计 UV 基数，海量数据去重统计，极低内存开销。
 | 原文链接：http://book.amd1dg.asia/blog/323540.Doc

原标题：golang 系统设计数据库慢请求排查流程
简介：golang 图片处理 go 图片裁剪压缩，golang 图像处理库，图片缩放裁剪水印，服务端图片处理。
 | 原文链接：http://book.amd1dg.asia/blog/863261.Doc

原标题：golang 系统设计 jwt 安全使用避坑要点
简介：程序信号中断退出处理逻辑，捕获系统中断信号，执行资源释放、关闭连接，实现程序优雅退出。
 | 原文链接：http://book.amd1dg.asia/blog/648741.Doc

原标题：golang 系统设计 webhook 回调处理架构
简介：golang sync.Mutex 互斥锁正确模式，互斥锁 defer Unlock，锁粒度控制，避免锁范围过大。
 | 原文链接：http://book.amd1dg.asia/blog/800966.Doc

原标题：golang k8s job 一次性任务执行
简介：golang GC 调优 GOGC 参数调整，调整 GOGC 阈值，控制 GC 触发时机，权衡内存占用与 CPU 开销。
 | 原文链接：http://book.amd1dg.asia/blog/941074.Doc

原标题：DevOps：WSL2生产环境使用风险提示
简介：模拟登录鉴权权限判断示例，实现简易登录流程，会话状态维护，完成接口权限校验，理解身份鉴权基础逻辑。
 | 原文链接：http://book.amd1dg.asia/blog/199092.Doc

原标题：快速入门OpenAPI文档生成基础实践
简介：golang yaml 解析配置加载实操，Go 解析 YAML 配置文件，读取配置参数，驱动业务运行。
 | 原文链接：http://book.amd1dg.asia/blog/783690.Doc

原标题：golang 系统设计依赖版本升级风险评估
简介：golang word 文档生成处理 go 方案，go 生成 word 文档报表，填充文本表格，输出 docx 文件。
 | 原文链接：http://book.amd1dg.asia/blog/820735.Doc

原标题：实战：Redis过期回调实现业务事件通知实践
简介：golang 字符串处理常用技巧汇总，字符串拼接、分割、替换、类型转换实操，规避字符串高频错误。
 | 原文链接：http://book.amd1dg.asia/blog/889621.Doc

原标题：安全笔记：Cookie安全属性SecureHttpOnly
简介：golang socket 文件描述符继承重启，父进程传递 listener fd 给子进程，实现 go 程序零停机热重启。
 | 原文链接：http://book.amd1dg.asia/blog/849884.Doc

原标题：golang redis stream 消息队列实践
简介：golang 内存持续上涨定位思路，区分内存泄漏、缓存占用、GC 参数不合理，分步定位内存持续走高。
 | 原文链接：http://book.amd1dg.asia/blog/010227.Doc

原标题：安全实践：接口错误信息不要暴露内部细节
简介：golang 压缩 zip 文件生成解压，golang 实现 zip 压缩打包，解压 zip 归档文件，处理批量文件归档。
 | 原文链接：http://book.amd1dg.asia/blog/226447.Doc

原标题：实战项目：搭建本地Mock服务快速开发联调
简介：golang go ring 环形容器循环队列，ring 环形链表实现循环队列，环形缓冲区业务场景。
 | 原文链接：http://book.amd1dg.asia/blog/828263.Doc

原标题：开发记录：数据库悲观锁乐观锁业务场景实践
简介：golang 速率限制令牌桶实现，Go 实现令牌桶限流算法，可复用限流器，控制业务调用速率。
 | 原文链接：http://book.amd1dg.asia/blog/595107.Doc

原标题：golang 系统设计定时任务分片执行分布式思路
简介：golang cobra 命令行参数配置绑定，cobra 绑定配置文件环境变量命令行参数，多源配置合并。
 | 原文链接：http://book.amd1dg.asia/blog/503721.Doc

原标题：入门实践：简单重试逻辑封装实现
简介：golang rsa 非对称加密签名验签，RSA 非对称加密与签名验签，实现非对称安全通信。
 | 原文链接：http://book.amd1dg.asia/blog/797553.Doc

原标题：TCP 长连接参数优化 TIME_WAIT
简介：golang sync.Pool 对象池复用对象，sync.Pool 复用临时对象，减少内存分配，降低 GC 频率提升性能。
 | 原文链接：http://book.amd1dg.asia/blog/358623.Doc

原标题：Troubleshooting：Nginx缓冲区过小大文件上传失败
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://book.amd1dg.asia/blog/830695.Doc

原标题：运维笔记：系统监控指标大盘搭建实操
简介：nodejs http 服务性能调优实战，调优 Node HTTP 服务内核参数，连接复用，提升接口并发处理能力。
 | 原文链接：http://book.amd1dg.asia/blog/083301.Doc

原标题：项目实践：Docker镜像安全扫描本地实操
简介：golang bufio.Scanner 按行读取大文件，Scanner 逐行读取文本文件，处理超大日志 csv。
 | 原文链接：http://book.amd1dg.asia/blog/018478.Doc

原标题：golang 系统设计 p0 故障复盘方法论讲解
简介：CLI 工具进度条交互效果开发，在命令行工具增加进度条展示，直观反馈任务执行进度，优化命令行体验。
 | 原文链接：http://book.amd1dg.asia/blog/675188.Doc

原标题：HelloShell：入门常用shell脚本编写
简介：golang go 包循环导入报错解决，A 导入 B B 导入 A，循环导入报错，重构代码拆分包消除循环依赖。
 | 原文链接：http://book.amd1dg.asia/blog/126629.Doc

原标题：坑点：Git仓库过大，clone速度极慢解决方案
简介：golang os.Signal 信号监听完整示例，signal.Notify 监听信号，缓冲 channel 防止信号丢失。
 | 原文链接：http://book.amd1dg.asia/blog/162574.Doc

原标题：golang 系统设计分布式事务业务选型决策思路
简介：GitHub 项目提交推送完整流程讲解，从仓库初始化到提交推送远程仓库，梳理全流程细节，避开新手高频错误。
 | 原文链接：http://book.amd1dg.asia/blog/059523.Doc

原标题：性能复盘：锁等待严重业务逻辑优化记录
简介：golang nats jetstream 持久消息队列，nats jetstream 持久化消息，保证消息不丢失，实现可靠消费。
 | 原文链接：http://book.amd1dg.asia/blog/965159.Doc

原标题：多操作系统开发兼容处理
简介：golang slice 切片底层原理与坑点，切片扩容、截取、底层数组共享，规避切片修改互相影响数据。
 | 原文链接：http://book.amd1dg.asia/blog/896557.Doc

原标题：代码格式化工具团队统一风格
简介：golang systemd 信号与优雅退出配合，systemd 停止服务发送 SIGTERM，go 程序捕获信号优雅关闭。
 | 原文链接：http://book.amd1dg.asia/blog/085692.Doc

原标题：一次数据库死锁现场分析与解决方案记录
简介：nodejs jwt 登录鉴权完整示例，Node 实现 JWT 登录鉴权，登录签发令牌，接口校验令牌身份。
 | 原文链接：http://book.amd1dg.asia/blog/245105.Doc

原标题：golang 分布式锁 redis 实现
简介：golang grpc metadata 元数据透传，metadata 传递 traceId、鉴权信息，全链路透传上下文信息。
 | 原文链接：http://book.amd1dg.asia/blog/558603.Doc

原标题：golang 系统设计回调签名校验防伪造实现
简介：golang rsa 非对称加密签名验签，RSA 非对称加密与签名验签，实现非对称安全通信。
 | 原文链接：http://book.amd1dg.asia/blog/281464.Doc

原标题：golang 系统设计日志规范结构化日志落地
简介：golang io.Copy 流式拷贝数据，io.Copy 拷贝 reader 到 writer，不用加载全部数据到内存。
 | 原文链接：http://book.amd1dg.asia/blog/676117.Doc

四、架构设计｜Architecture
原标题：零基础理解模块化与组件化基础思想
简介：golang go select 多路等待 channel，select 等待多个 channel，default 非阻塞，超时等待 channel。
 | 原文链接：http://book.amd1dg.asia/blog/863285.Doc

原标题：OpenSource：开源项目贡献者协作流程规范
简介：golang contract 契约测试微服务，微服务契约测试，保证接口变更不破坏调用方，提前发现兼容性问题。
 | 原文链接：http://book.amd1dg.asia/blog/769923.Doc

原标题：零基础理解HTTP常用请求头与状态码
简介：前端图片懒加载性能优化，实现图片懒加载，页面可视区域才加载图片，减少页面初始网络请求。
 | 原文链接：http://book.amd1dg.asia/blog/659699.Doc

原标题：golang 系统设计 sql 注入 xss 防护实践
简介：golang docker compose 开发环境 go 服务，docker compose 编排 go 服务与中间件，本地一键拉起整套开发环境。
 | 原文链接：http://book.amd1dg.asia/blog/467322.Doc

原标题：性能笔记：磁盘IO过高业务优化手段
简介：golang http client 连接池调优，调优 Go HTTP Client 连接池参数，复用 TCP 连接，减少连接创建开销。
 | 原文链接：http://book.amd1dg.asia/blog/278834.Doc

原标题：百万数据 Excel 导出内存优化
简介：rebase 操作防止代码丢失，讲解 rebase 风险点，操作前做好备份，规避错误操作造成代码提交丢失。
 | 原文链接：http://book.amd1dg.asia/blog/507433.Doc

原标题：大事务拆分防止连接池耗尽
简介：golang 定时任务任务持久化存储，定时任务持久化到数据库，服务重启任务不丢失，动态管理任务。
 | 原文链接：http://book.amd1dg.asia/blog/034130.Doc

原标题：golang kafka offset 提交策略
简介：golang atomic 原子操作整数，atomic 加减比较交换，无锁更新整型变量，简单计数器场景。
 | 原文链接：http://book.amd1dg.asia/blog/916649.Doc

原标题：部署实践：容器优雅停机配置处理信号
简介：golang 自定义 pprof 扩展业务指标，扩展 pprof，输出业务自定义指标，结合性能数据分析业务状态。
 | 原文链接：http://book.amd1dg.asia/blog/944579.Doc

原标题：架构复盘：服务优雅停机架构设计资源释放
简介：多套环境灵活切换配置方案，实现配置动态切换，通过环境变量、配置文件，快速切换开发测试生产环境。
 | 原文链接：http://book.amd1dg.asia/blog/054869.Doc

原标题：优化实践：读写分离分担主库查询压力
简介：代码模块化组件化拆分思路，讲解代码拆分原则，将大业务拆分为独立模块组件，提升代码复用与维护能力。
 | 原文链接：http://book.amd1dg.asia/blog/771288.Doc

原标题：Issue：WSL2内存持续暴涨不自动释放
简介：消息消费重试次数限制防爆炸，限制消息最大重试次数，防止失败消息无限重试造成消息爆炸堆积。
 | 原文链接：http://book.amd1dg.asia/blog/236421.Doc

原标题：Debug：时间回拨，定时任务调度逻辑错乱
简介：golang go‑zero 分布式锁组件使用，go‑zero 内置 redis 分布式锁，业务直接调用实现并发控制。
 | 原文链接：http://book.amd1dg.asia/blog/389658.Doc

原标题：方案设计：高可用Redis集群架构选型对比
简介：重复提交幂等防护再次讲解，梳理前端重复点击、网络重试场景，落地接口幂等，杜绝重复业务。
 | 原文链接：http://book.amd1dg.asia/blog/648452.Doc

原标题：golang 系统设计批量处理优化业务性能
简介：golang 优雅停机服务关闭实现，监听系统信号，关闭服务等待请求处理完毕，实现 Go 服务优雅停机。
 | 原文链接：http://book.amd1dg.asia/blog/949903.Doc

原标题：新手指南：虚拟机WSL开发环境入门配置
简介：开源项目本地运行排错完整清单，汇总开源项目拉取后运行失败各类问题，给出排查思路，快速解决本地启动异常。
 | 原文链接：http://book.amd1dg.asia/blog/096017.Doc

原标题：golang docker 部署 kafka 本地调试
简介：前端组件库按需加载性能优化，配置组件库按需引入，避免引入全部组件，减少打包产物体积。
 | 原文链接：http://book.amd1dg.asia/blog/107436.Doc

原标题：nodejs 数据库连接池配置调优
简介：golang k8s go 服务 yaml 资源编写，k8s 部署 go 应用 deployment service，健康检查资源限制配置。
 | 原文链接：http://book.amd1dg.asia/blog/725278.Doc

?
