---
title: Update record
date: 2022-06-01 14:31:18
permalink: /pages/88c2d1/
---

:::tip v2.9.3

增强 #I5XWL2 数据库插件支持脚本的存储

https://gitee.com/dromara/liteFlow/issues/I5XWL2

增强 #I605FA 支持etcd分离chain以及脚本的存储结构

https://gitee.com/dromara/liteFlow/issues/I605FA

增强 #I5ZLH6 支持zk分离chain以及脚本的存储结构

https://gitee.com/dromara/liteFlow/issues/I5ZLH6

增强 #I5Y92X 支持选择组件跳转同时指定组件名和标签

https://gitee.com/dromara/liteFlow/issues/I5Y92X

增强 #I5ULVA 修正不规范的问题，chain的name和id混用，不太严谨

https://gitee.com/dromara/liteFlow/issues/I5ULVA

修复 #I5ZS92 希望能直接获取组件参数的原始字符串，而不是只能获取转换后的 JSON 对象

https://gitee.com/dromara/liteFlow/issues/I5ZS92

修复 #I5YEHG 脚本的加载有先后顺序问题

https://gitee.com/dromara/liteFlow/issues/I5YEHG

修复 #I5ZS8I 修复EL中定义的tag和data中的字符串的空格和换行被过滤掉了的现象

https://gitee.com/dromara/liteFlow/issues/I5ZS8I

:::

:::tip v2.9.2

修复 2.9.1在Nacos场景启动失败的bug

:::

:::tip v2.9.1

特性 #I5WNMG 脚本组件支持javascript的语法

https://gitee.com/dromara/liteFlow/issues/I5WNMG

增强 #I5X7IT rule-source-ext-data支持在springboot yml配置文件中的原生配置

https://gitee.com/dromara/liteFlow/issues/I5X7IT

增强 #I5X1O6 提升安全性，更新不安全的第三方依赖

https://gitee.com/dromara/liteFlow/issues/I5X1O6

增强 #I5RV3G 规则插件的报错无法抛出来

https://gitee.com/dromara/liteFlow/issues/I5RV3G

增强 #I5XB03 增加dtd文件，加强xml的提示

https://gitee.com/dromara/liteFlow/issues/I5XB03

增强 #I5P263 脚本执行异常，出现异常的处理

https://gitee.com/dromara/liteFlow/issues/I5P263

修复 #I5WSG9 2.9.0版本 tag在 WHEN 下不生效

https://gitee.com/dromara/liteFlow/issues/I5WSG9

修复 #I5WLQW 扫描@ScriptBean修饰的类使用的hutool工具类不支持kotlin导致堆栈溢出

https://gitee.com/dromara/liteFlow/issues/I5WLQW

:::

:::tip v2.9.0

特性 #I5RV5D 循环表达式特性的增加

https://gitee.com/dromara/liteFlow/issues/I5RV5D

特性 #I5ROOR 增加关系型数据库规则存储插件的支持

https://gitee.com/dromara/liteFlow/issues/I5ROOR

特性 #I4I5WZ 增加nacos存储规则插件的支持

https://gitee.com/dromara/liteFlow/issues/I4I5WZ

特性 #I5R005 添加Etcd存储规则插件的支持

https://gitee.com/dromara/liteFlow/issues/I5R005

特性 #I5QCHL 支持在method级别声明式特性

https://gitee.com/dromara/liteFlow/issues/I5QCHL

特性 #I5RV4W 加强脚本和java之间的互动

https://gitee.com/dromara/liteFlow/issues/I5RV4W

特性 #I5U3RC 支持组件级别的规则参数配置

https://gitee.com/dromara/liteFlow/issues/I5U3RC

特性 #I5RG4H 选择组件支持组件标签选择

https://gitee.com/dromara/liteFlow/issues/I5RG4H

增强 #I5SYC8 支持同一组件不同组件ID的定义

https://gitee.com/dromara/liteFlow/issues/I5SYC8

增强 #I5QMDZ 把Zk存储的支持拆出来作为插件解耦合

https://gitee.com/dromara/liteFlow/issues/I5QMDZ

增强 #I5U1FH 去除老的表达式的支持，精简代码

https://gitee.com/dromara/liteFlow/issues/I5U1FH

增强 #I5Q3A7 优化QLExpress的Runner初始化

https://gitee.com/dromara/liteFlow/issues/I5Q3A7

