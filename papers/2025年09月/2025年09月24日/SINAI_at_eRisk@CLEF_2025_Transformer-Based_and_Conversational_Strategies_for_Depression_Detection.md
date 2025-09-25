# # SINAI at eRisk@CLEF 2025：基于Transformer的抑郁症检测对话策略

发布时间：2025年09月24日

`LLM应用` `医疗健康`

> SINAI at eRisk@CLEF 2025: Transformer-Based and Conversational Strategies for Depression Detection

# 摘要

> 本文介绍了SINAI-UJA团队参与eRisk@CLEF 2025实验室的研究工作，重点完成了两项任务：（i）任务2：抑郁症情境化早期检测；（ii）试点任务：基于LLMs的对话式抑郁症检测。针对任务2，我们将全面的预处理流程与RoBERTa Base、MentalRoBERTA Large等多个基于Transformer的模型相结合，以捕捉多用户对话的情境关联性与时序特性。针对试点任务，我们设计了一套对话策略，用于与LLM驱动的虚拟角色交互，核心目标是在有限对话轮次内最大化信息获取。在任务2中，基于F1分数，我们的系统在12支参赛队伍中排名第8。但深入分析表明，我们的模型在早期预测速度上表现突出，而这在实际应用部署中至关重要。这一结果凸显了早期检测与分类准确率之间的权衡关系，为未来研究中协同优化二者提供了方向。在试点任务中，我们在5支队伍中斩获第1名，并在DCHR、ADODL及ASHR所有评估指标上均取得最佳综合表现。该任务的成功证明，结构化对话设计与强大的语言模型相结合具有显著效果，同时也进一步验证了在敏感的心理健康评估场景中部署LLMs的可行性。

> This paper describes the participation of the SINAI-UJA team in the eRisk@CLEF 2025 lab. Specifically, we addressed two of the proposed tasks: (i) Task 2: Contextualized Early Detection of Depression, and (ii) Pilot Task: Conversational Depression Detection via LLMs. Our approach for Task 2 combines an extensive preprocessing pipeline with the use of several transformer-based models, such as RoBERTa Base or MentalRoBERTA Large, to capture the contextual and sequential nature of multi-user conversations. For the Pilot Task, we designed a set of conversational strategies to interact with LLM-powered personas, focusing on maximizing information gain within a limited number of dialogue turns. In Task 2, our system ranked 8th out of 12 participating teams based on F1 score. However, a deeper analysis revealed that our models were among the fastest in issuing early predictions, which is a critical factor in real-world deployment scenarios. This highlights the trade-off between early detection and classification accuracy, suggesting potential avenues for optimizing both jointly in future work. In the Pilot Task, we achieved 1st place out of 5 teams, obtaining the best overall performance across all evaluation metrics: DCHR, ADODL and ASHR. Our success in this task demonstrates the effectiveness of structured conversational design when combined with powerful language models, reinforcing the feasibility of deploying LLMs in sensitive mental health assessment contexts.

[Arxiv](https://arxiv.org/abs/2509.19861)