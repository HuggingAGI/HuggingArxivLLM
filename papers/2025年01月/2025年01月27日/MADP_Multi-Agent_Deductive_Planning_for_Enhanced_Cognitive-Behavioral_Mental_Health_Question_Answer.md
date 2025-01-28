# MADP: 多智能体演绎规划助力认知行为心理健康问答

发布时间：2025年01月27日

`Agent

理由：这篇论文提出了一个多代理演绎规划（MADP）框架，用于指导大型语言模型（LLMs）在心理健康问答任务中更深入地理解求助者背景并提供个性化帮助。MADP框架涉及多个代理（agents）之间的互动，这些代理基于认知行为疗法（CBT）的心理元素进行协作。因此，这篇论文主要关注的是多代理系统的设计和应用，属于Agent分类。` `心理健康` `对话系统`

> MADP: Multi-Agent Deductive Planning for Enhanced Cognitive-Behavioral Mental Health Question Answer

# 摘要

> 心理健康问答（MHQA）任务要求求助者和支持者在一轮对话中完成支持过程。由于求助者帖子内容丰富，支持者需深入理解并提供逻辑清晰、全面且结构化的回应。以往MHQA研究多聚焦于基于认知行为疗法（CBT）认知元素的单代理方法，却忽略了情感与认知等CBT元素间的互动，导致模型难以全面理解求助者的痛苦。为此，我们提出了多代理演绎规划（MADP）框架，基于CBT各心理元素的相互作用，指导大型语言模型（LLMs）更深入地理解求助者背景，提供个性化帮助。我们还基于MADP框架构建了新数据集，用于微调LLMs，得到专门模型MADP-LLM。通过广泛实验，包括与多个LLMs的对比、人类评估和自动评估，我们验证了MADP框架和MADP-LLM的有效性。

> The Mental Health Question Answer (MHQA) task requires the seeker and supporter to complete the support process in one-turn dialogue. Given the richness of help-seeker posts, supporters must thoroughly understand the content and provide logical, comprehensive, and well-structured responses. Previous works in MHQA mostly focus on single-agent approaches based on the cognitive element of Cognitive Behavioral Therapy (CBT), but they overlook the interactions among various CBT elements, such as emotion and cognition. This limitation hinders the models' ability to thoroughly understand the distress of help-seekers. To address this, we propose a framework named Multi-Agent Deductive Planning (MADP), which is based on the interactions between the various psychological elements of CBT. This method guides Large Language Models (LLMs) to achieve a deeper understanding of the seeker's context and provide more personalized assistance based on individual circumstances. Furthermore, we construct a new dataset based on the MADP framework and use it to fine-tune LLMs, resulting in a specialized model named MADP-LLM. We conduct extensive experiments, including comparisons with multiple LLMs, human evaluations, and automatic evaluations, to validate the effectiveness of the MADP framework and MADP-LLM.

[Arxiv](https://arxiv.org/abs/2501.15826)