增强 #I5U5O6 对声明式类&方法进行了重构，提升了使用友好度

https://gitee.com/dromara/liteFlow/issues/I5U5O6

增强 #I5T4LS 优化 FlowParserProvider 类

https://gitee.com/dromara/liteFlow/issues/I5T4LS

增强 #I5Q3SS 对于el表达式里的未定义的子表达式和未注册的node进行编译时检查

https://gitee.com/dromara/liteFlow/issues/I5Q3SS

增强 #I5OFMU 优化 Operator 代码

https://gitee.com/dromara/liteFlow/issues/I5OFMU

修复 #I5PK9Q 隐式流程里的异常会导致主流程里的异常发生

https://gitee.com/dromara/liteFlow/issues/I5PK9Q

修复 #I5PFLG 组件统计耗时未统计后置处理

https://gitee.com/dromara/liteFlow/issues/I5PFLG

:::

:::tip v2.8.5

特性 #I5KTST IF三元符语法的添加以及IF ELIF ELSE语法的添加

https://gitee.com/dromara/liteFlow/issues/I5KTST

增强 #I5O22X 增加EL解析中的报错详细信息

https://gitee.com/dromara/liteFlow/issues/I5O22X

增强 #I5MZJY 解决循环调用同步的隐式流程，参数只能取一次的问题

https://gitee.com/dromara/liteFlow/issues/I5MZJY

修复 #I5NH56 switch组件对于cglib代理过的bean目前处理的不够全面

https://gitee.com/dromara/liteFlow/issues/I5NH56

修复 I5NFV3 在zk集群中多个zk地址不生效的bug

https://gitee.com/dromara/liteFlow/issues/I5NFV3

:::

:::tip v2.8.4

特性 #I5M34O 支持在流程执行前就传入一个初始化好的context对象的特性

https://gitee.com/dromara/liteFlow/issues/I5M34O

增强 #I5LY8B 增强SwitchCondition里面的targetMap无法get到的问题

https://gitee.com/dromara/liteFlow/issues/I5LY8B

增强 #I5KAMF 是否可以增加自定义配置哪些异常类型日志不打印

https://gitee.com/dromara/liteFlow/issues/I5KAMF

增强 #I5EU86 把fastjson替换成jackson

https://gitee.com/dromara/liteFlow/issues/I5EU86

修复 #I5KJFP Switch组件如果被spring动态代理后，无法取到跳转到的目标节点的问题

https://gitee.com/dromara/liteFlow/issues/I5KJFP

:::

:::tip v2.8.3

特性 #I5IA5U 提供节点包装语法+替补节点的功能

https://gitee.com/dromara/liteFlow/issues/I5IA5U

增强 #I5IOC5 LiteFlowResponse提供errorCode的功能

https://gitee.com/dromara/liteFlow/issues/I5IOC5

增强 #I5IJLN 支持脚本里获取requestData

https://gitee.com/dromara/liteFlow/issues/I5IJLN

增强 #I5I1QH 重构查找解析器的代码

https://gitee.com/dromara/liteFlow/issues/I5I1QH

:::

:::tip v2.8.2

增强 #I5GBXI 支持EL中任意地方的注释

https://gitee.com/dromara/liteFlow/issues/I5GBXI

增强 #I5GD1G 在CmpStep中增加tag的属性

https://gitee.com/dromara/liteFlow/issues/I5GD1G

增强 #I5CBYT 框架内多次打印错误日志，希望可以关闭或调整打印次数

https://gitee.com/dromara/liteFlow/issues/I5CBYT

增强 #I5GS5F 优化Id生成器的Holder类的逻辑

https://gitee.com/dromara/liteFlow/issues/I5GS5F

修复 #I5GYX3 SWITCH不能只路由到1个节点的问题

https://gitee.com/dromara/liteFlow/issues/I5GYX3

修复 #I5F73R 隐式子流程如果是并发的，则初始参数在并发中会被覆盖的问题

https://gitee.com/dromara/liteFlow/issues/I5F73R

修复 #I5HBJC 当有并行子流程的时候，获取当前chainName有bug

https://gitee.com/dromara/liteFlow/issues/I5HBJC

:::

:::tip v2.8.1

增强 #I5FNR4 减少Liteflow核心包对第三方包的依赖

https://gitee.com/dromara/liteFlow/issues/I5FNR4

