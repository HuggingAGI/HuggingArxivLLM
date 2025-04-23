# AlignRAG：一个灵活的框架，解决RAG中检索感知推理的对齐问题。

发布时间：2025年04月21日

`RAG` `文本生成`

> AlignRAG: An Adaptable Framework for Resolving Misalignments in Retrieval-Aware Reasoning of RAG

# 摘要

> 检索增强生成（RAG）已成为基于知识的文本生成的基础范式。然而，现有的RAG流水线往往难以确保推理轨迹与检索内容施加的证据约束保持一致。本文重新定义RAG为一种检索感知推理问题，并揭示了一个核心挑战：推理不一致，即模型推理轨迹与检索证据之间的不匹配。为解决这一问题，我们提出了AlignRAG——一种新型测试时间框架，通过迭代的基于批注的对齐（CDA）步骤缓解推理不一致。与依赖静态训练或事后选择的传统方法不同，AlignRAG在推理过程中主动优化推理轨迹，确保与证据的细粒度对齐。我们的框架通过以下方式为检索感知推理引入新范式：（1）构建上下文丰富的训练语料库；（2）生成对比批注；（3）训练专门的	extit{批评语言模型（CLM）}识别推理不一致；（4）迭代优化推理轨迹。实验结果表明，AlignRAG在所有基线方法上表现更优，并可作为即插即用模块集成到现有RAG流水线中。通过将RAG重新定义为结构化推理轨迹，并为RAG中的推理不一致问题建立测试时间框架，AlignRAG推动了检索感知生成的实用进展。

> Retrieval-augmented generation (RAG) has emerged as a foundational paradigm for knowledge-grounded text generation. However, existing RAG pipelines often fail to ensure that the reasoning trajectories align with the evidential constraints imposed by retrieved content. In this paper, we reframe RAG as a problem of retrieval-aware reasoning and identify a core challenge: reasoning misalignment-the mismatch between a model's reasoning trajectory and the retrieved evidence. To address this challenge, we propose AlignRAG, a novel test-time framework that mitigates reasoning misalignment through iterative Critique-Driven Alignment (CDA) steps. In contrast to prior approaches that rely on static training or post-hoc selection, AlignRAG actively refines reasoning trajectories during inference by enforcing fine-grained alignment with evidence. Our framework introduces a new paradigm for retrieval-aware reasoning by: (1) constructing context-rich training corpora; (2) generating contrastive critiques from preference-aware reasoning trajectories; (3) training a dedicated \textit{Critic Language Model (CLM)} to identify reasoning misalignments; and (4) applying CDA steps to optimize reasoning trajectories iteratively. Empirical results demonstrate that AlignRAG consistently outperforms all baselines and could integrate as a plug-and-play module into existing RAG pipelines without further changes. By reconceptualizing RAG as a structured reasoning trajectory and establishing the test-time framework for correcting reasoning misalignments in RAG, AlignRAG provides practical advancements for retrieval-aware generation.

[Arxiv](https://arxiv.org/abs/2504.14858)