最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Architecture：链路追踪架构核心组件与埋点
简介：跨域偶现失败配置修复，解决跨域问题时而复现时而正常，定位配置漏配、请求头异常等隐性问题。
 | 原文链接：http://book.mfrftk.asia/blog/1012793.sHtMl

原标题：时间同步修复令牌提前过期
简介：golang 信号触发配置重载实践，收到 SIGUSR1 信号重新加载配置，线上无需重启刷新配置。
 | 原文链接：http://book.mfrftk.asia/blog/5280384.sHtMl

原标题：golang goroutine 池任务调度
简介：golang http 服务优雅关闭完整示例，接收终止信号，停止接收新请求，等待现有请求处理完毕后退出服务。
 | 原文链接：http://book.mfrftk.asia/blog/5545381.sHtMl

原标题：Practice：实现数据库连接池简易模拟实现
简介：golang 速率限制令牌桶实现，Go 实现令牌桶限流算法，可复用限流器，控制业务调用速率。
 | 原文链接：http://book.mfrftk.asia/blog/1787513.sHtMl

原标题：前端虚拟列表大数据渲染优化
简介：业务幂等键设计防重复逻辑，讲解幂等键设计思路，选择合适业务字段作为幂等标识，实现可靠防重复。
 | 原文链接：http://book.mfrftk.asia/blog/8442111.sHtMl

原标题：Practice：实现定时任务动态启停管理接口
简介：golang go 代码覆盖率线上统计，单元测试覆盖率统计，找出未测试代码分支，提升测试质量。
 | 原文链接：http://book.mfrftk.asia/blog/6372393.sHtMl

原标题：golang k8s 基础概念 pod deployment
简介：多套环境灵活切换配置方案，实现配置动态切换，通过环境变量、配置文件，快速切换开发测试生产环境。
 | 原文链接：http://book.mfrftk.asia/blog/6248905.sHtMl

原标题：方案设计：短链接系统完整架构方案拆解
简介：golang jwt jwk 公钥验证令牌，使用 jwk 公钥校验 jwt，非对称方式签发校验令牌，提升安全性。
 | 原文链接：http://book.mfrftk.asia/blog/2800129.sHtMl

原标题：快速入门OpenAPI文档生成基础实践
简介：内网 DNS 不稳定随机报错排查，定位内网 DNS 抖动问题，配置备选 DNS，解决偶现域名解析失败。
 | 原文链接：http://book.mfrftk.asia/blog/9657923.sHtMl

原标题：golang 令牌桶限流中间件 gin
简介：golang interface {} 类型断言类型转换，类型断言 ok 模式，避免断言失败触发 panic。
 | 原文链接：http://book.mfrftk.asia/blog/3059295.sHtMl

原标题：百万数据 Excel 导出内存优化
简介：golang sync.Once 只执行一次，sync.Once 做单例初始化，保证代码只执行一次，并发安全。
 | 原文链接：http://book.mfrftk.asia/blog/3742636.sHtMl

原标题：golang 系统设计内部服务调用超时设置要点
简介：端口占用释放资源重启服务，查找占用端口进程，结束占用进程，释放端口，让服务能够正常启动监听。
 | 原文链接：http://book.mfrftk.asia/blog/7027011.sHtMl

原标题：部署复盘：金丝雀发布流量切分实操方案
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：http://book.mfrftk.asia/blog/8349946.sHtMl

原标题：golang 系统设计回调异步处理防止超时阻塞
简介：golang 容器信号转发处理问题修复，docker/k8s 正确转发 SIGTERM 信号，保证 go 程序收到信号优雅退出。
 | 原文链接：http://book.mfrftk.asia/blog/3501900.sHtMl

原标题：golang k8s 网络策略网络隔离设置
简介：golang 内存 dump 线上堆快照采集，线上生成内存 dump 文件，线下分析，定位内存泄漏问题。
 | 原文链接：http://book.mfrftk.asia/blog/1591011.sHtMl

原标题：线上故障：Redis内存淘汰策略错误数据丢失
简介：golang go 项目依赖冲突解决完整思路，定位冲突包，replace、exclude、升级降级解决版本冲突。
 | 原文链接：http://book.mfrftk.asia/blog/7198248.sHtMl

原标题：golang docker 部署 es 本地开发
简介：golang docker 多阶段构建 go 镜像，Go 项目 Docker 多阶段构建，编译与运行阶段分离，大幅度缩减最终镜像体积，提升镜像分发效率。
 | 原文链接：http://book.mfrftk.asia/blog/8859856.sHtMl

原标题：golang grafana 监控面板简单配置
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://book.mfrftk.asia/blog/2028701.sHtMl

