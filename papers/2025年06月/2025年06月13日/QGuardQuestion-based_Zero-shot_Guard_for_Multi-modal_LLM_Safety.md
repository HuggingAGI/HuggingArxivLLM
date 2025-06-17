# QGuard：基于问题的零样本防护，保障多模态大语言模型的安全性

发布时间：2025年06月13日

`LLM应用

理由：这篇论文专注于大型语言模型（LLMs）的安全性问题，特别是如何防御有害提示和越狱提示。它提出了一种名为QGuard的方法，通过问题提示来拦截这些攻击，并且在实验中验证了其有效性。这属于LLM的实际应用，因为它展示了如何在实际场景中保护LLMs免受攻击，而不是纯粹的理论探讨或模型改进。` `人工智能`

> QGuard:Question-based Zero-shot Guard for Multi-modal LLM Safety

# 摘要

> 大型语言模型（LLMs）的最新进展对通用领域到专业领域产生了深远影响。然而，这些进展也显著增加了恶意用户利用有害提示和越狱提示进行攻击的可能性。尽管已有诸多努力防范有害提示和越狱提示，但保护LLMs免受此类攻击仍是关键且具挑战性的任务。本文提出QGuard，这是一种简单而有效的安全防护方法，通过问题提示以零样本方式拦截有害提示。我们的方法不仅能防御基于文本的有害提示，还可抵御多模态有害提示攻击。此外，通过多样化和修改保护问题，我们的方法在无需微调的情况下，仍能有效抵御最新有害提示。实验结果表明，我们的模型在仅文本和多模态有害数据集上均表现出色。同时，通过对问题提示的分析，我们实现了对用户输入的白盒分析。我们相信，QGuard为现实世界中LLM服务在缓解有害提示相关安全风险方面提供了重要见解。

> The recent advancements in Large Language Models(LLMs) have had a significant impact on a wide range of fields, from general domains to specialized areas. However, these advancements have also significantly increased the potential for malicious users to exploit harmful and jailbreak prompts for malicious attacks. Although there have been many efforts to prevent harmful prompts and jailbreak prompts, protecting LLMs from such malicious attacks remains an important and challenging task. In this paper, we propose QGuard, a simple yet effective safety guard method, that utilizes question prompting to block harmful prompts in a zero-shot manner. Our method can defend LLMs not only from text-based harmful prompts but also from multi-modal harmful prompt attacks. Moreover, by diversifying and modifying guard questions, our approach remains robust against the latest harmful prompts without fine-tuning. Experimental results show that our model performs competitively on both text-only and multi-modal harmful datasets. Additionally, by providing an analysis of question prompting, we enable a white-box analysis of user inputs. We believe our method provides valuable insights for real-world LLM services in mitigating security risks associated with harmful prompts.

[Arxiv](https://arxiv.org/abs/2506.12299)