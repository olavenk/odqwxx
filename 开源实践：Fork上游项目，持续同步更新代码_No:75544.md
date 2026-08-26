最新前沿技术资讯

一、入门教程｜Getting Started
原标题：开源实践：Fork上游项目，持续同步更新代码
简介：文件分片上传断点续传功能，实现文件分片上传，记录上传进度，支持断点续传大文件上传。
 | 原文链接：http://wiki.083dms.asia/arts/504365.Doc

原标题：前端虚拟列表大数据渲染优化
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：http://wiki.083dms.asia/arts/320381.Doc

原标题：服务健康检查监控接口开发
简介：golang grpc 服务端流推送数据，服务端流式响应，服务端持续向客户端推送多条响应消息。
 | 原文链接：http://wiki.083dms.asia/arts/068992.Doc

原标题：安全笔记：CORS跨域配置错误安全风险
简介：多线程线程安全脏数据规避，梳理多线程共享变量，做好同步控制，避免并发修改产生脏数据。
 | 原文链接：http://wiki.083dms.asia/arts/661755.Doc

原标题：排错：DockerCompose依赖顺序启动顺序坑
简介：golang 集成测试测试数据库回滚，集成测试结束自动回滚数据库，不污染测试环境数据。
 | 原文链接：http://wiki.083dms.asia/arts/011857.Doc

原标题：性能复盘：系统上下文切换过高性能下降调优
简介：golang 配置热更新不重启服务，实现配置热加载，监听配置变更，更新内存配置，无需重启服务实例。
 | 原文链接：http://wiki.083dms.asia/arts/018478.Doc

原标题：golang 系统设计本地缓存与分布式缓存
简介：动态定时任务业务调度实现，实现可以动态增删启停定时任务，无需重启服务调整调度任务。
 | 原文链接：http://wiki.083dms.asia/arts/564929.Doc

原标题：架构复盘：数据库主从架构设计与延迟应对方案
简介：golang go‑zero 缓存自动击穿防护，go‑zero 缓存组件自带缓存击穿防护，减少缓存层故障。
 | 原文链接：http://wiki.083dms.asia/arts/631060.Doc

原标题：实战：GraphQL服务搭建与CRUD实操
简介：nestjs 权限守卫鉴权实现方案，使用 Nest 守卫实现接口鉴权，角色权限控制，拦截未授权接口访问。
 | 原文链接：http://wiki.083dms.asia/arts/782182.Doc

原标题：实战：搭建本地对象存储兼容S3协议demo
简介：golang mysql 长连接检测保活设置，配置 mysql 连接保活检测，剔除失效连接，避免拿到断开无效数据库连接。
 | 原文链接：http://wiki.083dms.asia/arts/175008.Doc

原标题：golang 系统设计 tcp keepalive 参数调优实践
简介：golang rabbitmq go 客户端生产消费，streadway/amqp 实现 rabbitmq 生产者消费者，队列交换机绑定。
 | 原文链接：http://wiki.083dms.asia/arts/395260.Doc

原标题：nodejs redis 缓存业务实战
简介：golang hmac 签名生成校验示例，hmac 生成消息签名，做接口请求签名，校验数据不被篡改。
 | 原文链接：http://wiki.083dms.asia/arts/089766.Doc

原标题：golang jwt 过期刷新 token 实现
简介：golang context.WithCancel 手动取消上下文，WithCancel 生成可取消 ctx，手动调用 cancel 触发取消。
 | 原文链接：http://wiki.083dms.asia/arts/120307.Doc

原标题：golang k8s liveness readiness 探针
简介：数据库连接及时关闭连接泄漏，确保数据库连接使用完毕释放归还连接池，杜绝连接泄漏耗尽连接。
 | 原文链接：http://wiki.083dms.asia/arts/607044.Doc

原标题：golang 系统设计回调异步处理防止超时阻塞
简介：golang fuzz corpus 语料库使用，fuzz 语料存储历史输入，回归测试，持续复现曾经触发 bug 输入。
 | 原文链接：http://wiki.083dms.asia/arts/929526.Doc

原标题：nestjs 拦截器过滤器管道实战
简介：golang 信号触发配置重载实践，收到 SIGUSR1 信号重新加载配置，线上无需重启刷新配置。
 | 原文链接：http://wiki.083dms.asia/arts/345722.Doc

原标题：Troubleshoot：异步异常未捕获，进程悄无声息退出
简介：请求重试组件退避策略实现，封装重试组件，实现指数退避策略，避免大量请求同时重试压垮下游。
 | 原文链接：http://wiki.083dms.asia/arts/567255.Doc