原标题：效率笔记：gitlog高效查询历史提交技巧
简介：golang validator 自定义校验规则，Gin Validator 自定义校验器，实现业务特殊参数校验逻辑。
 | 原文链接：http://book.mfrftk.asia/blog/5378080.sHtMl

原标题：安全笔记：CORS跨域配置错误安全风险
简介：CI 构建缓存加速编译速度，开启 CI 流水线依赖缓存，复用上一次构建依赖包，缩短流水线构建耗时。
 | 原文链接：http://book.mfrftk.asia/blog/5164597.sHtMl

原标题：Docker 容器网络不通排查
简介：golang net/url 路径拼接处理，url.ParseRequestURI 处理请求 url，正确拼接 url 路径避免拼接错误。
 | 原文链接：http://book.mfrftk.asia/blog/7199426.sHtMl

原标题：golang 数据库批量更新性能优化
简介：express 请求参数校验处理，接入参数校验库，校验入参，拦截非法参数，提前拦截错误请求。
 | 原文链接：http://book.mfrftk.asia/blog/9027728.sHtMl

原标题：前端骨架屏提升页面体验
简介：golang netlink 系统信息获取，netlink 获取系统网络信息，网卡地址，内核网络状态读取。
 | 原文链接：http://book.mfrftk.asia/blog/7429882.sHtMl

原标题：零基础理解前后端简单交互流程
简介：批量异步处理系统业务落地，构建批量异步处理系统，把耗时业务异步化，提升接口响应速度。
 | 原文链接：http://book.mfrftk.asia/blog/7475965.sHtMl

原标题：入门实践：搭建简单的热更新开发环境
简介：大事务拆分防止连接池耗尽，将执行时间很长的大事务拆分为小事务，减少事务占用连接时长。
 | 原文链接：http://book.mfrftk.asia/blog/9542319.sHtMl

原标题：nodejs 消息队列消费服务开发
简介：golang 静态文件服务搭建教程，Go 搭建静态文件服务，托管静态资源，实现文件直接对外访问。
 | 原文链接：http://book.mfrftk.asia/blog/5166128.sHtMl

原标题：﻿【GettingStarted】从零搭建本地开发环境完整指南
简介：RPC 接口字段增减兼容处理，RPC 接口新增删除字段做好向前兼容，老版本服务不会解析报错崩溃。
 | 原文链接：http://book.mfrftk.asia/blog/3540312.sHtMl

原标题：设计思考：API网关和BFF职责边界划分
简介：新手参与开源社区贡献指南，介绍开源社区基础规则，讲解阅读 issue、提交 PR 流程，指导开发者参与开源贡献。
 | 原文链接：http://book.mfrftk.asia/blog/0477729.sHtMl

原标题：从零编写简易 CLI 命令行工具
简介：golang channel 缓冲无缓冲区别，缓冲 channel 与无缓冲 channel，底层行为差异业务选型参考。
 | 原文链接：http://book.mfrftk.asia/blog/1958935.sHtMl

原标题：数据库分表存储大表优化方案
简介：golang goroutine 泄露检测告警实现，监控 goroutine 数量，突增触发告警，提早发现协程泄露。
 | 原文链接：http://book.mfrftk.asia/blog/4827636.sHtMl

原标题：多套环境灵活切换配置方案
简介：空指针异常判空容错处理，讲解空指针产生场景，规范判空逻辑，增加容错，避免空指针直接造成程序崩溃。
 | 原文链接：http://book.mfrftk.asia/blog/8107592.sHtMl

原标题：golang 项目环境变量加载方案
简介：golang wasm 性能优化与内存管理，wasm 内存分配释放，减少内存拷贝，优化浏览器端性能。
 | 原文链接：http://book.mfrftk.asia/blog/7580267.sHtMl

原标题：golang 系统设计重试退避策略业务落地
简介：golang 半关闭 tcp 连接 shutdown，tcp 连接 shutdown 半关闭，单向关闭读或者写，理解 tcp 关闭流程。
 | 原文链接：http://book.mfrftk.asia/blog/8466248.sHtMl

原标题：golang 系统设计配置回滚版本历史记录实现
简介：golang tar gz 压缩解压处理，tar.gz 归档压缩解压，服务端日志备份、文件打包场景使用。
 | 原文链接：http://book.mfrftk.asia/blog/3177428.sHtMl

原标题：设计实践：如何设计可扩展业务数据库表结构
简介：golang http 重定向策略自定义，CheckRedirect 自定义重定向逻辑，限制重定向次数，防止死循环。
 | 原文链接：http://book.mfrftk.asia/blog/6782546.sHtMl

