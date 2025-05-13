# 我知道你所说的内容：揭露本地大型语言模型推理中的硬件缓存侧信道攻击。

发布时间：2025年05月10日

`LLM应用

摘要讨论了本地部署的大语言模型（LLMs）在隐私保护任务中的应用及其潜在的安全漏洞。具体来说，研究揭示了本地LLMs推理中存在的侧信道漏洞，这些漏洞可能导致用户输入和输出文本的泄露，从而威胁用户隐私。论文设计了一种新型的窃听攻击框架，并对多个本地LLM部署进行了攻击评估，展示了攻击的可行性及其对用户隐私的潜在威胁。这些内容属于LLM的实际应用及其安全性研究，因此归类为LLM应用。` `隐私保护`

> I Know What You Said: Unveiling Hardware Cache Side-Channels in Local Large Language Model Inference

# 摘要

> # 摘要
本地部署的大语言模型（LLMs）因其在隐私保护任务中的应用而备受关注，其中Meta、Google和Intel等公司在其开发中发挥了重要作用。然而，本地LLMs在硬件缓存侧信道方面的安全性尚未得到充分研究。本文揭示了本地LLM推理中存在新颖的侧信道漏洞：token值和token位置泄露，这些漏洞可能导致受害者输入和输出文本的泄露，从而危及用户隐私。

具体而言，攻击者能够通过解析token嵌入操作的缓存访问模式推断出token值，并通过自回归解码阶段的时序信息推断出token位置。为了展示这些泄露的风险，我们设计了一种新型的窃听攻击框架，针对开源和专有LLM推理系统。该攻击框架无需直接与受害者的LLM交互，且无需特权即可执行。

我们对一系列实用的本地LLM部署（如Llama、Falcon和Gemma）进行了攻击评估，结果显示我们的攻击取得了显著效果。恢复的输出和输入文本与真实值的平均编辑距离分别为5.2%和17.3%。此外，重建的文本在输入和输出方面分别达到了98.7%和98.0%的平均余弦相似度得分。

> Large Language Models (LLMs) that can be deployed locally have recently gained popularity for privacy-sensitive tasks, with companies such as Meta, Google, and Intel playing significant roles in their development. However, the security of local LLMs through the lens of hardware cache side-channels remains unexplored. In this paper, we unveil novel side-channel vulnerabilities in local LLM inference: token value and token position leakage, which can expose both the victim's input and output text, thereby compromising user privacy. Specifically, we found that adversaries can infer the token values from the cache access patterns of the token embedding operation, and deduce the token positions from the timing of autoregressive decoding phases. To demonstrate the potential of these leaks, we design a novel eavesdropping attack framework targeting both open-source and proprietary LLM inference systems. The attack framework does not directly interact with the victim's LLM and can be executed without privilege.
  We evaluate the attack on a range of practical local LLM deployments (e.g., Llama, Falcon, and Gemma), and the results show that our attack achieves promising accuracy. The restored output and input text have an average edit distance of 5.2% and 17.3% to the ground truth, respectively. Furthermore, the reconstructed texts achieve average cosine similarity scores of 98.7% (input) and 98.0% (output).

[Arxiv](https://arxiv.org/abs/2505.06738)