原标题：服务器 Swap 关闭提升响应速度
简介：golang 容器时区设置镜像构建处理，镜像内部设置正确时区，解决容器时间与宿主机不一致。
 | 原文链接：http://wiki.083dms.asia/arts/538527.Doc

原标题：分页逻辑错误数据漏查修复
简介：golang net.Conn 包装自定义连接，包装 net.Conn，统计读写字节，日志打印，超时控制。
 | 原文链接：http://wiki.083dms.asia/arts/860637.Doc

原标题：Issue复现：内存泄漏定位完整复盘记录
简介：golang go 程序敏感信息禁止打印日志，密钥密码禁止输出日志，防止敏感信息日志泄露。
 | 原文链接：http://wiki.083dms.asia/arts/726170.Doc

原标题：Shell 脚本自动化命令编写
简介：golang httptest 模拟 http 请求单元测试，httptest 模拟 http 请求，测试 http handler 逻辑不用启动服务。
 | 原文链接：http://wiki.083dms.asia/arts/503381.Doc

原标题：时间精度统一业务判断修复
简介：golang 限流熔断放在代理层实践，代理层统一限流熔断，对后端服务做流量保护。
 | 原文链接：http://wiki.083dms.asia/arts/264218.Doc

原标题：实战项目：CLI批量文件处理工具开发全过程
简介：golang 正则表达式 Go 实操案例，正则匹配提取替换，处理手机号邮箱校验，规避正则回溯 CPU 暴涨。
 | 原文链接：http://wiki.083dms.asia/arts/473794.Doc

原标题：全局时间标准统一逻辑错乱修复
简介：golang 服务限流熔断降级监控完整实践，微服务防护体系，限流熔断降级指标监控告警整套落地。
 | 原文链接：http://wiki.083dms.asia/arts/752722.Doc

原标题：golang 系统设计 http3 quic 简单原理了解
简介：golang 命令行参数解析开发，解析命令行入参，开发自定义 CLI 程序，读取启动参数配置服务。
 | 原文链接：http://wiki.083dms.asia/arts/591733.Doc

原标题：golang 系统设计熔断算法 hystrix 思路
简介：代理 HTTPS 证书访问异常处理，配置代理根证书，解决代理环境 HTTPS 证书校验失败无法访问外网。
 | 原文链接：http://wiki.083dms.asia/arts/119559.Doc

原标题：磁盘 inode 耗尽文件创建失败
简介：golang go 变量逃逸场景汇总，切片、指针、返回局部变量引发逃逸，变量分配到堆影响 GC。
 | 原文链接：http://wiki.083dms.asia/arts/942107.Doc

原标题：Debug：序列化反序列化版本不一致解析失败
简介：项目构建脚本编译打包解析，解读项目构建脚本，理清编译、压缩、资源复制流程，理解打包后产物如何生成。
 | 原文链接：http://wiki.083dms.asia/arts/053479.Doc

原标题：Debug：多线程共享可变变量产生脏数据
简介：API 接口调试与异常处理实战，覆盖接口请求、参数组装、错误捕获，提供调试思路，高效定位接口返回异常问题。
 | 原文链接：http://wiki.083dms.asia/arts/382947.Doc

原标题：CORS 跨域问题多种解决方案
简介：golang testing.TB Helper 标记辅助函数，t.Helper 标记辅助函数，报错打印真实调用位置。
 | 原文链接：http://wiki.083dms.asia/arts/501514.Doc

原标题：golang es 高亮搜索结果实现方案
简介：golang 集成测试测试数据库回滚，集成测试结束自动回滚数据库，不污染测试环境数据。
 | 原文链接：http://wiki.083dms.asia/arts/513093.Doc

原标题：Practice：实现请求body重复读取中间件实践
简介：消息消费重试次数限制防爆炸，限制消息最大重试次数，防止失败消息无限重试造成消息爆炸堆积。
 | 原文链接：http://wiki.083dms.asia/arts/985446.Doc

原标题：开发复盘：数据库批量更新优化性能实践
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://wiki.083dms.asia/arts/926752.Doc

原标题：golang 参数校验业务接口处理
简介：多实例部署 Session 共享方案，多服务实例部署场景，实现 Session 共享，保证用户登录状态跨实例生效。
 | 原文链接：http://wiki.083dms.asia/arts/985390.Doc

原标题：golang 系统设计 debug 远程调试 go 程序实操
简介：golang go 死锁检测工具，静态检查、运行检测，发现 channel 锁导致死锁问题。
 | 原文链接：http://wiki.083dms.asia/arts/867190.Doc