原标题：golang base64 编码解码实操
简介：golang init 函数合理使用边界，少用 init，优先显式调用初始化，便于控制初始化时机。
 | 原文链接：http://book.mfrftk.asia/blog/7789154.sHtMl

原标题：方案对比：单体、微服务、模块化单体取舍
简介：磁盘占满服务不可用清理方案，定位磁盘占用大文件，清理日志、缓存文件，恢复磁盘可用空间。
 | 原文链接：http://book.mfrftk.asia/blog/3088760.sHtMl

原标题：golang 系统设计集成测试环境准备清理实操
简介：golang go cover 覆盖率报告生成，go test‑cover 生成测试覆盖率，html 可视化查看未覆盖代码行。
 | 原文链接：http://book.mfrftk.asia/blog/2525465.sHtMl

原标题：实战项目：数据导出Excel百万级大数据导出方案
简介：golang go 终端 pty 伪终端操作，pty 启动子进程，模拟终端交互，实现交互式命令调用。
 | 原文链接：http://book.mfrftk.asia/blog/2637012.sHtMl

原标题：Practice：实现文件监控自动重启开发服务工具
简介：nodejs 跨域中间件配置细节，Express 跨域中间件配置细节，处理预检请求，修复偶现跨域失效。
 | 原文链接：http://book.mfrftk.asia/blog/3741147.sHtMl


二、踩坑排错｜Troubleshooting
原标题：golang 系统设计请求签名校验完整方案
简介：golang 负载均衡轮询加权轮询实现，手写负载均衡算法，轮询、加权轮询分发请求到后端节点。
 | 原文链接：http://book.mfrftk.asia/blog/3108680.sHtMl

原标题：golang 分布式锁 redis 实现
简介：前后端会话登录状态持久化，实现登录状态持久存储，重启服务登录状态不丢失，保障会话稳定性。
 | 原文链接：http://book.mfrftk.asia/blog/6003855.sHtMl

原标题：零基础理解缓存基础原理与简单使用
简介：golang viper 多源配置管理实操，viper 读取配置文件环境变量命令行参数，多源配置优先级管理。
 | 原文链接：http://book.mfrftk.asia/blog/2022717.sHtMl

原标题：CI 流水线构建失败日志排查
简介：golang mqtt 客户端 go 开发物联网，paho.mqtt.golang 实现 mqtt 客户端，物联网设备消息收发。
 | 原文链接：http://book.mfrftk.asia/blog/2357633.sHtMl

原标题：实战项目：容器健康探针配置完整实践示例
简介：golang gin 框架接口开发实战，Gin 框架搭建 HTTP 服务，开发增删改查接口，快速完成后端接口开发。
 | 原文链接：http://book.mfrftk.asia/blog/5549441.sHtMl

原标题：排错：CI流水线构建失败，日志无明确报错
简介：并发数据覆盖加锁安全处理，多线程并发修改同一数据，增加锁机制，防止并发覆盖丢失更新数据。
 | 原文链接：http://book.mfrftk.asia/blog/0992837.sHtMl

原标题：编译打包产物依赖分析解读
简介：golang go mod replace 本地模块替换，replace 替换模块为本地目录，修改第三方库本地调试。
 | 原文链接：http://book.mfrftk.asia/blog/5842156.sHtMl

原标题：架构笔记：任务调度系统架构设计与可靠性
简介：golang trace 可视化分析协程阻塞，使用 trace 网页 UI，定位协程阻塞、系统调用阻塞、锁等待。
 | 原文链接：http://book.mfrftk.asia/blog/8036831.sHtMl

原标题：坑点：环境配置写死代码，上线忘记修改
简介：百万数据 Excel 导出内存优化，优化大 Excel 导出逻辑，流式输出，避免一次性加载全部数据造成 OOM。
 | 原文链接：http://book.mfrftk.asia/blog/0369494.sHtMl

原标题：Architecture：服务注册发现架构原理与选型
简介：服务健康检查监控接口开发，开发健康检查接口，反馈服务运行状态，供编排工具监控服务存活状态。
 | 原文链接：http://book.mfrftk.asia/blog/7018687.sHtMl

原标题：golang 系统设计契约测试接口兼容性保障思路
简介：本地数据库开发环境搭建指南，讲解数据库安装配置、账号权限设置、连接测试，快速搭建用于开发调试的数据库实例。
 | 原文链接：http://book.mfrftk.asia/blog/6413299.sHtMl

原标题：OOMKilled 容器被杀完整排查
简介：golang 数据库连接池泄露检测逻辑，监控连接池状态，检测连接长时间未归还，告警连接泄漏问题。
 | 原文链接：http://book.mfrftk.asia/blog/6958035.sHtMl

