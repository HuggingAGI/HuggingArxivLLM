# FDLLM: 多语言、多领域黑箱环境下LLMs的文本指纹检测方法

发布时间：2025年01月27日

`LLM应用

理由：这篇论文主要讨论了在使用大型语言模型（LLMs）时如何识别和检测不同模型生成的文本，以防止恶意模型的攻击。论文提出了一个基于Qwen2.5-7B并使用LoRA微调的LLMGT指纹检测模型（FDLLM），并构建了一个包含多种语言和领域的数据集（FD-Datasets）。这些工作都是为了解决LLM在实际应用中的安全问题，因此属于LLM应用的范畴。` `信息安全`

> FDLLM: A Text Fingerprint Detection Method for LLMs in Multi-Language, Multi-Domain Black-Box Environments

# 摘要

> # 摘要
在使用大型语言模型（LLMs）集成平台时，若不清楚调用的是哪个LLM，可能会带来安全风险。攻击者可能利用这种黑盒环境，部署恶意模型并在用户代码中植入病毒。因此，用户亟需明确识别所交互的LLM，以免成为恶意模型的受害者。然而，现有研究多集中于人类与机器生成文本的混合分类，对仅由不同模型生成的文本分类关注较少。当前研究还面临两大瓶颈：LLM生成文本（LLMGT）数据集质量不佳，以及可检测的LLM覆盖范围有限，导致黑盒场景下对各类LLMGT的检测效果不佳。为此，我们提出了首个基于Qwen2.5-7B并使用LoRA微调的LLMGT指纹检测模型——	extbf{FDLLM}。FDLLM能更高效地处理跨语言和多领域的检测任务。此外，我们还构建了一个名为	extbf{FD-Datasets}的数据集，包含90,000个样本，涵盖多种语言和领域，覆盖20种不同的LLM。实验结果显示，FDLLM的宏观F1得分比最佳基线方法LM-D高出16.7\%。

> Using large language models (LLMs) integration platforms without transparency about which LLM is being invoked can lead to potential security risks. Specifically, attackers may exploit this black-box scenario to deploy malicious models and embed viruses in the code provided to users. In this context, it is increasingly urgent for users to clearly identify the LLM they are interacting with, in order to avoid unknowingly becoming victims of malicious models. However, existing studies primarily focus on mixed classification of human and machine-generated text, with limited attention to classifying texts generated solely by different models. Current research also faces dual bottlenecks: poor quality of LLM-generated text (LLMGT) datasets and limited coverage of detectable LLMs, resulting in poor detection performance for various LLMGT in black-box scenarios. We propose the first LLMGT fingerprint detection model, \textbf{FDLLM}, based on Qwen2.5-7B and fine-tuned using LoRA to address these challenges. FDLLM can more efficiently handle detection tasks across multilingual and multi-domain scenarios. Furthermore, we constructed a dataset named \textbf{FD-Datasets}, consisting of 90,000 samples that span multiple languages and domains, covering 20 different LLMs. Experimental results demonstrate that FDLLM achieves a macro F1 score 16.7\% higher than the best baseline method, LM-D.

[Arxiv](https://arxiv.org/abs/2501.16029)