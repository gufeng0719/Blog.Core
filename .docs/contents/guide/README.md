﻿# W 文档指南
## 亮点与优势

Blog.Core 是一个开箱即用的企业级权限管理应用框架。  
采用最新的前后端完全分离技术【 ASP.NET Core Api 5.0 + Vue 2.x 】。  
并结合 `IdentityServer4` ，可快速解决多客户端和多资源服务的统一认证与鉴权的问题。   
  
## 其他资料

博客园，早期架构搭建：[博客园](https://www.cnblogs.com/laozhang-is-phi/p/9495618.html)  
公众号，后期调整：[文章](https://mvp.neters.club/MVP_aspnetcore_2020/2020)  
视频：[B站](https://www.bilibili.com/video/BV1vC4y1p7Za)    


## 配套站点

本资源服务器，配合多个项目，构建前后端权限一体化平台，前端用 `VUE` 框架。  
前端-客户端：[预览](https://vueadmin.neters.club/)、[源码](https://github.com/anjoy8/Blog.Admin)     
前端-管理后台：[预览](http://vueblog.neters.club/)、[源码](https://github.com/anjoy8/Blog.Vue)     
认证平台：[预览](https://ids.neters.club/)、[源码](https://github.com/anjoy8/Blog.IdentityServer)       


### 为什么选择 ASPNET.Core
1、【开源】`ASPNET.NET Core` 是由 `Microsoft` 和 `.NET` 社区在 `GitHub` 上开源并维护的一个跨平台（支持 Windows、macOS 和 Linux）的新一代高性能框架，
拥有十分广泛的社区与支持者，可用于构建web应用、物联网IOT应用和移动端应用。  
2、【高效】Asp.net core(.net core)来源于.net，很容易迁移，而且也很容易上手，
但是又是不同的一个框架，除了上述对.net开发者十分友好以外，相对于之前的.net项目，速度上有巨大的改进，
相比与原来的`Web（.net framework 4.6）`程序性能提升了`2300%`。跟`python`、`java`等相同环境比较，性能都要优越，
参考[www.techempower.com](https://www.techempower.com/benchmarks/)。  
3、【跨平台】可以在`Windows`、`Mac`和`Linux`构建和运行跨平台的`Asp.Net Core`应用。  
4、【云原生】在云原生领域拥有天然的优势，搭配Azure云服务，配合K8s，更好的实现分布式应用，以及微服务应用。   
5、【微服务】`ASP.NET Core`尤其适用于微服务架构，也就是说ASP.NET Core不仅适合于中小型项目而且还特别适合于大型，超大型项目。  
6、【大公司】目前国内采用`ASP.NET Core`的大公司比如腾讯、网易，国际的有Bing，GoDaddy，Stackoverflow，Adobe，Microsoft
7、【总结来说】，`java`支持的，`ASPNET.Core`都支持，而且更轻量级、更高效跨，并且对.net开发者十分友好，微服务案例成熟。



### 框架功能点
1、丰富完整的接口文档，在查看的基础上，可以模拟前端调用，更方便。  
2、采用多层开发，隔离性更好，封装更完善。  
3、基于项目模板，可以一键创建自己的项目。  
4、搭配代码生成器，实现快速开发，节省成本。  
5、项目集成多库模式以及读写分离模式，可以同时处理多个数据库的不同模块，更快更安全。  
6、集成统一认证平台 `IdentityServer4` ，实现多个项目的统一认证管理，解决了之前一个项目，
一套用户的弊端，更适用微服务的开发。  
7、丰富的审计日志处理，方便线上项目快速定位异常点。  
8、支持自由切换多种数据库，Sqlite/SqlServer/MySql/PostgreSQL/Oracle；  
9、支持 `Docker` 容器化开发，可以搭配 k8s 更好的实现微服务。  


### 应用领域
1、【对接第三方api】项目通过`webapi`，可以快速对接第三方`api`服务，实现业务逻辑。  
2、【前后端分离】 采用的是`API`+前端的完全分离的开发模式，满足平时开发的所有需求，
你可以对接任何的自定义前端项目：无论是微信小程序，还是授权APP，无论是PC网页，
还是手机H5。  
3、【多项目】同时框架还集成了一套鉴权平台，采用IdentityServer4，可以快速的实现多个客户端的认证与授权服务，
从而大大的减少了平时的工作量，可以快速的进行产品迭代。  
4、【微服务】当然，因为采用的是API模式，所以同样适用于微服务项目，实现高并发的产品需求。  



### 市场前景
1、前后端分离模式已经是目前的主流开发模式，框架已经是一套可行的方案，开箱即用。 
2、拥有几十篇技术文档和3000人的技术社区，方便快捷的解决问题。  
3、目前已经有超过20多家公司在生产环境中使用，当然实际中更多，具体查看 [点击查看使用的情况](https://github.com/anjoy8/Blog.Core/issues/75)。  
4、同时可以搭配自己的业务，实现微服务的开发，在大数据高并发中，占有更好的优势。  
5、本项目直接作者由微软MVP“老张的哲学”出品，并长久维护，不会断更，有保障。



## 功能与进度

框架模块：  
- [√] 采用`仓储+服务+接口`的形式封装框架；
- [√] 异步 async/await 开发；
- [√] 接入国产数据库ORM组件 —— SqlSugar，封装数据库操作；
- [√] 支持自由切换多种数据库，MySql/SqlServer/Sqlite/Oracle/Postgresql/达梦/人大金仓；
- [√] 实现项目启动，自动生成种子数据 ✨； 
- [√] 五种日志记录，审计/异常/请求响应/服务操作/Sql记录等； 
- [√] 支持项目事务处理（若要分布式，用cap即可）✨；
- [√] 设计4种 AOP 切面编程，功能涵盖：日志、缓存、审计、事务 ✨；
- [√] 支持 T4 代码模板，自动生成每层代码；
- [√] 或使用 DbFirst 一键创建自己项目的四层文件（支持多库）；
- [√] 封装`Blog.Core.Webapi.Template`项目模板，一键重建自己的项目 ✨；
- [√] 搭配多个前端案例供参考和借鉴：Blog.Vue、Blog.Admin、Nuxt.tbug、Blog.Mvp.Blazor ✨；
- [√] 统一集成 IdentityServer4 认证 ✨;

组件模块：
- [√] 提供 Redis 做缓存处理；
- [√] 使用 Swagger 做api文档；
- [√] 使用 MiniProfiler 做接口性能分析 ✨；
- [√] 使用 Automapper 处理对象映射；  
- [√] 使用 AutoFac 做依赖注入容器，并提供批量服务注入 ✨；
- [√] 支持 CORS 跨域；
- [√] 封装 JWT 自定义策略授权；
- [√] 使用 Log4Net 日志框架，集成原生 ILogger 接口做日志记录；
- [√] 使用 SignalR 双工通讯 ✨；
- [√] 添加 IpRateLimiting 做 API 限流处理;
- [√] 使用 Quartz.net 做任务调度（目前单机多任务，集群调度暂不支持）;
- [√] 支持 数据库`读写分离`和多库操作 ✨;
- [√] 新增 Redis 消息队列 ✨;
- [√] 新增 RabbitMQ 消息队列 ✨;
- [√] 新增 EventBus 事件总线 ✨;
- [√] 新增 实现聚合支付;
- [ ] 计划 - 数据部门权限;
- [ ] 计划 - ES 搜索;

微服务模块：
- [√] 可配合 Docker 实现容器化；
- [√] 可配合 Jenkins 实现CI / CD；
- [√] 可配合 Consul 实现服务发现；
- [√] 可配合 Ocelot 实现网关处理；
- [√] 可配合 Nginx  实现负载均衡；
- [√] 可配合 Ids4   实现认证中心；


&nbsp;




