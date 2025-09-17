# 对齐方法评估的再思考：多样性、泛化与安全性洞察

发布时间：2025年09月16日

`LLM理论` `基础理论`

> Rethinking the Evaluation of Alignment Methods: Insights into Diversity, Generalisation, and Safety

# 摘要

> 大型语言模型（LLMs）的对齐需要精心设计，以平衡事实性、安全性、简洁性、主动性和多样性这些相互冲突的目标。现有研究多聚焦于单一技术或特定维度，却忽略了对其内在权衡的整体评估。为此，我们提出统一评估框架，从这五个维度对比主流LLM对齐方法（PPO、DPO、ORPO、KTO），并结合分布内与分布外数据集进行验证。借助经过人类研究验证的专用LLM-as-Judge提示，我们发现：DPO和KTO在事实准确性上表现突出，PPO和DPO在安全性上领先，PPO则最能兼顾简洁性与主动性。研究结果揭示了主流对齐方法的权衡机制，为开发更均衡、更可靠的LLM提供了指导。

> Large language models (LLMs) require careful alignment to balance competing objectives - factuality, safety, conciseness, proactivity, and diversity. Existing studies focus on individual techniques or specific dimensions, lacking a holistic assessment of the inherent trade-offs. We propose a unified evaluation framework that compares LLM alignment methods (PPO, DPO, ORPO, KTO) across these five axes, using both in-distribution and out-of-distribution datasets. Leveraging a specialized LLM-as-Judge prompt, validated through human studies, we reveal that DPO and KTO excel in factual accuracy, PPO and DPO lead in safety, and PPO best balances conciseness with proactivity. Our findings provide insights into trade-offs of common alignment methods, guiding the development of more balanced and reliable LLMs.

[Arxiv](https://arxiv.org/abs/2509.12936)