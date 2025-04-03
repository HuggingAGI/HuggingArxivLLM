# YourBench：为每个人打造轻松定制的专属评估集

发布时间：2025年04月02日

`LLM应用` `人工智能` `基准测试`

> YourBench: Easy Custom Evaluation Sets for Everyone

# 摘要

> 有效评估大型语言模型（LLMs）仍然是一个关键瓶颈。传统静态基准测试饱受饱和和污染的困扰，而人工评估既昂贵又耗时，这阻碍了及时或领域特定的评估，这对于实际应用至关重要。我们推出YourBench，一个新颖的开源框架，它通过直接基于用户提供的文档，动态自动生成可靠、最新且领域定制的基准测试，从而克服了这些限制。无需人工标注，成本低廉。我们仅使用少量源文本成功复制了7个多样化的MMLU子集，总推理成本不到15美元，同时完美保留了原始基准中观察到的模型性能排名（Spearman Rho = 1）。为了确保YourBench生成的数据基于提供的输入而非依赖模型的后验参数知识，我们还引入了Tempora-0325，这是一个包含超过7K个多样化文档的新数据集，所有文档均独家发布于2025年3月之后。我们对来自7个主要家族的26个SoTA模型进行了全面分析，涵盖不同规模（3-671B参数），通过严格的算法检查（如引用验证）和人工评估来验证生成评估的质量。我们发布了YourBench库、Tempora-0325数据集、基于Tempora的150k+问答对，以及所有评估和推理轨迹，以支持可重复研究，并赋能社区按需生成定制基准，从而推动更相关和可信的LLM评估。

> Evaluating large language models (LLMs) effectively remains a critical bottleneck, as traditional static benchmarks suffer from saturation and contamination, while human evaluations are costly and slow. This hinders timely or domain-specific assessment, crucial for real-world applications. We introduce YourBench, a novel, open-source framework that addresses these limitations by enabling dynamic, automated generation of reliable, up-to-date, and domain-tailored benchmarks cheaply and without manual annotation, directly from user-provided documents. We demonstrate its efficacy by replicating 7 diverse MMLU subsets using minimal source text, achieving this for under 15 USD in total inference costs while perfectly preserving the relative model performance rankings (Spearman Rho = 1) observed on the original benchmark. To ensure that YourBench generates data grounded in provided input instead of relying on posterior parametric knowledge in models, we also introduce Tempora-0325, a novel dataset of over 7K diverse documents, published exclusively after March 2025. Our comprehensive analysis spans 26 SoTA models from 7 major families across varying scales (3-671B parameters) to validate the quality of generated evaluations through rigorous algorithmic checks (e.g., citation grounding) and human assessments. We release the YourBench library, the Tempora-0325 dataset, 150k+ question answer pairs based on Tempora and all evaluation and inference traces to facilitate reproducible research and empower the community to generate bespoke benchmarks on demand, fostering more relevant and trustworthy LLM evaluation.

[Arxiv](https://arxiv.org/abs/2504.01833)