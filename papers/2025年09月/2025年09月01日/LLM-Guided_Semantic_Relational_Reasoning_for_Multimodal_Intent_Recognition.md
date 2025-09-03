# 面向多模态意图识别的LLM引导语义关系推理

发布时间：2025年09月01日

`LLM应用` `基础理论`

> LLM-Guided Semantic Relational Reasoning for Multimodal Intent Recognition

# 摘要

> 在现实场景中，从多模态信号理解人类意图对分析人类行为和增强人机交互至关重要。但现有方法受限于对模态的依赖，难以通过细粒度语义的关系推理实现复杂意图理解。为此，本文提出一种新颖的LLM引导语义关系推理（LGSRR）方法，借助大型语言模型（LLMs）的海量知识构建语义基础，提升小型模型的关系推理能力。具体而言，我们提出基于LLM的策略：通过由浅入深的思维链（CoT）自主挖掘、描述语义线索并按重要性排序，提取细粒度语义作为后续推理指导，且无需依赖人工定义的先验知识。此外，我们基于逻辑原理对三种基本语义关系类型进行形式化建模，分析其细微相互作用以实现更高效的关系推理。多模态意图与对话行为识别任务的大量实验表明，LGSRR性能优于现有最先进方法，且在多种语义理解场景中均实现稳定性能提升。完整数据和代码已开源至https://github.com/thuiar/LGSRR。

> Understanding human intents from multimodal signals is critical for analyzing human behaviors and enhancing human-machine interactions in real-world scenarios. However, existing methods exhibit limitations in their modality-level reliance, constraining relational reasoning over fine-grained semantics for complex intent understanding. This paper proposes a novel LLM-Guided Semantic Relational Reasoning (LGSRR) method, which harnesses the expansive knowledge of large language models (LLMs) to establish semantic foundations that boost smaller models' relational reasoning performance. Specifically, an LLM-based strategy is proposed to extract fine-grained semantics as guidance for subsequent reasoning, driven by a shallow-to-deep Chain-of-Thought (CoT) that autonomously uncovers, describes, and ranks semantic cues by their importance without relying on manually defined priors. Besides, we formally model three fundamental types of semantic relations grounded in logical principles and analyze their nuanced interplay to enable more effective relational reasoning. Extensive experiments on multimodal intent and dialogue act recognition tasks demonstrate LGSRR's superiority over state-of-the-art methods, with consistent performance gains across diverse semantic understanding scenarios. The complete data and code are available at https://github.com/thuiar/LGSRR.

[Arxiv](https://arxiv.org/abs/2509.01337)