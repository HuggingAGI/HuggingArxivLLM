# 重新审视大型语言模型在真实场景下的不确定性估计方法

发布时间：2025年06月01日

`LLM应用` `人工智能`

> Reconsidering LLM Uncertainty Estimation Methods in the Wild

# 摘要

> 大型语言模型（LLM）的不确定性估计（UE）方法近年来已成为检测幻觉现象不可或缺的工具。尽管提出了众多UE方法，但现有研究大多在孤立的短文本问答设置中使用AUROC或PRR等与决策阈值无关的指标进行评估。然而，UE方法在实际部署中面临诸多挑战。

在本研究中，我们系统性地考察了在实际场景下部署UE方法的四个关键方面。具体而言，我们评估了（1）UE方法对决策阈值选择的敏感性，（2）它们在面对诸如拼写错误、对抗提示和先前聊天历史等查询变换时的鲁棒性，（3）它们在长文本生成中的适用性，以及（4）处理单个查询多个UE评分的策略。

我们对19种UE方法的评估表明，大多数方法在校准数据集存在分布偏移时对阈值选择高度敏感。尽管这些方法通常能够抵御之前的聊天历史和拼写错误，但它们对对抗性提示却表现出显著的脆弱性。此外，虽然现有UE方法可以通过多种策略适应长文本生成，但仍有许多改进空间。最后，测试时对多个UE评分进行集成能够带来显著的性能提升，这凸显了其作为实用改进策略的潜力。

代码可在以下链接获取：https://github.com/duygunuryldz/uncertainty_in_the_wild。

> Large Language Model (LLM) Uncertainty Estimation (UE) methods have become a crucial tool for detecting hallucinations in recent years. While numerous UE methods have been proposed, most existing studies evaluate them in isolated short-form QA settings using threshold-independent metrics such as AUROC or PRR. However, real-world deployment of UE methods introduces several challenges. In this work, we systematically examine four key aspects of deploying UE methods in practical settings. Specifically, we assess (1) the sensitivity of UE methods to decision threshold selection, (2) their robustness to query transformations such as typos, adversarial prompts, and prior chat history, (3) their applicability to long-form generation, and (4) strategies for handling multiple UE scores for a single query. Our evaluations on 19 UE methods reveal that most of them are highly sensitive to threshold selection when there is a distribution shift in the calibration dataset. While these methods generally exhibit robustness against previous chat history and typos, they are significantly vulnerable to adversarial prompts. Additionally, while existing UE methods can be adapted for long-form generation through various strategies, there remains considerable room for improvement. Lastly, ensembling multiple UE scores at test time provides a notable performance boost, which highlights its potential as a practical improvement strategy. Code is available at: https://github.com/duygunuryldz/uncertainty_in_the_wild.

[Arxiv](https://arxiv.org/abs/2506.01114)