原标题：开发记录：搭建CI/CD流水线自动构建部署项目
简介：分布式任务调度集群原型开发，开发简易分布式调度原型，集群多节点运行，保证任务只执行一次。
 | 原文链接：http://wiki.083dms.asia/arts/172666.Doc

原标题：react hooks 常见陷阱避坑指南
简介：前端虚拟列表大数据渲染优化，实现虚拟滚动列表，只渲染可视区域 DOM，上万条数据页面流畅渲染。
 | 原文链接：http://wiki.083dms.asia/arts/492222.Doc

原标题：避坑：文件锁处理不当多进程竞争死锁
简介：golang redis stream 消息队列实战，redis stream 实现可靠消息队列，消费组、ack 确认，消息不丢失。
 | 原文链接：http://wiki.083dms.asia/arts/807046.Doc

原标题：golang 系统设计 saga 事务补偿模式实现思路
简介：SSH 密钥配置 GitHub 免密登录，分步生成配置 SSH 密钥，实现 GitHub 免密推送拉取，免去重复输入账号密码的麻烦。
 | 原文链接：http://wiki.083dms.asia/arts/941396.Doc

原标题：复盘总结：接口重构兼容旧版本改造复盘
简介：golang k8s secret 敏感配置加载，加载 k8s secret 存储密钥密码，敏感信息不存放配置文件。
 | 原文链接：http://wiki.083dms.asia/arts/215359.Doc


二、踩坑排错｜Troubleshooting
原标题：golang 系统设计 mq 消息积压解决方案
简介：并发数据覆盖加锁安全处理，多线程并发修改同一数据，增加锁机制，防止并发覆盖丢失更新数据。
 | 原文链接：http://wiki.083dms.asia/arts/892285.Doc

原标题：CPU 亲和性配置负载均衡调度
简介：golang 命令行参数解析开发，解析命令行入参，开发自定义 CLI 程序，读取启动参数配置服务。
 | 原文链接：http://wiki.083dms.asia/arts/052281.Doc

原标题：Practice：实现接口mock动态返回不同响应
简介：程序日志分级输出规范实践，区分日志等级，规范日志打印内容，合理输出日志，方便线上问题排查定位。
 | 原文链接：http://wiki.083dms.asia/arts/255586.Doc

原标题：用户敏感数据脱敏代码实现
简介：golang panic 崩溃日志完整收集，捕获所有 panic，打印堆栈，记录日志，方便定位崩溃根源。
 | 原文链接：http://wiki.083dms.asia/arts/298204.Doc

原标题：开发记录：接口请求日志记录完整中间件实现
简介：限流组件计数器令牌桶模式实现，实现计数器、令牌桶两种限流算法，封装可复用限流组件。
 | 原文链接：http://wiki.083dms.asia/arts/947461.Doc

原标题：golang mongodb 分页性能优化技巧
简介：golang go 排序 sort 包自定义排序，sort 包实现自定义排序逻辑，对切片按业务规则排序。
 | 原文链接：http://wiki.083dms.asia/arts/967768.Doc

原标题：CI 流水线超时时间延长配置
简介：golang 字符串处理常用技巧汇总，字符串拼接、分割、替换、类型转换实操，规避字符串高频错误。
 | 原文链接：http://wiki.083dms.asia/arts/212382.Doc

原标题：golang 系统设计 docker compose 本地开发环境搭建
简介：golang 协程数量监控统计方案，统计运行中 goroutine 数量，监控协程泄露，协程数量异常及时告警。
 | 原文链接：http://wiki.083dms.asia/arts/858107.Doc

原标题：Debug：时间回拨，定时任务调度逻辑错乱
简介：golang 时间戳秒毫秒纳秒转换，Unix UnixMilli UnixNano 互相转换，区分单位避免时间逻辑 bug。
 | 原文链接：http://wiki.083dms.asia/arts/820712.Doc

原标题：golang 系统设计故障应急响应完整流程梳理
简介：golang go proxy 私有代理配置，配置 go proxy 私有代理，加速依赖下载，内网环境构建项目。
 | 原文链接：http://wiki.083dms.asia/arts/855078.Doc

原标题：Practice：实现定时任务动态启停管理接口
简介：golang 跨平台系统差异处理方案，处理 windows linux mac 路径、信号、文件权限差异，代码跨平台兼容。
 | 原文链接：http://wiki.083dms.asia/arts/229935.Doc

原标题：golang redis 网络超时参数调优
简介：golang 结构体 json 序列化坑点，梳理 Go 结构体 JSON 序列化高频坑点，字段大小写、零值处理问题。
 | 原文链接：http://wiki.083dms.asia/arts/561747.Doc

