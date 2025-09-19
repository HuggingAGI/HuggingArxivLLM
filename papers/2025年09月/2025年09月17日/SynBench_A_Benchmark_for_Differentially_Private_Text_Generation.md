# # SynBench：差分隐私文本生成基准

发布时间：2025年09月17日

`LLM应用` `医疗健康` `金融科技`

> SynBench: A Benchmark for Differentially Private Text Generation

# 摘要

> 在医疗、金融等高风险领域，数据驱动的决策支持因监管、机构及隐私顾虑，在数据共享方面面临重重阻碍。尽管生成式AI模型（如大型语言模型）近年在开放域任务中表现亮眼，但其在敏感环境中的应用仍受限于行为不可预测性，以及用于基准测试的隐私保护数据集匮乏。现有的匿名化方法常显不足，尤其针对非结构化文本——编辑和掩码操作仍可能导致身份重新识别。差分隐私（DP）则提供了一种原则性解决方案，可生成具备正式隐私保障的合成数据。为此，本研究通过三项关键贡献应对这些挑战。首先，我们构建了一套综合评估框架，包含标准化的效用与保真度指标，并涵盖九个精心筛选的数据集。这些数据集捕捉了领域特有的复杂性，例如技术术语、长上下文依赖及专业文档结构。其次，我们开展了大规模实证研究，对最先进的差分隐私文本生成方法及不同规模、不同微调策略的大型语言模型进行基准测试。结果显示，在差分隐私约束下生成高质量领域特定合成数据仍是未解难题——领域复杂性越高，性能下降越明显。第三，我们针对合成文本开发了成员推理攻击（MIA）方法，首次通过实证证明：若使用可能存在于预训练语料库中的公共数据集，会导致声称的隐私保障失效。研究结果强调，亟需加强隐私审计，同时也揭示了开放域与专业领域评估之间的长期差距，为生成式AI在隐私敏感高风险场景中的负责任部署提供了重要启示。

> Data-driven decision support in high-stakes domains like healthcare and finance faces significant barriers to data sharing due to regulatory, institutional, and privacy concerns. While recent generative AI models, such as large language models, have shown impressive performance in open-domain tasks, their adoption in sensitive environments remains limited by unpredictable behaviors and insufficient privacy-preserving datasets for benchmarking. Existing anonymization methods are often inadequate, especially for unstructured text, as redaction and masking can still allow re-identification. Differential Privacy (DP) offers a principled alternative, enabling the generation of synthetic data with formal privacy assurances. In this work, we address these challenges through three key contributions. First, we introduce a comprehensive evaluation framework with standardized utility and fidelity metrics, encompassing nine curated datasets that capture domain-specific complexities such as technical jargon, long-context dependencies, and specialized document structures. Second, we conduct a large-scale empirical study benchmarking state-of-the-art DP text generation methods and LLMs of varying sizes and different fine-tuning strategies, revealing that high-quality domain-specific synthetic data generation under DP constraints remains an unsolved challenge, with performance degrading as domain complexity increases. Third, we develop a membership inference attack (MIA) methodology tailored for synthetic text, providing first empirical evidence that the use of public datasets - potentially present in pre-training corpora - can invalidate claimed privacy guarantees. Our findings underscore the urgent need for rigorous privacy auditing and highlight persistent gaps between open-domain and specialist evaluations, informing responsible deployment of generative AI in privacy-sensitive, high-stakes settings.

[Arxiv](https://arxiv.org/abs/2509.14594)