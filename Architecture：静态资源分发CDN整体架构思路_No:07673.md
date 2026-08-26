最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Architecture：静态资源分发CDN整体架构思路
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://book.xdpa0b.asia/blog/353951.Doc

原标题：避坑：请求未设置read超时无限挂起连接
简介：golang staticcheck 静态代码分析，staticcheck 深度静态检查，发现代码错误、性能问题、风格问题。
 | 原文链接：http://book.xdpa0b.asia/blog/728292.Doc

原标题：方案设计：多租户系统架构三种实现模式对比
简介：golang arp 缓存读取操作，读取系统 arp 缓存表，获取 ip 对应的 mac 地址信息。
 | 原文链接：http://book.xdpa0b.asia/blog/423217.Doc

原标题：架构笔记：业务系统反模式架构踩坑总结
简介：容器资源限制防止宿主机过载，设置容器 CPU 内存资源上限，避免单个容器耗尽宿主机全部硬件资源。
 | 原文链接：http://book.xdpa0b.asia/blog/570461.Doc

原标题：安全笔记：JWT安全风险，签名泄露过期控制
简介：golang defer panic 异常处理，理解 defer 延迟执行，panic 恐慌捕获，实现函数资源释放异常保护。
 | 原文链接：http://book.xdpa0b.asia/blog/511824.Doc

原标题：golang minio 分片上传断点续传
简介：数据库连接及时关闭连接泄漏，确保数据库连接使用完毕释放归还连接池，杜绝连接泄漏耗尽连接。
 | 原文链接：http://book.xdpa0b.asia/blog/574720.Doc

原标题：golang 系统设计分布式锁可重入实现思路
简介：golang yaml 解析配置加载实操，Go 解析 YAML 配置文件，读取配置参数，驱动业务运行。
 | 原文链接：http://book.xdpa0b.asia/blog/733329.Doc

原标题：方案对比：单体、微服务、模块化单体取舍
简介：数据库排序规则统一结果一致，统一数据库表排序规则，解决不同环境查询排序结果不一致问题。
 | 原文链接：http://book.xdpa0b.asia/blog/607760.Doc

原标题：golang 系统设计故障应急响应完整流程梳理
简介：golang 结构体 json 序列化坑点，梳理 Go 结构体 JSON 序列化高频坑点，字段大小写、零值处理问题。
 | 原文链接：http://book.xdpa0b.asia/blog/612402.Doc

原标题：分页逻辑错误数据漏查修复
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://book.xdpa0b.asia/blog/120380.Doc

原标题：nodejs 读取大文件 csv 处理方案
简介：配置与镜像分离防止信息泄露，业务配置不打包进镜像，外部挂载配置，避免密钥配置随镜像泄露。
 | 原文链接：http://book.xdpa0b.asia/blog/242587.Doc

原标题：批量数据处理脚本编写技巧
简介：golang 性能压测 wr 工具实操指南，wr 压测工具对 Go 接口压测，观察 QPS 延迟，定位接口性能瓶颈。
 | 原文链接：http://book.xdpa0b.asia/blog/482113.Doc

原标题：golang 系统设计令牌桶漏桶算法对比
简介：Git 混乱提交历史清理方法，针对杂乱的提交记录，使用 Git 工具整理，清理无效提交，还原整洁版本历史。
 | 原文链接：http://book.xdpa0b.asia/blog/288420.Doc

原标题：nestjs 框架模块化项目搭建
简介：golang crypto 密码学最佳实践，go crypto 包加密签名，规避不安全算法，使用安全密码套件。
 | 原文链接：http://book.xdpa0b.asia/blog/196667.Doc

原标题：golang websocket 服务端开发
简介：golang http client 连接池调优，调优 Go HTTP Client 连接池参数，复用 TCP 连接，减少连接创建开销。
 | 原文链接：http://book.xdpa0b.asia/blog/389705.Doc

原标题：服务器 Swap 关闭提升响应速度
简介：golang GC 调优 GOGC 参数调整，调整 GOGC 阈值，控制 GC 触发时机，权衡内存占用与 CPU 开销。
 | 原文链接：http://book.xdpa0b.asia/blog/894372.Doc

原标题：一次数据库死锁现场分析与解决方案记录
简介：golang consul 服务发现简单示例，对接 Consul 实现服务注册发现，微服务实例自动感知。
 | 原文链接：http://book.xdpa0b.asia/blog/679923.Doc

原标题：代码格式化工具团队统一风格
简介：golang benchmark 减少测试干扰，benchmark 执行循环 b.N，避免循环内部做非被测逻辑干扰结果。
 | 原文链接：http://book.xdpa0b.asia/blog/619180.Doc

