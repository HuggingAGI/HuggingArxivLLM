# CoSteer：解码时协作个性化，通过局部增量引导实现

发布时间：2025年07月07日

`LLM应用` `个性化生成`

> CoSteer: Collaborative Decoding-Time Personalization via Local Delta Steering

# 摘要

> 个性化文本生成在跨文化、时间和上下文维度适应多样化、动态变化的用户背景中发挥着关键作用。现有方法虽依赖集中式微调或静态偏好对齐，但在个人设备资源限制下难以实现实时适应。这导致了基于云的大模型无法访问本地化用户信息，而设备端小模型生成质量受限的两难困境。为解决这一矛盾，我们提出了CoSteer，一种通过本地化增量引导实现解码时个性化的协作框架。我们发现本地小模型在感知和个人背景无关输出间的logits差异可作为基于云LLMs的引导信号。具体而言，我们将token级优化视为在线学习问题，其中本地delta向量动态调整远程LLM在设备端环境中的logits。通过仅传输最终引导的token而非原始数据或中间向量，CoSteer在保持基于云LLMs一般能力的同时，确保了隐私保护且无需微调。实验结果表明，CoSteer能够有效利用本地存储的用户资料和历史记录，帮助LLMs生成个性化内容，通过设备端数据处理确保隐私，同时保持可接受的计算开销。

> Personalized text generation has become crucial for adapting language models to diverse and evolving users' personal context across cultural, temporal, and contextual dimensions. While existing methods often rely on centralized fine-tuning or static preference alignment, they struggle to achieve real-time adaptation under resource constraints inherent to personal devices. This limitation creates a dilemma: large cloud-based models lack access to localized user-specific information, while small on-device models cannot match the generation quality of their cloud counterparts. To address this dichotomy, we present CoSteer, a novel collaborative framework that enables decoding-time personalization through localized delta steering. Our key insight lies in leveraging the logits difference between personal context-aware and -agnostic outputs from local small models as steering signals for cloud-based LLMs. Specifically, we formulate token-level optimization as an online learning problem, where local delta vectors dynamically adjust the remote LLM's logits within the on-device environment. This approach preserves privacy by transmitting only the final steered tokens rather than raw data or intermediate vectors, while maintaining cloud-based LLMs' general capabilities without fine-tuning. Through comprehensive experiments on various personalized generation tasks, we demonstrate that CoSteer effectively assists LLMs in generating personalized content by leveraging locally stored user profiles and histories, ensuring privacy preservation through on-device data processing while maintaining acceptable computational overhead.

[Arxiv](https://arxiv.org/abs/2507.04756)