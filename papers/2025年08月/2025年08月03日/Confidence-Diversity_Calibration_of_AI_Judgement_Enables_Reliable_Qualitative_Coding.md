# # 摘要
AI判断的信心与多样性校准，助力可靠定性编码。

发布时间：2025年08月03日

`LLM应用`

> Confidence-Diversity Calibration of AI Judgement Enables Reliable Qualitative Coding

# 摘要

> 大型语言模型（LLMs）能够大规模实现定性编码，但在专家意见常常存在分歧的领域中，评估其输出的可靠性仍然具有挑战性。通过对八个先进LLMs在十个主题类别中的5,680个编码决策进行分析，我们发现单个模型的平均自信心度已能很好地反映模型间的共识程度（皮尔逊相关系数r=0.82）。通过引入模型多样性——以专家组投票的归一化香农熵量化——这一单一指标得以扩展为双重信号，几乎完全解释了共识程度（R²=0.979）。这种信心-多样性组合支持了一个三级工作流程：自动接受35%的片段（误判率低于5%），并将剩余部分定向送交人工审核，使人工工作量减少高达65%。在涵盖金融、医学、法律和多语言任务的六个公开数据集上的跨领域验证，进一步证实了这些改进（kappa值提升0.20-0.78）。我们的研究结果为在定性研究中校准AI判断提供了一个可推广、基于证据的标准。


> LLMs enable qualitative coding at large scale, but assessing the reliability of their output remains challenging in domains where human experts seldom agree. Analysing 5,680 coding decisions from eight state-of-the-art LLMs across ten thematic categories, we confirm that a model's mean self-confidence already tracks inter-model agreement closely (Pearson r=0.82). Adding model diversity-quantified as the normalised Shannon entropy of the panel's votes-turns this single cue into a dual signal that explains agreement almost completely (R^2=0.979). The confidence-diversity duo enables a three-tier workflow that auto-accepts 35% of segments with <5% audit-detected error and routes the remainder for targeted human review, cutting manual effort by up to 65%. Cross-domain replication on six public datasets spanning finance, medicine, law and multilingual tasks confirms these gains (kappa improvements of 0.20-0.78). Our results establish a generalisable, evidence-based criterion for calibrating AI judgement in qualitative research.

[Arxiv](https://arxiv.org/abs/2508.02029)