原标题：Practice：实现数据库事务消息最终一致性demo
简介：css 变量主题切换方案实现，使用 CSS 变量实现网页主题切换，多套主题样式快速切换无需大量 CSS。
 | 原文链接：http://book.xdpa0b.asia/blog/456069.Doc

原标题：golang redis 限流几种实现方案
简介：前端图片懒加载性能优化，实现图片懒加载，页面可视区域才加载图片，减少页面初始网络请求。
 | 原文链接：http://book.xdpa0b.asia/blog/452982.Doc

原标题：Issue复现：内存泄漏定位完整复盘记录
简介：多线程线程安全脏数据规避，梳理多线程共享变量，做好同步控制，避免并发修改产生脏数据。
 | 原文链接：http://book.xdpa0b.asia/blog/160087.Doc

原标题：golang 系统设计配置灰度下发简单实现思路
简介：golang kitex 超时重试熔断配置，kitex 配置调用超时、重试、熔断策略，保障微服务调用稳定性。
 | 原文链接：http://book.xdpa0b.asia/blog/837671.Doc

原标题：RPC 报文大小上限调优大请求
简介：golang tar gz 压缩解压处理，tar.gz 归档压缩解压，服务端日志备份、文件打包场景使用。
 | 原文链接：http://book.xdpa0b.asia/blog/018196.Doc

原标题：ICMP 放通网络丢包问题修复
简介：Docker 容器入门镜像实操教程，介绍 Docker 基础概念，演示镜像拉取、容器启停，帮助新手建立容器化开发认知。
 | 原文链接：http://book.xdpa0b.asia/blog/228050.Doc

原标题：golang 系统设计 tcp 三次握手四次挥手梳理
简介：限流组件计数器令牌桶模式实现，实现计数器、令牌桶两种限流算法，封装可复用限流组件。
 | 原文链接：http://book.xdpa0b.asia/blog/332407.Doc

原标题：磁盘占满服务不可用清理方案
简介：golang go http 安全头配置实践，设置 http 安全响应头，防范 XSS、点击劫持，提升 web 服务安全性。
 | 原文链接：http://book.xdpa0b.asia/blog/896207.Doc

原标题：golang 系统设计技术债务识别登记治理思路
简介：golang 读写分离 gorm 实现主从切换，gorm 配置主库写入从库查询，读写分离分担数据库查询压力。
 | 原文链接：http://book.xdpa0b.asia/blog/013219.Doc

原标题：前端国际化多语言方案落地
简介：golang go 优雅处理信号丢失场景，处理信号丢失、信号被忽略，保障程序可以正常接收终止信号。
 | 原文链接：http://book.xdpa0b.asia/blog/740209.Doc

原标题：运维笔记：服务器磁盘内存监控告警配置
简介：nodejs 内存溢出问题排查修复，Node.js 程序 OOM 排查流程，定位内存泄露，调整内存限制修复崩溃。
 | 原文链接：http://book.xdpa0b.asia/blog/418817.Doc

原标题：golang 系统设计分布式配置中心思路
简介：golang net/http/httptest 服务端模拟，httptest.NewRecorder 记录 handler 响应，校验返回状态码 body。
 | 原文链接：http://book.xdpa0b.asia/blog/175502.Doc

原标题：架构笔记：数据库连接池架构参数调优思路
简介：golang redis 过期时间处理技巧，设置 key 过期，监控过期事件，基于过期特性实现业务缓存逻辑。
 | 原文链接：http://book.xdpa0b.asia/blog/239163.Doc

原标题：坑点：软链接权限问题容器读取文件失败
简介：golang k8s informer 机制原理理解，informer 监听 k8s 资源变更，本地缓存，减少 apiserver 压力。
 | 原文链接：http://book.xdpa0b.asia/blog/615512.Doc

原标题：golang 系统设计灰度发布流量切分实现
简介：操作系统内核版本适配服务，针对服务运行要求，适配操作系统内核版本，规避内核兼容 bug。
 | 原文链接：http://book.xdpa0b.asia/blog/800940.Doc

原标题：Performance：缓存策略优化，降低数据库压力
简介：golang tidb 数据库 go 项目适配，go 程序适配 tidb，兼容 mysql 协议，分布式数据库业务开发。
 | 原文链接：http://book.xdpa0b.asia/blog/538524.Doc

原标题：golang 系统设计 csrf 接口防护实现
简介：接口限流逻辑简单模拟实现，编写简易限流逻辑，限制接口访问频次，保护服务，避免短时间大量请求压垮系统。
 | 原文链接：http://book.xdpa0b.asia/blog/666543.Doc

