# LLaMP: 为高保真材料知识检索与蒸馏而强化的语言模型

发布时间：2024年10月09日

`RAG

理由：这篇论文介绍了一种多模态检索增强生成（RAG）框架，名为LLaMP，它结合了分层推理与行动（ReAct）代理，能够动态且递归地与材料科学数据交互。RAG框架的核心是通过检索外部知识来增强生成过程，这与RAG的定义高度契合。因此，这篇论文应被分类为RAG。` `材料科学` `计算化学`

> LLaMP: Large Language Model Made Powerful for High-fidelity Materials Knowledge Retrieval and Distillation

# 摘要

> # 摘要
减少大型语言模型（LLMs）的幻觉在科学应用中至关重要，因为科学领域对可靠性和可重复性要求极高。然而，LLMs 天生缺乏长期记忆，这使得在特定领域的文献和数据上对其进行微调成为一项复杂且带有偏见的任务。本文介绍了 LLaMP，一种多模态检索增强生成（RAG）框架，采用分层推理与行动（ReAct）代理，能够动态且递归地与 Materials Project（MP）上的计算和实验数据交互，并通过高通量工作流接口运行原子模拟。无需微调，LLaMP 展示了强大的工具使用能力，能够理解和整合材料科学概念的各种模态，即时获取相关数据存储，处理高阶数据（如晶体结构和弹性张量），并简化计算材料和化学中的复杂任务。我们提出了一种结合不确定性和置信度估计的简单指标，用于评估 LLaMP 和普通 LLMs 的响应自洽性。我们的基准测试表明，LLaMP 有效缓解了 LLMs 的内在偏见，纠正了来自混合数据源的体积模量、电子带隙和形成能量的错误。我们还展示了 LLaMP 编辑晶体结构和使用预训练机器学习力场运行退火分子动力学模拟的能力。该框架提供了一种直观且几乎无幻觉的方法来探索和扩展材料信息学，并为知识蒸馏和微调其他语言模型建立了途径。代码和实时演示可在 https://github.com/chiang-yuan/llamp 获取。

> Reducing hallucination of Large Language Models (LLMs) is imperative for use in the sciences, where reliability and reproducibility are crucial. However, LLMs inherently lack long-term memory, making it a nontrivial, ad hoc, and inevitably biased task to fine-tune them on domain-specific literature and data. Here we introduce LLaMP, a multimodal retrieval-augmented generation (RAG) framework of hierarchical reasoning-and-acting (ReAct) agents that can dynamically and recursively interact with computational and experimental data on Materials Project (MP) and run atomistic simulations via high-throughput workflow interface. Without fine-tuning, LLaMP demonstrates strong tool usage ability to comprehend and integrate various modalities of materials science concepts, fetch relevant data stores on the fly, process higher-order data (such as crystal structure and elastic tensor), and streamline complex tasks in computational materials and chemistry. We propose a simple metric combining uncertainty and confidence estimates to evaluate the self-consistency of responses by LLaMP and vanilla LLMs. Our benchmark shows that LLaMP effectively mitigates the intrinsic bias in LLMs, counteracting the errors on bulk moduli, electronic bandgaps, and formation energies that seem to derive from mixed data sources. We also demonstrate LLaMP's capability to edit crystal structures and run annealing molecular dynamics simulations using pre-trained machine-learning force fields. The framework offers an intuitive and nearly hallucination-free approach to exploring and scaling materials informatics, and establishes a pathway for knowledge distillation and fine-tuning other language models. Code and live demo are available at https://github.com/chiang-yuan/llamp

[Arxiv](https://arxiv.org/abs/2401.17244)