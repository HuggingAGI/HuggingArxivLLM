# 受权限管理的大型语言模型：实施访问控制的方法

发布时间：2025年05月28日

`LLM应用` `人工智能`

> Permissioned LLMs: Enforcing Access Control in Large Language Models

# 摘要

> 在企业环境中，组织数据被隔离、分隔，并由复杂的访问控制框架精心保护。如果一个基于分隔数据微调的大型语言模型 (LLM) 处理具有不同访问权限的个体的下游任务请求，这些访问控制结构可能会完全失效。我们提出了一种新的 LLM 类别——Permissioned LLMs (PermLLM)，它在生成的查询响应中叠加组织数据访问控制结构。我们对确定 LLM 查询响应中访问控制是否正确执行的手段进行了形式化抽象。我们的形式化引入了相关响应的概念，可用于证明 PermLLM 机制是否正确实现。我们还引入了一种新的度量标准，称为访问优势，用于实证评估 PermLLM 机制的有效性。我们提出了三种基于参数高效微调的新型 PermLLM 机制，以实现所需的访问控制。我们还介绍了两种访问优势的实现——(i) 基于成员推断攻击的领域可区分性指数 (DDI)，以及 (ii) 基于 LLM 功能评估的效用差距指数 (UGI)。我们通过在四个公开数据集 (GPQA, RCV1, SimpleQA, 和 WMDP) 上进行的广泛实验，证明了我们的 PermLLM 机制的有效性，同时评估了 DDI 和 UGI 指标的自身有效性，用于量化 LLM 中的访问控制。

> In enterprise settings, organizational data is segregated, siloed and carefully protected by elaborate access control frameworks. These access control structures can completely break down if an LLM fine-tuned on the siloed data serves requests, for downstream tasks, from individuals with disparate access privileges. We propose Permissioned LLMs (PermLLM), a new class of LLMs that superimpose the organizational data access control structures on query responses they generate. We formalize abstractions underpinning the means to determine whether access control enforcement happens correctly over LLM query responses. Our formalism introduces the notion of a relevant response that can be used to prove whether a PermLLM mechanism has been implemented correctly. We also introduce a novel metric, called access advantage, to empirically evaluate the efficacy of a PermLLM mechanism. We introduce three novel PermLLM mechanisms that build on Parameter Efficient Fine-Tuning to achieve the desired access control. We furthermore present two instantiations of access advantage--(i) Domain Distinguishability Index (DDI) based on Membership Inference Attacks, and (ii) Utility Gap Index (UGI) based on LLM utility evaluation. We demonstrate the efficacy of our PermLLM mechanisms through extensive experiments on four public datasets (GPQA, RCV1, SimpleQA, and WMDP), in addition to evaluating the validity of DDI and UGI metrics themselves for quantifying access control in LLMs.

[Arxiv](https://arxiv.org/abs/2505.22860)