# OpenGrok: 蒸馏知识与遮罩机制赋能社交网络数据处理

发布时间：2025年02月11日

`LLM应用

理由：这篇论文讨论了将大型语言模型应用于社交网络服务数据处理的具体方法，包括模型微调和提示工程等技术，属于LLM的应用层面。` `社交网络服务`

> OpenGrok: Enhancing SNS Data Processing with Distilled Knowledge and Mask-like Mechanisms

# 摘要

> 本报告介绍 Lumen Labs 在处理社交网络服务 (SNS) 数据方面的创新方法。我们结合知识蒸馏与提示词工程技术，从 Grok 模型中提取高质量训练数据，其中蒸馏方法灵感源自 DeepSeek-R1 的 CoT 机制。随后，我们通过一种专为 SNS 数据设计的类似掩码机制，对 Phi-3-mini 模型进行微调。实验结果表明，我们的方法在多项 SNS 数据处理任务中超越现有模型（包括 Grok、Phi-3 和 GPT-4），达到业界领先水平。报告中包含方法的数学公式、工程实现细节、消融实验及对比分析。

> This report details Lumen Labs' novel approach to processing Social Networking Service (SNS) data. We leverage knowledge distillation, specifically a simple distillation method inspired by DeepSeek-R1's CoT acquisition, combined with prompt hacking, to extract valuable training data from the Grok model. This data is then used to fine-tune a Phi-3-mini model, augmented with a mask-like mechanism specifically designed for handling the nuances of SNS data. Our method demonstrates state-of-the-art (SOTA) performance on several SNS data processing tasks, outperforming existing models like Grok, Phi-3, and GPT-4. We provide a comprehensive analysis of our approach, including mathematical formulations, engineering details, ablation studies, and comparative evaluations.

[Arxiv](https://arxiv.org/abs/2502.07312)