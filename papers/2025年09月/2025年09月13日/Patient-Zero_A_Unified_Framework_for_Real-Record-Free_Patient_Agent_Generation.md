# Patient-Zero：无真实记录患者智能体生成的统一框架

发布时间：2025年09月13日

`Agent` `医疗健康`

> Patient-Zero: A Unified Framework for Real-Record-Free Patient Agent Generation

# 摘要

> 借助大型语言模型（LLMs）生成合成数据已成为多个领域的理想解决方案，尤其在医疗领域，可有效缓解数据收集难题。然而，现有研究多利用LLMs重写或补全已有医疗记录，不仅仍存在数据隐私、准确性和多样性局限，还缺乏真实患者般的互动能力。为此，我们提出无需真实医疗记录的逼真患者生成框架Patient-Zero。该框架首先设计医学对齐的多步骤生成架构，无需真实医疗数据，而是通过分层注入医疗知识构建全面的患者记录；其次，为提升虚拟患者与人类的互动能力，Patient-Zero设计动态更新机制以增强对话连贯性和表现。我们的框架在自适应对话策略与实时临床合理性验证的支持下，能够生成情境多样的患者记录，同时确保严格的医疗连贯性。实验结果显示，该模型在准确性、多样性和一致性上表现优异；经我们生成的虚拟患者训练后，现有模型在MedQA数据集上的性能显著提升。

> Synthetic data generation using large language models (LLMs) has emerged as a promising solution across various domains, particularly in medical field, to mitigate data collection challenges. However, existing studies mainly utilize LLMs to rewrite and complete existing medical records, where the limitations in data privacy, accuracy, and diversity sill exist, and additionally lack the ability to interact like real patients. To address these issues, we propose a realistic patient generation framework, Patient-Zero, which requires no real medical records. Patient-Zero first introduces a medically-aligned multi-step generation architecture, which builds comprehensive patient records through hierarchical medical knowledge injection without real medical records. Then, to optimize the virtual patient's interaction abilities with humans, Patient-Zero designs a dynamic updating mechanism to improve the consistency and conversational performance. Our framework enables the generation of contextually diverse patient records while maintaining strict medical coherence, supported by adaptive dialogue strategies and real-time clinical plausibility verification. Experimental results demonstrate that our model achieves good performance in accuracy, diversity, and consistency. After training with our generated virtual patients, existing models show significant improvements on the MedQA dataset.

[Arxiv](https://arxiv.org/abs/2509.11078)