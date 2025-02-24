# PDeepPP：基于预训练蛋白质语言的深度学习肽分类框架

发布时间：2025年02月21日

`其他` `生物技术` `生命科学`

> PDeepPP:A Deep learning framework with Pretrained Protein language for peptide classification

# 摘要

> 蛋白质翻译后修饰（PTMs）和生物活性肽（BPs）在生物学过程中发挥重要作用，具有巨大的治疗潜力。然而，传统实验方法在发现PTM位点和生物活性肽时往往耗时耗力且成本高昂。因此，基于深度学习的计算工具成为了预测PTM位点和肽段生物活性的理想选择。尽管该领域取得了进展，现有方法仍面临蛋白质序列复杂性和跨数据集高质量预测的双重挑战。

    为应对这些挑战，我们提出了一种创新的深度学习框架，将预训练的蛋白质语言模型与结合Transformer和CNN的神经网络相结合，用于肽段分类。通过整合预训练模型对蛋白质序列复杂关系的捕捉能力，并行网络的强大预测能力，我们的方法不仅提升了特征提取效率，还显著提高了预测精度。

    该框架在多个PTM位点和生物活性肽预测任务中得到应用，并通过大规模数据集增强了模型的鲁棒性。在涵盖33项任务的对比测试中，该模型在25项任务中达到了当前最优性能，超越了现有方法，展现出在不同数据集上的卓越 versatility。我们的研究结果表明，这一方法为大规模肽段发现和PTM分析提供了一个高效且可扩展的解决方案，为肽段分类和功能注释开辟了新的道路。

> Protein post-translational modifications (PTMs) and bioactive peptides (BPs) play critical roles in various biological processes and have significant therapeutic potential. However, identifying PTM sites and bioactive peptides through experimental methods is often labor-intensive, costly, and time-consuming. As a result, computational tools, particularly those based on deep learning, have become effective solutions for predicting PTM sites and peptide bioactivity. Despite progress in this field, existing methods still struggle with the complexity of protein sequences and the challenge of requiring high-quality predictions across diverse datasets.
  To address these issues, we propose a deep learning framework that integrates pretrained protein language models with a neural network combining transformer and CNN for peptide classification. By leveraging the ability of pretrained models to capture complex relationships within protein sequences, combined with the predictive power of parallel networks, our approach improves feature extraction while enhancing prediction accuracy.
  This framework was applied to multiple tasks involving PTM site and bioactive peptide prediction, utilizing large-scale datasets to enhance the model's robustness. In the comparison across 33 tasks, the model achieved state-of-the-art (SOTA) performance in 25 of them, surpassing existing methods and demonstrating its versatility across different datasets. Our results suggest that this approach provides a scalable and effective solution for large-scale peptide discovery and PTM analysis, paving the way for more efficient peptide classification and functional annotation.

[Arxiv](https://arxiv.org/abs/2502.15610)