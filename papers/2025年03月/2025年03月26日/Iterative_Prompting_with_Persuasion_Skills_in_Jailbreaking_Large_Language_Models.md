# 通过具备说服技巧的迭代提示实现大型语言模型的越狱

发布时间：2025年03月26日

`LLM应用` `人工智能` `伦理安全`

> Iterative Prompting with Persuasion Skills in Jailbreaking Large Language Models

# 摘要

> 大型语言模型（LLMs）的设计目标是使其输出与人类价值观保持一致。本研究提出了一种迭代提示技术，通过在多次迭代中系统性地优化每个提示，逐步提升其在越狱攻击中的有效性。该技术通过对GPT-3.5、GPT-4、LLaMa2、Vicuna和ChatGLM等主流LLMs的响应模式进行分析，使我们能够调整和优化提示内容，从而有效规避LLMs的伦理和安全限制。同时，我们结合劝说策略进一步提升提示的有效性，同时保持恶意意图的一致性。实验结果显示，随着攻击提示的不断优化，攻击成功率（ASR）显著提升，其中GPT4和ChatGLM的最高ASR达到90%，而LLaMa2的最低ASR为68%。与基线技术（PAIR和PAP）相比，我们的技术在ASR方面表现更优，并与GCG和ArtPrompt的表现相当。

> Large language models (LLMs) are designed to align with human values in their responses. This study exploits LLMs with an iterative prompting technique where each prompt is systematically modified and refined across multiple iterations to enhance its effectiveness in jailbreaking attacks progressively. This technique involves analyzing the response patterns of LLMs, including GPT-3.5, GPT-4, LLaMa2, Vicuna, and ChatGLM, allowing us to adjust and optimize prompts to evade the LLMs' ethical and security constraints. Persuasion strategies enhance prompt effectiveness while maintaining consistency with malicious intent. Our results show that the attack success rates (ASR) increase as the attacking prompts become more refined with the highest ASR of 90% for GPT4 and ChatGLM and the lowest ASR of 68% for LLaMa2. Our technique outperforms baseline techniques (PAIR and PAP) in ASR and shows comparable performance with GCG and ArtPrompt.

[Arxiv](https://arxiv.org/abs/2503.20320)