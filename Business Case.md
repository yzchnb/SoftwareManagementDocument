## Business Case


### Executive Summary

#### Problem/Opportunity

项目的机会在于国内的制作基础设施架构应用的公司并不多，大多数互联网公司，传统行业公司采用的缓存系统大多数为国外企业的分布式key-value内存缓存数据库，如memcached，redis等，而国内在该产业几乎是空白。我司有机会开发一款核心技术为自主研发的分布式key-value缓存内存数据库，并能够在市场上取得一定的占有率。

#### Organization’s Goal & Strategy

企业的短期目标是通过该项目的发布在市场上取得一定的占有率，提升该产品在基础架构级软件行业的影响力，从而提升企业在该领域的影响力，并能够使公司取得盈利。企业的战略目标在于通过该产品在市场上的高占有率，能够回收大部分成本，并上市融资，在技术领域上，提升中国在kv数据库这一领域上的话语权，填补中国基础软件行业的空白，提升民族软件形象。

#### MOV & Its Impact

该商业项目的Measurable Organizational Value(MOV)为在市场上取得更高的占有率，在6个月内，使国内至少5家企业使用我司的产品。1年内，50家中小企业使用，5家大型企业使用我司的产品。在2年内，100家中小企业使用，20家大型企业使用，国外有20家企业使用。实现该MOV能够在市场影响力上和财政上对企业有非常大的提升。只有实现了MOV中提及的目标，企业的成本才能收回，影响力才能提升，才能实现盈利。

#### Alternatives/Options

企业目前有四种项目可选方案，分别为企业内部全权负责开发该项目的全部内容；企业开发核心模块，外包其余模块；企业购买现有开源产品，在其基础上进行二次开发；企业放弃该项目。



### Business Case Analyse Team

| 角色         | 职责                        |
| ------------ | --------------------------- |
| 执行赞助商   | 提供该项目的执行支持        |
| 技术支持人员 | 提供该项目的技术指导/支持   |
| 过程改进人员 | 对项目的过程改善提出建议    |
| 项目经理     | 管理Business Case和项目团队 |
| 风险控制人员 | 为项目提供风险分析          |

### Introduction

#### Background

近些年来，随着4g的普及以及5g的出现，对于网络请求响应速度的需求日益提升，而内存key-value成为了所有互联网公司必须使用的缓存中间件。该项目由的商业目标是为所有需要使用到web技术的公司和组织，提供一个高速的，高并发的，分布式的内存缓存解决方案。当今时代，人们对于实时性访问需求越来越高，内存级别的数据缓存作为一级缓存可以极大地提升访问速度，提高响应比，是每个公司都需要使用的技术，前景很好。同时，目前世界上的大部分公司都在使用国外开源的内存kv数据库，如redis，memcached等产品，中国目前现有的内存kv数据库并未在国际上得到广泛认可，所以该项目承载着希望，能够成为中国内存kv数据库领域的领头羊，并未现有内存key-value数据库

#### Current Situation and Problem/Opportunity Statement

项目的机会在于国内的制作基础设施架构应用的公司并不多，大多数互联网公司，传统行业公司采用的缓存系统大多数为国外企业的kv数据库，而国内在该产业几乎是空白。公司希望能够开发全世界流行的新一代内存缓存数据库中间件，先打通国内市场，再进一步打开国外市场，为民族软件行业争光，成为中国，乃至世界在该领域的领头羊。

项目目前处于起步阶段，所存在的问题大多局限于人员方面。公司难以招聘到开发底层系统的编码人员，目前招聘大多数都是应用层面开发人员居多，从而导致了招聘的困难。同时由于项目的是属于基础架构级别项目，而非应用级别项目，在获取融资方面比较困难。项目所拥有的机会在于，首先，若能获取高额融资，需要招聘到有经验的底层开发人员，如从apache，oracle等公司挖角，其次，当项目在完成数次迭代后，能够率先提供给某些企业或政府免费试用以及使用培训，从而建立起产品口碑，能够获得快速扩张使用的机会。

#### Measurable Organizational Value (MOV)

使用时间线表格来记录MOV内容