原标题：灰度发布策略服务平滑升级
简介：前端静态缓存更新生效处理，修改静态资源版本标识，处理浏览器强缓存，让更新资源生效。
 | 原文链接：http://book.mfrftk.asia/blog/8832421.sHtMl

原标题：快速启动：本地运行开源项目排障清单
简介：前端组件库按需加载性能优化，配置组件库按需引入，避免引入全部组件，减少打包产物体积。
 | 原文链接：http://book.mfrftk.asia/blog/3910709.sHtMl

原标题：golang excel 简单读写操作示例
简介：golang proto 可选字段处理方案，protobuf 可选字段正确判断，区分未赋值与零值，业务逻辑不出现偏差。
 | 原文链接：http://book.mfrftk.asia/blog/0456755.sHtMl

原标题：服务健康检查告警监控体系
简介：数据库主从延迟业务兼容处理，业务适配主从复制延迟，避免读取从库拿到还未同步完成旧数据。
 | 原文链接：http://book.mfrftk.asia/blog/1975424.sHtMl

原标题：golang 系统设计重试退避策略业务落地
简介：异步异常捕获避免进程崩溃，捕获异步代码内部抛出异常，防止未捕获异常直接导致整个进程退出。
 | 原文链接：http://book.mfrftk.asia/blog/2788894.sHtMl

原标题：golang 系统设计大流量削峰处理方案
简介：golang go http 安全头配置实践，设置 http 安全响应头，防范 XSS、点击劫持，提升 web 服务安全性。
 | 原文链接：http://book.mfrftk.asia/blog/6944194.sHtMl

原标题：golang 系统设计 api 网关核心能力完整梳理
简介：多套环境灵活切换配置方案，实现配置动态切换，通过环境变量、配置文件，快速切换开发测试生产环境。
 | 原文链接：http://book.mfrftk.asia/blog/3036343.sHtMl

原标题：Issue：文件句柄耗尽，服务缓慢卡死复盘
简介：golang proto 可选字段处理方案，protobuf 可选字段正确判断，区分未赋值与零值，业务逻辑不出现偏差。
 | 原文链接：http://book.mfrftk.asia/blog/8727161.sHtMl

原标题：golang 文件上传下载接口开发
简介：静态资源 404 路径打包修复，修复打包后静态资源访问 404，调整资源输出路径，保证资源正常加载。
 | 原文链接：http://book.mfrftk.asia/blog/0850449.sHtMl

原标题：golang 系统设计 protobuf json 性能对比
简介：golang dns 自定义解析器实现，自定义 dns 解析，指定 dns 服务器，控制域名解析逻辑，适配内网环境。
 | 原文链接：http://book.mfrftk.asia/blog/2015669.sHtMl

原标题：golang 简易埋点日志上报实现
简介：K8s 镜像拉取网络故障修复，排查 K8s 集群镜像拉取网络问题，配置镜像源，恢复镜像正常拉取。
 | 原文链接：http://book.mfrftk.asia/blog/7592910.sHtMl

原标题：快速入门简单签名校验实现思路
简介：CORS 跨域问题多种解决方案，对比 CORS、代理等不同跨域方案优缺点，根据业务场景选择合适的跨域处理方式。
 | 原文链接：http://book.mfrftk.asia/blog/8951552.sHtMl

原标题：golang 开发环境快速搭建指南
简介：Fork 开源项目同步上游代码，Fork 开源仓库之后，配置上游源，同步官方最新代码，保持代码版本对齐。
 | 原文链接：http://book.mfrftk.asia/blog/7191557.sHtMl

原标题：Troubleshooting：依赖安装失败完整排查清单
简介：golang go 网络编程 net 包基础，net 包 tcp udp socket 编程，监听接收连接，读写数据。
 | 原文链接：http://book.mfrftk.asia/blog/8388007.sHtMl

原标题：动态定时任务业务调度实现
简介：golang go 符号表与调试信息取舍，区分生产环境调试符号取舍，平衡镜像体积与故障排查能力。
 | 原文链接：http://book.mfrftk.asia/blog/1170791.sHtMl

原标题：Docker Compose 一键搭建本地栈
简介：golang rsa 公钥加密私钥解密，rsa 非对称加密，大文件分块加密，处理非对称加密长度限制。
 | 原文链接：http://book.mfrftk.asia/blog/2218739.sHtMl

原标题：架构笔记：冷热数据分离架构设计与迁移
简介：golang html 模板防 xss 自动转义，理解 go html/template 自动转义，防止 XSS 攻击，处理不需要转义场景。
 | 原文链接：http://book.mfrftk.asia/blog/6934510.sHtMl

