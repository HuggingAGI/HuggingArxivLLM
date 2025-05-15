# 一系列大型语言模型在理解谜题陈述方面，其能力可与人类匹敌。

发布时间：2025年05月13日

`LLM理论` `人工智能`

> A suite of LMs comprehend puzzle statements as well as humans

# 摘要

> 近期研究声称大型语言模型（LMs）在理解复杂度较低的英文陈述方面逊色于人类（Dentella et al., 2024）。在此，我们重新审视了这些研究发现，提出人类的表现可能被高估，而模型的能力却被低估。我们采用相同的测试材料，开展了一项预注册研究，比较了人类在两种条件下的反应：一种允许反复阅读（复现原始研究），另一种限制反复阅读（更自然的理解测试）。限制反复阅读时，人类准确率显著下降至73%，低于Falcon-180B-Chat（76%）和GPT-4（81%）。较新的GPT-o1模型则实现了完美准确率。研究结果进一步显示，无论是人类还是模型，在面对涉及潜在互惠行为（如接吻）的查询时，都面临了不均衡的挑战，这表明两者共享语用敏感性，而非模型特有的缺陷。通过Llama-2-70B的对数概率分析、模型开放回答的重新编码以及对其他句子的语法评分，我们发现模型的表现被系统性低估。我们发现，GPT-4o可以根据提示框架与新手或专家的语法判断保持一致。这些发现凸显了在LLM评估中需要更加谨慎的实验设计和编码实践，并挑战了当前模型在语言理解上本质上弱于人类的假设。

> Recent claims suggest that large language models (LMs) underperform humans in comprehending minimally complex English statements (Dentella et al., 2024). Here, we revisit those findings and argue that human performance was overestimated, while LLM abilities were underestimated. Using the same stimuli, we report a preregistered study comparing human responses in two conditions: one allowed rereading (replicating the original study), and one that restricted rereading (a more naturalistic comprehension test). Human accuracy dropped significantly when rereading was restricted (73%), falling below that of Falcon-180B-Chat (76%) and GPT-4 (81%). The newer GPT-o1 model achieves perfect accuracy. Results further show that both humans and models are disproportionately challenged by queries involving potentially reciprocal actions (e.g., kissing), suggesting shared pragmatic sensitivities rather than model-specific deficits. Additional analyses using Llama-2-70B log probabilities, a recoding of open-ended model responses, and grammaticality ratings of other sentences reveal systematic underestimation of model performance. We find that GPT-4o can align with either naive or expert grammaticality judgments, depending on prompt framing. These findings underscore the need for more careful experimental design and coding practices in LLM evaluation, and they challenge the assumption that current models are inherently weaker than humans at language comprehension.

[Arxiv](https://arxiv.org/abs/2505.08996)