原标题：Redis 热点 key 拆分降低集群压力
简介：golang redis lua 脚本原子操作，使用 Lua 脚本实现原子逻辑，减少网络往返，保障多命令原子执行。
 | 原文链接：http://wiki.083dms.asia/arts/269794.Doc

原标题：开发复盘：大JSON解析分批处理避免内存溢出
简介：依赖安装失败全方位排错，从网络、镜像源、权限、版本多角度，定位依赖安装失败，给出对应修复手段。
 | 原文链接：http://wiki.083dms.asia/arts/802357.Doc

原标题：安全实践：生产环境禁止开启debug调试模式
简介：golang 进程信号捕获 SIGUSR 自定义信号，捕获用户自定义信号，实现线上不重启触发调试、日志切换。
 | 原文链接：http://wiki.083dms.asia/arts/590543.Doc

原标题：零基础理解幂等性基础概念与场景
简介：golang go 项目依赖冲突解决完整思路，定位冲突包，replace、exclude、升级降级解决版本冲突。
 | 原文链接：http://wiki.083dms.asia/arts/639114.Doc

原标题：golang 系统设计读写穿透更新缓存几种方案
简介：nodejs 内存溢出问题排查修复，Node.js 程序 OOM 排查流程，定位内存泄露，调整内存限制修复崩溃。
 | 原文链接：http://wiki.083dms.asia/arts/151772.Doc

原标题：容器内存扩容 OOM 被杀死修复
简介：分布式 ID 生成器高并发实现，实现高性能分布式 ID 生成器，适配高并发业务，生成全局唯一 ID。
 | 原文链接：http://wiki.083dms.asia/arts/495800.Doc

原标题：golang docker compose 本地开发最佳实践
简介：golang rsa 签名验签 pem 证书加载，加载 pem 格式密钥证书，rsa 签名与验签完整业务实现。
 | 原文链接：http://wiki.083dms.asia/arts/180012.Doc

原标题：快速入门简单签名校验实现思路
简介：golang http 服务优雅关闭完整示例，接收终止信号，停止接收新请求，等待现有请求处理完毕后退出服务。
 | 原文链接：http://wiki.083dms.asia/arts/769237.Doc

原标题：golang redis lua 脚本原子操作
简介：golang go 模块迁移从 GOPATH 到 GoMod，老项目从 GOPATH 迁移 go mod，解决依赖管理混乱问题。
 | 原文链接：http://wiki.083dms.asia/arts/533017.Doc

原标题：golang mongodb 分页性能优化技巧
简介：容器资源限制防止宿主机过载，设置容器 CPU 内存资源上限，避免单个容器耗尽宿主机全部硬件资源。
 | 原文链接：http://wiki.083dms.asia/arts/412135.Doc

原标题：golang 系统设计 cpu 高占用排查步骤
简介：Redis 大 key 拆分集群卡顿解决，拆分 Redis 超大 Key，避免大 key 操作造成 Redis 集群卡顿阻塞。
 | 原文链接：http://wiki.083dms.asia/arts/357296.Doc

原标题：golang 系统设计内部服务契约测试简单思路
简介：golang wasm 性能优化与内存管理，wasm 内存分配释放，减少内存拷贝，优化浏览器端性能。
 | 原文链接：http://wiki.083dms.asia/arts/201641.Doc

原标题：动态定时任务业务调度实现
简介：手写简易 RPC 服务通信原型，手写极简 RPC 原型，理解服务注册、网络传输、方法调用底层逻辑。
 | 原文链接：http://wiki.083dms.asia/arts/071005.Doc

原标题：golang 速率限制令牌桶实现
简介：golang map 并发读写 panic 解决方案，map 非并发安全，讲解加锁、sync.map 方案解决并发读写崩溃。
 | 原文链接：http://wiki.083dms.asia/arts/960800.Doc

原标题：OpenSource：开源项目版本发布CHANGELOG编写
简介：golang atomic.Value 存储任意类型数据，atomic.Value 安全存储读取任意类型，配置热更新常用。
 | 原文链接：http://wiki.083dms.asia/arts/958473.Doc

原标题：golang 系统设计业务指标系统指标定义思路
简介：golang 本地消息表实现最终一致性，本地消息表 + 定时任务轮询，可靠消息实现分布式事务。
 | 原文链接：http://wiki.083dms.asia/arts/937892.Doc

