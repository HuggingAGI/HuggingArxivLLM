# 对齐如何重塑生成边界

发布时间：2025年06月21日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）生成输出缺乏多样性的原因，并引入了分支因子（BF）这一指标来量化生成过程中的概率集中现象。通过对模型输出分布的分析，论文揭示了对齐调优对模型输出稳定性的影响，并提出了对齐调优引导模型行为的假设。这些研究内容属于对LLM内在机制和性能的理论分析，因此归类为LLM理论。` `人工智能`

> How Alignment Shrinks the Generative Horizon

# 摘要

> 尽管对齐的大型语言模型（LLMs）能力出众，但它们生成的输出往往缺乏多样性。我们通过分析模型输出分布中的概率集中现象，探讨了这种生成稳定性的原因。为了量化这种集中程度，我们引入了分支因子（BF）——一个衡量生成过程中有效可能下一步数量的与标记无关的指标。我们的实证分析揭示了两个关键发现：(1) 随着生成过程的推进，BF通常会下降，表明LLMs的输出越来越可预测；(2) 对齐调优从一开始就显著增强了模型输出分布的集中度，使BF相对于基础模型减少了近一个数量级（例如，从12降至1.2）。这种显著的减少解释了为什么对齐模型通常看起来对解码策略不太敏感。这种稳定性对复杂推理任务有着出人意料的影响。例如，对齐的Chain-of-Thought（CoT）模型（如DeepSeek distilled模型）通过生成更长的推理链，将生成过程推进到后期更确定性（更低BF）的阶段，从而产生更稳定的输出。我们假设对齐调优并没有从根本上改变模型的行为，而是引导其转向风格化标记（例如，“Sure”），这些标记能够解锁基础模型中已存在的低熵轨迹。这一观点得到了引导实验的支持，实验表明，通过提示基础模型使用这些标记，也可以类似地降低BF。综上所述，我们的研究将BF确立为一个强大的诊断工具，用于理解和控制LLM输出——阐明了对齐如何减少变异性、CoT如何促进稳定生成，以及如何引导基础模型远离多样性。

> Despite their impressive capabilities, aligned large language models (LLMs) often generate outputs that lack diversity. What drives this stability in the generation? We investigate this phenomenon through the lens of probability concentration in the model's output distribution. To quantify this concentration, we introduce the Branching Factor (BF) -- a token-invariant measure of the effective number of plausible next steps during generation. Our empirical analysis reveals two key findings: (1) BF often decreases as generation progresses, suggesting that LLMs become more predictable as they generate. (2) alignment tuning substantially sharpens the model's output distribution from the outset, reducing BF by nearly an order of magnitude (e.g., from 12 to 1.2) relative to base models. This stark reduction helps explain why aligned models often appear less sensitive to decoding strategies. Building on this insight, we find this stability has surprising implications for complex reasoning. Aligned Chain-of-Thought (CoT) models (e.g., DeepSeek-distilled models), for instance, leverage this effect; by generating longer reasoning chains, they push generation into later, more deterministic (lower BF) stages, resulting in more stable outputs. We hypothesize that alignment tuning does not fundamentally change a model's behavior, but instead steers it toward stylistic tokens (e.g., "Sure") that unlock low-entropy trajectories already present in the base model. This view is supported by nudging experiments, which show that prompting base models with such tokens can similarly reduce BF. Together, our findings establish BF as a powerful diagnostic for understanding and controlling LLM outputs - clarifying how alignment reduces variability, how CoT promotes stable generations, and how base models can be steered away from diversity.

[Arxiv](https://arxiv.org/abs/2506.17871)