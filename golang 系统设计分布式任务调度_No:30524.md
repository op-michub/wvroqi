最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计分布式任务调度
简介：golang 大内存分配 GC 抖动规避，避免瞬时大量对象创建，分批处理，防止 GC 抖动业务抖动。
 | 原文链接：http://m.share.hndfly.cn/Article/details/76932825.sHtML

原标题：设计思考：系统限流熔断降级完整防护体系
简介：golang 结构体零值可用性原则，go 结构体尽量做到零值可用，不用初始化直接使用提升易用性。
 | 原文链接：http://m.share.hndfly.cn/Article/details/70895243.sHtML

原标题：线上异常：缓存雪崩带来数据库压力瞬间飙升
简介：golang time.After 内存泄漏场景，for 循环使用 time.After 会创建大量 timer，造成内存泄漏。
 | 原文链接：http://m.share.hndfly.cn/Article/details/88525754.sHtML

原标题：从零搭建简单的健康检查接口示例
简介：golang 自定义 pprof 扩展业务指标，扩展 pprof，输出业务自定义指标，结合性能数据分析业务状态。
 | 原文链接：http://m.share.hndfly.cn/Article/details/04950382.sHtML

原标题：golang redis 限流几种实现方案
简介：请求工具封装统一异常处理，对网络请求做二次封装，统一捕获各类请求异常，标准化接口返回格式。
 | 原文链接：http://m.share.hndfly.cn/Article/details/67677838.sHtML

原标题：前端大文件分片上传完整方案
简介：数据库分表路由写入分片修正，修复分表路由逻辑，保证数据写入正确分片，不会出现数据丢失错乱。
 | 原文链接：http://m.share.hndfly.cn/Article/details/94489469.sHtML

原标题：前端 pdf 预览渲染方案对比
简介：golang delve 远程调试 go 线上程序，delve 远程调试，线上环境附加进程调试排查线上 bug。
 | 原文链接：http://m.share.hndfly.cn/Article/details/73073591.sHtML

原标题：项目实践：实现统一接口返回封装与全局异常处理
简介：分页逻辑错误数据漏查修复，修复分页查询逻辑漏洞，解决分页漏数据、重复返回数据等业务问题。
 | 原文链接：http://m.share.hndfly.cn/Article/details/20718076.sHtML

原标题：nodejs 多进程任务分发处理
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://m.share.hndfly.cn/Article/details/41883326.sHtML

原标题：HTTP 状态码请求头完整梳理
简介：golang cgo 调用 C 语言代码示例，cgo 调用 C 函数，go 与 C 互相调用，对接 C 语言库能力。
 | 原文链接：http://m.share.hndfly.cn/Article/details/01529753.sHtML

原标题：golang 系统设计开源项目贡献指南 contributing
简介：golang init 函数合理使用边界，少用 init，优先显式调用初始化，便于控制初始化时机。
 | 原文链接：http://m.share.hndfly.cn/Article/details/25480044.sHtML

原标题：Practice：实现熔断降级组件简单原型代码
简介：golang mysql 慢查询日志程序采集解析，程序读取解析 mysql 慢查询日志，统计慢 SQL 做监控告警。
 | 原文链接：http://m.share.hndfly.cn/Article/details/88541875.sHtML

原标题：Architecture：监控告警架构避免告警风暴设计
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：http://m.share.hndfly.cn/Article/details/31983332.sHtML

原标题：架构笔记：分库分表中间件选型业务约束
简介：业务接口幂等完整落地案例，完整业务场景幂等落地示例，覆盖表单提交、回调、重试各类场景。
 | 原文链接：http://m.share.hndfly.cn/Article/details/96245921.sHtML

原标题：GitHub 项目提交推送完整流程讲解
简介：Git commit 钩子提交规范校验，配置 Git 提交钩子，提交代码自动校验提交信息格式，规范提交记录。
 | 原文链接：http://m.share.hndfly.cn/Article/details/58379267.sHtML

原标题：实践：代码提交前自动格式化校验配置实践
简介：golang 分页查询封装通用工具，封装 Go 通用分页工具，统一处理分页参数，简化业务分页接口开发。
 | 原文链接：http://m.share.hndfly.cn/Article/details/60352310.sHtML

原标题：分布式 ID 生成器高并发实现
简介：前后端交互跨域问题完整处理，讲解跨域产生原理，列举多种解决方案，适配开发、生产不同环境的跨域处理。
 | 原文链接：http://m.share.hndfly.cn/Article/details/33618324.sHtML

原标题：golang 系统设计压测指标 qps rt 错误率讲解
简介：全量回归测试提升代码质量，搭建全量回归测试集，版本发布执行回归测试，避免迭代引入旧 bug。
 | 原文链接：http://m.share.hndfly.cn/Article/details/99033405.sHtML

