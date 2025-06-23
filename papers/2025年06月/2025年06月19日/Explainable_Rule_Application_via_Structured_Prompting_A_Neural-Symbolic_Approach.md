# # 摘要
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年06月19日

`LLM应用

摘要中提到，论文提出了一种结构化提示框架，用于改进大型语言模型在法律分析等需要精确逻辑推理任务中的表现。该框架结合了神经网络和符号方法，旨在提升模型的可解释性和逻辑一致性，并在实际任务中取得了显著效果。因此，这篇论文主要探讨了大型语言模型在特定应用中的优化和改进，属于LLM应用类别。` `神经符号系统`

> Explainable Rule Application via Structured Prompting: A Neural-Symbolic Approach

# 摘要

> 大型语言模型（LLMs）擅长处理复杂推理任务，但在一致规则应用、异常处理和可解释性方面表现欠佳，尤其在需要结合自然语言理解和精确逻辑推理的领域，例如法律分析。本文提出了一种结构化提示框架，将推理过程分解为三个可验证的步骤：实体识别、属性提取和符号规则应用。通过融合神经网络与符号方法，我们的方法不仅发挥了LLMs在解释上的灵活性，还借助形式化验证确保了逻辑的一致性。该框架将任务定义外化，使领域专家能够无需修改架构即可优化逻辑结构。在LegalBench的传闻证据判定任务中，我们的方法显著超越了基线模型。OpenAI的o系列模型表现尤为出色，其中o1在采用结构化分解与互补谓词后，F1分数达到0.929，o3-mini则为0.867，相较于其少量样本基线的0.714和0.74，分别实现了显著提升。这种混合神经符号系统为透明且一致的基于规则推理提供了有前景的解决方案，显示出其在结构化法律推理任务中实现可解释人工智能应用的潜力。

> Large Language Models (LLMs) excel in complex reasoning tasks but struggle with consistent rule application, exception handling, and explainability, particularly in domains like legal analysis that require both natural language understanding and precise logical inference. This paper introduces a structured prompting framework that decomposes reasoning into three verifiable steps: entity identification, property extraction, and symbolic rule application. By integrating neural and symbolic approaches, our method leverages LLMs' interpretive flexibility while ensuring logical consistency through formal verification. The framework externalizes task definitions, enabling domain experts to refine logical structures without altering the architecture. Evaluated on the LegalBench hearsay determination task, our approach significantly outperformed baselines, with OpenAI o-family models showing substantial improvements - o1 achieving an F1 score of 0.929 and o3-mini reaching 0.867 using structured decomposition with complementary predicates, compared to their few-shot baselines of 0.714 and 0.74 respectively. This hybrid neural-symbolic system offers a promising pathway for transparent and consistent rule-based reasoning, suggesting potential for explainable AI applications in structured legal reasoning tasks.

[Arxiv](https://arxiv.org/abs/2506.16335)