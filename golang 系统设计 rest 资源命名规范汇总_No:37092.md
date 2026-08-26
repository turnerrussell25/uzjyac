最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计 rest 资源命名规范汇总
简介：数据库分表路由写入分片修正，修复分表路由逻辑，保证数据写入正确分片，不会出现数据丢失错乱。
 | 原文链接：http://wiki.z26bb9.asia/arts/415551.Doc

原标题：端口占用访问失败排查方案
简介：golang gorm 事务手动回滚提交，手动控制事务流程，业务异常主动回滚，保障数据操作原子性。
 | 原文链接：http://wiki.z26bb9.asia/arts/011636.Doc

原标题：优化实践：Redis管道、批量命令减少网络往返
简介：golang accept 错误循环崩溃处理，accept 返回系统错误，处理临时错误，避免死循环占满 CPU。
 | 原文链接：http://wiki.z26bb9.asia/arts/507912.Doc

原标题：复盘总结：缓存改造业务落地踩坑复盘
简介：golang go 随机数安全与非安全，math/rand 伪随机与 crypto/rand 密码学安全随机，区分业务场景。
 | 原文链接：http://wiki.z26bb9.asia/arts/079453.Doc

原标题：Debug：静态资源缓存策略错误，用户看不到更新
简介：golang go 防止路径穿越攻击，文件操作校验路径，拒绝../ 路径穿越，禁止访问系统任意文件。
 | 原文链接：http://wiki.z26bb9.asia/arts/628171.Doc

原标题：Security：RPC调用身份认证安全加固
简介：数据库分表存储大表优化方案，对超大数据表做分表，拆分数据，降低单表数据量提升查询性能。
 | 原文链接：http://wiki.z26bb9.asia/arts/537001.Doc

原标题：实战项目：GitSubmodule管理多仓库实践
简介：golang validator 自定义校验规则，Gin Validator 自定义校验器，实现业务特殊参数校验逻辑。
 | 原文链接：http://wiki.z26bb9.asia/arts/363733.Doc

原标题：实战项目：HTTPS本地自签名证书配置实践
简介：golang 网卡 ip 读取网络信息获取，程序读取本机网卡 IP，多网卡环境筛选业务使用 IP 地址。
 | 原文链接：http://wiki.z26bb9.asia/arts/640152.Doc

原标题：golang es 聚合统计查询实现
简介：golang 微服务网关简易实现，http 反向代理、路由匹配、鉴权限流，理解网关核心原理。
 | 原文链接：http://wiki.z26bb9.asia/arts/258033.Doc

原标题：开发记录：JWT过期刷新滑动过期实现实践
简介：golang testify mock 模拟接口，mock 接口生成 mock 对象，单元测试模拟外部依赖行为。
 | 原文链接：http://wiki.z26bb9.asia/arts/348099.Doc

原标题：新手教程：如何给开源项目提交第一个PR
简介：数值 key 浮点匹配异常规避，避免浮点数作为 Redis 等存储的 key，防止精度问题引发 key 匹配失败。
 | 原文链接：http://wiki.z26bb9.asia/arts/599660.Doc

原标题：Troubleshoot：MySQL字符集utf8非utf8mb4emoji报错
简介：golang nats jetstream 持久消息队列，nats jetstream 持久化消息，保证消息不丢失，实现可靠消费。
 | 原文链接：http://wiki.z26bb9.asia/arts/088104.Doc

原标题：接口签名校验防篡改实现
简介：不必要字符转义关闭业务异常，关闭多余自动转义逻辑，防止业务数据被错误转义，破坏原始数据。
 | 原文链接：http://wiki.z26bb9.asia/arts/237511.Doc

原标题：nodejs 读取大文件 csv 处理方案
简介：golang GC 调优 GOGC 参数调整，调整 GOGC 阈值，控制 GC 触发时机，权衡内存占用与 CPU 开销。
 | 原文链接：http://wiki.z26bb9.asia/arts/422354.Doc

原标题：golang 静态文件服务搭建教程
简介：容器内存扩容 OOM 被杀死修复，调高容器内存限制，优化程序内存占用，避免程序被 OOM 终止。
 | 原文链接：http://wiki.z26bb9.asia/arts/866115.Doc

原标题：批量异步处理系统业务落地
简介：前端水印防信息泄露实现，实现网页水印功能，页面叠加用户信息水印，防止页面截图信息外泄。
 | 原文链接：http://wiki.z26bb9.asia/arts/768430.Doc

原标题：接口签名校验防篡改实现
简介：golang gorm 软删除实现逻辑，Gorm 开启软删除，删除数据仅标记，数据保留可恢复，满足业务数据留存。
 | 原文链接：http://wiki.z26bb9.asia/arts/796633.Doc

