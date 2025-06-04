# BitBypass：一种绕过对齐大型语言模型的全新方向，采用比特流伪装技术。

发布时间：2025年06月03日

`LLM应用` `网络安全` `人工智能`

> BitBypass: A New Direction in Jailbreaking Aligned Large Language Models with Bitstream Camouflage

# 摘要

> 大型语言模型 (LLMs) 固有的生成有害和不安全内容的风险，凸显了对其进行安全对齐的必要性。为此，研究者们开发了多种技术，包括监督微调、基于人类反馈的强化学习和红队方法，以确保大型语言模型的安全对齐。然而，这些经过安全对齐的大型语言模型仍然面临着来自对抗攻击的威胁，这些攻击利用了安全对齐过程中尚未被探索和潜在的漏洞。本文提出了一种名为 BitBypass 的新型黑盒越狱攻击方法，该方法通过连字符分隔的比特流伪装来实现对齐大型语言模型的越狱。这种方法开创了一种全新的越狱思路，它不再依赖于提示工程或对抗性操作，而是利用数据作为连续比特的基本信息表示。我们从对抗性视角对五种最先进的大型语言模型——GPT-4o、Gemini 1.5、Claude 3.5、Llama 3.1 和 Mixtral——进行了评估，结果表明 BitBypass 在绕过其安全对齐并诱导生成有害和不安全内容方面具有显著能力。此外，我们发现 BitBypass 在隐蔽性和攻击成功率方面优于多种最先进的越狱攻击方法。总体而言，这些结果凸显了 BitBypass 在越狱这些最先进的大型语言模型方面的卓越效果与效率。

> The inherent risk of generating harmful and unsafe content by Large Language Models (LLMs), has highlighted the need for their safety alignment. Various techniques like supervised fine-tuning, reinforcement learning from human feedback, and red-teaming were developed for ensuring the safety alignment of LLMs. However, the robustness of these aligned LLMs is always challenged by adversarial attacks that exploit unexplored and underlying vulnerabilities of the safety alignment. In this paper, we develop a novel black-box jailbreak attack, called BitBypass, that leverages hyphen-separated bitstream camouflage for jailbreaking aligned LLMs. This represents a new direction in jailbreaking by exploiting fundamental information representation of data as continuous bits, rather than leveraging prompt engineering or adversarial manipulations. Our evaluation of five state-of-the-art LLMs, namely GPT-4o, Gemini 1.5, Claude 3.5, Llama 3.1, and Mixtral, in adversarial perspective, revealed the capabilities of BitBypass in bypassing their safety alignment and tricking them into generating harmful and unsafe content. Further, we observed that BitBypass outperforms several state-of-the-art jailbreak attacks in terms of stealthiness and attack success. Overall, these results highlights the effectiveness and efficiency of BitBypass in jailbreaking these state-of-the-art LLMs.

[Arxiv](https://arxiv.org/abs/2506.02479)