原标题：Debug：分布式会话时钟不同步令牌提前失效
简介：golang 系统 IO 阻塞 goroutine 场景，理解系统调用阻塞 M，P 会调度其他 M，掌握 go 调度行为。
 | 原文链接：http://wiki.083dms.asia/arts/135024.Doc

原标题：golang 多协程任务池并发控制
简介：接口请求重试容错机制实现，封装请求重试逻辑，遇到临时网络故障自动重试，提升第三方调用稳定性。
 | 原文链接：http://wiki.083dms.asia/arts/845495.Doc

原标题：手写简易 RPC 服务通信原型
简介：golang go yaml 解析自定义类型，yaml 自定义序列化，时间、特殊类型自定义解析逻辑。
 | 原文链接：http://wiki.083dms.asia/arts/712831.Doc

原标题：golang 系统设计监控体系指标分类方法论梳理
简介：golang 日志输出 stdout 标准输出规范，容器环境日志输出到 stdout，由容器平台统一采集日志文件。
 | 原文链接：http://wiki.083dms.asia/arts/528985.Doc

原标题：排错：DockerCompose依赖顺序启动顺序坑
简介：手写简易 MQ 理解消息存储消费，手写极简消息队列 Demo，理解消息存储、投递、消费完整流程。
 | 原文链接：http://wiki.083dms.asia/arts/893316.Doc

原标题：nodejs 单元测试 jest 实操教程
简介：golang redis hash 结构业务实战，使用 Redis Hash 存储对象数据，适合对象字段频繁更新业务场景。
 | 原文链接：http://wiki.083dms.asia/arts/126302.Doc

原标题：Hands‑on：手写简易ORM框架理解底层原理
简介：golang grpc 双向流双向通信开发，grpc 双向流，服务端客户端持续互发消息，长连接流式业务场景。
 | 原文链接：http://wiki.083dms.asia/arts/085265.Doc

原标题：golang 系统设计数据库表设计通用规范模板
简介：golang pdf 生成 go 服务端生成 pdf，服务端动态生成 pdf 报表文件，直接输出下载给到前端。
 | 原文链接：http://wiki.083dms.asia/arts/352075.Doc

原标题：批量异步处理系统业务落地
简介：golang channel 关闭规则与坑点，关闭已经关闭 channel 会 panic，判断 channel 是否关闭正确写法。
 | 原文链接：http://wiki.083dms.asia/arts/806478.Doc

原标题：实践：OpenAPI自动生成接口文档完整实践
简介：golang icmp ping 程序实现，go 实现 ping 工具发送 icmp 报文，检测网络连通性。
 | 原文链接：http://wiki.083dms.asia/arts/952919.Doc

原标题：Git 混乱提交历史清理方法
简介：HTTPS 证书过期更新操作，检测 HTTPS 证书到期，更新证书文件，恢复 HTTPS 服务正常访问。
 | 原文链接：http://wiki.083dms.asia/arts/452850.Doc

原标题：golang 系统设计 rest 版本管理几种方案对比
简介：golang 静态文件服务搭建教程，Go 搭建静态文件服务，托管静态资源，实现文件直接对外访问。
 | 原文链接：http://wiki.083dms.asia/arts/573348.Doc

三、实战开发｜Practice
原标题：golang 系统设计多级缓存更新策略
简介：线程池拒绝策略任务丢失防护，合理设置线程池拒绝策略，处理任务队列满场景，避免业务任务直接丢失。
 | 原文链接：http://wiki.083dms.asia/arts/784217.Doc

原标题：磁盘 inode 耗尽文件创建失败
简介：golang go 泛型实现通用数据结构，泛型实现通用栈队列，复用逻辑支持多种数据类型。
 | 原文链接：http://wiki.083dms.asia/arts/219532.Doc

原标题：设计思考：分布式会话架构选型对比
简介：golang gzip 压缩 http 响应，服务端开启 gzip 压缩，减小接口响应体积，降低网络传输耗时。
 | 原文链接：http://wiki.083dms.asia/arts/418220.Doc

原标题：排错：容器OOM被杀死，日志看不到任何输出
简介：Cookie Session 会话状态管理，讲解 Cookie 与 Session 原理，理解登录状态保存，实现服务端会话管理逻辑。
 | 原文链接：http://wiki.083dms.asia/arts/382773.Doc

原标题：golang redis 过期 key 监听业务
简介：golang go‑fuzz 模糊测试开发，go fuzz 模糊测试，自动构造异常输入，发现代码隐藏 bug。
 | 原文链接：http://wiki.083dms.asia/arts/160336.Doc