原标题：HelloGitHubPages：部署你的第一个静态博客
简介：golang socket 文件描述符继承重启，父进程传递 listener fd 给子进程，实现 go 程序零停机热重启。
 | 原文链接：http://wiki.z26bb9.asia/arts/043544.Doc

原标题：golang docker 部署 redis 配置要点
简介：操作系统内核版本适配服务，针对服务运行要求，适配操作系统内核版本，规避内核兼容 bug。
 | 原文链接：http://wiki.z26bb9.asia/arts/829930.Doc

原标题：golang 系统设计主干开发 trunk‑based 讲解
简介：golang 分布式唯一 id 多种方案对比，雪花、redis、uuid 对比各方案优缺点，指导业务选型使用。
 | 原文链接：http://wiki.z26bb9.asia/arts/574668.Doc

原标题：日志驱动异常日志不输出修复
简介：Docker 容器入门镜像实操教程，介绍 Docker 基础概念，演示镜像拉取、容器启停，帮助新手建立容器化开发认知。
 | 原文链接：http://wiki.z26bb9.asia/arts/573454.Doc

原标题：开发记录：服务优雅关闭释放资源完整实现
简介：golang go 泛型使用避坑注意点，泛型与 interface 区别，泛型性能，什么时候适合使用泛型。
 | 原文链接：http://wiki.z26bb9.asia/arts/641099.Doc

原标题：Hands‑on：本地模拟分布式锁失效场景测试
简介：静态站点自动部署发布方案，配置流水线，代码更新自动构建静态站点并且部署上线，简化发布。
 | 原文链接：http://wiki.z26bb9.asia/arts/026856.Doc

原标题：nodejs 内存溢出问题排查修复
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://wiki.z26bb9.asia/arts/201633.Doc

原标题：Nginx 反向代理路由配置实战
简介：项目语义化版本号规范管理，遵循语义化版本规范管理项目版本，明确主次版本变更含义。
 | 原文链接：http://wiki.z26bb9.asia/arts/678647.Doc

原标题：golang 系统设计 go netpoll 多路复用简单理解
简介：golang go 服务压测前后性能对比，压测记录 QPS 延迟，优化前后对比，验证优化效果。
 | 原文链接：http://wiki.z26bb9.asia/arts/459069.Doc

原标题：避坑：定时任务重复执行带来业务脏数据
简介：Nginx 反向代理路由配置实战，配置 Nginx 反向代理，实现请求转发、路由分发，掌握 Nginx 基础配置能力。
 | 原文链接：http://wiki.z26bb9.asia/arts/204587.Doc

原标题：性能笔记：连接池参数调优数据库RPC连接池
简介：nodejs 接口限流防刷代码实现，Node 层实现接口限流，限制 IP 访问频次，防护接口被恶意高频调用。
 | 原文链接：http://wiki.z26bb9.asia/arts/640300.Doc

原标题：golang html 模板渲染简单示例
简介：Cookie Session 会话状态管理，讲解 Cookie 与 Session 原理，理解登录状态保存，实现服务端会话管理逻辑。
 | 原文链接：http://wiki.z26bb9.asia/arts/457060.Doc

原标题：入门实践：项目配置文件多环境管理方案
简介：看懂报错日志快速定位问题，讲解日志阅读方法，解析堆栈信息含义，学会从报错信息中定位代码出错位置。
 | 原文链接：http://wiki.z26bb9.asia/arts/341036.Doc

原标题：项目实践：灰度发布简易方案落地实践
简介：golang raw socket 底层网络报文收发，raw socket 收发原始网络报文，做网络抓包数据包处理。
 | 原文链接：http://wiki.z26bb9.asia/arts/314336.Doc

原标题：简易日志收集集中管理方案
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://wiki.z26bb9.asia/arts/933592.Doc

原标题：Git 仓库瘦身加快克隆下载速度
简介：golang 网卡 ip 读取网络信息获取，程序读取本机网卡 IP，多网卡环境筛选业务使用 IP 地址。
 | 原文链接：http://wiki.z26bb9.asia/arts/199610.Doc

原标题：Hands‑on：简易验证码生成校验后端实践
简介：文件监控服务自动重启开发，监控项目文件变更，代码修改自动重启服务，提升本地开发调试效率。
 | 原文链接：http://wiki.z26bb9.asia/arts/334244.Doc

原标题：程序信号中断退出处理逻辑
简介：golang gin 路由动态注册实现方案，根据配置动态注册接口路由，无需硬编码路由，适配动态业务模块。
 | 原文链接：http://wiki.z26bb9.asia/arts/125709.Doc