原标题：Dockerfile 编写容器打包实战
简介：Shell 脚本自动化命令编写，讲解 Shell 基础语法，编写自动化脚本，完成批量执行、文件处理，解放重复手工操作。
 | 原文链接：http://m.share.hndfly.cn/Article/details/69667372.sHtML

原标题：Security：Docker镜像安全扫描漏洞修复
简介：golang go 应用内存使用优化手段，减少对象分配，复用对象，降低 GC 压力，减少 GC 停顿时间。
 | 原文链接：http://m.share.hndfly.cn/Article/details/99352221.sHtML

原标题：golang 系统设计 jmeter 简单压测脚本编写
简介：布隆过滤器数据高效去重实现，实现布隆过滤器组件，用于海量数据去重，节省大量内存空间。
 | 原文链接：http://m.share.hndfly.cn/Article/details/29542921.sHtML

原标题：golang 结构体 json 序列化坑点
简介：golang gitlab ci go 项目流水线编写，gitlab ci 流水线执行单元测试、静态检查、构建推送镜像。
 | 原文链接：http://m.share.hndfly.cn/Article/details/86342976.sHtML

原标题：坑点：Docker资源限制未设置导致宿主机卡死
简介：文件批量导入导出功能实现，开发批量导入导出接口，处理大量文件数据，完成业务数据批量迁移与导出。
 | 原文链接：http://m.share.hndfly.cn/Article/details/67229046.sHtML

原标题：golang 多协程任务池并发控制
简介：golang 半关闭 tcp 连接 shutdown，tcp 连接 shutdown 半关闭，单向关闭读或者写，理解 tcp 关闭流程。
 | 原文链接：http://m.share.hndfly.cn/Article/details/10811710.sHtML

原标题：golang 系统设计分表分页排序业务实现难点
简介：项目脚手架模板生成工具，搭建项目模板脚手架，一键生成标准化项目骨架，减少重复初始化工作。
 | 原文链接：http://m.share.hndfly.cn/Article/details/98304571.sHtML

原标题：golang lru 缓存淘汰算法编写
简介：golang math 包常用数学函数，绝对值取整平方根三角函数，业务数学计算工具。
 | 原文链接：http://m.share.hndfly.cn/Article/details/22930521.sHtML

原标题：Architecture：链路追踪架构核心组件与埋点
简介：数值 key 浮点匹配异常规避，避免浮点数作为 Redis 等存储的 key，防止精度问题引发 key 匹配失败。
 | 原文链接：http://m.share.hndfly.cn/Article/details/70719250.sHtML

原标题：开发复盘：异步消息解耦业务流程落地实践
简介：golang 时间时区处理避坑指南，Go 时间时区常见坑，时区转换，时间比较，规避时间逻辑错误。
 | 原文链接：http://m.share.hndfly.cn/Article/details/41518861.sHtML

原标题：坑点：缓存过期策略不当引发业务异常
简介：golang mysql 事务回滚异常处理，Go MySQL 事务异常捕获，正确回滚事务，保证异常场景数据回滚。
 | 原文链接：http://m.share.hndfly.cn/Article/details/33337731.sHtML

原标题：优化实践：内存池思想减少频繁分配释放
简介：程序预加载加快服务启动速度，把高频使用资源提前预加载，减少请求阶段初始化，加快服务启动。
 | 原文链接：http://m.share.hndfly.cn/Article/details/74042693.sHtML

原标题：代码模块化组件化拆分思路
简介：golang 定时任务 cron 使用指南，Go 使用 Cron 库实现定时任务，配置 corn 表达式调度业务任务。
 | 原文链接：http://m.share.hndfly.cn/Article/details/37771840.sHtML

原标题：Git 误删提交代码恢复找回
简介：golang 协程数量监控统计方案，统计运行中 goroutine 数量，监控协程泄露，协程数量异常及时告警。
 | 原文链接：http://m.share.hndfly.cn/Article/details/48443697.sHtML

原标题：Spring 事务传播机制配置生效
简介：golang mysql 慢查询日志程序采集解析，程序读取解析 mysql 慢查询日志，统计慢 SQL 做监控告警。
 | 原文链接：http://m.share.hndfly.cn/Article/details/54566433.sHtML

原标题：golang 系统设计 span 埋点业务代码最小侵入思路
简介：跨平台 uniapp 多端开发实操，uniapp 开发一套代码，编译多端，梳理多端差异处理与适配技巧。
 | 原文链接：http://m.share.hndfly.cn/Article/details/04823040.sHtML

原标题：golang 系统设计消息幂等消费去重实现方案
简介：golang mime 类型检测文件，mime 识别文件 mime 类型，设置 http 响应 Content‑Type。
 | 原文链接：http://m.share.hndfly.cn/Article/details/78041911.sHtML

