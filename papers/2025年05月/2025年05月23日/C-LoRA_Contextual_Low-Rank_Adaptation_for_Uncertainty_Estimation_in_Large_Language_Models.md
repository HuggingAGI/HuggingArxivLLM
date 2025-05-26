# C-LoRA：面向大型语言模型不确定性估计的上下文低秩适配方法

发布时间：2025年05月23日

`LLM理论

摘要讨论了LoRA微调方法的改进，提出了一种新的不确定性感知微调方法C-LoRA，属于模型优化和理论分析的范畴，因此归类为LLM理论。` `人工智能`

> C-LoRA: Contextual Low-Rank Adaptation for Uncertainty Estimation in Large Language Models

# 摘要

> LoRA 是一种成本效益高的 LLM 微调方案，但在数据稀缺的 few-shot 场景中常导致预测过度自信。为解决此问题，研究者将经典统计学习方法引入可扩展的不确定性感知 LoRA 微调，但这些方法忽视了输入特征对不确定性估计的影响。为此，我们提出了一种全新的不确定性感知且参数高效的微调方法——情境化低秩适配（	extbf{C-LoRA}）。通过开发针对每个输入样本的情境化轻量级 LoRA 模块，C-LoRA 能够动态调整不确定性估计。通过将数据驱动的情境融入参数后验，C-LoRA 有效缓解过拟合，实现良好校准的不确定性，并生成稳健预测。大量实验表明，C-LoRA 在不确定性量化和模型泛化方面均优于现有方法。消融研究进一步证实了情境化模块在捕捉样本特定不确定性中的关键作用。C-LoRA 为 few-shot 场景下实现稳健、不确定性感知的 LLM 微调树立了新标准。

> Low-Rank Adaptation (LoRA) offers a cost-effective solution for fine-tuning large language models (LLMs), but it often produces overconfident predictions in data-scarce few-shot settings. To address this issue, several classical statistical learning approaches have been repurposed for scalable uncertainty-aware LoRA fine-tuning. However, these approaches neglect how input characteristics affect the predictive uncertainty estimates. To address this limitation, we propose Contextual Low-Rank Adaptation (\textbf{C-LoRA}) as a novel uncertainty-aware and parameter efficient fine-tuning approach, by developing new lightweight LoRA modules contextualized to each input data sample to dynamically adapt uncertainty estimates. Incorporating data-driven contexts into the parameter posteriors, C-LoRA mitigates overfitting, achieves well-calibrated uncertainties, and yields robust predictions. Extensive experiments demonstrate that C-LoRA consistently outperforms the state-of-the-art uncertainty-aware LoRA methods in both uncertainty quantification and model generalization. Ablation studies further confirm the critical role of our contextual modules in capturing sample-specific uncertainties. C-LoRA sets a new standard for robust, uncertainty-aware LLM fine-tuning in few-shot regimes.

[Arxiv](https://arxiv.org/abs/2505.17773)