原标题：Troubleshooting：Nginx缓冲区过小大文件上传失败
简介：golang 分库分表简单路由实现，简易分表路由逻辑实现，根据分片 key 计算分片位置，数据路由写入。
 | 原文链接：http://book.xdpa0b.asia/blog/168214.Doc

原标题：设计思考：API网关和BFF职责边界划分
简介：golang redis bitmap 位图业务实战，bitmap 做签到统计、用户状态标记，节省大量内存空间。
 | 原文链接：http://book.xdpa0b.asia/blog/490722.Doc

原标题：golang 系统设计链路数据存储选型对比讲解
简介：数据库索引重建提升查询速度，针对碎片化索引，重建数据库索引，恢复 SQL 查询执行性能。
 | 原文链接：http://book.xdpa0b.asia/blog/982039.Doc

原标题：性能复盘：系统上下文切换过高性能下降调优
简介：多线程线程安全脏数据规避，梳理多线程共享变量，做好同步控制，避免并发修改产生脏数据。
 | 原文链接：http://book.xdpa0b.asia/blog/728757.Doc

原标题：golang websocket 服务端开发
简介：golang crypto 密码学最佳实践，go crypto 包加密签名，规避不安全算法，使用安全密码套件。
 | 原文链接：http://book.xdpa0b.asia/blog/756934.Doc


二、踩坑排错｜Troubleshooting
原标题：golang k8s 滚动更新回滚策略
简介：内存泄漏定位分析完整流程，分享内存泄漏排查步骤，定位没有释放的对象，解决内存持续上涨问题。
 | 原文链接：http://book.xdpa0b.asia/blog/151654.Doc

原标题：golang 系统设计测试环境预发环境生产环境隔离
简介：nestjs 全局返回格式统一处理，Nest 全局拦截器统一包装接口返回数据，对外输出标准化响应格式。
 | 原文链接：http://book.xdpa0b.asia/blog/233994.Doc

原标题：Practice：实现接口防重提交组件实践
简介：消息队列重复消费业务处理，实现消息消费幂等，处理重复投递消息，保证多次消费业务结果一致。
 | 原文链接：http://book.xdpa0b.asia/blog/261955.Doc

原标题：ICMP 放通网络丢包问题修复
简介：golang grpc 客户端拦截器封装，grpc 客户端拦截器实现请求统一签名、重试、链路信息透传。
 | 原文链接：http://book.xdpa0b.asia/blog/311188.Doc

原标题：复盘总结：系统压测报告模板与分析思路
简介：golang go decimal 定点小数金额计算，decimal 库处理金额，规避 float64 精度丢失，财务计算。
 | 原文链接：http://book.xdpa0b.asia/blog/892079.Doc

原标题：开发复盘：大事务拆分优化业务性能实践
简介：golang http 服务性能优化调参，调优 Go HTTP 服务参数，调整连接池，提升服务并发吞吐能力。
 | 原文链接：http://book.xdpa0b.asia/blog/344687.Doc

原标题：包管理器依赖冲突解决方案
简介：多线程线程安全脏数据规避，梳理多线程共享变量，做好同步控制，避免并发修改产生脏数据。
 | 原文链接：http://book.xdpa0b.asia/blog/276759.Doc

原标题：DNS 解析异常第三方调用故障
简介：文件批量导入导出功能实现，开发批量导入导出接口，处理大量文件数据，完成业务数据批量迁移与导出。
 | 原文链接：http://book.xdpa0b.asia/blog/100920.Doc

原标题：golang 系统设计 go benchmark 性能测试实操
简介：golang redis lua 脚本原子操作，使用 Lua 脚本实现原子逻辑，减少网络往返，保障多命令原子执行。
 | 原文链接：http://book.xdpa0b.asia/blog/500712.Doc

原标题：Git 分支切换合并删除完整操作
简介：JWT 令牌过期异常处理，捕获 JWT 过期、篡改异常，编写业务处理逻辑，引导用户重新获取令牌。
 | 原文链接：http://book.xdpa0b.asia/blog/827698.Doc

原标题：golang 系统设计 traceId 全链路透传完整方案
简介：vue pinia 状态管理实战教程，Pinia 完整实战示例，实现状态定义修改，模块拆分替代 Vuex。
 | 原文链接：http://book.xdpa0b.asia/blog/013592.Doc

原标题：项目实践：MySQL读写分离本地模拟实践
简介：golang context 上下文传参讲解，讲解 Context 使用场景，传递元数据、控制协程超时取消，规范协程控制。
 | 原文链接：http://book.xdpa0b.asia/blog/446808.Doc

