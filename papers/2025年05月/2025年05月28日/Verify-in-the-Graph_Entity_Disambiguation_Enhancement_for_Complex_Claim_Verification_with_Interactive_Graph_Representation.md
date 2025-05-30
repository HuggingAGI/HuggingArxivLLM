# Verify-in-the-Graph：基于交互式图表示的复杂声明验证中实体消歧增强

发布时间：2025年05月28日

`Agent`

> Verify-in-the-Graph: Entity Disambiguation Enhancement for Complex Claim Verification with Interactive Graph Representation

# 摘要

> 索赔验证是一项历史悠久且极具挑战性的任务，它不仅要求极高的准确性，还需要对验证过程具有可解释性。随着大型语言模型（LLMs）时代的到来，这一任务成为了一个新兴的研究热点，因为现实世界中的索赔往往十分复杂，涉及复杂的语义结构或模糊的实体。传统方法通常通过将索赔分解为子索赔，并查询知识库来解决隐藏或模糊的实体。然而，缺乏有效的消歧策略来处理这些实体可能会破坏整个验证过程。为了解决这些挑战，我们提出了Verify-in-the-Graph（VeGraph），一个利用LLM代理的推理和理解能力的全新框架。VeGraph的工作流程分为三个阶段：（1）图表示阶段——输入索赔被分解为结构化的三元组，形成一个图结构化表示，整合了结构化与非结构化信息；（2）实体消歧阶段——VeGraph通过与知识库的迭代交互，解决图中模糊实体的问题，从而实现对子索赔的更深入验证；（3）验证阶段——剩余的三元组被逐一验证，以完成整个事实核查流程。使用Meta-Llama-3-70B（指令版本）进行的实验表明，VeGraph在HoVer和FEVEROUS两个基准测试中与基线模型相比表现优异，有效解决了索赔验证的难题。我们的源代码和数据集已对外公开，供进一步研究使用。

> Claim verification is a long-standing and challenging task that demands not only high accuracy but also explainability of the verification process. This task becomes an emerging research issue in the era of large language models (LLMs) since real-world claims are often complex, featuring intricate semantic structures or obfuscated entities. Traditional approaches typically address this by decomposing claims into sub-claims and querying a knowledge base to resolve hidden or ambiguous entities. However, the absence of effective disambiguation strategies for these entities can compromise the entire verification process. To address these challenges, we propose Verify-in-the-Graph (VeGraph), a novel framework leveraging the reasoning and comprehension abilities of LLM agents. VeGraph operates in three phases: (1) Graph Representation - an input claim is decomposed into structured triplets, forming a graph-based representation that integrates both structured and unstructured information; (2) Entity Disambiguation -VeGraph iteratively interacts with the knowledge base to resolve ambiguous entities within the graph for deeper sub-claim verification; and (3) Verification - remaining triplets are verified to complete the fact-checking process. Experiments using Meta-Llama-3-70B (instruct version) show that VeGraph achieves competitive performance compared to baselines on two benchmarks HoVer and FEVEROUS, effectively addressing claim verification challenges. Our source code and data are available for further exploitation.

[Arxiv](https://arxiv.org/abs/2505.22993)