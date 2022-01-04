## ASAM OpenSCENARIO: Version 2.0.0 Concepts

### 1. 背景

#### 1.1 ASAM & OpenScenario

​	2.0.0版本有累计超过90位相关团队或个人对OpenScenario作出贡献，其目的是为了解决场景的特征丰富度以及适用性问题，同时兼容OpenScenario 1.x.x 版本，涵盖的主要话题

1. Interface to Models & Topology 接口模型与拓扑
2. Parameter & Constraint Handling 参数与约束处理
3. Measurements, Grading & Success 测量、评分以及成功
4. Scenario Creation Methods 场景创建方法
5. Maneuver Description 行为描述
6. Glossary & Notation 术语与注意
7. Global Architecture 整体架构

#### 1.2 关于行业内的一些成熟的场景库技术

ASAM

中汽研

TAD

Apollo

#### 1.3 关于这篇文档

​	这篇文档基于现有的场景领域的工作，期望形成一份适用于产品不同阶段的场景使用最佳实践，指导相关研发、测试工作高效推进。相关的产出包裹但不限于: 方法论、流程定义、实用工具以及数据。

### 2. 

---

### 3. 与场景有关的OKR建议

#### 3.1 Objectives

​	创建一个面向限定公开道路的自动驾驶场景库，完成正向设计&数据回流双向场景闭环，推动产品研发、测试效率不断提升；

#### 3.2 Key Results

- 与现行的标准测试库完成对接

- 产出场景集合100+Abstract 场景，3000+Concrete 场景，有效Case数6000+；长期建设和维护，预计会分为三个阶段: 1. 人工设计场景&路测目标场景集；2. 泛化人工设计场景集&限制道路目标场景集； 3. 基础集合&日常维护

- 测试工具，配合仿真平台输出产品迭代所需的测试场景及评价执行；Option: PlanB 与类似腾讯等进行合作，确认能力支持情况

  ![image-20220104163048779](/Users/octo/Library/Application Support/typora-user-images/image-20220104163048779.png)

- 流程定义，

- 不同场景的评价指标

### 4. 测试场景的实用工具

#### 4.1 场景生成工具

#### 4.2 场景标注工具

#### 4.3 场景提取工具

#### 4.4 场景转换工具

#### 4.5 场景评价机制

### 5. 场景相关的标准

#### 5.1 ISO-34502结构化场景六层模型

#### 5.2 ASAM OpenScenario模型

### Open Questions

- TAD的交通环境描述方式是怎样的，具体的用途是什么？
- 基于纯视觉方案的全链路仿真测试中场景如何使用？