原标题：浏览器内存泄漏排查前端页面
简介：集成测试业务流程编写示例，编写业务流程集成测试，覆盖完整业务链路，验证模块之间协同工作是否正常。
 | 原文链接：http://book.xdpa0b.asia/blog/520359.Doc

原标题：golang 系统设计 protobuf json 性能对比
简介：Git 误提交撤销回退实操教程，演示多种撤销提交方式，区分已经推送远程和本地未提交场景，处理误提交代码。
 | 原文链接：http://book.xdpa0b.asia/blog/932863.Doc

原标题：golang grafana 监控面板简单配置
简介：分页逻辑错误数据漏查修复，修复分页查询逻辑漏洞，解决分页漏数据、重复返回数据等业务问题。
 | 原文链接：http://book.xdpa0b.asia/blog/736242.Doc

原标题：DevOps：多环境镜像标签版本管理规范
简介：golang go 程序抢占调度理解，理解 go 抢占式调度原理，长循环阻塞调度，造成协程调度延迟。
 | 原文链接：http://book.xdpa0b.asia/blog/159248.Doc

原标题：灰度发布策略服务平滑升级
简介：golang os/exec 安全执行外部命令，规避命令注入漏洞，参数分离，禁止拼接命令字符串执行。
 | 原文链接：http://book.xdpa0b.asia/blog/261737.Doc

原标题：系统文件描述符上限调大
简介：golang clickhouse go 客户端数据写入，clickhouse‑go 客户端写入查询，海量时序数据分析业务。
 | 原文链接：http://book.xdpa0b.asia/blog/855556.Doc

原标题：golang channel 通道并发处理
简介：Redis 分布式锁高并发安全实现，基于 Redis 实现分布式锁，处理锁过期、续期，保障集群并发安全。
 | 原文链接：http://book.xdpa0b.asia/blog/974164.Doc

原标题：golang mysql 索引失效常见场景
简介：golang sftp 文件上传下载操作，sftp 协议远程文件上传下载，实现服务器之间文件传输功能。
 | 原文链接：http://book.xdpa0b.asia/blog/122557.Doc

原标题：优化实践：异步改造同步接口提升吞吐能力
简介：限流规则误拦截正常请求修复，修正限流规则阈值，避免合法用户被限流拦截，兼顾防护与可用性。
 | 原文链接：http://book.xdpa0b.asia/blog/858113.Doc

原标题：golang 跨域处理中间件编写
简介：MySQL 慢查询索引优化实战，抓取慢查询 SQL，分析执行计划，新增或者调整索引，提升 SQL 执行速度。
 | 原文链接：http://book.xdpa0b.asia/blog/504131.Doc

原标题：golang 系统设计网关灰度流量切分简单方案
简介：golang 高并发下锁优化减少竞争，减小锁粒度，读写锁替换互斥锁，无锁编程降低锁竞争开销。
 | 原文链接：http://book.xdpa0b.asia/blog/678779.Doc

原标题：短信服务封装失败自动重试
简介：异步异常捕获避免进程崩溃，捕获异步代码内部抛出异常，防止未捕获异常直接导致整个进程退出。
 | 原文链接：http://book.xdpa0b.asia/blog/060004.Doc

原标题：golang k8s helm chart 简单编写
简介：golang netlink 系统信息获取，netlink 获取系统网络信息，网卡地址，内核网络状态读取。
 | 原文链接：http://book.xdpa0b.asia/blog/855849.Doc

原标题：开源实践：参与开源项目从Issue到PR完整流程
简介：golang go 调度器 GMP 模型通俗讲解，拆解 GMP 模型，理解 goroutine M P 调度原理，看懂调度状态。
 | 原文链接：http://book.xdpa0b.asia/blog/940381.Doc

原标题：golang ci 流水线代码质量扫描集成
简介：golang rabbitmq go 客户端生产消费，streadway/amqp 实现 rabbitmq 生产者消费者，队列交换机绑定。
 | 原文链接：http://book.xdpa0b.asia/blog/052550.Doc

原标题：Issue：文件句柄耗尽，服务缓慢卡死复盘
简介：golang go http 安全头配置实践，设置 http 安全响应头，防范 XSS、点击劫持，提升 web 服务安全性。
 | 原文链接：http://book.xdpa0b.asia/blog/859541.Doc

原标题：css 动画性能优化 GPU 加速
简介：SDK 版本兼容线上崩溃修复，处理 SDK 版本升级之后线上崩溃，定位 API 变更，做版本兼容适配改造。
 | 原文链接：http://book.xdpa0b.asia/blog/936249.Doc