原标题：Issue：CI脚本超时，构建任务无故终止
简介：配置与镜像分离防止信息泄露，业务配置不打包进镜像，外部挂载配置，避免密钥配置随镜像泄露。
 | 原文链接：http://wiki.z26bb9.asia/arts/357331.Doc

原标题：golang redis stream 消息队列实践
简介：GitHub Markdown 文档语法汇总，整理 Markdown 常用语法，编写仓库 README、文档，提升开源项目文档排版质量。
 | 原文链接：http://wiki.z26bb9.asia/arts/734060.Doc

原标题：部署实践：内网开发环境代理配置实践
简介：golang tcp_NODELAY 关闭延迟发送，设置 tcp_NODELAY，关闭 Nagle 算法，降低小包请求延迟。
 | 原文链接：http://wiki.z26bb9.asia/arts/208000.Doc

原标题：性能笔记：连接池参数调优数据库RPC连接池
简介：golang mysql 长连接检测保活设置，配置 mysql 连接保活检测，剔除失效连接，避免拿到断开无效数据库连接。
 | 原文链接：http://wiki.z26bb9.asia/arts/248068.Doc

原标题：避坑：批量操作未分批次，一次性内存打爆
简介：项目语义化版本号规范管理，遵循语义化版本规范管理项目版本，明确主次版本变更含义。
 | 原文链接：http://wiki.z26bb9.asia/arts/599815.Doc


二、踩坑排错｜Troubleshooting
原标题：快速入门OpenAPI文档生成基础实践
简介：golang mongodb 索引优化慢查询处理，mongodb 创建索引，分析慢查询，优化聚合查询执行性能。
 | 原文链接：http://wiki.z26bb9.asia/arts/526814.Doc

原标题：对象存储上传下载权限实操
简介：golang 文件上传下载接口开发，Go 开发文件上传下载接口，校验文件，处理文件读写存储逻辑。
 | 原文链接：http://wiki.z26bb9.asia/arts/737035.Doc

原标题：Debug：长连接未设置心跳，连接僵死不回收
简介：golang gin 静态资源访问配置，Gin 配置静态资源目录，直接对外提供静态文件访问服务。
 | 原文链接：http://wiki.z26bb9.asia/arts/684365.Doc

原标题：Practice：模拟磁盘满，验证服务降级表现
简介：golang 异步任务队列 worker 池开发，任务入数据库或 redis，worker 池消费执行，异步处理耗时业务。
 | 原文链接：http://wiki.z26bb9.asia/arts/618036.Doc

原标题：新手向：开源项目依赖安装失败排查
简介：golang 互斥锁读写锁并发安全，互斥锁读写锁实操，保护共享变量，解决多协程并发读写数据竞争。
 | 原文链接：http://wiki.z26bb9.asia/arts/777941.Doc

原标题：golang 系统设计分布式配置中心思路
简介：echarts 大数据渲染性能调优，大数据量 ECharts 图表调优，数据采样、分片渲染，解决图表卡顿。
 | 原文链接：http://wiki.z26bb9.asia/arts/632555.Doc

原标题：golang 系统设计 id 生成器选型对比
简介：echarts 大数据渲染性能调优，大数据量 ECharts 图表调优，数据采样、分片渲染，解决图表卡顿。
 | 原文链接：http://wiki.z26bb9.asia/arts/882170.Doc

原标题：golang 系统设计数据库表设计通用规范模板
简介：nodejs 内存溢出问题排查修复，Node.js 程序 OOM 排查流程，定位内存泄露，调整内存限制修复崩溃。
 | 原文链接：http://wiki.z26bb9.asia/arts/343588.Doc

原标题：golang 系统设计 monorepo 仓库管理方案
简介：移动端适配 rem vw 方案对比，对比 rem 与 vw 移动端适配方案，分析优缺点，给出选型建议。
 | 原文链接：http://wiki.z26bb9.asia/arts/600601.Doc

原标题：golang 系统设计滑动窗口限流代码示例
简介：css 动画性能优化 GPU 加速，优化 CSS 动画，使用 GPU 加速属性，避免动画过程页面卡顿掉帧。
 | 原文链接：http://wiki.z26bb9.asia/arts/356262.Doc

原标题：golang 系统设计契约测试接口兼容性保障思路
简介：golang gorm 子查询嵌套查询写法，Gorm 实现子查询、嵌套查询，复杂条件查询简化代码编写。
 | 原文链接：http://wiki.z26bb9.asia/arts/530929.Doc

原标题：golang traceId spanId 传递方案
简介：golang tar gz 压缩解压处理，tar.gz 归档压缩解压，服务端日志备份、文件打包场景使用。
 | 原文链接：http://wiki.z26bb9.asia/arts/901781.Doc