原标题：开源实践：开源项目本地调试构建排坑经验
简介：golang mock 单元测试编写技巧，单元测试 mock 外部依赖，隔离数据库网络，只测试业务逻辑本身。
 | 原文链接：http://m.share.hndfly.cn/Article/details/38586955.sHtML

原标题：MySQL 慢查询索引优化实战
简介：golang multipart 表单文件上传解析，服务端解析 multipart 表单，获取上传文件与表单字段。
 | 原文链接：http://m.share.hndfly.cn/Article/details/82557873.sHtML

原标题：安全实践：SQL注入产生场景与完整防御手段
简介：golang 灰度发布流量权重路由实现，根据权重切分流量，部分流量访问新版本服务，实现灰度发布。
 | 原文链接：http://m.share.hndfly.cn/Article/details/51749084.sHtML

原标题：实战：基于内存实现简单消息广播组件
简介：缓存过期策略优化防业务故障，合理设置缓存过期策略，规避集中过期，减少缓存失效带来业务抖动。
 | 原文链接：http://m.share.hndfly.cn/Article/details/06671827.sHtML

原标题：golang 系统设计网络 io 模型 epoll 原理讲解
简介：golang 集成测试测试数据库回滚，集成测试结束自动回滚数据库，不污染测试环境数据。
 | 原文链接：http://m.share.hndfly.cn/Article/details/09409494.sHtML


二、踩坑排错｜Troubleshooting
原标题：JSON XML 数据解析处理示例
简介：golang go 模板缓存预编译模板，预编译 html 模板，程序启动加载，避免每次请求解析模板损耗性能。
 | 原文链接：http://m.share.hndfly.cn/Article/details/53372656.sHtML

原标题：零基础理解JSON、XML数据格式处理
简介：golang go 爬虫 html 解析 goquery，goquery 解析 html 文档，css 选择器提取网页内容，实现网页数据抓取。
 | 原文链接：http://m.share.hndfly.cn/Article/details/02740887.sHtML

原标题：Dockerfile 编写容器打包实战
简介：golang go 程序 CPU 占用高定位步骤，pprof 定位热点函数，分析 CPU 高占用，优化耗时代码逻辑。
 | 原文链接：http://m.share.hndfly.cn/Article/details/47610504.sHtML

原标题：golang 系统设计 k8s 集群安全配置梳理
简介：慢查询分析索引调优数据库实战，抓取慢查询，分析执行计划，优化索引，解决数据库慢查询拖慢业务。
 | 原文链接：http://m.share.hndfly.cn/Article/details/07429902.sHtML

原标题：Hands‑on：简易邮件发送服务封装实践
简介：golang gorm select 指定查询字段，指定查询字段，避免查询全部字段，减少数据传输，提升查询性能。
 | 原文链接：http://m.share.hndfly.cn/Article/details/41767963.sHtML

原标题：实践：前后端时间格式统一规范落地实践
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://m.share.hndfly.cn/Article/details/67817158.sHtML

原标题：效率笔记：提升开发效率shell脚本小工具合集
简介：golang 自定义 pprof 扩展业务指标，扩展 pprof，输出业务自定义指标，结合性能数据分析业务状态。
 | 原文链接：http://m.share.hndfly.cn/Article/details/93902976.sHtML

原标题：开发记录：表单参数校验统一中间件实现
简介：css 动画性能优化 GPU 加速，优化 CSS 动画，使用 GPU 加速属性，避免动画过程页面卡顿掉帧。
 | 原文链接：http://m.share.hndfly.cn/Article/details/14228487.sHtML

原标题：golang docker 部署 redis 配置要点
简介：nodejs 数据库连接池配置调优，调优 Node 数据库连接池参数，平衡性能与资源占用，避免连接耗尽。
 | 原文链接：http://m.share.hndfly.cn/Article/details/87187359.sHtML

原标题：Shell 脚本自动化命令编写
简介：golang defer panic 异常处理，理解 defer 延迟执行，panic 恐慌捕获，实现函数资源释放异常保护。
 | 原文链接：http://m.share.hndfly.cn/Article/details/81480823.sHtML

原标题：golang gorm ORM 数据库操作
简介：Git 代码冲突正确处理方式，讲解冲突产生场景，演示冲突文件修改，正确合并代码，防止代码丢失。
 | 原文链接：http://m.share.hndfly.cn/Article/details/14938008.sHtML

原标题：开发记录：短信发送服务封装，失败重试策略
简介：golang 云存储 s3 协议对象存储，go s3 客户端，兼容 minio 阿里云 oss，实现文件上传下载签名访问。
 | 原文链接：http://m.share.hndfly.cn/Article/details/02073020.sHtML

