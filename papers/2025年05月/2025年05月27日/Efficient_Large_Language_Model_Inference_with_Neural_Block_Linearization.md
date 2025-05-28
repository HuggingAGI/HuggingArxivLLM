# # 摘要
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年05月27日

`LLM理论` `模型优化` `推理加速`

> Efficient Large Language Model Inference with Neural Block Linearization

# 摘要

> 基于transformer的大型语言模型（LLMs）在推理过程中面临高计算需求的挑战。为此，我们提出了一种名为神经块线性化（NBL）的创新框架，通过用线性最小均方误差估计器的线性近似替代自注意力层来加速推理。NBL借助典型相关分析计算近似误差的理论上限，并以此作为替换标准，选择线性化误差最小的模型层。该方法无需微调即可高效应用于预训练的LLMs。实验结果表明，NBL在多个推理基准测试中实现了显著的加速，同时保持了优秀的准确性。例如，在DeepSeek-R1-Distill-Llama-8B模型中，对12个自注意力层应用NBL可使推理速度提升32%，且准确率仅下降不到1%。这一方法为提升LLMs推理效率提供了灵活且有前景的解决方案。

> The high inference demands of transformer-based Large Language Models (LLMs) pose substantial challenges in their deployment. To this end, we introduce Neural Block Linearization (NBL), a novel framework for accelerating transformer model inference by replacing self-attention layers with linear approximations derived from Linear Minimum Mean Squared Error estimators. NBL leverages Canonical Correlation Analysis to compute a theoretical upper bound on the approximation error. Then, we use this bound as a criterion for substitution, selecting the LLM layers with the lowest linearization error. NBL can be efficiently applied to pre-trained LLMs without the need for fine-tuning. In experiments, NBL achieves notable computational speed-ups while preserving competitive accuracy on multiple reasoning benchmarks. For instance, applying NBL to 12 self-attention layers in DeepSeek-R1-Distill-Llama-8B increases the inference speed by 32% with less than 1% accuracy trade-off, making it a flexible and promising solution to improve the inference efficiency of LLMs.

[Arxiv](https://arxiv.org/abs/2505.21077)