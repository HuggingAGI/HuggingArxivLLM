# WebQuest: 网页序列多模态问答基准

发布时间：2024年09月24日

`Agent

理由：这篇论文主要讨论了构建能够自主帮助用户在各种人机界面上检索信息和完成任务的网络代理，并介绍了WebQuest数据集来评估这些代理的能力。虽然论文中提到了多模态LLMs（如GPT-4V、Gemini Flash等），但核心关注点是构建和评估能够自主完成任务的代理系统，因此更适合归类为Agent。` `人机交互` `信息检索`

> WebQuest: A Benchmark for Multimodal QA on Web Page Sequences

# 摘要

> 随着多模态LLMs的崛起，构建能够自主帮助用户在各种人机界面上检索信息和完成任务的网络代理变得更加可行。为此，我们需要创建涵盖广泛用例的挑战性基准，以反映现实世界的需求。本文介绍了WebQuest，一个多页面问答数据集，要求跨多个相关网页进行推理。与现有专注于多步骤网络导航和任务完成的UI基准不同，WebQuest评估了从多个网页中提取信息、多模态检索和信息组合的能力。数据集包含三类问题：单屏幕问答、多屏幕问答和基于导航轨迹的问答。我们评估了GPT-4V、Gemini Flash、Claude 3等专有多模态模型，以及InstructBLIP、PaliGemma等开源模型，发现单屏幕和多屏幕推理之间存在显著差距。最后，我们探索了Chain-of-Thought提示等推理时间技术，以提升模型在多屏幕推理上的表现。

> The rise of powerful multimodal LLMs has enhanced the viability of building web agents which can, with increasing levels of autonomy, assist users to retrieve information and complete tasks on various human-computer interfaces. It is hence necessary to build challenging benchmarks that span a wide-variety of use cases reflecting real-world usage. In this work, we present WebQuest, a multi-page question-answering dataset that requires reasoning across multiple related web pages. In contrast to existing UI benchmarks that focus on multi-step web navigation and task completion, our dataset evaluates information extraction, multimodal retrieval and composition of information from many web pages. WebQuest includes three question categories: single-screen QA, multi-screen QA, and QA based on navigation traces. We evaluate leading proprietary multimodal models like GPT-4V, Gemini Flash, Claude 3, and open source models like InstructBLIP, PaliGemma on our dataset, revealing a significant gap between single-screen and multi-screen reasoning. Finally, we investigate inference time techniques like Chain-of-Thought prompting to improve model capabilities on multi-screen reasoning.

[Arxiv](https://arxiv.org/abs/2409.13711)