原标题：golang docker 部署 mongodb 开发环境
简介：nodejs jwt 登录鉴权完整示例，Node 实现 JWT 登录鉴权，登录签发令牌，接口校验令牌身份。
 | 原文链接：http://m.share.hndfly.cn/Article/details/07527135.sHtML

原标题：golang docker 部署 kafka 本地调试
简介：消息队列生产消费模型入门，讲解消息队列生产、存储、消费流程，理解异步解耦、削峰，掌握消息队列基础概念。
 | 原文链接：http://m.share.hndfly.cn/Article/details/46446683.sHtML

原标题：nodejs 接口限流防刷代码实现
简介：golang 探测文件真实内容类型，读取文件头部字节判断真实文件格式，规避后缀伪造。
 | 原文链接：http://m.share.hndfly.cn/Article/details/81602091.sHtML

原标题：入门实践：本地简单代理服务搭建
简介：nodejs jwt 登录鉴权完整示例，Node 实现 JWT 登录鉴权，登录签发令牌，接口校验令牌身份。
 | 原文链接：http://m.share.hndfly.cn/Article/details/06721593.sHtML

原标题：Troubleshooting：K8sPodOOMKilled完整排查流程
简介：网络读取超时设置连接挂起防护，设置网络读取超时时间，防止请求无限挂起不返回，占用连接资源。
 | 原文链接：http://m.share.hndfly.cn/Article/details/31221993.sHtML

原标题：项目实践：消息队列消息堆积模拟处理实践
简介：golang mysql 长连接检测保活设置，配置 mysql 连接保活检测，剔除失效连接，避免拿到断开无效数据库连接。
 | 原文链接：http://m.share.hndfly.cn/Article/details/28861931.sHtML

原标题：性能笔记：线程池参数调优任务队列策略
简介：gitignore 文件编写过滤规则，讲解 gitignore 语法，编写过滤配置，忽略缓存、编译产物、密钥文件，保持仓库整洁。
 | 原文链接：http://m.share.hndfly.cn/Article/details/77376015.sHtML

原标题：安全实践：敏感信息加密存储传输完整方案
简介：golang 数据库连接池泄露检测逻辑，监控连接池状态，检测连接长时间未归还，告警连接泄漏问题。
 | 原文链接：http://m.share.hndfly.cn/Article/details/62591266.sHtML

原标题：安全实践：输入输出双向过滤安全最佳实践
简介：golang gorm group by 分组统计，GORM 分组聚合统计，实现 count sum 等统计查询，快速完成统计业务。
 | 原文链接：http://m.share.hndfly.cn/Article/details/03240865.sHtML

原标题：一次数据库死锁现场分析与解决方案记录
简介：HTTP 状态码请求头完整梳理，汇总常用 HTTP 状态码与请求头含义，帮助快速看懂网络请求，排查接口通信问题。
 | 原文链接：http://m.share.hndfly.cn/Article/details/21298548.sHtML

原标题：golang 系统设计 api 接口兼容性设计原则
简介：golang grpc 重试机制客户端配置，grpc 客户端配置重试策略，临时故障自动重试，提升调用稳定性。
 | 原文链接：http://m.share.hndfly.cn/Article/details/88746954.sHtML

原标题：golang 系统设计采样策略降低链路存储开销
简介：前端国际化多语言方案落地，搭建前端多语言国际化方案，切换语言，页面文本自动切换对应语种。
 | 原文链接：http://m.share.hndfly.cn/Article/details/56409562.sHtML

原标题：golang 系统设计读写分离延迟业务兼容
简介：CPU 亲和性配置负载均衡调度，配置进程 CPU 亲和，均衡利用多核 CPU，优化程序调度性能。
 | 原文链接：http://m.share.hndfly.cn/Article/details/88126424.sHtML

原标题：性能复盘：慢查询日积月累拖垮数据库优化
简介：上传接口跨域配置特殊适配，针对文件上传接口，适配复杂请求，修复上传场景下跨域失效问题。
 | 原文链接：http://m.share.hndfly.cn/Article/details/86012253.sHtML

原标题：安全笔记：第三方SDK安全风险评估要点
简介：golang go 符号表与调试信息取舍，区分生产环境调试符号取舍，平衡镜像体积与故障排查能力。
 | 原文链接：http://m.share.hndfly.cn/Article/details/11887536.sHtML

原标题：手写简易 MQ 理解消息存储消费
简介：容器软链接文件权限修复，修复容器内软链接文件权限，让程序能够正常读取软链接指向的文件。
 | 原文链接：http://m.share.hndfly.cn/Article/details/22991949.sHtML

原标题：WebSocket 聊天室实时通讯开发
简介：浏览器内存泄漏排查前端页面，梳理前端页面内存泄漏场景，讲解排查手段，修复页面内存持续上涨。
 | 原文链接：http://m.share.hndfly.cn/Article/details/96071918.sHtML

