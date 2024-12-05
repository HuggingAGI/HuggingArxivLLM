# 单细胞组学竞技场：关于利用单细胞数据对大型语言模型进行细胞类型注释的基准研究

发布时间：2024年12月03日

`LLM应用` `单细胞测序` `基因组学`

> Single-Cell Omics Arena: A Benchmark Study for Large Language Models on Cell Type Annotation Using Single-Cell Data

# 摘要

> 过去十年，单细胞测序领域的变革实现了对数千个单细胞的多种模式进行同步分子分析，让科学家得以探究复杂组织的多样功能，揭示潜在疾病机制。在所有分析步骤里，将单个细胞归为特定类型对于理解细胞异质性至关重要。然而，此过程通常劳动强度大，且需要丰富的专家知识。大型语言模型（LLMs）的最新进展显示，其能够高效处理和整合海量文本，自动提取诸如标记基因等基本生物学知识，有望推动细胞类型注释更高效、更自动化。为全面评估现代指令调整的 LLMs 在细胞类型识别过程自动化方面的能力，我们引入了 SOAR，这是针对单细胞基因组学中细胞类型注释任务的 LLMs 综合基准研究。具体而言，我们评估了 8 个指令调整的 LLMs 在 11 个数据集上的表现，涵盖多种细胞类型和物种。我们的研究探索了 LLMs 在单细胞 RNA 测序（scRNA-seq）数据中准确分类和注释细胞类型的潜力，同时通过跨模态翻译将其应用拓展至多组学数据。此外，我们还评估了思维链（CoT）提示技术在注释过程中生成详细生物学见解的有效性。结果表明，LLMs 能够为单细胞数据提供有力的解释，无需额外微调，促进了基因组学研究中细胞类型注释的自动化。

> Over the past decade, the revolution in single-cell sequencing has enabled the simultaneous molecular profiling of various modalities across thousands of individual cells, allowing scientists to investigate the diverse functions of complex tissues and uncover underlying disease mechanisms. Among all the analytical steps, assigning individual cells to specific types is fundamental for understanding cellular heterogeneity. However, this process is usually labor-intensive and requires extensive expert knowledge. Recent advances in large language models (LLMs) have demonstrated their ability to efficiently process and synthesize vast corpora of text to automatically extract essential biological knowledge, such as marker genes, potentially promoting more efficient and automated cell type annotations. To thoroughly evaluate the capability of modern instruction-tuned LLMs in automating the cell type identification process, we introduce SOAR, a comprehensive benchmarking study of LLMs for cell type annotation tasks in single-cell genomics. Specifically, we assess the performance of 8 instruction-tuned LLMs across 11 datasets, spanning multiple cell types and species. Our study explores the potential of LLMs to accurately classify and annotate cell types in single-cell RNA sequencing (scRNA-seq) data, while extending their application to multiomics data through cross-modality translation. Additionally, we evaluate the effectiveness of chain-of-thought (CoT) prompting techniques in generating detailed biological insights during the annotation process. The results demonstrate that LLMs can provide robust interpretations of single-cell data without requiring additional fine-tuning, advancing the automation of cell type annotation in genomics research.

[Arxiv](https://arxiv.org/abs/2412.02915)