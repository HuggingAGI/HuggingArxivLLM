# MindOmni: 利用RGPO方法在视觉语言模型中释放推理生成能力

发布时间：2025年05月19日

`LLM应用` `多模态`

> MindOmni: Unleashing Reasoning Generation in Vision Language Models with RGPO

# 摘要

> 当前文本到图像系统在处理多模态输入和复杂推理任务时存在局限性。为此，我们推出MindOmni——一个通过强化学习实现推理生成的统一多模态大语言模型。该模型采用创新的三阶段训练策略：首先构建一个融合了解码器仅扩散模块的统一视觉语言模型，随后利用链式思维（CoT）指令数据进行监督微调，最后通过我们提出的推理生成策略优化（RGPO）算法，借助多模态反馈实现高效策略更新。实验结果表明，MindOmni在理解和生成任务中均超越现有模型，尤其在数学推理等细粒度推理生成能力方面表现突出。项目代码即将在\href{https://github.com/EasonXiao-888/MindOmni}{https://github.com/EasonXiao-888/MindOmni}开放。

> Recent text-to-image systems face limitations in handling multimodal inputs and complex reasoning tasks. We introduce MindOmni, a unified multimodal large language model that addresses these challenges by incorporating reasoning generation through reinforcement learning. MindOmni leverages a three-phase training strategy: i) design of a unified vision language model with a decoder-only diffusion module, ii) supervised fine-tuning with Chain-of-Thought (CoT) instruction data, and iii) our proposed Reasoning Generation Policy Optimization (RGPO) algorithm, utilizing multimodal feedback to effectively guide policy updates. Experimental results demonstrate that MindOmni outperforms existing models, achieving impressive performance on both understanding and generation benchmarks, meanwhile showcasing advanced fine-grained reasoning generation capabilities, especially with mathematical reasoning instruction. All codes will be made public at \href{https://github.com/EasonXiao-888/MindOmni}{https://github.com/EasonXiao-888/MindOmni}.

[Arxiv](https://arxiv.org/abs/2505.13031)