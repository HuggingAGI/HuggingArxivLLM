# PersonaX：含LLM推断行为特征的多模态数据集

发布时间：2025年09月14日

`LLM应用` `基础理论`

> PersonaX: Multimodal Datasets with LLM-Inferred Behavior Traits

# 摘要

> 理解人类行为特征是人机交互、计算社会科学及个性化AI系统的核心议题。这种理解往往需要整合多种模态来捕捉细微的模式与关联。然而，现有资源鲜少提供将行为描述符与面部属性、传记信息等互补模态相结合的数据集。为填补这一空白，我们提出PersonaX——一个精心构建的多模态数据集集合，旨在支持跨模态的公众特征综合分析。PersonaX包含两部分：（1）CelebPersona，涵盖9444名来自不同职业的公众人物；（2）AthlePersona，覆盖7个主要体育联盟的4181名职业运动员。每个数据集均包含由三个高性能大型语言模型推断的行为特征评估，同时配有面部图像和结构化传记特征。我们从两个互补层面对PersonaX进行分析：首先，从文本描述中提取高层级特征分数，并通过五种统计独立性测试考察其与其他模态的关系；其次，提出一种专为多模态和多测量数据定制的新型因果表示学习（CRL）框架，并提供理论可识别性保证。在合成数据和真实世界数据上的实验均验证了我们方法的有效性。通过统一结构化与非结构化分析，PersonaX为研究LLM推断的行为特征与视觉、传记属性的关联奠定了基础，推动了多模态特征分析与因果推理的发展。

> Understanding human behavior traits is central to applications in human-computer interaction, computational social science, and personalized AI systems. Such understanding often requires integrating multiple modalities to capture nuanced patterns and relationships. However, existing resources rarely provide datasets that combine behavioral descriptors with complementary modalities such as facial attributes and biographical information. To address this gap, we present PersonaX, a curated collection of multimodal datasets designed to enable comprehensive analysis of public traits across modalities. PersonaX consists of (1) CelebPersona, featuring 9444 public figures from diverse occupations, and (2) AthlePersona, covering 4181 professional athletes across 7 major sports leagues. Each dataset includes behavioral trait assessments inferred by three high-performing large language models, alongside facial imagery and structured biographical features. We analyze PersonaX at two complementary levels. First, we abstract high-level trait scores from text descriptions and apply five statistical independence tests to examine their relationships with other modalities. Second, we introduce a novel causal representation learning (CRL) framework tailored to multimodal and multi-measurement data, providing theoretical identifiability guarantees. Experiments on both synthetic and real-world data demonstrate the effectiveness of our approach. By unifying structured and unstructured analysis, PersonaX establishes a foundation for studying LLM-inferred behavioral traits in conjunction with visual and biographical attributes, advancing multimodal trait analysis and causal reasoning.

[Arxiv](https://arxiv.org/abs/2509.11362)