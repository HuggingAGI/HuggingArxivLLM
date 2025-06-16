# 谁在聚光灯下？——隐藏的偏见正在削弱多模态检索增强生成

发布时间：2025年05月30日

`RAG` `知识密集型任务` `多模态`

> Who is in the Spotlight: The Hidden Bias Undermining Multimodal Retrieval-Augmented Generation

# 摘要

> 多模态检索增强生成（RAG）系统在知识密集型和开放领域任务中发挥着关键作用。然而，随着检索复杂性的增加，现有RAG模型对证据呈现顺序的敏感性问题日益凸显，尤其是在处理大量检索结果或高模态多样性时，往往会导致性能波动和推理偏差。针对这一问题，我们进行了首个关于多模态RAG系统位置偏见的全面研究。通过在仅文本、仅图像和混合模态任务上的控制实验，我们发现证据位置与系统性能之间呈现出一致的U型曲线关系。为了量化这种偏见，我们提出了位置敏感性指数（【数学公式】），并开发了一个可视化框架，用于追踪解码器各层中的注意力分配模式。研究结果表明，多模态交互会显著加剧位置偏见，且这种偏见会随着检索范围的增加而对数增长。这些发现不仅为RAG中的位置感知分析提供了理论和实证支持，还强调了通过优化证据排序或采用去偏策略来构建更加可靠和公平的生成系统的必要性。

> Multimodal Retrieval-Augmented Generation (RAG) systems have become essential in knowledge-intensive and open-domain tasks. As retrieval complexity increases, ensuring the robustness of these systems is critical. However, current RAG models are highly sensitive to the order in which evidence is presented, often resulting in unstable performance and biased reasoning, particularly as the number of retrieved items or modality diversity grows. This raises a central question: How does the position of retrieved evidence affect multimodal RAG performance? To answer this, we present the first comprehensive study of position bias in multimodal RAG systems. Through controlled experiments across text-only, image-only, and mixed-modality tasks, we observe a consistent U-shaped accuracy curve with respect to evidence position. To quantify this bias, we introduce the Position Sensitivity Index ($PSI_p$) and develop a visualization framework to trace attention allocation patterns across decoder layers. Our results reveal that multimodal interactions intensify position bias compared to unimodal settings, and that this bias increases logarithmically with retrieval range. These findings offer both theoretical and empirical foundations for position-aware analysis in RAG, highlighting the need for evidence reordering or debiasing strategies to build more reliable and equitable generation systems.

[Arxiv](https://arxiv.org/abs/2506.11063)