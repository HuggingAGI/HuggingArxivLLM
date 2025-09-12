# 多模态大型语言模型能否清晰看清材料？材料表征的多模态基准测试

发布时间：2025年09月11日

`LLM应用` `工业与制造`

> Can Multimodal LLMs See Materials Clearly? A Multimodal Benchmark on Materials Characterization

# 摘要

> 材料表征是获取材料信息的基础，它揭示了加工-微观结构-性能之间的关系，而这些关系正是指导材料设计与优化的关键。尽管多模态大语言模型（MLLMs）近年来在材料科学的生成与预测任务中展现出潜力，但其对实际表征成像数据的理解能力尚未得到充分挖掘。为填补这一空白，我们提出了MatCha——首个材料表征图像理解基准，它包含1500个问题，均需专家级领域知识才能解答。MatCha涵盖材料研究的四个关键阶段，包含21项不同任务，每项任务都旨在模拟材料科学家面临的真实挑战。我们在MatCha上对最先进的MLLMs进行评估后发现，它们与人类专家相比存在显著性能差距。这些模型在处理需要高级专业知识和复杂视觉感知的问题时，性能会明显下降。简单的少样本提示和思维链提示难以克服这些局限性。这些发现表明，现有MLLMs对实际材料表征场景的适应性仍有不足。我们期望MatCha能推动新材料发现、自主科学智能体等领域的未来研究。MatCha的相关资源可访问https://github.com/FreedomIntelligence/MatCha获取。

> Materials characterization is fundamental to acquiring materials information, revealing the processing-microstructure-property relationships that guide material design and optimization. While multimodal large language models (MLLMs) have recently shown promise in generative and predictive tasks within materials science, their capacity to understand real-world characterization imaging data remains underexplored. To bridge this gap, we present MatCha, the first benchmark for materials characterization image understanding, comprising 1,500 questions that demand expert-level domain expertise. MatCha encompasses four key stages of materials research comprising 21 distinct tasks, each designed to reflect authentic challenges faced by materials scientists. Our evaluation of state-of-the-art MLLMs on MatCha reveals a significant performance gap compared to human experts. These models exhibit degradation when addressing questions requiring higher-level expertise and sophisticated visual perception. Simple few-shot and chain-of-thought prompting struggle to alleviate these limitations. These findings highlight that existing MLLMs still exhibit limited adaptability to real-world materials characterization scenarios. We hope MatCha will facilitate future research in areas such as new material discovery and autonomous scientific agents. MatCha is available at https://github.com/FreedomIntelligence/MatCha.

[Arxiv](https://arxiv.org/abs/2509.09307)