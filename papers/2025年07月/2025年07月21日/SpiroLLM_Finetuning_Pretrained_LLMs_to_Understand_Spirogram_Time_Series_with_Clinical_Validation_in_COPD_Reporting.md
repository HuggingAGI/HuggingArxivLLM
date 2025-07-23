# SpiroLLM：优化预训练语言模型，深入理解肺功能图时间序列，实现COPD报告的临床验证。

发布时间：2025年07月21日

`LLM应用` `人工智能`

> SpiroLLM: Finetuning Pretrained LLMs to Understand Spirogram Time Series with Clinical Validation in COPD Reporting

# 摘要

> 慢性阻塞性肺病（COPD）是一种主要的慢性呼吸系统疾病，其特点是持续的气流受限，是全球致残和致死的主要原因之一。呼吸流量图时间序列在肺功能测试（PFTs）中常规采集，对于早期发现呼吸系统疾病和随时间监测肺功能至关重要。然而，目前大多数用于COPD诊断的AI模型仅限于输出分类结果，而无法提供诊断过程的依据，而现有的大型语言模型（LLMs）尚无法理解流量图，这严重限制了它们在临床中的信任度和应用。为解决这一挑战，我们利用来自英国生物样本库（UKB）的234,028名个体的队列，提出了SpiroLLM——首个能够理解流量图的多模态大型语言模型。该模型通过SpiroEncoder从呼吸曲线上提取形态特征，并使用SpiroProjector在统一的潜在空间中将其与肺功能测试的数值结果对齐，最终赋予大型语言模型生成全面诊断报告的能力。实验结果证实，SpiroLLM的诊断AUC达到0.8980（95%置信区间：0.8820-0.9132）。在鲁棒性测试中，SpiroLLM在核心数据缺失的情况下，仍保持100%的有效响应率，远超仅基于文本模型的13.4%，充分展现了其多模态设计的优越性。这项研究充分证明了将生理信号与大型语言模型深度融合的巨大潜力，为新一代可解释且可靠的临床决策支持工具奠定了新的范式。
    

> Chronic Obstructive Pulmonary Disease (COPD), a major chronic respiratory disease with persistent airflow limitation, is a leading global cause of disability and mortality. Respiratory spirogram time series, routinely collected during pulmonary function tests (PFTs), play a critical role in the early detection of repsiratory diseases and in monitoring lung function over time. However, most current AI models for COPD diagnosis are limited to outputting classification results without providing a rationale for their diagnostic process, while current Large Language Models (LLMs) cannot understand spirograms yet, which severely limits their clinical trust and adoption. To tackle this challenge, we leverage a cohort of 234,028 individuals from the UK Biobank (UKB) to propose SpiroLLM, the first multimodal large language model that can understand spirogram. The model extracts morphological features from respiratory curves via a SpiroEncoder and aligns them with PFT numerical values in a unified latent space using a SpiroProjector, ultimately empowering a large language model to generate a comprehensive diagnostic report. Experimental results confirm that SpiroLLM achieved a diagnostic AUROC of 0.8980 (95% CI: 0.8820-0.9132). In a robustness test with missing core data, it maintained a 100% valid response rate, far surpassing the 13.4% of a text-only model and showcasing the superiority of its multimodal design. This work demonstrates the substantial potential of deeply fusing physiological signals with large language models, establishing a new paradigm for the next generation of interpretable and reliable clinical decision support tools.

[Arxiv](https://arxiv.org/abs/2507.16145)