原标题：架构复盘：消息队列在业务系统中边界与最佳实践
简介：特殊输入字符过滤解析防护，过滤用户输入特殊字符，防止解析报错，规避恶意字符带来业务异常。
 | 原文链接：http://book.mfrftk.asia/blog/3556606.sHtMl

原标题：容器资源限制防止宿主机过载
简介：pnpm 包管理工具实战避坑指南，使用 pnpm 管理项目依赖，梳理常见坑点，充分利用 pnpm 优势。
 | 原文链接：http://book.mfrftk.asia/blog/6111246.sHtMl

原标题：Security：RPC调用身份认证安全加固
简介：golang go 项目工程目录布局标准，不同规模 go 项目目录结构，小型项目中型项目大型微服务项目布局。
 | 原文链接：http://book.mfrftk.asia/blog/2759196.sHtMl

原标题：架构复盘：热点数据防护架构防止节点过载
简介：消息消费重试次数限制防爆炸，限制消息最大重试次数，防止失败消息无限重试造成消息爆炸堆积。
 | 原文链接：http://book.mfrftk.asia/blog/1952593.sHtMl

原标题：Troubleshooting：WSL文件权限问题大量踩坑
简介：golang map 并发读写 panic 解决方案，map 非并发安全，讲解加锁、sync.map 方案解决并发读写崩溃。
 | 原文链接：http://book.mfrftk.asia/blog/8348572.sHtMl

原标题：排错：macOS权限保护导致脚本执行被拦截
简介：golang http cookie jar 会话处理，客户端 cookie jar 自动管理 cookie，处理登录态会话。
 | 原文链接：http://book.mfrftk.asia/blog/8316398.sHtMl

原标题：golang redis pipeline 原子性说明
简介：golang 数据库连接池泄露检测逻辑，监控连接池状态，检测连接长时间未归还，告警连接泄漏问题。
 | 原文链接：http://book.mfrftk.asia/blog/1558103.sHtMl

原标题：排坑：Git提交历史混乱，如何清理错误提交
简介：golang 互斥锁读写锁并发安全，互斥锁读写锁实操，保护共享变量，解决多协程并发读写数据竞争。
 | 原文链接：http://book.mfrftk.asia/blog/0830018.sHtMl

原标题：HelloShell：入门常用shell脚本编写
简介：线程池拒绝策略任务丢失防护，合理设置线程池拒绝策略，处理任务队列满场景，避免业务任务直接丢失。
 | 原文链接：http://book.mfrftk.asia/blog/9566787.sHtMl

原标题：golang k8s liveness readiness 探针
简介：golang 钉钉企业微信告警消息推送，go 调用企业微信钉钉接口，推送告警通知、业务消息。
 | 原文链接：http://book.mfrftk.asia/blog/1628056.sHtMl

原标题：golang 系统设计 canary 金丝雀部署实操
简介：API 接口调试与异常处理实战，覆盖接口请求、参数组装、错误捕获，提供调试思路，高效定位接口返回异常问题。
 | 原文链接：http://book.mfrftk.asia/blog/3503701.sHtMl

三、实战开发｜Practice
原标题：Architecture：API设计RESTful最佳实践与反模式
简介：golang delve 远程调试 go 线上程序，delve 远程调试，线上环境附加进程调试排查线上 bug。
 | 原文链接：http://book.mfrftk.asia/blog/5386643.sHtMl

原标题：Debug：网关超时时间小于后端接口超时设置
简介：golang 优雅处理数据库事务，Go 数据库事务封装，正确处理事务提交回滚，保证业务数据一致性。
 | 原文链接：http://book.mfrftk.asia/blog/8610735.sHtMl

原标题：golang redis stream 消息队列实践
简介：golang rsa 公钥加密私钥解密，rsa 非对称加密，大文件分块加密，处理非对称加密长度限制。
 | 原文链接：http://book.mfrftk.asia/blog/2436045.sHtMl

原标题：golang 系统设计配置回滚版本历史记录实现
简介：golang accept 错误循环崩溃处理，accept 返回系统错误，处理临时错误，避免死循环占满 CPU。
 | 原文链接：http://book.mfrftk.asia/blog/7248181.sHtMl

原标题：golang 系统设计 k8s 集群安全配置梳理
简介：golang 优雅处理数据库事务，Go 数据库事务封装，正确处理事务提交回滚，保证业务数据一致性。
 | 原文链接：http://book.mfrftk.asia/blog/1623349.sHtMl

原标题：golang 信号捕获程序退出处理
简介：golang defer 执行顺序与坑点，defer 后进先出，循环内部 defer 陷阱，资源释放正确写法。
 | 原文链接：http://book.mfrftk.asia/blog/1906010.sHtMl

