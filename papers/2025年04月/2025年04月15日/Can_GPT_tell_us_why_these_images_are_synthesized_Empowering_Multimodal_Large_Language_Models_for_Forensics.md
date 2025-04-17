# GPT能否解释这些图像的合成原因？多模态大型语言模型在取证中的应用

发布时间：2025年04月15日

`LLM应用

理由：这篇论文探讨了多模态大型语言模型（LLMs）在检测AI生成内容（AIGC）和图像篡改方面的实际应用。研究提出了一种基于语义篡改线索的新框架，并通过提示工程和少量样本学习技术，成功应用LLMs进行伪造检测，展示了其在现实任务中的有效性。因此，这篇论文属于LLM应用类别。` `计算机视觉`

> Can GPT tell us why these images are synthesized? Empowering Multimodal Large Language Models for Forensics

# 摘要

> 生成式AI的迅猛发展不仅推动了内容创作，也让图像篡改变得越发容易和难以察觉。虽然多模态大型语言模型（LLMs）蕴含丰富知识，但它们并非天生具备对抗AI生成内容（AIGC）的能力，更难以精准识别局部伪造细节。本研究聚焦于多模态LLMs在伪造检测领域的应用，提出了一种基于语义篡改线索的全新框架，该框架能够评估图像真实性、定位篡改区域、提供证据并追踪生成方法。通过精心设计的提示工程和少量样本学习技术，我们成功释放了LLMs在伪造分析中的潜力。实验结果表明，GPT4V在Autosplice和LaMa上的准确率分别达到92.1%和86.3%，与当前最优的AIGC检测方法不相上下。最后，我们深入探讨了多模态LLMs在该领域的局限性，并提出了改进建议。

> The rapid development of generative AI facilitates content creation and makes image manipulation easier and more difficult to detect. While multimodal Large Language Models (LLMs) have encoded rich world knowledge, they are not inherently tailored for combating AI-generated Content (AIGC) and struggle to comprehend local forgery details. In this work, we investigate the application of multimodal LLMs in forgery detection. We propose a framework capable of evaluating image authenticity, localizing tampered regions, providing evidence, and tracing generation methods based on semantic tampering clues. Our method demonstrates that the potential of LLMs in forgery analysis can be effectively unlocked through meticulous prompt engineering and the application of few-shot learning techniques. We conduct qualitative and quantitative experiments and show that GPT4V can achieve an accuracy of 92.1% in Autosplice and 86.3% in LaMa, which is competitive with state-of-the-art AIGC detection methods. We further discuss the limitations of multimodal LLMs in such tasks and propose potential improvements.

[Arxiv](https://arxiv.org/abs/2504.11686)