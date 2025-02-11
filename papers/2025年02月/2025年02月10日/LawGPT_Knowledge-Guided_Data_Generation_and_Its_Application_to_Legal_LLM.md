# LawGPT: 知识引导的数据生成及其在法律 LLM 中的应用

发布时间：2025年02月10日

`LLM应用` `法律推理` `法律领域`

> LawGPT: Knowledge-Guided Data Generation and Its Application to Legal LLM

# 摘要

> 大型语言模型（LLMs）无论专有还是开源，在自然语言处理任务中表现卓越。然而，在法律推理任务中，它们仍面临显著的局限性。专有模型带来数据隐私风险和高昂成本，开源模型则因缺乏法律领域数据表现欠佳。为解决这一问题，我们提出了KgDG，一个基于知识引导的法律推理数据生成框架。通过引入精炼和验证流程，确保生成数据的质量。借助KgDG，我们创建了一个包含5万条高质量示例的合成法律推理数据集。我们的训练模型LawGPT不仅超越了现有的法律领域专用LLMs，其性能还与专有LLMs相当，充分证明了KgDG和LawGPT的有效性。我们的代码和资源已公开发布于https://anonymous.4open.science/r/KgDG-45F5。

> Large language models (LLMs), both proprietary and open-source, have demonstrated remarkable capabilities across various natural language processing tasks. However, they face significant limitations in legal reasoning tasks. Proprietary models introduce data privacy risks and high inference costs, while open-source models underperform due to insufficient legal domain training data. To address these limitations, we study data generation for legal reasoning to improve the legal reasoning performance of open-source LLMs with the help of proprietary LLMs. This is challenging due to the lack of legal knowledge in proprietary LLMs and the difficulty in verifying the generated data. We propose KgDG, a knowledge-guided data generation framework for legal reasoning. Our framework enables leveraging legal knowledge to enhance generation diversity and introduces a refinement and verification process to ensure the quality of generated data. Moreover, we expand the generated dataset to further enhance the LLM reasoning capabilities. Using KgDG, we create a synthetic legal reasoning dataset containing 50K high-quality examples. Our trained model LawGPT outperforms existing legal-specific LLMs and achieves performance comparable to proprietary LLMs, demonstrating the effectiveness of KgDG and LawGPT. Our code and resources is publicly available at https://anonymous.4open.science/r/KgDG-45F5 .

[Arxiv](https://arxiv.org/abs/2502.06572)