# NeSyCoCo：一款用于组合泛化的神经符号概念合成工具

发布时间：2024年12月20日

`Agent` `人工智能` `视觉语言推理`

> NeSyCoCo: A Neuro-Symbolic Concept Composer for Compositional Generalization

# 摘要

> 组合泛化对于人工智能代理完成复杂的视觉语言推理任务极为关键。神经符号方法在捕捉组合结构上展现出良好前景，然而也面临重大挑战：（a）依赖预定义的谓词进行符号表示，限制了适应性；（b）从原始数据中提取谓词存在困难；（c）使用不可微操作来组合基本概念。为应对这些问题，我们提出了 NeSyCoCo 这一神经符号框架，借助大型语言模型（LLMs）生成符号表示，并将其映射到可微的神经计算。NeSyCoCo 带来了三项创新：（a）用依赖结构增强自然语言输入，强化与符号表示的对齐；（b）运用分布式词表示将各种基于语言的逻辑谓词与神经模块相连接；（c）利用归一化谓词分数的软组合来对齐符号推理和可微推理。我们的框架在 ReaSCAN 和 CLEVR-CoGenT 组合泛化基准测试中取得了领先成果，并在 CLEVR-SYN 基准测试中针对新的概念展现出强劲性能。

> Compositional generalization is crucial for artificial intelligence agents to solve complex vision-language reasoning tasks. Neuro-symbolic approaches have demonstrated promise in capturing compositional structures, but they face critical challenges: (a) reliance on predefined predicates for symbolic representations that limit adaptability, (b) difficulty in extracting predicates from raw data, and (c) using non-differentiable operations for combining primitive concepts. To address these issues, we propose NeSyCoCo, a neuro-symbolic framework that leverages large language models (LLMs) to generate symbolic representations and map them to differentiable neural computations. NeSyCoCo introduces three innovations: (a) augmenting natural language inputs with dependency structures to enhance the alignment with symbolic representations, (b) employing distributed word representations to link diverse, linguistically motivated logical predicates to neural modules, and (c) using the soft composition of normalized predicate scores to align symbolic and differentiable reasoning. Our framework achieves state-of-the-art results on the ReaSCAN and CLEVR-CoGenT compositional generalization benchmarks and demonstrates robust performance with novel concepts in the CLEVR-SYN benchmark.

[Arxiv](https://arxiv.org/abs/2412.15588)