# 智能体树：基于多视角推理增强大型语言模型的长上下文能力

发布时间：2025年09月08日

`Agent` `基础理论`

> Tree of Agents: Improving Long-Context Capabilities of Large Language Models through Multi-Perspective Reasoning

# 摘要

> 大型语言模型（LLMs）处理长上下文任务时，始终面临一个棘手难题——“中间信息丢失”：长输入中段的信息常常得不到充分利用。现有方案中，缩减输入可能丢失关键信息，扩展上下文窗口又容易造成注意力分散。为此，我们提出智能体树（Tree of Agents，TOA）——一种多智能体推理框架，它将输入切分成块，交由独立智能体分别处理。每个智能体先形成局部认知，再沿树状路径动态交换信息，实现协同推理。TOA支持智能体尝试不同推理顺序，从而实现多视角理解，既能有效减轻位置偏差，又能减少幻觉问题。为提升处理效率，我们引入前缀哈希缓存与自适应剪枝策略，在API开销相近的前提下，性能得到显著提升。实验结果显示，基于轻量级模型LLaMA3.1-8B的TOA，在各类长上下文任务中不仅显著优于多个基线模型，还能与Gemini1.5-pro等最新且规模大得多的商业模型比肩。代码已开源：https://github.com/Aireduce952/Tree-of-Agents。

> Large language models (LLMs) face persistent challenges when handling long-context tasks, most notably the lost in the middle issue, where information located in the middle of a long input tends to be underutilized. Some existing methods that reduce input have the risk of discarding key information, while others that extend context windows often lead to attention dispersion. To address these limitations, we propose Tree of Agents (TOA), a multi-agent reasoning framework that segments the input into chunks processed by independent agents. Each agent generates its local cognition, then agents dynamically exchange information for collaborative reasoning along tree-structured paths. TOA enables agents to probe different reasoning orders for multi-perspective understanding, effectively mitigating position bias and reducing hallucinations. To improve processing efficiency, we incorporate prefix-hash caching and adaptive pruning strategies, achieving significant performance improvements with comparable API overhead. Experiments show that TOA, powered by compact LLaMA3.1-8B, significantly outperforms multiple baselines and demonstrates comparable performance to the latest and much larger commercial models, such as Gemini1.5-pro, on various long-context tasks. Code is available at https://github.com/Aireduce952/Tree-of-Agents.

[Arxiv](https://arxiv.org/abs/2509.06436)