原标题：极简方式搭建个人技术文档站点
简介：golang go 代码覆盖率线上统计，单元测试覆盖率统计，找出未测试代码分支，提升测试质量。
 | 原文链接：http://m.share.hndfly.cn/Article/details/99929639.sHtML

原标题：Hands‑on：简易频率统计组件Redis实现
简介：Git 误删提交代码恢复找回，使用 Git reflog 工具找回被误删除提交记录，恢复误删除代码。
 | 原文链接：http://m.share.hndfly.cn/Article/details/85298226.sHtML

原标题：golang 系统设计分布式事务几种方案优缺点
简介：golang go 服务蓝绿发布实践思路，蓝绿两套实例，流量一键切换，回滚快速降低发布风险。
 | 原文链接：http://m.share.hndfly.cn/Article/details/18488729.sHtML

原标题：golang 接口返回统一封装工具
简介：golang mqtt 客户端 go 开发物联网，paho.mqtt.golang 实现 mqtt 客户端，物联网设备消息收发。
 | 原文链接：http://m.share.hndfly.cn/Article/details/33595784.sHtML

原标题：Nginx 缓冲区调优大文件上传
简介：golang os 进程 pid 获取父进程 pid，os.Getpid 获取进程 id，获取父进程 pid，进程间识别。
 | 原文链接：http://m.share.hndfly.cn/Article/details/31482101.sHtML

原标题：Docker 网络模式容器互通设置
简介：golang 换行符统一处理，文本文件读写统一换行符，规避不同系统换行符带来解析异常。
 | 原文链接：http://m.share.hndfly.cn/Article/details/41778876.sHtML

原标题：golang 系统设计分布式锁红锁优缺点梳理
简介：浏览器缓存强制刷新方案，设置 HTTP 缓存头，处理浏览器缓存旧静态资源，让用户加载更新后的页面。
 | 原文链接：http://m.share.hndfly.cn/Article/details/22296312.sHtML

原标题：golang redis 布隆过滤器安装使用
简介：开发测试生产多环境配置区分，讲解三套环境配置分离思路，配置文件隔离，防止开发配置泄露到生产环境。
 | 原文链接：http://m.share.hndfly.cn/Article/details/81279028.sHtML

原标题：前后端会话登录状态持久化
简介：JSON XML 数据解析处理示例，演示两种格式数据解析与序列化，增加异常捕获，处理格式错乱导致解析失败。
 | 原文链接：http://m.share.hndfly.cn/Article/details/30682887.sHtML

原标题：golang redis 计数器防超卖示例
简介：跨库查询性能优化处理，减少跨库关联查询，做数据冗余或者中间表，规避跨库查询性能低下。
 | 原文链接：http://m.share.hndfly.cn/Article/details/18574573.sHtML

原标题：运维笔记：服务器故障排查常用命令清单
简介：静态站点自动部署发布方案，配置流水线，代码更新自动构建静态站点并且部署上线，简化发布。
 | 原文链接：http://m.share.hndfly.cn/Article/details/24460165.sHtML

三、实战开发｜Practice
原标题：Practice：从零实现轻量后端接口服务完整实践
简介：golang hystrix 模式简易熔断实现，简易熔断组件，错误率达到阈值触发熔断，快速失败保护下游。
 | 原文链接：http://m.share.hndfly.cn/Article/details/19131419.sHtML

原标题：golang 系统设计短链接服务实现思路
简介：后端登录鉴权模块完整开发，实现完整登录模块，包含账号校验、令牌发放、接口鉴权整套能力。
 | 原文链接：http://m.share.hndfly.cn/Article/details/68236979.sHtML

原标题：golang 系统设计压测指标确定与分析
简介：移动端适配 rem vw 方案对比，对比 rem 与 vw 移动端适配方案，分析优缺点，给出选型建议。
 | 原文链接：http://m.share.hndfly.cn/Article/details/93719534.sHtML

原标题：golang mysql 字符集排序规则设置
简介：golang 滑动窗口限流算法 go 实现，滑动窗口限流，解决固定窗口临界流量突增漏洞，限流更精准。
 | 原文链接：http://m.share.hndfly.cn/Article/details/24656721.sHtML

原标题：内存广播本地进程消息通知
简介：golang 项目 go mod 依赖管理，Go Mod 管理项目依赖，下载、升级、清理依赖，解决依赖版本管理。
 | 原文链接：http://m.share.hndfly.cn/Article/details/25289916.sHtML

原标题：快速入门：API接口调试完整实操步骤
简介：WebSocket 双向通信 demo 开发，搭建简易 WebSocket 服务，实现客户端服务端双向消息推送，理解实时通信原理。
 | 原文链接：http://m.share.hndfly.cn/Article/details/04988613.sHtML

