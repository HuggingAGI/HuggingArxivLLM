# # 装傻：利用分布外策略逃逸 LLM 和多模态 LLM

发布时间：2025年03月25日

`LLM应用` `人工智能安全` `对抗攻击`

> Playing the Fool: Jailbreaking LLMs and Multimodal LLMs with Out-of-Distribution Strategy

# 摘要

> 尽管大型语言模型 (LLMs) 和多模态大型语言模型 (MLLMs) 在语言和视觉任务中展现了卓越的泛化能力，但它们在面对有害或敏感输入时，却容易受到越狱攻击，产生违背安全、伦理和公平标准的文本输出。随着通过人类反馈偏好微调实现的安全对齐技术的最新进展，LLMs 和 MLLMs 已经配备了安全护栏，能够在面对有害输入时生成安全、合乎伦理且公平的响应。然而，尽管安全对齐技术至关重要，但对其漏洞的研究仍然鲜为人知。本文研究了安全对齐技术未被探索的漏洞，评估其在面对可能超出对齐数据分布范围的“OOD 化”有害输入时，是否能持续提供安全保证。我们的核心观察是，将原始有害输入进行 OOD 化处理会大幅增加模型识别输入恶意意图的不确定性，从而提高了被越狱的可能性。利用这一漏洞，我们提出了 JOOD，一种通过 OOD 化输入超越安全对齐的新越狱框架。我们探索了多种现成的视觉和文本变换技术，用于对有害输入进行 OOD 化处理。值得注意的是，即使是基于简单混合的技术（如图像混合）也被证明在增加模型不确定性方面非常有效，从而有助于绕过安全对齐机制。在各种越狱场景下的实验表明，JOOD 成功越狱了近期专有的 LLMs 和 MLLMs，如 GPT-4 和 o1，攻击成功率显著高于以往的攻击方法。代码可在 https://github.com/naver-ai/JOOD 获取。


> Despite the remarkable versatility of Large Language Models (LLMs) and Multimodal LLMs (MLLMs) to generalize across both language and vision tasks, LLMs and MLLMs have shown vulnerability to jailbreaking, generating textual outputs that undermine safety, ethical, and bias standards when exposed to harmful or sensitive inputs. With the recent advancement of safety alignment via preference-tuning from human feedback, LLMs and MLLMs have been equipped with safety guardrails to yield safe, ethical, and fair responses with regard to harmful inputs. However, despite the significance of safety alignment, research on the vulnerabilities remains largely underexplored. In this paper, we investigate the unexplored vulnerability of the safety alignment, examining its ability to consistently provide safety guarantees for out-of-distribution(OOD)-ifying harmful inputs that may fall outside the aligned data distribution. Our key observation is that OOD-ifying the vanilla harmful inputs highly increases the uncertainty of the model to discern the malicious intent within the input, leading to a higher chance of being jailbroken. Exploiting this vulnerability, we propose JOOD, a new Jailbreak framework via OOD-ifying inputs beyond the safety alignment. We explore various off-the-shelf visual and textual transformation techniques for OOD-ifying the harmful inputs. Notably, we observe that even simple mixing-based techniques such as image mixup prove highly effective in increasing the uncertainty of the model, thereby facilitating the bypass of the safety alignment. Experiments across diverse jailbreak scenarios demonstrate that JOOD effectively jailbreaks recent proprietary LLMs and MLLMs such as GPT-4 and o1 with high attack success rate, which previous attack approaches have consistently struggled to jailbreak. Code is available at https://github.com/naver-ai/JOOD.

[Arxiv](https://arxiv.org/abs/2503.20823)