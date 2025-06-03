# 以角色之名思考：基于角色感知的推理推动角色扮演代理发展

发布时间：2025年06月02日

`Agent` `情感陪伴` `虚拟交互`

> Thinking in Character: Advancing Role-Playing Agents with Role-Aware Reasoning

# 摘要

> 大型语言模型（LLMs）的发展为角色扮演代理（RPA）在情感陪伴和虚拟交互等领域的应用开辟了新天地。然而，现有的RPA大多基于显式的对话数据构建，缺乏深层次的人类化内部思维过程，导致知识和风格表达流于表面。虽然大型推理模型（LRMs）可用于模拟角色思维，但其直接应用却面临两大挑战：注意力偏离（即RPA忘记自身角色）和风格漂移（即过于正式 rigid 的推理而非角色一致的推理）。为了解决这些挑战，本文提出了一种新颖的角色感知推理（RAR）方法，该方法包含两个重要阶段：角色身份激活（RIA）和推理风格优化（RSO）。RIA在推理过程中显式地引导模型使用角色档案，以抵消注意力偏离；然后，RSO通过LRM蒸馏将推理风格与角色和场景对齐，从而缓解风格漂移。大量实验表明，所提出的RAR通过有效解决注意力偏离和风格漂移问题，显著提升了RPA的性能。

> The advancement of Large Language Models (LLMs) has spurred significant interest in Role-Playing Agents (RPAs) for applications such as emotional companionship and virtual interaction. However, recent RPAs are often built on explicit dialogue data, lacking deep, human-like internal thought processes, resulting in superficial knowledge and style expression. While Large Reasoning Models (LRMs) can be employed to simulate character thought, their direct application is hindered by attention diversion (i.e., RPAs forget their role) and style drift (i.e., overly formal and rigid reasoning rather than character-consistent reasoning). To address these challenges, this paper introduces a novel Role-Aware Reasoning (RAR) method, which consists of two important stages: Role Identity Activation (RIA) and Reasoning Style Optimization (RSO). RIA explicitly guides the model with character profiles during reasoning to counteract attention diversion, and then RSO aligns reasoning style with the character and scene via LRM distillation to mitigate style drift. Extensive experiments demonstrate that the proposed RAR significantly enhances the performance of RPAs by effectively addressing attention diversion and style drift.

[Arxiv](https://arxiv.org/abs/2506.01748)