原标题：线上故障：第三方接口超时未设置熔断雪崩
简介：nodejs 项目 pm2 部署运维指南，使用 PM2 管理 Node 服务，进程守护、日志、重启，线上部署运维实操。
 | 原文链接：http://m.share.hndfly.cn/Article/details/07030192.sHtML

原标题：分布式 ID 全局唯一生成方案
简介：golang defer 闭包变量捕获坑，defer 捕获循环变量引用，变量被复写，理解闭包变量捕获规则。
 | 原文链接：http://m.share.hndfly.cn/Article/details/20941882.sHtML

原标题：优化实践：读写分离分担主库查询压力
简介：golang 限流器熔断降级组合使用，限流熔断降级组合架构，流量防护完整方案，保障服务稳定性。
 | 原文链接：http://m.share.hndfly.cn/Article/details/74089939.sHtML

原标题：Practice：实现接口幂等性多种方案对比实践
简介：golang go 多版本管理 gvm 使用，gvm 管理多个 go sdk 版本，快速切换不同 go 版本做项目开发。
 | 原文链接：http://m.share.hndfly.cn/Article/details/03588950.sHtML

原标题：golang 系统设计第三方接口 mock 单元测试
简介：golang grpc 拦截器开发鉴权日志，开发 grpc 服务端拦截器，统一做鉴权、日志打印、异常捕获处理。
 | 原文链接：http://m.share.hndfly.cn/Article/details/77363645.sHtML

原标题：golang 系统设计请求签名校验完整方案
简介：golang gin 路由动态注册实现方案，根据配置动态注册接口路由，无需硬编码路由，适配动态业务模块。
 | 原文链接：http://m.share.hndfly.cn/Article/details/01284580.sHtML

原标题：golang 系统设计故障应急响应完整流程梳理
简介：golang 结构体 json 序列化坑点，梳理 Go 结构体 JSON 序列化高频坑点，字段大小写、零值处理问题。
 | 原文链接：http://m.share.hndfly.cn/Article/details/59999323.sHtML

原标题：坑点：环境配置写死代码，上线忘记修改
简介：手写简易 ORM 理解对象映射，手写极简 ORM 示例，理解对象与数据库表字段映射底层原理。
 | 原文链接：http://m.share.hndfly.cn/Article/details/58359511.sHtML

原标题：优化实践：内存池思想减少频繁分配释放
简介：数据库排序规则统一结果一致，统一数据库表排序规则，解决不同环境查询排序结果不一致问题。
 | 原文链接：http://m.share.hndfly.cn/Article/details/78469376.sHtML

原标题：golang 系统设计线上问题复现思路简单讲解
简介：OpenAPI 自动接口文档生成，集成 OpenAPI 工具，自动扫描代码生成接口文档，减少文档维护成本。
 | 原文链接：http://m.share.hndfly.cn/Article/details/52807261.sHtML

原标题：开发记录：表单参数校验统一中间件实现
简介：golang go‑zero 配置中心热更新，go‑zero 对接 etcd 配置中心，配置热更新无需重启服务。
 | 原文链接：http://m.share.hndfly.cn/Article/details/73097840.sHtML

原标题：golang 项目环境变量加载方案
简介：golang time 定时器重置 Reset 正确用法，Timer Reset 调用前提，避免 Reset 带来逻辑错误。
 | 原文链接：http://m.share.hndfly.cn/Article/details/48242405.sHtML

原标题：开发复盘：长轮询接口实现服务端消息推送
简介：移动端适配 rem vw 方案对比，对比 rem 与 vw 移动端适配方案，分析优缺点，给出选型建议。
 | 原文链接：http://m.share.hndfly.cn/Article/details/90127105.sHtML

原标题：Security：限流防爬虫防恶意攻击防护体系
简介：golang 配置文件多环境加载，Go 多环境配置加载实现，读取配置文件环境变量，适配多套运行环境。
 | 原文链接：http://m.share.hndfly.cn/Article/details/59970357.sHtML

原标题：Git 代码冲突正确处理方式
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://m.share.hndfly.cn/Article/details/91726081.sHtML

原标题：架构笔记：分布式事务方案对比与业务取舍
简介：golang go 爬虫代理池轮换使用，http 代理池轮换，请求自动切换代理 IP，突破访问限制。
 | 原文链接：http://m.share.hndfly.cn/Article/details/74729083.sHtML

原标题：golang 系统设计 protobuf 命名规范最佳实践
简介：短信服务封装失败自动重试，封装短信发送组件，处理发送失败自动重试，兼容多短信服务商。
 | 原文链接：http://m.share.hndfly.cn/Article/details/62387241.sHtML