增强 #I5FV48 同样的规则，在用代码加载时不应该每次都被解析一遍

https://gitee.com/dromara/liteFlow/issues/I5FV48

修复 #I5G9L0 在相同组件执行完之后，取steps的时候，存在报错现象

https://gitee.com/dromara/liteFlow/issues/I5G9L0

:::

:::tip v2.8.0

特性 #I5CW7I 【版本特性】构造全新的EL规则表达式

https://gitee.com/dromara/liteFlow/issues/I5CW7I

特性 #I5CHYH 提供多上下文支持的特性

https://gitee.com/dromara/liteFlow/issues/I5CHYH

特性 #I5CJHI 支持requestId的自定义生成器

https://gitee.com/dromara/liteFlow/issues/I5CJHI

增强 #I5BR8P 组件打印信息，希望能定制带上别名

https://gitee.com/dromara/liteFlow/issues/I5BR8P

增强 #I4TGGV 子流程中的finally节点没有执行

https://gitee.com/dromara/liteFlow/issues/I4TGGV

增强 #I5BGGK 引入的dom4j 1.6.1版本报安全性问题，麻烦升级一下

https://gitee.com/dromara/liteFlow/issues/I5BGGK

增强 #I5BR5M chain重名的检测

https://gitee.com/dromara/liteFlow/issues/I5BR5M

增强 #I5BRFN 提取公共方法减少重复代码，去除魔法值

https://gitee.com/dromara/liteFlow/issues/I5BRFN

增强 #I5BVCU 改变核心结构，Condition也成为一个可执行单元

https://gitee.com/dromara/liteFlow/issues/I5BVCU

增强 #I5C3OC 增加xml的dtd文件，从而提供格式输入提示和较验

https://gitee.com/dromara/liteFlow/issues/I5C3OC

增强 #I5CHYJ 去除FlowExecutor中直接返回上下文的执行方法

https://gitee.com/dromara/liteFlow/issues/I5CHYJ

增强 #I5CW1E 调整LiteflowConfig包装类型

https://gitee.com/dromara/liteFlow/issues/I5CW1E

增强 #I5D89I 内部新增switchCondition，把选择组件独立出来做，更好的扩展

https://gitee.com/dromara/liteFlow/issues/I5D89I

增强 #I5DEGQ 增加Switch的节点类型，以替换cond节点的的定义

https://gitee.com/dromara/liteFlow/issues/I5DEGQ

增强 #I5E17C 对parser结构提取公共方法减少重复代码

https://gitee.com/dromara/liteFlow/issues/I5E17C

修复 #I58VZD 流程多次使用同一个条件组件问题

https://gitee.com/dromara/liteFlow/issues/I58VZD

修复 #I4IOLB when在解析时某些情况下不会合并

https://gitee.com/dromara/liteFlow/issues/I4IOLB

:::

:::tip v2.7.3

修复 #I5CB1Y 声明式组件无法进入beforeProcess和afterProcess方法

https://gitee.com/dromara/liteFlow/issues/I5CB1Y

修复 #I5C7LM 声明式组件的方法名自定义会出问题

https://gitee.com/dromara/liteFlow/issues/I5C7LM

:::

:::tip v2.7.2

修复 #I5BZW7 隐式流程的requestData获取不到的问题

https://gitee.com/dromara/liteFlow/issues/I5BZW7

修复 #I5C23U 子流程用getChainName取不到当前ChainName的问题

https://gitee.com/dromara/liteFlow/issues/I5C23U

:::

:::tip v2.7.1

特性 #I5AYM5 组件事件回调特性支持

https://gitee.com/dromara/liteFlow/issues/I5AYM5

修复 #I5AVD2 新版本2.7.0中，全局切面中拿不到组件的别名了

https://gitee.com/dromara/liteFlow/issues/I5AVD2

修复 #I5AYI1 修复默认值提醒有误差

https://gitee.com/dromara/liteFlow/issues/I5AYI1

:::

:::tip v2.7.0

特性 #I588BO 对Slot模型的重构，在用户使用中去除Slot模型的概念，引入上下文的概念

https://gitee.com/dromara/liteFlow/issues/I588BO

特性 #I4U5S3 liteFlow日志级别打印开关设置

https://gitee.com/dromara/liteFlow/issues/I4U5S3

增强 #I58VVV 对core的package结构进行整理

