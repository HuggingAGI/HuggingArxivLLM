# 基于奖励驱动的自动化Webshell恶意代码生成器，专为红队设计

发布时间：2025年05月30日

`LLM应用

理由：这篇论文主要讨论了如何利用大型语言模型（LLM）来生成恶意代码，并提出了一个自动化Webshell恶意代码生成器。虽然涉及安全问题，但核心是LLM的应用，因此归类为LLM应用。` `网络安全` `恶意代码防御`

> A Reward-driven Automated Webshell Malicious-code Generator for Red-teaming

# 摘要

> 频繁的网络攻击使得WebShell的利用与防御成为了网络安全领域的核心研究课题。然而，目前仍严重缺乏公开可用、按混淆方法分类的恶意代码数据集。现有基于提示工程的恶意代码生成方法，往往存在载荷多样性不足和冗余度过高的问题。为解决这些局限，我们提出了	extbf{RAWG}（	extbf{R}eward-driven 	extbf{A}utomated 	extbf{W}ebshell Malicious-code 	extbf{G}enerator），一个专为红队应用设计的奖励驱动型自动化Webshell恶意代码生成器。我们的方法首先将常见数据集中的Webshell样本分类为七种不同的混淆类型。接着，我们利用大型语言模型（LLM）从每个样本中提取并规范化关键令牌，构建了一个标准化的高质量语料库。基于此数据集，我们对开源大型模型进行了有监督微调（SFT），以实现生成多样化且高度混淆的Webshell恶意载荷。为了进一步提升生成质量，我们引入了近端策略优化（PPO），在强化学习过程中将恶意代码样本视为“选择”数据，良性代码视为“拒绝”数据。大量实验结果表明，与现有最先进的方法相比，RAWG在载荷多样性和逃逸有效性方面均取得了显著的性能提升。

> Frequent cyber-attacks have elevated WebShell exploitation and defense to a critical research focus within network security. However, there remains a significant shortage of publicly available, well-categorized malicious-code datasets organized by obfuscation method. Existing malicious-code generation methods, which primarily rely on prompt engineering, often suffer from limited diversity and high redundancy in the payloads they produce. To address these limitations, we propose \textbf{RAWG}, a \textbf{R}eward-driven \textbf{A}utomated \textbf{W}ebshell Malicious-code \textbf{G}enerator designed for red-teaming applications. Our approach begins by categorizing webshell samples from common datasets into seven distinct types of obfuscation. We then employ a large language model (LLM) to extract and normalize key tokens from each sample, creating a standardized, high-quality corpus. Using this curated dataset, we perform supervised fine-tuning (SFT) on an open-source large model to enable the generation of diverse, highly obfuscated webshell malicious payloads. To further enhance generation quality, we apply Proximal Policy Optimization (PPO), treating malicious-code samples as "chosen" data and benign code as "rejected" data during reinforcement learning. Extensive experiments demonstrate that RAWG significantly outperforms current state-of-the-art methods in both payload diversity and escape effectiveness.

[Arxiv](https://arxiv.org/abs/2505.24252)