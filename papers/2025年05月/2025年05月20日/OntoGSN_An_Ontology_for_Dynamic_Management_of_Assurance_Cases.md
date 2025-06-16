# OntoGSN：一个用于动态管理保证案例的本体

发布时间：2025年05月20日

`其他` `自动驾驶` `软件工程`

> OntoGSN: An Ontology for Dynamic Management of Assurance Cases

# 摘要

> 信心保证案例（ACs）是用于构建和维护系统属性（如安全性或鲁棒性）信心的重要工具。尽管现有工具为静态、文档中心型应用提供了支持，并且针对动态环境（如自动驾驶）的方法正在出现，但构建AC并非易事。管理AC同样充满挑战，因为面对变化时维护嵌入的知识需要付出巨大努力，这一过程会阻碍开发者——更糟糕的是，可能导致管理不善的案例，从而产生虚假信心。

为了解决这一问题，我们提出了OntoGSN：一个用于管理基于目标结构化表示法（GSN）标准的ACs的本体和配套中间件。OntoGSN提供了一种知识表示和可查询的图，这些图可以自动填充、评估和更新。我们的贡献包括：

- GSN社区标准v3在OWL本体中的1:1形式化，附带SWRL规则；
- 一个帮助本体和解析器，用于与广泛使用的AC工具集成；
- 一个设计决策的存储库和文档，用于OntoGSN的维护；
- 一个包含自动化模式的SPARQL查询库；
- 以及一个原型界面。

该本体严格遵循标准文本，并根据FAIR原则、OOPS框架、能力问题和社区反馈进行了评估。其他中间件组件的开发由社区需求指导，并接受持续评估。

为了展示我们贡献的实用性，我们通过一个涉及大型语言模型对抗鲁棒性保证的例子，展示了动态AC管理的潜力。

> Assurance cases (ACs) are a common artifact for building and maintaining confidence in system properties such as safety or robustness. Constructing an AC can be challenging, although existing tools provide support in static, document-centric applications and methods for dynamic contexts (e.g., autonomous driving) are emerging. Unfortunately, managing ACs remains a challenge, since maintaining the embedded knowledge in the face of changes requires substantial effort, in the process deterring developers - or worse, producing poorly managed cases that instill false confidence. To address this, we present OntoGSN: an ontology and supporting middleware for managing ACs in the Goal Structuring Notation (GSN) standard. OntoGSN offers a knowledge representation and a queryable graph that can be automatically populated, evaluated, and updated. Our contributions include: a 1:1 formalization of the GSN Community Standard v3 in an OWL ontology with SWRL rules; a helper ontology and parser for integration with a widely used AC tool; a repository and documentation of design decisions for OntoGSN maintenance; a SPARQL query library with automation patterns; and a prototypical interface. The ontology strictly adheres to the standard's text and has been evaluated according to FAIR principles, the OOPS framework, competency questions, and community feedback. The development of other middleware elements is guided by the community needs and subject to ongoing evaluations. To demonstrate the utility of our contributions, we illustrate dynamic AC management in an example involving assurance of adversarial robustness in large language models.

[Arxiv](https://arxiv.org/abs/2506.11023)