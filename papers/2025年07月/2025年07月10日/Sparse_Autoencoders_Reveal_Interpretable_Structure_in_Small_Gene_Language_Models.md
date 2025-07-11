# 稀疏自编码器揭示小型基因语言模型中的可解释结构

发布时间：2025年07月10日

`LLM理论` `基因组学`

> Sparse Autoencoders Reveal Interpretable Structure in Small Gene Language Models

# 摘要

> 稀疏自动编码器（SAEs）作为一种强大的工具，近年来在解释大型语言模型（LLMs）的内部表示中发挥了重要作用，揭示了具有语义意义的潜在特征。在生物领域，这一技术也展现出了独特价值：通过将SAEs应用于蛋白质语言模型，研究人员成功揭示了与蛋白质结构和功能相关的特征。近期，这一方法进一步拓展到了以基因组学为重点的模型，如Evo 2，成功识别出基因序列中的可解释特征。然而，目前尚不清楚SAEs是否能够从小型基因语言模型中提取出有意义的表示，因为这些模型通常参数较少、表达能力有限。为解决这一问题，我们提出将SAEs应用于小型基因语言模型的激活。实验表明，即使是小型模型，也能编码与生物相关的基因组特征，例如转录因子结合基序，而SAEs能够有效地揭示这些特征。我们的研究结果表明，紧凑的基因语言模型同样能够学习到结构化的基因组表示，而SAEs为解释不同规模的基因模型提供了一种可扩展的方法。

> Sparse autoencoders (SAEs) have recently emerged as a powerful tool for interpreting the internal representations of large language models (LLMs), revealing latent latent features with semantical meaning. This interpretability has also proven valuable in biological domains: applying SAEs to protein language models uncovered meaningful features related to protein structure and function. More recently, SAEs have been used to analyze genomics-focused models such as Evo 2, identifying interpretable features in gene sequences. However, it remains unclear whether SAEs can extract meaningful representations from small gene language models, which have fewer parameters and potentially less expressive capacity. To address it, we propose applying SAEs to the activations of a small gene language model. We demonstrate that even small-scale models encode biologically relevant genomic features, such as transcription factor binding motifs, that SAEs can effectively uncover. Our findings suggest that compact gene language models are capable of learning structured genomic representations, and that SAEs offer a scalable approach for interpreting gene models across various model sizes.

[Arxiv](https://arxiv.org/abs/2507.07486)