原标题：golang 系统设计接口幂等架构设计
简介：golang go test 单元测试命令参数详解，gotest 参数覆盖率，指定测试用例，跳过测试，单元测试命令实操。
 | 原文链接：http://wiki.083dms.asia/arts/696119.Doc

原标题：golang 系统设计接口幂等架构设计
简介：golang redis pipeline 与 txpipeline 区别，区分普通管道与事务管道，根据业务场景选择合适批量执行方案。
 | 原文链接：http://wiki.083dms.asia/arts/837007.Doc

原标题：nodejs 脚手架工具开发完整教程
简介：golang consul 服务发现简单示例，对接 Consul 实现服务注册发现，微服务实例自动感知。
 | 原文链接：http://wiki.083dms.asia/arts/137961.Doc

原标题：nodejs 单元测试 jest 实操教程
简介：Redis 热点 key 拆分降低集群压力，拆分访问量极高的热点 Key，分散请求压力，避免 Redis 节点压力过高。
 | 原文链接：http://wiki.083dms.asia/arts/423926.Doc

原标题：效率笔记：Makefile项目构建脚本编写实践
简介：golang k8s go 服务 yaml 资源编写，k8s 部署 go 应用 deployment service，健康检查资源限制配置。
 | 原文链接：http://wiki.083dms.asia/arts/204759.Doc

原标题：部署复盘：静态资源版本哈希缓存策略
简介：golang sync.Pool 对象池复用对象，sync.Pool 复用临时对象，减少内存分配，降低 GC 频率提升性能。
 | 原文链接：http://wiki.083dms.asia/arts/155717.Doc

原标题：限流组件计数器令牌桶模式实现
简介：nodejs http 服务性能调优实战，调优 Node HTTP 服务内核参数，连接复用，提升接口并发处理能力。
 | 原文链接：http://wiki.083dms.asia/arts/072706.Doc

原标题：DevOps：容器网络模式选型与坑点总结
简介：前端打包分包加载提速方案，前端打包做代码分包，拆分大 bundle，页面按需加载，提升首屏加载速度。
 | 原文链接：http://wiki.083dms.asia/arts/082006.Doc

原标题：方案设计：短链接系统完整架构方案拆解
简介：golang go‑zero 中间件鉴权限流，go‑zero 自定义中间件，实现鉴权、限流、日志打印通用能力。
 | 原文链接：http://wiki.083dms.asia/arts/482785.Doc

原标题：简易网关请求路由过滤模拟
简介：程序日志分级输出规范实践，区分日志等级，规范日志打印内容，合理输出日志，方便线上问题排查定位。
 | 原文链接：http://wiki.083dms.asia/arts/541529.Doc

原标题：性能复盘：GC停顿过长业务卡顿优化记录
简介：golang go mod 私有 git 仓库配置，配置 go mod 拉取私有仓库代码，处理私有模块依赖拉取问题。
 | 原文链接：http://wiki.083dms.asia/arts/223244.Doc

原标题：HelloMarkdown：GitHubMarkdown完整语法速查
简介：浮点计算精度错误处理方案，讲解浮点数计算精度丢失问题，使用合适数据类型，规避金额计算出错。
 | 原文链接：http://wiki.083dms.asia/arts/189982.Doc

原标题：golang html 模板渲染简单示例
简介：全局异常处理器接口返回统一，接入全局异常捕获，拦截业务全部异常，对外输出统一格式返回值。
 | 原文链接：http://wiki.083dms.asia/arts/745823.Doc

原标题：零基础理解读写分离基础思想
简介：git stash 代码暂存切换分支，使用 stash 暂存未提交代码，切换其他分支处理紧急任务，再恢复原有工作进度。
 | 原文链接：http://wiki.083dms.asia/arts/378152.Doc

原标题：前端骨架屏提升页面体验
简介：golang jwt 鉴权中间件完整示例，Gin JWT 鉴权中间件，令牌校验，解析用户信息，接口鉴权拦截。
 | 原文链接：http://wiki.083dms.asia/arts/671844.Doc

原标题：golang 系统设计延迟队列业务实现
简介：golang http 服务优雅关闭完整示例，接收终止信号，停止接收新请求，等待现有请求处理完毕后退出服务。
 | 原文链接：http://wiki.083dms.asia/arts/582440.Doc

原标题：nodejs 全局异常捕获进程防护
简介：接口压测定位系统性能瓶颈，使用压测工具对接口施压，观察指标，定位系统性能瓶颈点。
 | 原文链接：http://wiki.083dms.asia/arts/587660.Doc

