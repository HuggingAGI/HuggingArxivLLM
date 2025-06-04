# 加速代码编辑：编辑导向的推测解码助力代码复用与生成

发布时间：2025年06月03日

`LLM应用` `软件开发`

> Reuse or Generate? Accelerating Code Editing via Edit-Oriented Speculative Decoding

# 摘要

> 大型语言模型（LLMs）在代码编辑领域展现出卓越能力，显著提升了软件开发效率。然而，代码编辑任务的复杂性迫使现有方法依赖LLMs的自回归端到端生成，其中解码速度对整体效率至关重要。尽管推测式解码等推理加速技术已用于提升解码效率，但这些方法未能充分考虑代码编辑任务的独特性，即更改通常局部化且会复用现有代码段。针对这一局限，我们提出EfficientEdit，一种基于推测式解码的创新方法，通过两大核心机制优化LLM驱动的代码编辑效率：(1) 在识别潜在编辑位置时有效复用原始代码段，以及(2) 利用面向编辑的草稿模型生成高质量草稿，并通过平衡质量和加速的动态验证机制高效生成编辑内容。实验结果显示，EfficientEdit在CanItEdit和CodeIF-Bench基准测试中分别实现了高达10.38×和13.09×的加速效果，较现有最优推理加速方法提升了90.6%。

> Large Language Models (LLMs) have demonstrated remarkable capabilities in code editing, substantially enhancing software development productivity. However, the inherent complexity of code editing tasks forces existing approaches to rely on LLMs' autoregressive end-to-end generation, where decoding speed plays a critical role in efficiency. While inference acceleration techniques like speculative decoding are applied to improve the decoding efficiency, these methods fail to account for the unique characteristics of code editing tasks where changes are typically localized and existing code segments are reused. To address this limitation, we propose EfficientEdit, a novel method that improves LLM-based code editing efficiency through two key mechanisms based on speculative decoding: (1) effective reuse of original code segments while identifying potential edit locations, and (2) efficient generate edit content via high-quality drafts from edit-oriented draft models and a dynamic verification mechanism that balances quality and acceleration. Experimental results show that EfficientEdit can achieve up to 10.38$\times$ and 13.09$\times$ speedup compared to standard autoregressive decoding in CanItEdit and CodeIF-Bench, respectively, outperforming state-of-the-art inference acceleration approaches by up to 90.6%.

[Arxiv](https://arxiv.org/abs/2506.02780)