原标题：golang 优雅处理数据库事务
简介：前端打包分包加载提速方案，前端打包做代码分包，拆分大 bundle，页面按需加载，提升首屏加载速度。
 | 原文链接：http://wiki.z26bb9.asia/arts/673666.Doc

原标题：分页逻辑错误数据漏查修复
简介：golang grpc 客户端流上传数据，客户端流式请求，客户端分批上传数据到服务端，适合大文件传输。
 | 原文链接：http://wiki.z26bb9.asia/arts/711188.Doc

原标题：无用对象回收抑制内存上涨
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：http://wiki.z26bb9.asia/arts/118507.Doc

原标题：项目实践：搭建个人API网关最小实现版本
简介：golang go 项目 CI github actions 配置，github actions 实现 go 项目 ci，自动测试、代码检查、编译打包镜像。
 | 原文链接：http://wiki.z26bb9.asia/arts/081148.Doc

原标题：golang 系统设计 mq 故障降级业务策略
简介：数据库 utf8mb4 支持 emoji 存储，数据库字段设置 utf8mb4 字符集，完整支持 emoji 表情存储入库。
 | 原文链接：http://wiki.z26bb9.asia/arts/024444.Doc

原标题：golang mysql 防止 sql 注入实践
简介：golang go http 静态文件禁止目录遍历，http.FileServer 防止../ 路径穿越，了解底层安全实现。
 | 原文链接：http://wiki.z26bb9.asia/arts/430235.Doc

原标题：实践：Git工作流主干开发团队协作实践
简介：vite 项目配置与构建提速技巧，讲解 vite 配置优化手段，提升开发热更新速度与生产构建打包效率。
 | 原文链接：http://wiki.z26bb9.asia/arts/318783.Doc

原标题：文件句柄耗尽资源泄露处理
简介：golang url 参数编码处理方案，Go URL 参数编码解码，处理特殊字符，避免 URL 参数错乱。
 | 原文链接：http://wiki.z26bb9.asia/arts/855444.Doc

原标题：golang 信号量控制并发数量
简介：文件读写与异常捕获代码示例，演示文件读取写入操作，增加异常捕获逻辑，规避文件不存在、权限不足导致崩溃。
 | 原文链接：http://wiki.z26bb9.asia/arts/054363.Doc

原标题：golang rate‑limiter 限流组件
简介：golang go 包循环导入报错解决，A 导入 B B 导入 A，循环导入报错，重构代码拆分包消除循环依赖。
 | 原文链接：http://wiki.z26bb9.asia/arts/371700.Doc

原标题：复盘总结：数据库迁移升级风险评估清单
简介：golang 日志输出 stdout 标准输出规范，容器环境日志输出到 stdout，由容器平台统一采集日志文件。
 | 原文链接：http://wiki.z26bb9.asia/arts/122579.Doc

原标题：避坑：版本升级之后项目直接无法启动
简介：golang go 信号处理优雅重启实现，USR2 触发程序重启，不关闭监听 socket 实现零停机升级。
 | 原文链接：http://wiki.z26bb9.asia/arts/780583.Doc

原标题：接口请求重试容错机制实现
简介：Fork 开源项目同步上游代码，Fork 开源仓库之后，配置上游源，同步官方最新代码，保持代码版本对齐。
 | 原文链接：http://wiki.z26bb9.asia/arts/155953.Doc

原标题：golang 系统设计网关请求日志 traceId 透传实现
简介：golang go 比较运算符可比较类型，哪些类型可以直接 == 比较，map slice 函数不可直接比较。
 | 原文链接：http://wiki.z26bb9.asia/arts/234561.Doc

原标题：golang 系统设计蓝绿发布滚动发布对比
简介：golang http 重定向策略自定义，CheckRedirect 自定义重定向逻辑，限制重定向次数，防止死循环。
 | 原文链接：http://wiki.z26bb9.asia/arts/639961.Doc

原标题：golang 优雅处理数据库事务
简介：golang go 代码覆盖率线上统计，单元测试覆盖率统计，找出未测试代码分支，提升测试质量。
 | 原文链接：http://wiki.z26bb9.asia/arts/909221.Doc

原标题：Debug：静态资源缓存策略错误，用户看不到更新
简介：golang alertmanager 告警配置实践，alertmanager 配置告警路由，告警发送邮件钉钉，异常及时通知运维。
 | 原文链接：http://wiki.z26bb9.asia/arts/566388.Doc

原标题：golang 系统设计高可用服务架构梳理
简介：golang json omitempty 零值坑，omitempty 会忽略零值，区分业务是否需要输出零值字段。
 | 原文链接：http://wiki.z26bb9.asia/arts/436284.Doc

