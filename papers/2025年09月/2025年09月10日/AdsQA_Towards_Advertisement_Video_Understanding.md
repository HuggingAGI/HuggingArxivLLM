# AdsQA：迈向广告视频理解

发布时间：2025年09月10日

`LLM应用` `媒体与娱乐`

> AdsQA: Towards Advertisement Video Understanding

# 摘要

> 大型语言模型（LLMs）已朝着通用人工智能（AGI）迈出重要一步。与此同时，数学、编程等越来越多的特定领域问题，通过促使这些通用模型学习更深层次的专业知识，推动其持续进化。因此，当下正是进一步拓展知识型LLM专业应用多样性的时机，不过收集包含意外性、信息性任务的高质量数据仍颇具挑战。本文提出，将广告（ad）视频作为极具挑战性的测试场景，来探究LLM感知常见视觉领域中客观物理内容之外信息的能力。我们的出发点是充分利用广告视频线索丰富、信息密集的特质，比如其营销逻辑、说服策略及受众互动方式。我们的贡献主要有三：（1）据我们所知，这是首次通过设计精妙的任务，利用广告视频对LLM进行评估。我们构建了AdsQA——一个极具挑战性的广告视频问答基准，它源自1544个广告视频（含10962个片段，总时长22.7小时），涵盖5项挑战性任务。（2）我们提出ReAd-R模型——一种Deepseek-R1风格的强化学习（RL）模型，它能对问题进行反思，并通过奖励驱动的优化过程生成答案。（3）我们在AdsQA上对14个顶级LLM进行了基准测试，结果显示，我们的	exttt{ReAd-R}模型性能达到最先进水平，以显著优势超越了具备长链推理能力的强劲对手。

> Large language models (LLMs) have taken a great step towards AGI. Meanwhile, an increasing number of domain-specific problems such as math and programming boost these general-purpose models to continuously evolve via learning deeper expertise. Now is thus the time further to extend the diversity of specialized applications for knowledgeable LLMs, though collecting high quality data with unexpected and informative tasks is challenging. In this paper, we propose to use advertisement (ad) videos as a challenging test-bed to probe the ability of LLMs in perceiving beyond the objective physical content of common visual domain. Our motivation is to take full advantage of the clue-rich and information-dense ad videos' traits, e.g., marketing logic, persuasive strategies, and audience engagement. Our contribution is three-fold: (1) To our knowledge, this is the first attempt to use ad videos with well-designed tasks to evaluate LLMs. We contribute AdsQA, a challenging ad Video QA benchmark derived from 1,544 ad videos with 10,962 clips, totaling 22.7 hours, providing 5 challenging tasks. (2) We propose ReAd-R, a Deepseek-R1 styled RL model that reflects on questions, and generates answers via reward-driven optimization. (3) We benchmark 14 top-tier LLMs on AdsQA, and our \texttt{ReAd-R}~achieves the state-of-the-art outperforming strong competitors equipped with long-chain reasoning capabilities by a clear margin.

[Arxiv](https://arxiv.org/abs/2509.08621)