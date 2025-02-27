# FilterRAG：一种零样本知情的检索增强生成方法，用于缓解视觉问答中的幻觉问题。

发布时间：2025年02月25日

`RAG` `视觉问答` `计算机视觉`

> FilterRAG: Zero-Shot Informed Retrieval-Augmented Generation to Mitigate Hallucinations in VQA

# 摘要

> 视觉问答要求模型整合视觉与文本理解生成准确答案。然而，VQA模型在知识驱动和分布外场景中仍存在幻觉问题，容易生成看似合理但错误的答案。为此，我们提出了FilterRAG框架，它结合BLIP-VQA与检索增强生成技术，能够从维基百科和DBpedia等外部知识源中获取依据。在OK-VQA数据集上，FilterRAG实现了36.5%的准确率，证明了其在减少幻觉和提升领域内及分布外场景鲁棒性方面的有效性。这些发现凸显了FilterRAG在改善视觉问答系统以适应实际部署中的潜力。

> Visual Question Answering requires models to generate accurate answers by integrating visual and textual understanding. However, VQA models still struggle with hallucinations, producing convincing but incorrect answers, particularly in knowledge-driven and Out-of-Distribution scenarios. We introduce FilterRAG, a retrieval-augmented framework that combines BLIP-VQA with Retrieval-Augmented Generation to ground answers in external knowledge sources like Wikipedia and DBpedia. FilterRAG achieves 36.5% accuracy on the OK-VQA dataset, demonstrating its effectiveness in reducing hallucinations and improving robustness in both in-domain and Out-of-Distribution settings. These findings highlight the potential of FilterRAG to improve Visual Question Answering systems for real-world deployment.

[Arxiv](https://arxiv.org/abs/2502.18536)