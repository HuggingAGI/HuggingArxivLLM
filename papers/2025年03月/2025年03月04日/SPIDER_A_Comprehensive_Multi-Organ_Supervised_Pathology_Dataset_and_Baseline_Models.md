# SPIDER：首个综合性的多器官监督式病理数据集及基线模型

发布时间：2025年03月04日

`LLM应用` `病理学` `计算机视觉`

> SPIDER: A Comprehensive Multi-Organ Supervised Pathology Dataset and Baseline Models

# 摘要

> 推动计算病理学中的 AI 发展需要大规模、高质量且多样化的数据集，然而现有的公开数据集往往在器官多样性、类别覆盖范围或标注质量上存在局限。为了解决这一问题，我们推出了 SPIDER（ Supervised Pathology Image-DEscription Repository），这是目前最大的公开可用的切片级别数据集，涵盖了皮肤、结直肠和胸腔等多种器官类型，并为每个器官提供了全面的类别覆盖。SPIDER 提供了经专家病理学家验证的高质量标注，并包含了周围上下文切片，通过提供空间上下文来提升分类性能。

除了数据集，我们还展示了基于 Hibou-L 基础模型作为特征提取器，并结合注意力机制分类头在 SPIDER 上训练的基线模型。这些模型在多个组织类别中实现了最先进的性能，并为未来数字病理学研究提供了强有力的基准。除了切片分类，该模型还能够快速识别重要区域，提供定量组织指标，并为多模态方法奠定了基础。

该数据集和训练好的模型均公开可用，以促进研究、可重复性和 AI 驱动的病理学发展。访问地址：https://github.com/HistAI/SPIDER

> Advancing AI in computational pathology requires large, high-quality, and diverse datasets, yet existing public datasets are often limited in organ diversity, class coverage, or annotation quality. To bridge this gap, we introduce SPIDER (Supervised Pathology Image-DEscription Repository), the largest publicly available patch-level dataset covering multiple organ types, including Skin, Colorectal, and Thorax, with comprehensive class coverage for each organ. SPIDER provides high-quality annotations verified by expert pathologists and includes surrounding context patches, which enhance classification performance by providing spatial context.
  Alongside the dataset, we present baseline models trained on SPIDER using the Hibou-L foundation model as a feature extractor combined with an attention-based classification head. The models achieve state-of-the-art performance across multiple tissue categories and serve as strong benchmarks for future digital pathology research. Beyond patch classification, the model enables rapid identification of significant areas, quantitative tissue metrics, and establishes a foundation for multimodal approaches.
  Both the dataset and trained models are publicly available to advance research, reproducibility, and AI-driven pathology development. Access them at: https://github.com/HistAI/SPIDER

[Arxiv](https://arxiv.org/abs/2503.02876)