# # 基于多角色混合的语言模型用于人口模拟
多角色混合语言模型在人口模拟中的应用研究

发布时间：2025年04月07日

`LLM应用` `社会科学` `行为建模`

> Mixture-of-Personas Language Models for Population Simulation

# 摘要

> 大型语言模型（LLMs）的进步为它们在多个领域的新兴应用铺平了道路，例如在人类行为模拟中，LLMs可以增强社会科学领域的研究以及机器学习模型的训练。然而，由于个体和群体之间固有的差异性，预训练的LLMs往往无法捕捉目标人群的行为多样性。针对这一问题，我们提出了	extit{人物混合模型}（MoP），这是一种	extit{概率}提示方法，旨在使LLM的响应与目标人群保持一致。MoP是一个上下文混合模型，其中每个组件都是一个语言模型（LM）代理，由一个代表子群体行为的个性和示例组成。在模拟过程中，个性和示例会根据学习到的混合权重随机选择，以激发多样化的LLM响应。MoP具有灵活性，无需模型微调，并且可以在不同的基础模型之间进行迁移。在合成数据生成的实验中，MoP在一致性与多样性指标上优于其他竞争方法。

> Advances in Large Language Models (LLMs) paved the way for their emerging applications in various domains, such as human behavior simulations, where LLMs could augment human-generated data in social science research and machine learning model training. However, pretrained LLMs often fail to capture the behavioral diversity of target populations due to the inherent variability across individuals and groups. To address this, we propose \textit{Mixture of Personas} (MoP), a \textit{probabilistic} prompting method that aligns the LLM responses with the target population. MoP is a contextual mixture model, where each component is an LM agent characterized by a persona and an exemplar representing subpopulation behaviors. The persona and exemplar are randomly chosen according to the learned mixing weights to elicit diverse LLM responses during simulation. MoP is flexible, requires no model finetuning, and is transferable across base models. Experiments for synthetic data generation show that MoP outperforms competing methods in alignment and diversity metrics.

[Arxiv](https://arxiv.org/abs/2504.05019)