### Project Management Approach

#### Build or buy

* 由于本项目的开发目标是通过构建该产品从而在国内市场上取得内存kv数据库技术上的优势,因此该项目的核心功能的开发必须由公司内部的技术人员完成,也就是内部开发
* 但同时考虑到该项目规模较为庞大,同时存在一系列非核心功能会加大核心开发团队的工作负担(如项目的UI界面等),因此对于这些非核心的功能开发,可以交由外包团队完成,但总体开发方向应由公司内部技术人员把控

#### Choosing methodologies and technologies

##### Identify project driven-method

* 本项目开发的产品在项目开始前已明确定义,故为产品驱动型项目

##### Analyze other project characteristics

1. 本项目实现的系统为面向数据的内存数据库系统
2. 本项目实现的系统应当为通用工具
3. 本项目的产品应当支持高并发
4. 本项目的产品将适用于各个行业,在某些行业中,数据库的使用是安全性关键的,故需要进行严格的测试
5. 本项目的产品是用于执行已定义的内存数据库存储服务
6. 本项目的产品的目标运行环境为服务器环境

##### Identify high-level project risk

* 过程不确定性
  * 由于国内在内存数据库这一领域没有太多的技术积累,因此开发过程中将采用大量崭新的技术方法,将带来过程不确定性
* 资源不确定性
  * 同样是由于国内缺乏足够的技术积累,可能无法招募到足够的技术骨干进行开发,这将带来资源不确定性

##### Select general life-cycle approach

* 形式化验证
  * 由上述总结的一系列内存数据库项目的特征可知,该项目的产品涉及安全性关键(需要保证数据一致性,可持久化等特性),因此需要进行严格的测试,可采用形式化验证的手段对核心功能算法进行验证,以保证尽量系统漏洞
* 原型开发
  * 由于项目的产品对于开发团队来说是一个崭新的领域,因此可采用原型开发的方法对系统的功能进行初步检验
* 增量式交付
  * 由于项目开发难度较大,时间花费较长,出于成本方面的考虑,可以采用增量式交付的方法,再完成核心功能后交付第一个版本打响名声,从而吸引更多的人才以及投资,对于非核心需求(如用户友好等)可在之后的版本迭代后交付

#### Choice for process model

* 根据上述分析,我们可以得到:
  * 本项目是较为复杂的大型系统项目
  * 本项目具有较高的不确定性
  * 本项目应采用原型开发,增量式交付等方法进行开发
* 因此我们可以采用螺旋模型作为项目开发的过程模型
* 使用螺旋模型具有一下几个优势:
  * 螺旋模型引入了其他模型不具备的风险分析,可降低产品开发的风险
  * 设计上具有灵活性,可以在项目的各个阶段进行变更
  * 以小的分段来构建大型系统,使成本计算变得简单容易
  * 客户始终参与每个阶段的开发,保证了项目不偏离正确方向以及项目的可控性
  * 随着项目推进,客户始终掌握项目的最新信息

#### Software prototyping

* 本项目还采用软件原型的开发方法来降低项目风险
* 由于本项目在开发过程中常常要验证软件使用算法的正确性和性能,故通常采用抛弃型原型来对算法进行测试

#### Incremental delivery

* 在完成核心功能后,之后的非核心需求以及核心功能的更新可使用增量式交付的方式进行
* 使用增量性交付可以获取早期增量的反馈以改进之后的增量
* 由于本项目具有较大的开发风险,使用增量式交付可以让用户在早期看到项目成品,从而给予投资人信心,改善公司的经济压力,并提高公司的名气