https://gitee.com/dromara/liteFlow/issues/I58VVV

增强 #I595MU 在slot的元数据里增加每个组件执行的耗时和是否成功结果

https://gitee.com/dromara/liteFlow/issues/I595MU

增强 #I56ZQ3 打印步骤与执行时间

https://gitee.com/dromara/liteFlow/issues/I56ZQ3

增强 #I5A55K 在NodeComponent里重新加上beforeProcess和afterProcess方法

https://gitee.com/dromara/liteFlow/issues/I5A55K

增强 #I5851Y 对启动初始化的报错进行区分下，现在报错粒度太粗

https://gitee.com/dromara/liteFlow/issues/I5851Y

增强 #I5851R 对自定义组件名进行trim，防止开发者手误有空格

https://gitee.com/dromara/liteFlow/issues/I5851R

修复 #I4XRBA 关于when和then混合使用时(有any和isAccess的情况下)，then的节点先执行的问题

https://gitee.com/dromara/liteFlow/issues/I4XRBA

修复 #I4TJB0 自定义的Slot类必须有无惨构建

https://gitee.com/dromara/liteFlow/issues/I4TJB0

修复 #I4I730 this.setIsEnd(true)主动终止,2.6.4中抛出的异常ChainEndException还是打印error日志

https://gitee.com/dromara/liteFlow/issues/I4I730

:::

:::tip v2.6.14

特性 #I54VBS 从设计上改善NodeComponent，支持声明式组件

https://gitee.com/dromara/liteFlow/issues/I54VBS

增强 #I57IEJ requestId更换算法，看上去更加整洁

https://gitee.com/dromara/liteFlow/issues/I57IEJ

修复 #I576ZY 修复processor异常后 ICmpAroundAspect里面的aferProcess不能正常执行的问题

https://gitee.com/dromara/liteFlow/issues/I576ZY

:::

:::tip v2.6.13

特性 #I4ZVCL 执行器增加future的支持

https://gitee.com/dromara/liteFlow/issues/I4ZVCL

特性 #I51OBD 支持流程的销毁

https://gitee.com/dromara/liteFlow/issues/I51OBD

增强 #I4ZPNQ 隐式调用流程建议增加返回reponse的接口

https://gitee.com/dromara/liteFlow/issues/I4ZPNQ

修复 #I510LM 使用windows的绝对路径下的配置文件存在bug

https://gitee.com/dromara/liteFlow/issues/I510LM

:::

:::tip v2.6.12

增强 #I4YRVI 添加可执行实体对象作为构建流程的中间载体

https://gitee.com/dromara/liteFlow/issues/I4YRVI

修复 #I4YNN6 在某些高版本的springboot中，bean的重复注册会有问题

https://gitee.com/dromara/liteFlow/issues/I4YNN6

:::

:::tip v2.6.11

特性 #I4UPWG 模块架构调整，支持非Spring的项目使用

https://gitee.com/dromara/liteFlow/issues/I4UPWG

增强 #I4VTWB 代码动态构建规则,setClazz方法使用全限定名不太友好

https://gitee.com/dromara/liteFlow/issues/I4VTWB

增强 #I4TIWM whenExecutors目前不用注入到spring上下文中了

https://gitee.com/dromara/liteFlow/issues/I4TIWM

修复 #I4VEV2 用spring扫描组件，但是流程用动态代码创建，会出现slot无法分配的bug

https://gitee.com/dromara/liteFlow/issues/I4VEV2

修复 #I4VGCN 在非spring环境下，LiteflowConfigGetter无法获取到原始的config实例

https://gitee.com/dromara/liteFlow/issues/I4VGCN

:::

:::tip v2.6.10

特性 #I4R7AN 支持自定义组件执行器的扩展

https://gitee.com/dromara/liteFlow/issues/I4R7AN

增强 #I4T3NQ 适配spring的懒加载模式

https://gitee.com/dromara/liteFlow/issues/I4T3NQ

增强 #I4T3MQ 去除this.setIsEnd(true)打出的堆栈信息

https://gitee.com/dromara/liteFlow/issues/I4T3MQ

修复 #I4TBDT 修复因为ChianEndException导致的用slot接受抛错的问题

https://gitee.com/dromara/liteFlow/issues/I4TBDT

:::

:::tip v2.6.8

特性 #I4GS07 代码动态组件装配的特性

https://gitee.com/dromara/liteFlow/issues/I4GS07