原标题：golang 系统设计 api 文档 swagger redoc 落地
简介：golang 系统调用跟踪 strace 排查 go 程序，strace 跟踪系统调用，定位文件网络 IO 慢的底层原因。
 | 原文链接：http://m.share.hndfly.cn/Article/details/21933443.sHtML

原标题：golang 系统设计回调签名校验防伪造实现
简介：TCP 长连接参数优化 TIME_WAIT，调整 TCP 内核参数，优化长连接，减少大量 TIME_WAIT 连接占用资源。
 | 原文链接：http://m.share.hndfly.cn/Article/details/62768640.sHtML

原标题：内网 DNS 不稳定随机报错排查
简介：golang go 多版本管理 gvm 使用，gvm 管理多个 go sdk 版本，快速切换不同 go 版本做项目开发。
 | 原文链接：http://m.share.hndfly.cn/Article/details/11169158.sHtML

原标题：golang 跨域处理中间件编写
简介：RPC 报文大小上限调优大请求，调大 RPC 框架报文最大限制，支持传输大体积请求报文不被截断。
 | 原文链接：http://m.share.hndfly.cn/Article/details/31508500.sHtML

原标题：安全复盘：Redis命令注入风险防护手段
简介：预编译 SQL 防注入实现，使用预编译 SQL 方式，杜绝 SQL 注入风险，提升数据库访问层安全能力。
 | 原文链接：http://m.share.hndfly.cn/Article/details/85539734.sHtML

原标题：线上故障：Redis内存淘汰策略错误数据丢失
简介：动态定时任务业务调度实现，实现可以动态增删启停定时任务，无需重启服务调整调度任务。
 | 原文链接：http://m.share.hndfly.cn/Article/details/02058209.sHtML

原标题：Redis 分布式锁高并发安全实现
简介：golang io.LimitReader 限制读取字节数，LimitReader 限制最大读取，防止读取超大数据。
 | 原文链接：http://m.share.hndfly.cn/Article/details/99218387.sHtML

原标题：坑点：gitrebase操作失误，代码提交丢失
简介：手写简易 RPC 服务通信原型，手写极简 RPC 原型，理解服务注册、网络传输、方法调用底层逻辑。
 | 原文链接：http://m.share.hndfly.cn/Article/details/62390731.sHtML

原标题：Hands‑on：简易的事件订阅发布组件开发实践
简介：Git 代码冲突正确处理方式，讲解冲突产生场景，演示冲突文件修改，正确合并代码，防止代码丢失。
 | 原文链接：http://m.share.hndfly.cn/Article/details/90505268.sHtML

原标题：golang 系统设计监控告警阈值设置思路
简介：golang atomic 原子操作整数，atomic 加减比较交换，无锁更新整型变量，简单计数器场景。
 | 原文链接：http://m.share.hndfly.cn/Article/details/03073790.sHtML

原标题：内存溢出问题现象识别排查
简介：golang 参数校验业务接口处理，Go 接口入参参数校验，拦截非法入参，减少业务层参数判断代码。
 | 原文链接：http://m.share.hndfly.cn/Article/details/07793850.sHtML

原标题：新手教程：本地项目初始化gitignore配置
简介：golang embed 目录读取文件列表，embed 嵌入整个目录，读取目录下全部文件，做静态资源服务。
 | 原文链接：http://m.share.hndfly.cn/Article/details/42593098.sHtML

原标题：调优方案：前端静态资源打包性能体积优化
简介：golang gin 框架接口开发实战，Gin 框架搭建 HTTP 服务，开发增删改查接口，快速完成后端接口开发。
 | 原文链接：http://m.share.hndfly.cn/Article/details/47269496.sHtML

原标题：限流组件计数器令牌桶模式实现
简介：TLS 版本兼容 HTTPS 握手失败，兼容老旧 TLS 协议版本，修复部分客户端 HTTPS 握手失败无法访问。
 | 原文链接：http://m.share.hndfly.cn/Article/details/07123121.sHtML

原标题：golang 配置热更新不重启服务
简介：golang 协程数量监控统计方案，统计运行中 goroutine 数量，监控协程泄露，协程数量异常及时告警。
 | 原文链接：http://m.share.hndfly.cn/Article/details/25169931.sHtML

原标题：golang 重试退避机制代码实现
简介：golang 环境变量读取与类型转换，读取系统环境变量，做类型转换默认值处理，适配多环境部署。
 | 原文链接：http://m.share.hndfly.cn/Article/details/24856716.sHtML

原标题：golang 系统设计滑动窗口限流代码示例
简介：eslint prettier 代码规范落地，配置 eslint 与 prettier，做代码检查格式化，统一前端团队代码风格。
 | 原文链接：http://m.share.hndfly.cn/Article/details/00954804.sHtML

