# Logic-RAG：通过利用视觉空间知识增强大型多模态模型的能力，提升道路场景理解效果

发布时间：2025年03月16日

`RAG` `自动驾驶` `人工智能`

> Logic-RAG: Augmenting Large Multimodal Models with Visual-Spatial Knowledge for Road Scene Understanding

# 摘要

> 大模态模型（LMMs）正逐步融入自动驾驶系统，用于提升用户交互体验。然而，这些模型在精细空间推理方面的局限性对系统可解释性和用户信任度带来挑战。本文介绍了一种名为Logic-RAG的新型检索增强生成（RAG）框架，旨在提升LMMs在驾驶场景中的空间理解能力。Logic-RAG利用感知模块、查询到逻辑嵌入器和逻辑推理引擎构建基于一阶逻辑（FOL）的对象间关系动态知识库。我们通过合成与真实驾驶视频对Logic-RAG进行了视觉空间查询评估。当使用GPT-4V和Claude 3.5等流行LMMs模拟自动驾驶系统时，这些模型在合成驾驶场景中的准确率仅为55%，在真实驾驶场景中低于75%。借助Logic-RAG增强后，这些模型的准确率分别提升至80%和90%以上。消融实验表明，即使不进行逻辑推理，Logic-RAG构建的事实背景也能将准确率提升15%。Logic-RAG具有良好的扩展性：支持无缝替换组件为改进版本，并允许领域专家以FOL和自然语言形式构建新知识。总之，Logic-RAG有效弥补了LMMs在自动驾驶应用中的关键空间推理缺陷。代码和数据可在https://github.com/Imran2205/LogicRAG获取。

> Large multimodal models (LMMs) are increasingly integrated into autonomous driving systems for user interaction. However, their limitations in fine-grained spatial reasoning pose challenges for system interpretability and user trust. We introduce Logic-RAG, a novel Retrieval-Augmented Generation (RAG) framework that improves LMMs' spatial understanding in driving scenarios. Logic-RAG constructs a dynamic knowledge base (KB) about object-object relationships in first-order logic (FOL) using a perception module, a query-to-logic embedder, and a logical inference engine. We evaluated Logic-RAG on visual-spatial queries using both synthetic and real-world driving videos. When using popular LMMs (GPT-4V, Claude 3.5) as proxies for an autonomous driving system, these models achieved only 55% accuracy on synthetic driving scenes and under 75% on real-world driving scenes. Augmenting them with Logic-RAG increased their accuracies to over 80% and 90%, respectively. An ablation study showed that even without logical inference, the fact-based context constructed by Logic-RAG alone improved accuracy by 15%. Logic-RAG is extensible: it allows seamless replacement of individual components with improved versions and enables domain experts to compose new knowledge in both FOL and natural language. In sum, Logic-RAG addresses critical spatial reasoning deficiencies in LMMs for autonomous driving applications. Code and data are available at https://github.com/Imran2205/LogicRAG.

[Arxiv](https://arxiv.org/abs/2503.12663)