原标题：项目实践：实现数据脱敏组件支持多种脱敏规则
简介：golang accept 错误循环崩溃处理，accept 返回系统错误，处理临时错误，避免死循环占满 CPU。
 | 原文链接：http://wiki.z26bb9.asia/arts/822411.Doc

原标题：快速上手单元测试，写出第一个测试用例
简介：golang gin 参数绑定 query form json，掌握 Gin 多种参数绑定方式，适配不同请求格式参数读取。
 | 原文链接：http://wiki.z26bb9.asia/arts/832672.Doc

原标题：Hands‑on：简易ID生成雪花算法完整实现
简介：RPC 报文大小上限调优大请求，调大 RPC 框架报文最大限制，支持传输大体积请求报文不被截断。
 | 原文链接：http://wiki.z26bb9.asia/arts/576384.Doc

原标题：定时任务重复执行分布式锁
简介：golang 进程信号捕获 SIGUSR 自定义信号，捕获用户自定义信号，实现线上不重启触发调试、日志切换。
 | 原文链接：http://wiki.z26bb9.asia/arts/903056.Doc

原标题：golang 系统设计开源项目安全漏洞处理流程
简介：golang gorm 索引设置与优化技巧，定义数据库索引，理解索引生效条件，避免索引失效慢查询。
 | 原文链接：http://wiki.z26bb9.asia/arts/088841.Doc

原标题：安全笔记：HTTPSTLS配置安全加固实践
简介：接口签名验签完整安全方案，一套完整接口签名方案，包含签名生成、请求携带、服务端验签校验。
 | 原文链接：http://wiki.z26bb9.asia/arts/862655.Doc

原标题：架构复盘：系统扩容缩容架构无状态优先原则
简介：golang go mod tidy 依赖清理，go mod tidy 自动增删依赖，整理 go.mod go.sum 文件。
 | 原文链接：http://wiki.z26bb9.asia/arts/382541.Doc

原标题：快速上手简单性能监控指标查看
简介：nestjs 拦截器过滤器管道实战，实操 Nest 拦截器、异常过滤器、管道校验，处理请求与响应统一逻辑。
 | 原文链接：http://wiki.z26bb9.asia/arts/634103.Doc

原标题：Troubleshoot：RPC序列化对象字段增减兼容踩坑
简介：开源项目构建失败排查步骤，梳理构建报错排查流程，从依赖、网络、权限、脚本多角度定位项目构建失败原因。
 | 原文链接：http://wiki.z26bb9.asia/arts/292773.Doc

原标题：设计思考：业务系统如何设计优雅失败架构
简介：golang 压缩 zip 文件生成解压，golang 实现 zip 压缩打包，解压 zip 归档文件，处理批量文件归档。
 | 原文链接：http://wiki.z26bb9.asia/arts/660958.Doc

三、实战开发｜Practice
原标题：Issue：WSL2内存持续暴涨不自动释放
简介：golang docker 镜像构建最佳实践，Go 项目 Docker 镜像构建最佳实践，减小镜像体积，安全构建。
 | 原文链接：http://wiki.z26bb9.asia/arts/750664.Doc

原标题：golang k8s 日志收集 efk 简单架构
简介：时间同步修复令牌提前过期，服务器时间不同步导致 JWT 令牌提前过期，同步系统时间解决异常。
 | 原文链接：http://wiki.z26bb9.asia/arts/707955.Doc

原标题：Docker 网络模式容器互通设置
简介：golang go 时间 time.Timer time.Ticker，定时器与周期定时器，Stop Reset 正确使用，防止资源泄漏。
 | 原文链接：http://wiki.z26bb9.asia/arts/263957.Doc

原标题：golang 系统设计批量处理优化业务性能
简介：golang go 比较运算符可比较类型，哪些类型可以直接 == 比较，map slice 函数不可直接比较。
 | 原文链接：http://wiki.z26bb9.asia/arts/384594.Doc

原标题：Performance：数据库索引优化常见错误案例
简介：全平台系统环境变量配置，汇总多操作系统环境变量配置方法，统一项目读取逻辑，适配不同运行平台。
 | 原文链接：http://wiki.z26bb9.asia/arts/669123.Doc

原标题：线上异常：接口偶发超时，完整定位过程记录
简介：golang docker 镜像构建最佳实践，Go 项目 Docker 镜像构建最佳实践，减小镜像体积，安全构建。
 | 原文链接：http://wiki.z26bb9.asia/arts/730368.Doc

原标题：程序预加载加快服务启动速度
简介：golang http client 连接池调优，调优 Go HTTP Client 连接池参数，复用 TCP 连接，减少连接创建开销。
 | 原文链接：http://wiki.z26bb9.asia/arts/370232.Doc

