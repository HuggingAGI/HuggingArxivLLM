# 多语言与多口音的音频LLM越狱

发布时间：2025年04月01日

`LLM应用

论文摘要讨论了大型音频语言模型（LALMs）在安全方面的应用，特别是对抗性音频越狱攻击。研究重点在于多语言和多口音环境下的攻击方法及其对模型的影响，属于LLM的应用层面，因此归类为LLM应用。` `音频安全` `多模态安全`

> Multilingual and Multi-Accent Jailbreaking of Audio LLMs

# 摘要

> 大型音频语言模型（LALMs）在音频理解领域取得了显著进展，但同时也带来了严重的安全风险，尤其是通过音频越狱攻击。尽管先前研究主要集中在英语为中心的攻击上，我们发现了一个更为严重的漏洞：多语言和多口音的对抗性音频越狱攻击，其中语言和声学的变化极大地提高了攻击成功的几率。本文中，我们介绍了Multi-AudioJail，这是首个系统性利用这些漏洞的框架，通过（1）一个包含对抗性扰动的多语言/多口音音频越狱提示的新型数据集，以及（2）一个分层评估管道，揭示了声学扰动（如混响、回声和耳语效果）如何与跨语言语音学相互作用，导致越狱成功率（JSR）激增高达+57.25个百分点（例如，肯尼亚口音的混响攻击对MERaLiON）。至关重要的是，我们的研究进一步揭示，多模态LLMs比单模态系统更易受攻击：攻击者只需利用最薄弱的环节（例如，非英语音频输入）就能破坏整个模型，这一点我们通过多语言音频攻击的成功率比纯文本攻击高出3.1倍的实证结果加以证明。我们计划发布我们的数据集，以推动跨模态防御研究，呼吁社区在LALMs的发展中解决这一不断扩大的多模态攻击面。

> Large Audio Language Models (LALMs) have significantly advanced audio understanding but introduce critical security risks, particularly through audio jailbreaks. While prior work has focused on English-centric attacks, we expose a far more severe vulnerability: adversarial multilingual and multi-accent audio jailbreaks, where linguistic and acoustic variations dramatically amplify attack success. In this paper, we introduce Multi-AudioJail, the first systematic framework to exploit these vulnerabilities through (1) a novel dataset of adversarially perturbed multilingual/multi-accent audio jailbreaking prompts, and (2) a hierarchical evaluation pipeline revealing that how acoustic perturbations (e.g., reverberation, echo, and whisper effects) interacts with cross-lingual phonetics to cause jailbreak success rates (JSRs) to surge by up to +57.25 percentage points (e.g., reverberated Kenyan-accented attack on MERaLiON). Crucially, our work further reveals that multimodal LLMs are inherently more vulnerable than unimodal systems: attackers need only exploit the weakest link (e.g., non-English audio inputs) to compromise the entire model, which we empirically show by multilingual audio-only attacks achieving 3.1x higher success rates than text-only attacks. We plan to release our dataset to spur research into cross-modal defenses, urging the community to address this expanding attack surface in multimodality as LALMs evolve.

[Arxiv](https://arxiv.org/abs/2504.01094)