| 时间线 | MOV                                                          |
| :----- | ------------------------------------------------------------ |
| 6个月  | 在国内有5家中小企业使用我司产品作为kv数据库                  |
| 1年    | 在国内有50家中小企业，5家大型企业使用我司产品作为kv数据库    |
| 2年    | 在国内有100家中小企业，20家大型企业使用我司产品作为kv数据库，在国外有20家企业使用我司产品作为kv数据库 |

#### How achieving the project’s MOV will support the organization’s goal and strategy

实现MOV中包含的目标在各个方面都能帮助企业实现企业的目标以及战略。企业首要目标是将我司产品成功的开发出来，并推广向市场，提升企业在国际上的影响力。在两年内能够达到国内100家中小企业，20家大型企业使用我司产品作为kv数据库，且在国外有20家企业使用我司产品作为kv数据库，这毫无疑问会使企业成为该领域的新星，让企业的影响力得到显著的提升。企业的下一目标即为盈利，毫无疑问，当该项目在市场上取得较高的占有率时，会吸引越来越多的企业使用我司的产品，而作为一款几乎每个使用到web技术的公司都必备的基础架构级别的设施，其他企业使用我司产品的机会是很大的，所以盈利是当企业占有率提升到较高水平后的必然情况。该项目的战略目标包括持续性的吸纳如今已有的缓存技术的优点，并持续增强与各类web框架集成的能力，最终达到提高市场占有率的目的。从开发人员角度来说，希望该产品能够进一步提高数据提取响应速度，增强数据稳定性，并支持各类分布式事务，并有野心从中间件的身份脱离出，能够成为独立的数据库，进一步打开市场，进一步提升中国软件行业在国际上的地位。从公司角度来说希望该产品能够提升公司品牌的知名度，从而吸纳更多资金投入我司，更多人才加入我司，从而不仅仅提升我司的经济效益水平，还能提升品牌效益，以便于后期开发更多底层基础架构级别应用，底层中间件，从而达到良性循环，占有更多世界市场。

#### Objectives of Writing this Business Case

编写该商业案例分析的目的在于为当前所分析得到的商业机会提供一个便捷参考，以及对项目MOV进行具体的阐述，以及对我司可执行的项目提供各种可选方案，以及对他们的具体分析，包括方案的经济效益分析，可行性分析，风险控制分析等。

### Alternatives

#### Alternative One (base case)

| 概述 | 企业内部全权开发此项目的全部内容                             |
| ---- | ------------------------------------------------------------ |
| 描述 | 企业通过自己建立项目团队，包括招聘足够的开发人员，设计人员，测试人员，项目管理人员，市场分析人员，营销人员，销售人员等，开发项目的全部内容，包括核心存储引擎，通信模块，高并发性能优化算法模块，UI模块，以及项目的需求，设计文档，用户使用文档，手册。同时包括营销人员使用的微信公众号后台，项目官方网站等。 |

#### Alternative Two

| 概述 | 企业开发核心模块，部分模块外包                               |
| ---- | ------------------------------------------------------------ |
| 描述 | 企业自己建立项目团队，包括招聘足够的开发人员，设计人员，测试人员，项目管理人员，市场分析人员，营销人员，销售人员等，开发该项目中核心的模块，包括存储引擎，通信模块，高并发性能优化算法模块。但是公司将其余如UI模块，用户使用文档，手册，以及营销人员使用的微信公众号后台，项目官方网站外包给其他小公司。 |

#### Alternative Three

| 概述 | 购买现存的开源kv数据库，在其基础上二次开发                   |
| ---- | ------------------------------------------------------------ |
| 描述 | 企业自己建立项目团队，包括招聘足够的开发人员，设计人员，测试人员，项目管理人员，市场分析人员，营销人员，销售人员等，首先让开发和设计人员通过技术商讨，选择一个国际上开源的kv数据库项目，与其所属公司或组织进行联系，并进行购买，在其基础上对其进行二次开发，改进，使其在功能上更符合我司的要求，在性能上有较大幅度的提升。之后再进行UI模块的编写，也包括UI模块，以及项目的需求，设计文档，用户使用文档，手册。同时包括营销人员使用的微信公众号后台，项目官方网站等。 |

#### Alternative Four

| 概述 | 放弃该项目                               |
| ---- | ---------------------------------------- |
| 描述 | 企业可以选择放弃该商业机会，不做任何事。 |

### Alternative Analysis

//TODO