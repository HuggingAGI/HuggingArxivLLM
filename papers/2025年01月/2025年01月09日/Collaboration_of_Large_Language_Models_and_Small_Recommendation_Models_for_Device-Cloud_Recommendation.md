# 大型语言模型与小型推荐模型的协同，助力设备-云推荐

发布时间：2025年01月09日

`LLM应用

理由：这篇论文主要讨论了大型语言模型（LLMs）在推荐系统中的应用，并提出了一个设备-云LLM-SRM协同推荐框架（LSC4Rec）。论文的核心内容是如何将LLMs与小型推荐模型（SRMs）结合，以解决LLMs在实时用户偏好捕捉方面的不足。虽然论文涉及了LLMs的理论和实现，但其主要关注点是如何在实际应用中优化推荐系统的性能，因此应归类为“LLM应用”。` `推荐系统` `云计算`

> Collaboration of Large Language Models and Small Recommendation Models for Device-Cloud Recommendation

# 摘要

> # 摘要
大型语言模型（LLMs）在推荐系统中的应用（LLM4Rec）是一个极具前景的研究方向，已在该领域展现出卓越性能。然而，其无法捕捉实时用户偏好的问题极大地限制了LLM4Rec的实际应用，原因在于：（i）LLMs的训练和推理成本高昂，难以频繁进行；（ii）LLMs难以访问实时数据（其庞大的参数量阻碍了在设备上的部署）。幸运的是，小型推荐模型（SRMs）能够有效弥补LLM4Rec的这些不足，它们以极少的资源消耗实现频繁的训练和推理，并能方便地访问设备上的实时数据。
  鉴于此，我们在设备-云协作的背景下设计了设备-云LLM-SRM协同推荐框架（LSC4Rec）。LSC4Rec旨在整合LLMs和SRMs的优势，以及云计算和边缘计算的好处，实现互补协同。我们通过设计三种策略来增强LSC4Rec的实用性：协同训练、协同推理和智能请求。在训练过程中，LLM生成候选列表以增强SRM在协同场景中的排序能力，并使SRM能够自适应更新以捕捉实时用户兴趣。在推理过程中，LLM和SRM分别部署在云端和设备上。LLM基于用户行为生成候选列表和初始排序结果，SRM根据候选列表进行重新排序，最终结果整合了LLM和SRM的评分。设备通过比较LLM和SRM排序列表的一致性来决定是否需要新的候选列表。我们全面而广泛的实验分析验证了LSC4Rec中每种策略的有效性。

> Large Language Models (LLMs) for Recommendation (LLM4Rec) is a promising research direction that has demonstrated exceptional performance in this field. However, its inability to capture real-time user preferences greatly limits the practical application of LLM4Rec because (i) LLMs are costly to train and infer frequently, and (ii) LLMs struggle to access real-time data (its large number of parameters poses an obstacle to deployment on devices). Fortunately, small recommendation models (SRMs) can effectively supplement these shortcomings of LLM4Rec diagrams by consuming minimal resources for frequent training and inference, and by conveniently accessing real-time data on devices.
  In light of this, we designed the Device-Cloud LLM-SRM Collaborative Recommendation Framework (LSC4Rec) under a device-cloud collaboration setting. LSC4Rec aims to integrate the advantages of both LLMs and SRMs, as well as the benefits of cloud and edge computing, achieving a complementary synergy. We enhance the practicability of LSC4Rec by designing three strategies: collaborative training, collaborative inference, and intelligent request. During training, LLM generates candidate lists to enhance the ranking ability of SRM in collaborative scenarios and enables SRM to update adaptively to capture real-time user interests. During inference, LLM and SRM are deployed on the cloud and on the device, respectively. LLM generates candidate lists and initial ranking results based on user behavior, and SRM get reranking results based on the candidate list, with final results integrating both LLM's and SRM's scores. The device determines whether a new candidate list is needed by comparing the consistency of the LLM's and SRM's sorted lists. Our comprehensive and extensive experimental analysis validates the effectiveness of each strategy in LSC4Rec.

[Arxiv](https://arxiv.org/abs/2501.05647)