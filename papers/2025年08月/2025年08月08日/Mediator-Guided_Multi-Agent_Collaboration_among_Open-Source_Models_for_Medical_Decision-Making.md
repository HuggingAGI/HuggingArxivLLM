# 基于中介引导的开源模型间多智能体协作用于医疗决策

发布时间：2025年08月08日

`Agent` `多模态`

> Mediator-Guided Multi-Agent Collaboration among Open-Source Models for Medical Decision-Making

# 摘要

> 复杂医疗决策涉及多学科临床医生的协作。设计AI多智能体系统能够加速和提升人类级别的临床决策能力。现有研究主要聚焦于纯语言任务的多智能体系统，但将其扩展到多模态场景仍具挑战。简单地将多种视觉语言模型（VLMs）结合使用，可能反而会导致错误结果的解读。相比同规模的大型语言模型（LLMs），VLMs在遵循指令和自我反思方面的能力较弱，这严重限制了其在协作流程中的表现。本研究中，我们提出了MedOrch——一个基于中介引导的多智能体协作框架，专为医疗多模态决策设计。MedOrch采用基于LLM的中介智能体，让多个基于VLM的专家智能体能够交换并反思各自的输出，从而实现高效协作。我们选择多个开源的通用和领域特定VLMs，而非昂贵的GPT系列模型，充分展现了异构模型的优势。实验表明，不同VLMs智能体的协作能够超越单一智能体的能力上限。我们在五个医疗视觉问答基准测试中验证了这一方法，无需额外训练即可实现卓越的协作性能。我们的研究结果凸显了中介引导的多智能体协作在推动医疗多模态智能发展中的重要价值。我们的代码将公开发布。

> Complex medical decision-making involves cooperative workflows operated by different clinicians. Designing AI multi-agent systems can expedite and augment human-level clinical decision-making. Existing multi-agent researches primarily focus on language-only tasks, yet their extension to multimodal scenarios remains challenging. A blind combination of diverse vision-language models (VLMs) can amplify an erroneous outcome interpretation. VLMs in general are less capable in instruction following and importantly self-reflection, compared to large language models (LLMs) of comparable sizes. This disparity largely constrains VLMs' ability in cooperative workflows. In this study, we propose MedOrch, a mediator-guided multi-agent collaboration framework for medical multimodal decision-making. MedOrch employs an LLM-based mediator agent that enables multiple VLM-based expert agents to exchange and reflect on their outputs towards collaboration. We utilize multiple open-source general-purpose and domain-specific VLMs instead of costly GPT-series models, revealing the strength of heterogeneous models. We show that the collaboration within distinct VLM-based agents can surpass the capabilities of any individual agent. We validate our approach on five medical vision question answering benchmarks, demonstrating superior collaboration performance without model training. Our findings underscore the value of mediator-guided multi-agent collaboration in advancing medical multimodal intelligence. Our code will be made publicly available.

[Arxiv](https://arxiv.org/abs/2508.05996)