原标题：坑点：gitreset误删本地代码恢复方案
简介：golang time 时间格式化参考时间牢记，2006‑01‑02T15:04:05Z07:00，掌握 go 时间格式化关键点。
 | 原文链接：http://book.xdpa0b.asia/blog/543947.Doc

原标题：实战项目：数据导出Excel百万级大数据导出方案
简介：golang json omitempty 零值坑，omitempty 会忽略零值，区分业务是否需要输出零值字段。
 | 原文链接：http://book.xdpa0b.asia/blog/122193.Doc

原标题：golang 项目 go mod 依赖管理
简介：golang http MaxHeaderBytes 限制请求头，设置 http 最大请求头大小，防止超大 header 攻击。
 | 原文链接：http://book.xdpa0b.asia/blog/536690.Doc

原标题：实战项目：Nginx限速、限流、防爬虫配置实践
简介：golang clickhouse go 客户端数据写入，clickhouse‑go 客户端写入查询，海量时序数据分析业务。
 | 原文链接：http://book.xdpa0b.asia/blog/432106.Doc

原标题：线上故障：消息队列重复消费业务处理异常
简介：golang go 项目 CI github actions 配置，github actions 实现 go 项目 ci，自动测试、代码检查、编译打包镜像。
 | 原文链接：http://book.xdpa0b.asia/blog/013381.Doc

原标题：架构笔记：海量消息堆积架构处理能力设计
简介：前端工程化 webpack 打包优化，针对 webpack 项目做打包调优，分包、压缩、Tree‑Shaking，缩减包体积。
 | 原文链接：http://book.xdpa0b.asia/blog/665132.Doc

原标题：分布式 ID 全局唯一生成方案
简介：golang gin 路由动态注册实现方案，根据配置动态注册接口路由，无需硬编码路由，适配动态业务模块。
 | 原文链接：http://book.xdpa0b.asia/blog/091000.Doc

原标题：批量操作分批处理防止 OOM
简介：golang go 程序守护进程实现思路，go 程序不做 daemon 化，依靠 systemd pm2 k8s 实现进程守护。
 | 原文链接：http://book.xdpa0b.asia/blog/086406.Doc

原标题：golang 系统设计 changelog 变更日志维护
简介：golang redis 锁超时业务处理，Redis 分布式锁超时问题处理，锁续期逻辑，防止业务未完成锁提前释放。
 | 原文链接：http://book.xdpa0b.asia/blog/120701.Doc

原标题：golang 系统设计告警升级通知策略配置思路
简介：程序信号中断退出处理逻辑，捕获系统中断信号，执行资源释放、关闭连接，实现程序优雅退出。
 | 原文链接：http://book.xdpa0b.asia/blog/798217.Doc

原标题：API 接口调试与异常处理实战
简介：golang gitlab ci go 项目流水线编写，gitlab ci 流水线执行单元测试、静态检查、构建推送镜像。
 | 原文链接：http://book.xdpa0b.asia/blog/221049.Doc

三、实战开发｜Practice
原标题：设计实践：如何设计可扩展业务数据库表结构
简介：golang go 锁竞争导致 CPU 飙升，识别锁竞争场景，减少锁粒度，优化并发逻辑降低 CPU 开销。
 | 原文链接：http://book.xdpa0b.asia/blog/573726.Doc

原标题：实践：消息队列死信处理业务落地实践
简介：golang 钉钉企业微信告警消息推送，go 调用企业微信钉钉接口，推送告警通知、业务消息。
 | 原文链接：http://book.xdpa0b.asia/blog/425956.Doc

原标题：分布式 ID 全局唯一生成方案
简介：异步任务堆积消费能力优化，处理消息任务堆积问题，提升消费处理速度，恢复队列正常处理水位。
 | 原文链接：http://book.xdpa0b.asia/blog/077978.Doc

原标题：安全实践：输入输出双向过滤安全最佳实践
简介：golang http MaxHeaderBytes 限制请求头，设置 http 最大请求头大小，防止超大 header 攻击。
 | 原文链接：http://book.xdpa0b.asia/blog/885312.Doc

原标题：golang grpc protobuf 开发实操
简介：日志驱动异常日志不输出修复，排查日志驱动配置，修复日志写入配置，恢复程序正常日志输出。
 | 原文链接：http://book.xdpa0b.asia/blog/569355.Doc

原标题：零基础学习简单正则表达式实战案例
简介：golang e2e 端到端测试 go 接口，编写 e2e 测试，完整模拟用户请求，校验整套业务链路正确性。
 | 原文链接：http://book.xdpa0b.asia/blog/306589.Doc

