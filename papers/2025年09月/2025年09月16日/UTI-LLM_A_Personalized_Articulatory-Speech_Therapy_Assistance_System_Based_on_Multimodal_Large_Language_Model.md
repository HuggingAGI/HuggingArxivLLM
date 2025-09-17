# UTI-LLM：基于多模态大型语言模型的个性化发音言语治疗辅助系统

发布时间：2025年09月16日

`LLM应用` `医疗健康`

> UTI-LLM: A Personalized Articulatory-Speech Therapy Assistance System Based on Multimodal Large Language Model

# 摘要

> 言语治疗在改善中风等神经损伤引起的言语障碍方面发挥着关键作用。然而，传统人工与计算机辅助系统在实时可用性和发音动作反馈上存在局限，制约了其实际应用。近年来，多模态大型语言模型（MLLMs）在医疗健康领域展现出巨大潜力，尤其凭借其整合多模态数据的能力，可提供适应性评估与治疗反馈。但目前仍面临诸多挑战：发音信息获取与融合不足、发音器官运动轨迹解析不充分，以及高质量领域数据集稀缺，这些都阻碍了MLLMs在言语治疗中的应用。为解决这些问题，我们提出一种基于MLLM的言语康复辅助系统，该系统协同融合超声舌成像与语音信号，以提供精准、交互式的发音反馈。我们构建了高质量的领域数据集，包含超声舌成像-语音对话对（UTI-speech）。该数据集通过微调增强模型的临床适应性。基于此数据集，我们提出超声视频与语音信号的时空融合训练策略，可实现细粒度发音障碍分析，并最终生成可操作的反馈建议。

> Speech therapy plays a critical role in training speech disorders caused by neurological impairments such as stroke. However, traditional manual and computer-assisted systems are limited in real-time accessibility and articulatory motion feedback, constraining their practical utility. Recent advances in multimodal large language models (MLLMs) have demonstrated significant potential in healthcare, particularly through their ability to integrate multimodal data for adaptive assessment and therapeutic feedback. Nevertheless, challenges including insufficient acquisition and fusion of articulatory information, inadequate parsing of articulatory organ motion trajectories, and the scarcity of high-quality domain-specific datasets hinder the application of MLLMs in speech therapy. To address these limitations, we propose an MLLM-based speech rehabilitation assistance system that synergistically leverages ultrasound tongue imaging and speech signals to deliver precise, interactive articulatory feedback. We construct a high-quality domain-specific dataset comprising UTI-speech dialogue pairs. This dataset facilitates fine-tuning to enhance the model's clinical adaptability. Building on this dataset, our methods achieves spatiotemporal fusion training strategy of ultrasound videos and speech signals, enabling fine-grained articulatory impairment analysis and ultimately generating actionable feedback.

[Arxiv](https://arxiv.org/abs/2509.13145)