# 隐藏检测：通过监测隐藏状态识别大型视觉语言模型的越狱攻击
# 摘要
近年来，大型视觉语言模型（LVLMs）在图像描述、视觉问答和文本到图像生成等任务中取得了显著的成功。然而，这些成功也使其成为恶意攻击的主要目标对象，尤其是针对越狱攻击的防范。这些攻击试图绕过内容安全过滤器，生成有害或不当内容。

发布时间：2025年02月20日

`LLM理论` `人工智能安全` `多模态`

> HiddenDetect: Detecting Jailbreak Attacks against Large Vision-Language Models via Monitoring Hidden States

# 摘要

> 与仅处理语言的模型相比，大型视觉语言模型（LVLMs）在整合额外模态后，更容易受到安全风险（如越狱攻击）的影响。现有研究主要关注事后对齐技术，而LVLMs内部的安全机制仍未得到充分探索。本研究旨在探讨LVLMs在推理过程中是否内在编码了与安全相关的信号。我们的发现表明，当处理不安全提示时，LVLMs的内部激活模式具有显著差异，这一特性可用于检测和缓解对抗性输入，而无需进行大量微调。基于此发现，我们提出了HiddenDetect——一个无需调优的新型框架，通过利用模型内部激活来提升安全性。实验结果表明，HiddenDetect在检测针对LVLMs的越狱攻击方面超越了现有最优方法。通过利用内在的安全感知模式，我们的方法为增强LVLMs在多模态威胁下的鲁棒性提供了一个高效且可扩展的解决方案。我们的代码将在https://github.com/leigest519/HiddenDetect公开发布。

> The integration of additional modalities increases the susceptibility of large vision-language models (LVLMs) to safety risks, such as jailbreak attacks, compared to their language-only counterparts. While existing research primarily focuses on post-hoc alignment techniques, the underlying safety mechanisms within LVLMs remain largely unexplored. In this work , we investigate whether LVLMs inherently encode safety-relevant signals within their internal activations during inference. Our findings reveal that LVLMs exhibit distinct activation patterns when processing unsafe prompts, which can be leveraged to detect and mitigate adversarial inputs without requiring extensive fine-tuning. Building on this insight, we introduce HiddenDetect, a novel tuning-free framework that harnesses internal model activations to enhance safety. Experimental results show that {HiddenDetect} surpasses state-of-the-art methods in detecting jailbreak attacks against LVLMs. By utilizing intrinsic safety-aware patterns, our method provides an efficient and scalable solution for strengthening LVLM robustness against multimodal threats. Our code will be released publicly at https://github.com/leigest519/HiddenDetect.

[Arxiv](https://arxiv.org/abs/2502.14744)