原标题：golang 错误处理最佳实践汇总
简介：golang grpc 拦截器开发鉴权日志，开发 grpc 服务端拦截器，统一做鉴权、日志打印、异常捕获处理。
 | 原文链接：http://wiki.z26bb9.asia/arts/722883.Doc

原标题：golang 系统设计缓存优化落地实操指南
简介：nodejs 集成测试业务流程编写，编写 Node 集成测试，调用真实接口，验证完整业务链路执行结果。
 | 原文链接：http://wiki.z26bb9.asia/arts/192994.Doc

原标题：线上故障：Redis内存淘汰策略错误数据丢失
简介：golang go 值传递引用传递理解，go 全部为值传递，指针本质拷贝指针值，理清参数传递行为。
 | 原文链接：http://wiki.z26bb9.asia/arts/028743.Doc

原标题：golang k8s liveness readiness 探针
简介：nodejs 跨域中间件配置细节，Express 跨域中间件配置细节，处理预检请求，修复偶现跨域失效。
 | 原文链接：http://wiki.z26bb9.asia/arts/714032.Doc

原标题：线上异常：接口偶发超时，完整定位过程记录
简介：golang 跨域处理中间件编写，Gin 跨域中间件开发，处理预检 OPTIONS 请求，解决浏览器跨域报错。
 | 原文链接：http://wiki.z26bb9.asia/arts/910934.Doc

原标题：golang 系统设计分表扩容数据平滑迁移思路
简介：gRPC 服务端客户端入门示例，搭建 gRPC 服务端与调用客户端，学习 protobuf 定义，掌握 RPC 基础开发流程。
 | 原文链接：http://wiki.z26bb9.asia/arts/815481.Doc

原标题：线上异常：布隆过滤器误判造成业务逻辑异常
简介：数据库事务 ACID 原理讲解，拆解事务四大特性，理解事务隔离、原子性，明白事务如何保障数据安全。
 | 原文链接：http://wiki.z26bb9.asia/arts/126259.Doc

原标题：golang mysql 读写分离简单实现
简介：golang go cover 覆盖率报告生成，go test‑cover 生成测试覆盖率，html 可视化查看未覆盖代码行。
 | 原文链接：http://wiki.z26bb9.asia/arts/045884.Doc

原标题：运维笔记：服务器日志轮转logrotate配置
简介：数据库分表路由写入分片修正，修复分表路由逻辑，保证数据写入正确分片，不会出现数据丢失错乱。
 | 原文链接：http://wiki.z26bb9.asia/arts/471736.Doc

原标题：架构复盘：供应链安全架构依赖包风险治理
简介：golang 开发环境快速搭建指南，快速完成 Golang 开发环境配置，工具链安装，环境变量设置，准备开发。
 | 原文链接：http://wiki.z26bb9.asia/arts/351592.Doc

原标题：golang 系统设计 sql 注入 xss 防护实践
简介：rebase 操作防止代码丢失，讲解 rebase 风险点，操作前做好备份，规避错误操作造成代码提交丢失。
 | 原文链接：http://wiki.z26bb9.asia/arts/536078.Doc

原标题：golang 系统设计压测环境隔离避免影响生产
简介：golang context 超时取消实战案例，使用 context 控制协程、http 请求超时，自动终止超时任务，避免协程无限阻塞。
 | 原文链接：http://wiki.z26bb9.asia/arts/899882.Doc

原标题：本地简易配置中心动态管理
简介：重复提交幂等防护再次讲解，梳理前端重复点击、网络重试场景，落地接口幂等，杜绝重复业务。
 | 原文链接：http://wiki.z26bb9.asia/arts/777585.Doc

原标题：安全笔记：依赖包漏洞检测供应链安全
简介：golang cgo 性能开销避坑指南，cgo 调用开销，减少频繁 cgo 调用，规避 cgo 带来内存泄漏风险。
 | 原文链接：http://wiki.z26bb9.asia/arts/515439.Doc

原标题：DevOps：容器健康探针livenessreadiness配置
简介：golang tcp 四次挥手 go 程序行为，理解 tcp 四次挥手，处理连接关闭、重置、RST 包异常场景。
 | 原文链接：http://wiki.z26bb9.asia/arts/715427.Doc

原标题：golang 优雅停机服务关闭实现
简介：数据库分表路由写入分片修正，修复分表路由逻辑，保证数据写入正确分片，不会出现数据丢失错乱。
 | 原文链接：http://wiki.z26bb9.asia/arts/552030.Doc

原标题：golang ci 流水线漏洞扫描依赖检查
简介：nodejs 日志轮转生产环境配置，配置 Node 日志轮转切割，防止日志文件无限变大，适配生产环境。
 | 原文链接：http://wiki.z26bb9.asia/arts/751334.Doc

