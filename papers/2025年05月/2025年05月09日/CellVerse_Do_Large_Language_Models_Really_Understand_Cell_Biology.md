# CellVerse：大型语言模型真的理解细胞生物学吗？

发布时间：2025年05月09日

`LLM应用` `细胞生物学` `药物开发`

> CellVerse: Do Large Language Models Really Understand Cell Biology?

# 摘要

> 近期研究显示，将单细胞数据建模为自然语言并利用大型语言模型（LLMs）解析细胞生物学具有可行性，但LLMs在语言驱动的单细胞分析任务中的表现尚未得到全面评估。为应对这一挑战，我们推出CellVerse——一个统一的以语言为中心的问题回答基准测试平台。它整合了四种单细胞多组学数据，并覆盖了三个层次的分析任务：细胞类型注释（细胞水平）、药物反应预测（药物水平）和基因扰动分析（基因水平）。我们对14个开源和闭源的LLMs（参数规模从160M到671B）在CellVerse上的表现进行了系统评估。实验结果令人瞩目：（1）现有专用模型（如C2S-Pythia）在CellVerse的全部子任务中表现不佳，而通用模型（如Qwen、Llama、GPT和DeepSeek系列）在细胞生物学领域展现了初步的理解能力。（2）当前LLMs的表现未达预期，提升空间显著。尤其在备受关注的药物反应预测任务中，所有评估模型的表现均未显著优于随机猜测。CellVerse首次大规模实证表明，将LLMs应用于细胞生物学仍面临诸多挑战。通过推出CellVerse，我们为利用自然语言推进细胞生物学研究奠定了基础，并期待这一范式能为下一代单细胞分析注入新动力。

> Recent studies have demonstrated the feasibility of modeling single-cell data as natural languages and the potential of leveraging powerful large language models (LLMs) for understanding cell biology. However, a comprehensive evaluation of LLMs' performance on language-driven single-cell analysis tasks still remains unexplored. Motivated by this challenge, we introduce CellVerse, a unified language-centric question-answering benchmark that integrates four types of single-cell multi-omics data and encompasses three hierarchical levels of single-cell analysis tasks: cell type annotation (cell-level), drug response prediction (drug-level), and perturbation analysis (gene-level). Going beyond this, we systematically evaluate the performance across 14 open-source and closed-source LLMs ranging from 160M to 671B on CellVerse. Remarkably, the experimental results reveal: (1) Existing specialist models (C2S-Pythia) fail to make reasonable decisions across all sub-tasks within CellVerse, while generalist models such as Qwen, Llama, GPT, and DeepSeek family models exhibit preliminary understanding capabilities within the realm of cell biology. (2) The performance of current LLMs falls short of expectations and has substantial room for improvement. Notably, in the widely studied drug response prediction task, none of the evaluated LLMs demonstrate significant performance improvement over random guessing. CellVerse offers the first large-scale empirical demonstration that significant challenges still remain in applying LLMs to cell biology. By introducing CellVerse, we lay the foundation for advancing cell biology through natural languages and hope this paradigm could facilitate next-generation single-cell analysis.

[Arxiv](https://arxiv.org/abs/2505.07865)