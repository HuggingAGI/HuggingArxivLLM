# 基于多模态大型语言模型的季节性广告主动检测与校准

发布时间：2024年10月16日

`LLM应用

**理由**：这篇论文主要讨论了如何利用多模态LLMs（MLMs）进行季节性广告的主动检测与校准，并展示了在实际广告排名系统中的应用效果。虽然论文涉及广告系统和季节性检测，但其核心创新点在于利用LLMs进行季节性检测，并展示了LLMs在广告排名系统中的具体应用。因此，将其分类为LLM应用更为合适。` `推荐系统`

> Proactive Detection and Calibration of Seasonal Advertisements with Multimodal Large Language Models

# 摘要

> # 摘要
大规模广告投放系统受多种因素影响，这些因素不仅关乎用户体验，还直接影响收入。其中，季节性广告的主动检测与校准便是提升转化率和用户满意度的关键。本文聚焦于季节性广告的主动检测与校准（PDCaSA），这一课题在广告排名与推荐领域，无论是工业界还是学术界，都备受关注。我们基于大规模工业广告排名系统的实践，从多角度深入剖析了这一问题，并分享了研究成果。这些成果包括问题的明确界定、现实系统中的动机分析、评估指标，以及对现有挑战、经验教训和数据标注与机器学习建模最佳实践的深刻见解。尤为值得一提的是，我们提出了利用多模态LLMs（MLMs）进行季节性检测的创新方案，该方案在我们的内部基准测试中取得了0.97的顶级F1分数。展望未来，我们预见MLMs将在知识蒸馏、机器标注以及集成与分层季节性检测系统中发挥重要作用，为广告排名系统注入更丰富的季节性信息。

> A myriad of factors affect large scale ads delivery systems and influence both user experience and revenue. One such factor is proactive detection and calibration of seasonal advertisements to help with increasing conversion and user satisfaction. In this paper, we present Proactive Detection and Calibration of Seasonal Advertisements (PDCaSA), a research problem that is of interest for the ads ranking and recommendation community, both in the industrial setting as well as in research. Our paper provides detailed guidelines from various angles of this problem tested in, and motivated by a large-scale industrial ads ranking system. We share our findings including the clear statement of the problem and its motivation rooted in real-world systems, evaluation metrics, and sheds lights to the existing challenges, lessons learned, and best practices of data annotation and machine learning modeling to tackle this problem. Lastly, we present a conclusive solution we took during this research exploration: to detect seasonality, we leveraged Multimodal LLMs (MLMs) which on our in-house benchmark achieved 0.97 top F1 score. Based on our findings, we envision MLMs as a teacher for knowledge distillation, a machine labeler, and a part of the ensembled and tiered seasonality detection system, which can empower ads ranking systems with enriched seasonal information.

[Arxiv](https://arxiv.org/abs/2411.00780)