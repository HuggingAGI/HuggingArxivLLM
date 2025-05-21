# 揭秘大型语言模型的越狱攻击：意图隐藏与转移策略

发布时间：2025年05月20日

`LLM应用`

> Exploring Jailbreak Attacks on LLMs through Intent Concealment and Diversion

# 摘要

> 尽管大型语言模型（LLMs）取得了显著的进步，但其安全性仍然是一个紧迫的问题。一个主要的威胁是越狱攻击，其中对抗性提示绕过模型的安全措施，生成有害或令人反感的内容。研究人员通过研究越狱攻击，深入了解大型语言模型的安全性和鲁棒性。然而，现有的越狱攻击方法面临两个主要挑战：（1）迭代查询数量过多，（2）跨模型泛化能力差。此外，最近的越狱攻击评估数据集主要集中在问答场景上，缺乏对需要准确再生有害内容的文本生成任务的关注。

为了解决这些挑战，我们提出两个贡献：（1）ICE，一种新颖的黑盒越狱方法，采用意图隐藏和多样化策略，有效规避安全约束。ICE通过单次查询实现高攻击成功率（ASR），显著提高效率和跨模型的可转移性。 (2) BiSceneEval，一个全面的数据集，旨在评估LLMs在问答和文本生成任务中的鲁棒性。实验结果表明，ICE在现有越狱技术中表现优异，揭示了当前防御机制中的关键漏洞。我们的研究发现强调了混合安全策略的必要性，该策略将预定义的安全机制与实时语义分解相结合，以增强大型语言模型的安全性。

> Although large language models (LLMs) have achieved remarkable advancements, their security remains a pressing concern. One major threat is jailbreak attacks, where adversarial prompts bypass model safeguards to generate harmful or objectionable content. Researchers study jailbreak attacks to understand security and robustness of LLMs. However, existing jailbreak attack methods face two main challenges: (1) an excessive number of iterative queries, and (2) poor generalization across models. In addition, recent jailbreak evaluation datasets focus primarily on question-answering scenarios, lacking attention to text generation tasks that require accurate regeneration of toxic content. To tackle these challenges, we propose two contributions: (1) ICE, a novel black-box jailbreak method that employs Intent Concealment and divErsion to effectively circumvent security constraints. ICE achieves high attack success rates (ASR) with a single query, significantly improving efficiency and transferability across different models. (2) BiSceneEval, a comprehensive dataset designed for assessing LLM robustness in question-answering and text-generation tasks. Experimental results demonstrate that ICE outperforms existing jailbreak techniques, revealing critical vulnerabilities in current defense mechanisms. Our findings underscore the necessity of a hybrid security strategy that integrates predefined security mechanisms with real-time semantic decomposition to enhance the security of LLMs.

[Arxiv](https://arxiv.org/abs/2505.14316)