特性 #I4QWH7 支持循环依赖

https://gitee.com/dromara/liteFlow/issues/I4QWH7

增强 #I4OQIX 组件执行轨迹日志级别调整

https://gitee.com/dromara/liteFlow/issues/I4OQIX

增强 #I4OTK4 希望finally组件可以获取到then组件的异常对象

https://gitee.com/dromara/liteFlow/issues/I4OTK4

增强 #I4PJKP when标签中默认的errorResume改为false

https://gitee.com/dromara/liteFlow/issues/I4PJKP

增强 #I4PTY4 修复CopyOnWriteHashMap可能存在的Bug

https://gitee.com/dromara/liteFlow/issues/I4PTY4

增强 #I4QV69 QLExpressScriptExecutor加载缓存脚本有线程安全问题

https://gitee.com/dromara/liteFlow/issues/I4QV69

增强 #I4QWJK 重构parser逻辑，解决的代码冗余问题

https://gitee.com/dromara/liteFlow/issues/I4QWJK

增强 #I4R5UI 升级LiteFlow的相关第三方依赖jar包的版本

https://gitee.com/dromara/liteFlow/issues/I4R5UI

修复 #I4RF0A 解决有些场景里启动时SpringAware后加载的问题

https://gitee.com/dromara/liteFlow/issues/I4RF0A

修复 #I4QOP6 when超时时抛出的错是NPT

https://gitee.com/dromara/liteFlow/issues/I4QOP6

修复 #I4PA2A 在NodeComponent的isAccess中获取tag失败

https://gitee.com/dromara/liteFlow/issues/I4PA2A

:::

:::tip v2.6.7

修复 #I4MINM 加载脚本节点时，节点里面的实例对象被改动了

https://gitee.com/dromara/liteFlow/issues/I4MINM

:::

:::tip v2.6.6

特性 #I4E5NX 异步线程池自定义

https://gitee.com/dromara/liteFlow/issues/I4E5NX

增强 #I4M3Q4 ruleSource支持配置绝对路径的配置文件

https://gitee.com/dromara/liteFlow/issues/I4M3Q4

修复 #I4LV63 在2.6.5版本中多线程tag取值中，xml没有问题，而json形式有问题

https://gitee.com/dromara/liteFlow/issues/I4LV63

修复 #I4LUQ5 默认的slot的dataMap无法放入值为null的对象

https://gitee.com/dromara/liteFlow/issues/I4LUQ5

:::

:::tip v2.6.5

增强 #I4IDB0 hutool依赖版本冲突，升级了hutool版本

https://gitee.com/dromara/liteFlow/issues/I4IDB0

修复 #I4HZYN 使用When操作同一个Node时，会造成Tag标签的线程不安全

https://gitee.com/dromara/liteFlow/issues/I4HZYN

:::

:::tip v2.6.4

特性 #I4GYV2 script节点支持从文件中获取脚本

https://gitee.com/dromara/liteFlow/issues/I4GYV2

特性 #I4HGOW 支持链路的前置和后置节点

https://gitee.com/dromara/liteFlow/issues/I4HGOW

特性 #I4FSHW 优雅平滑刷新的支持

https://gitee.com/dromara/liteFlow/issues/I4FSHW

特性 #I4GS03 并行节点中支持任意节点结束即继续的流程设计

https://gitee.com/dromara/liteFlow/issues/I4GS03

增强 #I4HKZG 借鉴asyncTool对异步线程底层进行了彻底重构

https://gitee.com/dromara/liteFlow/issues/I4HKZG

增强 #I4HD8L 支持异步节点返回自定义的错误

https://gitee.com/dromara/liteFlow/issues/I4HD8L

增强 #I4GZ1Q 增强异步线程超时的情况下打印出具体超时节点的信息

https://gitee.com/dromara/liteFlow/issues/I4GZ1Q

增强 #I4EXCP 新增 自定义 关闭/启动 Banner

https://gitee.com/dromara/liteFlow/issues/I4EXCP

修复 #I4GY9L 在启动后马上刷新流程后会有offerSlot的报错

https://gitee.com/dromara/liteFlow/issues/I4GY9L

修复 #I4FYKA jsonparser好像缺少脚本条件组件的解析

https://gitee.com/dromara/liteFlow/issues/I4FYKA

修复 #I4HQAA setIsEnd目前受isContinue的判断影响，还是会继续