原标题：Security：限流防爬虫防恶意攻击防护体系
简介：golang mqtt 客户端 go 开发物联网，paho.mqtt.golang 实现 mqtt 客户端，物联网设备消息收发。
 | 原文链接：http://book.mfrftk.asia/blog/1903750.sHtMl

原标题：golang 系统设计 debug 远程调试 go 程序实操
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://book.mfrftk.asia/blog/1264989.sHtMl

原标题：开发记录：搭建CI/CD流水线自动构建部署项目
简介：golang gorm 事务手动回滚提交，手动控制事务流程，业务异常主动回滚，保障数据操作原子性。
 | 原文链接：http://book.mfrftk.asia/blog/9950086.sHtMl

原标题：DevOps：Docker镜像优化，减小镜像体积实践
简介：react 状态管理方案选型对比，对比 Redux、Zustand 等 React 状态管理库，分析适用业务场景辅助选型。
 | 原文链接：http://book.mfrftk.asia/blog/4225053.sHtMl

原标题：零基础理解读写分离基础思想
简介：golang context.WithTimeout 超时上下文，WithTimeout 设置超时时间，超时自动 cancel 释放协程。
 | 原文链接：http://book.mfrftk.asia/blog/5523456.sHtMl

原标题：业务错误码体系设计方案
简介：分布式 ID 全局唯一生成方案，讲解分布式 ID 生成思路，实现全局唯一 ID，满足分布式系统主键生成需求。
 | 原文链接：http://book.mfrftk.asia/blog/1961842.sHtMl

原标题：设计思考：分布式系统时钟同步带来的架构问题
简介：后端大文件分片上传接口开发，开发后端分片上传接口，接收分片，合并分片完成大文件存储。
 | 原文链接：http://book.mfrftk.asia/blog/1849109.sHtMl

原标题：golang 系统设计开源 pr 评审合并流程实操
简介：golang k8s 客户端 client‑go 简单示例，client‑go 操作 k8s 资源，增删改查 pod deployment 等资源对象。
 | 原文链接：http://book.mfrftk.asia/blog/3689235.sHtMl

原标题：Hands‑on：简易验证码生成校验后端实践
简介：golang go 并发模式 fan‑out fan‑in，fanout 分发任务 fanin 汇总结果，多协程并发处理任务。
 | 原文链接：http://book.mfrftk.asia/blog/0512462.sHtMl

原标题：golang 系统设计第三方调用超时重试熔断
简介：golang jwt 令牌刷新逻辑实现，实现 JWT 双令牌机制，access 短期有效 refresh 刷新令牌，实现无感续期登录。
 | 原文链接：http://book.mfrftk.asia/blog/6957648.sHtMl

原标题：Troubleshoot：DNS解析异常导致第三方调用失败
简介：限流组件计数器令牌桶模式实现，实现计数器、令牌桶两种限流算法，封装可复用限流组件。
 | 原文链接：http://book.mfrftk.asia/blog/5617010.sHtMl

原标题：快速入门容器基础概念，理解镜像与容器
简介：nodejs 进程间通信 IPC 实操，演示 Node.js 主进程子进程 IPC 通信，进程之间传递消息数据。
 | 原文链接：http://book.mfrftk.asia/blog/2247037.sHtMl

原标题：新手教程：Gittag版本标签打标签实操
简介：golang https 客户端跳过证书校验，开发测试环境跳过 tls 证书校验，仅用于内网测试禁止生产使用。
 | 原文链接：http://book.mfrftk.asia/blog/2977904.sHtMl

原标题：实战：Redis管道批量操作性能优化实践
简介：前端打包产物体积压缩优化，多手段压缩前端打包产物，移除无用代码，压缩资源，提升页面加载速度。
 | 原文链接：http://book.mfrftk.asia/blog/8649795.sHtMl

原标题：效率笔记：终端开发工具提升日常调试效率
简介：golang errors.Is errors.As 错误判断，判断是否为指定错误类型，提取自定义错误信息，错误处理进阶。
 | 原文链接：http://book.mfrftk.asia/blog/2721063.sHtMl

原标题：Troubleshoot：跨库关联查询，性能急剧恶化
简介：定时任务周期调度 demo 开发，实现简单定时调度程序，按时间周期执行业务逻辑，理解定时任务运行机制。
 | 原文链接：http://book.mfrftk.asia/blog/9626910.sHtMl

原标题：效率笔记：Makefile项目构建脚本编写实践
简介：golang go 项目 CI github actions 配置，github actions 实现 go 项目 ci，自动测试、代码检查、编译打包镜像。
 | 原文链接：http://book.mfrftk.asia/blog/3404733.sHtMl