原标题：优化实践：接口批量合并减少网络请求次数
简介：golang websocket 服务端开发，Go 实现 WebSocket 服务端，处理连接、消息收发，实现长连接服务。
 | 原文链接：http://book.xdpa0b.asia/blog/423392.Doc

原标题：OpenSource：开源项目README高质量编写指南
简介：集成测试业务流程编写示例，编写业务流程集成测试，覆盖完整业务链路，验证模块之间协同工作是否正常。
 | 原文链接：http://book.xdpa0b.asia/blog/438739.Doc

原标题：避坑：Spring事务传播行为理解错误事务失效
简介：golang sync.Pool 对象池复用对象，sync.Pool 复用临时对象，减少内存分配，降低 GC 频率提升性能。
 | 原文链接：http://book.xdpa0b.asia/blog/895748.Doc

原标题：多线程线程安全脏数据规避
简介：golang 雪花算法 workId 自动获取，自动获取机器 workId，不用手动配置，简化分布式 id 部署。
 | 原文链接：http://book.xdpa0b.asia/blog/191999.Doc

原标题：golang docker volume 数据持久化
简介：golang 分布式锁 redis 实现，基于 Redis 实现 Go 分布式锁，解决多实例并发竞争资源问题。
 | 原文链接：http://book.xdpa0b.asia/blog/752338.Doc

原标题：golang mysql limit 大分页优化
简介：golang go 领域驱动 DDD 项目分层，go 项目 DDD 分层架构，领域层应用层基础设施层划分业务代码。
 | 原文链接：http://book.xdpa0b.asia/blog/563294.Doc

原标题：网关集成鉴权限流日志一体化
简介：nodejs 全局异常捕获进程防护，捕获未捕获异常与 Promise 拒绝，尽量保护进程不因为异常直接退出。
 | 原文链接：http://book.xdpa0b.asia/blog/075389.Doc

原标题：golang 系统设计告警风暴抑制合并降噪方案
简介：golang 信号量控制并发数量，使用信号量控制并发，限制同时执行任务数量，保护下游资源。
 | 原文链接：http://book.xdpa0b.asia/blog/709178.Doc

原标题：图片上传预览格式大小处理
简介：分页逻辑错误数据漏查修复，修复分页查询逻辑漏洞，解决分页漏数据、重复返回数据等业务问题。
 | 原文链接：http://book.xdpa0b.asia/blog/202175.Doc

原标题：golang redis 分布式计数器开发
简介：CDN 缓存刷新获取最新静态资源，调用 CDN 刷新接口，清除节点旧缓存，用户访问到更新后的静态文件。
 | 原文链接：http://book.xdpa0b.asia/blog/507072.Doc

原标题：golang 优雅处理 http 超时设置
简介：golang go 锁竞争导致 CPU 飙升，识别锁竞争场景，减少锁粒度，优化并发逻辑降低 CPU 开销。
 | 原文链接：http://book.xdpa0b.asia/blog/315259.Doc

原标题：golang url 参数编码处理方案
简介：golang go 调用动态链接库 so 文件，go 加载 so 动态库调用函数，复用编译好的 C 动态库。
 | 原文链接：http://book.xdpa0b.asia/blog/449120.Doc

原标题：golang docker 网络模式桥接 host
简介：文件描述符优化进程卡死修复，及时关闭文件句柄，控制打开文件数量，解决文件句柄耗尽进程卡死。
 | 原文链接：http://book.xdpa0b.asia/blog/987329.Doc

原标题：golang 系统设计 git 分支流程 gitflow 实操
简介：死信队列处理消息阻塞业务，配置死信队列，处理消费失败消息，避免失败消息阻塞整个队列业务。
 | 原文链接：http://book.xdpa0b.asia/blog/305061.Doc

原标题：golang k8s 滚动更新回滚策略
简介：golang go‑zero 分布式锁组件使用，go‑zero 内置 redis 分布式锁，业务直接调用实现并发控制。
 | 原文链接：http://book.xdpa0b.asia/blog/120422.Doc

原标题：golang 系统设计回调签名校验防伪造实现
简介：golang go 爬虫异步并发抓取，协程池控制并发抓取网页，多协程采集，提升爬虫采集速度。
 | 原文链接：http://book.xdpa0b.asia/blog/270257.Doc

原标题：golang 限流熔断降级完整示例
简介：接口请求重试容错机制实现，封装请求重试逻辑，遇到临时网络故障自动重试，提升第三方调用稳定性。
 | 原文链接：http://book.xdpa0b.asia/blog/018962.Doc

原标题：设计思考：防雪崩，系统过载保护架构设计
简介：golang 消息队列中间件选型对比，kafka redis‑stream rabbitmq，对比吞吐量可靠性选型参考。
 | 原文链接：http://book.xdpa0b.asia/blog/552592.Doc

