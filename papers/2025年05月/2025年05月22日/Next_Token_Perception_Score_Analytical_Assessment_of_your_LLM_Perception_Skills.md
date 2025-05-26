# 下一个标记感知分数：对大型语言模型感知能力的分析评估

发布时间：2025年05月22日

`LLM理论` `机器学习`

> Next Token Perception Score: Analytical Assessment of your LLM Perception Skills

# 摘要

> 自回归预训练已成为大型语言模型 (LLMs) 学习通用表示的非正式范式。然而，下游感知任务的线性探针性能显示出显著的变化，表明针对下一个令牌预测优化的特征并不始终很好地转移到下游感知任务。我们证明，通过自回归学习的表示捕获了可能位于对感知最有信息量的子空间之外的特征。为了量化自回归预训练与下游感知之间的（错位）对齐，我们引入了下一个令牌感知分数 (NTPS)——一个在线性设置下推导出的分数，用于衡量自回归和感知特征子空间的重叠。该指标可以从预训练表示和标签数据中轻松以闭合形式计算，并被证明同时上界和下界了额外的损失。经验上，我们展示了 NTPS 在 12 个多样化 NLP 数据集和 8 个预训练模型（参数范围从 2.7 亿到 80 亿）上与线性探针准确度的强相关性，证实了其作为衡量对齐程度的效用。此外，我们展示了 NTPS 在低秩适应 (LoRA) 微调后增加，尤其是在大型模型中，表明 LoRA 将表示与感知任务对齐增强了子空间重叠，从而提高了下游性能。更重要的是，我们发现 NTPS 可靠地预测了 LoRA 微调带来的额外准确度提升，从而提供了一种轻量级的预筛选工具用于 LoRA 适应。我们的结果为分析 LLM 感知技能提供了理论见解和实用工具。


> Autoregressive pretraining has become the de facto paradigm for learning general-purpose representations in large language models (LLMs). However, linear probe performance across downstream perception tasks shows substantial variability, suggesting that features optimized for next-token prediction do not consistently transfer well to downstream perception tasks. We demonstrate that representations learned via autoregression capture features that may lie outside the subspaces most informative for perception. To quantify the (mis)alignment between autoregressive pretraining and downstream perception, we introduce the Next Token Perception Score (NTPS)-a score derived under a linear setting that measures the overlap between autoregressive and perception feature subspaces. This metric can be easily computed in closed form from pretrained representations and labeled data, and is proven to both upper- and lower-bound the excess loss. Empirically, we show that NTPS correlates strongly with linear probe accuracy across 12 diverse NLP datasets and eight pretrained models ranging from 270M to 8B parameters, confirming its utility as a measure of alignment. Furthermore, we show that NTPS increases following low-rank adaptation (LoRA) fine-tuning, especially in large models, suggesting that LoRA aligning representations to perception tasks enhances subspace overlap and thus improves downstream performance. More importantly, we find that NTPS reliably predicts the additional accuracy gains attained by LoRA finetuning thereby providing a lightweight prescreening tool for LoRA adaptation. Our results offer both theoretical insights and practical tools for analytically assessing LLM perception skills.

[Arxiv](https://arxiv.org/abs/2505.17169)