原标题：nodejs http 服务性能调优实战
简介：golang word 文档生成处理 go 方案，go 生成 word 文档报表，填充文本表格，输出 docx 文件。
 | 原文链接：http://book.mfrftk.asia/blog/9183365.sHtMl

原标题：分布式锁失效问题排查修复
简介：golang httptest 模拟外部 http 服务，httptest.NewServer 模拟第三方 http 服务，单元测试 mock 外部接口。
 | 原文链接：http://book.mfrftk.asia/blog/2210017.sHtMl

原标题：golang context 上下文传参讲解
简介：golang go xml 解析生成 xml 文档，encoding/xml 解析 xml，结构体标签映射 xml 节点属性。
 | 原文链接：http://book.mfrftk.asia/blog/0424801.sHtMl

原标题：入门实践：实现简单文件读写功能
简介：golang redis bitmap 位图业务实战，bitmap 做签到统计、用户状态标记，节省大量内存空间。
 | 原文链接：http://book.mfrftk.asia/blog/0942622.sHtMl

原标题：踩坑：大报文传输，RPC消息超过大小限制
简介：golang nil channel 阻塞特性，nil channel 读写永久阻塞，理解 nil channel 行为做逻辑控制。
 | 原文链接：http://book.mfrftk.asia/blog/6158942.sHtMl

原标题：新手快速上手 Git 版本控制实操指南
简介：golang context 上下文传参讲解，讲解 Context 使用场景，传递元数据、控制协程超时取消，规范协程控制。
 | 原文链接：http://book.mfrftk.asia/blog/3495024.sHtMl

原标题：运维笔记：服务器日志轮转logrotate配置
简介：ICMP 放通网络丢包问题修复，放开 ICMP 协议，解决 MTU 问题导致网络丢包，修复网络不稳定现象。
 | 原文链接：http://book.mfrftk.asia/blog/6461687.sHtMl

原标题：方案设计：异步解耦业务架构边界识别
简介：golang go select 多路等待 channel，select 等待多个 channel，default 非阻塞，超时等待 channel。
 | 原文链接：http://book.mfrftk.asia/blog/0438020.sHtMl

原标题：golang 系统设计请求签名校验完整方案
简介：移动端适配 rem vw 方案对比，对比 rem 与 vw 移动端适配方案，分析优缺点，给出选型建议。
 | 原文链接：http://book.mfrftk.asia/blog/0166075.sHtMl

原标题：避坑：请求未设置read超时无限挂起连接
简介：golang 雪花 id 重复问题排查，排查雪花算法 ID 重复问题，时钟回拨、机器 ID 冲突，给出修复方案。
 | 原文链接：http://book.mfrftk.asia/blog/5930647.sHtMl

原标题：入门实践：搭建简单的热更新开发环境
简介：Shell 运维脚本服务器效率提升，编写常用运维 Shell 脚本，自动化服务器运维操作，减少手工重复工作。
 | 原文链接：http://book.mfrftk.asia/blog/7865389.sHtMl

原标题：架构复盘：消息队列在业务系统中边界与最佳实践
简介：日志驱动异常日志不输出修复，排查日志驱动配置，修复日志写入配置，恢复程序正常日志输出。
 | 原文链接：http://book.mfrftk.asia/blog/0535510.sHtMl

原标题：分布式任务调度集群原型开发
简介：golang 压缩 zip 文件生成解压，golang 实现 zip 压缩打包，解压 zip 归档文件，处理批量文件归档。
 | 原文链接：http://book.mfrftk.asia/blog/2045383.sHtMl

原标题：性能复盘：慢查询日积月累拖垮数据库优化
简介：golang init 函数合理使用边界，少用 init，优先显式调用初始化，便于控制初始化时机。
 | 原文链接：http://book.mfrftk.asia/blog/7533462.sHtMl

原标题：Hands‑on：本地模拟分布式锁失效场景测试
简介：手写简易 MQ 理解消息存储消费，手写极简消息队列 Demo，理解消息存储、投递、消费完整流程。
 | 原文链接：http://book.mfrftk.asia/blog/1923890.sHtMl

原标题：从零编写简易 CLI 命令行工具
简介：golang go 比较运算符可比较类型，哪些类型可以直接 == 比较，map slice 函数不可直接比较。
 | 原文链接：http://book.mfrftk.asia/blog/3687780.sHtMl

原标题：实战项目：前端资源打包体积优化完整实操
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://book.mfrftk.asia/blog/4860645.sHtMl

四、架构设计｜Architecture
原标题：调优方案：服务实例扩容，水平扩展性能
简介：本地运行正常线上报错排查，对比本地与线上环境差异，从配置、系统版本、文件权限定位线上独有的 bug。
 | 原文链接：http://book.mfrftk.asia/blog/6704425.sHtMl