原标题：坑点：限流计数器重置时机错误，绕过限流规则
简介：SDK 版本兼容线上崩溃修复，处理 SDK 版本升级之后线上崩溃，定位 API 变更，做版本兼容适配改造。
 | 原文链接：http://book.xdpa0b.asia/blog/806967.Doc

原标题：golang 数据库批量更新性能优化
简介：golang 静态文件服务搭建教程，Go 搭建静态文件服务，托管静态资源，实现文件直接对外访问。
 | 原文链接：http://book.xdpa0b.asia/blog/673920.Doc

原标题：golang 系统设计 git 钩子自动化校验实现
简介：macOS 脚本执行权限开启，给 Shell 脚本添加可执行权限，解决 macOS 下脚本无法运行权限报错。
 | 原文链接：http://book.xdpa0b.asia/blog/119874.Doc

原标题：golang 系统设计 ide 配置 go 开发效率提升技巧
简介：跨平台换行符统一异常修复，统一代码文件换行符，解决不同操作系统换行符不一致带来脚本执行异常。
 | 原文链接：http://book.xdpa0b.asia/blog/966389.Doc

原标题：简易日志收集集中管理方案
简介：golang 限流熔断放在代理层实践，代理层统一限流熔断，对后端服务做流量保护。
 | 原文链接：http://book.xdpa0b.asia/blog/153197.Doc

原标题：入门实践：简单批量处理脚本编写
简介：golang testify mock 模拟接口，mock 接口生成 mock 对象，单元测试模拟外部依赖行为。
 | 原文链接：http://book.xdpa0b.asia/blog/970661.Doc

原标题：golang md5 sha 加密工具实现
简介：前后端交互跨域问题完整处理，讲解跨域产生原理，列举多种解决方案，适配开发、生产不同环境的跨域处理。
 | 原文链接：http://book.xdpa0b.asia/blog/379173.Doc

原标题：安全实践：防止重放攻击接口签名方案
简介：golang 限流器熔断降级组合使用，限流熔断降级组合架构，流量防护完整方案，保障服务稳定性。
 | 原文链接：http://book.xdpa0b.asia/blog/865161.Doc

原标题：nestjs 权限守卫鉴权实现方案
简介：简易网关请求路由过滤模拟，模拟网关基础能力，实现请求路由转发、简单过滤，理解网关核心工作逻辑。
 | 原文链接：http://book.xdpa0b.asia/blog/785139.Doc

原标题：golang 系统设计雪花算法 id 原理剖析
简介：golang benchmark 减少测试干扰，benchmark 执行循环 b.N，避免循环内部做非被测逻辑干扰结果。
 | 原文链接：http://book.xdpa0b.asia/blog/752179.Doc

原标题：Performance：数据库大表优化，冷热数据分离
简介：golang http 文件下载断点续传服务，服务端实现断点续传，支持大文件分段下载，提升大文件下载稳定性。
 | 原文链接：http://book.xdpa0b.asia/blog/373959.Doc

原标题：方案对比：同步事务vs事务消息最终一致性
简介：golang 信号捕获程序退出处理，Go 捕获操作系统信号，做资源回收，控制程序退出流程。
 | 原文链接：http://book.xdpa0b.asia/blog/290218.Doc

原标题：golang kafka 同步异步消费对比
简介：golang 结构体 json 序列化坑点，梳理 Go 结构体 JSON 序列化高频坑点，字段大小写、零值处理问题。
 | 原文链接：http://book.xdpa0b.asia/blog/084646.Doc

原标题：零基础理解内存溢出基础现象与表现
简介：nestjs 全局返回格式统一处理，Nest 全局拦截器统一包装接口返回数据，对外输出标准化响应格式。
 | 原文链接：http://book.xdpa0b.asia/blog/566500.Doc

原标题：golang 系统设计避免索引失效书写 sql 原则
简介：跨库查询性能优化处理，减少跨库关联查询，做数据冗余或者中间表，规避跨库查询性能低下。
 | 原文链接：http://book.xdpa0b.asia/blog/855044.Doc

原标题：实战项目：GitHubAction自动测试构建实践
简介：golang 时间轮算法实现延时调度，手写简易时间轮，高并发大量延时任务，降低轮询 CPU 消耗。
 | 原文链接：http://book.xdpa0b.asia/blog/131358.Doc

四、架构设计｜Architecture
原标题：安全笔记：请求头伪造IP漏洞防护
简介：文件锁正确使用避免死锁，合理使用文件锁，控制多进程访问同一个文件，规避文件锁死锁现象。
 | 原文链接：http://book.xdpa0b.asia/blog/815546.Doc

