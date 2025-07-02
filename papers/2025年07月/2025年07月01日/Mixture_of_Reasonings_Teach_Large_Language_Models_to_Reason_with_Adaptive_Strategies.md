# 教大型语言模型学会自适应推理策略：推理的混合方法

发布时间：2025年07月01日

`LLM理论` `模型训练`

> Mixture of Reasonings: Teach Large Language Models to Reason with Adaptive Strategies

# 摘要

> 大型语言模型（LLMs）在复杂任务中表现出色，通过先进的提示技术，如思维链（CoT）和思维树（ToT）。然而，它们对人工编写的任务特定提示的依赖限制了其适应性和效率。我们引入了Mixture of Reasoning（MoR），一种训练框架，将多样化的推理策略嵌入到LLMs中，使其能够进行自主的任务自适应推理，无需外部提示工程。

MoR分为两个阶段：思维生成阶段，利用GPT-4o等模型生成多样化的推理链模板；以及SFT数据集构建阶段，将这些模板与基准数据集配对，用于监督微调。实验结果表明，MoR显著提升了模型性能。其中，MoR-150在使用CoT提示时达到了0.730，较基线提升了2.2%；在其他任务中，性能更是提升了13.5%。MoR消除了对任务特定提示的需求，为各种任务提供了通用且稳健的推理解决方案。

> Large language models (LLMs) excel in complex tasks through advanced prompting techniques like Chain-of-Thought (CoT) and Tree-of-Thought (ToT), but their reliance on manually crafted, task-specific prompts limits adaptability and efficiency. We introduce Mixture of Reasoning (MoR), a training framework that embeds diverse reasoning strategies into LLMs for autonomous, task-adaptive reasoning without external prompt engineering. MoR has two phases: Thought Generation, creating reasoning chain templates with models like GPT-4o, and SFT Dataset Construction, pairing templates with benchmark datasets for supervised fine-tuning.Our experiments show that MoR significantly enhances performance, with MoR150 achieving 0.730 (2.2% improvement) using CoT prompting and 0.734 (13.5% improvement) compared to baselines. MoR eliminates the need for task-specific prompts, offering a generalizable solution for robust reasoning across diverse tasks.

[Arxiv](https://arxiv.org/abs/2507.00606)