# businessworks - 基础业务集成开发平台


#一.Overview
> 当前业务系统已经形成了一个庞大的生态，各种新老系统，中间件在一起完成业务功能，在维护系统，开发新业务的过程中，感受到了越来越大的压力。
旧的系统必须维护改造，新的系统业务能够快速发展，新旧系统之间都需要互联互通，如果我们能有效的在实施EIP，将会对我们系统的架构升级，服务能力，业务快速发展提供保障。

>Businesworks的设计目标是为复杂业务系统提供平台化的底层支持，所谓平台化，就是对业务开发能以扩展，隔离的方式推进，驱动业务快速支持。

>专门为复杂业务系统而设计，达到以下设计目标：

 - 1.业务和平台分离。
 平台将不关心具体的业务，只通过抽象统一的模型去完成业务逻辑。平台提供定制扩展机制，方便业务方通过定制扩展开发实现自己的业务需求。
 - 2.业务隔离
 业务方将作为平台的ISV(Independent Software Vendors)，通过交易平台，设计开发自己的业务。各业务方完全隔离，如果需要对方提供的服务，该业务方可以通过平台注册提供服务。对于调用者来着，这互相彼此完全透明。业务方只和平台打交道。
 - 3.变化和实现分离
 在复杂业务平台系统中，业务变动需求频繁，比如大促期间，招商平台需要对玩法，招商流程等进行快速调整。因此我们需要把业务变化通过规则引擎管理起来，实现变化与实现分离，通过规则引擎去快速响应需求变化而不是硬编码实现，从而提高业务服务能力和系统稳定性。
 - 4.职责功能分离
 系统实现通过plugin形式实现，通过在平台的注册提供服务，形成微服务架构，减少系统之间耦合，使系统实现简明规范，并且系统之间易于通过事件驱动方式协调，提高系统性能和稳定。


#二.文档说明
> docs/Roadmap 路线图
> docs/Roadmap  概要设计



##参考文章
- 1.平台化三部曲之一微核心可扩展架构——从Eclipse平台看交易平台化 https://yq.aliyun.com/articles/38
- 2.平台化三部曲之二模块化开发——Google Guice 平台模块化开发的果汁 https://yq.aliyun.com/articles/39
- 3.平台化三部曲之三流程编排——平台化是舞台，流程编排就是导演一场戏 https://yq.aliyun.com/articles/772
- 4.基础业务集成开发平台(BusinessWorks) - 概要设计篇 https://yq.aliyun.com/articles/47515
- 5.基础业务集成开发平台(BusinessWorks) - 业务开发篇 https://yq.aliyun.com/articles/47523


