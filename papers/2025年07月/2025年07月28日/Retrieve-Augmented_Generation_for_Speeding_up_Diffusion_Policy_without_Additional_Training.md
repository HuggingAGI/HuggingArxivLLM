# 检索增强生成：加速扩散策略的生成，无需额外训练

发布时间：2025年07月28日

`RAG` `模仿学习` `框架设计`

> Retrieve-Augmented Generation for Speeding up Diffusion Policy without Additional Training

# 摘要

> 扩散策略（DPs）在模仿学习任务中表现优异，但其依赖的扩散模型需要多次去噪步骤才能生成动作，导致生成时间过长。为解决这一问题，研究者提出了基于知识蒸馏的一致性策略（CP）等方法，但这些方法需要大量训练时间，尤其在处理困难任务时。本研究提出了一种名为RAGDP（基于知识增强的扩散策略生成框架）的创新框架，通过利用知识库加速预训练扩散策略的推理，无需额外训练。具体而言，RAGDP通过DP编码器对观测-动作对进行编码，构建专家演示的向量数据库。推理时，对当前观测进行嵌入，并提取最相似的专家动作。结合中间去噪步骤，显著减少了生成动作所需的步骤数。实验表明，RAGDP结合基础模型和现有加速方法，可以在不增加训练成本的情况下，有效提升准确性和推理速度。即使将模型加速20倍，RAGDP仍保持7%的准确性优势，超越CP等蒸馏模型。

> Diffusion Policies (DPs) have attracted attention for their ability to achieve significant accuracy improvements in various imitation learning tasks. However, DPs depend on Diffusion Models, which require multiple noise removal steps to generate a single action, resulting in long generation times. To solve this problem, knowledge distillation-based methods such as Consistency Policy (CP) have been proposed. However, these methods require a significant amount of training time, especially for difficult tasks. In this study, we propose RAGDP (Retrieve-Augmented Generation for Diffusion Policies) as a novel framework that eliminates the need for additional training using a knowledge base to expedite the inference of pre-trained DPs. In concrete, RAGDP encodes observation-action pairs through the DP encoder to construct a vector database of expert demonstrations. During inference, the current observation is embedded, and the most similar expert action is extracted. This extracted action is combined with an intermediate noise removal step to reduce the number of steps required compared to the original diffusion step. We show that by using RAGDP with the base model and existing acceleration methods, we improve the accuracy and speed trade-off with no additional training. Even when accelerating the models 20 times, RAGDP maintains an advantage in accuracy, with a 7% increase over distillation models such as CP.

[Arxiv](https://arxiv.org/abs/2507.21452)