原标题：golang 系统设计缓存预热脚本编写实操
简介：nestjs 框架模块化项目搭建，从零搭建 NestJS 项目，模块化拆分业务，搭建规范后端项目骨架。
 | 原文链接：http://wiki.083dms.asia/arts/234119.Doc

原标题：golang 系统设计内部服务链路 trace 传递实现
简介：线上接口超时故障排查思路，从网络、数据库、代码逻辑逐层排查接口超时，定位慢请求根因。
 | 原文链接：http://wiki.083dms.asia/arts/098399.Doc

原标题：安全复盘：日志打印敏感信息泄露治理
简介：golang md5 sha 加密工具实现，实现 MD5、SHA 哈希工具，做数据摘要，用于签名校验场景。
 | 原文链接：http://wiki.083dms.asia/arts/862572.Doc

原标题：Practice：实现异步任务结果查询回调实践
简介：Docker 容器网络不通排查，排查容器网络模式、端口映射、防火墙，解决容器之间、容器外部网络不通。
 | 原文链接：http://wiki.083dms.asia/arts/884350.Doc

原标题：golang 系统设计请求签名校验完整方案
简介：端口占用释放资源重启服务，查找占用端口进程，结束占用进程，释放端口，让服务能够正常启动监听。
 | 原文链接：http://wiki.083dms.asia/arts/941211.Doc

原标题：Practice：实现业务id生成不连续有序ID方案
简介：golang go 依赖漏洞检测 govulncheck，govulncheck 扫描依赖安全漏洞，发现项目供应链风险。
 | 原文链接：http://wiki.083dms.asia/arts/613305.Doc

原标题：golang 系统设计故障演练简单落地思路方法论
简介：golang select 随机分支执行特性，多个 channel 就绪 select 随机选择，理解 select 行为特性。
 | 原文链接：http://wiki.083dms.asia/arts/661631.Doc

原标题：线上故障：消息队列重复消费业务处理异常
简介：golang sync.Map 高并发 map 使用场景，sync.Map 适用场景，读写实操，对比普通 map 加锁性能差异。
 | 原文链接：http://wiki.083dms.asia/arts/826012.Doc

原标题：golang docker 多阶段构建 go 镜像
简介：golang httptest 模拟外部 http 服务，httptest.NewServer 模拟第三方 http 服务，单元测试 mock 外部接口。
 | 原文链接：http://wiki.083dms.asia/arts/562039.Doc

原标题：golang 系统设计 git 工作流本地开发提交流程
简介：golang 内存持续上涨定位思路，区分内存泄漏、缓存占用、GC 参数不合理，分步定位内存持续走高。
 | 原文链接：http://wiki.083dms.asia/arts/578518.Doc

原标题：golang 定时任务 cron 使用指南
简介：golang 分布式追踪全链路日志打印，日志打印 traceId，各个服务日志可串联，排查跨服务调用问题。
 | 原文链接：http://wiki.083dms.asia/arts/822325.Doc

原标题：避坑：CookieSecure属性造成测试环境登录失败
简介：golang 速率限制令牌桶实现，Go 实现令牌桶限流算法，可复用限流器，控制业务调用速率。
 | 原文链接：http://wiki.083dms.asia/arts/080574.Doc

原标题：实战：WebSocket断线重连完整业务处理实践
简介：golang 命令行参数解析开发，解析命令行入参，开发自定义 CLI 程序，读取启动参数配置服务。
 | 原文链接：http://wiki.083dms.asia/arts/805381.Doc

原标题：实践：大文件分片上传后端完整实现思路
简介：轻量 API 后端接口服务快速开发，快速搭建简易 API 服务，实现基础接口能力，快速支撑小型业务需求。
 | 原文链接：http://wiki.083dms.asia/arts/064396.Doc

原标题：预编译 SQL 防注入实现
简介：程序日志分级输出规范实践，区分日志等级，规范日志打印内容，合理输出日志，方便线上问题排查定位。
 | 原文链接：http://wiki.083dms.asia/arts/571381.Doc

原标题：golang 系统设计联合索引设计避坑要点
简介：golang 时间戳秒毫秒纳秒转换，Unix UnixMilli UnixNano 互相转换，区分单位避免时间逻辑 bug。
 | 原文链接：http://wiki.083dms.asia/arts/715380.Doc

原标题：缓存穿透击穿雪崩全套防护
简介：数据库事务 ACID 原理讲解，拆解事务四大特性，理解事务隔离、原子性，明白事务如何保障数据安全。
 | 原文链接：http://wiki.083dms.asia/arts/754012.Doc

原标题：golang rsa 非对称加密签名验签
简介：golang k8s go 服务 yaml 资源编写，k8s 部署 go 应用 deployment service，健康检查资源限制配置。
 | 原文链接：http://wiki.083dms.asia/arts/362774.Doc