https://gitee.com/dromara/liteFlow/issues/I4HQAA

修复 #I4HTY6 异步线程池不受配置控制的bug，一直是默认的数量

https://gitee.com/dromara/liteFlow/issues/I4HTY6

:::

:::tip v2.6.3

增强 #I4E0V9 支持在NodeComponent里自定义beforeProcess和afterProcess,没有覆盖方式时，默认读取aspect里的方法

https://gitee.com/dromara/liteFlow/issues/I4E0V9

增强 #I4DGEU 可以实现把ZK客户端curator依赖改成optional吗

https://gitee.com/dromara/liteFlow/issues/I4DGEU

修复 #I4E11G xml里定义条件组件有空格无法识别，如：b( testChan3 | testChan2 )。增加节点trim处理

https://gitee.com/dromara/liteFlow/issues/I4E11G

修复 #I4E2V4 修复异步线程池没有被TTL修饰有可能引起的无法拿到ThreadLocal值的问题

https://gitee.com/dromara/liteFlow/issues/I4E2V4

:::

:::tip v2.6.2

特性 #I4CRSY 在一个流程中的同名组件无法传递不同的参数，为组件增加标签属性

https://gitee.com/dromara/liteFlow/issues/I4CRSY

:::

:::tip v2.6.1

修复 #I4CGL8 QLExpress脚本引擎在refresh脚本节点的时候会失败

https://gitee.com/dromara/liteFlow/issues/I4CGL8

增强 #I455ZS 规则重复嵌套校验

https://gitee.com/dromara/liteFlow/issues/I455ZS

:::

:::tip v2.6.0

特性 #I4892Y 提供私有投递特性，slot这种结构体系，对于多个子线程进入同一个组件的情况下，不容易区分不同的传值。无法做到重用组件

https://gitee.com/dromara/liteFlow/issues/I4892Y

特性 #I49FDK 中断重试目前是全局的，希望增加针对个别组件和特定exception

https://gitee.com/dromara/liteFlow/issues/I49FDK

增强 #I49JP1 DataBus中SlotSize的大小不支持动态扩展，无法应对高并发下的流量突增

https://gitee.com/dromara/liteFlow/issues/I49JP1

增强 #I45QAJ 支持自定义的zkNodePath

https://gitee.com/dromara/liteFlow/issues/I45QAJ

修复 #I49EHH setIsEnd设计的不合理性

https://gitee.com/dromara/liteFlow/issues/I49EHH

修复 #I4BAJC setIsEnd结束的流程不需要进行重试

https://gitee.com/dromara/liteFlow/issues/I4BAJC

修复 #I49L1S 初始化DataBus的数据槽索引QUEUE大小的时候容量设置有问题

https://gitee.com/dromara/liteFlow/issues/I49L1S

修复 #I46U6Y 自定义JsonParse,调用flowExecutor的reloadRule,抛出异常

https://gitee.com/dromara/liteFlow/issues/I46U6Y

:::

:::tip v2.6.0-BETA1

特性 #I44FT8 支持脚本语言的组件，并支持动态刷新脚本(版本特性)

https://gitee.com/dromara/liteFlow/issues/I44FT8

特性 #I3ZVEA 流程组件支持重试

https://gitee.com/dromara/liteFlow/issues/I3ZVEA

增强 #I40DWO 流程配置文件中增加业务描述，打印步骤中带入业务描述

https://gitee.com/dromara/liteFlow/issues/I40DWO

修复 #I3VZMZ when类型condition场景下记录节点执行路径的方法会造成数据丢失

https://gitee.com/dromara/liteFlow/issues/I3VZMZ

修复 #I3UOJG 流程终止Slot内无数据

https://gitee.com/dromara/liteFlow/issues/I3UOJG

:::

:::tip v2.5.10

增强 #I426YS 支持多个不同类型的配置方式同时解析

https://gitee.com/dromara/liteFlow/issues/I426YS

修复 #I40VPB 关于LiteflowExecutorAutoConfiguration中的shutdown bean名称

https://gitee.com/dromara/liteFlow/issues/I40VPB

:::

:::tip v2.5.9

修复：#I413PU 增加liteflow.enable参数，来标记是否自动装配liteflow

https://gitee.com/dromara/liteFlow/issues/I413PU

修复：#I40YVK 当主流程与子流程在不同的配置文件中时，会报错