原标题：优化实践：读写分离分担主库查询压力
简介：golang http 服务优雅关闭完整示例，接收终止信号，停止接收新请求，等待现有请求处理完毕后退出服务。
 | 原文链接：http://wiki.z26bb9.asia/arts/599656.Doc

原标题：零基础理解跨域问题产生原因与基础方案
简介：内存广播本地进程消息通知，实现进程内内存消息广播，进程内部模块之间事件通知解耦。
 | 原文链接：http://wiki.z26bb9.asia/arts/078033.Doc

原标题：内存泄漏定位分析完整流程
简介：批量数据处理脚本编写技巧，编写脚本批量处理大量业务数据，循环处理、分批执行，提升数据处理效率。
 | 原文链接：http://wiki.z26bb9.asia/arts/723553.Doc

原标题：ICMP 放通网络丢包问题修复
简介：GraphQL 接口查询优化实操，体验 GraphQL 查询方式，按需获取字段，减少冗余数据传输，优化接口请求效率。
 | 原文链接：http://wiki.z26bb9.asia/arts/166413.Doc

原标题：golang 系统设计消息队列降级业务开关实现
简介：golang CPU 绑定亲和性设置 go 程序，设置进程 CPU 亲和绑定核心，减少 CPU 调度开销，提升计算性能。
 | 原文链接：http://wiki.z26bb9.asia/arts/751200.Doc

原标题：消息队列重复消费业务处理
简介：golang 简单爬虫请求防封禁，简易 Go 爬虫实现，增加请求间隔、UA 伪装，规避被目标站点封禁 IP。
 | 原文链接：http://wiki.z26bb9.asia/arts/043266.Doc

原标题：golang 系统设计链路数据存储选型对比讲解
简介：golang go 优雅处理信号丢失场景，处理信号丢失、信号被忽略，保障程序可以正常接收终止信号。
 | 原文链接：http://wiki.z26bb9.asia/arts/104254.Doc

原标题：开发复盘：消息队列消息顺序性业务落地实践
简介：golang 信号捕获程序退出处理，Go 捕获操作系统信号，做资源回收，控制程序退出流程。
 | 原文链接：http://wiki.z26bb9.asia/arts/149723.Doc

原标题：golang 系统设计延迟消息实现几种方案对比
简介：golang go 防止路径穿越攻击，文件操作校验路径，拒绝../ 路径穿越，禁止访问系统任意文件。
 | 原文链接：http://wiki.z26bb9.asia/arts/614802.Doc

原标题：golang 系统设计分布式锁看门狗续期原理理解
简介：服务健康检查告警监控体系，搭建健康检查加告警体系，服务异常及时推送告警通知运维人员。
 | 原文链接：http://wiki.z26bb9.asia/arts/449575.Doc

原标题：golang docker 镜像体积优化技巧
简介：golang hertz 反向代理与负载均衡，hertz 实现反向代理，内置负载均衡，快速搭建网关类服务。
 | 原文链接：http://wiki.z26bb9.asia/arts/195808.Doc

原标题：异步异常捕获避免进程崩溃
简介：rebase 操作防止代码丢失，讲解 rebase 风险点，操作前做好备份，规避错误操作造成代码提交丢失。
 | 原文链接：http://wiki.z26bb9.asia/arts/485461.Doc

原标题：排错：GitLFS大文件推送失败完整排障
简介：express 中间件开发业务实践，开发 Express 自定义中间件，拦截请求，实现鉴权、日志记录等通用逻辑。
 | 原文链接：http://wiki.z26bb9.asia/arts/692545.Doc

原标题：Debug：预加载逻辑错误服务启动时间成倍拉长
简介：golang 项目 go mod 依赖管理，Go Mod 管理项目依赖，下载、升级、清理依赖，解决依赖版本管理。
 | 原文链接：http://wiki.z26bb9.asia/arts/773101.Doc

原标题：golang 系统设计限流熔断降级组合使用
简介：golang strings.Builder 字符串高效拼接，strings.Builder 做字符串拼接，比 += 性能更高，减少内存拷贝。
 | 原文链接：http://wiki.z26bb9.asia/arts/054130.Doc

原标题：golang 系统设计配置中心核心能力梳理讲解
简介：golang 命令行彩色输出终端，终端彩色文字输出，进度条交互，优化命令行工具用户体验。
 | 原文链接：http://wiki.z26bb9.asia/arts/498911.Doc

四、架构设计｜Architecture
原标题：golang 系统设计告警分级 p0‑p3 定义处理流程
简介：消息队列生产消费模型入门，讲解消息队列生产、存储、消费流程，理解异步解耦、削峰，掌握消息队列基础概念。
 | 原文链接：http://wiki.z26bb9.asia/arts/566913.Doc