原标题：排错：内网域名解析不稳定导致服务随机报错
简介：golang goroutine 协程基础实操，Goroutine 基础实操案例，启动协程执行任务，理解轻量级协程特性。
 | 原文链接：http://book.xdpa0b.asia/blog/169902.Doc

原标题：OpenSource：大型仓库Git历史清理瘦身实操
简介：简易日志收集集中管理方案，搭建轻量日志收集方案，把多服务日志汇总，集中检索查看日志信息。
 | 原文链接：http://book.xdpa0b.asia/blog/054213.Doc

原标题：golang 系统设计锁优化减少竞争提升吞吐
简介：golang goroutine 池任务调度，实现 goroutine 池，复用协程，频繁任务场景减少协程创建销毁开销。
 | 原文链接：http://book.xdpa0b.asia/blog/595800.Doc

原标题：golang 系统设计热点数据缓存处理
简介：golang go‑zero api 接口开发与路由，go‑zero 编写 api 定义文件，生成代码开发 http 接口。
 | 原文链接：http://book.xdpa0b.asia/blog/163570.Doc

原标题：部署复盘：静态站点部署CDN完整流程
简介：分布式 ID 生成器高并发实现，实现高性能分布式 ID 生成器，适配高并发业务，生成全局唯一 ID。
 | 原文链接：http://book.xdpa0b.asia/blog/231130.Doc

原标题：运维笔记：线上服务健康检查脚本编写
简介：golang wasm 浏览器 js 交互，go wasm 与 js 互相调用，浏览器端 go 程序操作 dom 调用 js 函数。
 | 原文链接：http://book.xdpa0b.asia/blog/422811.Doc

原标题：Troubleshooting：防火墙安全组拦截访问请求
简介：golang 空接口 interface {} 类型处理，interface {} 存储任意类型，类型转换，处理泛型之前通用数据。
 | 原文链接：http://book.xdpa0b.asia/blog/427380.Doc

原标题：golang 系统设计告警升级通知策略配置思路
简介：golang channel 作为函数参数方向，声明 channel 入参方向，只读 channel 只写 channel 提升代码约束。
 | 原文链接：http://book.xdpa0b.asia/blog/882972.Doc

原标题：react 状态管理方案选型对比
简介：golang io.MultiReader MultiWriter 拼接流，多个 reader 拼接，多 writer 同时写入一份数据。
 | 原文链接：http://book.xdpa0b.asia/blog/345926.Doc

原标题：实战：gRPC服务编写客户端服务端完整demo
简介：golang go list 双向链表使用，container/list 双向链表，频繁增删节点业务场景使用。
 | 原文链接：http://book.xdpa0b.asia/blog/759492.Doc

原标题：分布式 ID 生成器高并发实现
简介：golang context 包标准用法规范，context 传递请求元数据、超时、取消，函数第一个参数传入 ctx。
 | 原文链接：http://book.xdpa0b.asia/blog/789499.Doc

原标题：golang redis bitmap 位图统计实现
简介：数据库索引重建提升查询速度，针对碎片化索引，重建数据库索引，恢复 SQL 查询执行性能。
 | 原文链接：http://book.xdpa0b.asia/blog/777519.Doc

原标题：开发生产环境资源路径统一
简介：包管理器依赖缓存清理，清理本地依赖缓存，解决缓存旧包引发问题，拉取最新版本依赖包。
 | 原文链接：http://book.xdpa0b.asia/blog/722092.Doc

原标题：零基础理解会话、Cookie、Session基础
简介：golang hertz http 框架快速上手，hertz 高性能 http 框架，路由中间件参数校验快速开发接口服务。
 | 原文链接：http://book.xdpa0b.asia/blog/507869.Doc

原标题：新手向：开源项目fork与同步上游代码
简介：重复提交幂等防护再次讲解，梳理前端重复点击、网络重试场景，落地接口幂等，杜绝重复业务。
 | 原文链接：http://book.xdpa0b.asia/blog/358405.Doc

原标题：golang 系统设计数据库版本迁移回滚方案
简介：golang 自定义 http round tripper，封装 http 客户端拦截，实现请求日志、签名、重试统一处理逻辑。
 | 原文链接：http://book.xdpa0b.asia/blog/610471.Doc

原标题：排错：打包后资源路径，开发生产行为不一致
简介：golang aes 对称加密解密示例，AES 对称加密解密实现，业务敏感数据加密存储传输。
 | 原文链接：http://book.xdpa0b.asia/blog/192225.Doc

?
