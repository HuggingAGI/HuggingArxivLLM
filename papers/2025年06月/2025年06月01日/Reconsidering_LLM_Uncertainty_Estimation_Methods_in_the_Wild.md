# 重新审视大型语言模型不确定性估计的实际应用方法

发布时间：2025年06月01日

`LLM应用` `人工智能` `不确定性估计`

> Reconsidering LLM Uncertainty Estimation Methods in the Wild

# 摘要

> 大型语言模型（LLM）的不确定性估计（UE）方法已成为检测幻觉现象的重要工具。尽管提出了众多UE方法，但现有研究多在孤立的短文本问答场景中使用AUROC或PRR等阈值独立指标进行评估。然而，将UE方法应用于实际场景面临多重挑战。本文系统性地探讨了在实际场景下部署UE方法的四个关键方面：（1）UE方法对决策阈值选择的敏感性，（2）面对打字错误、对抗性提示及先前聊天记录等查询变换时的鲁棒性，（3）其在长文本生成中的适用性，以及（4）处理单个查询时多个UE得分的策略。我们在19种UE方法上的评估发现，当校准数据集出现分布偏移时，大多数方法对阈值选择高度敏感。尽管这些方法通常能抵御先前聊天记录和打字错误的干扰，但对对抗性提示却表现出显著的脆弱性。此外，虽然现有UE方法可以通过多种策略适应长文本生成，但仍有较大的改进空间。最后，我们在测试时对多个UE得分进行集成，能够带来显著的性能提升，这凸显了其作为实用改进策略的潜力。代码可在以下地址获取：https://github.com/duygunuryldz/uncertainty_in_the_wild。


> Large Language Model (LLM) Uncertainty Estimation (UE) methods have become a crucial tool for detecting hallucinations in recent years. While numerous UE methods have been proposed, most existing studies evaluate them in isolated short-form QA settings using threshold-independent metrics such as AUROC or PRR. However, real-world deployment of UE methods introduces several challenges. In this work, we systematically examine four key aspects of deploying UE methods in practical settings. Specifically, we assess (1) the sensitivity of UE methods to decision threshold selection, (2) their robustness to query transformations such as typos, adversarial prompts, and prior chat history, (3) their applicability to long-form generation, and (4) strategies for handling multiple UE scores for a single query. Our evaluations on 19 UE methods reveal that most of them are highly sensitive to threshold selection when there is a distribution shift in the calibration dataset. While these methods generally exhibit robustness against previous chat history and typos, they are significantly vulnerable to adversarial prompts. Additionally, while existing UE methods can be adapted for long-form generation through various strategies, there remains considerable room for improvement. Lastly, ensembling multiple UE scores at test time provides a notable performance boost, which highlights its potential as a practical improvement strategy. Code is available at: https://github.com/duygunuryldz/uncertainty_in_the_wild.

[Arxiv](https://arxiv.org/abs/2506.01114)