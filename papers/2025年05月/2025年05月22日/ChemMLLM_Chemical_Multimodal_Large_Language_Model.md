# # ChemMLLM：化学多模态大模型

发布时间：2025年05月22日

`LLM应用` `化学信息学`

> ChemMLLM: Chemical Multimodal Large Language Model

# 摘要

> 近年来，多模态大型语言模型（MLLMs）在众多应用领域取得了显著进展。然而，专注于跨模态理解和生成的化学MLLMs仍处于探索阶段。为填补这一空白，我们提出了一种统一的化学多模态大型语言模型ChemMLLM，专为分子理解和生成设计。我们设计了涵盖文本、分子SMILES字符串和图像的五个多模态任务，并整理了相应的数据集。我们对ChemMLLM在这些任务上的性能进行了全面评估，将其与多种通用领先MLLMs和化学LLMs进行了对比。实验结果表明，ChemMLLM在所有评估任务中均表现优异。例如，在分子图像优化任务中，ChemMLLM相较于最佳基准（GPT-4o）实现了118.9%的性能提升（4.27 vs 1.95属性改进）。该模型的代码已开源，可在GitHub上获取。

> Multimodal large language models (MLLMs) have made impressive progress in many applications in recent years. However, chemical MLLMs that can handle cross-modal understanding and generation remain underexplored. To fill this gap, in this paper, we propose ChemMLLM, a unified chemical multimodal large language model for molecule understanding and generation. Also, we design five multimodal tasks across text, molecular SMILES strings, and image, and curate the datasets. We benchmark ChemMLLM against a range of general leading MLLMs and Chemical LLMs on these tasks. Experimental results show that ChemMLLM achieves superior performance across all evaluated tasks. For example, in molecule image optimization task, ChemMLLM outperforms the best baseline (GPT-4o) by 118.9\% (4.27 vs 1.95 property improvement). The code is publicly available at https://github.com/bbsbz/ChemMLLM.git.

[Arxiv](https://arxiv.org/abs/2505.16326)