原标题：Troubleshooting：代理环境下证书校验失败HTTPS报错
简介：golang sql 注入风险规避要点，参数化查询杜绝 sql 注入，禁止字符串拼接 SQL 语句执行。
 | 原文链接：http://wiki.z26bb9.asia/arts/901030.Doc

原标题：golang 系统设计用户签到统计方案
简介：golang md5 sha 加密工具实现，实现 MD5、SHA 哈希工具，做数据摘要，用于签名校验场景。
 | 原文链接：http://wiki.z26bb9.asia/arts/673204.Doc

原标题：排错：对象存储跨域配置不生效前端上传失败
简介：golang 雪花算法 workId 自动获取，自动获取机器 workId，不用手动配置，简化分布式 id 部署。
 | 原文链接：http://wiki.z26bb9.asia/arts/836708.Doc

原标题：前端国际化多语言方案落地
简介：golang 错误处理最佳实践汇总，Go 错误处理规范，包装错误，堆栈携带，拒绝简单忽略错误。
 | 原文链接：http://wiki.z26bb9.asia/arts/596986.Doc

原标题：Issue：系统fd快速上涨进程慢慢卡死
简介：golang testing.TB Helper 标记辅助函数，t.Helper 标记辅助函数，报错打印真实调用位置。
 | 原文链接：http://wiki.z26bb9.asia/arts/489115.Doc

原标题：golang 系统设计一致性哈希原理讲解
简介：CI/CD 流水线自动构建部署落地，搭建完整 CI/CD 流水线，代码提交自动构建、测试、部署到目标环境。
 | 原文链接：http://wiki.z26bb9.asia/arts/902415.Doc

原标题：本地简易配置中心动态管理
简介：从零编写简易 CLI 命令行工具，通过实战案例实现基础命令交互，理解命令行程序执行逻辑，产出可运行小工具。
 | 原文链接：http://wiki.z26bb9.asia/arts/125632.Doc

原标题：golang 系统设计 sql 注入 xss 防护实践
简介：golang recover 捕获 panic 使用边界，recover 只在 defer 内部生效，协程内部必须捕获本协程 panic。
 | 原文链接：http://wiki.z26bb9.asia/arts/152406.Doc

原标题：浏览器内存泄漏排查前端页面
简介：GraphQL 接口查询优化实操，体验 GraphQL 查询方式，按需获取字段，减少冗余数据传输，优化接口请求效率。
 | 原文链接：http://wiki.z26bb9.asia/arts/152149.Doc

原标题：golang 系统设计故障复盘模板 postmortem 参考
简介：golang go mod graph 可视化依赖图，可视化 go 依赖关系，直观看到包之间依赖，定位冲突。
 | 原文链接：http://wiki.z26bb9.asia/arts/165220.Doc

原标题：golang kafka 消费者偏移量管理
简介：golang aes cbc gcm 模式加密对比，AES‑CBC AES‑GCM 模式加密解密，理解两种模式差异选型。
 | 原文链接：http://wiki.z26bb9.asia/arts/017865.Doc

原标题：架构笔记：事件驱动架构适用场景与坑点
简介：DNS 解析异常第三方调用故障，排查 DNS 解析故障，修复域名解析，恢复第三方接口网络调用。
 | 原文链接：http://wiki.z26bb9.asia/arts/400343.Doc

原标题：golang 系统设计 cpu 高占用排查步骤
简介：golang go 排序 sort 包自定义排序，sort 包实现自定义排序逻辑，对切片按业务规则排序。
 | 原文链接：http://wiki.z26bb9.asia/arts/566394.Doc

原标题：调优方案：消息队列消费速度优化处理堆积
简介：golang tcp keepalive 参数程序配置，go 程序设置 tcp keepalive，操作系统 tcp 保活参数，清理僵死连接。
 | 原文链接：http://wiki.z26bb9.asia/arts/014184.Doc

原标题：新手指南：本地多版本环境共存配置
简介：大文件导出内存溢出防护，流式处理大文件导出，边读边写，不把全部数据加载内存，规避 OOM。
 | 原文链接：http://wiki.z26bb9.asia/arts/185594.Doc

原标题：实战：Nginx实现文件限速下载配置实践
简介：模拟登录鉴权权限判断示例，实现简易登录流程，会话状态维护，完成接口权限校验，理解身份鉴权基础逻辑。
 | 原文链接：http://wiki.z26bb9.asia/arts/898503.Doc

原标题：golang es 更新文档注意版本冲突
简介：golang go 项目依赖冲突解决完整思路，定位冲突包，replace、exclude、升级降级解决版本冲突。
 | 原文链接：http://wiki.z26bb9.asia/arts/641503.Doc

?