原标题：golang 日志脱敏敏感字段过滤
简介：golang 分布式锁防死锁实现要点，锁超时、续期、锁持有者校验，避免锁死锁，保障分布式锁可靠性。
 | 原文链接：http://book.mfrftk.asia/blog/6254761.sHtMl

原标题：golang 系统设计 rest 资源命名规范汇总
简介：golang gin 路由分组权限管控，Gin 路由分组，不同分组绑定鉴权中间件，实现接口权限分组管控。
 | 原文链接：http://book.mfrftk.asia/blog/1514505.sHtMl

原标题：Hands‑on：简易图片压缩处理服务demo
简介：golang errors.Is errors.As 错误判断，判断是否为指定错误类型，提取自定义错误信息，错误处理进阶。
 | 原文链接：http://book.mfrftk.asia/blog/7199354.sHtMl

原标题：快速入门YAML配置文件语法与示例
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://book.mfrftk.asia/blog/9600025.sHtMl

原标题：Architecture：文件处理服务架构大文件内存规避
简介：golang rsa 签名验签 pem 证书加载，加载 pem 格式密钥证书，rsa 签名与验签完整业务实现。
 | 原文链接：http://book.mfrftk.asia/blog/3903497.sHtMl

原标题：golang 系统设计 protobuf 枚举类型规范写法
简介：golang 优雅停机服务关闭实现，监听系统信号，关闭服务等待请求处理完毕，实现 Go 服务优雅停机。
 | 原文链接：http://book.mfrftk.asia/blog/9247658.sHtMl

原标题：golang 系统设计内部服务链路 trace 传递实现
简介：服务器时钟同步任务错乱修复，配置服务器 NTP 时间同步，保证集群所有机器时间保持一致。
 | 原文链接：http://book.mfrftk.asia/blog/3788695.sHtMl

原标题：Architecture：中小型后端服务整体架构设计复盘
简介：序列化版本不一致解析失败，保证序列化对象版本对齐，修复版本不匹配导致对象反序列化失败。
 | 原文链接：http://book.mfrftk.asia/blog/6404499.sHtMl

原标题：多版本开发环境共存配置
简介：Git 误删提交代码恢复找回，使用 Git reflog 工具找回被误删除提交记录，恢复误删除代码。
 | 原文链接：http://book.mfrftk.asia/blog/5459730.sHtMl

原标题：golang k8s 持久化 pv pvc 使用实操
简介：eslint prettier 代码规范落地，配置 eslint 与 prettier，做代码检查格式化，统一前端团队代码风格。
 | 原文链接：http://book.mfrftk.asia/blog/4170608.sHtMl

原标题：golang 系统设计依赖版本升级风险评估
简介：golang 日志 zap 结构化日志实践，接入 Zap 结构化日志库，打印结构化日志，方便日志检索解析。
 | 原文链接：http://book.mfrftk.asia/blog/1848384.sHtMl

原标题：代码格式化工具团队统一风格
简介：golang init 函数合理使用边界，少用 init，优先显式调用初始化，便于控制初始化时机。
 | 原文链接：http://book.mfrftk.asia/blog/8603079.sHtMl

原标题：项目实践：OpenTelemetry链路追踪本地部署实践
简介：golang net/url 路径拼接处理，url.ParseRequestURI 处理请求 url，正确拼接 url 路径避免拼接错误。
 | 原文链接：http://book.mfrftk.asia/blog/7198150.sHtMl

原标题：实战项目：本地模拟磁盘IO高负载观察服务行为
简介：WSL 文件权限访问异常修复，处理 WSL 环境文件权限错乱，调整权限配置，实现文件正常读写访问。
 | 原文链接：http://book.mfrftk.asia/blog/3895492.sHtMl

原标题：golang 系统设计灰度发布实现思路
简介：golang go‑zero 框架项目快速搭建，go‑zero 脚手架生成微服务项目，api rpc 服务快速开发。
 | 原文链接：http://book.mfrftk.asia/blog/8379983.sHtMl

原标题：项目实践：幂等表实现接口幂等业务实践
简介：golang loki 日志收集 go 服务集成，日志输出适配 loki，标签携带 traceId，日志集中检索排查问题。
 | 原文链接：http://book.mfrftk.asia/blog/4461372.sHtMl

原标题：Git 代码冲突正确处理方式
简介：golang 大文件读取内存优化，Go 流式读取大文件，分块处理，避免大文件一次性加载全部到内存。
 | 原文链接：http://book.mfrftk.asia/blog/3130133.sHtMl

?