四、架构设计｜Architecture
原标题：避坑：请求未设置read超时无限挂起连接
简介：golang goroutine 池任务调度，实现 goroutine 池，复用协程，频繁任务场景减少协程创建销毁开销。
 | 原文链接：http://wiki.083dms.asia/arts/134817.Doc

原标题：线上接口超时故障排查思路
简介：golang csv 读写批量数据处理，Go 读写 CSV 文件，批量导入导出业务数据，处理 CSV 格式解析。
 | 原文链接：http://wiki.083dms.asia/arts/160977.Doc

原标题：快速入门YAML配置文件语法与示例
简介：golang go 泛型使用避坑注意点，泛型与 interface 区别，泛型性能，什么时候适合使用泛型。
 | 原文链接：http://wiki.083dms.asia/arts/022141.Doc

原标题：golang kafka 同步异步消费对比
简介：golang 内存缓存简单实现方案，Go 实现进程内简易内存缓存，本地缓存热点数据，减少远程调用。
 | 原文链接：http://wiki.083dms.asia/arts/195732.Doc

原标题：golang 系统设计数据脱敏架构实现
简介：golang 配置文件多环境加载，Go 多环境配置加载实现，读取配置文件环境变量，适配多套运行环境。
 | 原文链接：http://wiki.083dms.asia/arts/031792.Doc

原标题：部署实践：服务器SSH安全加固配置实践
简介：golang dns 自定义解析器实现，自定义 dns 解析，指定 dns 服务器，控制域名解析逻辑，适配内网环境。
 | 原文链接：http://wiki.083dms.asia/arts/354025.Doc

原标题：golang mysql 避免 select * 查询
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://wiki.083dms.asia/arts/687122.Doc

原标题：golang kafka 核心概念分区副本
简介：golang go 测试文件命名规范，_test.go 测试文件，TestXxx 单元测试函数命名规范。
 | 原文链接：http://wiki.083dms.asia/arts/061601.Doc

原标题：golang git 提交信息规范校验
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://wiki.083dms.asia/arts/811939.Doc

原标题：golang 系统设计网关灰度流量切分简单方案
简介：正则表达式优化 CPU 占满问题，优化正则表达式写法，避免回溯，防止正则运算 CPU 占用 100%。
 | 原文链接：http://wiki.083dms.asia/arts/261817.Doc

原标题：项目实践：多环境配置管理组件设计与实现
简介：golang regexp 正则捕获分组提取数据，正则捕获分组提取子匹配内容，拿到需要业务字段。
 | 原文链接：http://wiki.083dms.asia/arts/570463.Doc

原标题：方案设计：短链接系统完整架构方案拆解
简介：golang 单元测试 table‑driven，表格驱动单元测试写法，批量输入多组测试用例，简化单元测试代码。
 | 原文链接：http://wiki.083dms.asia/arts/766074.Doc

原标题：新手指南：如何读懂开源项目报错日志
简介：Git 误删提交代码恢复找回，使用 Git reflog 工具找回被误删除提交记录，恢复误删除代码。
 | 原文链接：http://wiki.083dms.asia/arts/246372.Doc

原标题：golang gorm 批量插入性能调优
简介：hosts 配置本地回环访问修复，修改 hosts 配置，修复 127.0.0.1 解析异常，本地服务访问失败问题。
 | 原文链接：http://wiki.083dms.asia/arts/281214.Doc

原标题：分布式事务最终一致性实现
简介：golang go 爬虫异步并发抓取，协程池控制并发抓取网页，多协程采集，提升爬虫采集速度。
 | 原文链接：http://wiki.083dms.asia/arts/712384.Doc

原标题：DevOps：环境配置管理区分开发测试生产
简介：golang io.Copy 流式拷贝数据，io.Copy 拷贝 reader 到 writer，不用加载全部数据到内存。
 | 原文链接：http://wiki.083dms.asia/arts/247965.Doc

原标题：排错：多实例部署session共享失效登录失效
简介：从零编写简易 CLI 命令行工具，通过实战案例实现基础命令交互，理解命令行程序执行逻辑，产出可运行小工具。
 | 原文链接：http://wiki.083dms.asia/arts/657730.Doc

原标题：开发记录：日志脱敏防止敏感信息输出实践
简介：golang udp 服务端客户端开发示例，golang 实现 UDP 服务收发数据包，实现 udp 协议通信程序。
 | 原文链接：http://wiki.083dms.asia/arts/957900.Doc

?
