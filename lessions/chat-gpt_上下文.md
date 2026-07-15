- # 《Go Backend Engineer Training Camp》持续学习上下文

  ## 一、我的学习目标

  我要系统学习 Golang，不是只学习语法，而是按照**企业级 Go 后端工程师路线**学习。

  最终目标：

  1. 掌握 Go 语言本身
  2. 掌握 Go 后端工程开发能力
  3. 掌握高并发系统设计
  4. 掌握工程化项目结构
  5. 能设计和开发 Flow Engine（流程引擎）
  6. 能理解 Go Runtime、性能优化、并发模型
  7. 最终达到可以独立设计生产级 Go 服务的水平

  ------

  # 二、课程设计要求

  请按照：

  《Go Backend Engineer Training Camp》

  形式输出。

  预计：

  约 100 节课。

  每节课都是完整课程。

  不要简单回答，要像正式培训课程。

  ------

  # 三、固定课程模板

  以后每一章保持以下结构：

  ------

  # Go Backend Engineer Training Camp

  # Module X · 模块名称

  # Lesson X · Chapter X

  # 本章标题

  ------

  ## 一句话总结本章

  用一句工程化语言总结。

  ------

  ## 本章学习目标

  说明学习完成后应该掌握：

  例如：

  - 理解 xxx 原理
  - 能实现 xxx
  - 能应用到企业项目

  ------

  # 正文教学

  要求：

  不要只列知识点。

  每个知识点需要：

  1. 是什么？
  2. 为什么需要？
  3. 怎么使用？
  4. 常见错误？
  5. 企业项目怎么使用？

  代码示例：

  使用 Go。

  代码要有解释。

  ------

  # Flow Engine 实战关联

  每一章都需要说明：

  这个知识如何应用到流程引擎。

  我的目标项目：

  Flow Engine。

  需要重点结合：

  - 流程节点执行
  - 节点调度
  - Worker
  - Scheduler
  - 状态管理
  - 任务队列
  - 并发执行
  - 节点失败处理
  - 数据持久化

  ------

  # 本章总结

  总结核心知识。

  ------

  # 今日验收标准

  必须提供：

  完成本章后：

  我应该能够：

  ✅ xxx

  ✅ xxx

  ✅ xxx

  ------

  # 今日作业

  分三个等级：

  ## Level 1

  基础理解练习

  ## Level 2

  工程代码练习

  ## Level 3

  Flow Engine 实战设计任务

  ------

  # 今日 Takeaway

  一句工程经验总结。

  ------

  # 下一章预告

  说明下一章内容。

  ------

  # 四、已经完成的课程内容

  ## Module 1：Go 基础语言

  ------

  ## Lesson 1

  完成：

  Go 基础入门。

  包括：

  - Go 环境
  - Hello World
  - 编译运行
  - package
  - main
  - 变量
  - var
  - :=
  - const
  - 基础类型
  - 条件
  - 循环
  - 函数
  - struct
  - interface
  - error

  ------

  # Lesson 2

  ## Chapter 18

  ## Defer、Panic、Recover

  学习：

  - defer 延迟执行
  - defer 执行顺序
  - defer 参数计算
  - defer 与闭包
  - defer 与返回值
  - 文件释放
  - 锁释放
  - 事务处理
  - panic
  - recover
  - 服务异常恢复
  - Flow Engine 节点异常保护

  ------

  ## Chapter 19

  ## Goroutine 并发基础

  学习：

  - 并发和并行
  - Thread 与 Goroutine
  - Go Scheduler
  - Goroutine 生命周期
  - WaitGroup
  - 数据竞争
  - Mutex
  - CSP 思想
  - Channel 初步
  - Worker Pool
  - Flow Engine 并发节点执行

  ------

  ## Chapter 20

  ## Channel 深入

  学习：

  - Channel 原理
  - 无缓冲 Channel
  - 有缓冲 Channel
  - 阻塞机制
  - close
  - range
  - select
  - timeout
  - Worker Pool
  - Task Queue
  - Result Channel
  - Flow Engine 调度模型

  ------

  ## Chapter 21

  ## Select 高级并发控制

  学习：

  - select 多路监听
  - default
  - timeout
  - Context
  - WithCancel
  - WithTimeout
  - WithDeadline
  - Done()
  - Goroutine 生命周期
  - Graceful Shutdown
  - Worker 优雅退出
  - Flow Engine 节点取消

  ------

  ## Chapter 22

  ## Sync 包深入

  学习：

  - Mutex
  - RWMutex
  - 死锁
  - 临界区
  - sync.Once
  - sync.Pool
  - atomic
  - race detector
  - 高并发缓存设计
  - Flow 状态并发安全

  ------

  ## Chapter 23

  ## Go Runtime 深入

  学习：

  - Go Runtime
  - G-M-P 模型
  - Scheduler
  - Goroutine 调度
  - 抢占式调度
  - Stack
  - Heap
  - GC
  - 三色标记
  - 内存逃逸
  - 性能优化
  - Runtime 监控

  ------

  # Module 2：Go 工程化开发

  ## Chapter 24

  ## Go Module 与项目结构

  学习：

  - package
  - import
  - export规则
  - Go Module
  - go.mod
  - go.sum
  - go mod tidy
  - cmd
  - internal
  - pkg
  - 企业项目目录设计
  - 分层架构
  - main.go 职责
  - Flow Engine 项目结构

  ------

  # 五、当前学习进度

  当前已经完成：

  ```
  Module 1
   ├── Lesson 1
   └── Lesson 2
        ├── Chapter 18
        ├── Chapter 19
        ├── Chapter 20
        ├── Chapter 21
        ├── Chapter 22
        └── Chapter 23


  Module 2
   └── Chapter 24
  ```

  ------

  # 六、下一章节继续位置

  从：

  # Module 2 · Go 工程化开发

  ## Chapter 25

  开始。

  标题：

  # 配置管理与环境设计——生产系统如何管理数据库、Redis、密钥

  内容：

  需要包括：

  - 为什么需要配置管理
  - 配置文件设计
  - YAML
  - JSON
  - TOML
  - 环境变量
  - dev/test/prod 环境
  - Config Layer设计
  - Secret管理
  - 数据库配置
  - Redis配置
  - 服务启动流程
  - Dependency Injection
  - Go 后端项目初始化

  ------

  # 七、输出风格要求

  保持当前风格：

  - 中文教学
  - 详细解释
  - 不要过度简略
  - 初学者能理解
  - 但是内容达到企业工程师水平
  - 多使用代码
  - 多解释设计原因
  - 结合真实生产系统
  - 每章必须有 Flow Engine 场景

  ------

  # 八、我的学习方式

  我会：

  - 保存每一章节
  - 上传 GitHub
  - 按章节学习
  - 完成作业后继续下一章

  所以：

  请不要跳章节。

  保持课程连续性。

  ------

  复制以上内容到新的对话即可恢复当前学习路线。你下一次只需要输入：

  **“继续”**

  即可从：

  **Chapter 25：配置管理与环境设计**

  继续。