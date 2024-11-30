# 针对决策型基础模型中的幻觉检测问题，本研究提出了一种灵活的定义，并对该领域的最新进展进行了全面回顾与总结。

发布时间：2024年03月25日

`Agent` `自主系统` `机器人技术`

> Hallucination Detection in Foundation Models for Decision-Making: A Flexible Definition and Review of the State of the Art

# 摘要

> 自主系统正迅速普及，涉及制造业、农业机器人、医疗助理乃至娱乐产业等多个领域。现有的自主系统大多采用模块化组件进行决策、规划和控制，而这些组件的设计或是基于人工，或是基于学习。尽管现行方法在特定设计情境下的表现不俗，但在测试阶段无可避免出现的罕见、未预料场景中，其表现却往往不尽人意。随着大量跨领域大数据训练而成的基础模型的崛起，研究者开始相信这些模型可能填补了现有规划方法在常识推理上的空白。他们认为，如同人类应对突发状况一样，这种常识推理将有助于弥合算法开发与实际部署到未知场景之间的差距。如今，大规模语言模型已涉足机器人及自主系统领域，研究人员争先恐后地展示其在实际应用中的潜力。虽然这种方法在实践中展现出巨大希望，但基础模型存在的问题是会“臆想”出看似合理实则不佳的决策。因此，我们主张应适时后退一步，同步研发能够量化模型决策确定性，并能在其产生“臆想”时予以识别的系统。在此项研究中，我们将探讨基础模型在决策任务中的现有关键应用案例，给出关于“臆想”的通用定义并举例说明，聚焦于决策问题的既有“臆想”检测与缓解策略，并就这一激动人心的领域发掘更多研究空间。

> Autonomous systems are soon to be ubiquitous, from manufacturing autonomy to agricultural field robots, and from health care assistants to the entertainment industry. The majority of these systems are developed with modular sub-components for decision-making, planning, and control that may be hand-engineered or learning-based. While these existing approaches have been shown to perform well under the situations they were specifically designed for, they can perform especially poorly in rare, out-of-distribution scenarios that will undoubtedly arise at test-time. The rise of foundation models trained on multiple tasks with impressively large datasets from a variety of fields has led researchers to believe that these models may provide common sense reasoning that existing planners are missing. Researchers posit that this common sense reasoning will bridge the gap between algorithm development and deployment to out-of-distribution tasks, like how humans adapt to unexpected scenarios. Large language models have already penetrated the robotics and autonomous systems domains as researchers are scrambling to showcase their potential use cases in deployment. While this application direction is very promising empirically, foundation models are known to hallucinate and generate decisions that may sound reasonable, but are in fact poor. We argue there is a need to step back and simultaneously design systems that can quantify the certainty of a model's decision, and detect when it may be hallucinating. In this work, we discuss the current use cases of foundation models for decision-making tasks, provide a general definition for hallucinations with examples, discuss existing approaches to hallucination detection and mitigation with a focus on decision problems, and explore areas for further research in this exciting field.

[Arxiv](https://arxiv.org/abs/2403.16527)