# 基于本体的概念蒸馏：放射学报告检索与标注

发布时间：2025年08月27日

`RAG` `医疗健康`

> Ontology-Based Concept Distillation for Radiology Report Retrieval and Labeling

# 摘要

> 基于放射学报告的检索增强学习为提升长尾医学影像任务（如胸部X光片罕见病检测）性能开辟了新方向。然而现有方法多依赖CLIP或CXR-BERT等模型生成的高维文本嵌入进行比较，这类方法不仅解释难度大、计算成本高，还与医学知识的结构化特性脱节。为此，我们提出了一种全新的本体驱动方法，通过统一医学语言系统（UMLS）中的临床核心概念来对比放射学报告文本。我们基于RadGraph-XL和SapBERT构建了增强型处理流水线，从自由文本报告中提取标准化医学实体，并将其关联到UMLS概念（CUIs），进而形成每个报告的透明、可解释的集合型表示。我们还基于修正加权的特沃斯基指数定义了任务自适应相似度度量，该度量能有效捕捉医学实体间的同义、否定及层级关系，实现了报告间高效且语义准确的相似度比较。在MIMIC-CXR数据集的放射影像分类任务中，我们的方法性能超越了现有基于嵌入的检索技术，尤其在长尾场景下优势显著。此外，我们利用该流水线为MIMIC-CXR生成了基于本体的疾病标签，为下游学习任务提供了宝贵的新资源。我们的研究为临床AI系统提供了更具可解释性、可靠性和任务针对性的检索策略，尤其适用于需重点考虑可解释性和领域知识整合的场景。代码开源地址：https://github.com/Felix-012/ontology-concept-distillation

> Retrieval-augmented learning based on radiology reports has emerged as a promising direction to improve performance on long-tail medical imaging tasks, such as rare disease detection in chest X-rays. Most existing methods rely on comparing high-dimensional text embeddings from models like CLIP or CXR-BERT, which are often difficult to interpret, computationally expensive, and not well-aligned with the structured nature of medical knowledge. We propose a novel, ontology-driven alternative for comparing radiology report texts based on clinically grounded concepts from the Unified Medical Language System (UMLS). Our method extracts standardised medical entities from free-text reports using an enhanced pipeline built on RadGraph-XL and SapBERT. These entities are linked to UMLS concepts (CUIs), enabling a transparent, interpretable set-based representation of each report. We then define a task-adaptive similarity measure based on a modified and weighted version of the Tversky Index that accounts for synonymy, negation, and hierarchical relationships between medical entities. This allows efficient and semantically meaningful similarity comparisons between reports. We demonstrate that our approach outperforms state-of-the-art embedding-based retrieval methods in a radiograph classification task on MIMIC-CXR, particularly in long-tail settings. Additionally, we use our pipeline to generate ontology-backed disease labels for MIMIC-CXR, offering a valuable new resource for downstream learning tasks. Our work provides more explainable, reliable, and task-specific retrieval strategies in clinical AI systems, especially when interpretability and domain knowledge integration are essential. Our code is available at https://github.com/Felix-012/ontology-concept-distillation

[Arxiv](https://arxiv.org/abs/2508.19915)