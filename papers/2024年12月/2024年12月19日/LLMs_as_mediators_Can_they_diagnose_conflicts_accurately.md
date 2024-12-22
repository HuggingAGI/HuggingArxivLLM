# LLMs 充当调解者：它们能否精准诊断冲突？

发布时间：2024年12月19日

`LLM应用` `语言模型` `冲突调解`

> LLMs as mediators: Can they diagnose conflicts accurately?

# 摘要

> 先前的研究表明，要能够调解冲突，各方分歧的观察者必须能够可靠地分辨出分歧的根源，究竟是源于对事实的信念差异（因果关系），还是源于价值观的差异（道德）。在本文中，我们测试了 OpenAI 的大型语言模型 GPT 3.5 和 GPT 4 能否完成这项任务，以及哪种类型的分歧对于 LLM 的诊断尤其具有挑战性。我们用 OpenAI 的 GPT 3.5 和 GPT 4 重现了 Koçak 等人（2003）中的研究 1，该研究采用了小插图设计。我们发现，这两个 LLM 对因果和道德准则差异的语义理解与人类相似，并且能够可靠地区分。当被要求诊断对话中的分歧根源时，在道德不一致的情况下，与人类相比，两个 LLM 都倾向于高估因果分歧的程度，低估道德分歧的程度。对于使用依赖特定问题具体语言的近似量表的 GPT 4 而言，这种倾向尤为显著。在使用近似或远距量表时，GPT 3.5 的表现不如 GPT 4 或人类。本研究首次测试了利用 LLM 通过诊断因果和评估准则中分歧的根源来调解冲突的潜力。

> Prior research indicates that to be able to mediate conflict, observers of disagreements between parties must be able to reliably distinguish the sources of their disagreement as stemming from differences in beliefs about what is true (causality) vs. differences in what they value (morality). In this paper, we test if OpenAI's Large Language Models GPT 3.5 and GPT 4 can perform this task and whether one or other type of disagreement proves particularly challenging for LLM's to diagnose. We replicate study 1 in Koçak et al. (2003), which employes a vignette design, with OpenAI's GPT 3.5 and GPT 4. We find that both LLMs have similar semantic understanding of the distinction between causal and moral codes as humans and can reliably distinguish between them. When asked to diagnose the source of disagreement in a conversation, both LLMs, compared to humans, exhibit a tendency to overestimate the extent of causal disagreement and underestimate the extent of moral disagreement in the moral misalignment condition. This tendency is especially pronounced for GPT 4 when using a proximate scale that relies on concrete language specific to an issue. GPT 3.5 does not perform as well as GPT4 or humans when using either the proximate or the distal scale. The study provides a first test of the potential for using LLMs to mediate conflict by diagnosing the root of disagreements in causal and evaluative codes.

[Arxiv](https://arxiv.org/abs/2412.14675)