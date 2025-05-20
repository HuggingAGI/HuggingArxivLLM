# PsyMem：细粒度心理对齐与显式记忆控制，助力高级角色扮演大型语言模型

发布时间：2025年05月19日

`LLM应用

理由：这篇论文主要探讨了如何改进大型语言模型在角色扮演任务中的表现，提出了一个新的框架，并通过实验验证了其在特定应用场景中的有效性。因此，它属于LLM应用类别。` `角色扮演` `可信社会模拟`

> PsyMem: Fine-grained psychological alignment and Explicit Memory Control for Advanced Role-Playing LLMs

# 摘要

> 现有基于LLM的角色扮演方法常依赖表面的文字描述或简化的评估指标，难以有效建模角色的内在与外在维度。此外，这些方法通常通过隐式的模型知识或基础检索增强生成来模拟角色记忆，缺乏显式的记忆对齐，导致记忆一致性不足。这些问题削弱了角色扮演LLM在可信社会模拟等应用中的可靠性。为解决这些局限，我们提出了PsyMem——一个结合精细心理属性与显式记忆控制的创新框架。PsyMem通过补充26个心理指标，使角色建模更加细致。同时，PsyMem采用记忆对齐训练，显式训练模型将角色回应与记忆对齐，从而实现在推理过程中进行动态记忆控制。通过对Qwen2.5-7B-Instruct模型进行训练（使用包含5,414个角色和38,962个对话的专门设计数据集），得到的PsyMem-Qwen模型在角色扮演方面超越了基线模型，在人类相似度和角色忠诚度方面表现最佳。

> Existing LLM-based role-playing methods often rely on superficial textual descriptions or simplistic metrics, inadequately modeling both intrinsic and extrinsic character dimensions. Additionally, they typically simulate character memory with implicit model knowledge or basic retrieval augment generation without explicit memory alignment, compromising memory consistency. The two issues weaken reliability of role-playing LLMs in several applications, such as trustworthy social simulation. To address these limitations, we propose PsyMem, a novel framework integrating fine-grained psychological attributes and explicit memory control for role-playing. PsyMem supplements textual descriptions with 26 psychological indicators to detailed model character. Additionally, PsyMem implements memory alignment training, explicitly trains the model to align character's response with memory, thereby enabling dynamic memory-controlled responding during inference. By training Qwen2.5-7B-Instruct on our specially designed dataset (including 5,414 characters and 38,962 dialogues extracted from novels), the resulting model, termed as PsyMem-Qwen, outperforms baseline models in role-playing, achieving the best performance in human-likeness and character fidelity.

[Arxiv](https://arxiv.org/abs/2505.12814)