https://gitee.com/dromara/liteFlow/issues/I40YVK

修复：#I41S18 在开启监控的情况下，偶尔会报出空指针的问题

https://gitee.com/dromara/liteFlow/issues/I41S18

:::

:::tip v2.5.8

修复：#I3YX3Z 当抛出异常时，LiteflowResponse中的Slot为null

https://gitee.com/dromara/liteFlow/issues/I3YX3Z

:::

:::tip v2.5.7

修复：#I3W8FH 自定义配置源类无法依赖spring上下文中的bean的bug

https://gitee.com/dromara/liteFlow/issues/I3W8FH

:::

:::tip v2.5.6
修复: #I3SFOO:2.5.X解析多个flow.xml文件时条件节点的条件节点list会被清空

https://gitee.com/dromara/liteFlow/issues/I3SFOO

增强: #I3S5G8:动态平滑刷新机制

https://gitee.com/dromara/liteFlow/issues/I3S5G8

增强: #I3S0QA:DataBus 性能优化 Lock Free

https://gitee.com/dromara/liteFlow/issues/I3S0QA
:::

:::tip v2.5.5
增强: #I3QRW9 希望增加对SpringBoot 1.5.x版本的兼容适配

https://gitee.com/dromara/liteFlow/issues/I3QRW9

增强：#I3N144 是否能支持rule的通配符

https://gitee.com/dromara/liteFlow/issues/I3N144

增强：#I3IPXG 流程加载的时候 可以把流程加载的来源 也打印到日志中

https://gitee.com/dromara/liteFlow/issues/I3IPXG

修复：#I3ND7T 目前springboot下的缺省rule-source不起作用

https://gitee.com/dromara/liteFlow/issues/I3ND7T
:::

:::tip v2.5.4
修复: #I3NSF8 空的flow文件会导致无法启动

https://gitee.com/dromara/liteFlow/issues/I3NSF8
:::

:::tip v2.5.3
特性：#I3N2E2 支持编程时式的注册组件的方式

https://gitee.com/dromara/liteFlow/issues/I3N2E2

增强：#I3MMBL 添加additional-spring-configuration-metadata.json 到 liteflow-springboot-starter

https://gitee.com/dromara/liteFlow/issues/I3MMBL
:::

:::tip v2.5.2
修复：#I3IG1K SpringBoot的fat jar模式下，流程文件会找不到的问题

https://gitee.com/dromara/liteFlow/issues/I3IG1K

增强：#I3IGEB 重命名FlowExecutor中流程调用方法名称

https://gitee.com/dromara/liteFlow/issues/I3IGEB
:::

:::tip v2.5.1
增强：#I3I1TW 优化FlowExecutor中调用方法

https://gitee.com/dromara/liteFlow/issues/I3I1TW
:::

:::tip v2.5.0

特性：#I3CTY2 规则支持json和yml

https://gitee.com/dromara/liteFlow/issues/I3CTY2

特性：#I37QVR 提供异步组件执行时候的线程池支持

https://gitee.com/dromara/liteFlow/issues/I37QVR

增强：#I3CT11 能对任意包的下的组件进行切面

https://gitee.com/dromara/liteFlow/issues/I3CT11

修复：#I3CT9A 监控打印的耗时不准确问题

https://gitee.com/dromara/liteFlow/issues/I3CT9A

增强：#I3C5Y9 对于底层配置结构作了优化更改

https://gitee.com/dromara/liteFlow/issues/I3C5Y9

增强：#I3CTMQ 抛弃org.apache.common的包，依赖hutool

https://gitee.com/dromara/liteFlow/issues/I3CTMQ

增强：#I3CTUK 每个组件的对slot index的存储，换成阿里的TTL

https://gitee.com/dromara/liteFlow/issues/I3CTUK

修复：#I3CT49 连续的when标签，之间并不是完全并行的

https://gitee.com/dromara/liteFlow/issues/I3CT49

修复：#I3DM7Y 2.4.0-RC1版本会出现基础同步组件失败的情形

https://gitee.com/dromara/liteFlow/issues/I3DM7Y

修复：#I3DMX4 目前FlowExecutor会吃掉业务异常

https://gitee.com/dromara/liteFlow/issues/I3DMX4

支持：#I3CT01 LiteFlow增加单元测试

https://gitee.com/dromara/liteFlow/issues/I3CT01

:::