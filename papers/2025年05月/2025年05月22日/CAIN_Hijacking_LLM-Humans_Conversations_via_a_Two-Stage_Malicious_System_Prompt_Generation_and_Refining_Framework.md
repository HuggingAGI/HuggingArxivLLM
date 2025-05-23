# # **CAIN** 通过双阶段恶意系统提示生成和优化框架实现对LLM与人类对话的劫持

发布时间：2025年05月22日

`LLM应用` `对抗攻击`

> CAIN: Hijacking LLM-Humans Conversations via a Two-Stage Malicious System Prompt Generation and Refining Framework

# 摘要

> 大型语言模型（LLMs）虽然推动了诸多应用的发展，但其安全性问题也日益凸显，尤其易受对抗攻击。本研究揭示了一种新型安全威胁：通过操控LLMs的系统提示，仅针对特定问题（如“我应该投票给哪位美国总统？”、“新冠疫苗安全吗？”）生成恶意回答，而在其他问题上表现正常。这种攻击手段危害极大，因为它允许恶意行为者通过网络传播看似无害却有害的系统提示，从而实现大规模信息操控。为验证这一威胁，我们开发了CAIN算法，该算法无需访问LLM参数，即可在黑盒环境下自动整理出针对特定目标问题的有害系统提示。实验结果表明，CAIN在开源和商用LLMs上均表现出显著的对抗效果。在非定向攻击中，CAIN使目标问题的F1值下降高达40%，同时保持良性输入的高精度。在定向攻击中，CAIN在特定有害回答上实现了超过70%的F1得分，对良性问题影响甚微。我们的研究结果强调了提升LLMs稳健性措施的紧迫性，以保障其在实际应用中的完整性和安全性。所有源代码将公开发布。

> Large language models (LLMs) have advanced many applications, but are also known to be vulnerable to adversarial attacks. In this work, we introduce a novel security threat: hijacking AI-human conversations by manipulating LLMs' system prompts to produce malicious answers only to specific targeted questions (e.g., "Who should I vote for US President?", "Are Covid vaccines safe?"), while behaving benignly on others. This attack is detrimental as it can enable malicious actors to exercise large-scale information manipulation by spreading harmful but benign-looking system prompts online. To demonstrate such an attack, we develop CAIN, an algorithm that can automatically curate such harmful system prompts for a specific target question in a black-box setting or without the need to access the LLM's parameters. Evaluated on both open-source and commercial LLMs, CAIN demonstrates significant adversarial impact. In untargeted attacks or forcing LLMs to output incorrect answers, CAIN achieves up to 40% F1 degradation on targeted questions while preserving high accuracy on benign inputs. For targeted attacks or forcing LLMs to output specific harmful answers, CAIN achieves over 70% F1 scores on these targeted responses with minimal impact on benign questions. Our results highlight the critical need for enhanced robustness measures to safeguard the integrity and safety of LLMs in real-world applications. All source code will be publicly available.

[Arxiv](https://arxiv.org/abs/2505.16888)