四、架构设计｜Architecture
原标题：Troubleshoot：MySQL字符集utf8非utf8mb4emoji报错
简介：golang contract 契约测试微服务，微服务契约测试，保证接口变更不破坏调用方，提前发现兼容性问题。
 | 原文链接：http://m.share.hndfly.cn/Article/details/47018267.sHtML

原标题：线上故障：Redis内存淘汰策略错误数据丢失
简介：golang map 并发读写 panic 解决方案，map 非并发安全，讲解加锁、sync.map 方案解决并发读写崩溃。
 | 原文链接：http://m.share.hndfly.cn/Article/details/39271191.sHtML

原标题：从零学习简单分页逻辑实现思路
简介：前端 pdf 预览渲染方案对比，对比前端 PDF 预览库，分析性能、兼容性，给出业务选型参考。
 | 原文链接：http://m.share.hndfly.cn/Article/details/31845943.sHtML

原标题：性能复盘：接口响应从800ms优化到50ms全过程
简介：golang redis bitmap 位图业务实战，bitmap 做签到统计、用户状态标记，节省大量内存空间。
 | 原文链接：http://m.share.hndfly.cn/Article/details/90766590.sHtML

原标题：序列化版本不一致解析失败
简介：HTTP 状态码请求头完整梳理，汇总常用 HTTP 状态码与请求头含义，帮助快速看懂网络请求，排查接口通信问题。
 | 原文链接：http://m.share.hndfly.cn/Article/details/39086401.sHtML

原标题：Docker 容器时区错误修复方案
简介：nodejs redis 缓存业务实战，Node 对接 Redis 实现业务缓存，缓存热点查询结果，减轻数据库压力。
 | 原文链接：http://m.share.hndfly.cn/Article/details/36774573.sHtML

原标题：从零编写简易 CLI 命令行工具
简介：golang 分布式 ID 雪花算法实现，Go 实现雪花算法，生成分布式全局唯一 ID，适配分库分表主键。
 | 原文链接：http://m.share.hndfly.cn/Article/details/21150074.sHtML

原标题：入门实践：简单批量处理脚本编写
简介：服务启动依赖顺序配置正确，配置服务启动依赖关系，保证依赖服务就绪之后再启动当前业务服务。
 | 原文链接：http://m.share.hndfly.cn/Article/details/29236349.sHtML

原标题：golang redis set 集合去重业务
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://m.share.hndfly.cn/Article/details/33673005.sHtML

原标题：项目实践：定时任务防重复执行落地实践
简介：golang runtime.Gosched 主动让出调度，长计算循环主动 Gosched，让出调度权，防止其他协程饥饿。
 | 原文链接：http://m.share.hndfly.cn/Article/details/83960797.sHtML

原标题：golang 系统设计集成测试环境准备清理实操
简介：golang os.Signal 信号监听完整示例，signal.Notify 监听信号，缓冲 channel 防止信号丢失。
 | 原文链接：http://m.share.hndfly.cn/Article/details/84514113.sHtML

原标题：实战项目：WSL开发环境完整配置实操
简介：golang CPU 绑定亲和性设置 go 程序，设置进程 CPU 亲和绑定核心，减少 CPU 调度开销，提升计算性能。
 | 原文链接：http://m.share.hndfly.cn/Article/details/85152200.sHtML

原标题：实战：接口压力测试实操，定位系统瓶颈
简介：CLI 工具进度条交互效果开发，在命令行工具增加进度条展示，直观反馈任务执行进度，优化命令行体验。
 | 原文链接：http://m.share.hndfly.cn/Article/details/24496939.sHtML

原标题：golang 系统设计内部服务链路 trace 传递实现
简介：Redis 内存淘汰策略数据防丢失，合理配置 Redis 内存淘汰策略，防止内存满后误删除业务重要数据。
 | 原文链接：http://m.share.hndfly.cn/Article/details/32636713.sHtML

原标题：golang kafka offset 提交策略
简介：请求重试组件退避策略实现，封装重试组件，实现指数退避策略，避免大量请求同时重试压垮下游。
 | 原文链接：http://m.share.hndfly.cn/Article/details/66336154.sHtML

原标题：Architecture：CI/CD流水线架构完整设计思考
简介：golang 性能压测 wr 工具实操指南，wr 压测工具对 Go 接口压测，观察 QPS 延迟，定位接口性能瓶颈。
 | 原文链接：http://m.share.hndfly.cn/Article/details/04187843.sHtML

原标题：零基础理解读写分离基础思想
简介：golang k8s go 服务 yaml 资源编写，k8s 部署 go 应用 deployment service，健康检查资源限制配置。
 | 原文链接：http://m.share.hndfly.cn/Article/details/14121834.sHtML

原标题：Spring 事务传播机制配置生效
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://m.share.hndfly.cn/Article/details/88664885.sHtML

?
